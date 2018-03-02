## Useful Linux Commands

This file is a collection of some useful linux commands. And it will be updated every few weeks.

### du -h
Use this command to check the size of a folder and its subfolders, use flag `--max-depth` to assign the depth of subfolders to display and defualt is to show all subfloders. Ex. use `du -h --max-depth=1 .` to show the size of current folder and all subfolders in this folder.

### df -h
Show available space of disks.

### sudo mokutil --enable-validation
Install mokutil and use this command to turn UEFI secure booting on. Use `--disable-validation` to trun secure booting off.

### sudo ntfsfix
Fix mounting errors of ntfs format disk. Ex. `sudo ntfsfix /dev/sda5`
