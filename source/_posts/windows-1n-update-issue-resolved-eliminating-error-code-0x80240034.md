---
title: "Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
date: 2025-02-10T19:37:18.732Z
updated: 2025-02-16T22:50:21.364Z
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-audio-conversion-made-simple-youtube-to-mp3-mac-edition/"><u>[New] 2024 Approved Audio Conversion Made Simple YouTube to MP3, Mac Edition</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-exploring-youtubes-financial-blueprint-for-short-form-video-success/"><u>[New] 2024 Approved Exploring YouTube's Financial Blueprint for Short-Form Video Success</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/rom-zeroes-to-heroes-amplifying-your-youtube-following-for-2024/"><u>[New] From Zeroes to Heroes Amplifying Your Youtube Following for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-generate-laughter-kapwings-meme-creator-for-2024/"><u>[Updated] Generate Laughter Kapwing's Meme Creator for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elusive-search-icon-techniques-for-windows-11/"><u>Elusive Search Icon Techniques for Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-windows-11-screen-saver-issues-troubleshooting-steps/"><u>Fix Windows 11 Screen Saver Issues - Troubleshooting Steps</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-unlock-on-iphone-6s-plus-how-to-fix-it-by-drfone-ios/"><u>In 2024, Apple ID Unlock On iPhone 6s Plus? How to Fix it?</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-convert-your-social-feeds-videos-into-listenable-audio/"><u>In 2024, Convert Your Social Feed's Videos Into Listenable Audio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-how-to-fix-building-load-issues-on-pc/"><u>PUBG - How to Fix Building Load Issues on PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210334850-solution-found-overcoming-keyboard-input-issues-now-working/"><u>Solution Found: Overcoming Keyboard Input Issues - Now Working!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-common-errors-with-the-windows-11-start-button-and-menu-issues/"><u>Solving Common Errors with the Windows 11 Start Button and Menu Issues</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-samsung-galaxy-a14-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-resolution-of-the-critical-error-0x800f020b-during-xerox-printer-updates-in-windows/"><u>Step-by-Step Resolution of the Critical Error 0X800F020b During Xerox Printer Updates in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fix-guide-say-goodbye-to-csgo-freezes-and-crashes-fast/"><u>Ultimate Fix Guide: Say Goodbye to CSGO Freezes & Crashes Fast!</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unlock-free-youtube-gallery-downloads-now-for-2024/"><u>Unlock Free YouTube Gallery Downloads Now for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

