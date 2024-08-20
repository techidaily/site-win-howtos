---
title: How to Use System File Checker (SFC) and Deployment Image Servicing Tool (DISM) in Windows 10 Recovery
date: 2024-08-19T06:52:13.058Z
updated: 2024-08-20T06:52:13.058Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Use System File Checker (SFC) and Deployment Image Servicing Tool (DISM) in Windows 10 Recovery
excerpt: This Article Describes How to Use System File Checker (SFC) and Deployment Image Servicing Tool (DISM) in Windows 10 Recovery
thumbnail: https://thmb.techidaily.com/836b19a99b81c291189dfbcf8add59f634c1fb8aacdfd70319b10cdaec65e638.jpg
---

## Unlock the Potential of System File Checker (SFC) and Deployment Image Servicing (DISM) for Seamless Windows 10 Recovery

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586c9a4e6db41.jpg)

 Windows 10 is equipped with some very handy tools that allow you to solve your computer problems.**System File Checker** and**Deployment Image & Servicing Management** tools are ones of them.

You should consider using these tools when:

**a) troubleshooting a buggy Windows system;**
**b) blue screen of death errors occur;**
**c) applications crash;**
**d) some Windows features are not working properly.**

and etc.

 In this post, we will show you some tools that you can use to solve your computer problems:

[**System File Checker tool**](#1)
[**Deployment Image & Servicing Management tool**](#2)
[**System Restore**](#3)

**Run SFC Command to Repair System Files**

 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Admin)** .

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca149cf04d.png)

 When prompted with the UAC, hit**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca13144fd3.jpg)

2) In the Command Prompt window, type in the following command:

sfc /scannow

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca221df44e.jpg)

Leave the Command Prompt window on until the command completes.

 3) If you see the message saying that   **Windows Resource Protection did not find any integrity violations** , then everything is fine with your system.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca520c7e49.png)

 4) If you see a message saying   **Windows Resource Protection found corrupt files but was unable to fix some of them** , then you need to go to[**safe mode**](https://tools.techidaily.com/drivereasy/download/) and run the system file checker again.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca59f1f21f.jpg)

 If the SFC command doesn’t work well, please mve on to the next section to run the DISM command to fix the SFC command problem and then run SFC command again.

**Run the DISM Command to Fix SFC Problems**

**DISM** stands for Deployment Image & Servicing Management, which is a tool that can fix component store corruption that prevents the SFC command from working properly.

 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca149cf04d.png)

 When prompted with the UAC, hit**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca13144fd3.jpg)

2) In the Command Prompt window, type in the following command:

DISM /Online /Cleanup-Image /RestoreHealth

 Make sure you have made no typo and hit**Enter** .

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca8464439b.jpg)

Wait for a while for the whole process to finishes.

 3) When the whole process finishes, restart your computer. Then run SFC command again so it will help you replace any corrupted files with the correct ones.

 **System Refresh or Reset**

 If the above tools cannot help you solve your computer problems, you can have a try at refreshing or resetting your Windows 10.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586caacd9f489.jpg)

For more detailed information, please go to the posts below:

