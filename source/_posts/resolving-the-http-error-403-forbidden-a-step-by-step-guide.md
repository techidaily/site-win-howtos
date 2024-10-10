---
title: "Resolving the HTTP Error 403: Forbidden - A Step-by-Step Guide"
date: 2024-10-08T20:51:49.189Z
updated: 2024-10-09T16:19:49.778Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the HTTP Error 403: Forbidden - A Step-by-Step Guide"
excerpt: "This Article Describes Resolving the HTTP Error 403: Forbidden - A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/933460ab5e97c9ff94ee3e62c125239a5731074d09b9d43607b3861f48a7087e.jpg
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
<li><a href="https://youtube-video-recordings.techidaily.com/updated-avoiding-youtubes-controversial-scrutiny/"><u>[Updated] Avoiding YouTube's Controversial Scrutiny</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-utilizing-no-cost-countdown-efficient-time-management/"><u>[Updated] In 2024, Utilizing No-Cost Countdown Efficient Time Management</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-sdr-vs-hdri-elevating-your-content-with-advanced-color-techniques/"><u>2024 Approved SDR Vs. HDRI Elevating Your Content with Advanced Color Techniques</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-your-iphone-se-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From your iPhone SE</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-preventing-surges-through-your-routers-ports/"><u>Effective Solutions for Preventing Surges Through Your Router's Ports</u></a></li>
<li><a href="https://extra-resources.techidaily.com/free-windows-10-recorder-tools-a-comprehensive-updated-guide/"><u>Free Windows 10 Recorder Tools A Comprehensive, Updated Guide</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-intel-nvme-drivers-instantly-a-smooth-user-friendly-download-process/"><u>Get Your Intel NVMe Drivers Instantly - A Smooth, User-Friendly Download Process</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Read This Guide to Find a Reliable Alternative to Fake GPS On Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-google-chrome-lagging-effective-methods-to-restart-and-optimize-performance/"><u>Resolving Google Chrome Lagging: Effective Methods to Restart & Optimize Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-to-restore-screen-visibility-on-dell-laptops-a-comprehensive-guide/"><u>Step-by-Step Solutions to Restore Screen Visibility on Dell Laptops - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-the-night-light-feature-issues-in-windows-11/"><u>Troubleshooting Guide: Fixing the 'Night Light' Feature Issues in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unreal-development-hangs-on-d3d-device-lifespan/"><u>Unreal Development Hangs on D3D Device Lifespan</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-support-detecting-and-connecting-to-bluetooth-devices/"><u>Windows 10 Support: Detecting and Connecting to Bluetooth Devices</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052059/7443" target="_top" id="2052059">
  <img src="//a.impactradius-go.com/display-ad/7443-2052059" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052059/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

