---
title: Step-by-Step Solution for the 'Windows 10 Update Fails with Error 0xC1900208' Problem
date: 2024-10-11T06:39:02.379Z
updated: 2024-10-15T17:56:29.546Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for the 'Windows 10 Update Fails with Error 0xC1900208' Problem
excerpt: This Article Describes Step-by-Step Solution for the 'Windows 10 Update Fails with Error 0xC1900208' Problem
thumbnail: https://thmb.techidaily.com/42900d3cd2ac79478a2e9a5f62d92e59b26835c360208046bfffff6e9458bb6e.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://win-howtos.techidaily.com/fixed-wolfenstein-2-could-not-write-crash-dump/"><u>[Fixed] Wolfenstein 2 Could Not Write Crash Dump</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-express-individuality-with-youtube-backgrounds/"><u>[Updated] 2024 Approved Express Individuality with YouTube Backgrounds</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-visionary-8-tools-transforming-gameplay/"><u>2024 Approved Visionary 8 Tools Transforming Gameplay</u></a></li>
<li><a href="https://some-approaches.techidaily.com/movavim4vmpeg/"><u>免費在線Movavi輕鬆改變M4V成MPEG的視頻編解碼器</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202768284-easy-fixes-for-windows-11-pc-reset-errors-learn-how-to-resolve-them-today/"><u>Easy Fixes for Windows 11 PC Reset Errors - Learn How to Resolve Them Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-fix-cache-miss-error-errcachemiss-on-google-chrome/"><u>Expert Tips to Fix 'Cache Miss' Error (ERR_CACHE_MISS) on Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-boot-guide-overcoming-slow-startups-in-windows-7-systems/"><u>Fast Boot Guide: Overcoming Slow Startups in Windows 7 Systems</u></a></li>
<li><a href="https://facebook.techidaily.com/friendly-fun-in-the-digital-age-staying-positive/"><u>Friendly Fun in the Digital Age: Staying Positive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208017909-huion-pen-issues-heres-how-to-restore-functionality-quickly/"><u>Huion Pen Issues? Here's How to Restore Functionality Quickly!</u></a></li>
<li><a href="https://review-topics.techidaily.com/infinix-data-retrieval-tool-restore-lost-data-from-infinix-note-30i-by-fonelab-android-recover-data/"><u>Infinix Data Retrieval tool – restore lost data from Infinix Note 30i</u></a></li>
<li><a href="https://fox-blue.techidaily.com/iphones-approach-to-high-dynamic-range-photography/"><u>IPhone's Approach to High Dynamic Range Photography</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-pcs-sudden-sleep-problems-with-simple-fixes/"><u>Resolve Your PC's Sudden Sleep Problems with Simple Fixes</u></a></li>
<li><a href="https://extra-information.techidaily.com/revolutionizing-video-praise-with-innovative-approaches/"><u>Revolutionizing Video Praise with Innovative Approaches</u></a></li>
<li><a href="https://games-able.techidaily.com/the-freelance-gamers-compendium-unveiling-the-best-free-steam-titles/"><u>The Freelance Gamer's Compendium: Unveiling the Best Free Steam Titles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-2024-strategies-resolving-bluetooth-connectivity-issues-on-your-windows-10-pc/"><u>Top 2024 Strategies: Resolving Bluetooth Connectivity Issues on Your Windows 10 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-wwe-2k-battlegrounds-level-100-directx-11-glitches/"><u>Troubleshooting Guide: Resolving WWE 2K Battlegrounds' Level 10.0 DirectX 11 Glitches</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unleashing-potential-an-insiders-view-on-the-razer-book-13-laptop/"><u>Unleashing Potential: An Insider’s View on the Razer Book 13 Laptop</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918666/19272" target="_top" id="1918666">
  <img src="//a.impactradius-go.com/display-ad/19272-1918666" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918666/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

