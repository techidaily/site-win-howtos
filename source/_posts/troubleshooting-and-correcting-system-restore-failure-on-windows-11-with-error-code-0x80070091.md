---
title: Troubleshooting and Correcting System Restore Failure on Windows 11 with Error Code 0X80070091
date: 2025-01-09T17:07:49.889Z
updated: 2025-01-13T17:16:01.333Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Correcting System Restore Failure on Windows 11 with Error Code 0X80070091
excerpt: This Article Describes Troubleshooting and Correcting System Restore Failure on Windows 11 with Error Code 0X80070091
thumbnail: https://thmb.techidaily.com/b5e9ddde4e68e5c468b12c2fce264f22eb978dc955e335250b1f4d060c7be8f8.jpg
---

## Troubleshooting Made Easy: Fix Windows Error Code 0xC0000098 in Minutes

 While booting your PC, Windows gives you a BSOD with the**error code** **0xc0000098** . It can be rather frustrating not being able to use your device. You just get stuck at the blue/black screen. But don’t panic. This is a most common Windows error and it’s never hard to fix it at all…

## About the error 0xc0000098

> _During the start-up process, the**Boot Configuration Data** (BCD) is very essential to provide required information to load the operating system. If the Boot Configuration Data is missing or corrupted, Windows won’t be able to load operating system and gives you the error**0xc0000098** ._

![](https://images.drivereasy.com/wp-content/uploads/2019/12/0xc0000098-windows-7.jpg)

 _Error Code**0xc0000098**_  o_n Windows 7, Vista_

![](https://images.drivereasy.com/wp-content/uploads/2019/12/0xc0000098.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 _Error Code**0xc0000098**_  o_n Windows 10, 8, 8.1_

## Try these fixes

 Below you will get to know all possible fixes to solve your boot error 0xc0000098\. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. **[Rebuild BCD manually](#f1)**
2. **[Try Startup Repair](#f2)**
3. **[Perform a CHKDSK](#f3)**
4. **[Run System File Checker](#f4)**
5. **[Use a Windows Reimage Tool](#fix-reimage)**
6. **[Perform a clean install of Windows](#f5)**

### Fix 1: Rebuild BCD manually

 Since this is a BSOD error, you won’t be able to access your PC normally. To repair your PC, you’ll need to use a Windows recovery drive: an installation USB media or a CD/DVD.

#### Step 1: Prepare installation media

 If you don’t have one, you need to create USB/DVD bootable media yourself. Here is how to do it:

**Note:** You can skip to Step 2 if you already have a (DVD/USB) installation media.

 1) Go to **[Windows 10 download](https://www.microsoft.com/en-us/software-download/windows10)**  page. (Or **[Windows 11](https://www.microsoft.com/software-download/windows11) ,** [Windows 8](https://www.microsoft.com/en-us/software-download/windows8ISO) ,[**Windows 7**](https://www.microsoft.com/en-us/software-download/windows7) )

![](https://images.drivereasy.com/wp-content/uploads/2020/01/download-win-10-1.jpg)

2) Download the installation media and save it on your computer.

3) Double-click the Media Creation Tool to launch the tool.

4) Select the **Create installation media (USB flash drive, DVD, or ISO file) for another PC** option.

![](https://images.drivereasy.com/wp-content/uploads/2020/01/Create-instalaltion-media-USB-flash-driveor-CD-DVD.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Select the language, edition, and architecture (64-bit or 32-bit) for the Windows system.

 6) Choose your preferred media. If you choose a USB flash drive, make sure you have a blank USB flash drive with at least 8GB of space.

 7) Follow the on-screen instructions to finish the setup.

#### Step 2: Change the boot order to USB/DVD

 Change the boot order in the BIOS setup. If you use a bootable USB drive, please put**Removable Devices** as the first boot choice. Otherwise, your PC will boot normally from your hard drive.

1) Turn on your device.

2) As soon as your computer starts booting up, press the function key to enter BIOS.

**Note:** The key to access BIOS can vary from**Esc** ,**Delete** to**F2** ,**F8** ,**F12** , depending on your manufacturer and computer model.  
![](https://images.drivereasy.com/wp-content/uploads/2019/12/keyboard-bios-keys.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Once in BIOS, go to the**Boot** sector and set**Removable Devices** or**CD-Rom Drive** as the first boot device.

 4) Save the changes and exit.

#### Step 3: Boot with an Installation or Repair disc or USB drive

1) Boot your PC from the bootable CD/DVD/USB.

2) In the Windows Setup menu, click**Next** .

3) Select**Repair your computer** in the lower-left corner.

