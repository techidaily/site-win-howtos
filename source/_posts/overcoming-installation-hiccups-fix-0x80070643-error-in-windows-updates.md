---
title: "Overcoming Installation Hiccups: Fix 0X80070643 Error in Windows Updates"
date: 2024-08-06 13:27:44
updated: 2024-08-09 12:31:20
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming Installation Hiccups: Fix 0X80070643 Error in Windows Updates"
excerpt: "This Article Describes Overcoming Installation Hiccups: Fix 0X80070643 Error in Windows Updates"
thumbnail: https://thmb.techidaily.com/3b3b313aac4422406d268b9ec86a52f71522ac5dfd6eae7e41b861cd70dad021.png
---

## Overcoming Obstacles in NVIDIA System Installation

![Fix nvidia installer failed issue](https://images.drivereasy.com/wp-content/uploads/2016/01/Fix-nvidia-installer-failed-2.jpg)

 “_**NVIDIA Installer failed**_ ” is a common error in Windows 10\. If you get this error when you’re installing NVIDIA drivers, try the solutions we’ve listed here to fix it.

## Fixes for NVIDIA Installer failed error

* [Some quick fixes](#h-some-quick-fixes)
* [Solution 1: Update the Nvidia Driver Automatically](#h-solution-1-update-the-nvidia-driver-automatically)
* [Solution 2: Uninstall the NVIDIA app if you have it](#h-solution-2-uninstall-the-nvidia-app-if-you-have-it)
* [Solution 3: Temporarily turn off any antivirus software or firewall](#h-solution-3-temporarily-turn-off-any-antivirus-software-or-firewall)
* [Solution 4: Kill all NVIDIA processes and delete related Files](#h-solution-4-kill-all-nvidia-processes-and-delete-related-files)
* [Solution 5: Try a clean installation with DDU](#h-solution-5-try-a-clean-installation-with-ddu)

## Some quick fixes

 If the driver software installation fails, try to reboot your computer and try the driver installation again. If that falls short, try explicitly uninstalling the previous version (if any), rebooting, and then reinstalling. If it fails again, make sure that you select “**Custom** ” and check “**Perform a clean installation** ” during the driver installation.

![](https://www.drivereasy.com/wp-content/uploads/2016/01/nvidia-custom-install.png)

![](https://www.drivereasy.com/wp-content/uploads/2016/01/nvidian-clean-installation.png)

## Solution 1: Update the Nvidia Driver Automatically

 Installing an incompatible driver can cause this error. Before you move on and try further steps, try using **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  to install the driver. It’s as simple as two clicks.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making mistakes when installing.

 You can update your drivers automatically with either the [**7 days free trial**](https://tools.techidaily.com/drivereasy/download/) or the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) of Driver Easy. It takes just 2 clicks, and you get full support and a 30-day money-back guarantee with the Pro version:

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2020/10/6_0_scan-now.jpg)
3. Click the**Activate & Update** button next to the flagged device to automatically download and install the correct version of this driver.  

 Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (You’ll need the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  for this – when you select Update All, you’ll get a prompt to upgrade. If you’re not prepared to purchase the Pro version yet, Driver Easy provides a 7-day trial at no cost, granting access to all Pro features like fast downloads and easy installation. No charges will occur until after your 7-day trial period ends.)  
![](https://www.drivereasy.com/wp-content/uploads/2021/05/NVIDIA-GeForce-RTX-3090-Ti.jpg)
4. After updating, restart your computer to take effect.

## Solution 2: Uninstall the NVIDIA app if you have it

 Nvidia app and Nvidia GeForce Experience can’t co-exist with each other, so if you have the former installed on your computer, you should uninstall it first before you try the GeForce Experience installer. To do so:

1. On your keyboard, press the**Windows** key and the**I** key together to open Settings.
2. Go to**Apps** \>**Installed apps** . Find the**NVIDIA app** and**Uninstall** it.  
![](https://www.drivereasy.com/wp-content/uploads/2016/01/uninstall-nvidia-app.png)

If this still doesn’t help, please move on.

## Solution 3: Temporarily turn off any antivirus software or firewall

 Some antivirus software would block certain files, which prevents you from successfully completing your installation. For example many “Comodo” antivirus users have reported that it causes NVIDIA driver updates to fail. So if you’re running antivirus software or a firewall, your might need to turn them off during your installation. You’ll also need to make sure all their processes are turned off. You can check and kill all processes via your Task Manager.

 After installing the driver, remember to re-enable your antivirus software and firewall to help keep your PC safe.

 To temporarily disable your antivirus software and firewall, follow the steps below:

1. On your keyboard, press the**Windows logo + R keys** simultaneously to open the Run box. Type**taskmgr** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-taskmgr.jpg)
2. Select**Processes** . Then right-click on the antivirus processes that are related to your antivirus program(s) and select**End task** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-End-task.jpg)

To disable Windows firewall:

1. On your keyboard, press the**Windows logo key** and**R** at the same time to invoke the Run box. Then Type or paste**control firewall.cpl** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/run-box-firewall.jpg)
2. From the left menu, select**Turn Windows Defender Firewall on or off** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/disable-firewall-2.jpg)
3. Select**Turn off Windows Defender Firewall (not recommended)** for Domain network, Private Network and Public network. Then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/disable-firewall-3.jpg)

 After that, try installing the NVIDIA driver again. Make sure you select “**Custom** ” and check the box for “**perform clean installation** ” while installing the driver still.

 If the NVIDIA Installer failed error remains, please enable your antivirus program and Windows firewall, then move on to the next step below.

## Solution 4: Kill all NVIDIA processes and delete related Files

This is to make sure that your system state is fully reset:

1. Go to**Task Manager** . In the**Processes** tab (as instructed[here](#task) ), end all NVIDIA tasks.
2. Delete the following NVIDIA files if they exist. (Note: You might need to log in as an administrator to delete the files)  
   * C:\\Windows\\System32\\DriverStore\\FileRepository\\nvdsp.inf file  
   * C:\\Windows\\System32\\DriverStore\\FileRepository\\nv\_lh file  
   * C:\\Windows\\System32\\DriverStore\\FileRepository\\nvoclock file  
   * C:\\Program Files\\NVIDIA Corporation\\  
   * C:\\Program Files (x86)\\NVIDIA Corporation\\
3. Reboot the system, then install the driver again.Make sure you select **Custom** and check **Perform a clean installation** as you install the driver.

## Solution 5: Try a clean installation with DDU

 Another very common reason for NVIDIA Installer failed error is an outdated or faulty graphics card driver files in your computer. In this case, it’s recommended that you do a clean reinstallation of the Nvidia display card driver. To do so, DDU (Display Driver Uninstaller) is usually recommended, as it can do a pretty good job removing all the older or faulty display driver files on your computer.

To do a clean reinstallation of the display card driver with DDU:

1. Download and search for the execution file of the display card driver from the website of your GPU manufacturer **[NVIDIA](https://tools.techidaily.com/drivereasy/download/)**  .
2. Download DDU from the[**official download page**](https://www.guru3d.com/files-details/display-driver-uninstaller-download.html) . Then unzip the folder, and double-click the**DDU** file to further extract the execution file.  
![](https://www.drivereasy.com/wp-content/uploads/2024/02/ddu-3.png)
3. Boot your computer into Safe Mode as instructed here:[**Start Safe Mode using the System Configuration tool**](https://tools.techidaily.com/drivereasy/download/)
4. When in Safe Mode, go to the folder where you unzip the DDU execution file. Double-click to run**Display Driver Uninstaller** .  
![](https://www.drivereasy.com/wp-content/uploads/2024/02/ddu-2.png)
5. Select **GPU** and **your GPU manufacturer** on the right side. Then click **Clean and restart** .  
![](https://www.drivereasy.com/wp-content/uploads/2024/02/ddu-1.png)
6. Your computer should restart when the old driver files for your graphics card are cleaned.
7. Double-click the setup file for the display card driver you’ve downloaded from step 1 to run the driver installation.
8. Restart your computer afterward.

---

 That’s it! We hope these solutions have helped you get your NVIDIA installer working properly.

* [Drivers](https://tools.techidaily.com/drivereasy/download/)
* [NVIDIA](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
