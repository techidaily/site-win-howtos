---
title: "How to Correct 'Bad Image' Errors for Windows 11 Users: A Comprehensive Fix"
date: 2025-01-14T17:54:49.314Z
updated: 2025-01-19T19:27:14.716Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Correct 'Bad Image' Errors for Windows 11 Users: A Comprehensive Fix"
excerpt: "This Article Describes How to Correct 'Bad Image' Errors for Windows 11 Users: A Comprehensive Fix"
thumbnail: https://thmb.techidaily.com/38a10dded96ded9495ccb2173f240c20a69acb6b4b947c6dc175d30ce0f723b9.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-toggle-off-instagram-tv-feature/"><u>[New] 2024 Approved Toggle Off Instagram TV Feature</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-quick-guide-automating-mac-screenshot-via-shortcuts-for-2024/"><u>[Updated] Quick Guide Automating Mac Screenshot via Shortcuts for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/99-pre-order-deal-on-the-newest-apple-watch-series-by-best-buy-exclusive-tips-inside/"><u>$99 Pre-Order Deal on the Newest Apple Watch Series by Best Buy – Exclusive Tips Inside</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/beware-latest-microsoft-patch-could-worsen-evening-work-struggles-insights-from-zdnet/"><u>Beware: Latest Microsoft Patch Could Worsen Evening Work Struggles - Insights From ZDNet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/combat-blizzards-wow-lag-proven-strategies-for-smooth-gameplay/"><u>Combat Blizzard's Wow Lag: Proven Strategies for Smooth Gameplay</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/how-to-capture-computer-screens-and-webcam-video-simultaneously-on-windows10/"><u>How to Capture Computer Screens and Webcam Video Simultaneously on Windows10?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202987997-mac-camera-issues-resolve-them-with-these-easy-techniques/"><u>Mac Camera Issues? Resolve Them with These Easy Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-a-guide-to-repairing-unknown-usb-and-port-reset-faults-in-windows-11-systems/"><u>Mastering the Fix: A Guide to Repairing Unknown USB and Port Reset Faults in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-limited-memory-challenges-fixing-windows-10-errors/"><u>Overcoming Limited Memory Challenges: Fixing Windows 10 Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-unfreezing-your-laptops-trackpad-or-external-mouse/"><u>Step-by-Step Solutions: Unfreezing Your Laptop's Trackpad or External Mouse</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-samsung-galaxy-m34-5g-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Samsung Galaxy M34 5G Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

