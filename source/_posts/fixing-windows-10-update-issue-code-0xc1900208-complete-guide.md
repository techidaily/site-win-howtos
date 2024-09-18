---
title: Fixing Windows 10 Update Issue Code 0xC1900208 - Complete Guide
date: 2024-09-10T17:15:32.636Z
updated: 2024-09-17T22:22:01.394Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing Windows 10 Update Issue Code 0xC1900208 - Complete Guide
excerpt: This Article Describes Fixing Windows 10 Update Issue Code 0xC1900208 - Complete Guide
thumbnail: https://thmb.techidaily.com/1dd490a8bd0fd9490b2a1a7e2f3e07f4fe288167493a224a8c1401933c662484.jpeg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

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
<li><a href="https://visual-screen-recording.techidaily.com/new-5-best-mid-range-gaming-keyboards-for-enthusiasts-for-2024/"><u>[New] 5 Best Mid-Range Gaming Keyboards for Enthusiasts for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-techniques-for-depicting-realism-in-docuscripts/"><u>[New] Techniques for Depicting Realism in Docuscripts</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-the-historical-context-for-2024/"><u>[New] The Historical Context for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/ace-your-tests-elite-strategies-and-key-certifications/"><u>Ace Your Tests: Elite Strategies and Key Certifications</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/designing-distinctive-denouements-for-2024/"><u>Designing Distinctive Denouements for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-advice-fixing-bugs-and-crashes-in-nwstoreexe-efficiently/"><u>Expert Advice: Fixing Bugs and Crashes in NW_store.exe Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-reconciling-incompatible-hardware-with-wow-game-driver-support/"><u>Guide to Reconciling Incompatible Hardware with WoW Game Driver Support</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-easily-fix-the-d3dx939dll-file-is-missing-problem-on-windows-systems/"><u>How to Easily Fix the d3dx9_39.dll File Is Missing Problem on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-mitigate-power-burst-issues-on-networking-hardware-ports/"><u>How to Mitigate Power Burst Issues on Networking Hardware Ports</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-reverting-to-classic-from-sierra-to-os-x-1010/"><u>In 2024, Reverting to Classic From Sierra To OS X 10.10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-12-prominent-vivo-t2-pro-5g-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Vivo T2 Pro 5G Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-acquiring-authorization-from-the-trusted-installer-for-system-file-alterations/"><u>Step-by-Step: Acquiring Authorization From the Trusted Installer for System File Alterations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-pc-when-it-freezes-at-windows-setup-screen/"><u>Troubleshooting Your PC When It Freezes at Windows Setup Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unexpected-restarts-plague-win10-systems/"><u>Unexpected Restarts Plague Win10 Systems</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896546/19272" target="_top" id="1896546">
  <img src="//a.impactradius-go.com/display-ad/19272-1896546" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896546/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

