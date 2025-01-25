---
title: Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
date: 2025-01-18T16:06:33.384Z
updated: 2025-01-25T17:03:33.204Z
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
<li><a href="https://fox-blue.techidaily.com/new-ultimate-guide-to-15-best-4k-recording-tools/"><u>[New] Ultimate Guide to #15 Best 4K Recording Tools</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-say-goodbye-to-paywalls-with-free-video-handling-tools-for-2024/"><u>[Updated] Say Goodbye to Paywalls with Free Video Handling Tools for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-aoc-usb-monitor-not-detected-problems-on-windows-11-systems/"><u>How to Resolve 'AOC USB Monitor Not Detected' Problems on Windows 11 Systems</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-face-id-to-pay-for-apple-tvplus-on-iphone-15-plus-by-drfone-ios-unlock-ios-unlock/"><u>How to Use Face ID to Pay for Apple TV+ on iPhone 15 Plus</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-lock-apps-on-xiaomi-redmi-note-12-5g-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Xiaomi Redmi Note 12 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-solutions-for-balancing-iphone-hdr-footage-with-advanced-premiere-pro-tools/"><u>In 2024, Solutions for Balancing iPhone HDR Footage with Advanced Premiere Pro Tools</u></a></li>
<li><a href="https://win-dash.techidaily.com/leading-sound-capture-tools-compatible-with-windows-7-ultimate-guide-for-musicians-and-podcasters/"><u>Leading Sound Capture Tools Compatible with Windows 7: Ultimate Guide for Musicians and Podcasters</u></a></li>
<li><a href="https://win-howtos.techidaily.com/proven-methods-for-defrosting-a-sluggish-computer-screen/"><u>Proven Methods for Defrosting a Sluggish Computer Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-complete-guide-to-fixing-installation-problems-with-the-windows-1903-feature-update/"><u>The Complete Guide to Fixing Installation Problems with the Windows 1903 Feature Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-resolving-internet-explorer-not-responding/"><u>Troubleshooting Steps: Resolving 'Internet Explorer Not Responding'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-pc-fixing-the-night-light-feature-in-windows-10-and-11/"><u>Troubleshooting Your PC: Fixing the Night Light Feature in Windows 10 & 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

