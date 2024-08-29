---
title: "Journey's End: Fortnite Launching Successfully"
date: 2024-08-28T00:35:29.815Z
updated: 2024-08-29T00:35:29.815Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Journey's End: Fortnite Launching Successfully"
excerpt: "This Article Describes Journey's End: Fortnite Launching Successfully"
thumbnail: https://thmb.techidaily.com/4813724d53b5cad6b133b133522844cf1838d9743eb384dd583504939bc1aed2.jpg
---

## Winning Against Windows Update Challenge: Solving Error 0X802n02e Successfully

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
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
16. Click**OK** and then click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-web.techidaily.com/024-approved-a-compreayers-guide-to-growth-updating-youtube-metadata/"><u>[New] 2024 Approved  A Compreayer's Guide to Growth  Updating YouTube Metadata</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-dispelling-myths-about-tiktok-bans/"><u>[New] 2024 Approved  Dispelling Myths About TikTok Bans</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-beneath-the-surface-a-deep-dive-into-private-story-making-for-2024/"><u>[New] Beneath the Surface  A Deep Dive Into Private Story Making for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-harmony-at-hand-free-audio-from-fb/"><u>[New] Harmony at Hand  Free Audio From FB</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-obs-live-broadcasting-on-instagram/"><u>[New] In 2024, OBS Live Broadcasting on Instagram</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-next-gen-options-to-record-high-quality-gaming-footage/"><u>[Updated] Next Gen Options to Record High-Quality Gaming Footage</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-infinix-note-30-pro-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Infinix Note 30 Pro Fingerprint Lock</u></a></li>
<li><a href="https://win-howtos.techidaily.com/combat-svchostexes-extreme-cpu-drain-on-windows-11-effective-fixes-and-tips-unveiled/"><u>Combat svchost.exe's Extreme CPU Drain on Windows 11: Effective Fixes and Tips Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/compreh-ensive-strategies-for-diagnosing-and-repairing-windows-driver-power-problem/"><u>Compreh Ensive Strategies for Diagnosing & Repairing Window's Driver Power Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210600140-constraint-a-do-not-redact-any-percentages-or-numerical-values/"><u>Constraint A: Do Not Redact Any Percentages or Numerical Values.</u></a></li>
<li><a href="https://games-able.techidaily.com/crafting-a-champion-critical-settings-to-customize-in-fps-games/"><u>Crafting a Champion: Critical Settings to Customize in FPS Games</u></a></li>
<li><a href="https://win-howtos.techidaily.com/deciphering-and-correcting-error-code-1068-on-your-windows-pc-solved/"><u>Deciphering and Correcting Error Code 1068 on Your Windows PC [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-and-troubleshooting-windows-blue-screen-error-0xc00x00000e9-a-step-by-step-guide/"><u>Decoding and Troubleshooting Windows Blue Screen Error 0xC00^X00000E9: A Step-by-Step Guide</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/experience-effortless-baking-with-the-power-of-cookiebot/"><u>Experience Effortless Baking with the Power of Cookiebot</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-and-fix-error-144-in-livekernel-event/"><u>Expert Tips to Overcome and Fix Error 144 in LiveKernel Event</u></a></li>
<li><a href="https://win-howtos.techidaily.com/feature-update-to-windows-11-version-1607-failed-to-install/"><u>Feature Update to Windows 11 Version 1607 Failed to Install</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-microsoft-print-to-pdf-error-a-step-by-step-guide-for-windows-10-and-11-users/"><u>Fixing the Microsoft Print to PDF Error: A Step-by-Step Guide for Windows 10 and 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-ensure-your-touchpad-cursor-remains-active-in-windows-11/"><u>How To Ensure Your Touchpad Cursor Remains Active In Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-windows-plus-shift-plus-s-working-again-on-your-pc-windows-1110/"><u>How to Get Windows + Shift + S Working Again on Your PC (Windows 11/10)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-an-unresponsive-integrated-webcam-in-the-windows-environment/"><u>How to Repair an Unresponsive Integrated Webcam in the Windows Environment</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-samsung-galaxy-m54-5g-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Samsung Galaxy M54 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-the-essential-enhancements-for-a-superstar-stardew-fan/"><u>In 2024, The Essential Enhancements for a Superstar Stardew Fan</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-windows-11-stalling-at-startup-quick-fix-tips-and-tricks/"><u>Overcome Windows 11 Stalling at Startup: Quick Fix Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-windows-file-access-issues-no-more-errors/"><u>Resolve Windows File Access Issues: No More Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revived-stalled-audio-on-discord/"><u>Revived Stalled Audio on Discord</u></a></li>
<li><a href="https://win-howtos.techidaily.com/say-goodbye-to-drawn-out-closures-solving-the-puzzle-of-a-lethargic-windows-10-shutdown/"><u>Say Goodbye to Drawn-Out Closures: Solving the Puzzle of a Lethargic Windows 10 Shutdown</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-the-problem-dealing-with-non-functional-winplusshiftpluss-in-windows-versions-11-and-10/"><u>Solve the Problem: Dealing With Non-Functional Win+Shift+S in Windows Versions 11 & 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-cannot-reset-this-computer-issue-in-windows-10/"><u>Solving the 'Cannot Reset This Computer' Issue in Windows 10</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshoot-imessage-problems-effortlessly-top-7-solutions-for-apple-devices/"><u>Troubleshoot iMessage Problems Effortlessly: Top 7 Solutions for Apple Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-reset-issues-on-your-windows-11-machine-expert-solutions/"><u>Troubleshooting and Fixing Reset Issues on Your Windows 11 Machine: Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-speaker-issues-and-fixing-high-pitched-sounds-in-windows-os-tips-and-solutions/"><u>Troubleshooting Speaker Issues and Fixing High-Pitched Sounds in Windows OS: Tips & Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-to-diagnose-and-repair-driverpowerstatefailure-glitches/"><u>Ultimate Guide to Diagnose and Repair DRIVER_POWER_STATE_FAILURE Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-correcting-entry-point-missing-mistakes-on-windows-devices/"><u>Understanding and Correcting ‘Entry Point Missing’ Mistakes on Windows Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-netflix-connectivity-issues-is-it-just-you/"><u>Understanding Netflix Connectivity Issues - Is It Just You?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-isnt-my-logitech-keyboard-working-on-windows-11-troubleshooting-tips/"><u>Why Isn't My Logitech Keyboard Working on Windows 11? Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-wont-my-computer-shut-down-on-windows-11-proven-methods-to-fix-and-restart-safely/"><u>Why Won't My Computer Shut Down on Windows 11? Proven Methods to Fix and Restart Safely</u></a></li>
</ul></div>
