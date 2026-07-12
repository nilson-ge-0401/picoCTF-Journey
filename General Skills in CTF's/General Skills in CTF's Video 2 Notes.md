# General Skills in CTF's Video 2 Notes
## Linux Basics
1. root: Highest Directory(/), Linux Superuser, All Privileges
## Linux Basic Commands
1. reset command: Hard reset the terminal if it's broken
2. pwd command: Print Working Directory
3. cp command: copy file
4. rm command: remove file (Cannot remove folder/directory)
5. rmdir command: remove folder/directory (Cannot remove files)
6. rm -r command: remove folder/directory (Cannot remove files) (-r: recursive)
7. mv command: move file, it can also rename file (Ex: mv file1.txt file2.txt)
8. touch command: create empty file (Ex: touch empty-file)
9. man command: Manual Pager Utils (File Reader) (System Files Only)
10. echo command: print out values (Ex: echo "Hello")
11. wget command: download file from the internet (Ex: wget https://drive.google.com/file/d/1G-grfVw1NldMD3TRG-7Lco-yOuaoTKoK/view?usp=sharing)
12. unzip command: unzip zipfile (Ex: unzip file1.zip)
13. chmod command: change file permissions
14. ./[file name.sh]: execute file (Ex: ./script.sh)
15. python3: use or execute python file
16. exit: logout
## Linux File Permissions
1. r: read
2. w: write
3. x: execute
### Linux File Permissions Format
Example: rwxrw-r--
1. user: read, write, execute (rwx)
2. group: read, write (rw-)
3. others: read (r--)
### Modify Linux File Permissions
chmod command: Modify file permissions
1. chmod +x [file name]: Give the file the permission to execute (Ex: chmod +x script.sh)
2. chmod +r [file name]: Give the file the permission to be read (Ex: chmod +r file.txt)
3. chmod +w [file name]: Give the file the permission to be modified (Ex: chmod +w file.txt)
## Linux PowerTools
1. less command: File Reader (Personal Files or Other Files)
2. history command: List all commands that the user has ever entered
3. grep command: Search keyword or value in a file or files (Ex: grep "Hi" *.txt)
4. find command: Search for file or files (Ex: find -name "python") -> Find the files with the name start with "python"
5. file command: List the properties of a file (Ex: file monster.txt)
6. strings command: List binary or machine code into clear text (Ex: strings unknown_file)
7. apt command: Program Management System, use it to install app or program (Ex: sudo apt install gimp)
8. sudo command: Linux Root User, Highest Privilege (Ex: sudo -i)
## Basic Program Concepts
1. input ----> Program ----> output ----> Terminal Window
2. Example: echo "Hello" ----> echo Program ----> "Hello" ----> "Hello"
3. Terminal = STDOUT = STDERR
4. File Redirection: Export the result of a command to a file (Ex: grep "hello" file.txt > answer.txt)
5. | symbol: Packaged to (Ex: strings unknown_file | grep "picoCTF" | less) ---> Use less to print out the results contain "picoCTF" from the unknown_file
