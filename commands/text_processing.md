<h2>Text Processing</h2>
<br/>


|1|[grep](#1) |[nano](#2)|[cat](#3) | [vi](#7)|
|-|-----------|----------|----------|-------|
|2|[sort](#4) |[head](#5)|[tail](#6)|[less](#7)|



<span id="1">
<p>grep:&nbsp Command searches for a specific pattern or text string within a file or files</p>

<span id="2">
<p>nano:&nbsp  Text editor that allows you to create and edit files from within the terminal</p>

```
nano filename.txt
```

<span id="3">
<p>cat:&nbsp Concatenate and display the contents of one or more files</p>

``` 
cat file.txt
```
<ul>
    <li>Ctrl-O to save changes to the file you're currently editing</li>
    <li>Press Ctrl-X to exit </li>
</ul>

<span id="3">
<p>vi:&nbsp </p>

``` 
vi file.txt
```
<ul>
    <li>i - insert mode</li>
    <li>(esc) + :q! - exit </li>
    <li>(esc) + :wq! - save and exit</li>
</ul>

<span id="4">
<p>sort:&nbsp Sort lines of text</p>

```
sort file.txt
```

<span id="5">
<p>head:&nbsp Display the first few lines of a text file or output</p>

```
head -n 5 file.txt
```

<span id="6">
<p>tail:&nbsp Display the last few lines of a text file or output.</p>

```
tail -n 5 file.txt
```

<span id="7">
<p>less:&nbsp command is used to view the contents of a file on Linux, one page at a time..</p>

```
less my_file.txt
```