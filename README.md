NUKE - The Fuc***g Android Remote Addmin tool

A cloud based remote android managment suite, Runs with node js

Features : 

1.GPS Logging
2.Microphone Recording
3.View Contacts
4.SMS Logs
5.Send SMS
6.Call Logs
7.View Installed Apps
8.View Stub Permissions
9.Live Clipboard Logging
10.Live Notification Logging
11.View WiFi Networks (logs previously seen)
12.File Explorer & Downloader
13.Command Queuing
14.Built In APK Builder
15.Prerequisites
16.Java Runtime Environment 8
17.See installation for OS specifics

NodeJs A Server Installation:

Install JRE 8 (We cannot stress this enough USE java 1.8.0 ANY issues that dont use this will be closed WITHOUT a response)

Debian, Ubuntu, Etc
sudo apt-get install openjdk-8-jre
Fedora, Oracle, Red Hat, etc
su -c "yum install java-1.8.0-openjdk"


install PM2

npm install pm2 -g
Download and Extract the latest release from HERE

Now Download Nuke.zip and extract it; 

# In the extracted folder, run these commands

1.npm install 
2.pm2 start index.js 
3.pm2 startup 

# Set a Username & Password.

Stop Nuke : 
Commands

1.pm2 stop index
2.Open maindb.json in a text editor
under admin
set the username as plain text
set the password as a LOWERCASE MD5 hash
save the file
run pm2 restart all
in your browser navigate to http://<your local ip>:1510
  
  Do it ::::
