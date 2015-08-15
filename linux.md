# LINUX

## Terminal

**Keyboard Shortcuts**
+ `CTRL + l` - Clears the terminal
+ `SHIFT + PGUP` - Go up the terminal
+ `SHIFT + PGDN` - Go down the terminal

**Commands**
+ `clear` - Clears the terminal

## User Management

+ `su` - Logs in as a superuser
+ `useradd [USERNAME]` - Add new system user
+ `passwd` - Changes password of the current user
+ `passwd [USERNAME]` - Changes the password of a specific user. _Logged in as root_
+ `userdel [USERNAME]` - Remove a user from the system. _Logged in as root_
+ `userdel [USERNAME]` - Remove a user from the system and its user folder on the `/home` directory and mail spools. _Logged in as root_
+ `usermod -G [GROUPNAME1],...,[GROUPNAMEN] [USERNAME]` - Change the list of groups the user belongs to. _Logged in as root_
+ `usermod -G -a [GROUPNAME1],...,[GROUPNAMEN] [USERNAME]` - Add a user to the group. _Logged in as root_
+ `groups [USERNAME]` - Shows the list of groups the user belongs to