[**How to refresh Windows 10?**](https://tools.techidaily.com/drivereasy/download/)
[**How to reset Windows 10?**](https://tools.techidaily.com/drivereasy/download/)

**Pro Tip:**
 In many cases, most of your computer problems can be solved by updating your device drivers to their latest versions unless the problems are with the hardware, in which case, you will need to get your hardware replaced.

 To update device drivers, you can use[**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) for assistance. It automatically detects, downloads and updates your missing and outdated device drivers and allow you to finish the whole process in just a couple of minutes.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e8abc65e6ec.jpg)

 If you want to have your own professional tech support and tons of other features in Driver Easy such as driver back up and driver restore, by all means, have a try at the[**professional version of Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . It allows you to update all your device drivers in just ONE click and poof, your computer problems are gone!

 You can always ask for a refund thirty days within the purchase if you are not satisfied with it. What’s with the hold up, come on and have a try at[**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) now!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-dive-deep-into-duality-mastering-multi-video-watching-on-youtube/"><u>[New] 2024 Approved  Dive Deep Into Duality  Mastering Multi-Video Watching on YouTube</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-the-dynamic-duo-of-filmmaking-and-thumbnail-design/"><u>[New] 2024 Approved  The Dynamic Duo of Filmmaking and Thumbnail Design</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-non-networked-game-haven-top-screen-free-android-titles/"><u>[New] Non-Networked Game Haven  Top Screen-Free Android Titles</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-record-rapidly-innovative-iphone-time-lapse-methods/"><u>[New] Record Rapidly  Innovative iPhone Time-Lapse Methods</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-top-techniques-for-high-resolution-webcam-videos/"><u>[Updated] 2024 Approved  Top Techniques for High-Resolution WebCam Videos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-essential-tools-for-every-videographers-kit-for-2024/"><u>[Updated] Essential Tools for Every Videographer's Kit for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-ios-selection-showcase-premier-psp-emulators-ranked-1-5/"><u>[Updated] In 2024, IOS Selection Showcase  Premier PSP Emulators Ranked #1-5</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-olympic-spirits-2022s-short-track-feat/"><u>[Updated] In 2024, Olympic Spirits  2022'S Short-Track Feat</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-best-options-cheap-but-premium-4k-projector-systems/"><u>2024 Approved  Best Options  Cheap but Premium 4K Projector Systems</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-navigating-network-growth-strategies-for-instagram-success/"><u>2024 Approved  Navigating Network Growth  Strategies for Instagram Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-windows-error-0x80070643-tips-for-successful-updates-and-installs/"><u>Bypassing the Windows Error 0X80070643: Tips for Successful Updates and Installs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-oculus-hardware-problems-tips-and-tricks/"><u>Comprehensive Fixes for Oculus Hardware Problems: Tips and Tricks</u></a></li>
<li><a href="https://article-tips.techidaily.com/digital-canvas-delight-premier-apps-for-ipados-artistry-for-2024/"><u>Digital Canvas Delight  Premier Apps for iPadOS Artistry for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-broken-pc-components-in-windows-operating-systems/"><u>Easy Fixes for Broken PC Components in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-when-microsofts-default-browser-crashes-or-freezes/"><u>Easy Fixes for When Microsoft's Default Browser Crashes or Freezes</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/free-video-editing-software-round-up-choose-from-7-options/"><u>Free Video Editing Software Round-Up  Choose From 7 Options</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-over-cpu-usage-by-microsoft-security-essentials-in-windows-11-issue-fixed/"><u>How to Address Over-CPU Usage by Microsoft Security Essentials in Windows 11 [ISSUE FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-hidden-wi-fi-settings-in-windows-11/"><u>How to Fix Hidden Wi-Fi Settings in Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-trouble-with-iphone-12-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>In 2024, Trouble with iPhone 12 Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/noise-gone-boosting-audio-back-to-life-in-forza-horizon-4-expert-tips-and-tricks/"><u>Noise Gone? Boosting Audio Back to Life in Forza Horizon 4 - Expert Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-windows-11-performance-addressing-surge-in-disk-usage-from-microsofts-telemetry-feature/"><u>Optimizing Windows 11 Performance: Addressing Surge in Disk Usage From Microsoft's Telemetry Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rapid-resolution-eliminating-the-out-of-memory-bugs-in-rdr2-through-settings-tweaks/"><u>Rapid Resolution: Eliminating the 'Out of Memory' Bugs in RDR2 Through Settings Tweaks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-microsoft-compatibility-telemetrys-excessive-disk-use-in-windows-10/"><u>Resolving Microsoft Compatibility Telemetry's Excessive Disk Use in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-restoring-visibility-of-bluetooth-on-pcs-device-manager/"><u>Solution Guide: Restoring Visibility of Bluetooth on PC's Device Manager</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-for-the-common-exe-application-failure-problems/"><u>Solution Steps for the Common EXE. Application Failure Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-miracast-issues-upgrading-graphics-drivers-for-seamless-connection/"><u>Solving Miracast Issues: Upgrading Graphics Drivers for Seamless Connection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/squamous-cell-carcinoma-usually-appears-as-a-central-tumor-and-can-lead-to-local-obstruction-symptoms/"><u>Squamous Cell Carcinoma Usually Appears as a Central Tumor and Can Lead to Local Obstruction Symptoms</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-correcting-user-settings-to-driver-failed-alert/"><u>Step-by-Step Solution for Correcting 'User Settings to Driver Failed' Alert</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-windows-reboot-and-choose-boot-device-problem/"><u>Step-by-Step Solution for Windows Reboot and Choose Boot Device Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/text-difficulty-windows-11-copy-issue/"><u>Text Difficulty: Windows 11 Copy Issue</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-art-of-dialogue-in-writing-scripts-for-2024/"><u>The Art of Dialogue in Writing Scripts for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-problem-of-inaccessible-dhcp-servers-a-successful-resolution-guide/"><u>The Problem of Inaccessible DHCP Servers - A Successful Resolution Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fixes-for-overcoming-repeated-rebooting-issues-in-windows-11/"><u>The Ultimate Fixes for Overcoming Repeated Rebooting Issues in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-brightness-control-malfunction-solutions-at-hand/"><u>Windows 10 Brightness Control Malfunction - Solutions at Hand</u></a></li>
</ul></div>
