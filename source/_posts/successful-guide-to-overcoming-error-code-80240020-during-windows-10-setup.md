---
title: Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
date: 2024-12-24T17:01:05.379Z
updated: 2024-12-28T11:24:30.574Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
excerpt: This Article Describes Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
thumbnail: https://thmb.techidaily.com/2e5cadcabaa5bc146e9286cd6ccf5e30c43742afdff538e1080a5add013b39bf.jpg
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

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
<li><a href="https://article-tips.techidaily.com/updated-oral-outputs-the-ultimate-list-for-offline-transcription-apps/"><u>[Updated] Oral Outputs The Ultimate List for Offline Transcription Apps</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-permanent-bond-incorquadible-tiktok-profile-url-addition/"><u>2024 Approved Permanent Bond Incorquadible TikTok Profile URL Addition</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-nokia-g42-5g-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Nokia G42 5G to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-overheating-issue-on-your-hp-spectre-x360-laptop/"><u>How to Resolve the Overheating Issue on Your HP Spectre X360 Laptop</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-a15-5g-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy A15 5G Phone without Google Account?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-oppo-find-x7-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Oppo Find X7 to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-freezes-and-lag-a-step-by-step-guide-to-a-smooth-file-explorer-on-windows/"><u>Overcoming Freezes and Lag: A Step-by-Step Guide to a Smooth File Explorer on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-infinite-load-screen-problems-in-valorant-a-complete-guide/"><u>Resolving the Infinite Load Screen Problems in VALORANT - A Complete Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-winrts-com-hiccup/"><u>Solving WinRTS COM Hiccup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-premier-selection-of-uninterruptible-power-backups/"><u>The Premier Selection of Uninterruptible Power Backups</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missing-desktop-icons-on-windows-11-solved/"><u>Troubleshooting Missing Desktop Icons on Windows 11 – Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-responsive-fn-keys-in-dell-laptops-effective-strategies-and-fixes/"><u>Troubleshooting Non-Responsive Fn Keys in Dell Laptops: Effective Strategies and Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlock-the-full-potential-of-your-file-explorer-in-windows-10/"><u>Unlock the Full Potential of Your File Explorer in Windows 10</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-best-vlc-trimming-software-for-mac-no-quality-loss-guaranteed/"><u>Updated Best VLC Trimming Software for Mac No Quality Loss Guaranteed</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-search-functionality-on-disk-based-discord/"><u>Upgrading Search Functionality on Disk-Based Discord</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-update-failure-cracking-the-0xc1900208-barrier-a-comprehensive-fix/"><u>Windows 10 Update Failure - Cracking the 0xC1900208 Barrier: A Comprehensive Fix</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

