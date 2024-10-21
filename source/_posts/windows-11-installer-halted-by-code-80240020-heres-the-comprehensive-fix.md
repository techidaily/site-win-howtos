---
title: Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix
date: 2024-10-18T20:00:23.369Z
updated: 2024-10-21T19:21:10.274Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix
excerpt: This Article Describes Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix
thumbnail: https://thmb.techidaily.com/6ac471d87db668dcc4b6f87c6982a3ef4bb37e3fbffe0068ce8a47124a8a8199.jpg
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
<li><a href="https://facebook-video-footage.techidaily.com/new-perfecting-the-skill-for-selective-youtube-downloads/"><u>[New] Perfecting the Skill for Selective YouTube Downloads</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-top-budget-friendly-android-video-callers/"><u>[Updated] 2024 Approved Top Budget-Friendly Android Video Callers</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-unlocking-image-potential-smart-online-cropping-techniques/"><u>[Updated] Unlocking Image Potential Smart Online Cropping Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-when-youtube-sounds-dont-work-properly-on-a-windows-10-computer/"><u>Easy Fixes for When YouTube Sounds Don't Work Properly on a Windows 10 Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-for-the-endless-loop-of-configuring-windows-a-comprehensive-walkthrough/"><u>Fixes for the Endless Loop of 'Configuring Windows': A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-persistent-screen-flashes-on-your-windows-10-pc/"><u>Fixing Persistent Screen Flashes on Your Windows 10 PC</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/o-use-youtube-enhancements-to-improve-video-quality/"><u>How to Use YouTube Enhancements to Improve Video Quality</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-perfecting-the-synergy-of-visuals-and-voiceovers-in-videos/"><u>In 2024, Perfecting the Synergy of Visuals and Voiceovers in Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-reviewing-multiple-cameras-are-there-upgrades/"><u>In 2024, Reviewing Multiple Cameras Are There Upgrades?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-bypassing-icloud-activation-lock-on-iphone-xs-max-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Bypassing iCloud Activation Lock on iPhone XS Max</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-samsung-galaxy-s23-tactical-edition-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Samsung Galaxy S23 Tactical Edition Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://fox-blue.techidaily.com/perfecting-motion-capture-a-guide-to-gopro-time-lapse-photos/"><u>Perfecting Motion Capture A Guide to GoPro Time Lapse Photos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-hosted-network-failures-in-windows-10/"><u>Resolved: Troubleshooting Hosted Network Failures in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-update-issues-how-to-fix-windows-11-freezing-during-installation/"><u>Resolving Update Issues: How to Fix Windows 11 Freezing During Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-non-functioning-scroll-buttons-in-synaptics-mouse-pad-for-windows-10-users/"><u>Solving Non-Functioning Scroll Buttons in Synaptics Mouse Pad for Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-lenovo-mouse-pad-issues-on-windows-10-8-and-7-solutions-included/"><u>Troubleshooting Lenovo Mouse Pad Issues on Windows 10, 8 & 7 – Solutions Included</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-addressing-serious-bugs-and-crashes-in-black-ops-4/"><u>Troubleshooting Steps: Addressing Serious Bugs and Crashes in Black Ops 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-windows-0xc0000005-blue-screen-of-death/"><u>Ultimate Guide: Resolving the Windows 0xC0000005 Blue Screen of Death</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

