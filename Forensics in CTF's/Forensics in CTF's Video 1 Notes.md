# Forensics in CTF's Video 1 Notes
## Computer Anatomy
Hardware ---> OS ---> Scheduler, App, FileSystem
1. Hardware: Laptop, Desktop, Server, Phone, Tablet, RAM, CPU, SSD, HDD, GPU, Motherboard .....
2. OS: Windows, MacOS, Linux
3. Scheduler: Enables Concurrency
4. FileSystem: Manages Files (Path, TimeStamp, Owner, Permissions, Data)
## Woke Files
1. Hidden Files: Protection, Discretion
2. Metadata: Data about the Data, Facts about the Data (TimeStamps, Owner, Permissions, Format, Size)
3. exiftool command: List all metadata/properties of a file (Ex: exiftool file.txt)
## Files as hex
1. Default: interpretation
2. Raw: No interpretation, use hex editor
3. xxd command: Open file as hex format (Ex: xxd file.txt)
4. Magic Bytes: Can be used to identify what kind of the file it is.
