# Linux Commands

| **File Operations** | **Directory Operations** | **System Information** | **Process Management** | **Network Management** | **Text Processing** | **Package Management** | **Disk Operations** | **Security Tools**   |
|---------------------|--------------------------|------------------------|------------------------|------------------------|----------------------|------------------------|---------------------|-----------------------|
| `cp`                | `mkdir`                  | `echo`                 | `ps`                   | `ifconfig`             | `grep`               | `apt-get`              | `fdisk`             | `aircrack-ng`         |
| `mv`                | `rmdir`                  | `date`                 | `kill`                 | `netstat`              | `sort`               | `nano`                 | `testdisk`          | `wesside-ng`          |
| `rm`                | `cd`                     | `free`                 | `top`                  | `curl`                 | `sed`                | `man`                  | `df`                | `dnsenum`             |
| `touch`             | `pwd`                    | `uname`                |                        | `wget`                 | `awk`                |                        | `du`                | `dnsmap`              |
| `cat`               | `dircolors`              | `lspci`                |                        | `lsof`                 | `more`               |                        | `lsblk`             | `dmitry`              |
| `ls`                | `manpath`                | `whereis`              |                        |                        | `less`               |                        | `mount`             |                       |
|                     | `apropos`                | `whatis`               |                        |                        |                      |                        | `umount`            |                       |
|                     | `mandb`                  | `info`                 |                        |                        |                      |                        | `blkid`             |                       |
|                     |                          | `history`              |                        |                        |                      |                        | `ls`                |                       |
|                     |                          |                        |                        |                        |                      |                        |                     |                       |


##

<details>
  <summary> 1. File and Directory Management</summary>

1. **`echo`**: Display a line of text.
   ```sh
   echo "Hello, World!"
   ```
2. **`mv`**: Move or rename files.
   ```sh
   mv oldfile.txt newfile.txt
   ```
3. **`cp`**: Copy files and directories.
   ```sh
   cp source.txt destination.txt
   ```
4. **`mkdir`**: Create directories.
   ```sh
   mkdir new_directory
   ```
5. **`rmdir`**: Remove empty directories.
   ```sh
   rmdir old_directory
   ```
6. **`clear`**: Clear the terminal screen.
   ```sh
   clear
   ```
7. **`cal` and `ncal`**: Display a calendar.
   ```sh
   cal    # Display current month's calendar
   ncal   # Display calendar in an alternative layout
   ```
8. **`pwd`**: Print the current working directory.
   ```sh
   pwd
   ```
9. **`date`**: Display or set the system date and time.
   ```sh
   date
   ```
10. **`free`**: Display memory usage.
    ```sh
    free -h   # Display memory usage in human-readable format
    ```
11. **`du`**: Estimate file space usage.
    ```sh
    du -h    # Display disk usage in human-readable format
    ```
12. **`df`**: Report file system disk space usage.
    ```sh
    df -h    # Display disk space usage in human-readable format
    ```
13. **`cat`**: Concatenate and display files.
    ```sh
    cat file.txt
    ```
14. **`ls`**: List directory contents.
    ```sh
    ls -l    # List in long format
    ```
15. **`rm`**: Remove files or directories.
    ```sh
    rm file.txt
    ```
16. **`lspci`**: List all PCI devices.
    ```sh
    lspci
    ```
</details>

<details>
  <summary>2. System Information and Management</summary>

1. **`whereis`**: Locate the binary, source, and manual page files for a command.
    ```sh
    whereis ls
    ```
2. **`whatis`** and **`info`**: Display one-line manual page descriptions and detailed command information.
    ```sh
    whatis ls
    info ls
    ```
3. **`cd`**: Change the current directory.
    ```sh
    cd /path/to/directory
    ```
4. **`more`**: View file contents one screen at a time.
    ```sh
    more file.txt
    ```
5. **`less`**: View file contents with backward movement.
    ```sh
    less file.txt
    ```
6. **`dircolors`**: Set up color definitions for `ls`.
    ```sh
    dircolors
    ```
7. **`manpath`**: Determine search path for manual pages.
    ```sh
    manpath
    ```
8. **`apropos`**: Search the manual page names and descriptions.
    ```sh
    apropos keyword
    ```
9. **`mandb`**: Create or update the manual page index caches.
    ```sh
    mandb
    ```
10. **`history`**: Show the command history.
    ```sh
    history
    ```
11. **`sort`**: Sort lines of text files.
    ```sh
    sort file.txt
    ```
12. **`fdisk`**: Manipulate disk partition table.
    ```sh
    fdisk -l   # List disk partitions
    ```
13. **`locate`**: Find files by name.
    ```sh
    locate filename
    ```
14. **`find`**: Search for files in a directory hierarchy.
    ```sh
    find /path -name filename
    ```
15. **`ifconfig`**: Configure network interfaces.
    ```sh
    ifconfig
    ```
16. **`apt-get`**: Package handling utility.
    ```sh
    sudo apt-get update    # Update package lists
    ```
17. **`nano`**: Text editor in the terminal.
    ```sh
    nano file.txt
    ```
18. **`man`**: Display the manual page for a command.
    ```sh
    man ls
    ```
19. **`aircrack-ng`**: Network security tool.
    ```sh
    aircrack-ng file.cap
    ```
20. **`wesside-ng`**: Automate WEP key recovery.
    ```sh
    wesside-ng -i wlan0
    ```
21. **`testdisk`**: Data recovery tool.
    ```sh
    testdisk
    ```
22. **`touch`**: Change file timestamps or create empty files.
    ```sh
    touch newfile.txt
    ```
23. **`head`**: Output the first part of files.
    ```sh
    head file.txt
    ```
24. **`tail`**: Output the last part of files.
    ```sh
    tail file.txt
    ```
25. **`grep`**: Print lines matching a pattern.
    ```sh
    grep "pattern" file.txt
    ```
26. **`chmod`**: Change file modes or Access Control Lists.
    ```sh
    chmod 755 file.txt
    ```
27. **`chown`**: Change file owner and group.
    ```sh
    chown user:group file.txt
    ```
28. **`ps`**: Report a snapshot of current processes.
    ```sh
    ps aux
    ```
29. **`kill`**: Send a signal to a process.
    ```sh
    kill 1234    # Kill process with PID 1234
    ```
30. **`uname`**: Print system information.
    ```sh
    uname -a
    ```
31. **`top`**: Display real-time system information, including active processes.
    ```sh
    top
    ```
32. **`wget`**: Non-interactive network downloader.
    ```sh
    wget http://example.com/file
    ```
33. **`curl`**: Transfer data from or to a server.
    ```sh
    curl http://example.com
    ```
34. **`sed`**: Stream editor for filtering and transforming text.
    ```sh
    sed 's/old/new/g' file.txt
    ```
35. **`netstat`**: Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships.
    ```sh
    netstat -an
    ```
36. **`lsof`**: List open files.
    ```sh
    lsof
    ```
37. **`dnsenum`**: Enumerate DNS information.
    ```sh
    dnsenum example.com
    ```
38. **`dnsmap`**: Network discovery by brute force.
    ```sh
    dnsmap example.com
    ```
39. **`dmitry`**: Deepmagic Information Gathering Tool.
    ```sh
    dmitry -winsepfbo example.com
    ```
</details>

#
