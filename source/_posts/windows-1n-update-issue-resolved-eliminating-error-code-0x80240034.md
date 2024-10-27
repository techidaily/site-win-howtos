---
title: "Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
date: 2024-10-20T17:11:34.750Z
updated: 2024-10-27T18:04:00.161Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
excerpt: "This Article Describes Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
thumbnail: https://thmb.techidaily.com/d44c84cbf0699642eded061365e62aa884811112a5aa8ff88c8335f623b0d0e8.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

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
<li><a href="https://facebook-video-content.techidaily.com/new-fb-content-downloaded-masterful-mp4-edition-for-2024/"><u>[New] FB Content Downloaded Masterful MP4 Edition for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-best-in-class-no-charging-switch-replicas/"><u>[New] In 2024, Best-in-Class, No-Charging Switch Replicas</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-simplicity-in-recording-an-overwatch-perspective/"><u>[New] In 2024, Simplicity in Recording An Overwatch Perspective</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-unusual-sideway-photos-in-instagram-storytelling/"><u>2024 Approved Unusual Sideway Photos in Instagram Storytelling</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-solutions-for-fixing-windows-11-bluetooth-connectivity-problems/"><u>Effortless Solutions for Fixing Windows 11 Bluetooth Connectivity Problems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ensuring-optimal-performance-updating-your-toshiba-satellites-windows-drivers-made-simple/"><u>Ensuring Optimal Performance: Updating Your Toshiba Satellite's Windows Drivers Made Simple</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-restoring-functionality-to-a-stuck-spacebar-on-windows-pressure-systems/"><u>Expert Advice: Restoring Functionality to a Stuck Spacebar on Windows Pressure Systems</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-lava-yuva-3-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-chromecast-updates-a-comprehensive-guide/"><u>Mastering Chromecast Updates: A Comprehensive Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/perfecting-zoom-on-snapchat-for-better-snaps-for-2024/"><u>Perfecting Zoom on Snapchat for Better Snaps for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-resolve-microsoft-error-code-651-on-your-pc/"><u>Quick Solutions: Resolve Microsoft Error Code 651 on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-windows-update-troubles-with-easy-fixes-for-unfound-patches/"><u>Solve Your Windows Update Troubles with Easy Fixes for Unfound Patches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-livekernelevent-144-mistake-step-by-step-guide/"><u>Solving the LiveKernelEvent 144 Mistake: Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-easily-overcoming-error-0x80070652-during-windows-updates/"><u>Step-by-Step Fixes for Easily Overcoming Error 0X80070652 During Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-overcoming-driverpowerstatefailure-woes/"><u>Step-by-Step Guide: Overcoming DRIVER_POWER_STATE_FAILURE Woes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-the-runtimebroker-service-resolving-high-cpu-usage-issues-in-windows-10/"><u>Understanding the RuntimeBroker Service: Resolving High CPU Usage Issues in Windows 10</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-your-instagram-saves-tips-for-monitoring-profile-engagement/"><u>Unveiling Your Instagram Saves: Tips for Monitoring Profile Engagement</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

