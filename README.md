# Rom-old
The roms of the essential products ph-1 before

## Android 11
Vendor : [QQ1A.200105.088.img](https://storage.googleapis.com/essential-static/vendor-QQ1A.200105.088.zip)
##### WARNING: This image is building for the Android 11 of the Essential Products PH-1 by Essetial Official.You can use this to develop a new line by yourself or developers.We can provide support but update (The update will be build in January 2020). Thanks for use!

## Android 10
* February 2020 Release | Q 10 - Q Release 6 - QQ1A.200105.032
Download : [OTA](https://storage.googleapis.com/essential-static/PH1-OTA-QQ1A.200105.032.zip) | [Image](https://storage.googleapis.com/essential-static/PH1-Images-QQ1A.200105.032.zip)
* January 2020 Release | Q 10 - Q Release 5 - QQ1A.200105.007
Download : [OTA](https://storage.cloud.google.com/essential-static/PH1-OTA-QQ1A.200105.007.zip) | [Image](https://storage.cloud.google.com/essential-static/PH1-Images-QQ1A.200105.007.zip)
* December 2019 Release | Q 10 - Q Release 4 - QQ1A.191205.017
Download : [OTA](https://storage.googleapis.com/essential-static/PH1-OTA-QQ1A.191205.017.zip) | [Image](https://storage.googleapis.com/essential-static/PH1-Images-QQ1A.191205.017.zip)
* November 2019 Release | Q 10 - Q Release 3 - QP1A.191005.014
Download : [OTA](https://storage.googleapis.com/essential-static/PH1-OTA-QP1A.191005.014.zip) | [Image](https://storage.googleapis.com/essential-static/PH1-Images-QP1A.191005.014.zip)
* October 2019 Release | Q 10 - Q Release 2 - QP1A.190711.148
Download : [OTA](https://storage.googleapis.com/essential-static/PH1-OTA-QP1A.190711.148.zip) | [Image](https://storage.googleapis.com/essential-static/PH1-Images-QP1A.190711.148.zip)
* September 2019 Release | Q 10 - Q Release 1.5 - QP1A.190711.122(Open Market)
Download : [OTA](https://storage.googleapis.com/essential-static/PH1-OTA-QP1A.190711.122.zip) | [Image](https://storage.googleapis.com/essential-static/PH1-Images-QP1A.190711.122.zip)
* September 2019 Release | Q 10 - Q Release 1 - QP1A.190711.107(Telus)
Download : [OTA](https://storage.googleapis.com/essential-static/PH1-OTA-QP1A.190711.107.zip) | [Image](https://storage.googleapis.com/essential-static/PH1-Images-QP1A.190711.107.zip)
## Android 9
* July 2019 Release | Pie 9 - P Release 12 - PQ1A.190105.090
Download : [OTA](https://storage.googleapis.com/essential-static/PH1-OTA-PQ1A.190105.090.zip) | [Image](https://storage.googleapis.com/essential-static/PH1-Images-PQ1A.190105.090.zip)
* June 2019 Release | Pie 9 - P Release 11 - PQ1A.190105.077(Sprint)
Download : [OTA](https://storage.cloud.google.com/essential-static/PH1-OTA-PQ1A.190105.077.zip) | [Image](https://storage.cloud.google.com/essential-static/PH1-Images-PQ1A.190105.077.zip)
* May 2019 Release | Pie 9 - P Release 10 - PQ1A.190105.058
Download : [OTA](https://storage.cloud.google.com/essential-static/PH1-OTA-PQ1A.190105.058.zip | [Image](https://storage.cloud.google.com/essential-static/PH1-Images-PQ1A.190105.058.zip)
* April 2019 Release | Pie 9 - P Release 9 - PQ1A.190105.045
Download : [OTA](https://storage.cloud.google.com/essential-static/PH1-OTA-PQ1A.190105.045.zip) | [Image](https://storage.cloud.google.com/essential-static/PH1-Images-PQ1A.190105.045.zip)

#Flashing Instructions

* Set up your computer for flashing

* Download the fastboot tool from the Android SDK Platform-Tools package
Add it to your path so the flash scripts can find it
Connect your Essential phone to your computer with a USB cable
Enable unlocking
Before you can flash a new image, ensure Developer options are enabled and OEM unlocking is turned on. To do this:

Tap Settings, then tap System > About phone
Scroll to the bottom of the page, then tap Build number multiple times until you see the pop-up message “You are now a developer” (It usually takes seven taps)
Go back one screen to System, then tap Developer options
Find the option: OEM Unlocking and turn it on
Fastboot mode
Put your Essential Phone into fastboot mode by doing either of the following:

Use the ADB tool packaged above to run the command: adb reboot bootloader
Reboot your phone while holding the Volume-down button
Unlock your bootloader
NOTE: Installing the factory image will erase all information from your device. So remember to backup your phone before continuing.

Run the command: fastboot flashing unlock
Press the Volume-down button to navigate to the YES option, then press the Power button to confirm
Flash your factory image

Download the factory image to your computer
Unzip the downloaded file
Go to where you unzipped the images
For Linux / Mac OS X - Run the command: flashall.sh
For Windows - Run the command: flashall.bat
Relock your bootloader (Only if you are on stock)
After flashing, it’s a good idea to relock your bootloader for security.

Go back to fastboot mode
Run the command: fastboot flashing lock
