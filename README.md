# XposedInstaller-script
![](http://i.imgur.com/cynjg4ml.png)

####*With this bash script you will be able to install Xposed without a recovery.*
  
      
##**Instructions:**

* 1 Download the proper Xposed Zip depending on your device from the official [XDA thread](http://forum.xda-developers.com/showthread.php?t=3034811) and install the Xposed apk.

* 2 Download the latest installer.bin from this repo (select English or Spanish) and place both files in the internal memory of your phone with the original name.

* 3 Your phone must be rooted with [SuperSu](https://play.google.com/store/apps/details?id=eu.chainfire.supersu&hl=es) installed (if not, root will be loosed after reboot).

* 4 Latest version of [BusyBox](https://play.google.com/store/apps/details?id=stericson.busybox&hl=es) must be installed.

* 5 Install an Android Terminal emulator like [this](https://play.google.com/store/apps/details?id=jackpal.androidterm&hl=es) one or [this](https://play.google.com/store/apps/details?id=yarolegovich.materialterminal&hl=es). You can use ADB too.

  
  
  
When all it done, open Terminal emulator and write:

**su**
  
  

Allow root permissions.

**sh /sdcard/installer.bin** or you can use this too: **sh /storage/emulated/0/installer.bin**



The script will be launched. Look at the errors, if any will appear in red. If the errors doesn't appear on the script, maybe they are in the log generated at /sdcard/Xposedinstaller.log


_If you have any troubles, contact me. I am iicc on XDA, HTCmania, 4PDA, DualSim and iicc1 on GitHub and Telegram._
