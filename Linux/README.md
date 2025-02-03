  WEEK 2 : DAY 1 : Linux

Linux: Linux is a free, open-source operating system (OS) based on Unix. It acts as an interface between computer hardware and software applications, managing system resources like memory, CPU, and storage.

Features of Linux:
1. Open source
2. Secure
3. Simplified updates for all installed software.
4. Multiuser

File System Hierarchy:
/home: home directory for other users.
/root: It is home directory for root user.
/boot: It contains bootable files for Linux.
/etc: It contains all configuration files.
/usr: By default software are installed in this directory.
/bin: It contains commands used by all users.
/sbin: It contains commands used by the root user.
/opt: Optional application software packages.
/dev: Essential device files.


WEEK 2 : DAY 2 : Linux
Learned some basic Linux commands:
mkdir my_folder: create a new directory
mkdir -p folder1/folder2/folder3: create nested directories
rm -r my_folder: delete a directory and its contents
mv old_name new_name: move or rename a file/directory
find /home -name "file.txt": find files by name

uptime: check system uptime
whoami: check current username
chmod 755 file.sh: change file permissions
chown user:user file.txt: change file ownership


WEEK 2 : DAY 3 : Linux

File Permissions:
r (read) → 4
w (write) → 2
x (execute) → 1

Changing Permissions:
chmod 755 filename 
chmod u+x filename 

Changing Ownership:
chown user:group filename


User Management
whoami : Show current user 
who : Show logged-in users
id : Show user ID and group ID
adduser username : Add a new user
passwd username : Change user password
usermod -aG groupname username : Add user to a group
deluser username : Delete a user
groupadd groupname: Create a group
delgroup groupname: Delete a group


