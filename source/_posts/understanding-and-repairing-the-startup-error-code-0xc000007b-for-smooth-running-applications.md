---
title: Understanding And Repairing The Startup Error Code 0xC000007b For Smooth Running Applications
date: 2025-02-03T17:44:35.096Z
updated: 2025-02-07T03:30:21.689Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Understanding And Repairing The Startup Error Code 0xC000007b For Smooth Running Applications
excerpt: This Article Describes Understanding And Repairing The Startup Error Code 0xC000007b For Smooth Running Applications
thumbnail: https://thmb.techidaily.com/35506a9c5eeb39965a6739f4255f2a7fd3073f2c89e35224944b9c79ce0abec8.jpg
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
<li><a href="https://extra-skills.techidaily.com/new-soaring-in-high-definition-an-in-depth-xiaomi-analysis/"><u>[New] Soaring in High Definition An In-Depth Xiaomi Analysis</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-capturing-your-lenovo-display-with-ease-for-2024/"><u>[Updated] Capturing Your Lenovo Display with Ease for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-fix-audio-glitches-with-youtube-video-player-errors-on-windows-11-systems/"><u>Diagnose and Fix Audio Glitches with YouTube Video Player Errors on Windows 11 Systems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exclusive-black-friday-laptop-savings-for-november-2024-shop-smart-with-our-guide-cnet/"><u>Exclusive Black Friday Laptop Savings for November 2024 - Shop Smart with Our Guide! | CNET</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-overcoming-the-challenge-of-a-non-charging-ps4-controller/"><u>Expert Tips: Overcoming the Challenge of a Non-Charging PS4 Controller</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-your-pubg-game-running-in-202-new-solutions-for-startup-problems/"><u>Get Your PUBG Game Running in 202# New Solutions for Startup Problems</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-motorola-defy-2-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Motorola Defy 2 Phones with/without a PC</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-honor-x9a-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Honor X9a</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-windows-1n-repeated-reboot-problem-with-simple-steps/"><u>Solving the Windows 1N Repeated Reboot Problem with Simple Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-bluetooth-mouse-failing-on-windows-devices/"><u>Step-by-Step Solution for 'Bluetooth Mouse Failing' On Windows Devices</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-oppo-reno-8t-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Oppo Reno 8T 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-lenovo-mouse-pad-on-pc-effective-solutions-for-windows-systems/"><u>Troubleshoot Lenovo Mouse Pad on PC: Effective Solutions for Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-geforce-experience-access-issues-successfully/"><u>Troubleshooting and Repairing GeForce Experience Access Issues Successfully</u></a></li>
<li><a href="https://win-forum.techidaily.com/uncover-the-secrets-of-windows-11-explore-11-essential-yet-overlooked-features/"><u>Uncover the Secrets of Windows 11 - Explore 11 Essential Yet Overlooked Features!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unexpected-shutdowns-in-windows-10-pro/"><u>Unexpected Shutdowns in Windows 10 Pro</u></a></li>
<li><a href="https://extra-tips.techidaily.com/visual-vividity-techniques-in-hue-adjustment/"><u>Visual Vividity Techniques in Hue Adjustment</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-poco-f5-5g-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Poco F5 5G Auto Does Not Work | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

