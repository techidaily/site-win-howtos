---
title: How To Make Your Cursor Stand Still Once And For All
date: 2024-08-19T07:24:24.910Z
updated: 2024-08-20T07:24:24.910Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How To Make Your Cursor Stand Still Once And For All
excerpt: This Article Describes How To Make Your Cursor Stand Still Once And For All
thumbnail: https://thmb.techidaily.com/109f8e41f016b710f8a0ad598776af950e5e0ec716fb01a083b32b51c83dd241.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

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
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://instagram-videos.techidaily.com/new-boosting-your-profile-top-25-high-gainning-instagram-tags-for-2024/"><u>[New] Boosting Your Profile  Top 25 High-Gainning Instagram Tags for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-free-10-high-quality-passport-photos-available-here/"><u>[New] Free 10 High-Quality Passport Photos Available Here</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-how-to-download-part-of-youtube-video/"><u>[Updated] How to Download Part of YouTube Video?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-snapshot-to-sequence-capturing-life-in-motion/"><u>[Updated] Snapshot to Sequence  Capturing Life in Motion</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-honor-x7b-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Honor X7b Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-ssltls-connection-problems-when-using-firefox-browser/"><u>Addressing SSL/TLS Connection Problems When Using Firefox Browser</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-boot-issues-expert-advice-to-get-you-up-and-running-again/"><u>Beat Boot Issues: Expert Advice to Get You Up and Running Again</u></a></li>
<li><a href="https://extra-information.techidaily.com/breaking-new-ground-top-6-platforms-for-digital-artistry/"><u>Breaking New Ground  Top 6 Platforms for Digital Artistry</u></a></li>
<li><a href="https://win-howtos.techidaily.com/common-solutions-for-intermittent-connectivity-issues-with-wireless-mice-on-modern-operating-systems/"><u>Common Solutions for Intermittent Connectivity Issues with Wireless Mice on Modern Operating Systems</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/compare-and-conquer-why-ios-chatgpt-wins-over-web/"><u>Compare & Conquer: Why iOS ChatGPT Wins Over Web</u></a></li>
<li><a href="https://win-howtos.techidaily.com/destiny-the-second-server-problems-heres-how-to-resolve-them-efficiently/"><u>Destiny the Second Server Problems? Here's How to Resolve Them Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/directx-11-unavailable-troubleshooting-steps-for-graphics-card-compatibility/"><u>DirectX 11 Unavailable? Troubleshooting Steps for Graphics Card Compatibility</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-stop-a-hanging-window-update-on-older-systems-troubleshooting-guide/"><u>Effective Solutions to Stop a Hanging Window Update on Older Systems (Troubleshooting Guide)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-tricks-to-unfreeze-and-optimize-your-windows-11-taskbar-experience/"><u>Effective Tricks to Unfreeze and Optimize Your Windows 11 Taskbar Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209943784-expert-tips-to-fix-continuous-operation-mode-on-windows-11-the-shutdown-problem-solved/"><u>Expert Tips to Fix Continuous Operation Mode on Windows 11 - The Shutdown Problem SOLVED</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-resolve-windows-updates-error-decoding-the-mystery-of-0x8007001f/"><u>Expert Tips to Resolve Windows Updates Error: Decoding the Mystery of 0X8007001F</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-common-issues-why-your-dvd-isnt-working-with-windows/"><u>Fixing Common Issues: Why Your DVD Isn't Working with Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-10-update-mishap-overcome-error-code-0xc1900208/"><u>Fixing the Windows 10 Update Mishap: Overcome Error Code 0xC1900208</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210060400-get-your-keyboards-arrow-keys-working-again-with-these-proven-tips/"><u>Get Your Keyboard's Arrow Keys Working Again with These Proven Tips!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-malfunctioning-keyboard-light-on-windows-and-macos-devices/"><u>How to Fix Malfunctioning Keyboard Light on Windows and macOS Devices</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-14-pro-max-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone 14 Pro Max Data From iOS iCloud? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-of-your-steelseries-arctis-5s-built-in-mic/"><u>How to Restore Functionality of Your SteelSeries Arctis 5'S Built-In Mic</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-12-pro-max-without-passcode-or-face-id-by-drfone-ios/"><u>How to Unlock Apple iPhone 12 Pro Max without Passcode or Face ID</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-strategies-to-fix-frame-rate-drops-and-lags-in-world-of-warcraft/"><u>In-Depth Strategies to Fix Frame Rate Drops and Lags in World of Warcraft</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-dns-failure-discover-4-effortless-solutions-for-restoring-connectivity/"><u>Overcome DNS Failure: Discover 4 Effortless Solutions for Restoring Connectivity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-hp-laptop-camera-glitches-in-windows-11-expert-advice-and-effective-methods/"><u>Overcoming HP Laptop Camera Glitches in Windows 11: Expert Advice and Effective Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/preventing-automatic-startups-tips-and-tricks-for-windows-11-users/"><u>Preventing Automatic Startups: Tips and Tricks for Windows 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-no-device-drivers-detected-a-comprehensive-guide-to-troubleshoot-and-fix-during-windows-7-setup/"><u>Resolving 'No Device Drivers Detected': A Comprehensive Guide to Troubleshoot and Fix During Windows 7 Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-how-to-fix-bluetooth-stack-service-not-starting-problem/"><u>Resolving Issues: How to Fix 'Bluetooth Stack Service Not Starting' Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-win11-non-stop-blue-screen/"><u>Resolving: Win11 Non-Stop Blue Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reworking-records-6-windows-applications-for-date-revision/"><u>Reworking Records: 6 Windows Applications for Date Revision</u></a></li>
<li><a href="https://techidaily.com/sign-a-pdf-v11-document-with-electronic-signature-tool-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>Sign a PDF v1.1 document with electronic signature tool</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-addressing-problems-when-your-computer-cant-communicate-with-the-system-events-service/"><u>Solved: Addressing Problems When Your Computer Can't Communicate With the System Events Service</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-world-of-warcraft-lag-problems-for-seamless-quests-and-battles/"><u>Solving World of Warcraft Lag Problems for Seamless Quests and Battles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-solving-elevated-cpu-use-due-to-audio-device-graph-isolation-on-windows/"><u>Step-by-Step Guide: Solving Elevated CPU Use Due to Audio Device Graph Isolation on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-windows-update-error-0x802e200d-successfully-diy/"><u>Troubleshooting and Resolving Windows Update Error 0X802e200d Successfully [DIY]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-device-detection-issues-with-bluetooth-in-windows-11/"><u>Troubleshooting Guide: Fixing Device Detection Issues with Bluetooth in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-usb-reconnection-issues-solved/"><u>Troubleshooting Guide: USB Reconnection Issues Solved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-reactivating-your-devices-bluetooth-functionality/"><u>Troubleshooting Steps: Reactivating Your Device's Bluetooth Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-netsvc-how-to-troubleshoot-and-reduce-high-svchostexe-network-activity/"><u>Understanding NETsvc: How to Troubleshoot & Reduce High Svchost.exe Network Activity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-is-runtime-broker-and-fix-its-high-cpu-error-on-windows-10-solved/"><u>What Is Runtime Broker and Fix Its High CPU Error on Windows 10 [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wi-fi-troubleshooting-guide-reactivating-wi-fi-on-all-devices/"><u>Wi-Fi Troubleshooting Guide: Reactivating Wi-Fi on All Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212524940-windows-explorer-down-fix-now/"><u>Windows Explorer Down – Fix Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/your-invisible-sd-no-more-anxiety/"><u>Your Invisible SD? No More Anxiety</u></a></li>
</ul></div>
