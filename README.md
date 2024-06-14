# Basic Linux Commands

##Contents

1. [Introduction](#introduction) (1)
2. [echo](#echo) (4)
3. [mv](#mv) (5)
4. [cp](#cp) (7)
5. [mkdir](#mkdir) (3)
6. [rmdir](#rmdir) (2)
7. [clear](#clear) (1)
8. [cal and ncal](#cal-and-ncal) (4)
9. [pwd](#pwd) (1)
10. [date](#date) (6)
11. [free](#free) (2)
12. [du](#du) (4)
13. [df](#df) (3)
14. [cat](#cat) (2)
15. [ls](#ls) (5)
16. [rm](#rm) (2)
17. [lspci](#lspci) (6)
18. [whereis](#whereis) (2)
19. [whatis and info](#whatis-and-info) (1)
20. [cd](#cd) (1)
21. [more](#more) (2)
22. [less](#less) (6)
23. [dircolors](#dircolors) (1)
24. [manpath](#manpath) (1)
25. [apropos](#apropos) (1)
26. [mandb](#mandb) (1)
27. [history](#history) (1)
28. [sort](#sort) (1)
29. [fdisk](#fdisk) (1)
30. [locate](#locate) (2)
31. [find](#find) (4)
32. [ifconfig](#ifconfig) (2)
33. [apt-get](#apt-get) (2)
34. [nano](#nano) (1)
35. [man](#man) (12)
36. [aircrack-ng](#aircrack-ng) (2)
37. [wesside-ng](#wesside-ng) (1)
38. [Other Useful Commands](#other-useful-commands) (8)
39. [Running Programs from the Console](#running-programs-from-the-console) (1)
40. [Backup Settings](#backup-settings) (1)
41. [testdisk](#testdisk) (2)
42. [Software Manager](#software-manager) (1)
43. [Functions of Some Files and Directories](#functions-of-some-files-and-directories) (2)
44. [Linux Mint Basics](#linux-mint-basics) (2)
45. [Shell Programming](#shell-programming) (2)
46. [Conquest Day of Mecca](#conquest-day-of-mecca) (1)

## Introduction

This repository provides explanations and examples for basic Linux commands. Each command is covered with its usage, options, and examples to help users understand and utilize them effectively.

## echo (4)

The `echo` command is used to display a line of text/string that is passed as an argument.

**Usage:**
```sh
echo [option] [string]
```

**Examples:**
```sh
echo "Hello, World!"
```

## mv (5)

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

## cp (7)

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

## mkdir (3)

The `mkdir` command is used to create directories.

**Usage:**
```sh
mkdir [option] directory_name
```

**Examples:**
```sh
mkdir new_directory
```

## rmdir (2)

The `rmdir` command is used to remove empty directories.

**Usage:**
```sh
rmdir [option] directory_name
```

**Examples:**
```sh
rmdir empty_directory
```

## clear (1)

The `clear` command is used to clear the terminal screen.

**Usage:**
```sh
clear
```

## cal and ncal (4)

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

## pwd (1)

The `pwd` command prints the current working directory.

**Usage:**
```sh
pwd
```

## date (6)

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

## free (2)

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

## du (4)

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

## df (3)

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

## cat (2)

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

## ls (5)

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

## rm (2)

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

## lspci (6)

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

## whereis (2)

The `whereis` command locates the binary, source, and manual page files for a command.

**Usage:**
```sh
whereis command
```

**Examples:**
```sh
whereis ls
```

## whatis and info (1)

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

## cd (1)

The `cd` command changes the current directory.

**Usage:**
```sh
cd [directory]
```

**Examples:**
```sh
cd /home/user
```

## more (2)

The `more` command views file contents interactively.

**Usage:**
```sh
more [option] [file]
```

**Examples:**
```sh
more file.txt
```

## less (6)

The `less` command views file contents interactively, similar to `more` but with more features.

**Usage:**
```sh
less [option] [file]
```

**Examples:**
```sh
less file.txt
```

## dircolors (1)

The `dircolors` command sets up color definitions for `ls`.

**Usage:**
```sh
dircolors [option] [file]
```

**Examples:**
```sh
dircolors
```

## manpath (1)

The `manpath` command displays the search path for manual pages.

**Usage:**
```sh
manpath [option]
```

**Examples:**
```sh
manpath
```

## apropos (1)

The `apropos` command searches the manual page names and descriptions.

**Usage:**
```sh
apropos keyword
```

**Examples:**
```sh
apropos copy
```

## mandb (1)

The `mandb` command initializes or updates the manual page index caches.

**Usage:**
```sh
mandb [option]
```

**Examples:**
```sh
mandb
```

## history (1)

The `history` command displays the command history list.

**Usage:**
```sh
history [option]
```

**Examples:**
```sh
history
```

## sort (1)

The `sort` command sorts lines of text files.

**Usage:**
```sh
sort [option] [file]
```

**Examples:**
```sh
sort file.txt
```

## fdisk (1)

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

## locate (2)

The `locate` command finds files by name.

**Usage:**
```sh
locate [option] pattern
```

**Examples:**
```sh
locate file.txt
```

## find (4)

The `find` command searches for files in a directory hierarchy.

**Usage:**
```sh
find [path] [option] [expression]
```

**Examples:**
```sh
find / -name file.txt
```

## ifconfig (2)

The `ifconfig` command configures a network interface.

**Usage:**
```sh
ifconfig [interface] [option]
```

**Examples:**
```sh
ifconfig eth0
```

## apt-get (2)

The `apt-get` command is a package handling utility.

**Usage:**
```sh
apt-get [option] command
```

**Examples:**
```sh
apt-get update
```

## nano (1)

The `nano` command is a simple text editor.

**Usage:**
```sh
nano [option] [file]
```

**Examples:**
```sh
nano file.txt
```

## man (12)

The `man` command displays the user manual of any command.

**Usage:**
```sh
man [command]
```

**Examples:**
```sh
man ls
```

## aircrack-ng (2)

The `aircrack-ng` command is a network software suite for monitoring and attacking WiFi networks.

**Usage:**
```sh
aircrack-ng [option] [file]
```

**Examples:**
```sh
aircrack-ng -a2 -b [target bssid] [capture file]
```

## wesside-ng (1)

The `wesside-ng` command is an automatic tool for WEP key recovery.

**Usage:**
```sh
wesside-ng [option] [interface]
```

**Examples:**
```sh
wesside-ng -i wlan0
```

## Other Useful Commands (8)

### Running Programs from the Console (1)

You can run programs from the console by typing their name and pressing Enter.

**Usage:**
```sh
program_name
```

### Backup Settings (1)

Backup settings can be configured using various tools and commands.

### testdisk (2)

The `testdisk` command is a data recovery utility.

**Usage:**
```sh
testdisk [option]
```

**Examples:**
```sh
testdisk
```

### Software Manager (1)

The Software Manager allows you to install and manage software on your system.

### Functions of Some Files and Directories (2)

Files and directories serve various functions in Linux. For example:
- `/etc`: Contains configuration files.
- `/home`: Contains user home directories.

### Linux Mint Basics (2)

Linux Mint provides a user-friendly desktop experience with various features and customization options.

### Shell Programming (2)

Shell programming involves writing scripts to automate tasks.

### Conquest Day of Mecca (1)

A historical day marking the conquest of Mecca.
