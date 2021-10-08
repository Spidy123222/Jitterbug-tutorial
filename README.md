# **Welcome to the JitterBug iOS Setup Page**
Jitterbug is a app that is based on libimobiledevice that is able activate a debugger to an app which allows jit. 
## How does it work?
It works in 2 different ways.

1. Via vpn (Requires a Paid Developer account or a TestFlight Version) which is used for using it on the device its running. This version is JitterBug
2. With a Second Device. This requires a seperate device that has JitterBug to activate a app on the main device (Anyone can Sign). This version is JitterBug lite

When you use jitterbug you use a Pairing File and DeveloperDiskImage to activate a debugger for jit. The normal flow of using it is you select you're desired device and tap the pairing file for it. Depending if a DeveloperDiskImage is mounted to the device it will either ask to mount after you select an app but if it does not ask it should activate the debugger for jit.

## Requirements

- DeveloperDiskImage (Has to be exact iOS or iPadOS number or closest one to it. Not all iOS versions updates it every time.)
- PairingFile (The tutorial will tell you how to obtain it)
- Altstore or Cydia Impactor or Testflight

## Obtaining Required Files

**DeveloperDiskImage:**
This has to be exact iOS or iPadOS number or closest one to it. Not all iOS versions updates it every time. Not having the right DeveloperDiskImage can make this not work because it would fail to mount. Keep in mind that You can only mount the DeveloperDiskImage 

if it doesnt already have one. If you dont know if it is already mounted yuo can go into the Settings app and scroll down and if you see a icon with a hammer and says Developer. If you see a icon and button in there then it is already mounted and dont need to be mounted again. **The DeveloperDiskImage can unmount from restarting device or full shutdown and has to be done again. If its the same ios version just remount the one you used from before.**

Download1: [https://github.com/mspvirajpatel/Xcode_Developer_Disk_Images/releases/](https://github.com/mspvirajpatel/Xcode_Developer_Disk_Images/releases/)

Download2: [https://github.com/pdso/DeveloperDiskImage/tree/master](https://github.com/pdso/DeveloperDiskImage/tree/master)


## Getting Started

