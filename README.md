# How-To-Use-Metasploitable-DVWA-On-Android

How To Use Metasploitable (DVWA,Mutillidae,BWAPP) On Android

In this post am going to tell you how to use DVWA, BWAP, Mutillidae Web Applications on your Android smartphone in a simple step by step procedure.
let’s Start…

first we need a web server, that supports PHP and Mysql.

you can found it on google play
https://play.google.com/store/apps/details?id=com.sylkat.apache

install the app and open it then start apache2 service
and creat  folder in internal or external storage
Download the DVWA 
https://dvwa.co.uk/
and extracr to the folder we had created  it

Open the folder and rename ‘DVWA-master’ to ‘dvwa’ 

And Open your Browser then type 127.0.0.1/dvwa

It will show this type of error “DVWA System error – config file not found. Copy config/config.inc.php.dist to config/config.inc.php and configure to your environment.”

A filename ‘config.inc.php.dist ‘ rename it to ‘config.inc.php’ it will be available in
 folder\dvwa\config

Now, again type ‘127.0.0.1/dvwa’ in the URL of the browser,

Click on ‘Create/Reset Database’

It will show this type of error
image.png
Then open it in any text editor and in the password tab , clear the password or make the password empty by remove the default password and give username as root. (its user database user id, password).

Now, again click on ‘Create / Reset Database’

You will see this type of output,
image.png
Click on ‘Login’ or it will automatically redirect to the login page,

The default username is ‘admin’ and the password is ‘password’.

Great, you successfully installed DVWA in your android
