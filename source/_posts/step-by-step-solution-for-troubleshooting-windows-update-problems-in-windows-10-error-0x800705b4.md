---
title: Step-by-Step Solution for Troubleshooting Windows Update Problems in Windows 10 (Error 0X800705b4)
date: 2024-08-19T06:42:38.889Z
updated: 2024-08-20T06:42:38.889Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for Troubleshooting Windows Update Problems in Windows 10 (Error 0X800705b4)
excerpt: This Article Describes Step-by-Step Solution for Troubleshooting Windows Update Problems in Windows 10 (Error 0X800705b4)
thumbnail: https://thmb.techidaily.com/7e02bd572984315c91b0feee5bb97c59ecfef3acd51a935224f88b492a26dbad.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-sure.techidaily.com/n-2024-critical-asmr-series-to-experience/"><u>[New] In 2024, Critical ASMR Series to Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restarts-computer-responds-to-games/"><u>[RESTARTS] Computer Responds to Games</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-innovative-10-ideas-thatll-boost-your-brand-on-igtv/"><u>[Updated] 2024 Approved  Innovative 10 Ideas That'll Boost Your Brand on IGTV</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-social-media-hitmakers-top-10-music-video-recipes-for-fb/"><u>[Updated] In 2024, Social Media Hitmakers - TOP 10 Music Video Recipes for FB</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-perfect-settings-for-live-broadcasts/"><u>[Updated] Perfect Settings for Live Broadcasts</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-broadcast-power-play-which-livestream-tool-should-you-use/"><u>2024 Approved  Broadcast Power Play  Which Livestream Tool Should You Use?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-hd-video-recording-for-windows-10-users/"><u>2024 Approved  HD Video Recording for Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-error-code-24-device-missing-in-windows-1187-environments/"><u>Comprehensive Fixes for Error Code 24 - Device Missing in Windows 11/8/7 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-fix-exe-not-responding-problems-swiftly/"><u>Diagnose and Fix 'Exe Not Responding' Problems Swiftly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-your-device-casting-troubles-in-windows-11-expert-tips/"><u>Diagnosing and Repairing Your Device Casting Troubles in Windows 11: Expert Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-sims-4-game-not-starting-correctly/"><u>Effective Solutions for Sims 4 Game Not Starting Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortlessly-resolve-your-windows-10-continuous-rebooting-dilemma-today/"><u>Effortlessly Resolve Your Windows 10 Continuous Rebooting Dilemma Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-39-explained-effective-solutions-for-your-cd-and-dvd-player-issues/"><u>Error Code #39 Explained: Effective Solutions for Your CD and DVD Player Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-overcoming-monitor-resolution-adjustment-hurdles-now-solved/"><u>Expert Tips for Overcoming Monitor Resolution Adjustment Hurdles – Now Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-successful-installation-of-the-windows-10-version-n-to-n-solutions/"><u>Expert Tips for Successful Installation of the Windows 10 Version N to N: Solutions</u></a></li>
<li><a href="https://win-solutions.techidaily.com/guide-to-prevent-and-fix-granblue-fantasy-from-crashing-during-relink-on-windows/"><u>Guide to Prevent and Fix Granblue Fantasy From Crashing During ReLink on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-corrupted-windows-store-cache-solutions-explored/"><u>How to Fix a Corrupted Windows Store Cache - Solutions Explored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-non-functional-spacebar-key-on-windows-11-pcs/"><u>How to Fix a Non-Functional Spacebar Key on Windows 11 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-identify-and-change-management-controlled-configuration-settings-in-windows/"><u>How to Identify and Change Management-Controlled Configuration Settings in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-the-your-pc-cant-be-reset-issue-in-windows-10-solution-guide/"><u>How to Overcome the 'Your PC Can’t Be Reset' Issue in Windows 10 - Solution Guide</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-realme-11x-5g-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Realme 11X 5G Back to Operation | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-turn-on-bluetooth-on-windows-7-solved/"><u>How to Turn on Bluetooth on Windows 7 [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restoring-issues-with-your-windows-store-cache-fixed/"><u>How To: Restoring Issues with Your Windows Store Cache (FIXED)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-audacity-for-the-mac-enthusiast-advanced-recording-techniques/"><u>In 2024, Audacity for the Mac Enthusiast  Advanced Recording Techniques</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-yi-cameras-edge-in-cinematic-quality-4k-capture/"><u>In 2024, Yi Camera's Edge in Cinematic Quality 4K Capture</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-conundrum-solved-reactivate-corsair-led-lighting-today/"><u>Keyboard Conundrum Solved - Reactivate Corsair LED Lighting Today</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-oppo-a18-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Oppo A18? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-valorant-lags-post-reboot-solution/"><u>Navigating Valorant Lags: Post-Reboot Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-disruptions-the-guide-to-stop-shockwave-flash-from-crashing-on-google-chrome/"><u>No More Disruptions: The Guide to Stop Shockwave Flash From Crashing on Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-correct-non-compatible-device-drivers-on-windows-os-for-optimal-performance/"><u>Resolved: How To Correct Non-Compatible Device Drivers On Windows OS For Optimal Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-silent-issues-effective-solutions-for-your-acer-laptops-audio-problem/"><u>Resolving Silent Issues: Effective Solutions for Your Acer Laptop's Audio Problem</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/step-by-step-guide-for-igtv-video-submission-for-2024/"><u>Step-by-Step Guide for IGTV Video Submission for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-crc-eliminating-persistent-data-integrity-problems/"><u>Troubleshooting CRC: Eliminating Persistent Data Integrity Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-wacom-digitizer-drivers-missing-issue-in-windows-10/"><u>Troubleshooting Wacom Digitizer Drivers Missing Issue in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-reducing-high-cpu-usage-from-wudfhostexe-in-windows-10/"><u>Understanding and Reducing High CPU Usage From wudfhost.exe in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/update-the-mystery-of-inaccessible-content-is-finally-solved/"><u>Update: The Mystery of 'Inaccessible Content' Is Finally Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-update-woes-heres-how-you-can-successfully-reapply-or-rollback-fixed/"><u>Windows 10 Update Woes? Here's How You Can Successfully Reapply or Rollback [FIXED]</u></a></li>
</ul></div>
