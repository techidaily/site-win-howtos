---
title: "Fixing PC Crashes During Games: Solutions for Windows 11, 10, 7, 8.1 & 8"
date: 2024-10-12T18:52:24.039Z
updated: 2024-10-15T21:10:10.772Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing PC Crashes During Games: Solutions for Windows 11, 10, 7, 8.1 & 8"
excerpt: "This Article Describes Fixing PC Crashes During Games: Solutions for Windows 11, 10, 7, 8.1 & 8"
thumbnail: https://thmb.techidaily.com/75040013d17be0726faccbc397c3b3541c1732db61566ed595168e5f4f1378d7.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://tech-hub.techidaily.com/a-critical-look-at-auto-gpt-solo-use/"><u>A Critical Look at Auto-GPT Solo Use</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-guide-on-integrating-nintendo-switch-game-system-with-television-display-for-enhanced-gaming-fun/"><u>Comprehensive Guide on Integrating Nintendo Switch Game System With Television Display for Enhanced Gaming Fun</u></a></li>
<li><a href="https://win-howtos.techidaily.com/exiting-question-unreal-and-d3d-part-ways/"><u>Exiting Question: Unreal and D3D Part Ways?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-correcting-steam-game-setup-failures-during-updates-or-new-installs/"><u>Guide to Correcting Steam Game Setup Failures During Updates or New Installs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-addressing-windows-problem-inability-to-locate-a-suitable-printer-driver-fixed/"><u>Guide: Addressing Windows Problem - Inability to Locate a Suitable Printer Driver [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-windows-11-kb5003607-0x8007cdfe-update-problem/"><u>How to Fix the Windows 11 KB5003607 (0X8007CDFE) Update Problem</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-realme-narzo-60-5g-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Realme Narzo 60 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-icloud-lock-from-your-iphone-12-pro-max-and-ipad-by-drfone-ios/"><u>In 2024, How to fix iCloud lock from your iPhone 12 Pro Max and iPad</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-masterful-use-of-digital-boards-in-web-meetings-across-appleandroid-and-laptops/"><u>In 2024, Masterful Use of Digital Boards in Web Meetings Across Apple/Android & Laptops</u></a></li>
<li><a href="https://win-answers.techidaily.com/life-is-strange-resolving-the-true-colors-glitch-a-step-by-step-tutorial/"><u>Life Is Strange: Resolving the True Colors Glitch - A Step by Step Tutorial</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-the-solution-to-unstuck-yourself-from-far-cry-ergy-screen-deadlock/"><u>Mastering the Solution to Unstuck Yourself From Far Cry Ergy Screen Deadlock</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/next-gen-graphics-the-latest-upgrade-to-windows-11s-geforce-210-drivers/"><u>Next-Gen Graphics: The Latest Upgrade to Windows 11'S GeForce 210 Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-eliminating-screen-tearing-issues-in-valorant-a-step-by-step-guide/"><u>Resolved: Eliminating Screen Tearing Issues in VALORANT - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-graphics-card-compatibility-issues-with-fortnite-on-windows/"><u>Resolving Graphics Card Compatibility Issues with Fortnite on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208665187-solving-the-sims-4-not-launching-problem-a-step-by-step-guide/"><u>Solving the 'Sims 4 Not Launching' Problem: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/speculating-on-language-models-the-future-of-gpt-5/"><u>Speculating on Language Models: The Future of GPT-5?</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/streaming-your-favorite-movies-and-shows-in-subtitled-hd-how-to-use-chromecast-with-mkv-videos/"><u>Streaming Your Favorite Movies and Shows in Subtitled HD - How to Use Chromecast with MKV Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-errors-when-opening-microsoft-store/"><u>Troubleshooting Guide: Resolving Errors When Opening Microsoft Store</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-solutions-fixing-common-problems-with-your-wacom-tablet/"><u>Troubleshooting Solutions: Fixing Common Problems with Your Wacom Tablet</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

