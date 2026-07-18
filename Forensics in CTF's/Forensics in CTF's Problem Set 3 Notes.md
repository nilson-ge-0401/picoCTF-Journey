# Forensics in CTF's Problem Set 3 Notes
## Challenge 1: Extensions
1. Use wget to download the file
2. file flag.txt ---> You will notice that it's actually a png file
3. mv flag.txt flag.png ---> Rename flag.txt to flag.png
4. xdg-open flag.png ---> Open the image using the image viewer
5. Submit the flag to the submission
## Challenge 2: St3g0
1. Use wget to download the file
2. sudo gem install zsteg ---> Install zsteg command-line tool
3. zsteg pico.flag.png
4. Find the flag and submit it
## Challenge 3: What Lies Within
1. Use wget to download the file
2. sudo gem install zsteg ---> Bypass this step if zsteg is already installed
3. zsteg buildings.png
4. Find the flag and submit it
