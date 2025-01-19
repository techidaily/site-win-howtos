---
title: How to Fix 'Windows 11 Couldn't Be Installed' Error - Decode and Solve Error Code 80240020
date: 2025-01-16T16:40:19.531Z
updated: 2025-01-19T18:07:04.347Z
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
<li><a href="https://vp-tips.techidaily.com/1-manycam-cutting-edge-live-streaming-and-virtual-camera-app/"><u>1. ManyCam: Cutting-Edge Live Streaming and Virtual Camera App</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-bp550-revamped-the-ultimate-2023-examination/"><u>2024 Approved BP550 Revamped - The Ultimate 2023 Examination</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-insiders-pick-of-advanced-audio-software-a-vtubers-guide/"><u>2024 Approved Insider's Pick of Advanced Audio Software A Vtuber's Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/are-you-experiencing-issues-with-the-xbox-live-service-or-is-there-a-server-outage/"><u>Are You Experiencing Issues with the Xbox Live Service or Is There a Server Outage?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/boosting-windows-7-launch-times-tips-and-solutions-to-combat-delayed-startups/"><u>Boosting Windows 7 Launch Times: Tips & Solutions to Combat Delayed Startups</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-fixes-to-get-your-logitech-mouse-scroll-wheel-back-on-track/"><u>DIY Fixes to Get Your Logitech Mouse Scroll Wheel Back on Track</u></a></li>
<li><a href="https://technical-tips.techidaily.com/exploding-popularity-on-instagram-discover-these-10-methods-for-creating-viral-content/"><u>Exploding Popularity on Instagram: Discover These 10 Methods for Creating Viral Content</u></a></li>
<li><a href="https://win-howtos.techidaily.com/illuminate-the-path-ahead-strategies-for-dealing-with-monster-hunter-worldcups-blackout-at-boot-and-ensuring-a-colorful-comeback/"><u>Illuminate the Path Ahead - Strategies for Dealing with Monster Hunter: World'cups Blackout at Boot and Ensuring a Colorful Comeback</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-correcting-the-youtube-audio-renderer-malfunction-on-your-windows-10-computer/"><u>Step-by-Step Guide to Correcting the Youtube Audio Renderer Malfunction on Your Windows 10 Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-repairing-damaged-system-files-on-windows-11/"><u>Step-by-Step Solutions: Repairing Damaged System Files on Windows 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/successful-intel-optane-memory-driver-installation-guide-for-windows-systems/"><u>Successful Intel Optane Memory Driver Installation Guide for Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/swift-techniques-for-repairing-problematic-directx-launch-scenarios/"><u>Swift Techniques for Repairing Problematic DirectX Launch Scenarios</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/vidvibes-merge-android-and-ios-insta-photos/"><u>VidVibes Merge Android & iOS Insta Photos</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

