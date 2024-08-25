# Android Debloater

This is a program that uses Android Debug Bridge (ADB) to debloat a phone to basically bare android, with not a lot of apps left.

## Install ADB

Windows: [Download Link](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)

MacOS: [Download Link](https://dl.google.com/android/repository/platform-tools-latest-darwin.zip)

Ubuntu/Debian:
```sudo apt-get install adb fastboot```

Fendora:
```sudo dnf install android-tools```

Arch Linux:
```sudo pacman -S android-tools```

RedHat/CentOS/Rocky:
```sudo yum install adb fastboot```

Alpine Linux:
```sudo apk add adb fastboot```

OpenSUSE:
```sudo zypper install adb fastboot```

## How to run:

### Windows

1. Download the Latest Windows file from [Releases](https://github.com/W1ldAustin/android-debloater/releases)
2. Download the latest ADB version and put the Windows Debloater file into the same folder as Platform Tools (which has ADB inside of it)
3. Open up Command Prompt/Terminal and go to the folder of the Download
4. Run the command ```adb start-server```
5. Plug your phone into your PC and authorize the phone to the computer. If it does not prompt you to authorize the device, make sure ADB is enable under Developer Options > USB Debugging. If Developer Mode is not enabled, go to About and click on Build Number until it says Developer Mode is enabled
6. Type in ```.\Android_Debloater.bat``` into the Command Prompt/Terminal and let it run.

### Linux
1. Download the Latest Linux file from [Releases](https://github.com/W1ldAustin/android-debloater/releases)
2. Open up the Terminal and change the directory to the folder the file is in (normally Downloads)
3. Run the commands for your Linux system to install ADB
4. Make the file executable by running the following command: ```sudo chmod a+x Android_Debloater.sh```
5. Run the Command ```adb start-server```
6. Plug the phone into the computer and authorize the phone to the computer. If it does not prompt you to authorize the device, make sure ADB is enable under Developer Options > USB Debugging. If Developer Mode is not enabled, go to About and click on Build Number until it says Developer Mode is enabled
7. Run the file by running ```./Android_Debloater.sh```

## Want to me to update the bloatware list?
I only know what bloatware to add if I am either told or it is on one of my personal android devices. If you would like to help the project and let me know what I need to add, make an issue with a list of apps that the debloat script did not get and I will add it when I can.
