# Forensics in CTF's Video 2 Notes
## Disk Analysis
### Imaging
1. Analysis through software
2. Work from a copy
3. dd command: Convert or copy raw data (Ex: dd if=hello.txt of=hello1.txt) ---> copy hello.txt to hello1.txt (if: input file, of: output file)
### Layers
1. Multimedia Layer: Partition Table
2. Block Layer: Contains the data, Equal-sized chunk
3. Journal Layer: Incremental Backup, Recover from crashes
4. Metadata Layer: Permission, Ownership, TimeStamps, File Properties
5. Filename Layer: Normal shell experience/GUI Experience, Highest Layer
### Sleuthkit
1. Traverse all Layers
2. Start at multimedia layer
#### Multimedia Layer Commands
1. mmstat: List the type of the partition table
2. mmls: List the partition
3. mmcat: Print out the whole partition table
#### Block Layer Commands
1. blkstat: List the type of the block
2. blkls: List the blocks
3. blkcat: Print out all blocks
4. blkcalc: Calculate the blocks
#### Journal Layer Commands
1. jls
2. jcat
#### Metadata Layer Commands (i=inode)
1. istat
2. ils
3. icat
4. ifind
#### Filename Layer Commands (i=inode)
1. fls
2. fcat
3. ffind
### Autopsy
1. GUI form of Sleuthkit
