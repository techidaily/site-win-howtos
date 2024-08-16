---
title: "Winning Against Windows's 0X80070490 Update Error: Comprehensive Fix Strategies"
date: 2024-08-15T11:40:09.035Z
updated: 2024-08-16T11:40:09.035Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Winning Against Windows's 0X80070490 Update Error: Comprehensive Fix Strategies"
excerpt: "This Article Describes Winning Against Windows's 0X80070490 Update Error: Comprehensive Fix Strategies"
thumbnail: https://thmb.techidaily.com/a284b8622794b8ba45f3866eaa63e737e0684e210dde0d1e1927202914413ca4.jpg
---

## Comprehensive Guide: Resolve Windows Update Error 0X8024002E Once and For All

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

 A lot of Windows 10 users have reported an error while trying to update their operating system. What usually happens is they fail to install their system updates, and an error code shows up on Windows Update that says “0x8024002e”.

 If this is also happening to you, you’re no doubt very frustrated. But the good news is you should be able to fix it quite easily. We’ve put together some suggestions to help you fix the problem. Here are a few things you can try:

1. **[Reset your Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
2. **[Modify your Windows Update setting in the registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Perform a clean boot](https://tools.techidaily.com/drivereasy/download/)**

## Fix 1: Reset your Windows Update components

 The Windows Update “0x8024002e” error code may occur because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this fixes your problem.

To reset these components:

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “cmd” in the Run box, then, on your keyboard, press the**Ctrl** ,**Shift** and**Enter** keys at the same time.

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-884.png)

3. If prompted, click**Yes** .
4. In Command Prompt, type the following lines of command and press**Enter** on your keyboard after typing each:

net stop bits
net stop wuauserv
net stop appidsvc
net stop cryptsvc

5. Type these lines of command and press**Enter** after typing each in Command Prompt:

ren %systemroot%\softwaredistribution softwaredistribution.old
ren %systemroot%\system32\catroot2 catroot2.old

6. In Command Prompt, type these commands and press**Enter** after each:

net start bits
net start wuauserv
net start appidsvc
net start cryptsvc

7. Try updating your system with Windows Update, and see if the 0x8024002e error is gone.

 If it is, then you’ve solved your problem. But if not, you may need to…

## Fix 2: Modify your Windows setting in the registry

 This issue can also be fixes by adjusting a Windows Update setting in the registry. Here is how:

 You may experience serious problems if you don’t modify your registry properly. So be careful for what you’re doing in registry. And in case anything goes wrong, you can back up your registry, which you’ll know how by going through the steps below.

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “regedit” in the Run box and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-905.png)
3. If prompted, click**Yes** .
4. On the Registry Editor, click**File** , then select**Export** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
9. Change the**value data** to**0** , then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
16. Click**OK** and then click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
17. Check to see if the error occurs. If it doesn’t, repeat step**13 to 16**  until you find out the startup item that causes the issue.  
 If there’s any startup item that causes the 0x8024002e error, you should see what program is this item related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.

 Hopefully one of the fixes above helped you fix your 0x8024002e error on Windows Update. If you have any questions or suggestions, you’re more than welcome to leave us a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://win-howtos.techidaily.com/1723209063772-fixed-windows-cannot-access-the-specified-device-path-or-file-error/"><u>[Fixed] ‘Windows Cannot Access the Specified Device Path or File’ Error</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-enjoy-anytime-anywhere-with-our-12-channel-stream-for-2024/"><u>[New] Enjoy Anytime, Anywhere with Our 12 Channel Stream for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-guide-to-screen-record-on-mac-with-shortcuts-for-2024/"><u>[New] Guide to Screen Record on Mac with Shortcuts for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-elite-screenwriting-circle/"><u>[Updated] 2024 Approved  Elite Screenwriting Circle</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-harmonic-hits-top-rated-dj-template-downloads/"><u>[Updated] 2024 Approved  Harmonic Hits  Top-Rated DJ Template Downloads</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-discovering-the-timeline-for-youtube-earnings/"><u>[Updated] Discovering the Timeline for YouTube Earnings</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-accelerating-your-ascension-to-instagram-a-list-status-our-fast-track-guide-of-15-must-try-strategies/"><u>[Updated] In 2024, Accelerating Your Ascension to Instagram A-List Status  Our Fast Track Guide of 15 Must-Try Strategies</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-how-to-seamless-transition-of-photos-from-your-device-to-snapchat/"><u>[Updated] In 2024, How-To  Seamless Transition of Photos From Your Device to Snapchat</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-manufacture-memorable-visuals-on-giphy-for-2024/"><u>[Updated] Manufacture Memorable Visuals on Giphy for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-optimizing-large-scale-video-migrations-from-iphone-to-mac-systems/"><u>2024 Approved  Optimizing Large-Scale Video Migrations From iPhone to Mac Systems</u></a></li>
