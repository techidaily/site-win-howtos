---
title: Fixing Windows 11 Installation Hanging on 99%% - A Complete Guide
date: 2024-10-04T22:00:13.836Z
updated: 2024-10-09T18:57:40.774Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing Windows 11 Installation Hanging on 99%% - A Complete Guide
excerpt: This Article Describes Fixing Windows 11 Installation Hanging on 99%% - A Complete Guide
thumbnail: https://thmb.techidaily.com/0c878b30db98d758dc708e36a3a1a79c906ed9e88e0726b5c47115417927372d.jpg
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
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-precision-preservation-adding-dates-to-photos-with-ease/"><u>[New] In 2024, Precision Preservation Adding Dates to Photos with Ease</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-techniques-to-effortlessly-attain-professional-graphic-content/"><u>[New] Techniques to Effortlessly Attain Professional Graphic Content</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-invite-and-guest-at-tiktok-lives-easily/"><u>[Updated] 2024 Approved Invite and Guest at TikTok Lives Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-your-file-explorer-running-smoothly-again-overcome-windows-11-hiccups/"><u>Get Your File Explorer Running Smoothly Again - Overcome Windows 11 Hiccups!</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-nokia-g22-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Nokia G22 to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/insights-into-instagram-follower-exits-for-2024/"><u>Insights Into Instagram Follower Exits for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-screen-mirroring-tips-to-fix-miracast-rejected-by-device/"><u>Mastering Screen Mirroring: Tips to Fix 'Miracast Rejected by Device'</u></a></li>
<li><a href="https://hardware-help.techidaily.com/secure-and-simple-download-of-canon-mg3620-drivers/"><u>Secure and Simple Download of Canon MG3620 Drivers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/snapmaster-pro-advanced-ai-enhanced-editing-for-2024/"><u>SnapMaster Pro Advanced AI Enhanced Editing for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-motorola-moto-g-stylus-2023-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Motorola Moto G Stylus (2023) with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-common-issues-with-unresponsive-laptop-touchpads-step-by-step/"><u>Solving Common Issues with Unresponsive Laptop Touchpads Step by Step</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-1110-audio-glitches-successfully/"><u>Solving Windows 11/10 Audio Glitches Successfully</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151856/7443" target="_top" id="2151856">
  <img src="//a.impactradius-go.com/display-ad/7443-2151856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

