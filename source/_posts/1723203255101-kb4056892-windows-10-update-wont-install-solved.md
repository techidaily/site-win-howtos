---
title: KB4056892 Windows 10 Update Won't Install [SOLVED]
date: 2024-08-19T07:22:40.512Z
updated: 2024-08-20T07:22:40.512Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes KB4056892 Windows 10 Update Won't Install [SOLVED]
excerpt: This Article Describes KB4056892 Windows 10 Update Won't Install [SOLVED]
thumbnail: https://thmb.techidaily.com/48b583faa31b393aa904516c2278bd0e1546bcda1fa4122648e108e1ee1f91de.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-capturing-life-in-hd-top-webcam-recorder-reviews/"><u>[New] Capturing Life in HD - Top WebCam Recorder Reviews</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-tiktok-photo-editing-hack-how-to-ace-the-viral-hacks-easily/"><u>[New] In 2024, TikTok Photo Editing Hack  How to Ace the Viral Hacks Easily</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-junior-jams-and-junction-gaming/"><u>[New] Junior Jams & Junction Gaming</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-navigating-the-world-of-speech-to-text-with-google-expertly/"><u>[New] Navigating the World of Speech-to-Text with Google Expertly</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-procleanse-top-tier-background-removal-tool/"><u>[New] ProCleanse  Top-Tier Background Removal Tool</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-rapid-growth-techniques-for-youtube-views-via-collaborative-videos/"><u>[New] Rapid Growth Techniques for YouTube Views via Collaborative Videos</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-transformative-tools-unveiling-top-6-nft-platforms-for-artists/"><u>[New] Transformative Tools  Unveiling Top 6 NFT Platforms For Artists</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-vlcs-network-live-stream-capabilities/"><u>[Updated] Unveiling VLC's Network Live Stream Capabilities</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-10-essential-gratuitous-lut-downloads-of-the-year/"><u>2024 Approved  Top 10 Essential, Gratuitous LUT Downloads of the Year</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/adobe-premiere-elements-vs-the-rest-top-alternative-video-editors/"><u>Adobe Premiere Elements Vs. The Rest Top Alternative Video Editors</u></a></li>
<li><a href="https://article-files.techidaily.com/best-15-gear-to-secure-your-gopro-on-movement/"><u>Best 15 Gear to Secure Your GoPro on Movement</u></a></li>
<li><a href="https://win-howtos.techidaily.com/binkw32dll-error-comprehensive-solutions-to-restore-file-accessibility/"><u>Binkw32.dll Error: Comprehensive Solutions to Restore File Accessibility</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clear-expert-tips-to-overcome-no-input-detected-screen-challenges/"><u>Clear Expert Tips to Overcome 'No Input Detected' Screen Challenges</u></a></li>
<li><a href="https://win-howtos.techidaily.com/compatible-cameras-list-for-windows-hello/"><u>Compatible Cameras List for Windows Hello</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-strategies-to-resolve-oculus-hardware-issues/"><u>Comprehensive Strategies to Resolve Oculus Hardware Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-and-remedying-the-service-unavailable-a-guide-for-tackling-http-error-503/"><u>Decoding and Remedying the 'Service Unavailable' - A Guide for Tackling HTTP Error 503</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-ethernet-connection-failures-on-pcs-running-windows-11-or-7/"><u>Diagnosing and Repairing Ethernet Connection Failures on PCs Running Windows 11 or 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-fix-your-oculus-gear-problems-2024-update/"><u>Effective Solutions to Fix Your Oculus Gear Problems – 2024 Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-resolving-windows-11-freezing-issues/"><u>Effective Solutions: Resolving Windows 11 Freezing Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-troubleshooting-guide-reviving-your-malfunctioning-usb-connectors/"><u>Effortless Troubleshooting Guide: Reviving Your Malfunctioning USB Connectors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/end-the-unending-startup-loop-expert-tips-for-stabilizing-windows-11/"><u>End the Unending Startup Loop: Expert Tips for Stabilizing Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-nonfunctional-lenovo-mouse-pad-in-various-windows-systems-windows-10-8-and-7/"><u>Fixing a Nonfunctional Lenovo Mouse Pad in Various Windows Systems [Windows 10, 8 & 7]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-ethernet-network-errors-on-your-pc-tips-for-windows-10-and-7-operating-systems/"><u>Fixing Ethernet Network Errors on Your PC: Tips for Windows 10 & 7 Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-through-fixing-a-blocked-windows-10-version-1607-enhancement-rollout/"><u>Guide Through Fixing a Blocked Windows 10 Version 1607 Enhancement Rollout</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-troubleshoot-and-solve-error-0x80n4005-a-step-by-step-guide/"><u>How to Correctly Troubleshoot and Solve Error 0X80n4005 - A Step-by-Step Guide</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-samsung-galaxy-s23-fe-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-phone-number-from-your-apple-id-from-your-iphone-xs-max-by-drfone-ios/"><u>How To Remove Phone Number From Your Apple ID from Your iPhone XS Max?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-print-to-pdf-not-working-in-windows-11/"><u>How To Resolve 'Print to PDF Not Working' In Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-max-to-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro Max To Android devices? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-fix-a-fatal-exception-handler-error-on-windows/"><u>How to Troubleshoot and Fix a Fatal Exception Handler Error on Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-quick-guide-to-nokia-c210-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Nokia C210 FRP Bypass Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208972954-minecraft-and-windows-woes-no-more-solve-your-video-card-driver-problems-today/"><u>Minecraft and Windows Woes No More - Solve Your Video Card Driver Problems Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-resource-allocation-in-complex-system-environments/"><u>Optimizing Resource Allocation in Complex System Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-driver-problems-making-your-wd-my-passport-ultra-visible-in-windows/"><u>Overcoming Driver Problems: Making Your WD My Passport Ultra Visible in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/perfecting-your-streamgame-recording-in-obs-fixes-for-blackout-troubles/"><u>Perfecting Your Stream/Game Recording in OBS – Fixes for Blackout Troubles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-deactivated-led-lights-on-mac-and-pc-keyboards/"><u>Quick Solutions for Deactivated LED Lights on Mac and PC Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fix-guide-when-the-printer-driver-host-hangs-up-on-32-bit-os/"><u>Resolved: Fix Guide - When the Printer Driver Host Hangs Up on 32-Bit OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-notorious-0x8-80071ac3-error-cleaning-a-dirty-storage-device/"><u>Resolving the Notorious 0X8 80071AC3 Error: Cleaning a 'Dirty' Storage Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-audio-on-steam-effective-and-swift-methods-for-gamers/"><u>Revive Audio on Steam: Effective & Swift Methods for Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-solutions-to-reset-and-optimize-your-keyboard-performance/"><u>Simple Solutions to Reset and Optimize Your Keyboard Performance</u></a></li>
<li><a href="https://tech-hub.techidaily.com/tech-titans-meet-ms-bzs-merger-explored-with-ais-role-in-creativity-podcast/"><u>Tech Titans Meet: MS, BZ's Merger Explored with AI's Role in Creativity [Podcast]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-side-by-side-assembly-errors-in-windows-10-systems-diy/"><u>Troubleshooting & Resolving Side-by-Side Assembly Errors in Windows 10 Systems [DIY]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-eliminating-lag-time-on-windows-11-keyboards/"><u>Troubleshooting and Eliminating Lag Time on Windows 11 Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-rpc-server-unreachable-errors-on-pc/"><u>Troubleshooting Steps for 'RPC Server Unreachable' Errors on PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-fixing-a-broken-lenovo-print-recognition-feature/"><u>Troubleshooting Tips for Fixing a Broken Lenovo Print Recognition Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-printer-driver-issues-solutions-included/"><u>Troubleshooting Windows Printer Driver Issues – Solutions Included</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208782428-troubleshooting-your-astro-a40s-unresponsive-mic-solutions-revealed/"><u>Troubleshooting Your Astro A40's Unresponsive Mic - Solutions Revealed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unity-graphics-error-solved-overcome-the-failed-to-initialize-hurdle-easily/"><u>Unity Graphics Error Solved: Overcome the 'Failed to Initialize' Hurdle Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unraveling-the-mystery-effective-ways-to-address-continuous-reboots-in-windows-10/"><u>Unraveling the Mystery: Effective Ways to Address Continuous Reboots in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207691368-what-to-do-if-windows-10-doesnt-recognize-your-logitech-keyboard/"><u>What to Do if Windows 10 Doesn’t Recognize Your Logitech Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/yac551-yamahaaturbosound-ii-sound-module-based-on-the-ymf794bymu794b-dsp-plus-midi-synthesader-plus-codec-and-256-mb-of-spiram-for-sample-storage-instead-of55/"><u>YAC551 - Yamaha'aturboSound II Sound Module Based on the YMF794B/YMU794B (DSP + MIDI Synthesader + Codec) and 256 MB of SPIRAM for Sample Storage Instead of ROM. It Also Includes a Second Audio Input Connector</u></a></li>
</ul></div>
