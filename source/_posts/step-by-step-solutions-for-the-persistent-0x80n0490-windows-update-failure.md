---
title: Step-by-Step Solutions for the Persistent 0X80n0490 Windows Update Failure
date: 2024-10-02T05:10:47.671Z
updated: 2024-10-04T05:28:52.669Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for the Persistent 0X80n0490 Windows Update Failure
excerpt: This Article Describes Step-by-Step Solutions for the Persistent 0X80n0490 Windows Update Failure
thumbnail: https://thmb.techidaily.com/672b93a029ff6e4433ec19a377fab4ffa2a67286a950d0a63433c57fd863da90.jpg
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
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-oppo-reno-10-5g-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Oppo Reno 10 5G System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-unexpected-outages-how-to-fix-your-erratic-internet-connection/"><u>Dealing With Unexpected Outages: How to Fix Your Erratic Internet Connection</u></a></li>
<li><a href="https://games-able.techidaily.com/dynamic-cooling-design-maximizes-graphics-output-speed/"><u>Dynamic Cooling Design Maximizes Graphics Output Speed</u></a></li>
<li><a href="https://fox-sure.techidaily.com/how-can-i-protect-my-photographs-a-comprehnensive-guide-on-copyrighting-imagery/"><u>How Can I Protect My Photographs? A Comprehnensive Guide on Copyrighting Imagery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-audio-hardware-detection-failures-on-windows-11-computers/"><u>How to Fix Audio Hardware Detection Failures on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-when-your-macs-trackpad-wont-respond/"><u>How to Repair When Your Mac's Trackpad Won't Respond</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-your-itel-p55-lock-screen-password-by-drfone-android/"><u>How to Reset your Itel P55 Lock Screen Password</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mute-monitor-mayhem-with-ease/"><u>Mute Monitor Mayhem with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/obs-game-capturing-woes-fix-that-perplexing-black-screen-issue-today/"><u>OBS Game Capturing Woes? Fix That Perplexing Black Screen Issue Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-surface-keyboard-quirk/"><u>Resolved Surface Keyboard Quirk</u></a></li>
<li><a href="https://video-capture.techidaily.com/speedy-conversion-trick-transform-your-flac-collection-into-mp3-instantly/"><u>Speedy Conversion Trick: Transform Your FLAC Collection Into MP3 Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-strategies-to-revive-and-restart-an-unresponsive-pc/"><u>Step-by-Step Strategies to Revive and Restart an Unresponsive PC</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-and-solving-chromes-heavy-cpu-load-problems/"><u>Troubleshooting and Solving Chrome’s Heavy CPU Load Problems</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134500/19576" target="_top" id="2134500">
  <img src="//a.impactradius-go.com/display-ad/19576-2134500" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134500/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

