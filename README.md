Web-Dev-Tools
=============

This documentation introduces some useful tools for web developers.




Web remote debugging tool
* iOS
   Debugging Web Content on iOS: 
http://developer.apple.com/library/safari/#documentation/appleapplications/Reference/SafariWebContent/DebuggingSafarioniPhoneContent/DebuggingSafarioniPhoneContent.html#//apple_ref/doc/uid/TP40006515

* Android Chrome
https://developers.google.com/chrome-developer-tools/docs/remote-debugging#connect-device-via-usb
1. Install the Android SDK
2. Enable USB debugging on your device
3. On the mobile device, launch Chrome. Open Settings > Advanced > DevTools and check the Enable USB Web debugging 
./adb kill-server
./adb forward tcp:9222 localabstract:chrome_devtools_remote
* daemon not running. starting it now on port 5037 *
* daemon started successfully *



Useful tools:
Livereload: 

On Win(it's free):

1.Install:
http://feedback.livereload.com/knowledgebase/articles/67441-how-do-i-start-using-livereload-

2.use the browser extensions
http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-
