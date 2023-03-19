#  Linux Commands
## Genral use linux commands


<span id="top">Linux commands</span>


|1 | [ls](#1)  | [cat](#20)   | [top](#21)     | [iptables](#31) | [df](#40)     |
|--|-----------|--------------|----------------|-----------------|---------------|
|2 | [cd](#2)  | [head](#11)  | [kill](#22)    | [hostname](#32) | [uptime](#41) |
|3 | [pwd](#3) | [tail](#12)  | [ping](#23)    | [whoani](#33)   | [date](#42)   |
|4 | [cp](#4)  | [find](#13)  | [ssh](#24)     | [su](#50)       | [cal](#43)    |
|5 | [mv](#5)  | [tar](#14)   | [ftp](#25)     | [sudo](#34)     | [clear](#44)  |
|6 | [rm](#6)  | [gzip](#15)  | [curl](#26)    | [passwd](#35)   | [exit](#45)   |
|7 |[mkdir](#7)| [chmod](#16) | [wget](#27)    | [history](#36)  | [scp](#46)    |
|8 |[rmdir](#8)| [chown](#17) | [ifconfig](#28)| [which](#37)    | [less](#47)   |
|9 |[touch](#9)| [chgrp](#18) | [nestat](#29)  | [man](#38)      | [du](#48)     |
|10|[nano](#10)| [ps](#19)    | [route](#30)   | [apropos](#39)  | [gunzip](#49) |

<br>


- [Navigation Commands](#nav)
- [File Management](#fs)
- [Text Processing](#tp)
- [System Information](#sf)
- [Networking](#nw)
- [User Management](#um)
- [other](#o)

<span id='nav'>Navigation Commands<span>
<br>
<ol>
<li>
<span id="1">
<p>ls: List files and directories in the current directory
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
<li> <span id="2">cd: Change directory</span> 
<ul>
 <li>cd [Dirctoryname] :Into Directory.we can use <strong>cd dir1/dir2 </strong> to get in child directory</li>
 <li>cd .: get out of directory.<strong> cd ../..  </strong> to get out of child directory</li>
 <li>cd - : This option changes the current directory to the previous directory you were in</li>
 <li>cd ~ : This option changes the current directory to your home directory.</li>
 <li>cd / : This option changes the current directory to the root directory.</li>
</ul>
</li>
<li> <span id="3">pwd: Print Working Directory</span> </li>
      print Current Working directory
</ol>

<p align='right'><a href="#top">&#8593; Back to Top</a></p>

<span id='fs'>File Management<span>
<ol>
<li><span id="7">mkdir</span></li>
<li><span id="8">rmdir</span></li>
<li><span id="9">touch</span></li>
<li><span id="6">rm :</span> This command is used to remove a file or directory. Use it with caution, as it permanently deletes the file or directory</li>
<li><span id="4">cp</span></li>
<li><span id="5">mv</span></li>
<li><span id="16">chmod</span></li>
<li><span id="">in</span></li>
<li><span id="">find</span></li>
<li><span id="">tar</span></li>
<li><span id="">gzip</span></li>
<li><span id="">cmp</span></li>
<li><span id="">zip</span></li>
<li><span id="">unzip</span></li>
<li><span id="">mount</span></li>
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



