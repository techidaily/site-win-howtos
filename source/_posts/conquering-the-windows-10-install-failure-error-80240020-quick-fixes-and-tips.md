---
title: Conquering the 'Windows 10 Install Failure' (Error 80240020) - Quick Fixes & Tips
date: 2024-10-04T21:17:23.391Z
updated: 2024-10-09T20:51:03.978Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Conquering the 'Windows 10 Install Failure' (Error 80240020) - Quick Fixes & Tips
excerpt: This Article Describes Conquering the 'Windows 10 Install Failure' (Error 80240020) - Quick Fixes & Tips
thumbnail: https://thmb.techidaily.com/20ff4f86f64949aeed71ebab473532ee23ffbe18dd68a783845f09bf91d3afe4.jpg
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
<li><a href="https://extra-approaches.techidaily.com/new-render-photos-add-inward-radiant-spread-in-photoshop/"><u>[New] Render Photos Add Inward Radiant Spread in Photoshop</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-10-must-use-photo-watermark-tools/"><u>[Updated] 2024 Approved 10 Must-Use Photo Watermark Tools</u></a></li>
<li><a href="https://sound-issues.techidaily.com/audio-restoration-tips-a-user-friendly-guide-to-troubleshoot-pc-sound-issues/"><u>Audio Restoration Tips: A User-Friendly Guide to Troubleshoot PC Sound Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-non-connectivity-what-to-do-when-your-device-is-paired-but-fails-to-connect-on-windows-11/"><u>Diagnosing and Fixing Non-Connectivity: What to Do When Your Device Is Paired but Fails to Connect on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Vivo Y200? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-fixing-bluetooth-stack-service-failed-to-initialize-issue/"><u>Expert Advice on Fixing 'Bluetooth Stack Service Failed to Initialize' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-boot-issues-how-to-get-your-computer-to-properly-shutdown-windows-10/"><u>Fixing Boot Issues: How To Get Your Computer To Properly Shutdown Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-reconnect-and-resync-an-xbox-one-controller-that-wont-pair-up/"><u>How To: Reconnect and Resync An Xbox One Controller That Won't Pair Up</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-enter-the-ispoofer-discord-server-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, How to enter the iSpoofer discord server On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/itel-p55-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Itel P55 Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/lifetime-access-to-new-languages-zero-price-endless-potential/"><u>Lifetime Access to New Languages: Zero Price, Endless Potential</u></a></li>
<li><a href="https://win-howtos.techidaily.com/non-specific-symptoms-like-cough-and-weight-loss-are-common-in-lung-cancer-but-not-diagnostic-on-their-own/"><u>Non-Specific Symptoms Like Cough and Weight Loss Are Common in Lung Cancer but Not Diagnostic on Their Own.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-fortnite-graphics-support-problems-with-windows-pc/"><u>Resolving Fortnite Graphics Support Problems with Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-to-restore-your-mouses-right-click-in-windows-11/"><u>Step-by-Step Solutions to Restore Your Mouse's Right Click in Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/top-12-clicker-games-you-may-like-on-pc/"><u>Top 12 Clicker Games You May Like on PC</u></a></li>
<li><a href="https://fox-that.techidaily.com/unraveling-the-mysteries-of-icloud-problems-in-ios-a-step-by-step-fixers-handbook/"><u>Unraveling the Mysteries of iCloud Problems in iOS: A Step-by-Step Fixer's Handbook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-wont-your-surface-charge-heres-how-to-fix-it/"><u>Why Won't Your Surface Charge? Here's How to Fix It</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132161/7443" target="_top" id="2132161">
  <img src="//a.impactradius-go.com/display-ad/7443-2132161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132161/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

