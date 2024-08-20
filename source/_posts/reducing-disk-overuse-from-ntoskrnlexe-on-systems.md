---
title: Reducing Disk Overuse From Ntoskrnl.exe on Systems
date: 2024-08-19T07:51:45.632Z
updated: 2024-08-20T07:51:45.632Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Reducing Disk Overuse From Ntoskrnl.exe on Systems
excerpt: This Article Describes Reducing Disk Overuse From Ntoskrnl.exe on Systems
thumbnail: https://thmb.techidaily.com/f17f33138f47cc809c1c7740ec4a954bd7d355028092c16b39a2af30bc8bac07.jpg
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
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2016/09/services-and-applications.jpg)
3. Double-click**Windows Search** .  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2016/09/windwos-search-6101.jpg)
4. In the**General** tab, click **Stop** .  
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2016/09/stop-button.jpg)
5. Wait for the service to stop, then press**OK** to save the change and exit.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2016/09/ok-to-save-the-change-6104.jpg)

## Method 2: Check incompatible programs

 Some users say that this only happens when they use certain programs. Especially when they have antivirus software running in the background. The antivirus software might have some conflicts with certain programs. The next time you encounter this situation, try to pay extra attention to see if you can find the program that is messing with your system. If such a program can be located, try reinstallingit or uninstalling it completely.

## Method 3: Run SFC and DISM

 Corrupted system files may cause high CPU and disk usage with ntoskrnl.exe, but luckily, there are two built-in tools that can help to identify and repair such bad system files. The whole process could take some time, and we suggest you don’t run any other programs when doing the test. To run these tools:

### 3.1\. Scan corrupt files with System File Checker

 1) On your keyboard, press the**Windows** logo key and**R** at the same time. Type**cmd** and press**Ctrl+Shift+Enter** at the same time to run Command Prompt as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/cmd-1.jpg)

 Click**Yes** when prompted for permission to make changes to your device.

 2) In the Command Prompt window, copy and paste the following command and hit**Enter** .

sfc /scannow

 3) System File Checker will then scan all system files and repair any corrupted or missing ones it detected. This may take 3-5 minutes.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/scan-now.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
### 3.2\. Run dism.exe

 1) On your keyboard, press the**Windows** logo key and**R** at the same time. Type**cmd** and press**Ctrl+Shift+Enter** to run Command Prompt as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/cmd-1.jpg)

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## Method 4: Disable Runtime Broker

 Normally, the runtime broker process should only use a very low CPU resource, but if things go wrong, it could take up to 100% CPU and disk usage, making your Windows run slowly and buggy. In this case, you can try to disable it to see if it helps. To do so:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here: [How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the **Windows** key and the **R** key together. Type **regedit** and hit **Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location: `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\TimeBroker`  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2016/09/runtime-broker.png)
