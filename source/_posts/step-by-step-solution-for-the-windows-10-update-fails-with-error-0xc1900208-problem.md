---
title: Step-by-Step Solution for the 'Windows 10 Update Fails with Error 0xC1900208' Problem
date: 2024-10-14T19:44:31.083Z
updated: 2024-10-21T19:34:46.499Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for the 'Windows 10 Update Fails with Error 0xC1900208' Problem
excerpt: This Article Describes Step-by-Step Solution for the 'Windows 10 Update Fails with Error 0xC1900208' Problem
thumbnail: https://thmb.techidaily.com/42900d3cd2ac79478a2e9a5f62d92e59b26835c360208046bfffff6e9458bb6e.jpg
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
<li><a href="https://win-howtos.techidaily.com/fixed-windows-11-update-error-0x80070541/"><u>[Fixed] Windows 11 Update Error 0X80070541</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-teaching-technology-trends-the-top-10-audio-visual-devices-for-classrooms/"><u>[New] Teaching Technology Trends The Top 10 Audio-Visual Devices for Classrooms</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-skys-best-pixels-face-off-dji-inspire-1-and-gopro-fusion-mini/"><u>[Updated] In 2024, Sky's Best Pixels Face-Off DJi Inspire 1 & GoPro Fusion Mini</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-unlocking-earnings-a-step-by-step-guide-to-youtubes-monetization-on-mobile/"><u>[Updated] In 2024, Unlocking Earnings A Step-by-Step Guide to YouTube's Monetization on Mobile</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-iphone-photography-fundamentals-the-essential-10-arrangement-rules/"><u>[Updated] IPhone Photography Fundamentals The Essential 10 Arrangement Rules</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-less-is-more-the-best-video-url-reducers-revealed/"><u>[Updated] Less Is More The Best Video URL Reducers Revealed</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-influencer-insights-the-top-5-instagram-moves-for-viral-content/"><u>2024 Approved Influencer Insights The Top 5 Instagram Moves for Viral Content</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-iphone-shutterbugs-tips-for-better-images/"><u>2024 Approved IPhone Shutterbugs Tips for Better Images</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-no-more-a-step-by-step-solution-for-windows-camera-error-code-0xa00f4292/"><u>Error No More: A Step-by-Step Solution for Windows Camera Error Code 0Xa00f4292</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-fix-resolving-windows-failed-to-install-issues/"><u>Fast Fix: Resolving 'Windows Failed To Install' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-unresponsive-google-chrome-issue-with-simple-relaunch-steps/"><u>Fix Unresponsive Google Chrome Issue with Simple Relaunch Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-defeating-the-2erious-case-of-miracast-not-working-on-your-gadget/"><u>Guide to Defeating the 2Erious Case of Miracast Not Working on Your Gadget</u></a></li>
<li><a href="https://vp-tips.techidaily.com/guide-transferring-movies-from-dvds-to-apple-tv-with-easy-ripping-techniques/"><u>Guide: Transferring Movies From DVDs to Apple TV with Easy Ripping Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-dvd-files-running-again-in-windows-operating-system/"><u>How to Get DVD Files Running Again in Windows Operating System</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-oppo-find-x6-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Oppo Find X6 to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fixing-your-microphone-problems-in-windows-10/"><u>Step-by-Step Guide to Fixing Your Microphone Problems in Windows 10</u></a></li>
<li><a href="https://tech-revival.techidaily.com/tech-made-easy-installing-the-latest-version-of-llama-2-locally/"><u>Tech Made Easy: Installing the Latest Version of Llama 2 Locally</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-strategies-to-overcome-game-lag-in-fallout-4/"><u>Top Strategies to Overcome Game Lag in Fallout 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-your-usb-to-hdmi-link-isnt-working-fixes-and-tips/"><u>Why Your USB to HDMI Link Isn't Working: Fixes & Tips</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

