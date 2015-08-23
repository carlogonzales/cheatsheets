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
+ `groupsadd [GROUPNAME]` - Add a new group
+ `usermod -G [GROUPNAME1],...,[GROUPNAMEN] [USERNAME]` - Change the list of groups the user belongs to. _Logged in as root_
+ `usermod -aG [GROUPNAME1],...,[GROUPNAMEN] [USERNAME]` - Add a user to the group. _Logged in as root_
+ `groups [USERNAME]` - Shows the list of groups the user belongs to

### Password

+ `apg` - Generate a random password

## Networking

### Firewall

+ `ufw status` - Shows the firewall status
+ `ufw status verbose` - Shows the firewall status and rules
+ `ufw status numbered` - Shows the firewall status and numbered rules
+ `ufw enable` - Enables the firewall
+ `ufw disable` - Disables the firewall
+ `ufw default allow outgoing` - Set `allow` as default to all outgoing connections
+ `ufw default allow incoming` - Set `allow` as default to all incoming connections 
+ `ufw default deny outgoing` - Set `allow` as default to all outgoing connections
+ `ufw default deny incoming` - Set `allow` as default to all incoming connections 
+ `ufw allow [PORT]/[PROTOCOL]` - Allow connections on a port on a specific protocol, e.g. `22/tcp`.
+ `ufw allow [FROM_PORT]:[TO_PORT]/[PROTOCOL]` - Allow connections an a range of port on a specific protocol, e.g. `22/tcp`.
+ `ufw allow from [IP_ADDRESS]` - Allow connections from a specific IP address.
+ `ufw deny [PORT]/[PROTOCOL]` - Deny connections on a port on a specific protocol, e.g. `22/tcp`.
+ `ufw deny [FROM_PORT]:[TO_PORT]/[PROTOCOL]` - Deny connections an a range of port on a specific protocol, e.g. `22/tcp`.
+ `ufw deny from [IP_ADDRESS]` - Deny connections from a specific IP address.