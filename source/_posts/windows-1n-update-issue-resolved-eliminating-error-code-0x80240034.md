---
title: "Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
date: 2024-12-07T18:38:41.065Z
updated: 2024-12-13T20:47:45.388Z
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-crafting-professional-grade-steam-gameplay-videos/"><u>[New] 2024 Approved Crafting Professional-Grade Steam Gameplay Videos</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-revolutionary-top-8-methods-convert-subtitles-to-srt-format-seamlessly/"><u>[New] In 2024, Revolutionary Top 8 Methods Convert Subtitles to SRT Format Seamlessly</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-mastering-multiplatform-meeting-logistics-on-zoom/"><u>[Updated] In 2024, Mastering Multiplatform Meeting Logistics on Zoom</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208722915-diagnosing-and-repairing-when-you-cant-watch-netflix-solutions-inside/"><u>Diagnosing & Repairing When You Can't Watch Netflix – Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-fixes-for-when-your-lenovo-laptop-camera-stops-working-expert-tips-included/"><u>DIY Fixes for When Your Lenovo Laptop Camera Stops Working - Expert Tips Included</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-driver-failed-mistake-adjust-your-user-configuration-correctly/"><u>Fixing 'Driver Failed' Mistake - Adjust Your User Configuration Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-unexpected-shutdown-error-1067-on-your-windows-pc-now-solved/"><u>How to Overcome Unexpected Shutdown (Error 1067) on Your Windows PC - Now Solved</u></a></li>
<li><a href="https://win-bits.techidaily.com/mise-a-jour-lecteur-dordinateur-d-maintenant-pret-pour-les-systemes-dexploitation-windows-1011/"><u>Mise À Jour : Lecteur D'ordinateur (D) Maintenant Prêt Pour Les Systèmes D'exploitation Windows 10/11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-nubia-red-magic-9-proplus-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Nubia Red Magic 9 Pro+ to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-and-easy-techniques-to-enhance-your-keyboards-speed/"><u>Quick & Easy Techniques to Enhance Your Keyboard's Speed</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-correcting-the-libgdk-win32-20-0dll-file-not-found-issue/"><u>Ultimate Guide: Correcting the libgdk-win32-2.0-0.dll File Not Found Issue</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

