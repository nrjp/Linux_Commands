#  Linux Commands
## Genral use linux commands


<span id="top">Linux commands</span>


|1 | [ls](#1)     | [cat](#20)   | [top](#21)     | [iptables](#31) | [df](#40)     |
|--|--------------|--------------|----------------|-----------------|---------------|
|2 | [cd](#2)     | [tar](#11)   | [kill](#22)    | [hostname](#32) | [uptime](#41) |
|3 | [pwd](#3)    | [gzip](#12)  | [ping](#23)    | [whoani](#33)   | [date](#42)   |
|4 | [mkdir](#4)  | [cmp](#13)   | [ssh](#24)     | [su](#50)       | [cal](#43)    |
|5 | [rmdir](#5)  | [tar](#14)   | [ftp](#25)     | [sudo](#34)     | [clear](#44)  |
|6 | [touch](#6)  | [gzip](#15)  | [curl](#26)    | [passwd](#35)   | [exit](#45)   |
|7 | [rm](#7)     | [chmod](#16) | [wget](#27)    | [history](#36)  | [scp](#46)    |
|8 | [cp](#8)     | [chown](#17) | [ifconfig](#28)| [which](#37)    | [less](#47)   |
|9 | [mv](#9)     | [chgrp](#18) | [nestat](#29)  | [man](#38)      | [du](#48)     |
|10| [chmod](#10) | [ps](#19)    | [route](#30)   | [apropos](#39)  | [gunzip](#49) |

<br />


- [Navigation Commands](#nav)
- [File Management](#fs)
- [Text Processing](#tp)
- [System Information](#sf)
- [Networking](#nw)
- [User Management](#um)
- [other](#o)

<br/>

<span id='nav'><b>Navigation Commands</b><span>
<br>
<ol>
<li>
<span id="1">
<p>ls:&nbsp List files and directories in the current directory
 ls can be use with different options
  <ul>
    <li>-a : Lists all files including hidden files </li>
    <li>-A : Lists all files including hidden files but excludes the(current directory) and .. (parent directory) directories</li>
    <li>-l : Displays the long format listing that includes file permissions, ownership, size, date, and time</li>
    <li>-h : Displays file sizes in human-readable format (e.g., KB, MB, GB)</li>
    <li>-r : Lists files in reverse order</li>
    <li>-R : Lists files recursively in subdirectories</li>
    <li>-t : Lists files sorted by modification time, with the newest files first</li>
    <li>-x : Lists files sorted by modification alphabetically</li>
    <li>-s : Displays the file size in blocks</li>
    <li>-1 : Lists files in a single column format</li>
    <li>-u : Lists files sorted by access time, with the newest accessed files first</li>
    <li>-F : Add a / at end.it will help you to distinguish directories from files.</li>
    <li>-m : Show the files and  directories separated by a comma</li>
    <li>-Q : add quotation marks to all directories and file</li>
    <li>-la : Lists all files including hidden files with user, size of the file, and date and time </li>
    <li>--color : Enables colorized output to distinguish between file types and permissions</li>
    <li>--group-directories-first : Lists directories before files</li>
  </ul>
  we can also use combination of options with ls command

</span> 
</li>

<br/>

<li> <span id="2">cd:&nbsp Change directory</span> 
<ul>
 <li>cd [Dirctoryname] :Into Directory.we can use <strong>cd dir1/dir2 </strong> to get in child directory</li>
 <li>cd .: get out of directory.<strong> cd ../..  </strong> to get out of child directory</li>
 <li>cd - : changes the current directory to the previous directory you were in</li>
 <li>cd ~ : changes the current directory to your home directory.</li>
 <li>cd / : changes the current directory to the root directory.</li>
</ul>
</li>

<br/>

<li> <span id="3">pwd:&nbsp Print Working Directory</span> </li>
      print Current Working directory
</ol>

<br/>

<p align='right'><a href="#top">&#8593; Back to Top</a></p>

<span id='fs'><b>File Management</b><span>
<ol>
<li><span id="4">mkdir</span>:&nbsp Create a new directory.</li>
<br/>
<li><span id="5">rmdir</span>:&nbsp Remove empty directories.</li>
<br/>
<li><span id="6">touch</span>:&nbsp Create a new empty file.
  <ul>
    <li>touch [filename]:creates a new empty file with the specified name.</li>
    <li>we can use touch to create multiple files touch [filename1] [filename1] [filename1] .....</li>
  </ul>
</li>
<br/>
<li><span id="7">rm</span>:&nbsp Remove files and directories.
  <ul>
    <li>rm [filename]: Removes the specified file.</li>
    <li>rm -r [directoryname]: Removes the specified directory and its contents recursively.</li>
    <li>rm -f filename/directoryname: Removes the specified file or directory forcefully, without prompting for confirmation</li>
    <li>rm -i [filename/directoryname]: Prompts for confirmation before removing the specified file or directory</li>
    <li>rm -v [filename/directoryname]: Displays a message for each file or directory that is removed, showing the name of the file or directory.</li>
  </ul>
  Note : The rm command can be very dangerous if used incorrectly. Be very careful when using the -r or -f options, as they can delete files and directories recursively without asking for confirmation.
</li>
<br/>
<li><span id="8">cp</span>:&nbsp copy files and directories
  <ul>
    <li>cp [source] [destination]: Copies the source file to the destination.</li>
    <li>cp -i [sourcefile] [destination]: Prompts for confirmation before overwriting an existing file.</li>
    <li>cp -v [sourcefile] [destination]: Displays a message for each file or directory that is copied, showing the name of the file or directory.</li>
  </ul>
</li>
<br/>
<li><span id="9">mv</span>:&nbsp move or rename files and directories
  <ul>
    <li>mv [sourcefile] [destinationfile]: Moves or renames the source file to the destination file.</li>
    <li>mv -i [sourcefile/directory] [destinationfile/directory]: Prompts for confirmation before overwriting an existing file</li>
    <li>mv -v [sourcefile/directory] [destinationfile/directory]: Displays a message for each file or directory that is moved, showing the name of the file or directory.</li>
  </ul>
</li>

<br/>

<li><span id="10">chmod</span>:&nbsp Change the permissions of files and directories.</li>
  <ul>
    <li>chmod +r/w/x : Add permissions to directory/file</li>
    <li>chmod -r/w/x : Add permissions to directory/file</li>
    <li>chmod ugo+rwx filename: Adds the read, write, and execute permissions to the specified file for the user, group, and others.</li>
    <li>chmod ugo-rwx filename: This option removes all permissions from the specified file for the user, group, and others</li>
  </ul>
</li>
<br>
- u:&nbsp file owner<br>
- g:&nbsp users who are members of the group<br>
- o:&nbsp All other users<br>
- a:&nbsp All users same as ugo<br>

<br/>

<b>Permissions</b>
  <ul>
    <li>r/4: The read permission allows the file to be read.</li>
    <li>w/2: The write permission allows the file to be modified.</li>
    <li>x/1: The execute permission allows the file to be executed as a program or script.</li>
    <li>-/0: The dash symbol indicates that a permission is not set.</li>
  </ul><br/>
  The permissions are displayed in the following order: owner, group, and others.<br>
  drwxr-xr-x<br />
    - d:&nbsp directory<br>
    - owner permissions:&nbsp drw - The owner has read, write, and execute permissions<br>
    - group permissions:&nbsp r-x - The group has read and execute permissions<br>
    - others permissions:&nbsp r-x- Others have read-only permission<br>
<br/>
CHMOD in Numbers<br>
 - Read and write permissions would be assigned a value of 6 (4+2)<br>
 - Read, write, and execute permissions would be assigned a value of 7 (4+2+1)<br>
 - No permissions would be assigned a value of 0<br/>
 chmod 755: - owner read, write, and execute permissions (7) and group and others read and execute permissions (5)<br>
</br>
You can view the full list of options and their descriptions by typing </br><pre>man chmod</pre>
<br>

<br/>

<!-- <li><span id="">in</span></li>
<li><span id="">find</span></li> -->
<li><span id="11">tar</span>:&nbsp Package multiple files into a single file for backup or distribution.</li>
<pre>
tar -cvf archive.tar file1  directory1
tar -czvf name-of-archive.tar.gz /path/to/directory-or-file
</pre>
<ul>
  <li>-c: create a new archive</li>
  <li>-x: extract files from an archive</li>
  <li>-r: append files to an archive</li>
  <li>-t: list the contents of an archive</li>
  <li>-u: update an archive with newer files</li>
  <li>-f: specify the name of the archive file</li>
  <li>-v: display progress while processing files</li>
  <li>-z: compress the archive using gzip</li>
  <li>-p: preserve file permissions and ownership</li>
</ul>
<br>
You can view the full list of options and their descriptions by typing <br /><pre>man tar </pre>
<br>

<br />

<li><span id="12">gzip</span>:&nbsp compress files using the gzip compression</li>
<pre>
# gzip file will create a file file.gz and delete the original file
gzip file.txt
<br>
# To compress a file and keep the original
gzip -k file.txt
<br>
# To decompress a file
gzip -d file.txt.gz
<br>
# To compress a file and write the compressed data to standard output
gzip -c file.txt > file.txt.gz
<br>
# To test the integrity of a compressed file
gzip -t file.txt.gz
</pre>
<ul>
<li>-c:&nbsp write compressed data to standard output instead of creating a new file</li>
<li>-d:&nbsp decompress a compressed file</li>
<li>-f:&nbsp force compression or decompression even if a file with the same name already exists</li>
<li>-k:&nbsp keep the original file after compression or decompression (by default, the original file is deleted)</li>
<li>-r:&nbsp compress files in a directory recursively</li>
<li>-l:&nbsp list information about a compressed file, such as compression ratio and uncompressed size</li>
<li>-r:&nbsp compress files in a directory recursively</li>
<li>-t:&nbsp test the integrity of a compressed file</li>
<li>-v:&nbsp verbose mode, display the name and percentage reduction for each file that is compressed or decompressed</li>
<li>1 to -9:&nbsp set the compression level, where -1 is the fastest and produces the largest compressed file, and -9 is the slowest and produces the smallest compressed file</li>
</ul>
<br>
You can view the full list of options and their descriptions by typing <br/><pre>man gzip </pre>
<br>
<br />

<li><span id="13">cmp</span>:&nbsp compare two files byte-by-byte and displays the differences between them</li>
<pre>
# compare two txt files
cmp file1.txt file2.txt 
</pre>
You can view the full list of options by typing<br /><pre> man cmp </pre>
<br>
<br />

<li><span id="">zip</span>:&nbsp create, modify, and extract ZIP archives</li>
<pre>
# To create zip contains file1.txt and file2.txt
zip archive.zip file1.txt file2.txt
<br>
# To add a new file file3.txt to an existing ZIP 
zip archive.zip file3.txt
</pre>
<br>
You can view the full list of options by typing<br /><pre> man zip </pre>
<br>
<br />
<li><span id="">unzip</span></li>
<pre>
# unzip file
unzip archive.zip
<br>
# To extract a specific file named file1.txt from a ZIP
unzip archive.zip file1.txt
<br>
# To extract all files to destination
unzip archive.zip -d destination
</pre>
<br>
You can view the full list of options by typing<br /><pre> man unzip </pre>
<br>
<br />

<li><span id="">mount</span>:&nbsp attach a filesystem to a directory hierarchy</li>
<pre>
# To mount a filesystem located on a device such as a USB drive
mount /dev/sdb1 /mnt/usb
</pre>
<br>
You can view the full list of options by typing <br /><pre> man mount </pre>
<br>
<br />


</pre>
</ol>

<p align='right'><a href="#top">&#8593; Back to Top</a></p>

<span id='ts'>Text Processing<span>
<ol>
<li><span id="">grep</span></li>
<li><span id="10">nano</span></li>
<li><span id="">cat</span></li>
<li><span id="">cut</span></li>
<li><span id="">sort</span></li>
<li><span id="">head</span></li>
<li><span id="">tail</span></li>
</ol>

<p align='right'><a href="#top">&#8593; Back to Top</a></p>

<span id='sf'>System Information<span>
<ol>
<li><span id="">uname</span></li>
<li><span id="21">top</span></li>
<li><span id="">sudo</span></li>
<li><span id="">history</span></li>
<li><span id="">df</span></li>
<li><span id="">du</span></li>
<li><span id="">clear</span></li>
<li><span id="">exit</span></li>
<li><span id="">free</span></li>
</ol>

<p align='right'><a href="#top">&#8593; Back to Top</a></p>

<span id='nw'>Networking<span>
<ol>
<li><span id="">ping</span></li>
<li><span id="">nestat</span></li>
<li><span id="">ifconfig</span></li>
<li><span id="">ssh</span></li>
<li><span id="">traceroute</span></li>
<li><span id="">wget</span></li>
<li><span id="">iptables</span></li>
</ol>

<p align='right'><a href="#top">&#8593; Back to Top</a></p>

<span id='um'>User Management<span>
<ol>
<li><span id="">useradd</span></li>
<li><span id="">passwd</span></li>
<li><span id="">su</span></li>
<li><span id="">chown</span></li>
</ol>

<p align='right'><a href="#top">&#8593; Back to Top</a></p>

<span id='o'>Other<span>
<ol>
<li><span id="">service</span></li>
<li><span id="22">kill</span></li>
<li><span id="22">ps</span></li>
<li><span id="">apt</span></li>
<li><span id="22">pacman</span></li>
<li><span id="22">rpm</span></li>
<li><span id="22">cal</span></li>
<li><span id="">date</span></li>
<li><span id="">alias</span></li>
<li><span id="">dd</span></li>
<li><span id="">whatis</span></li>
</ol>

<p align='right'><a href="#top">&#8593; Back to Top</a></p>



