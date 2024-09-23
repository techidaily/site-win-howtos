---
title: Step-by-Step Approach to Correct the 'Failed to Set Up Service' Error (0X80072EFD) on Your PC
date: 2024-09-21T23:02:11.319Z
updated: 2024-09-22T19:04:02.022Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Approach to Correct the 'Failed to Set Up Service' Error (0X80072EFD) on Your PC
excerpt: This Article Describes Step-by-Step Approach to Correct the 'Failed to Set Up Service' Error (0X80072EFD) on Your PC
thumbnail: https://thmb.techidaily.com/104450fe8ea4a9516969410598e82c71d2951cffe9ee598f36dc42477a8a3193.jpg
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-pixel-capture-reimagined/"><u>[New] 2024 Approved Pixel Capture Reimagined</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-record-webcam-video-with-vlc-for-2024/"><u>[Updated] Record Webcam Video with VLC for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-vivo-y27s-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Vivo Y27s without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-resolving-sudden-auto-power-offs-in-computers/"><u>Expert Advice on Resolving Sudden Auto Power-Offs in Computers</u></a></li>
<li><a href="https://some-techniques.techidaily.com/fine-tune-focus-effective-minecraft-zooming-strategies-for-2024/"><u>Fine-Tune Focus Effective Minecraft Zooming Strategies for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/get-save-and-enjoy-discover-these-6-excellent-linkedin-downloader-tools-for-2024/"><u>Get, Save, and Enjoy Discover These 6 Excellent LinkedIn Downloader Tools for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-non-functioning-usb-on-hp-computers-a-comprehensive-fix-guide/"><u>Solving Non-Functioning USB on HP Computers: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206353380-solving-your-pcs-unintended-nap-problem-quick-and-simple-fixes/"><u>Solving Your PC's Unintended Nap Problem: Quick & Simple Fixes!</u></a></li>
<li><a href="https://win-solutions.techidaily.com/the-mighty-stanley-j5c09-a-review-highlighting-its-robust-capabilities/"><u>The Mighty Stanley J5C09: A Review Highlighting Its Robust Capabilities</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fix-for-unavailable-audiovideo-device-drivers-in-your-computer-setup/"><u>The Ultimate Fix for Unavailable Audio/Video Device Drivers in Your Computer Setup</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094477/7443" target="_top" id="2094477">
  <img src="//a.impactradius-go.com/display-ad/7443-2094477" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094477/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

