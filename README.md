# Quicks version 1.0
SFTP Upload Script for MacOS

This script automaticaly uploads your file to your Server via SFTP.  
Install lftp  
```
brew install lftp
```
Download the workflow and change the variables:
```HOST="XXX.XXX.XXX.XXX"
USER="Username"
PASS="Password"
```
  And also change: 
```
printf https://yourdomain.com/yourpath/$url | pbcopy
```
