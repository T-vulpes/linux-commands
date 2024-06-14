# Basic Linux Commands

##Contents

1. [Introduction](#introduction)
2. [echo](#echo) 
3. [mv](#mv) 
4. [cp](#cp) 
5. [mkdir](#mkdir) 
6. [rmdir](#rmdir) 
7. [clear](#clear) 
8. [cal and ncal](#cal-and-ncal) 
9. [pwd](#pwd) 
10. [date](#date) 
11. [free](#free)
12. [du](#du) 
13. [df](#df) 
14. [cat](#cat) 
15. [ls](#ls) 
16. [rm](#rm) 
17. [lspci](#lspci)
18. [whereis](#whereis) 
19. [whatis and info](#whatis-and-info)
20. [cd](#cd)
21. [more](#more)
22. [less](#less) 
23. [dircolors](#dircolors) 
24. [manpath](#manpath) 
25. [apropos](#apropos) 
26. [mandb](#mandb) 
27. [history](#history) 
28. [sort](#sort) 
29. [fdisk](#fdisk) 
30. [locate](#locate) 
31. [find](#find) 
32. [ifconfig](#ifconfig) 
33. [apt-get](#apt-get) 
34. [nano](#nano) 
35. [man](#man) 
36. [aircrack-ng](#aircrack-ng) 
37. [wesside-ng](#wesside-ng) 
38. [Other Useful Commands](#other-useful-commands)
39. [Running Programs from the Console](#running-programs-from-the-console)
40. [testdisk](#testdisk) 
41. [Functions of Some Files and Directories](#functions-of-some-files-and-directories) 

## Introduction
This repository provides explanations and examples for basic Linux commands. 

## echo 

The `echo` command is used to display a line of text/string that is passed as an argument.

**Usage:**
```sh
echo [option] [string]
```

**Examples:**
```sh
echo "Hello, World!"
```

## mv 

The `mv` command is used to move or rename files and directories.

**Usage:**
```sh
mv [option] source target
```

**Examples:**
```sh
mv file1.txt file2.txt
mv file.txt /home/user/Documents/
```

## cp 

The `cp` command is used to copy files and directories.

**Usage:**
```sh
cp [option] source destination
```

**Examples:**
```sh
cp file1.txt file2.txt
cp -r /source/directory /destination/directory
```

## mkdir 

The `mkdir` command is used to create directories.

**Usage:**
```sh
mkdir [option] directory_name
```

**Examples:**
```sh
mkdir new_directory
```

## rmdir 

The `rmdir` command is used to remove empty directories.

**Usage:**
```sh
rmdir [option] directory_name
```

**Examples:**
```sh
rmdir empty_directory
```

## clear 

The `clear` command is used to clear the terminal screen.

**Usage:**
```sh
clear
```

## cal and ncal

The `cal` command displays a simple calendar, and `ncal` displays a calendar in a different format.

**Usage:**
```sh
cal [month] [year]
ncal [option] [month] [year]
```

**Examples:**
```sh
cal
ncal -w
```

## pwd 

The `pwd` command prints the current working directory.

**Usage:**
```sh
pwd
```

## date 

The `date` command displays or sets the system date and time.

**Usage:**
```sh
date [option] [+format]
```

**Examples:**
```sh
date
date "+%Y-%m-%d %H:%M:%S"
```

## free 

The `free` command displays the amount of free and used memory in the system.

**Usage:**
```sh
free [option]
```

**Examples:**
```sh
free
free -h
```

## du 

The `du` command estimates file space usage.

**Usage:**
```sh
du [option] [file]
```

**Examples:**
```sh
du
du -sh
```

## df 

The `df` command reports file system disk space usage.

**Usage:**
```sh
df [option]
```

**Examples:**
```sh
df
df -h
```

## cat 

The `cat` command concatenates and displays files.

**Usage:**
```sh
cat [option] [file]
```

**Examples:**
```sh
cat file.txt
cat file1.txt file2.txt
```

## ls 

The `ls` command lists directory contents.

**Usage:**
```sh
ls [option] [file]
```

**Examples:**
```sh
ls
ls -l
```

## rm 

The `rm` command removes files or directories.

**Usage:**
```sh
rm [option] file
```

**Examples:**
```sh
rm file.txt
rm -r directory
```

## lspci

The `lspci` command lists all PCI devices.

**Usage:**
```sh
lspci [option]
```

**Examples:**
```sh
lspci
lspci -v
```

## whereis

The `whereis` command locates the binary, source, and manual page files for a command.

**Usage:**
```sh
whereis command
```

**Examples:**
```sh
whereis ls
```

## whatis and info 

The `whatis` command displays a one-line description of a command, and `info` provides detailed information.

**Usage:**
```sh
whatis command
info command
```

**Examples:**
```sh
whatis ls
info ls
```

## cd

The `cd` command changes the current directory.

**Usage:**
```sh
cd [directory]
```

**Examples:**
```sh
cd /home/user
```

## more 

The `more` command views file contents interactively.

**Usage:**
```sh
more [option] [file]
```

**Examples:**
```sh
more file.txt
```

## less 

The `less` command views file contents interactively, similar to `more` but with more features.

**Usage:**
```sh
less [option] [file]
```

**Examples:**
```sh
less file.txt
```

## dircolors

The `dircolors` command sets up color definitions for `ls`.

**Usage:**
```sh
dircolors [option] [file]
```

**Examples:**
```sh
dircolors
```

## manpath 

The `manpath` command displays the search path for manual pages.

**Usage:**
```sh
manpath [option]
```

**Examples:**
```sh
manpath
```

## apropos

The `apropos` command searches the manual page names and descriptions.

**Usage:**
```sh
apropos keyword
```

**Examples:**
```sh
apropos copy
```

## mandb 

The `mandb` command initializes or updates the manual page index caches.

**Usage:**
```sh
mandb [option]
```

**Examples:**
```sh
mandb
```

## history

The `history` command displays the command history list.

**Usage:**
```sh
history [option]
```

**Examples:**
```sh
history
```

## sort

The `sort` command sorts lines of text files.

**Usage:**
```sh
sort [option] [file]
```

**Examples:**
```sh
sort file.txt
```

## fdisk 

The `fdisk` command

 is a disk partitioning tool.

**Usage:**
```sh
fdisk [option] [device]
```

**Examples:**
```sh
fdisk /dev/sda
```

## locate 

The `locate` command finds files by name.

**Usage:**
```sh
locate [option] pattern
```

**Examples:**
```sh
locate file.txt
```

## find 

The `find` command searches for files in a directory hierarchy.

**Usage:**
```sh
find [path] [option] [expression]
```

**Examples:**
```sh
find / -name file.txt
```

## ifconfig 

The `ifconfig` command configures a network interface.

**Usage:**
```sh
ifconfig [interface] [option]
```

**Examples:**
```sh
ifconfig eth0
```

## apt-get 

The `apt-get` command is a package handling utility.

**Usage:**
```sh
apt-get [option] command
```

**Examples:**
```sh
apt-get update
```

## nano 

The `nano` command is a simple text editor.

**Usage:**
```sh
nano [option] [file]
```

**Examples:**
```sh
nano file.txt
```

## man 

The `man` command displays the user manual of any command.

**Usage:**
```sh
man [command]
```

**Examples:**
```sh
man ls
```

## aircrack-ng 

The `aircrack-ng` command is a network software suite for monitoring and attacking WiFi networks.

**Usage:**
```sh
aircrack-ng [option] [file]
```

**Examples:**
```sh
aircrack-ng -a2 -b [target bssid] [capture file]
```

## wesside-ng 

The `wesside-ng` command is an automatic tool for WEP key recovery.

**Usage:**
```sh
wesside-ng [option] [interface]
```

**Examples:**
```sh
wesside-ng -i wlan0
```

## Other Useful Commands

### Running Programs from the Console 

You can run programs from the console by typing their name and pressing Enter.

**Usage:**
```sh
program_name
```

### testdisk 

The `testdisk` command is a data recovery utility.

**Usage:**
```sh
testdisk [option]
```

**Examples:**
```sh
testdisk
```

### Functions of Some Files and Directories 

Files and directories serve various functions in Linux. For example:
- `/etc`: Contains configuration files.
- `/home`: Contains user home directories.