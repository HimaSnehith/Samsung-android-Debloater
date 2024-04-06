***Disclaimer***
I always double check what you are removing, I am not responsible for anything that happens to your mobile :)


Debloat Samsung Android Phones with Android Debug Bridge (ADB)
This repository contains a list of Android Debug Bridge (ADB) commands to aggressively disable apps/bloatware from Samsung Android devices that don't normally display an option to remove them.
Running all commands listed in commands.txt will disable almost all Samsung apps. This includes the Galaxy App Store, Samsung Themes, Samsung Dex, Samsung Bixby, Facebook, and more. The end result will be a minimalist Samsung phone. These commands will not disrupt Samsung Knox or the Google Play Store. Use at your own risk and read over all commands to make sure you don't take out something you need. While these commands cannot harm your device, there may be situations where your phone gets into a crash-loop and the easiest fix is to boot the device into "Recovery Mode" and perform a factory reset. Research the procedure to boot into recovery mode for your Samsung phone, it can differ between models.


Instructions to install the required software:(For advanced or Nerd people)
And (noobs scroll down where everything is spoon feeded....)
The following instructions assumes you are familiar with using a command-line interface. Further reading on ADB can be found here: https://developer.android.com/studio/command-line/adb#Enabling.

**(Recommended for stability) Backup, update, and factory reset your phone.**
1. On your phone, enable Android's "Developer Options"
2. In "Developer Options", turn on "USB Debugging"
3. On your computer, download Android SDK Platform-Tools for your OS.
4. Extract Android SDK Platform-Tools and start a command-prompt/shell session in the extracted folder's directory.
5. Connect your Samsung Android phone to your computer with USB debugging enabled. Verify that adb sees your device and the daemon is running with the following command
6. adb devices
7. You should see the device name listed as a "device".
8. At this point your device should prompt you to accept USB debugging from your computer. Tap "Allow".

9. Enter your device's shell with the following command
10. adb shell
Once in the device's shell, copy and paste all desired commands from safetoremovepackages.txt to remove the package.(Which is in txt fromat can be downloadd above).

The tool required to unistall these packages is **universal android deloater**
where only 2 files in the bottom are required to download.(uad_gui-windows and uad_gui-windows-opengui)
you can run anyofthese one is the spare os the other.

Instructions to install the required software:(For Noobs or beginners):
I'll provide you a folder named 'bloatware rem' in the main brach section where you just need to dowwnload and run the abouve commands :)
same follow the above commands above from where the android directory and the debloater apps are already present in the folder given 
just run these apps uad_gui-windows or uad_gui-windows-opengui.
and follow the safetoremovepackages.txt which are all safe to remove based on you uses.

