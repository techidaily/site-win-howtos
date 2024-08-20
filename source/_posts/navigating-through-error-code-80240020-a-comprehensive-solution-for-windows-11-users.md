---
title: "Navigating Through Error Code 80240020: A Comprehensive Solution for Windows 11 Users"
date: 2024-08-19T06:29:30.942Z
updated: 2024-08-20T06:29:30.942Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Navigating Through Error Code 80240020: A Comprehensive Solution for Windows 11 Users"
excerpt: "This Article Describes Navigating Through Error Code 80240020: A Comprehensive Solution for Windows 11 Users"
thumbnail: https://thmb.techidaily.com/3f74865abe3cde83f5178213b8f2028e6688a23ca37959ec467d0c79369ad79b.jpg
---

## Comprehensive Guide: Resolve Windows Update Error 0X8024002E Once and For All

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

 A lot of Windows 10 users have reported an error while trying to update their operating system. What usually happens is they fail to install their system updates, and an error code shows up on Windows Update that says “0x8024002e”.

 If this is also happening to you, you’re no doubt very frustrated. But the good news is you should be able to fix it quite easily. We’ve put together some suggestions to help you fix the problem. Here are a few things you can try:

1. **[Reset your Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
2. **[Modify your Windows Update setting in the registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Perform a clean boot](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-905.png)
3. If prompted, click**Yes** .
4. On the Registry Editor, click**File** , then select**Export** .  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
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
<li><a href="https://some-techniques.techidaily.com/new-excellent-20-copy-free-pubg-thumbnail-sequences/"><u>[New] Excellent 20 Copy-Free PUBG Thumbnail Sequences</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-expert-fb-media-downloader-enhanced-firefox-support/"><u>[New] In 2024, Expert FB Media Downloader  Enhanced FireFox Support</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-boosting-youtube-productions-best-mac-mp4-editors-guide-for-2024/"><u>[Updated] Boosting YouTube Productions  Best Mac MP4 Editors Guide for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-revolutionizing-videography-with-the-impressive-nikon-j5/"><u>[Updated] Revolutionizing Videography with the Impressive Nikon J5</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-itel-a60-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Itel A60 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-comprehensive-fix-guide-to-restore-ethernet-networking-in-windows-10-and-7/"><u>A Comprehensive Fix Guide to Restore Ethernet Networking in Windows 10 & 7</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-samsung-galaxy-xcover-7-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Samsung Galaxy XCover 7 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-tecno-pop-8-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Tecno Pop 8 Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/capturing-your-macbook-pro-screens-a-step-by-step-tutorial-for-2024/"><u>Capturing Your MacBook Pro Screens  A Step-by-Step Tutorial for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/critical-update-overcoming-continuous-restart-issues-in-windows-10-systems/"><u>Critical Update: Overcoming Continuous Restart Issues in Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-error-code-0x80070643-a-step-by-step-guide-to-fixing-windows-updates-and-install-failures/"><u>Decoding Error Code 0X80070643: A Step-by-Step Guide to Fixing Windows Updates and Install Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/detailed-steps-to-correctly-resolve-chrome-could-not-load-plugin-on-windows-10-machines/"><u>Detailed Steps to Correctly Resolve 'Chrome Could Not Load Plugin' On Windows 10 Machines</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-errconnectionrefused-with-pictures/"><u>Fix: ERR_CONNECTION_REFUSED [with Pictures]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-functional-mic-on-windows-10-a-step-by-step-guide/"><u>Fixing a Non-Functional Mic on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/forward-error-correction-fec/"><u>Forward Error Correction (FEC):</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/harmonizing-snaps-integrating-tunes-seamlessly/"><u>Harmonizing Snaps  Integrating Tunes Seamlessly</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-x-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone X without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-error-code-0x8024401c-when-updating-windows-tips-for-windows-11-users/"><u>How to Fix Error Code 0X8024401c When Updating Windows: Tips for Windows 11 Users</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-infinix-zero-30-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Infinix Zero 30 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/make-animated-magic-happen-top-5-online-stop-motion-makers/"><u>Make Animated Magic Happen Top 5 Online Stop Motion Makers</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/mobile-video-editing-with-music-top-apps-for-android-and-ios-for-2024/"><u>Mobile Video Editing with Music Top Apps for Android and iOS for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/netflix-malfunction-on-lg-screens-19-proven-solutions-for-a-seamless-viewing-experience/"><u>Netflix Malfunction on LG Screens: 19 Proven Solutions for a Seamless Viewing Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-error-0x887a0006-a-comprehensive-guide-to-a-quick-and-easy-solution/"><u>Overcoming Error 0X887A0006 - A Comprehensive Guide to a Quick and Easy Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-server-errors-in-overwatch-effective-fixes-and-tips/"><u>Overcoming Server Errors in Overwatch: Effective Fixes and Tips</u></a></li>
<li><a href="https://extra-hints.techidaily.com/professional-insights-enhancing-digital-videos-and-photos-online/"><u>Professional Insights  Enhancing Digital Videos & Photos Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/spread-spectrum-techniques-improve-security-by-making-signals-resistant-to-interference-and-eavesdropping/"><u>Spread Spectrum Techniques Improve Security by Making Signals Resistant to Interference and Eavesdropping.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-game-troubles-tackling-installation-and-updating-problems-efficiently/"><u>Steam Game Troubles: Tackling Installation & Updating Problems Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-correcting-asus-webcam-malfunctions-and-blackouts-for-windows-10-users/"><u>Step-by-Step Guide to Correcting ASUS Webcam Malfunctions and Blackouts for Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fix-a-stuck-windows-11-installation-process/"><u>Step-by-Step Guide to Fix a Stuck Windows 11 Installation Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/teredos-quest-foiled-an-in-depth-look-at-their-qualifying-hurdles/"><u>Teredo's Quest Foiled: An In-Depth Look at Their Qualifying Hurdles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-easy-anti-cheat-glitches-in-apex-legends-fixed/"><u>Troubleshooting Easy Anti-Cheat Glitches in Apex Legends - Fixed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-overcome-cannot-access-device-path-in-windows/"><u>Troubleshooting Guide: Overcome 'Cannot Access Device Path in Windows'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missing-binkw32dll-files-effectively/"><u>Troubleshooting Missing binkw32.dll Files Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-notfound-message-for-d3dcompiler43dll-in-your-system/"><u>Troubleshooting the 'NotFound' Message for d3dcompiler_43.dll in Your System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209859177-why-isnt-the-classic-shortcut-key-combo-work-troubleshooting-steps-inside/"><u>Why Isn't the Classic Shortcut Key Combo Work? Troubleshooting Steps Inside</u></a></li>
<li><a href="https://driver-download.techidaily.com/windows-11-compatible-intel-iris-plus-graphics-card-drivers-version-655/"><u>Windows 11 Compatible Intel Iris Plus Graphics Card Drivers Version 655</u></a></li>
</ul></div>
