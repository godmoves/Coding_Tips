## Useful Linux Commands

This file is a collection of some useful linux commands. And it will be updated every few weeks.

### du -h
Use this command to check the size of a folder and its subfolders, use flag `--max-depth` to assign the depth of subfolders to display and defualt is to show all subfloders. E.g., use `du -h --max-depth=1 .` to show the size of current folder and all subfolders in this folder.

### df -h
Show available space of disks.

### sudo mokutil --enable-validation
Install mokutil and use this command to turn UEFI secure booting on. Use `--disable-validation` to trun secure booting off.

### sudo ntfsfix
Fix mounting errors of ntfs format disk. E.g., `sudo ntfsfix /dev/sda5`

### ls -l | grep '^-' | wc -l
Check file number in a folder.

### sudo init 3
Turn off the X server. And use `sudo init 5` to restart it.

### move show application up in ubuntu 17.04
gsettings org.gnome.shell.extensions.dash-to-dock show-apps-at-top true

### Cache info for git
git config --global credential.helper cache