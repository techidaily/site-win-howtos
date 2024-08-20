---
title: Windows 11 Update Error Code 0X80240034 Explained and How to Fix It Successfully
date: 2024-08-19T07:04:35.040Z
updated: 2024-08-20T07:04:35.040Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 11 Update Error Code 0X80240034 Explained and How to Fix It Successfully
excerpt: This Article Describes Windows 11 Update Error Code 0X80240034 Explained and How to Fix It Successfully
thumbnail: https://thmb.techidaily.com/fa206782af9b714e31a62f7ae5d0a20ed9b7932652ed0826ec0104cd05df9774.jpg
---

## How to Fix Windows Update Error Code 0X8024002E Easily

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

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
16. Click**OK** and then click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
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
<li><a href="https://snapchat-videos.techidaily.com/new-iphone-camera-roll-synergy-with-snapchat-sharing/"><u>[New] IPhone Camera Roll Synergy with Snapchat Sharing</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/evealing-youtubes-showcase-of-notable-user-comments/"><u>[New] Revealing YouTube's Showcase of Notable User Comments</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-elevate-your-online-presence-with-these-top-30-username-ideas/"><u>[Updated] In 2024, Elevate Your Online Presence with These Top 30 Username Ideas</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-unlock-social-connectivity-with-downloader-tools/"><u>[Updated] In 2024, Unlock Social Connectivity with Downloader Tools</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-affordable-action-camera-deals-top-6-for-less-than-100-only/"><u>2024 Approved  Affordable Action Camera Deals  Top 6 for Less Than $100 Only</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-subtle-harmonies-on-desktop-systems/"><u>2024 Approved  Subtle Harmonies on Desktop Systems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/canons-spectral-conversion-paid-and-gratis-lut-tools-for-2024/"><u>Canon's Spectral Conversion  Paid & Gratis LUT Tools for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209008590-connectivity-hacks-for-your-xbox-one-controller-overcoming-synchronization-challenges-easily/"><u>Connectivity Hacks for Your Xbox One Controller – Overcoming Synchronization Challenges Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corrected-key-media-transfer-components-lacking-on-your-pcs-hardware-list/"><u>Corrected: Key Media Transfer Components Lacking on Your PC's Hardware List</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-disruptions-in-connectivity-to-off-site-servers/"><u>Diagnosing and Repairing Disruptions in Connectivity to Off-Site Servers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fixes-stop-windows-11-endless-reboots/"><u>Effortless Fixes: Stop Windows 11 Endless Reboots</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-eliminate-windows-10-setup-problem-decode-error-code-80240020/"><u>Expert Tips to Eliminate Windows 10 Setup Problem - Decode Error Code 80240020</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208065872-fix-my-surface-wont-charge-problem-expert-tips-for-a-full-battery/"><u>Fix My Surface Won't Charge Problem – Expert Tips for a Full Battery</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-print-screen-key-malfunction-on-windows-11-and-10/"><u>Fixing the Issue: Print Screen Key Malfunction on Windows 11 & 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hardware-breakdown-unrecoverable-issue/"><u>Hardware Breakdown: Unrecoverable Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-msmpengexe-high-cpu-usage-in-windows-11-complete-solution/"><u>How to Fix MsMpEng.exe High CPU Usage in Windows 11: Complete Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-update-failure-in-warframe-solutions-and-tips/"><u>How to Resolve 'Update Failure' In Warframe - Solutions & Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-repair-windows-update-glitches-now/"><u>How To Successfully Repair Windows Update Glitches, Now</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-vivo-x100-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Vivo X100 Screen | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-webcam-troubleshooting-quick-fixes-to-get-you-back-on-camera/"><u>Lenovo Webcam Troubleshooting: Quick Fixes to Get You Back on Camera</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/leverage-hashtags-for-top-ranked-fb-pages/"><u>Leverage Hashtags for Top-Ranked FB Pages</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-pubg-top-solutions-for-eliminating-game-lags/"><u>Optimizing PUBG: Top Solutions for Eliminating Game Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-issues-with-component-configuration-in-windows-operating-systems/"><u>Overcoming Issues with Component Configuration in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-lockup-solving-initialization-issues-in-destiny-2/"><u>Overcoming the Lockup: Solving Initialization Issues in Destiny 2</u></a></li>
<li><a href="https://win-howtos.techidaily.com/problem-solved-correcting-login-keyboard-connectivity-issues/"><u>Problem Solved: Correcting Login Keyboard Connectivity Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-lenovo-mouse-pad-problems-in-windows-systems-a-step-by-step-fix/"><u>Resolve Your Lenovo Mouse Pad Problems in Windows Systems: A Step-by-Step Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-common-issues-with-initializing-smartaudio/"><u>Resolved: Common Issues with Initializing SmartAudio</u></a></li>
<li><a href="https://games-able.techidaily.com/reverting-xbox-wireless-controls-on-s-and-x/"><u>Reverting Xbox Wireless Controls on S and X</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-input-devices-troubleshoot-unresponsive-mouse-and-keyboard-on-windows-7-systems/"><u>Reviving Input Devices: Troubleshoot Unresponsive Mouse and Keyboard on Windows 7 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/scrolling-gain-windows-mouse-mastery/"><u>Scrolling Gain: Windows Mouse Mastery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-usb-connection-issues-on-your-pc-running-windows-10-or-11/"><u>Solving USB Connection Issues on Your PC Running Windows 10 or 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-wevideo-the-simple-way-to-make-professional-looking-videos/"><u>Updated 2024 Approved WeVideo The Simple Way to Make Professional-Looking Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-compatible-solutions-for-a-malfunctioning-laptop-touchpad-fixes-for-1187/"><u>Windows-Compatible Solutions for a Malfunctioning Laptop Touchpad: Fixes for 11/8/7</u></a></li>
</ul></div>
