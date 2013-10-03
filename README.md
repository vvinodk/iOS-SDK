iOS6-SDK
=======
This is a legacy version of Estimote SDK. Visit https://github.com/Estimote/iOS7-SDK to get the current version.

=======

To use this version of SDK in your project you should follow these three simple steps:

First, add files from the SDK folder to your project. Your files list should look somehow like this:

![ScreenShot FileList](http://estimote.com/api/FilesListScreenShot.png)

Then add the CoreBluetooth.framework to your project. 
The Link With Binary Libraries section in Build Phases of your project should contain both CoreBluetooth.framework and libEstimoteBLE.a

![ScreenShot LinkWithBinaryLibraries](http://estimote.com/api/CoreBluetoothScreenShot.png)

The last step is to import BeaconManager.h file into classes that in which it will be used.

![ScreenShot Import](http://estimote.com/api/ImportScreenShot.png)
