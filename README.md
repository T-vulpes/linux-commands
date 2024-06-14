# <span style="color:blue">Basic Linux Commands</span>

## <span style="color:blue">Contents</span>

1. [<span style="color:darkgreen">Introduction</span>](#introduction)
2. [<span style="color:darkgreen">echo</span>](#echo)
3. [<span style="color:darkgreen">mv</span>](#mv)
4. [<span style="color:darkgreen">cp</span>](#cp)
5. [<span style="color:darkgreen">mkdir</span>](#mkdir)
6. [<span style="color:darkgreen">rmdir</span>](#rmdir)
7. [<span style="color:darkgreen">clear</span>](#clear)
8. [<span style="color:darkgreen">cal and ncal</span>](#cal-and-ncal)
9. [<span style="color:darkgreen">pwd</span>](#pwd)
10. [<span style="color:darkgreen">date</span>](#date)
11. [<span style="color:darkgreen">free</span>](#free)
12. [<span style="color:darkgreen">du</span>](#du)
13. [<span style="color:darkgreen">df</span>](#df)
14. [<span style="color:darkgreen">cat</span>](#cat)
15. [<span style="color:darkgreen">ls</span>](#ls)
16. [<span style="color:darkgreen">rm</span>](#rm)
17. [<span style="color:darkgreen">lspci</span>](#lspci)
18. [<span style="color:darkgreen">whereis</span>](#whereis)
19. [<span style="color:darkgreen">whatis and info</span>](#whatis-and-info)
20. [<span style="color:darkgreen">cd</span>](#cd)
21. [<span style="color:darkgreen">more</span>](#more)
22. [<span style="color:darkgreen">less</span>](#less)
23. [<span style="color:darkgreen">dircolors</span>](#dircolors)
24. [<span style="color:darkgreen">manpath</span>](#manpath)
25. [<span style="color:darkgreen">apropos</span>](#apropos)
26. [<span style="color:darkgreen">mandb</span>](#mandb)
27. [<span style="color:darkgreen">history</span>](#history)
28. [<span style="color:darkgreen">sort</span>](#sort)
29. [<span style="color:darkgreen">fdisk</span>](#fdisk)
30. [<span style="color:darkgreen">locate</span>](#locate)
31. [<span style="color:darkgreen">find</span>](#find)
32. [<span style="color:darkgreen">ifconfig</span>](#ifconfig)
33. [<span style="color:darkgreen">apt-get</span>](#apt-get)
34. [<span style="color:darkgreen">nano</span>](#nano)
35. [<span style="color:darkgreen">man</span>](#man)
36. [<span style="color:darkgreen">aircrack-ng</span>](#aircrack-ng)
37. [<span style="color:darkgreen">wesside-ng</span>](#wesside-ng)
38. [<span style="color:darkgreen">Other Useful Commands</span>](#other-useful-commands)
39. [<span style="color:darkgreen">Running Programs from the Console</span>](#running-programs-from-the-console)
40. [<span style="color:darkgreen">testdisk</span>](#testdisk)
41. [<span style="color:darkgreen">Functions of Some Files and Directories</span>](#functions-of-some-files-and-directories)

## <span style="color:blue">Introduction</span>

This repository provides explanations and examples for basic Linux commands.

## <span style="color:blue">echo</span>

The `echo` command is used to display a line of text/string that is passed as an argument.

**Usage:**
```sh
echo [option] [string]

Examples:
echo "Hello, World!"

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


