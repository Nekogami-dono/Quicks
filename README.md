# Quicks version 1.0
SFTP Upload Script for MacOS

This script automaticaly uploads your file to your Server via SFTP.
## Install Guide
First of all install lftp!  
```
brew install lftp
```
Start Automator, based in /Applications/  
Create a new Automator document and then choose Service
![Service](https://octodex.github.com/images/yaktocat.png)

Download the source and change the variables:
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
