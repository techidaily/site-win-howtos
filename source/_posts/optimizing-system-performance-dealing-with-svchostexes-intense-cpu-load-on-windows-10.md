---
title: "Optimizing System Performance: Dealing with svchost.exe's Intense CPU Load on Windows 10"
date: 2024-12-23T14:43:56.530Z
updated: 2024-12-27T19:29:20.511Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Optimizing System Performance: Dealing with svchost.exe's Intense CPU Load on Windows 10"
excerpt: "This Article Describes Optimizing System Performance: Dealing with svchost.exe's Intense CPU Load on Windows 10"
thumbnail: https://thmb.techidaily.com/ed43cb68b7509790195a4106080566d9794dc5d45025fc9ee05e6abe84591529.jpg
---

## Optimizing ntoskrnl.exe for Better Performance on PC

 If your Windows is working slowly, and when you check your Task Manager and find that the**System** item is hogging much of your CPU (or Disk in some cases) usage, you’re not alone. Many Windows users are reporting this problem. Don’t worry, it’s possible to fix.

**\*** Right-click the**System** item and click**Properties** , you’ll see a new item called**ntoskrnl.exe** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b0f9d613fd6.png)

## What is ntoskrnl.exe?

 Ntoskrnl.exe, short for**Windows NT operating system kernel** , is a fundamental part of the system. Usually, when you see the uncommon usage of high CPU or memory, you should shut down the possible programs that are causing the problem.

 If this happens a lot, you should see if there is something wrong with certain application settings or files in your system.

## How do I fix it?

 Here are 4 methods for you to try. You may not have to try them all; just work your way down until you find the one that works for you.

* **[Method 1: Disable Windows Search Service](#a)**
* **[Method 2: Check Incompatible Programs](#b)**
* **[Method 3: Run SFC and DISM](#c)**
* **[Method 4: Disable Runtime Broker](#d)** [](#d)

 It is always suggested that you keep your device drivers updated to eliminate the possibility of such problems.

 Driver Easy is a tool that detects, downloads, and updates drivers (if you go Pro). You can use it to fix any driver problems. If you go to Pro, you can even update all drivers with just one click. If the high system CPU usage problem is caused by drivers, you can use Driver Easy to fix it quickly.

 You can update your drivers automatically with either the [**7 days free trial**](https://tools.techidaily.com/drivereasy/download/) or the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) of Driver Easy. It takes just 2 clicks, and you get full support and a 30-day money-back guarantee with the Pro version:

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2020/10/6_0_scan-now.jpg)
3. Click the**Activate & Update** button next to the flagged device to automatically download and install the correct version of this driver.  

 Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (You’ll need the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  for this – when you select Update All, you’ll get a prompt to upgrade. If you’re not prepared to purchase the Pro version yet, Driver Easy provides a 7-day trial at no cost, granting access to all Pro features like fast downloads and easy installation. No charges will occur until after your 7-day trial period ends.)  
![](https://www.drivereasy.com/wp-content/uploads/2021/05/NVIDIA-GeForce-RTX-3090-Ti-3.jpg)
4. After updating, restart your computer to take effect.

**The Pro version of Driver Easy** comes with _full technical support_ . If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

## Method 1: Disable Windows Search service

 A lot of users suggested that disabling Windows Search helps to reduce the CPU and Disk usage caused by ntoskrnl.exe. To see if this does the trick for you as well:

1. On your keyboard, press the **Windows key** and**X** at the same time, then click **Computer management** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/computer-management.png)
2. Expand**Services and Applications** and click**Services** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/services-and-applications.jpg)
3. Double-click**Windows Search** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/windwos-search-6101.jpg)
4. In the**General** tab, click **Stop** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://www.drivereasy.com/wp-content/uploads/2016/09/stop-button.jpg)
5. Wait for the service to stop, then press**OK** to save the change and exit.  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/ok-to-save-the-change-6104.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 2: Check incompatible programs

 Some users say that this only happens when they use certain programs. Especially when they have antivirus software running in the background. The antivirus software might have some conflicts with certain programs. The next time you encounter this situation, try to pay extra attention to see if you can find the program that is messing with your system. If such a program can be located, try reinstallingit or uninstalling it completely.

## Method 3: Run SFC and DISM

 Corrupted system files may cause high CPU and disk usage with ntoskrnl.exe, but luckily, there are two built-in tools that can help to identify and repair such bad system files. The whole process could take some time, and we suggest you don’t run any other programs when doing the test. To run these tools:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3.1\. Scan corrupt files with System File Checker

 1) On your keyboard, press the**Windows** logo key and**R** at the same time. Type**cmd** and press**Ctrl+Shift+Enter** at the same time to run Command Prompt as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/cmd-1.jpg)

 Click**Yes** when prompted for permission to make changes to your device.

 2) In the Command Prompt window, copy and paste the following command and hit**Enter** .

