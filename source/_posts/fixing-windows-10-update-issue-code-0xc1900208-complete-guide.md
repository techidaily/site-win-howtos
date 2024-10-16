---
title: Fixing Windows 10 Update Issue Code 0xC1900208 - Complete Guide
date: 2024-10-10T00:07:14.652Z
updated: 2024-10-16T04:09:42.724Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing Windows 10 Update Issue Code 0xC1900208 - Complete Guide
excerpt: This Article Describes Fixing Windows 10 Update Issue Code 0xC1900208 - Complete Guide
thumbnail: https://thmb.techidaily.com/1dd490a8bd0fd9490b2a1a7e2f3e07f4fe288167493a224a8c1401933c662484.jpeg
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
<li><a href="https://video-screen-grab.techidaily.com/new-the-ultimate-cheat-sheet-to-gameplay-screencasts-in-overwatch-for-2024/"><u>[New] The Ultimate Cheat Sheet to Gameplay Screencasts in Overwatch for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-ideal-top-3ip-apps-for-clear-audio-recordings/"><u>[Updated] In 2024, Ideal Top 3iP Apps for Clear Audio Recordings</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-unlocking-the-secrets-of-success-top-strategies-for-fb-video-growth-for-2024/"><u>[Updated] Unlocking the Secrets of Success Top Strategies for FB Video Growth for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/cookiebot-driven-analytics-and-personalization-solutions/"><u>Cookiebot-Driven Analytics and Personalization Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-recover-corrupt-system-components-on-your-windows-11-device/"><u>Effective Solutions to Recover Corrupt System Components on Your Windows 11 Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-24-decoded-addressing-the-missing-device-warning-in-windows-versions/"><u>Error Code 24 Decoded: Addressing the Missing Device Warning in Windows Versions</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-realme-12-pro-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Realme 12 Pro 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-optimal-solutions-for-webp-to-jpg-image-transformation/"><u>In 2024, Optimal Solutions for WebP-to-JPG Image Transformation</u></a></li>
<li><a href="https://games-able.techidaily.com/key-factors-for-choosing-between-amds-rx-7800-and-7700xt/"><u>Key Factors for Choosing Between AMD's RX 7800 and 7700XT</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mastering-korean-from-home-cutting-edge-online-resource-list/"><u>Mastering Korean From Home: Cutting-Edge Online Resource List</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-boot-not-detected-issues-on-your-device-easy-troubleshooting-steps-inside/"><u>Resolve Boot Not Detected Issues on Your Device - Easy Troubleshooting Steps Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-repair-a-corrupted-windows-store-cache/"><u>Resolved: How to Repair a Corrupted Windows Store Cache</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-device-unrecognized-in-winnt/"><u>Resolving 'Device Unrecognized' In WinNT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-the-hp-laptop-camera-in-windows-10-expert-tips-and-fixes/"><u>Reviving the HP Laptop Camera in Windows 10: Expert Tips & Fixes</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-future-of-search-can-gpt-disrupt-it/"><u>The Future of Search: Can GPT Disrupt It?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-addressing-insufficient-resource-allocation-warnings/"><u>Troubleshooting Guide: Addressing Insufficient Resource Allocation Warnings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-preventing-unexpected-restarts-on-your-windows-10-machine/"><u>Understanding & Preventing Unexpected Restarts on Your Windows 10 Machine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-msdia80dll-importance-and-whether-to-retain/"><u>Understanding msdia80.dll: Importance & Whether To Retain</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unveiling-how-to-regain-access-to-missing-bluetooth-icon-on-windows-11-os/"><u>Unveiling How to Regain Access to Missing Bluetooth Icon on Windows 11 OS</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137224/26400" target="_top" id="2137224">
  <img src="//a.impactradius-go.com/display-ad/26400-2137224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137224/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

