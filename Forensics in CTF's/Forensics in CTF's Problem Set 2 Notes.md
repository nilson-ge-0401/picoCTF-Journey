# Forensics in CTF's Problem Set 2 Notes
## Challenge 1: Sleuthkit Intro
1. Use wget to download the img file
2. Use gunzip to extract the img
3. use mmls to list all partitions
4. connect to the remote server
5. paste the length of the Linux partition
6. submit the flag
## Challenge 2: Disk, disk, sleuth!
1. Use wget to download the img file
2. Use gunzip to extract the img
3. Use mmls to list all partitions and not the Linux partition "start code" (Usually 2048)
4. srch_strings -o 2048 dds1.alpine.flag.img | grep "pico"
5. Find and copy the flag to the submission
## Challenge 3: Disk, disk, sleuth! 2
1. Use wget to download the img file
2. Use gunzip to extract the img
3. Use mmls to list all partitions and not the Linux partition "start code" (Usually 2048)
4. fls -o 2048 dds2.alpine.flag.img  (List all files in the Linux partition)
5. fls -r -o 2048 dds2.alpine.flag.img | grep "down" (Find the file with the name down*)
6. icat -o 2048 dds2.alpine.flag.img 18291 (cat the content of the txt file) (18291 is the inode for the file)
7. Enter the flag to the submission
## Challenge 4: Sleuthkit Apprentice
1. Use wget to download the file
2. Use gunzip to extract the img
3. Use mmls to list all partitions
4. You will see 3 Linux partitions, ignore the "Linux Swap" partition since it usually doesn't contain any files
5. fls -o 2048 disk.flag.img ---> You will see files with vary formats, so it's not the partition we want
6. fls -o 360448 disk.flag.img ---> You will see normal Linux system files and folders, it's the one we need
7. fls -r -o 360448 disk.flag.img | grep "flag" ---> You will see 2 txt files
8. icat -o 360448 disk.flag.img 2082 ---> You will see 2 random numbers, so it's not the flag
9. icat -o 360448 disk.flag.img 2371 ---> You will see the flag
10. Copy and paste the flag to the submission
