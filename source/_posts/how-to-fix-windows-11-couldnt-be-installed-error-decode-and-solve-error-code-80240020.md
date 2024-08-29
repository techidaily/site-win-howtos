---
title: How to Fix 'Windows 11 Couldn't Be Installed' Error - Decode and Solve Error Code 80240020
date: 2024-08-28T00:27:31.635Z
updated: 2024-08-29T00:27:31.635Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix 'Windows 11 Couldn't Be Installed' Error - Decode and Solve Error Code 80240020
excerpt: This Article Describes How to Fix 'Windows 11 Couldn't Be Installed' Error - Decode and Solve Error Code 80240020
thumbnail: https://thmb.techidaily.com/66380fee6148181c7fbef919ab70be5b7f03dcd6ba9d00048b2c822f6ae741fb.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-soundsnatcher-free-toolkit-insights-and-usage/"><u>[New] 2024 Approved  SoundSnatcher Free Toolkit  Insights & Usage</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-harnessing-your-phone-for-virtual-world-explorations-for-2024/"><u>[New] Harnessing Your Phone for Virtual World Explorations for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-prime-picks-for-live-tv-access-and-streaming/"><u>[New] Prime Picks for Live TV Access and Streaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-screen-flickering-in-windows-10/"><u>[Solved] Screen Flickering in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-unreal-engine-is-exiting-due-to-d3d-device-being-lost/"><u>[Solved] Unreal Engine Is Exiting Due to D3D Device Being Lost</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-windows-10-slow-shutdown-issue/"><u>[Solved] Windows 10 Slow Shutdown Issue</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-the-ultimate-disco-streaming-guide-3-essential-recording-methods/"><u>[Updated] 2024 Approved  The Ultimate Disco Streaming Guide  3 Essential Recording Methods</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-oppo-reno-8t-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/adjustment-woes-windows-11-resolution-halted/"><u>Adjustment Woes - Windows 11 Resolution Halted</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-and-repairing-disk-write-errors-in-steam-with-simple-techniques/"><u>Bypassing and Repairing Disk Write Errors in Steam with Simple Techniques</u></a></li>
<li><a href="https://extra-information.techidaily.com/capture-striking-shots-using-leading-lines-iphone-for-2024/"><u>Capture Striking Shots Using Leading Lines (iPhone) for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/creating-immersive-video-games-experiences-on-steam/"><u>Creating Immersive Video Games Experiences on Steam</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-87-fixing-the-parameter-is-incorrect-in-loadlibrary-issues/"><u>Error Code 87: Fixing 'The Parameter Is Incorrect' In LoadLibrary Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-fixes-for-unexpected-system-restarts-in-windows-10/"><u>Expert Fixes for Unexpected System Restarts in Windows 10</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/expert-strategies-for-seamless-clip-composition-for-2024/"><u>Expert Strategies for Seamless Clip Composition for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-get-your-keyboards-light-turned-on-again-in-mac-oswindows/"><u>Expert Tips to Get Your Keyboard's Light Turned On Again in Mac OS/Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-error-code-0x800f020b-during-your-xerox-update-on-pcs-running-windows/"><u>Expert Tips to Overcome Error Code 0X800F020B During Your Xerox Update on PCs Running Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206059037-fast-track-to-fixing-error-code-0x887a0006-a-speedier-solution-guide/"><u>Fast Track to Fixing Error Code 0X887A0006 – A Speedier Solution Guide!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-laptops-non-charging-battery-issues-simple-solutions-inside/"><u>Fix Your Laptop's Non-Charging Battery Issues - Simple Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-frame-drops-and-lag-in-fallout-2022-resolutions/"><u>Fixing Frame Drops and Lag in Fallout ([2022 Resolutions])</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-back-online-expert-advice-on-fixing-service-stopped-errors-in-hamachi/"><u>Get Back Online: Expert Advice on Fixing 'Service Stopped' Errors in Hamachi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unable-to-start-program-error-code-0xc000007b/"><u>How to Fix 'Unable to Start Program' Error Code 0xC000007B</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unresponsive-usb-connectivity-issues-in-windows-11-devices/"><u>How to Fix Unresponsive USB Connectivity Issues in Windows 11 Devices</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-securely-archive-device-drivers-in-windows-11-and-10-environments/"><u>How to Securely Archive Device Drivers in Windows 11 and 10 Environments</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-accessible-no-cost-tools-to-craft-professional-slideshows/"><u>In 2024, Accessible, No-Cost Tools to Craft Professional Slideshows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-fix-youtube-buffering-on-mobile-fb-content/"><u>In 2024, Fix YouTube Buffering on Mobile  FB Content</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-xiaomi-13t-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Xiaomi 13T Phone Pattern Lock</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-motorola-g54-5g-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Motorola G54 5G Device</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-understanding-av1-a-first-step-for-beginners/"><u>In 2024, Understanding AV1  A First Step for Beginners</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-failure-in-windows-10/"><u>Keyboard Failure in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-not-working-heres-how-to-restore-full-functionality/"><u>Keyboard Not Working? Here's How to Restore Full Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204633189-lenovo-fingerprint-recognition-woes-heres-how-you-can-fix-it-without-a-hitch/"><u>Lenovo Fingerprint Recognition Woes? Here’s How You Can Fix It Without a Hitch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mysterious-keys-cessation/"><u>Mysterious Keys Cessation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-crashes-in-nier-automata-on-windows-comprehensive-solutions/"><u>No More Crashes in Nier: Automata on Windows - Comprehensive Solutions</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/no-more-latency-choose-av1-for-youtube-playback-for-2024/"><u>No More Latency  Choose AV1 for YouTube Playback for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-touchpad-trouble-expert-tips-to-restore-functionality-on-your-pc/"><u>Overcoming Touchpad Trouble: Expert Tips to Restore Functionality on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-slow-shutdown-woes-on-windows-10-devices/"><u>Quick Fixes for Slow Shutdown Woes on Windows 10 Devices</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/quick-ukrainian-understanding-through-deliberate-10-minute-practices-93-chars/"><u>Quick Ukrainian Understanding Through Deliberate 10-Minute Practices (93 Chars)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/recognizing-and-repairing-a-missing-hard-drive-connection-issue-fixes/"><u>Recognizing and Repairing a Missing Hard Drive Connection Issue [FIXES]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-identifying-and-fixing-windows-update-database-issues-on-windows-11/"><u>Resolved: Identifying and Fixing Windows Update Database Issues on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-steam-connection-issues-overcoming-could-not-connect-to-steam-network-errors/"><u>Resolving Steam Connection Issues: Overcoming 'Could Not Connect to Steam Network' Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-steps-for-fixing-your-windows-update-hang-on-0-barrier/"><u>Simple Steps for Fixing Your Windows' Update Hang on 0%% Barrier</u></a></li>
<li><a href="https://win-howtos.techidaily.com/small-cell-lung-cancer-sclc-is-highly-aggressive-with-rapid-growth-rates-and-early-metastasis/"><u>Small Cell Lung Cancer (SCLC) Is Highly Aggressive, with Rapid Growth Rates and Early Metastasis.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-laptops-touchpad-problems-in-windows-11-8-and-7/"><u>Solving Your Laptop's Touchpad Problems in Windows 11, 8 and 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-the-rpc-server-accessibility-error-in-windows/"><u>Step-by-Step Guide: Correcting the RPC Server Accessibility Error in Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-ultimate-pathway-autoplay-youtube-videos-within-fb-networks-for-2024/"><u>The Ultimate Pathway  Autoplay YouTube Videos Within FB Networks for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-your-touchscreen-in-windows-10-discover-how-to-fix-it-using-5-different-approaches/"><u>Trouble with Your Touchscreen in Windows 10? Discover How to Fix It Using 5 Different Approaches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202609749-trouble-with-your-windows-11-taskbar-easy-fixes-to-restore-functionality-now/"><u>Trouble with Your Windows 11 Taskbar? Easy Fixes to Restore Functionality Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solutions-for-winodws-10s-persistent-0x800705b4-update-problem-resolved/"><u>Troubleshooting & Solutions for Winodws 10'S Persistent 0X800705b4 Update Problem [Resolved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-right-click-issues-on-windows-11-a-step-by-step-guide/"><u>Troubleshooting Right-Click Issues on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-repairing-broken-files-in-windows-11-systems/"><u>Troubleshooting Tips: Repairing Broken Files in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-fix-destiny-2-wont-initialize-issue/"><u>Troubleshooting: How to Fix 'Destiny 2 Won't Initialize' Issue</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-5-steps-to-ensure-your-windows-system-is-safe-and-locked/"><u>Ultimate Guide: 5 Steps To Ensure Your Windows System Is Safe and Locked</u></a></li>
<li><a href="https://driver-download.techidaily.com/update-your-razer-naga-mouse-software-for-windows-systems/"><u>Update Your Razer Naga Mouse Software for Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-11-volume-troubleshooting-guide-get-your-sounds-back-today/"><u>Win 11 Volume Troubleshooting Guide - Get Your Sounds Back Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-camera-malfunction-overcome-error-code-0xa00f4292-with-these-simple-fixes/"><u>Windows Camera Malfunction? Overcome Error Code 0XA00F4292 with These Simple Fixes</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->