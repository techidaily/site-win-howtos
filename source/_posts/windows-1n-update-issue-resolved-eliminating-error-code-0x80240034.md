---
title: "Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
date: 2024-12-15T16:06:07.485Z
updated: 2024-12-22T22:53:25.575Z
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
<li><a href="https://instagram-video-files.techidaily.com/new-instagram-searching-skills-unlock-additional-free-filters/"><u>[New] Instagram Searching Skills – Unlock Additional Free Filters</u></a></li>
<li><a href="https://youtube-data.techidaily.com/outubes-financial-frontier-maximizing-your-content-revenue-for-2024/"><u>[New] YouTube's Financial Frontier Maximizing Your Content Revenue for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-5-ways-to-record-webinar-for-free-for-2024/"><u>[Updated] 5 Ways to Record Webinar for Free for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-enhancing-video-aesthetics-incorporating-lc-and-bb-in-facebook-posts/"><u>[Updated] In 2024, Enhancing Video Aesthetics Incorporating LC and BB in Facebook Posts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-unveiling-the-instagram-success-script/"><u>[Updated] In 2024, Unveiling the Instagram Success Script</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-windows-11s-airplane-mode-issue-effective-strategies-and-tips/"><u>Addressing Windows 11'S Airplane Mode Issue: Effective Strategies and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-overcoming-the-0x80072efd-mishap-on-windows-10-systems/"><u>Effective Solutions for Overcoming the 0X80072EFD Mishap on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-excessive-cpu-consumption-caused-by-wudfhostexe-on-windows-10/"><u>How to Resolve Excessive CPU Consumption Caused by WUDFHost.exe on Windows 10</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-step-by-step-sharing-photos-on-youtube/"><u>In 2024, Step-by-Step Sharing Photos on YouTube</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/navigating-rights-to-instagram-lyrics/"><u>Navigating Rights to Instagram Lyrics</u></a></li>
<li><a href="https://program-issues.techidaily.com/pc-troubleshooting-addressing-thaumaturge-crashes-on-windows-and-macos-systems/"><u>PC Troubleshooting: Addressing Thaumaturge Crashes on Windows & MacOS Systems</u></a></li>
<li><a href="https://unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-itel-p55-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Itel P55</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-repair-your-wacom-pen-in-windows-11-or-windows-10-environments/"><u>Troubleshooting Guide: How to Repair Your Wacom Pen in Windows 11 or Windows 10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-total-war-rome-remastered-crashes-solved/"><u>Troubleshooting Total War Rome Remastered Crashes – Solved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-cant-i-adjust-my-volume-in-windows-10-solution-details/"><u>Why Can't I Adjust My Volume in Windows 10? [SOLUTION DETAILS]</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

