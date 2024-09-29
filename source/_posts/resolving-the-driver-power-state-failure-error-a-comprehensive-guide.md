---
title: "Resolving the Driver Power State Failure Error: A Comprehensive Guide"
date: 2024-09-27T17:05:21.704Z
updated: 2024-09-29T05:59:07.713Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the Driver Power State Failure Error: A Comprehensive Guide"
excerpt: "This Article Describes Resolving the Driver Power State Failure Error: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/76da0ed68bc2a93de3bddfb794fb58ce57d0ed84b978982943f32b5ddbb0e182.jpg
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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-win10-gaming-sessions-best-recording-approaches/"><u>[New] In 2024, Win10 Gaming Sessions Best Recording Approaches</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pushing-the-boundaries-of-titles-in-adobe-ae/"><u>[New] Pushing the Boundaries of Titles in Adobe AE</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-tips-for-efficiently-editing-videos-for-social-media-engagement-for-2024/"><u>[New] Tips for Efficiently Editing Videos for Social Media Engagement for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-firefox-secerrorunknownissuer-easily/"><u>[Solved] Firefox SEC_ERROR_UNKNOWN_ISSUER | Easily</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-top-8-tactics-for-striking-youtube-thumbnails-that-perform-well/"><u>[Updated] In 2024, Top 8 Tactics for Striking YouTube Thumbnails That Perform Well</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-photography-tips-accurately-annotating-dates-on-pictures/"><u>2024 Approved Photography Tips Accurately Annotating Dates on Pictures</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/content-marketing/"><u>Content Marketing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-facing-werfaultexe-errors-on-your-pc/"><u>Easy Fixes for Facing werFault.exe Errors on Your PC</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-samsung-galaxy-s23-tactical-edition-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Samsung Galaxy S23 Tactical Edition Devices | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-poco-x6-pro-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Poco X6 Pro</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-pcs-to-prevent-win10-cpu-spike/"><u>Optimizing PCs to Prevent Win10 CPU Spike</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-display-connectivity-problems-aoc-usb-monitors-and-windows-11-solutions/"><u>Resolving Display Connectivity Problems: AOC USB Monitors and Windows 11 Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-solving-the-problem-of-non-responsive-boot-sequence/"><u>Understanding and Solving the Problem of Non-Responsive Boot Sequence</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

