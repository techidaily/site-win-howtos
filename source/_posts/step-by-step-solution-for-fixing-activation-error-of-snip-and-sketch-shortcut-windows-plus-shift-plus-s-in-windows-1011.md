---
title: Step-by-Step Solution for Fixing Activation Error of Snip & Sketch Shortcut (Windows + Shift + S) in Windows 10/11
date: 2024-10-03T15:27:32.025Z
updated: 2024-10-04T08:27:47.861Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for Fixing Activation Error of Snip & Sketch Shortcut (Windows + Shift + S) in Windows 10/11
excerpt: This Article Describes Step-by-Step Solution for Fixing Activation Error of Snip & Sketch Shortcut (Windows + Shift + S) in Windows 10/11
thumbnail: https://thmb.techidaily.com/2151304b15358b5e0486365b1b4e0f5fc2185a4452deb2b08eaf2b9d1e47c0a1.jpg
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
<li><a href="https://extra-approaches.techidaily.com/new-step-by-step-process-for-efficient-use-of-macs-preview-app/"><u>[New] Step-by-Step Process for Efficient Use of Mac's Preview App</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-how-to-make-a-mark-as-an-hdr-photography-pro-with-lightroom/"><u>[Updated] How to Make a Mark as an HDR Photography Pro with Lightroom</u></a></li>
<li><a href="https://extra-information.techidaily.com/apple-excellence-iphones-best-no-cost-image-assemblers-and-layouts-for-2024/"><u>Apple Excellence – iPhone's Best No-Cost Image Assemblers & Layouts for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/execution-blocked-code-stalls/"><u>Execution Blocked: Code Stalls</u></a></li>
<li><a href="https://tech-haven.techidaily.com/expert-strategies-for-seamless-chatgpt-extension-functionality/"><u>Expert Strategies for Seamless ChatGPT Extension Functionality</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-motorola-moto-g23-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-playlist-guide-for-youtube-enthusiasts-online-and-mobile/"><u>In 2024, The Ultimate Playlist Guide for YouTube Enthusiasts Online & Mobile</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-top-8-montage-apps-for-your-androidiphone/"><u>In 2024, Top 8 Montage Apps for Your Android/iPhone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-yts-game-changers-the-elite-ladies-in-gaming/"><u>In 2024, YT's Game Changers The Elite Ladies in Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-system-hang-ups-effective-techniques-to-shut-down-windows-11-solved/"><u>Overcoming System Hang-Ups: Effective Techniques to Shut Down Windows 11 [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restored-enable-your-systems-area-wide-safety-features-now/"><u>Restored: Enable Your System’s Area-Wide Safety Features Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-usb-connectivity-issues-for-windows-1011-users/"><u>Solving USB Connectivity Issues for Windows 10/11 Users</u></a></li>
<li><a href="https://buynow-info.techidaily.com/transforming-tablets-into-workstations-a-closer-look-at-the-2amoble-and-high-performance-capabilities-of-the-new-ipad-pro-m1-2021/"><u>Transforming Tablets Into Workstations: A Closer Look at the 2Amoble and High-Performance Capabilities of the New iPad Pro (M1, 2021)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-fix-hp-laptops-malfunctioning-usb-port/"><u>Troubleshooting Steps: Fix HP Laptop's Malfunctioning USB Port</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-resolving-svchost-high-cpu-consumption-issues-on-windows-11/"><u>Understanding and Resolving Svchost High CPU Consumption Issues on Windows 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

