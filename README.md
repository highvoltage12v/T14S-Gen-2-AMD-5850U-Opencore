This is an updated OpenCore Folder for the thinkpad T14S Gen 2 AMD 5850U. Currently using Mac OS Sonoma for Intel wireless support (AX210) Sequoia would work if a correct Broadcom card was used with IOSurface patches. 

Change your SMBIOS to MacBookPro16,3, add your System Serial Numer and save this info to config.plist

Currently NootedRed for GPU support has issues with Metal support to use Applications such as chrome 
GPU rasterization must be turned off you must start chrome without GPU rendereing go to flags and disable rasterization 
open -a Google\ Chrome --args --disable-gpu


Working:
Power Management Sleep/Wake/Lid/Battery Status
Modified Trackpad VoodooI2C Trackpad Support. No touch screen. Trackpoint Nub
USB ports correctly mapped
Wireless working when Realtek card is swapped for Intel/Broadcom 
Audio
Webcam
Functions keys toggled via FN key 
NVMEFix/Trim Support 
