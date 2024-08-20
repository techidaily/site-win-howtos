---
title: Resolve Your VCRUNTIME140.dll Missing File Issue - Comprehensive Fix Guide
date: 2024-08-19T07:04:20.165Z
updated: 2024-08-20T07:04:20.165Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolve Your VCRUNTIME140.dll Missing File Issue - Comprehensive Fix Guide
excerpt: This Article Describes Resolve Your VCRUNTIME140.dll Missing File Issue - Comprehensive Fix Guide
thumbnail: https://thmb.techidaily.com/79f38eb573cc99e5f54bf7180a8b2f400aa646add73d8ccbbc068b9cd2192911.jpg
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

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Fix 2: Modify your Windows setting in the registry

 This issue can also be fixes by adjusting a Windows Update setting in the registry. Here is how:

 You may experience serious problems if you don’t modify your registry properly. So be careful for what you’re doing in registry. And in case anything goes wrong, you can back up your registry, which you’ll know how by going through the steps below.

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “regedit” in the Run box and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-905.png)
3. If prompted, click**Yes** .
4. On the Registry Editor, click**File** , then select**Export** .  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .
7. Click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
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
<li><a href="https://youtube-web.techidaily.com/024-approved-how-to-pick-a-youtube-channel-name/"><u>[New] 2024 Approved  How To Pick a YouTube Channel Name</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-rethink-your-favorite-films-top-7-replacements/"><u>[New] Rethink Your Favorite Films - Top 7 Replacements</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-a6400-absent-actors-where-are-the-videos/"><u>[Updated] A6400 Absent Actors  Where Are the Videos?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-hunt-down-these-10-vectors-stock-image-websites/"><u>[Updated] Hunt Down These 10 Vectors Stock Image Websites</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-crystal-clear-capture-amping-up-your-home-studio-recordings/"><u>[Updated] In 2024, Crystal Clear Capture  Amping Up Your Home Studio Recordings</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-from-instant-sharing-to-long-term-storage-snapshots-journey/"><u>[Updated] In 2024, From Instant Sharing to Long-Term Storage  Snapshots' Journey</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-powerhouse-of-4k-reviewing-the-nikon-j5-camera/"><u>[Updated] The Powerhouse of 4K  Reviewing the Nikon J5 Camera</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-8-ultimate-windows-10-video-grabber-apps-you-must-try/"><u>2024 Approved  8 Ultimate Windows 10 Video Grabber Apps You Must Try</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-navigating-youtube-music-eclecticism/"><u>2024 Approved  Navigating YouTube Music Eclecticism</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-unleash-creativity-fast-windows-10-photo-edits-made-simple/"><u>2024 Approved  Unleash Creativity Fast  Windows 10 Photo Edits Made Simple</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/android-call-history-recovery-recover-deleted-call-logs-from-realme-v30-by-fonelab-android-recover-call-logs/"><u>Android Call History Recovery - recover deleted call logs from Realme V30</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-connection-woes-on-windows-10-how-to-get-your-paired-devices-really-connected-and-working/"><u>Bluetooth Connection Woes on Windows 10 - How to Get Your Paired Devices Really Connected and Working</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-too-many-redirects-error-swiftly-and-effectively/"><u>Bypass Too Many Redirects Error Swiftly & Effectively</u></a></li>
<li><a href="https://games-able.techidaily.com/correcting-common-mistakes-in-purchasing-an-oled-monitor/"><u>Correcting Common Mistakes in Purchasing an OLED Monitor</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/elevate-your-income-with-proven-vimeo-advertising-strategies/"><u>Elevate Your Income with Proven Vimeo Advertising Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-insights-on-addressing-and-repairing-the-critical-windows-update-failure-0x80244022/"><u>Expert Insights on Addressing & Repairing the Critical 'Windows Update Failure: 0X80244022'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-the-driverpowerstatefailure-challenge/"><u>Expert Tips to Overcome the DRIVER_POWER_STATE_FAILURE Challenge</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-and-guide-pubg-building-loading-problems-solved/"><u>Fix & Guide: PUBG Building Loading Problems Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-of-your-dell-laptops-control-keys/"><u>How to Restore Functionality of Your Dell Laptop's Control Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-scroll-functionality-on-your-windows-10-laptops-touchpad/"><u>How to Restore Scroll Functionality on Your Windows 10 Laptop's Touchpad</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-best-4k-hdtv-monitors-for-gameplay-excellence/"><u>In 2024, Best 4K HDTV Monitors for Gameplay Excellence</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-xiaomi-civi-3-disney-100th-anniversary-edition-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Xiaomi Civi 3 Disney 100th Anniversary Edition Through Google Earth?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-lava-yuva-2-pro-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Lava Yuva 2 Pro to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Motorola Moto E13? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastery-in-media-manipulation-ttml-and-xml-for-superior-srt-outputs-for-2024/"><u>Mastery in Media Manipulation  TTML & XML for Superior SRT Outputs for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-google-chromes-not-responding-glitches-expert-fix-guide/"><u>Overcoming Google Chrome's 'Not Responding' Glitches – Expert Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/renderer-startup-problems-heres-how-the-2021-revisions-can-help/"><u>Renderer Startup Problems? Here's How the 2021 Revisions Can Help</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-bluetooth-visibility-issues-for-seamless-connectivity-fixed/"><u>Resolving Bluetooth Visibility Issues for Seamless Connectivity [Fixed]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-cannot-reset-pc-issue-in-windows-11-a-complete-guide/"><u>Resolving the 'Cannot Reset PC' Issue in Windows 11 – A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-implemented-for-unwritable-0x-memory-address-error/"><u>Solution Implemented for Unwritable 0X Memory Address Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-game-playability-resolving-windows-driver-issues-for-a-smooth-minecraft-experience/"><u>Solving Game Playability: Resolving Windows Driver Issues for a Smooth Minecraft Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-for-restoring-broken-dell-usb-port-functionality/"><u>Step-by-Step Tutorial for Restoring Broken Dell USB Port Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-solve-unwanted-screen-shaking-in-windows-11-expert-tips-and-tricks/"><u>Troubleshoot and Solve Unwanted Screen Shaking in Windows 11 – Expert Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-non-functional-hdmi-connection-via-usb/"><u>Troubleshooting a Non-Functional HDMI Connection via USB</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208403692-troubleshooting-audio-issues-for-windows-11-and-7-users-fix-crackling-sounds/"><u>Troubleshooting Audio Issues for Windows 11 & 7 Users - Fix Crackling Sounds!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-windows-11-brightness-control-issues/"><u>Troubleshooting Guide: Fixing Windows 11 Brightness Control Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-11-overcoming-user-profile-service-sign-in-errors/"><u>Troubleshooting Windows 11: Overcoming 'User Profile Service' Sign-In Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixing-the-right-click-function-on-a-mouse-in-windows-11/"><u>Troubleshooting: Fixing the Right-Click Function on a Mouse in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212047394-windows-11s-troublesome-touchscreen-try-these-five-fixes/"><u>Windows 11'S Troublesome Touchscreen? Try These Five Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-sleepy-secret-pc-does-not-awake/"><u>Windows' Sleepy Secret - PC Does Not Awake</u></a></li>
</ul></div>
