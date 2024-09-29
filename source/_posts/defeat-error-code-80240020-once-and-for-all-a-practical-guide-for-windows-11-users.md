---
title: Defeat Error Code 80240020 Once and For All - A Practical Guide for Windows 11 Users
date: 2024-09-27T23:13:12.229Z
updated: 2024-09-29T00:12:29.809Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Defeat Error Code 80240020 Once and For All - A Practical Guide for Windows 11 Users
excerpt: This Article Describes Defeat Error Code 80240020 Once and For All - A Practical Guide for Windows 11 Users
thumbnail: https://thmb.techidaily.com/647ef78b4d08f0529cf98c1ddda37990b536ba3daaeb866103686a0f1d6cb404.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-firefoxs-prime-expert-downloads-and-addons-navigating-facebook-videos/"><u>[New] In 2024, Firefox's Prime Expert Downloads & Addons Navigating Facebook Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/warmup-needed-after-playing/"><u>[WARMUP] Needed After Playing</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-enhance-your-digital-footprint-upload-tiktoks-on-twitter/"><u>2024 Approved Enhance Your Digital Footprint Upload TikToks on Twitter</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/6-methods-to-share-apple-iphone-14-pro-screen-with-pc-drfone-by-drfone-ios/"><u>6 Methods to Share Apple iPhone 14 Pro Screen with PC | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209144841-biomarker-testing-is-essential-for-identifying-patients-who-will-benefit-from-targeted-therapy/"><u>Biomarker Testing Is Essential for Identifying Patients Who Will Benefit From Targeted Therapy.</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-update-toshiba-dynabook-pc-latest-drivers-for-windows-systems/"><u>Download and Update Toshiba Dynabook PC - Latest Drivers for Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-applied-custom-setup-features-now-fully-functional-again/"><u>Fixes Applied: Custom Setup Features Now Fully Functional Again</u></a></li>
<li><a href="https://extra-hints.techidaily.com/from-two-dimensions-techniques-for-3d-text-in-illustrator/"><u>From Two-Dimensions Techniques for 3D Text in Illustrator</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/network-initialization-issue-resolved-in-dragon-ball-fighterz/"><u>Network Initialization Issue Resolved in Dragon Ball FighterZ</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-nokia-c300-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Nokia C300? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-mouse-pointer-vanishing-issues-in-windows-1e/"><u>Resolving Mouse Pointer Vanishing Issues in Windows 1E</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-resolved-fixing-the-critical-setup-failure-error-1603/"><u>Successfully Resolved: Fixing the Critical Setup Failure - Error 1603</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-10-lightroom-alternatives-free-and-paid-filmora/"><u>Top 10 Lightroom Alternatives [Free & Paid] | Filmora</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-kodi-buffering-woes-easy-steps-for-seamless-viewing/"><u>Troubleshoot Kodi Buffering Woes – Easy Steps for Seamless Viewing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-jumpy-scroll-bars-in-windows-10-file-explorer-solutions-that-work/"><u>Troubleshooting Jumpy Scroll Bars in Windows 10 File Explorer: Solutions That Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-update-why-cant-i-print-to-pdf-with-microsoft-heres-help/"><u>Windows 11 Update: Why Can't I Print to PDF with Microsoft? Here’s Help!</u></a></li>
<li><a href="https://win-able.techidaily.com/winning-strategies-for-uninterrupted-gaming-battle-royale-fixes-on-desktops-tech-insights-2024/"><u>Winning Strategies for Uninterrupted Gaming: Battle Royale Fixes on Desktops (Tech Insights - 2024)</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

