---
title: How to Fix 'Policy Diagnostic Service Is Down' Error
date: 2024-08-19T07:30:50.023Z
updated: 2024-08-20T07:30:50.023Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix 'Policy Diagnostic Service Is Down' Error
excerpt: This Article Describes How to Fix 'Policy Diagnostic Service Is Down' Error
thumbnail: https://thmb.techidaily.com/f06ecdd32f0e95a7a4f703e01e2d64ef66252665cb47e60c44797d0e0a016c7b.jpg
---

## Resolving 'Diagnostics Policy Service Is Offline – Here’s What To Do

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)

3) Click the **Update**  button next to a flagged network adapter driver to automatically download and install the correct version of this driver (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **Pro** version – you’ll be prompted to upgrade when you click Update All).

 Driver Easy requires network connection to update drivers. If your windows can’t access the Internet, please use the Offline Scan feature of Driver Easy to help you.

 4) After updating your network adapter driver, please restart your computer.

 5) Run the Network Diagnostics to see if it goes well.

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
<li><a href="https://win-howtos.techidaily.com/fixed-windows-10-update-error-0x80070541/"><u>[Fixed] Windows 10 Update Error 0X80070541</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-accelerate-your-library-quick-tiktok-download-strategies-for-2024/"><u>[New] Accelerate Your Library  Quick TikTok Download Strategies for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-a-comprehensive-look-at-editing-and-uploading-virtual-reality-videos-to-youtube/"><u>[Updated] 2024 Approved  A Comprehensive Look at Editing and Uploading Virtual Reality Videos to YouTube</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-unlocking-the-power-of-words-in-google-meet-discussions/"><u>[Updated] 2024 Approved  Unlocking the Power of Words in Google Meet Discussions</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-how-to-dodge-facebook-video-sponsored-content/"><u>2024 Approved  How to Dodge Facebook Video Sponsored Content</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-invaluable-slide-show-tools-for-business-executives/"><u>2024 Approved  Invaluable Slide Show Tools for Business Executives</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-magnifying-quality-with-magix-photo-tools/"><u>2024 Approved  Magnifying Quality with MAGIX Photo Tools</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-vivo-y100i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/advanced-subtitle-editing-unlocking-potential-with-macos-for-2024/"><u>Advanced Subtitle Editing  Unlocking Potential with MacOS for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/asus-rog-phone-7-ultimate-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Asus ROG Phone 7 Ultimate Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-windows-update-problem-code-8007000e-explained/"><u>Effective Fixes for Windows Update Problem - Code 8007000E Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-minecrafts-windows-stability-issues-with-your-video-card-driver-update/"><u>Fixing Minecraft's Windows Stability Issues with Your Video Card Driver Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-diagnose-and-repair-error-0xc0000005-crashes-in-windows-environments/"><u>How to Diagnose and Repair Error 0Xc0000005 Crashes in Windows Environments</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-infinix-hot-40i-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Infinix Hot 40i If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-missing-power-symbols-in-windows-11-expert-troubleshooting-steps/"><u>How to Fix Missing Power Symbols in Windows 11: Expert Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-issues-with-windows-and-system-event-services-connection/"><u>How to Overcome Issues with Windows and System Event Services Connection</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-full-length-video-view-remove-youtube-preview/"><u>In 2024, Full-Length Video View  Remove YouTube Preview</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-lock-apps-on-realme-12-proplus-5g-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Realme 12 Pro+ 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-y17s-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Vivo Y17s Phone without Any Data Loss</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-iphone-15-pro-max-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/"><u>In 2024, iPhone 15 Pro Max Asking for Passcode after iOS 17/14 Update, What to Do?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-passfab-apple-iphone-13-mini-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>In 2024, PassFab Apple iPhone 13 mini Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/live-streaming-elite-9-edition-for-2024/"><u>Live Streaming Elite  #9 Edition for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fixes-for-deadly-errors-in-black-ops-latest-edition/"><u>Mastering the Fixes for Deadly Errors in Black Op's Latest Edition</u></a></li>
<li><a href="https://android-frp.techidaily.com/motorola-edge-40-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Motorola Edge 40 ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/oculus-equipment-error-resolution-best-practices/"><u>Oculus Equipment Error Resolution: Best Practices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-lag-and-hang-ups-in-your-new-windows-11-setup/"><u>Overcoming Lag and Hang-Ups in Your New Windows 11 Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/playstation-4-trouble-solve-the-mystery-of-error-code-ce-34878-0-today/"><u>PlayStation 4 Trouble? Solve the Mystery of Error Code CE-34878-0 Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-configuration-system-didnt-initialize-error-on-your-windows-10-pc-guide/"><u>Resolve 'Configuration System Didn't Initialize' Error on Your Windows 10 PC [Guide]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-netflix-issue-overcoming-proxy-and-vpn-detected-warnings/"><u>Resolve Your Netflix Issue: Overcoming Proxy and VPN Detected Warnings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-specified-module-not-found-errors-a-step-by-step-guide/"><u>Resolving 'Specified Module Not Found' Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211840975-solving-your-pdf-printing-issues-in-seconds/"><u>Solving Your PDF Printing Issues in Seconds!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-thawing-your-computer-from-a-freeze/"><u>Step-by-Step Guide: Thawing Your Computer From a Freeze</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-apps-and-online-tools-to-track-infinix-note-30-vip-racing-edition-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Infinix Note 30 VIP Racing Edition Phone With/Without IMEI Number</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-non-functional-laptop-microphone/"><u>Troubleshooting Guide: Fixing a Non-Functional Laptop Microphone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-when-your-pc-doesnt-detect-headphones/"><u>Troubleshooting Guide: Resolving When Your PC Doesn't Detect Headphones</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-how-to-fix-a-non-responsive-razer-keyboard/"><u>Troubleshooting Tips: How To Fix A Non-Responsive Razer Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-restoring-touch-functionality-in-windows-10-devices-5-strategies/"><u>Troubleshooting Tips: Restoring Touch Functionality in Windows 10 Devices (5 Strategies)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-solutions-to-resolve-binkyw32-dll-file-disappearance/"><u>Ultimate Solutions to Resolve Binkyw32 DLL File Disappearance</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-final-cut-pro-x-tutorial-cropping-images-for-video-editing/"><u>Updated In 2024, Final Cut Pro X Tutorial Cropping Images for Video Editing</u></a></li>
</ul></div>