4. On the right side, double-click**Start** , and change its value to**4** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/runtime-broker-4.png)
5. Restart your computer for the changes to take effect.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-best-free-youtube-intro-makers/"><u>[New] 2024 Approved  Best Free YouTube Intro Makers</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-practical-demonstrations-creating-and-configuring-timer-modules-in-obs/"><u>[New] In 2024, Practical Demonstrations  Creating and Configuring Timer Modules in OBS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-potential-windows-update-database-error-detected-in-windows-11/"><u>[SOLVED] Potential Windows Update Database Error Detected in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205582672-solved-windows-update-error-0x80070002-easily/"><u>[Solved] Windows Update Error 0X80070002 | Easily</u></a></li>
<li><a href="https://win11.techidaily.com/10-substitutes-for-bitlocker-in-winxp-systems/"><u>10 Substitutes for BitLocker in WinXP Systems</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-oneplus-nord-ce-3-5g-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My OnePlus Nord CE 3 5G Wont Charge | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-the-ultimate-guide-to-hash-tagging-for-brand-success-on-fb/"><u>2024 Approved  The Ultimate Guide to Hash Tagging for Brand Success on FB</u></a></li>
<li><a href="https://change-location.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-vivo-v30-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/crafting-the-perfect-cover-letter-tips-and-tricks-from-chatgpt/"><u>Crafting the Perfect Cover Letter: Tips and Tricks From ChatGPT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/detected-missing-windows-core-dll-for-apis/"><u>Detected Missing Windows Core DLL for APIs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-fixes-eradicating-unwanted-lines-from-computer-visuals/"><u>DIY Fixes: Eradicating Unwanted Lines From Computer Visuals</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/examining-youtubes-copyright-stance-versus-cc-approach/"><u>Examining Youtube's Copyright Stance Versus CC Approach</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-problem-with-creating-a-directx-rendering-context/"><u>Fixed: Problem with Creating a DirectX Rendering Context</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-nokia-150-2023-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Nokia 150 (2023) to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hosted-network-error-not-started-in-windows-pressenting-solutions-for-quick-fixes/"><u>Hosted Network Error 'Not Started' In Windows Pressenting Solutions for Quick Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-dysfunction-fixes-for-windows-1078-users-facing-typing-issues/"><u>Keyboard Dysfunction Fixes for Windows 10/7/8 Users Facing Typing Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/masterful-approaches-to-repair-your-unsuccessful-attempts-at-accessing-remote-server-resources/"><u>Masterful Approaches to Repair Your Unsuccessful Attempts at Accessing Remote Server Resources</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-blur-video-online-without-spending-a-dime-a-tutorial/"><u>New Blur Video Online Without Spending a Dime A Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-repeated-device-unrecognized-by-system-messages-when-using-usb-devices/"><u>Overcoming Repeated 'Device Unrecognized by System' Messages When Using USB Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-resolved-issue-buildings-now-load-correctly/"><u>PUBG: Resolved Issue - Buildings Now Load Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quiet-car-chaos-heres-how-to-restore-audio-in-forza-horizon-4/"><u>Quiet Car Chaos? Here's How to Restore Audio in Forza Horizon 4</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-messages-after-motorola-razr-40-has-been-deleted-by-fonelab-android-recover-messages/"><u>Recover your messages after Motorola Razr 40 has been deleted</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-steps-to-overcome-the-frustrating-windows-update-error-at-0/"><u>Simple Steps to Overcome the Frustrating Windows Update Error at 0%%</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-occurred-while-resetting-issue-in-windows-11-a-comprehensive-guide/"><u>Solving the 'Problem Occurred While Resetting' Issue in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-windows-11-crimson-display-problem/"><u>Solving the Windows 11 Crimson Display Problem</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/start-streaming-sports-a-mac-based-channel-guide-for-2024/"><u>Start Streaming Sports  A Mac-Based Channel Guide for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fix-boot-problems-with-windows-getting-ready/"><u>Step-by-Step Guide to Fix Boot Problems with 'Windows Getting Ready'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-addressing-problems-with-laptopdesktop-startup-failures/"><u>Step-by-Step Solution: Addressing Problems with Laptop/Desktop Startup Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-future-without-d3d-implications-for-unreal/"><u>The Future Without D3D: Implications for Unreal</u></a></li>
<li><a href="https://facebook.techidaily.com/the-moral-dilemrances-of-disapproving-platforms/"><u>The Moral Dilemrances of Disapproving Platforms</u></a></li>
<li><a href="https://fox-that.techidaily.com/the-ultimate-guide-to-detecting-water-damage-9-warning-signs-on-your-iphone/"><u>The Ultimate Guide to Detecting Water Damage: 9 Warning Signs on Your iPhone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-advice-expert-guides-on-computer-hardware/"><u>Tom's Tech Advice: Expert Guides on Computer Hardware</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721471078000-troubleshoot-failed-iphone-computer-pairing-quick-solutions/"><u>Troubleshoot Failed iPhone-Computer Pairing - Quick Solutions!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-0x800705b4-windows-update-errors-for-windows-10-users/"><u>Troubleshooting & Fixing 0X800705b4 Windows Update Errors for Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-input-not-recognized-on-your-monitor/"><u>Troubleshooting Guide: Resolving 'Input Not Recognized' On Your Monitor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-correcting-application-initialization-errors-hex-code-0xc000007b/"><u>Troubleshooting Tips: Correcting Application Initialization Errors (Hex Code 0xC000007B)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixing-platform-not-supported-error-on-intel-serial-io-driver-installation/"><u>Troubleshooting: Fixing 'Platform Not Supported' Error on Intel Serial IO Driver Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/upping-the-ante-in-digital-playgrounds-advanced-techniques-for-faster-smoother-games-on-windows-11/"><u>Upping the Ante in Digital Playgrounds: Advanced Techniques for Faster, Smoother Games on Windows 11</u></a></li>
</ul></div>