4) Go to**Troubleshoot** \>**Advanced Options** \>**Command Prompt** .

![](https://images.drivereasy.com/wp-content/uploads/2020/01/command-prompt.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) In Command Prompt, type the following command lines and hit Enter after each command. (There’s a space between**bootrec** and**/** .)

bootrec /scanos

bootrec /fixmbr

bootrec /fixboot

bootrec /rebuildbcd

 Type**Y** and press**Enter** if you’re prompted for permission.

 6) After you have entered the commands above, close the Command Prompt and Reboot your PC.

 The 0xc0000098 error should now be fixed as your PC begins to load. If not, try the fix below.

### Fix 2: Startup Repair

 Startup Repair is a built-in tool to diagnose and repair some common problems on Windows. You may need to run Startup Repair (even 2 or 3 times).

1) Boot your PC from your setup disk (USB/DVD/CD).

2) Select**Repair your computer** and go to**Troubleshoot** \>**Advanced Options** \>**Startup Repair** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/startup-repair.jpg)

 3) Startup Repair will begin scanning your installation for known issues and will attempt a repair if it finds any.

 4) If it fails, you can run Startup Repair again.

### Fix 3: CHKDSK

 CHKDSK, short for “check disk”, aims to check disk and verify system files for any errors.

 1) Boot your device from your installation media and go to**Command Prompt** .

 2) Type the following command line and press**Enter** .

chkdsk C: /f /r /x

* **C:** is the letter of the drive where Windows is installed, you can change it if you’ve installed it on another drive.
* **r** directs to find out the error.
* **x** symbolizes the volume that requires scanning.

3) CHKDSK will manage to fix the problems it finds.

4) Close Command Prompt and restart your device to check if the Windows system can load up again.

### Fix 4: System File Checker

 The error 0xc0000098 can also be caused by missing or corrupt system files. System File Checker (SFC) can help you to restore the missing files and repair any problematic ones.

 1) Again go to**Command Prompt** and type the following command and hit**Enter** .

sfc /scannow /offbootdir=c:\ /offwindir=c:\windows

 This command is slightly different from_**sfc /scannow**_ because this is done with a different installation of Windows (**_/offwindir=c:\\windows_** ) on a different drive (_**/offbootdir=c**_ :).

2) Wait for the scan to finish.

### Fix 5: Use a Windows Fortect Tool

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  Windows repair works by replacing system files automatically. It’s like a clean Windows reinstallation in one hour, without losing any programs, settings, or user data. It can fix the 0xc0000098 error code without a computer restart.

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.

 2) Open Fortect and it might take 3\~5 minutes to analyze your PC. Sit back and grab a cup of coffee. Once complete, you will be able to review the detailed scan report for free.

![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)

 3) Click**Start Repair** to restore any corrupted files. You will need to purchase a license key to do so and don’t have pressure on it, for it has a 60-day money-back guarantee.

![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Enter your license key and the restoration will begin automatically. Reimage handles all.

### Fix 6: Perform a clean install of Windows

 If neither of the fixes above did the trick, then you need to do a clean reinstall of Windows to fix your issues and return your PC to a cleaner state.

 1) Boot from your installation media and select**Next** .

 2) Select**Install now** \> check the**I accept** box >**Next** \> select**Custom: Install Windows only (advanced)** .

 3) If multiple disks are displayed, you’ll only need to delete all partitions from the disk where you want to install Windows.

 3) Highlight each drive/partition in the list and select**Delete** . When the Windows Setup notification appears, select**OK** .

 4) Do this for every drive in the list except the one that says**Unallocated Space** . When you’re finished, only**Drive 0 Unallocated Space** should remain.

 5) Select**Next** .

 6) The Windows setup screen requests you choose your language/keyboard layout, remove the external storage drive from your device, and select**OK** . This will restart your device.

 7) Your device should be working properly now.

