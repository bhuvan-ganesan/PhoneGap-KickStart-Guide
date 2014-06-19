PhoneGap-KickStart-Guide
========================

<b><u>Phonegap installation steps</u></b> 

1) Install node.js - http://nodejs.org/dist/v0.10.28/node-v0.10.28-x86.msi

2) Install phonegap - <code>npm install -g phonegap</code> (If throwing error check if you are behind proxy)

3) set Proxy with the following command - 

<code>npm config set proxy http://proxy.company.com:8080</code>

<code>npm config set https-proxy http://proxy.company.com:8080</code>

&

if you have username password set

<code>npm config set proxy http://login:pass@host:port</code>

<code>npm config set https-proxy http://login:pass@host:port</code>


4) Install cordova - <code>npm install -g cordova</code>

5) Install ant - 

<i>Download the .zip for the binaries from http://ant.apache.org/bindownload.cgi.</i>
<i>Extract the binaries on the path C:java\ant\ where [java] and [ant] would be self created folders you can store in any directory structure of your preference.</i>

6) Set path variable for ant

<i>To set up the variables › Right Click My Computer › Click Properties › Click Advanced system settings  › Click Environment Variables › Click Path > Add the path value in it.</i>

7) Install android sdk

8) Set path variable for android sdk pointing to platform-tools and tools as above set (6)

9) Create a workspace for phonegap

10) Open command promp

11) Traverse to workspace folder

12) Now create first Phone Gap app

<code>cordova create MyFirstPhoneGap com.myapp.helloworld Hello</code>

13) Traverse to project folder EX: <code>cd Hello</code>

14) Set Environment for Android/IOS

<code>cordova platform add android</code>

15) To build phonegap app with Android/IOS 
<code>cordova build android</code>

16) Start the emulator

17) To run Android/IOS App 

<code>cordova run android</code>

Voila, Now your first application is developed.

Open www folder in your favourite editor and start working around the index.html page to have fun for start.

 <b>Tips and Tricks</b>
 
  # Try Using http://brackets.io/ as HTML Editor


Your comments will encourage us to do more these kind of tutorials.

Soon Demo and Example will Update TODO
