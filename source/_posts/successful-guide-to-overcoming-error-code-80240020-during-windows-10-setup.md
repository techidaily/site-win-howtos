---
title: Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
date: 2025-01-13T20:04:39.850Z
updated: 2025-01-19T20:22:10.288Z
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
<li><a href="https://article-helps.techidaily.com/new-unified-brand-presence-across-digital-platforms/"><u>[New] Unified Brand Presence Across Digital Platforms</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-how-to-restore-windows-photo-viewer-in-windows-10-for-2024/"><u>[Updated] How to Restore Windows Photo Viewer in Windows 10 for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-reach-new-heights-top-7-applications-turning-your-art-into-nfts-for-2024/"><u>[Updated] Reach New Heights Top 7 Applications Turning Your Art Into NFTs for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlock-the-power-of-podcasts-15-tips-for-multitasking-and-growth/"><u>[Updated] Unlock the Power of Podcasts 15 Tips for Multitasking and Growth</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-how-to-use-filters-on-instagram-2023/"><u>2024 Approved How to Use Filters on Instagram 2023?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-innovating-connectivity-the-moto-z2-reviewed/"><u>2024 Approved Innovating Connectivity The Moto Z2 Reviewed</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/advanced-animators-toolkit-samples-for-2024/"><u>Advanced Animator's Toolkit Samples for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-troubleshooting-techniques-for-correcting-oculus-gear-issues-in-the-new-year/"><u>DIY Troubleshooting Techniques for Correcting Oculus Gear Issues in the New Year</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-speaker-distortion-on-windows-10-and-7-a-complete-guide/"><u>How to Fix Speaker Distortion on Windows 10 & 7: A Complete Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-oppo-find-x6-pro-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Oppo Find X6 Pro online without jailbreak</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-mastering-canon-footage-a-step-by-step-guide-to-video-editing/"><u>New In 2024, Mastering Canon Footage A Step-by-Step Guide to Video Editing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-non-responsive-windows-11-start-menu-issues/"><u>Quick Solutions for Non-Responsive Windows 11 Start Menu Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-adobe-flash-player-crashes-on-google-chrome-solved/"><u>Resolving Adobe Flash Player Crashes on Google Chrome - Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-your-suddenly-nonfunctional-wireless-mouse-in-windows-11-or-10/"><u>Troubleshooting Guide: Fixing Your Suddenly Nonfunctional Wireless Mouse in Windows 11 or 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unprintable-pdf-woes-masterful-shortcuts-to-make-them-work/"><u>Unprintable PDF Woes? Masterful Shortcuts to Make Them Work!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-bluetooth-troubleshooting-tips-for-smooth-device-connection-guide/"><u>Windows 10 Bluetooth Troubleshooting Tips for Smooth Device Connection (Guide)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-woes-no-more-achieve-perfect-harmony-between-your-device-driver-and-os-for-a-smooth-gaming-experience/"><u>Windows Woes No More - Achieve Perfect Harmony Between Your Device Driver and OS for a Smooth Gaming Experience</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

