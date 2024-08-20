---
title: "Bypassing the Windows Error 0X80070643: Tips for Successful Updates and Installs"
date: 2024-08-19T06:16:38.478Z
updated: 2024-08-20T06:16:38.478Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Bypassing the Windows Error 0X80070643: Tips for Successful Updates and Installs"
excerpt: "This Article Describes Bypassing the Windows Error 0X80070643: Tips for Successful Updates and Installs"
thumbnail: https://thmb.techidaily.com/12bebdcee4292f456ae693e07b507d42d27bcfe897e62f47668299d0542c70dd.jpg
---

## Winning Against Windows Update Challenge: Solving Error 0X802n02e Successfully

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
16. Click**OK** and then click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-unlocking-potential-tubebuddy-and-channel-mastery/"><u>[New] 2024 Approved  Unlocking Potential  TubeBuddy & Channel Mastery</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-elevate-your-videos-discoverability-mastering-tags/"><u>[New] In 2024, Elevate Your Video's Discoverability - Mastering Tags</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-step-by-step-perfecting-your-vr-recording-skills/"><u>[Updated] In 2024, Step-by-Step  Perfecting Your VR Recording Skills</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-giggle-factor-comparing-humor-in-tiktok-and-snapchat-videos-for-2024/"><u>[Updated] The Giggle Factor  Comparing Humor in TikTok and Snapchat Videos for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-crafty-counterfeits-how-to-find-fake-engagements/"><u>2024 Approved  Crafty Counterfeits  How to Find Fake Engagements</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-superior-economical-live-camera-snapper/"><u>2024 Approved  Superior Economical Live Camera Snapper</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-and-repairing-error-code-28-on-your-windows-computers-device-manager/"><u>Addressing and Repairing Error Code 28 on Your Windows Computer’s Device Manager</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/budding-builders-simple-stylish-mc-habitats-for-2024/"><u>Budding Builders  Simple, Stylish MC Habitats for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/deciphering-facebook-messages-a-study-on-messenger-symbols/"><u>Deciphering Facebook Messages - A Study on Messenger Symbols</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decode-and-defeat-expert-strategies-to-stop-frequent-device-unrecognized-errors-on-your-pc/"><u>Decode and Defeat - Expert Strategies to Stop Frequent ‘Device Unrecognized’ Errors on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-when-microsofts-default-browser-crashes-or-freezes/"><u>Easy Fixes for When Microsoft's Default Browser Crashes or Freezes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-how-to-restore-night-light-feature-in-windows-11/"><u>Fixing the Issue: How to Restore Night Light Feature in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-missing-device-driver-issue-step-by-step-guide-for-windows-answer/"><u>Fixing the Missing Device Driver Issue: Step-by-Step Guide for Windows [Answer]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-updating-or-locating-missing-printer-drivers-in-windows-fixed/"><u>Guide to Updating or Locating Missing Printer Drivers in Windows [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-no-playable-content-detected-in-windows-media-player/"><u>How to Resolve No Playable Content Detected in Windows Media Player</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/ideal-chat-and-meetup-tools-for-large-groups-for-2024/"><u>Ideal Chat & Meetup Tools for Large Groups for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-motorola-defy-2-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Motorola Defy 2 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-for-windows-cannot-read-files-from-device-expert-advice-and-tips/"><u>Mastering the Fix for 'Windows Cannot Read Files From Device': Expert Advice and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-sound-from-my-acer-try-these-pro-tricks-for-audio-recovery/"><u>No Sound From My Acer? Try These Pro Tricks for Audio Recovery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-cpu-use-by-windows-sound-card-driver/"><u>Resolve Excessive CPU Use by Windows Sound Card Driver</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-dxgkrnl-fatal-error-in-videos-on-windows-systems/"><u>Resolving the DXGKRNL Fatal Error in Videos on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-update-error-code-0x80cuh0002-quickly-and-easily/"><u>Resolving Windows Update Error Code 0X80cuh0002 Quickly and Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-disappeared-desktop-icons-for-windows-11-users-issue-resolved/"><u>Restore Disappeared Desktop Icons for Windows 11 Users [ISSUE RESOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-web-connection-woes-tips-to-address-the-err-internet-disconnected-message/"><u>Solving Your Web Connection Woes: Tips to Address the 'ERR INTERNET DISCONNECTED' Message</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-net-framework-35-installation-tackling-and-fixing-error-code-0x800f081f-issues/"><u>Successful .NET Framework 3.5 Installation: Tackling and Fixing Error Code 0X800F081F Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-a-non-functional-laptop-microphone/"><u>Troubleshooting & Repairing a Non-Functional Laptop Microphone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-error-0x802n-2400d-in-windows-updates/"><u>Troubleshooting Guide: Resolving Error 0X802n-2400D in Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-ssl-handshake-failures-when-using-google-chrome-and-mozilla-firefox/"><u>Troubleshooting SSL Handshake Failures When Using Google Chrome and Mozilla Firefox</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ultra-fast-ultra-economical-ev-charger-brands-unveiling-powerdrives-low-cost-high-performance-options/"><u>Ultra Fast, Ultra Economical EV Charger Brands - Unveiling PowerDrive’s Low-Cost High Performance Options</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-brief-on-achieving-clear-background-effects-for-2024/"><u>Ultra-Brief on Achieving Clear Background Effects for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/unleashing-video-potential-steps-to-become-a-staff-pick-favorite/"><u>Unleashing Video Potential  Steps to Become a Staff Pick Favorite</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wacom-pen-wont-connect-to-windows-1110-heres-how-you-can-solve-it/"><u>Wacom Pen Won't Connect to Windows 11/10? Here's How You Can Solve It!</u></a></li>
</ul></div>
