PhoneGap-KickStart-Guide
========================

Phonegap installation steps 

1) install node.js - http://nodejs.org/dist/v0.10.28/node-v0.10.28-x86.msi

2) install phonegap - npm install -g phonegap (If throwing error check if you are behind proxy)

3) set Proxy with the following command - 

<code>npm config set proxy http://proxy.company.com:8080</code>

<code>npm config set https-proxy http://proxy.company.com:8080</code>

&

if you have username password set

<code>npm config set proxy http://login:pass@host:port</code>

<code>npm config set https-proxy http://login:pass@host:port</code>


4) install <code>cordova - npm install -g cordova</code>

5) install ant - 

<i>Download the .zip for the binaries from http://ant.apache.org/bindownload.cgi.</i>
<i>Extract the binaries on the path C:java\ant\ where [java] and [ant] would be self created folders you can store in any directory structure of your preference.</i>
<i>Set up Environment variables with the names JAVA_HOME & ANT_HOME</i>

6) set path variable for ant

7) install android sdk

8) set path variable for android sdk pointing to platform-tools and tools

9) create a workspace for phonegap

10) Open command promp

11) Traverse to workspace folder

12) now create first app

<code>cordova create MyFirstPhoneGap com.myapp.helloworld Hello</code>

13) Traverse to project folder EX: <code>cd Hello</code>

14) set Environment for Android/IOS

<code>cordova platform add android</code>

15) To build phonegap app with Android/IOS 
<code>cordova build android</code>

16) start the emulator

17) To run Android/IOS App 

<code>cordova run android</code>

Voila, Now your first application is developed.

Open www folder in your favourite editor and start working around the index.html page to have fun for start.

 <b>Tips and Tricks</b>
 
  # Try Using http://brackets.io/ as HTML Editor


Your comments will encourage us to do more these kind of tutorials.

Soon Demo and Example will Update TODO
