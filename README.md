# Basic Linux Commands

## Contents

1. [Introduction](#introduction)
2. [File Management](#file-management)
   - [echo](#echo)
   - [mv](#mv)
   - [cp](#cp)
   - [mkdir](#mkdir)
   - [rmdir](#rmdir)
   - [touch](#touch)
3. [System Information](#system-information)
   - [clear](#clear)
   - [cal and ncal](#cal-and-ncal)
   - [pwd](#pwd)
   - [date](#date)
   - [free](#free)
   - [du](#du)
   - [df](#df)
   - [uname](#uname)
   - [top](#top)
4. [File Viewing](#file-viewing)
   - [cat](#cat)
   - [more](#more)
   - [less](#less)
   - [head](#head)
   - [tail](#tail)
5. [Network Commands](#network-commands)
   - [ifconfig](#ifconfig)
   - [netstat](#netstat)
   - [wget](#wget)
   - [curl](#curl)
6. [Process Management](#process-management)
   - [ps](#ps)
   - [kill](#kill)
7. [Text Processing](#text-processing)
   - [grep](#grep)
   - [sed](#sed)
   - [sort](#sort)
8. [Permissions Management](#permissions-management)
   - [chmod](#chmod)
   - [chown](#chown)
9. [Miscellaneous](#miscellaneous)
   - [history](#history)
   - [dnsenum](#dnsenum)
   - [dnsmap](#dnsmap)
   - [dmitry](#dmitry)

## Introduction
This repository provides explanations and examples for basic Linux commands. 

## File Management

### echo
| Usage | Example |
|-------|---------|
| echo [option] [string] | `echo "Hello, World!"` |

The `echo` command is used to display a line of text/string that is passed as an argument.

### mv
| Usage | Example |
|-------|---------|
| mv [option] source target | `mv file1.txt file2.txt`<br>`mv file.txt /home/user/Documents/` |

The `mv` command is used to move or rename files and directories.

### cp
| Usage | Example |
|-------|---------|
| cp [option] source destination | `cp file1.txt file2.txt`<br>`cp -r /source/directory /destination/directory` |

The `cp` command is used to copy files and directories.

### mkdir
| Usage | Example |
|-------|---------|
| mkdir [option] directory_name | `mkdir new_directory` |

The `mkdir` command is used to create directories.

### rmdir
| Usage | Example |
|-------|---------|
| rmdir [option] directory_name | `rmdir empty_directory` |

The `rmdir` command is used to remove empty directories.

### touch
| Usage | Example |
|-------|---------|
| touch [option] file_name | `touch newfile.txt` |

The `touch` command is used to create empty files or update the timestamp of existing files.

## System Information

### clear
| Usage | Example |
|-------|---------|
| clear | `clear` |

The `clear` command is used to clear the terminal screen.

### cal and ncal
| Usage | Example |
|-------|---------|
| cal [month] [year] | `cal` |
| ncal [option] [month] [year] | `ncal -w` |

The `cal` command displays a simple calendar, and `ncal` displays a calendar in a different format.

### pwd
| Usage | Example |
|-------|---------|
| pwd | `pwd` |

The `pwd` command prints the current working directory.

### date
| Usage | Example |
|-------|---------|
| date [option] [+format] | `date`<br>`date "+%Y-%m-%d %H:%M:%S"` |

The `date` command displays or sets the system date and time.

### free
| Usage | Example |
|-------|---------|
| free [option] | `free`<br>`free -h` |

The `free` command displays the amount of free and used memory in the system.

### du
| Usage | Example |
|-------|---------|
| du [option] [file] | `du`<br>`du -sh` |

The `du` command estimates file space usage.

### df
| Usage | Example |
|-------|---------|
| df [option] | `df`<br>`df -h` |

The `df` command reports file system disk space usage.

### uname
| Usage | Example |
|-------|---------|
| uname [option] | `uname`<br>`uname -a` |

The `uname` command prints system information.

### top
| Usage | Example |
|-------|---------|
| top | `top` |

The `top` command displays real-time system information, including running processes.

## File Viewing

### cat
| Usage | Example |
|-------|---------|
| cat [option] [file] | `cat file.txt`<br>`cat file1.txt file2.txt` |

The `cat` command concatenates and displays files.

### more
| Usage | Example |
|-------|---------|
| more [option] [file] | `more file.txt` |

The `more` command views file contents interactively.

### less
| Usage | Example |
|-------|---------|
| less [option] [file] | `less file.txt` |

The `less` command views file contents interactively, similar to `more` but with more features.

### head
| Usage | Example |
|-------|---------|
| head [option] [file] | `head file.txt`<br>`head -n 5 file.txt` |

The `head` command outputs the first part of files.

### tail
| Usage | Example |
|-------|---------|
| tail [option] [file] | `tail file.txt`<br>`tail -n 5 file.txt` |

The `tail` command outputs the last part of files.

## Network Commands

### ifconfig
| Usage | Example |
|-------|---------|
| ifconfig [interface] [option] | `ifconfig eth0` |

The `ifconfig` command configures a network interface.

### netstat
| Usage | Example |
|-------|---------|
| netstat -tuln | `netstat -tuln` |

The `netstat` command displays network connections, routing tables, interface statistics, masquerade connections, and multicast memberships.

### wget
| Usage | Example |
|-------|---------|
| wget [option] url | `wget http://example.com/file.zip` |

The `wget` command downloads files from the web.

### curl
| Usage | Example |
|-------|---------|
| curl [option] url | `curl http://example.com` |

The `curl` command transfers data from or to a server.

## Process Management

### ps
| Usage | Example |
|-------|---------|
| ps [option] | `ps`<br>`ps aux` |

The `ps` command reports a snapshot of current processes.

### kill
| Usage | Example |
|-------|---------|
| kill [option] pid | `kill 1234`<br>`kill -9 1234` |

The `kill` command sends a signal to a process, usually to terminate it.

## Text Processing

### grep
| Usage | Example |
|-------|---------|
| grep [option] pattern [file] | `grep "hello" file.txt`<br>`grep -i "hello" file.txt` |

The `grep` command searches for patterns in files.

### sed
| Usage | Example |
|-------|---------|
| sed 's/oldstring/newstring/g' file.txt | `sed 's/oldstring/newstring/g' file.txt` |

The `sed` command is a stream editor used for text processing and transformation.

### sort
| Usage | Example |
|-------|---------|
| sort [option] [file] | `sort file.txt` |

The `sort` command sorts lines of text files.

## Permissions Management

### chmod
| Usage | Example |
|-------|---------|
| chmod [option] mode file | `chmod 755 file.txt`<br>`chmod +x script.sh` |

The `chmod` command changes file permissions.

### chown
| Usage | Example |
|-------|---------|
| chown [option] owner[:group] file | `chown user:group file.txt` |

The `chown` command changes file ownership.

## Miscellaneous

### history
| Usage | Example |
|-------|---------|
| history [option] | `history` |

The `history` command displays the command history list.

### dnsenum
| Usage | Example |
|-------|---------|
| dnsenum [domain] | `dnsenum example.com` |

The `dnsenum` command enumerates DNS information of a domain.

### dnsmap
| Usage | Example |
|-------|---------|
| dnsmap [domain] | `dnsmap example.com` |

The `dnsmap` command is used for subdomain bruteforce.

### dmitry
| Usage | Example |
|-------|---------|
| dmitry [option] target | `dmitry -winsepfb example.com` |

The `dmitry` command (Deepmagic Information Gathering Tool) is a Unix/Linux command-line application coded in C.

