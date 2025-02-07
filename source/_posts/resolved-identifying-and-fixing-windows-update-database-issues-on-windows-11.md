---
title: "Resolved: Identifying and Fixing Windows Update Database Issues on Windows 11"
date: 2025-02-02T14:01:46.595Z
updated: 2025-02-07T10:05:07.470Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Identifying and Fixing Windows Update Database Issues on Windows 11"
excerpt: "This Article Describes Resolved: Identifying and Fixing Windows Update Database Issues on Windows 11"
thumbnail: https://thmb.techidaily.com/255a2b0d86b70a9b8b182a32b7f077670444b2206bc46e01ddb9543cc9317ad5.png
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
<li><a href="https://screen-recording.techidaily.com/new-unveiling-the-secrets-detailed-guide-on-capturing-screens-with-zd-for-2024/"><u>[New] Unveiling the Secrets Detailed Guide on Capturing Screens with ZD for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-procure-visual-gold-from-leading-4-video-content-creators/"><u>[Updated] 2024 Approved Procure Visual Gold From Leading 4 Video Content Creators</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-beat-to-visuals-an-iphone-guide-for-music-videos-for-2024/"><u>[Updated] Beat to Visuals An iPhone Guide for Music Videos for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-the-ultimate-macos-manual-for-ootd-videographers-for-2024/"><u>[Updated] The Ultimate MacOS Manual for OOTD Videographers for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/big-apple-targets-energy-intensive-crypto-mining-fueled-by-old-school-power-sources/"><u>Big Apple Targets Energy-Intensive Crypto Mining Fueled by Old School Power Sources</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-to-connect-airpods-to-windows-11-expert-advice/"><u>Easy Fixes to Connect AirPods to Windows 11 - Expert Advice</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-most-recent-nvidia-rtx-2070-super-drivers-compatible-with-windows-10-and-11-systems/"><u>Get the Most Recent Nvidia RTX 2070 Super Drivers: Compatible with Windows 10 & 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-correcting-user-profile-service-logon-failure-a-detailed-walkthrough/"><u>Guide to Correcting 'User Profile Service Logon Failure' - A Detailed Walkthrough</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-unlocking-money-potential-a-beginners-guide-on-periscope/"><u>In 2024, Unlocking Money Potential A Beginner's Guide on Periscope</u></a></li>
<li><a href="https://win-howtos.techidaily.com/minecraft-crash-fixes-overcoming-and-preventing-error-ncode-5-mishaps/"><u>Minecraft Crash Fixes: Overcoming and Preventing Error nCode 5 Mishaps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-error-code-0x80072f8f-comprehensive-guide-for-windows-11-and-10-users/"><u>Resolving Error Code 0X80072F8F: Comprehensive Guide for Windows 11 & 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-troubleshooting-techniques-for-compromised-windows-store-caches/"><u>Solved: Troubleshooting Techniques for Compromised Windows Store Caches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-troubleshooting-your-hp-laptops-nonfunctioning-camera-in-windows-1/"><u>Step-by-Step Guide: Troubleshooting Your HP Laptop's Nonfunctioning Camera in Windows 1</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-windows-10-sound-settings-issue-a-complete-guide/"><u>Troubleshoot and Fix Windows 10 Sound Settings Issue - A Complete Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1726029679273-xmedia-recode/"><u>XMedia Recode翻案中に遭遇した問題とその解決手順</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

