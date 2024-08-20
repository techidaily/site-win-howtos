---
title: "Resolving Hardware Malfunctions: Fixing a Frozen HDD/SSD on Windows 11"
date: 2024-08-19T06:17:03.573Z
updated: 2024-08-20T06:17:03.573Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Hardware Malfunctions: Fixing a Frozen HDD/SSD on Windows 11"
excerpt: "This Article Describes Resolving Hardware Malfunctions: Fixing a Frozen HDD/SSD on Windows 11"
thumbnail: https://thmb.techidaily.com/1f2f4c22410ca8169af4ae6d02cdc0eba714608bc6ab4df470b116ebdad1c1fb.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://extra-skills.techidaily.com/new-optimized-text-designs-for-after-effects/"><u>[New] Optimized Text Designs for After Effects</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-bad-image-error-on-windows-1110/"><u>[Solved] Bad Image Error on Windows 11/10</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-elevating-your-content-strategy-with-smart-igtv-hashtags/"><u>[Updated] In 2024, Elevating Your Content Strategy with Smart IGTV Hashtags</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mirthvid-quick-start-for-video-makers/"><u>2024 Approved  MirthVid  Quick Start for Video Makers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/action-seekers-dream-the-ultimate-review-of-sj-cam-s6/"><u>Action Seeker's Dream  The Ultimate Review of SJ-CAM S6</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-and-correcting-the-vibrant-red-screens-of-windows-11-computers/"><u>Addressing and Correcting the Vibrant Red Screens of Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-heat-issues-on-the-hp-spectre-x360-expert-advice-and-fixes/"><u>Dealing with Heat Issues on the HP Spectre X360: Expert Advice & Fixes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/disable-screen-lock-on-asus-by-drfone-android-unlock-android-unlock/"><u>Disable screen lock on Asus</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-samsung-galaxy-s23-fe-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Samsung Galaxy S23 FE FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-tools-for-fixing-windows-11-understanding-sfcdism-utilities/"><u>Effective Tools for Fixing Windows 11: Understanding SFC/DISM Utilities</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-the-lenovo-laptop-webcam-malfunction/"><u>Expert Tips for Fixing the Lenovo Laptop Webcam Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-network-setup-errors-for-an-optimal-dragon-ball-fighterz-gaming-experience/"><u>Fixing Network Setup Errors for an Optimal Dragon Ball FighterZ Gaming Experience</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-keep-your-pcs-w11-drivers-current/"><u>How To Keep Your PC's W11 Drivers Current</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-initial-black-outages-when-playing-monster-hunter-world/"><u>How to Overcome Initial Black Outages When Playing Monster Hunter: World?</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-facebooks-quintessential-changes-for-enthusiasts/"><u>In 2024, Facebook's Quintessential Changes for Enthusiasts</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-vivo-y02t-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Vivo Y02T to Another | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-wireless-methods-to-mirrorapple-iphone-se-and-ipad-to-fire-stick-with-ease-drfone-by-drfone-ios/"><u>In 2024, Wireless Methods to MirrorApple iPhone SE & iPad to Fire Stick With Ease | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/is-it-safe-to-remove-msdia80dll-comprehensive-guide-on-its-purpose-and-maintenance/"><u>Is It Safe to Remove msdia80.dll? Comprehensive Guide on Its Purpose and Maintenance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/latest-techniques-to-eliminate-latency-problems-in-fallout-4/"><u>Latest Techniques to Eliminate Latency Problems in Fallout 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mysterious-shade-monitor-malaise/"><u>Mysterious Shade: Monitor Malaise</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/pinpoint-wolfs-howling-frequency-for-2024/"><u>Pinpoint Wolfs Howling Frequency for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-guide-how-to-enable-microsoft-pdf-printing-in-windows-11/"><u>Resolved Guide: How to Enable Microsoft PDF Printing in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-missing-fixservice-registry-entry-issue-in-windows-10/"><u>Resolving 'Missing' FixService Registry Entry Issue in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-site-unreachable-issues-in-chrome/"><u>Resolving 'Site Unreachable' Issues in Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-game-performance-with-x3daudio17dll-fixes/"><u>Restore Game Performance with X3DAudio1_7.dll Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revolutionized-gaming-pubg-plus-dxgidll-aligned/"><u>Revolutionized Gaming: PUBG + Dxgi.dll Aligned</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/revolutionizing-smartphone-photography-iphone-xs-features-explored/"><u>Revolutionizing Smartphone Photography  IPhone X's Features Explored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-overcoming-non-responsive-file-explorer-problems-on-windows-11-systems/"><u>Solved: Overcoming Non-Responsive File Explorer Problems on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-overcoming-the-vcruntime140dll-file-missing-dilemma-resolution-guide/"><u>Troubleshooting Tips: Overcoming the VCRuntime140.dll File Missing Dilemma [RESOLUTION GUIDE]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-what-to-do-when-you-see-errcachemiss-on-google-chrome/"><u>Troubleshooting: What To Do When You See 'ERR_CACHE_MISS' On Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-is-xinput13dll-and-what-to-do-when-its-missing/"><u>What Is XINPUT1_3.dll (and What to Do When It's Missing)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/windows-11-and-usb-woes-heres-how-to-get-recognition/"><u>Windows 11 and USB Woes? Here's How to Get Recognition!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-keyboard-latency-issues-now-fixed/"><u>Windows 11 Keyboard Latency Issues - Now Fixed</u></a></li>
</ul></div>
