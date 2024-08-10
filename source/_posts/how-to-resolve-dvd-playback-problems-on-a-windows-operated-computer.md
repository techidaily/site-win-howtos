---
title: How to Resolve DVD Playback Problems on a Windows-Operated Computer
date: 2024-08-07 10:48:33
updated: 2024-08-09 11:14:45
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Resolve DVD Playback Problems on a Windows-Operated Computer
excerpt: This Article Describes How to Resolve DVD Playback Problems on a Windows-Operated Computer
thumbnail: https://thmb.techidaily.com/0637330b995d15dd54d33a9215c8a5f8a705636812bbbbc0bf18d5302643fdc0.jpg
---

## How I Resolved the Prolonged Shutdown Problem on My Windows 10 PC

After a day’s work, you click**Shut down** and pack your stuff for leaving. But when you glance at your computer screen, it’s still on the loading screen. You stand and watch it impatiently. Usually, the shutdown process should be taken no more than a few seconds. But when it takes you a lot of time while shutting down, your computer has Windows 10 slow shutdown issue.  
 Don’t worry, you’re not alone. And this issue should be easy to fix.

## Try these fixes

1. [**Disconnect your USB-C device before shut down**](https://tools.techidaily.com/drivereasy/download/)
2. [**Run Power Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
3. [**Disable Fast Startup feature**](https://tools.techidaily.com/drivereasy/download/)
4. [**Repair system files**](https://tools.techidaily.com/drivereasy/download/)
5. [**Registry fix**](https://tools.techidaily.com/drivereasy/download/)

### Fix 1: Disconnect your USB-C device before shut down

![](https://images.drivereasy.com/wp-content/uploads/2019/08/619Rf5BkGlL._SL1273_-1019x1024.jpg)

 USB Type-C sample  
 Photo from Amazon

 Microsoft has confirmed that there’s a new bug which will affect your computer shut down process slowly. The bug in the USB Type-C Connector System Software Interface (UCSI) software may cause a 1 minute delay for Windows 10 to shut down.

**Note** : This bug only affects with Windows shut down, won’t influence normal functionality on your computer. And it will work normally after restarting the system.

The solution for this bug is very simple.

 Disconnect your USB Type-C devices before you shut down your computer. So this bug won’t affect your shutdown process.

### Fix 2: Run Power Troubleshooter

 Windows has built-in troubleshooter to fix some common errors. You can try Power Troubleshooter to fix the slow shut down issue.

1. Press the**Windows logo key + I** to open**Settings** .
2. Click**Update & Security** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/2-3.jpg)
3. Choose**Troubleshoot** in the left pane. Then click**Power** and click**Run the troubleshooter** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/power-1.jpg)
4. Follow the on-screen instructions to finish the process.
5. Reboot your computer to apply the changes.

### Fix 3: Disable Fast Startup feature

 If your Fast Startup is enabled, when you shut down the computer, you may encounter slow shutdown or back to the Windows Lock Screen.  
 Fast Startup is supposed to reduce startup time by pre-loading some boot information before your PC shuts off. But when it’s enabled and you shut down the computer, all sessions logged off and the computer enters hibernation. This feature may slow down shutdown speed for your computer.  
 To solve it, you can simply disable the Fast Startup.

1. Press the **Windows logo key + Pause** and click **Control Panel Home** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/07/0-1.jpg)
2. Change **View by Large icons** and click **Power Options** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/07/1-11.jpg)
3. Click **Choose what the power button do** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/07/2-9.jpg)
4. Click **Change settings that are currently unavailable** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/07/3-8.jpg)
5. Make sure you uncheck **Turn on fast startup (recommended)** . Then click **Save Changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/07/4-7.jpg)
6. Reboot your computer to apply the changes.

### Fix 4: Repair system files

 The corrupted system file will let the system take more time to shut down your computer. To solve it, you can use System File Checker (SFC) to repair the broken system files.

1. On your keyboard, press the **Windows logo key** and **R** key at the same time to invoke the Run box.
2. Type “cmd” and press **Shift** +**Ctrl** +**Enter** together to open Command Prompt in the administrator mode.  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/command-prompt-1.jpg)  
**Note** : Do **NOT** click OK or just press the Enter key as that won’t allow you to open Command Prompt in the administrator mode.
3. Type “sfc /scannow” in the window and press **Enter** . Then wait for the verification is 100% complete.  
![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap4.jpg)
4. Reboot your computer to check the changes.

 If the result indicates that there are broken files exists but SFC can’t fix it, you can turn to Deployment Image Servicing and Management (DISM) Tool for deeper examine and repair.  
 Click [here](https://tools.techidaily.com/drivereasy/download/) for a tutorial on how to use the DISM Tool.

### Fix 5: Registry fix

 If the above fixes can’t help, you can try this one. The corruption of registry files may the reason for the slow shut down issue. You can solve the issue by following the below steps:

1. Press the**Windows logo key + R** to open the Run box.
2. Type “regedit” and press**Enter** to open**Registry Edition** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/registry.jpg)
3. Copy and paste the text into the address bar and press**Enter** .  
 “ **Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Session Manager\\Memory Management** “.
4. Double-click**ClearPageFileAtShutdown** , change the value to**0** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/shut.jpg)
5. Copy and paste the text into the address bar and press Enter.  
 “ **Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control** “.
6. Find**WaitToKillServiceTimeout** file in the right pane. Double click it and set the value between**1000 to 20000** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/shut1.jpg)
7. Click**OK** .
8. Reboot your computer to apply the changes.

## Bonus: Update your driver

 If there’re any old or corrupted drivers on your Windows 10 PC, this will cause trouble to your computer. To get a better-using experience and prevent your computer from trouble, it’s important to keep your device drivers up-to-date.

 You can do this manually by downloading the latest drivers from the devices’ manufacturer official website. This will take time and need a litter computer knowledge. If you want to save some time or not confident with drivers, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  to do it automatically.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click Scan Now button. Driver Easy will then scan your computer and detect any problem drivers. You sound driver is no exception.  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/NVIDIA-18.jpg)
3. Click **Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All).  
**Note** : You can do it for free if you like, but it’s partly manual.  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/NVIDIA-Geoforce.jpg)
4. Reboot your Windows 10 computer and check the issue.

 Hopefully, the above methods can help you to fix your problem. If you have any suggestions or questions, feel free to leave your comments below.

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
