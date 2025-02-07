---
title: Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
date: 2025-02-06T02:47:53.314Z
updated: 2025-02-07T07:07:24.054Z
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
<li><a href="https://visual-screen-recording.techidaily.com/new-breaking-down-freevid-cam-capture-tech/"><u>[New] Breaking Down FreeVid Cam Capture Tech</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-chatcast-collector-fb-groups-for-2024/"><u>[New] ChatCast Collector - FB Groups for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-comprehensive-examination-assessing-gecatas-game-logger/"><u>[New] In 2024, Comprehensive Examination Assessing Gecata's Game Logger</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-mastering-game-streams-with-ai-enhanced-portraits/"><u>[Updated] 2024 Approved Mastering Game Streams with AI-Enhanced Portraits</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-break-into-cash-with-periscope-first-timers-tips/"><u>[Updated] Break Into Cash with Periscope First-Timers' Tips</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-download-and-use-movie-maker-on-windows-11/"><u>[Updated] Download and Use Movie Maker on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/2023s-definitive-tricks-to-optimize-performance-and-reduce-lags-in-fallout-4-adventures/"><u>2023'S Definitive Tricks to Optimize Performance & Reduce Lags in Fallout 4 Adventures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209865722-battleye-service-install-errors-now-corrected/"><u>BattlEye Service Install Errors - Now Corrected</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-fixes-for-windows-10-not-shutting-down-now-resolved/"><u>Expert Fixes for Windows 10 Not Shutting Down - Now Resolved!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/harmonizing-wireless-channels-the-ultimate-guide-to-linking-different-bluetooth-speakers-to-just-one-device/"><u>Harmonizing Wireless Channels: The Ultimate Guide to Linking Different Bluetooth Speakers to Just One Device</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-mastering-chroma-key-techniques-for-professional-videos/"><u>In 2024, Mastering Chroma Key Techniques for Professional Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-connection-issues-how-to-get-airpods-working-with-windows-11/"><u>Solving Your Connection Issues: How To Get AirPods Working with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-application-launch-failures-with-error-0xc000007b-steps-for-success/"><u>Troubleshoot and Fix Application Launch Failures with Error 0xC000007B – Steps for Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-ftdi-bus-system-errors-driver-incompatibility-causes-loss-of-memory-protection/"><u>Understanding FTDI Bus System Errors: Driver Incompatibility Causes Loss of Memory Protection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/xbox-one-and-pc-integration-button-maneuvers/"><u>Xbox One & PC Integration: Button Maneuvers</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