sfc /scannow

 3) System File Checker will then scan all system files and repair any corrupted or missing ones it detected. This may take 3-5 minutes.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/scan-now.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3.2\. Run dism.exe

 1) On your keyboard, press the**Windows** logo key and**R** at the same time. Type**cmd** and press**Ctrl+Shift+Enter** to run Command Prompt as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/cmd-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click**Yes** when prompted for permission to make changes to your device.

 2) In the Command Prompt window, copy and paste the following commands and hit**Enter** after each line:

dism.exe /online /cleanup-image /scanhealth

dism.exe /online /cleanup-image /restorehealth

2) When the process finishes:

* If the DISM tool gives you errors, you can always try this command line. This will take up to 2 hours.

dism /online /cleanup-image /startcomponentcleanup

* If you get **Error: 0x800F081F** , reboot your computer, then open Command Prompt as administrator again (step 1) and run this command line instead:

Dism.exe /Online /Cleanup-Image /AnalyzeComponentStore

 When these tests are done, see if the ntoskrnl.exe high CPU or disk usage problem remains. If the problem still persists, please move on to the next fix.

## Method 4: Disable Runtime Broker

 Normally, the runtime broker process should only use a very low CPU resource, but if things go wrong, it could take up to 100% CPU and disk usage, making your Windows run slowly and buggy. In this case, you can try to disable it to see if it helps. To do so:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here: [How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the **Windows** key and the **R** key together. Type **regedit** and hit **Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location: `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\TimeBroker`  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/runtime-broker.png)
4. On the right side, double-click**Start** , and change its value to**4** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/runtime-broker-4.png)
5. Restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

See if the ntoskrnl.exe high CPU or disk usage problem remains.

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
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-a-comprehensive-guide-to-previewing-facebooks-hidden-activities/"><u>[New] 2024 Approved A Comprehensive Guide to Previewing Facebook's Hidden Activities</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-quiet-echo-architects-6-unpublicized-voice-recorder-apps/"><u>[Updated] 2024 Approved Quiet Echo Architects 6 Unpublicized Voice Recorder Apps</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-the-leading-free-online-screencasting-solutions/"><u>[Updated] The Leading Free Online Screencasting Solutions</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-grandmaster-gaming-evaluating-the-best-7-total-war-experiences/"><u>2024 Approved Grandmaster Gaming Evaluating the Best 7 Total War Experiences</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-techniques-for-resolving-touchpad-problems-on-your-laptop-computer/"><u>Effective Techniques for Resolving Touchpad Problems on Your Laptop Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ethernet-troubleshooting-techniques-for-microsoft-windows-11-and-7-operating-systems/"><u>Ethernet Troubleshooting Techniques for Microsoft Windows 11 and 7 Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-corrupted-files-in-windows-11-with-the-powerful-sfc-and-dism-utilities/"><u>How to Fix Corrupted Files in Windows 11 with the Powerful SFC and DISM Utilities</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-file-explorer-freezing-problems-in-windows-11/"><u>How to Resolve File Explorer Freezing Problems in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-vivo-v29-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Vivo V29 to Outlook | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-a-comprehensive-guide-to-iphone-se-2020-blacklist-removal-tips-and-tools-drfone-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iPhone SE (2020) Blacklist Removal Tips and Tools | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-flip-it-a-step-by-step-guide-to-rotating-clips-in-fcp/"><u>In 2024, Flip It! A Step-by-Step Guide to Rotating Clips in FCP</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-xiaomi-redmi-note-13-5g-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Xiaomi Redmi Note 13 5G</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-ultimate-guide-best-video-capture-tools-for-windows/"><u>In 2024, Ultimate Guide Best Video Capture Tools for Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-for-starting-a-hosted-network-in-windows-10-when-it-wont-turn-on/"><u>Solution Steps for Starting a Hosted Network in Windows 10 when It Won't Turn On</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-0x80070490-issue-comprehensive-guide-to-fixing-windows-update-failures/"><u>Solving the 0X80070490 Issue: Comprehensive Guide to Fixing Windows Update Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/streamlined-wd-firmware-integration-for-optimal-cpu-management/"><u>Streamlined WD Firmware Integration for Optimal CPU Management</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solving-the-problem-detected-on-startup-in-windows-11-easily/"><u>Troubleshooting and Solving the ‘Problem Detected on Startup’ in Windows 11 Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/update-needed-confirm-d3d11-graphics-support-for-proper-engine-functionality/"><u>Update Needed: Confirm D3D11 Graphics Support for Proper Engine Functionality</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Lava Yuva 2 Pro? | Dr.fone</u></a></li>
</ul></div>

