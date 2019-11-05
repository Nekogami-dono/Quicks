# Quicks version 1.0
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/nekogami-dono/quicks)

SFTP Upload Script for MacOS

This script automaticaly uploads your file to your Server via SFTP.
## Install Guide
First of all install lftp!  
```
$ brew install lftp
```
Start Automator, based in /Applications/  
Create a new Automator document and then choose quick action  
1. Drop Down choose file or folder  
2. Drop down choose Finder  
Then add a shell script from the sidebar search for shell  
and change the right drop down from argument to stdin!
![Service](https://raw.githubusercontent.com/Nekogami-dono/Quicks/master/service.png)

After that Download the source and change the variables:
```
HOST="XXX.XXX.XXX.XXX"
USER="Username"
PASS="Password"
```
  And also change: 
```
cd /your/upload/path
printf https://yourdomain.com/yourpath/$url | pbcopy
```
Paste it in the Shell Box and safe it.
Now you can execute the script with right click quickaction "Quicks"  
## Add a Shortcut
System Preferences -> Keyboard -> Shortcut -> services -> Files and Folder -> Quicks
