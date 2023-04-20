<h2>User Management</h2>

|1|[useradd](#1)|[passwd](#2)|[su](#3)|
|-|-----------|---------|----------|
|2|[chown](#4)|[usermod](#5)|[userdel](#6)|


<span id="1">
<p>useradd:&nbsp command is used to create a new user account on a Linux system. By default, the command creates a new user account with a home directory, shell, and group membership</p>

```
useradd newuser
```

<span id="2">
<p>passwd:&nbsp command is used to set or change the password for a user account on a Linux system. By default, the command prompts the user to enter a new password</p>

```
passwd newuser
```

<span id="3">
<p>su:&nbsp command is used to switch to another user account on a Linux system. By default, the command switches to the root user account, but it can be used to switch to any other user account if the user has the correct permissions</p>

```
su newuser
```

<span id="4">
<p>chown:&nbsp command is used to change the ownership of a file or directory on a Linux system. It can be used to change the owner of a file to another user account or group, as well as to change the group ownership of a file</p>

```
chown newuser file.txt
```

<span id="5">
<p>usermod:&nbsp command is used to modify user accounts on a Linux system. It can be used to change a user's home directory, shell, group membership, and other account settings</p>

```
usermod -aG sudo newuser

```

<span id="6">
<p>userdel:&nbsp command is used to delete a user account on a Linux system. By default, the command removes the user's home directory and mailbox</p>

```
userdel newuser
```