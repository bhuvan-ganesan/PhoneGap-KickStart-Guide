PhoneGap-KickStart-Guide
========================

Phonegap installation steps 

1) install node.js - http://nodejs.org/dist/v0.10.28/node-v0.10.28-x86.msi

2) install phonegap - npm install -g phonegap (If throwing error check if you are behind proxy)

3) set Proxy with the following command - 

npm config set proxy http://proxy.company.com:8080
npm config set https-proxy http://proxy.company.com:8080

&

if you have username password set
npm config set proxy http://login:pass@host:port
npm config set https-proxy http://login:pass@host:port


4) install cordova - npm install -g cordova

5) install ant - 

6) set path variable for ant

7) install android sdk

8) set path variable for android sdk pointing to platform-tools and tools

9) create a workspace for phonegap

10) Open command promp

11) Traverse to workspace folder

12) now create first app

cordova create MyFirstPhoneGap com.myapp.helloworld Hello

13) Traverse to project folder

14) set Environment 
cordova platform add android

15) cordova build android

16) start the emulator

17) cordova run android

Voila, Now your first application is developed.

Open www folder in your favourite editor and start working around the index.html page to have fun for start.

Your comments will encourage us to do more these kind of tutorials.

Soon Demo and Example will Update TODO
