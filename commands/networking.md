<h2>Networking</h2>

|1|[ping](#1)|[nestat](#2)   |[ifconfig](#3)  |
|-|-----------|--------------|----------------|
|2|[ssh](#4)  |[scp](#5)     |[traceroute](#6)|
|3|[wget](#7) |[iptables](#8)||


<span id="1">
<p>ping:&nbsp command is used to test the connectivity between two networked devices</p>

```
ping google.com
```

<span id="2">
<p>nestat:&nbsp command displays information about the network connections and network statistics on a Linux system. It can show active network connections, listening ports, and other network-related information</p>

```
netstat -an
```

<span id="3">
<p>ifconfig:&nbsp command displays information about the network interfaces on a Linux system. It can show the IP address, netmask, and other network-related information for each interface</p>

```
ifconfig -a
```
<span id="4">
<p>ssh:&nbsp command is used to connect to a remote system securely over an encrypted network connection. It allows a user to log in to a remote system and execute commands on that system as if they were physically present at the machine</p>

```
ssh user@192.168.0.10
```

<span id="5">
<p>scp:&nbsp command is used to securely transfer files between a local and a remote system over an encrypted network connection. It uses the same encryption technology as ssh to transfer files securely</p>

```
scp file.txt user@192.168.0.10:/home/user
```

<span id="6">
<p>traceroute:&nbsp command is used to trace the path of network packets from a source to a destination. It shows the routers that the packets traverse along the way and the time it takes for the packets to reach each router</p>

```
traceroute google.com
```

<span id="7">
<p>wget:&nbsp command is used to download files from the Internet. It can download files using various protocols such as HTTP, HTTPS, and FTP</p>

```
wget http://example.com/file.zip
```
<span id="8">
<p>iptables:&nbsp command is used to configure the firewall on a Linux system. It can be used to block or allow network traffic based on various criteria such as source IP address, destination IP address, protocol, and port number</p>

```
iptables -A INPUT -s 192.168.0.10 -j DROP

```