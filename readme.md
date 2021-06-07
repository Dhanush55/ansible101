# LINUX BASIC COMMANDS
FIle Commands
Listing files <h2> ```ls```</h2> <br />
Changing directory <h2> ```cd [path]```</h2> <br />
Changing directory to root <h2> ```cd /```</h2> <br />
Changing directory previous one <h2> ```cd ..```</h2> <br />
Used for listing files some of its options with details such as ugo names, permissions, size ... etc <h2> ``` ls -ltrah``` </h2> <br />
Present working directory <h2> ```pwd``` </h2> <br />
Creating a file <h2> ```touch``` </h2> <br />
Remove file <h2> ```rm``` </h2> <br />
Make directory <h2> ```mkdir``` </h2> <br />
Remove directory <h2> ```rmdir``` </h2> <br />
Remove directory recursively with files inside and without any permissions <h2> ```rm -rf``` </h2> <br />
Copy contents from one file to another <h2> ```cp``` </h2> <br />
Copy all files in the directory recursively <h2> ```cp -r``` </h2> <br />
Move contents from one file to another and used to rename file name as well <h2> ```mv``` </h2> <br />
To create a symbolic link or soft link of a file <h2>```ln -s [home/path] [file name] [link name]```</h2> <br />
Show the contents of file <h2> ```cat/more``` </h2> <br />
Display first/last 10 lines <h2> ```Head/Tail``` </h2> <br />
Append/replace a file <h2> ```>> or >``` </h2> <br />
Word count of a file which displays line, size and no of words <h2> ```wc``` </h2> <br />
To encrypt a file <h2> ```gpg -c [filename]``` </h2> <br />
To decrypt a file <h2> ```gpg [filename]``` </h2> <br />
<br />
Search for names & pattern inside files <h2> ```grep``` </h2> <br />
Search recursively with directory <h2> ```grep -r [keyword] [path]``` </h2> <br />
Locate a file or directory <h2> ```locate``` </h2> <br />
Find all or specific files of a format <h2> ```find [path] -name *.txt``` </h2> <br />
Find files with specific size <h2> ```find [path] -size [+100M]``` </h2> <br />
File permission
Assigning Read write Execute for a file <h2> ```chmod 777``` </h2>
<h2>Change permission values</h2>
<table style="width:80%">
  <tr>
    <th>Action</th>
    <th>Value</th> 
  </tr>
  <tr>
    <td>Read</td>
    <td>4</td>
  </tr>
    <tr>
    <td>Write</td>
    <td>2</td>
  </tr>
    <tr>
    <td>Execute</td>
    <td>1</td>
  </tr>
  </table>
Change Ownership of a file ```chown [File] [User]```
