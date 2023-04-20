<h2>Other</h2>

|1|[service](#1)|[kill](#2)|[ps](#3)|
|-|-----------|---------|----------|
|2|[apt](#4)|[pacman](#5)|[rpm](#6)|
|3|[cal](#7)|[date](#8)|[alias](#9)|
|4|[dd](#10)|[whatis](#11)| [which](#12)|
|5|[curl](#13)|


<span id="1">
<p>service:&nbsp command is used to control system services on Linux. It allows you to start, stop, restart, and check the status of a service.</p>

```
service apache2 start
```

<span id="2">
<p>kill:&nbsp command is used to terminate processes on Linux. It sends a signal to a process, which can be used to stop it or modify its behavior</p>

```
kill -9 <process_id>

kill -9 1234
```

<span id="3">
<p>ps:&nbsp command is used to display information about running processes on Linux. It can be used to see which processes are currently running and to get information about their resource usage</p>

```
ps aux
```

<span id="4">
<p>apt:&nbsp command is used to manage software packages on Debian and Ubuntu Linux systems</p>

```
sudo apt update
```

<span id="5">
<p>pacman:&nbsp command is used to manage software packages on Arch Linux systems. It can be used to install, update, and remove software packages</p>

```
sudo pacman -S firefox
```

<span id="6">
<p>rpm:&nbsp command is used to manage software packages on Red Hat and Fedora Linux systems. It can be used to install, update, and remove software packages</p>

```
sudo rpm -i package.rpm
```

<span id="7">
<p>cal:&nbsp command is used to display a calendar of the current month or a specified month and year on Linux</p>

```
cal 04 2023
```

<span id="8">
<p>date:&nbsp command is used to display or set the system date and time on Linux</p>

```
date +"%T %Z"
```

<span id="9">
<p>alias:&nbsp command is used to create and manage command aliases on Linux</p>

```
alias ll='ls -alF'
```
command creates an alias for the ls -alF command, so that you can use ll instead of typing out the full command

<span id="10">
<p>dd:&nbsp This command is used to copy and convert files on Linux</p>

```
dd if=/dev/sda of=image.img bs=1M
```
command creates a disk image of the entire /dev/sda disk, using a block size of 1 megabyte.

<span id="11">
<p>whatis:&nbsp  command is used to display a brief description of a command on Linux</p>

```
whatis grep
```
command displays a brief description of the grep command, which is used to search for patterns in text files

<span id="12">
<p>which:&nbsp command is used to locate the binary executable file that would be executed if you run a particular command</p>

```
which python
```

<span id="13">
<p>curl:&nbsp command is used to transfer data from or to a server, using one of several supported protocols, including HTTP, HTTPS, FTP, and others
 It can be used to download files from a server, send data to a server, or test server connectivity</p>

```
curl https://example.com/my_file.txt -o my_file.txt
```
command will download the file my_file.txt from the example.com server using HTTPS, and save it as a local file with the same name
