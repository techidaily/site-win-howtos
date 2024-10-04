---
title: Complete Fixes for Windows 11 Installation Problems You've Encountered
date: 2024-10-02T02:33:54.728Z
updated: 2024-10-04T13:35:50.196Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Complete Fixes for Windows 11 Installation Problems You've Encountered
excerpt: This Article Describes Complete Fixes for Windows 11 Installation Problems You've Encountered
thumbnail: https://thmb.techidaily.com/468b7a50fb837089e10cec38dd44fa01aaab4078b704b313fd2f69558ac117bb.png
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
<li><a href="https://youtube-clips.techidaily.com/new-essential-insights-into-youtubes-content-policy-framework/"><u>[New] Essential Insights Into YouTube's Content Policy Framework</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-capturing-consciousness-proven-techniques-for-documenting-virtual-play/"><u>[Updated] 2024 Approved Capturing Consciousness Proven Techniques for Documenting Virtual Play</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-elevate-user-experience-with-these-leading-videophones-for-2024/"><u>[Updated] Elevate User Experience with These Leading Videophones for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-look-ups-for-gopro-movies-select-15-luts-for-2024/"><u>Best Look-Ups for GoPro Movies Select 15 LUTs for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-to-combat-overwhelming-cpu-demand-within-windows-driver-foundation/"><u>Effective Strategies to Combat Overwhelming CPU Demand Within Windows Driver Foundation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/experiencing-netflix-difficulties-learn-how-to-fix-common-problems/"><u>Experiencing Netflix Difficulties? Learn How To Fix Common Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-broken-function-keyboard-issues-on-your-asus-computer-a-step-by-step-fix/"><u>Fix Broken Function Keyboard Issues on Your ASUS Computer – A Step-by-Step Fix</u></a></li>
<li><a href="https://fox-that.techidaily.com/fixing-facetime-a-comprehensive-list-of-strategies-and-troubleshooting-steps/"><u>Fixing FaceTime: A Comprehensive List of Strategies and Troubleshooting Steps</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/harness-the-power-of-mematic-for-notes/"><u>Harness the Power of Mematic for Notes</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-the-video-money-roadmap-dailymotion-and-youtube-compared/"><u>In 2024, The Video Money Roadmap Dailymotion & YouTube Compared</u></a></li>
<li><a href="https://win-howtos.techidaily.com/missing-sd-recognition-here-to-help/"><u>Missing SD Recognition? Here to Help!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fix-your-windows-11-from-getting-stuck-at-the-startup-screen-instantly/"><u>Resolved: Fix Your Windows 11 From Getting Stuck at the Startup Screen Instantly</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-future-of-augmented-interaction-qualcomms-pioneering-project-with-samsung-and-google-in-creating-next-gen-smart-glasses-exclusive-analysis-by-5/"><u>Unveiling the Future of Augmented Interaction: Qualcomm's Pioneering Project with Samsung and Google in Creating Next-Gen Smart Glasses – Exclusive Analysis by ZDNet</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-the-top-6-head-mounts-expert-reviews-for-action-photography-for-2024/"><u>Unveiling The Top 6 Head Mounts Expert Reviews for Action Photography for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

