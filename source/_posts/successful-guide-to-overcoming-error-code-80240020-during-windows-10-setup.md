---
title: Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
date: 2025-01-09T17:36:51.333Z
updated: 2025-01-13T16:52:26.868Z
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
<li><a href="https://extra-resources.techidaily.com/new-best-practices-for-b-roll-utilization/"><u>[New] Best Practices for B-Roll Utilization</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-from-dull-to-delightful-how-to-craft-standout-youtube-thumbnails/"><u>[New] From Dull to Delightful How To Craft Standout YouTube Thumbnails</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pro-audios-essential-guide-to-top-10-free-luts/"><u>[New] Pro Audio's Essential Guide to Top 10 Free LUTs</u></a></li>
<li><a href="https://youtube-data.techidaily.com/he-art-of-concluding-your-videos-powerfully-for-2024/"><u>[New] The Art of Concluding Your Videos Powerfully for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-ensuring-authenticity-of-your-youtube-account/"><u>2024 Approved Ensuring Authenticity of Your YouTube Account</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-fix-exe-not-responding-problems-swiftly/"><u>Diagnose and Fix 'Exe Not Responding' Problems Swiftly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/failed-installation-of-windows-11-1607-fixes-and-solutions/"><u>Failed Installation of Windows 11 1607: Fixes and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fatal-circuitry-issue-system-halt/"><u>Fatal Circuitry Issue: System Halt</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-invalid-value-for-registry-error-when-opening-photos-on-windows-11/"><u>Fix: Invalid Value for Registry Error When Opening Photos on Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-samsung-galaxy-m54-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Samsung Galaxy M54 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restoring-issues-with-your-windows-store-cache-fixed/"><u>How To: Restoring Issues with Your Windows Store Cache (FIXED)</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-addressing-persistent-pauses-at-0-during-windows-updates/"><u>Mastering the Fix: Addressing Persistent Pauses at 0% During Windows Updates</u></a></li>
<li><a href="https://some-approaches.techidaily.com/movavi-online-conversor-libre-de-vuelo-entre-formatos-f4v-y-mov/"><u>Movavi Online: Conversor Libre De Vuelo Entre Formatos F4V Y MOV</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimize-performance-managing-high-cpu-use-by-microsoft-defender-antivirus-in-windows-10-devices/"><u>Optimize Performance: Managing High CPU Use by Microsoft Defender Antivirus in Windows 10 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-onedrive-lockout-windows-user-guide-needed/"><u>Reverse OneDrive Lockout: Windows User Guide Needed</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/step-by-step-windows-7-to-10-system-update/"><u>Step-by-Step: Windows 7 to 10 System Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-your-ps4-dualshocks-charging-issue/"><u>Troubleshooting Guide: Fixing Your PS4 Dualshock's Charging Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-permanent-100-on-windows-update/"><u>Troubleshooting Guide: Resolving Permanent 100% on Windows Update</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

