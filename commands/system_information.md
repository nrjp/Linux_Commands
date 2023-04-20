<h2>System Information</h2>

|1|[uname](#1)    |[top](#2)    |[sudo](#3) | [lsb_release -a](#10)|
|-|---------------|-------------|-----------|--------------------|
|2|[history](#4)  |[df](#5)     |[du](#6)   |[hostname](#11)|
|3|[clear](#7)    |[exit](#8)   |[free](#9) |[whoami](#12)|
|4|[hostname](#13)|[uptime](#14)|[date](#15)|



<span id="1">
<p>uname:&nbsp Displays the system information including kernel version, operating system, machine hardware</p>

```
uname -a
```

<span id="2">
<p>top:&nbsp Displays real-time information about system processes including CPU and memory usage</p>

```
top
```

<span id="3">
<p>sudo:&nbsp allows a user to run a command with administrative privileges</p>

```
sudo apt-get install package_name
```

<span id='10'>
<p>lsb_release -a :&nbsp Displays the LSB (Linux Standard Base) information including distribution ID, description, and release number
</p>

```
lsb_release -a
```
<span id="4">
<p>history:&nbsp The history command displays a list of the commands that have been executed in the current terminal session</p>

```
history 10
```

<span id="5">
<p>df:&nbsp command displays information about the file system disk space usage, including the total, used, and available space on each mounted file system</p>

```
df -h
```

<span id="6">
<p>du:&nbsp command displays information about the disk space usage of files and directories. This is useful for finding large files or directories that are taking up a lot of space on the system</p>

```
du -h
```

<span id="11">
<p>hostname:&nbsp Displays the hostname of the system.</p>

```
hostname
```

<span id="7">
<p>clear:&nbsp  command is used to clear the terminal screen.</p>

```
clear
```

<span id="8">
<p>exit:&nbsp command is used to close the current terminal session or shell</p>

```
exit
```

<span id="9">
<p>free:&nbsp command displays information about the system's memory usage, including the total, used, and free memory</p>

```
free -h
```

<span id="12">
<p>whoami:&nbsp Displays the username of the currently logged-in user</p>

```
whoami
```

<span id="13">
<p>hostname:&nbsp Displays the hostname of the system</p>

```
hostname
```
<span id="14">
<p>hostname:&nbsp command in Linux is used to show how long the system has been running, as well as the current system load averages for 1, 5, and 15 minutes</p>

```
uptime
```

<span id="15">
<p>date:&nbsp shows current date and time</p>

```
date
```

<h4>Option we can use with commands</h4>
<ul>
    <li>-h: display output in a human-readable format, such as using kilobytes (kB), megabytes (MB), or gigabytes (GB) instead of bytes </li>
    <li>-k or -kh: display output in kilobytes</li>
    <li>-l: display output in long format, which provides more detailed information about files or directories, such as permissions, ownership, and timestamps</li>
    <li>-a: display all files and directories, including hidden ones</li>
    <li>-r: reverse the order of output, such as sorting files or directories in reverse alphabetical order</li>
    <li>-t: sort output by time, such as by creation or modification time</li>
    <li>-i: display the inode number of each file or directory</li>
    <li>-f: do not sort the output, and display files and directories in the order they appear</li>
    <li>-n: sort output numerically, such as by file size or numerical value</li>
    <li>-q: suppress error messages</li>
    <li>-v: display verbose output or additional information</li>
</ul>
