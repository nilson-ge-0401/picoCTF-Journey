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
9. man command: Manual Pager Utils (File Reader)
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
