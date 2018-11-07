# QR Code Scanner

To get started follow [the guide](https://cordova.apache.org)

So this is what i've done in short :

`$cordova create scanner biz.aldaffah.scanner Scanner`

Because i am an android user

`$cordova platform add android`

`$cordova plugin add barecode-scanner`

Then i've got the project running and displaying the index.html default page

After some Q/A in the cordova slack i've got something working with [this repo](https://github.com/phonegap/phonegap-plugin-barcodescanner)

So the only thing you have to do if you understand why you should use phonegap-plugin-barcodescanner instead of barecode-scanner is to copy the content of the www folder of this repo into the one you got after running the commands
