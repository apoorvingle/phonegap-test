Phonegap Test Application
=========================

Setting up your development environment
+ install apache-ant
    - `sudo apt-get install apache-ant`
+ install nodejs server [Installing nodejs and npm](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-an-ubuntu-14-04-server)
    - `sudo apt-get update && sudo apt-get install nodejs npm`
+ install cordova [Installing phonegap cordova](http://docs.phonegap.com/en/edge/guide_cli_index.md.html#The%20Command-Line%20Interface) 
    - `npm install cordova -g`
+ [install android-sdk](http://developer.android.com/sdk/installing/index.html)

Getting the sample code
+ clone this repository in your workspace directory 
    - `git clone https://github.com/apoorvingle/phonegap-test.git`
+ change your directory to the hello working directory
    - `cd hello`
+ add android platform to your project
    - `cordova platform add android`
+ build the project to create an apk
    - `cordova build`
+ test your application 
    - on an emulator by `cordova emulate android`
    - on an actual device connected using adb `cordova run android`

+ all your application html, js, css, images etc files would be in `www/` folder
+ __Do not change__ any other files other than files in `www/` unless you are 100%
  sure what you are doing.

###### Cheers!