#### Pro tip: Update the essential drivers

 If the new setup fails to add some essential drivers correctly after a clean installation, such as for the network adapter and graphics card, you’ll need to update the driver whether through**Windows Update** or**Device Manager** .

##### 1\. Check for updates

![](https://images.drivereasy.com/wp-content/uploads/2020/01/Windows-update.jpg)

 Type**Check for updates** in the Search box and press**Enter** .

##### 2\. Device Manager

![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-driver.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Device Manager, right-click your device and select**Update Driver** then choose search automatically.

##### 3\. Download from the manufacturer’s website

 Although Windows does a pretty good job detecting and installing most device drivers automatically, it can’t always update all of your drivers because of the OEM (Original equipment manufacturer) restrictions. In that case, you need to go to the manufacturer’s website for new drivers and install it manually.

##### 4\. Update all of your drivers automatically (Recommended)

 If you don’t have the time, patience or computer skills to update these drivers manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 **All the drivers in Driver Easy come straight from the manufacturer.**

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  it takes just 2 clicks:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now.png)

 3) Click**Update All** to automatically download and install the correct version of all essential and peripheral drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click_Update All_ . You get**full support** and a no-questions-asked**30-day money back guarantee** .)

![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note: You can do it for free if you like, but it’s partly manual.

 If you need assistance or have any questions, please contact Driver Easy’s support team at [**support@drivereasy.com**](https://vapordna.pxf.io/vnbxna) .

 Good to go? Hopefully, one of the fixes above did the trick for you. Feel free to leave us a comment if you have further questions or suggestions.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-sorbet-surveillance-complete-guide-to-ice-cream-screen-capture-for-2024/"><u>[New] Sorbet Surveillance Complete Guide to Ice Cream Screen Capture for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-ultimate-guide-to-7-superior-video-players-on-mac/"><u>[New] Ultimate Guide to 7 Superior Video Players on Mac</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-the-complete-guide-to-assembling-youtube-music-collections-onlineapp-wise/"><u>[Updated] 2024 Approved The Complete Guide to Assembling YouTube Music Collections Online/App-Wise</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-crucial-info-every-asmr-viewer-should-absorb/"><u>[Updated] In 2024, Crucial Info Every ASMR Viewer Should Absorb</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-expert-tips-for-effective-pip-use-on-edge-browser/"><u>[Updated] In 2024, Expert Tips for Effective PIP Use on Edge Browser</u></a></li>
<li><a href="https://win-howtos.techidaily.com/battleye-installation-issues-resolved-how-to-fix-and-ensure-successful-setup/"><u>BattlEye Installation Issues Resolved: How to Fix and Ensure Successful Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquering-challenges-a-tale-of-fixed-nvidia-setup/"><u>Conquering Challenges: A Tale of Fixed NVIDIA Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-correcting-ethernet-connection-failures-for-windows-10-and-7-users/"><u>Diagnosing and Correcting Ethernet Connection Failures for Windows 10 & 7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-tips-correcting-system-io-hardware-misfires-efficiently/"><u>DIY Tips: Correcting System I/O Hardware Misfires Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-full-functionality-in-windows-audio-controls-missing/"><u>Ensuring Full Functionality in Windows: Audio Controls Missing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-the-errcachemiss-hurdle-in-your-chrome-web-browser/"><u>How to Overcome the ERR_CACHE_MISS Hurdle in Your Chrome Web Browser</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revelations-on-elon-musks-ai-endeavor-the-mystery-behind-truthgpt/"><u>Revelations on Elon Musk’s AI Endeavor – The Mystery Behind TruthGPT</u></a></li>
<li><a href="https://program-issues.techidaily.com/solving-the-issue-what-to-do-when-your-qbittorent-download-is-halted/"><u>Solving the Issue: What to Do When Your qBittorent Download Is Halted</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-appearing-bluetooth-in-pc-device-settings/"><u>Troubleshooting Steps for Appearing Bluetooth in PC Device Settings</u></a></li>
</ul></div>

