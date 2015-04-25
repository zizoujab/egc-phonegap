Welcome to EGC phonegap tutorial!
===================


This repo contains assets for a login page with ajax , Used technologies are  **phonegap** and **jQuery Mobile**. 

Login is done using this url : [disycs.com/egc/login.php?username=zizoujab&password=zizoujab](disycs.com/egc/login.php?username=zizoujab&password=zizoujab) 
for zizoujab as username and password you will get an **Ok** response , for other values you will get a **KO** response. 

Installation
-------------
Before starting you need to be sure that you have cordova set up. 
Execute cordova -v in terminal/cmd , if you get current version then you are ok.
```sh
cordova -v 
5.0.0
```

If you dont get the version , install and configure cordova ( [http://phonegap.com/install/](http://phonegap.com/install/) ) 

###Steps to set up the project

```sh
cordova create hello enis.egc.training Hello
``` 
A project skeleton will be generated

Then get the content of this repo ( by cloning it or downloading as a zip file ) and copy it in  **hello/www** folder.

```sh
cd hello
cordova add platform android 
```
A folder named **android** will be added to **platforms**
```sh
cordova build android
```
Android Project will be built 
```
cordova run android
```

You will get and android app running in the emulator/device containing a login page 

