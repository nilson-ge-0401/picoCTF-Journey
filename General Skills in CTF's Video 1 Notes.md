# General Skills Video 1 Notes
## CyberChef and Decimals
1. Use CyberChef online to convert between any decimal
2. Use "From Base" box to convert any decimals to Base 10
3. Use "To Base" box to convert Base 10 to any decimals
4. Hexadecimal = Base 16
5. Octal = Base 8
6. Encoding = Translation from a number to truly anything
## The Shell
1. The shell = cmdlet window
2. Examples : Windows CMD, Windows PowerShell, Terminal, Bash
3. GUI: Mouse and Clicks, Phone, Tablet, Laptop, Desktop
4. Pros of Shell: Fast, Powerful, Automatable
### Shell Command in Ubuntu
1. Create new folder: mkdir [folder name]
2. Delete folder: rm -rf [folder name]   (rm:remove , r:recursive, f:force)
3. Create new file: touch [file name.type]  (Ex: touch file.txt)
4. Start an app or program: [program name]  (Ex: gimp)
5. Install softwares: sudo apt install [program name]  (sudo: execute with sys admin permission, apt:prgram management system for Ubuntu) (Ex: sudo apt install gimp)
6. Edit file: nano [file name]  (nano: notebook program on ubuntu that enables user to edit file using shell)
7. List content in a file: cat [file name] (it can list contents in a txt file)
8. Arithmetic (Math calculation): expr [calculation] (Ex: expr 3+4)
### Shell expression (Web Shell)
syreal-picoctf@webshell:~$
1. syreal-picoctf: username
2. @: seperator
3. webshell: machine name
4. ~: home directory
5. $: seperator between the command
### Entering command in Shell
1. Open a program: [program name] (Ex: nano)
2. Controlling a program with argument: [program name][argument] (Ex: nano file.txt)
3. List all contents in a directory: ls -al
4. Change directory: cd [path] (Ex: cd /)
5. Go to parent folder: cd ..
6. Echo words to a new file: echo ["word"] > [file name.type] (Ex: echo "hello" > test.txt)
7. To find specific content in a file: grep ["content"] [file name.type] (Ex: grep "monster" file01.txt)
8. Clear the terminal: clear
### Tips
1. Tab: Switch between different buttons or choices
2. Ctrl+c: Stop
