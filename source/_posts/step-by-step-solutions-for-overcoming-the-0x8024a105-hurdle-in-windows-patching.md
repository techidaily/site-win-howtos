---
title: Step-by-Step Solutions for Overcoming the 0X8024A105 Hurdle in Windows Patching
date: 2024-08-19T07:19:28.890Z
updated: 2024-08-20T07:19:28.890Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for Overcoming the 0X8024A105 Hurdle in Windows Patching
excerpt: This Article Describes Step-by-Step Solutions for Overcoming the 0X8024A105 Hurdle in Windows Patching
thumbnail: https://thmb.techidaily.com/7a3bff4e2eede5438bb2fccedcb9095f7ad51baa5a8f2d8fdc6330db34850673.jpg
---

## Resolving the Troublesome 0X80240017 Windows Update Issue: Proven Solutions

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04d8761fcdb.jpg)

 The**0x80240017** error is a common Windows Update error which happens when you’re downloading or installing your Windows updates and indicates the Windows update failed. It’s generally caused by system files corruption or driver issues. But don’t worry. You can try the solutions below to fix this problem easily.

## Try these fixes

 Here are the solutions that have helped other Windows users resolve error 0x80240017\. You don’t need to try them all; just work your way down the list until everything’s working again.

1. **[Run Windows Update Troubleshooter](#F1)**
2. **[Reset Windows Update Components](#F2)**
3. **[Repair corrupted system files](#F3)**
4. **[Update available drivers](#F4)**

 Note: the screenshots below com from Windows 10, and fixes apply to Windows 11, 8 and 7.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### Fix 1: Run Windows Update Troubleshooter

 Windows Update Troubleshooter is a helpful tool built in Windows system, and you can use it to scan and fix the Windows Update error 0x80240017.

Here’s what you can do:

1. Type**Troubleshoot** in the search box on your desktop, and click**Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04da616dafa.jpg)
2. Click**Troubleshoot** on the left. Click**Windows Update** \>**Run the troubleshooter** .  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
### Fix 2: Reset Windows Update Components

 Windows Update components ensure Windows Update runs properly and the updates can be installed successfully in your computer. If there’s anything wrong during the process, you can try resetting Windows Update components and see how it works.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Copy and paste the following commands one by one in Command Prompt, and press**Enter** on your keyboard.  
**net stop wuauserv**  
**net stop cryptSvc**  
**net stop bits**  
**net stop msiserver**  
 **ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old**  
**ren C:\\Windows\\System32\\catroot2 catroot2.old**  
**net start wuauserv**  
**net start cryptSvc**  
**net start bits**  
**net start msiserver**  
**pause**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dd3338a3f.jpg)
3. Wait for the commands to complete, and exit Command Prompt.
4. Open Windows Update and see if it works properly.

 If your issue still persists, don’t worry, There is something else to try.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
sfc /scannow  
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.

 Try to update Windows again and see if it fixes your error 0x80240017\. Still no luck? There’s one more thing to try.

### Fix 4: Update available drivers

 To ensure your computer operates without problems, you should keep your devices drivers up to date. And here are two ways for you to update drivers:**manually** and**automatically** .

**Manually update your driver** – You can go to the manufacturer’s website of your devices, find the latest driver that’s compatible with your Windows operating system, and download it. Once done, open the downloaded file and follow the instruction to install it to your computer.

**Automatically update your driver** **(recommended)** – If you don’t have time or patience, you can do it automatically with[**Driver** **Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  it takes just 2 clicks (and you get full support and a**30-day money back guarantee** ):

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Then Driver Easy will scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/driver-easy-scan.jpg)
3. Click the**Update** button next to the flagged device(s) to automatically download the driver (you can do that with the FREE version), then install it in your computer.  
 Or click**Update All** to automatically download and install all the correct drivers for problem drivers (you can do this with the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) , and you’ll be prompted to upgrade when your click**Update All** ).  
![](https://images.drivereasy.com/wp-content/uploads/2023/07/driver-easy-update.jpg)
4. Restart your computer to take effect.

 Open Windows Update to download and install updates and it should working now.

 So there you have it – Hope this post helps in resolving your**Windows Update error** **0x80240017** . If you have any questions or suggestions, feel free to leave a comment below.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](/tag-search/?tagId=62)

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
<li><a href="https://win-howtos.techidaily.com/fixed-unplanned-windows-interruption-curbs-cpu-usage/"><u>[FIXED] Unplanned Windows Interruption Curbs CPU Usage</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-revolutionizing-ps2-playtime-on-ios-with-top-emulators/"><u>[New] Revolutionizing PS2 Playtime on iOS with Top Emulators</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-leading-5-digital-recording-devices/"><u>[Updated] 2024 Approved  Leading 5 Digital Recording Devices</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-gamers-paradise-our-candidate-7-best-fps-titles/"><u>[Updated] In 2024, Gamer's Paradise  Our Candidate 7 Best FPS Titles</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-tactical-steps-to-obtain-top-notch-pictorial-content/"><u>[Updated] Tactical Steps to Obtain Top-Notch Pictorial Content</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-adjusting-screenshots-why-does-imovie-alter-video-sizes/"><u>2024 Approved  Adjusting Screenshots  Why Does iMovie Alter Video Sizes?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-platform-power-playout-which-streams-better-obs-or-twitch-studio/"><u>2024 Approved  Platform Power Playout  Which Streams Better - OBS or Twitch Studio?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-the-essential-guide-to-state-of-the-art-screen-recorders/"><u>2024 Approved  The Essential Guide to State-of-the-Art Screen Recorders</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avoid-rdr2-crashes-due-to-high-memory-usage-tips-on-increasing-your-pagefile-size/"><u>Avoid RDR2 Crashes Due to High Memory Usage - Tips on Increasing Your Pagefile Size</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-walkthrough-correcting-windows-10s-troubling-update-bug-0x80240034/"><u>Complete Walkthrough: Correcting Windows 10'S Troubling Update Bug 0X80240034</u></a></li>
<li><a href="https://win-howtos.techidaily.com/connectivity-issue-blizzard-downed/"><u>Connectivity Issue: Blizzard Downed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/destiny-2-launch-issue-resolved-conquering-the-persistent-initializing-error/"><u>Destiny 2 Launch Issue Resolved: Conquering the Persistent Initializing Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-the-youtube-sound-output-issue-in-windows-11-environments/"><u>Diagnosing & Fixing the Youtube Sound Output Issue in Windows 11 Environments</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/direct-guide-saving-twitter-videos-on-your-mobile-device-for-2024/"><u>Direct Guide  Saving Twitter Videos on Your Mobile Device for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-guide-to-canon-mx-series-printer-driver-updates-and-installation-on-your-pc-download-now/"><u>Easy Guide to Canon MX Series Printer Driver Updates & Installation on Your PC - Download Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-for-dealing-with-hang-ups-in-windows-10/"><u>Effective Strategies for Dealing with Hang-Ups in Windows 10</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/elevate-chat-dynamics-pin-messages-with-confidence-in-discord/"><u>Elevate Chat Dynamics  Pin Messages with Confidence in Discord</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202021194-expert-advice-on-correcting-windows-update-failure-with-error-code-0x8024402c-learn-how-here/"><u>Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-diagnosing-and-correcting-the-0x80072efd-glitch-in-windows-11-systems/"><u>Expert Advice on Diagnosing and Correcting the 0X80072EFD Glitch in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-troubleshooting-and-overcoming-windows-mysterious-blackout-problems/"><u>Expert Tips on Troubleshooting and Overcoming Windows' Mysterious Blackout Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-diagnose-and-cure-your-pcs-persistent-black-screen-on-windows-11/"><u>Guide to Diagnose & Cure Your PC's Persistent Black Screen on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hid-integrity-rectified-missing-touch-element/"><u>HID Integrity: Rectified Missing Touch Element</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-white-screen-error-fixes-and-troubleshooting-steps-for-effective-solutions/"><u>Laptop White Screen Error Fixes and Troubleshooting Steps for Effective Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/latest-fixes-for-miracast-not-recognized-on-this-device/"><u>Latest Fixes for 'Miracast Not Recognized on This Device'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-quick-remedies-for-easy-anti-cheat-troubles-in-apee-legends/"><u>Master the Quick Remedies for Easy Anti-Cheat Troubles in Apee Legends</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-startup-challenges-fixing-a-malfunctioning-keyboard-before-logging-in/"><u>Overcoming Startup Challenges: Fixing a Malfunctioning Keyboard Before Logging In</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210046270-persistent-windows-update-problems-heres-what-you-need-to-do/"><u>Persistent Windows Update Problems? Here's What You Need To Do!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/prime-pick-simple-effective-gaming-edit-suites-for-2024/"><u>Prime Pick  Simple, Effective Gaming Edit Suites for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-construction-errors-how-to-ensure-complete-building-loads/"><u>PUBG Construction Errors: How to Ensure Complete Building Loads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-windows-10-screens-touch-sensitivity-with-these-5-proven-strategies/"><u>Revive Your Windows 10 Screen's Touch Sensitivity with These 5 Proven Strategies</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/ridiculousrender-hub-for-2024/"><u>RidiculousRender Hub for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/sfc-and-dism-windows-10-repair-options/"><u>SFC and DISM: Windows 10 Repair Options</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-remedies-for-a-broken-usb-mouse-connection-on-your-notebook/"><u>Step-by-Step Remedies for a Broken USB Mouse Connection on Your Notebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210242492-stop-the-interruptions-solve-your-pcs-unintended-sleep-problems-now/"><u>Stop the Interruptions: Solve Your PC's Unintended Sleep Problems Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/total-war-rome-remastered-how-to-fix-the-latest-game-crash-issues/"><u>Total War Rome Remastered - How To Fix The Latest Game Crash Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-arrow-keys-discover-easy-fixes-to-restore-functionality/"><u>Trouble with Arrow Keys? Discover Easy Fixes to Restore Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-stuck-spacebar-key-under-windows-10/"><u>Troubleshooting a Stuck Spacebar Key Under Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-the-expired-semaphore-time-limit-error-0x80070079/"><u>Troubleshooting and Repairing the Expired Semaphore Time Limit (Error 0X80070079)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-pubg-loads-failure-for-in-game-structures/"><u>Troubleshooting PUBG Loads Failure for In-Game Structures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-techniques-for-fixing-laptop-mouse-freezing-issues/"><u>Troubleshooting Techniques for Fixing Laptop Mouse Freezing Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-overcome-the-extended-semaphore-connection-timeout-error-code-0x80070079/"><u>Troubleshooting: Overcome the Extended Semaphore Connection Timeout (Error Code 0X80070079)</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-best-solarmovie-alternatives-watch-movies-free-online/"><u>Updated Best SolarMovie Alternatives-Watch Movies Free Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-wont-update-discover-the-steps-to-resolve-update-freezing-issues/"><u>Windows 10 Won’t Update? Discover the Steps to Resolve Update Freezing Issues</u></a></li>
</ul></div>