<li><a href="https://driver-install.techidaily.com/asus-usb-bt400-bt-driver-win11-8-support/"><u>Asus USB-BT400 BT Driver - Win11, 8 Support</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-failed-windows-update-queries/"><u>Diagnosing and Repairing Failed Windows Update Queries</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-repairing-a-broken-signature-character-input/"><u>Expert Advice on Repairing a Broken '@' Signature Character Input</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-to-repairing-a-non-responsive-wacom-digital-drawing-pad/"><u>Expert Guide to Repairing a Non-Responsive Wacom Digital Drawing Pad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-track-to-connectivity-repair-techniques-for-remote-server-connection-failures/"><u>Fast Track to Connectivity: Repair Techniques for Remote Server Connection Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-for-windows-11-dvdcd-rom-error-incomplete-or-corrupted-device-configuration-data-error-code-19/"><u>Fix for Windows 11 DVD/CD-ROM Error: Incomplete or Corrupted Device Configuration Data (Error Code 19)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208806869-fix-windows-update-error-8007000e-fast-a-step-by-step-guide/"><u>Fix Windows Update Error 8007000E Fast: A Step-by-Step Guide!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-unavailable-module-problem-in-your-software-application/"><u>Fixing the Unavailable Module Problem in Your Software Application</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-the-most-out-of-your-laptop-fixing-issues-with-the-trackpad/"><u>Getting the Most Out of Your Laptop: Fixing Issues with the Trackpad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-fixing-the-missing-device-issue-error-24-in-windows-10-11-and-earlier-versions/"><u>Guide to Fixing the Missing Device Issue (Error 24) in Windows 10, 11, and Earlier Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-resolve-win11win8win7-error-this-device-is-not-present-code-24/"><u>How to Correctly Resolve Win11/Win8/Win7 Error 'This Device Is Not Present (Code 24)'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-noisy-or-cracking-audio-outputs-on-windows-11-and-7-systems/"><u>How to Fix Noisy or Cracking Audio Outputs on Windows 11 and 7 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-tearing-problems-on-your-valorant-display-comprehensive-fixes/"><u>How to Resolve Tearing Problems on Your Valorant Display – Comprehensive Fixes</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>How To Simulate GPS Movement With Location Spoofer On Apple iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-14-pro-phone-without-password-by-drfone-android/"><u>How To Unlock Xiaomi 14 Pro Phone Without Password?</u></a></li>
<li><a href="https://fox-helps.techidaily.com/how-to-use-zoom-in-your-daily-gmail-routine/"><u>How to Use Zoom in Your Daily Gmail Routine</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-essential-procedures-instilling-stopwatch-capabilities-in-broadcast-encoders/"><u>In 2024, Essential Procedures  Instilling Stopwatch Capabilities in Broadcast Encoders</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-apple-iphone-xs-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On Apple iPhone XS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-sound-reconstruction-with-ffmpeg-preserving-format-integrity/"><u>In 2024, Sound Reconstruction with FFmpeg  Preserving Format Integrity</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ring-asmr-filming-techniques-essential-tips-unveiled-for-2024/"><u>Mastering ASMR Filming Techniques  Essential Tips Unveiled for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-your-pdf-printing-blues-with-these-fast-fixes/"><u>Overcome Your PDF Printing Blues with These Fast Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-bad-module-info-issue-and-prevent-your-game-from-crashing/"><u>Resolve 'Bad Module Info' Issue & Prevent Your Game From Crashing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-fix-persistent-keyboard-delay-on-windows-11/"><u>Resolved: How to Fix Persistent Keyboard Delay on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-missing-dll-from-steam/"><u>Resolving Missing DLL From Steam</u></a></li>
<li><a href="https://extra-support.techidaily.com/rising-stars-top-sierra-dvd-production-tools-for-2024/"><u>Rising Stars  Top Sierra DVD Production Tools for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/semaphore-timeout-resolution-step-by-step-fix-for-error-0x80070079/"><u>Semaphore Timeout Resolution: Step-by-Step Fix for Error 0X80070079</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-dilemma-ultimate-guide-to-resolve-your-pcs-persistent-freezing/"><u>Solving the Dilemma: Ultimate Guide to Resolve Your PC's Persistent Freezing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-a-windows-surface-that-wont-charge-even-though-it-is-connected/"><u>Step-by-Step Fixes for a Windows Surface That Won't Charge Even Though It Is Connected</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-overcoming-fatal-installation-error-16-and-ensuring-a-smooth-start/"><u>Step-by-Step Guide to Overcoming 'Fatal Installation Error 16#' And Ensuring a Smooth Start</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-zte-nubia-z60-ultra-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your ZTE Nubia Z60 Ultra Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fix-for-non-detected-accessories-in-windows-10-using-bluetooth-technology/"><u>The Ultimate Fix for Non-Detected Accessories in Windows 10 Using Bluetooth Technology</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-printing-a-pdf-file-quick-fixes-you-must-try-today/"><u>Trouble Printing a PDF File? Quick Fixes You Must Try Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-non-functional-touchpad-scrolls/"><u>Troubleshooting and Resolving Non-Functional Touchpad Scrolls</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-to-get-your-windows-10-sound-back-on-track/"><u>Troubleshooting Steps to Get Your Windows 10 Sound Back on Track</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-techniques-for-overcoming-driverpowerstatefailure-bugs/"><u>Troubleshooting Techniques for Overcoming DRIVER_POWER_STATE_FAILURE Bugs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-laptops-touchpad-problems-in-windows-operating-systems/"><u>Troubleshooting Your Laptop's Touchpad Problems in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlock-the-power-of-the-essential-troubleshooting-tactics-for-when-it-wont-press-down/"><u>Unlock the Power of the '@': Essential Troubleshooting Tactics for When It Won’t Press Down</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203895192-unlocking-bluetooth-potential-in-windows-7-comprehensive-solutions-covered/"><u>Unlocking Bluetooth Potential in Windows 7: Comprehensive Solutions Covered</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-cant-i-get-to-the-windows-smartscreen-right-now-solutions-for-temporary-glitches/"><u>Why Can't I Get to the Windows SmartScreen Right Now? Solutions for Temporary Glitches</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-sony-xperia-10-v-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Sony Xperia 10 V Offline? Troubleshooting Guide | Dr.fone</u></a></li>
</ul></div>
