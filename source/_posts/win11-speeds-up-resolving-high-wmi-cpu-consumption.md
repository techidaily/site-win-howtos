---
title: "Win11 Speeds Up: Resolving High WMI CPU Consumption"
date: 2024-10-05T23:23:57.919Z
updated: 2024-10-09T20:26:44.602Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Win11 Speeds Up: Resolving High WMI CPU Consumption"
excerpt: "This Article Describes Win11 Speeds Up: Resolving High WMI CPU Consumption"
thumbnail: https://thmb.techidaily.com/c18d888464621b9b20ff1e9897c3e6fc08590ad7205eab6f350d2eff8745d04c.jpg
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
<li><a href="https://desktop-recording.techidaily.com/updated-screen-casting-in-vlc-reviewed/"><u>[Updated] Screen Casting in VLC Reviewed</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-artistic-techniques-for-3d-text-effect/"><u>2024 Approved Artistic Techniques for 3D Text Effect</u></a></li>
<li><a href="https://fox-helps.techidaily.com/a-detailed-guide-to-extract-and-save-audio-from-popular-video-sharing-sites/"><u>A Detailed Guide to Extract and Save Audio From Popular Video Sharing Sites</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/beyond-the-hype-why-creating-gun-prototypes-via-3d-printing-is-tougher-than-it-seems/"><u>Beyond the Hype: Why Creating Gun Prototypes via 3D Printing Is Tougher Than It Seems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corrective-steps-when-your-hp-laptop-camera-fails-on-windows-11/"><u>Corrective Steps When Your HP Laptop Camera Fails on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-8024020-successful-troubleshooting-steps-for-windows-11-setup-issues/"><u>Error Code 8024020 - Successful Troubleshooting Steps for Windows 11 Setup Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/forza-horizon-asterisk-4-noise-solutions-eliminate-silence-and-enjoy-the-race-again/"><u>Forza Horizon Asterisk 4 Noise Solutions - Eliminate Silence and Enjoy the Race Again</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-boost-creativity-how-to-use-movie-maker-on-windows-8/"><u>In 2024, Boost Creativity How to Use Movie Maker on Windows 8</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-troubleshooting-the-livekernelevent-117-mistake/"><u>Step-by-Step Guide: Troubleshooting the LiveKernelEvent 117 Mistake</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-nokia-c300-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Nokia C300? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-repair-a-non-functional-microphone-in-a-laptop/"><u>Troubleshooting: How to Repair a Non-Functional Microphone in a Laptop</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-oppo-reno-8t-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Oppo Reno 8T 5G without Him Knowing | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006933/19272" target="_top" id="2006933">
  <img src="//a.impactradius-go.com/display-ad/19272-2006933" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

