---
title: Windows Audio Failure No More - Win 10/11 Fixed
date: 2025-02-06T08:24:53.400Z
updated: 2025-02-07T06:03:30.999Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows Audio Failure No More - Win 10/11 Fixed
excerpt: This Article Describes Windows Audio Failure No More - Win 10/11 Fixed
thumbnail: https://thmb.techidaily.com/c64fedaf756cbcf9ac92722c1b2668052e1efc526bd85097cc0c097ddacbbc3a.jpg
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-the-essential-checklist-for-syncing-obs-and-zoom/"><u>[New] 2024 Approved The Essential Checklist for Syncing OBS & Zoom</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-unveiling-hidden-spaces-discovering-your-yt-comments/"><u>[Updated] 2024 Approved Unveiling Hidden Spaces Discovering Your YT Comments</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-iphone-guide-engage-with-audio-content-seamlessly/"><u>2024 Approved IPhone Guide Engage with Audio Content Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-file-history-misconfiguration-in-windows/"><u>Addressing File History Misconfiguration in Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/complete-tutorial-on-thawing-out-your-frozen-ios-device/"><u>Complete Tutorial on Thawing Out Your Frozen iOS Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnostic-overcome-normalized-keyboard-performance-after-repair/"><u>Diagnostic Overcome: Normalized Keyboard Performance After Repair</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722974363253-elevate-your-audio-experience-with-gigabytes-free-driver-download-now/"><u>Elevate Your Audio Experience with Gigabyte's Free Driver Download Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-fixes-for-user-profile-service-startup-failure-in-windows-11/"><u>Expert Fixes for 'User Profile Service' Startup Failure in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-wireless-capability-is-turned-off-solved/"><u>Fix Wireless Capability Is Turned Off [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-charger-issues-fix-your-non-charging-battery-swiftly/"><u>Laptop Charger Issues? Fix Your Non-Charging Battery Swiftly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-service-has-failed-to-sign-in-error-by-fixing-the-user-profile-on-windows-11/"><u>Overcoming 'Service Has Failed to Sign In' Error by Fixing the User Profile on Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-bring-your-vision-to-life-adobe-premiere-pro-for-mac-creators/"><u>Updated Bring Your Vision to Life Adobe Premiere Pro for Mac Creators</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-your-motivation-matters-addressing-the-root-causes-of-academic-disinterest/"><u>Why Your Motivation Matters: Addressing the Root Causes of Academic Disinterest</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

