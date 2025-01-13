---
title: "Resolved Issue: Decode the Mystery Behind Error Code 0X80004005"
date: 2025-01-12T17:21:17.539Z
updated: 2025-01-13T16:08:45.711Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved Issue: Decode the Mystery Behind Error Code 0X80004005"
excerpt: "This Article Describes Resolved Issue: Decode the Mystery Behind Error Code 0X80004005"
thumbnail: https://thmb.techidaily.com/be7eb26b929d376d352a2b6560c781f129b853a9868bdf923c96ee4b76c8aaef.jpg
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
<li><a href="https://extra-resources.techidaily.com/updated-accessible-alternatives-googles-simplicity-versus-samsungs-innovation/"><u>[Updated] Accessible Alternatives Google's Simplicity Versus Samsung's Innovation</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-crafting-perfect-youtube-music-playlists-via-web-and-mobile-platforms/"><u>[Updated] In 2024, Crafting Perfect YouTube Music Playlists via Web & Mobile Platforms</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-the-missing-desktop-icon-under-systemprofile-directory/"><u>Effective Solutions for the Missing Desktop Icon Under SystemProfile Directory</u></a></li>
<li><a href="https://fox-helps.techidaily.com/evaluating-video-space-on-a-64gb-card/"><u>Evaluating Video Space on a 64GB Card</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-the-startup-screen-problem-in-monster-hunter-world/"><u>Expert Tips to Overcome the Startup Screen Problem in Monster Hunter: World</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-11-installation-error-802e0020-step-by-step-solution-guide/"><u>Fixing Windows 11 Installation Error 802E0020 - Step-by-Step Solution Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-itel-p55-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Itel P55? | Dr.fone</u></a></li>
<li><a href="https://win-workspace.techidaily.com/how-does-cryptocurrency-transform-finance-discover-key-advantages-according-to-experts-at-yl-software/"><u>How Does Cryptocurrency Transform Finance? Discover Key Advantages According to Experts at YL Software</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-locked-iphone-6-without-passcode-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock locked iPhone 6 without Passcode</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-picks-expert-recommended-8-convertors-from-sub-to-srt/"><u>In 2024, Top Picks Expert-Recommended 8 Convertors From Sub to Srt</u></a></li>
<li><a href="https://extra-support.techidaily.com/pivot-producer-system-for-2024/"><u>Pivot Producer System for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixes-how-to-restore-function-key-usage-on-your-device/"><u>Troubleshooting Fixes: How to Restore Function Key Usage on Your Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win11-speeds-up-resolving-high-wmi-cpu-consumption/"><u>Win11 Speeds Up: Resolving High WMI CPU Consumption</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206517999-your-sd-card-not-detected-heres-the-fix/"><u>Your SD Card Not Detected? Here's the Fix</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

