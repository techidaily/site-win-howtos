---
title: "Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All!"
date: 2024-09-22T01:13:59.202Z
updated: 2024-09-29T05:09:47.415Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All!"
excerpt: "This Article Describes Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All!"
thumbnail: https://thmb.techidaily.com/0ca201532589a8340625e0277d57d7a6d8a4fe5f03caf08035754438a176d190.jpg
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
<li><a href="https://youtube-zero.techidaily.com/nnovative-techniques-for-enhancing-youtube-audio/"><u>[New] Innovative Techniques for Enhancing YouTube Audio</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-a-comprehensive-look-at-quantum-hdr/"><u>[Updated] A Comprehensive Look at Quantum HDR</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-infinix-gt-10-pro-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Infinix GT 10 Pro</u></a></li>
<li><a href="https://win-webster.techidaily.com/access-your-onedrive-files-anywhere-new-offline-feature-enables-rural-remote-accessibility-tech-insights/"><u>Access Your OneDrive Files Anywhere: New Offline Feature Enables Rural Remote Accessibility | Tech Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-sporadic-wi-fi-mouse-failures-in-modern-operating-systems-windows-1110/"><u>Diagnosing and Repairing Sporadic Wi-Fi Mouse Failures in Modern Operating Systems (Windows 11/10)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-honor-magic-v2-frp-by-drfone-android/"><u>Full Guide to Bypass Honor Magic V2 FRP</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hearthstone-performance-boost-effortless-lag-fixes/"><u>Hearthstone Performance Boost: Effortless Lag Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-total-war-rome-remastered-game-crashing-issues-easily/"><u>How to Fix Total War: Rome Remastered Game Crashing Issues Easily</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-vivo-y100a-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Vivo Y100A Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-videos-from-motorola-moto-g-5g-2023-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Videos from Motorola Moto G 5G (2023) to iPad | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-unleashing-video-potential-efficiently-add-subtitlescc-to-your-youtube-videos/"><u>In 2024, Unleashing Video Potential Efficiently Add Subtitles/CC to Your YouTube Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/jokesinframe-instant-memes-and-more-for-2024/"><u>JokesInFrame Instant Memes & More for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-computers-stuck-at-windows-setup-a-step-by-step-guide/"><u>Resolve Your Computer's 'Stuck at Windows Setup': A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-how-to-enable-your-devices-wireless-functionality/"><u>Resolving Issues: How to Enable Your Device's Wireless Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-plugged-in-but-not-charging-problems-on-your-microsoft-surface/"><u>Solving Plugged In But Not Charging Problems on Your Microsoft Surface</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885947/19272" target="_top" id="1885947">
  <img src="//a.impactradius-go.com/display-ad/19272-1885947" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

