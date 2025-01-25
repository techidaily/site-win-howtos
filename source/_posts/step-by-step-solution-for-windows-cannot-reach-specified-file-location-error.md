---
title: Step-by-Step Solution for 'Windows Cannot Reach Specified File Location Error'
date: 2025-01-23T18:10:47.959Z
updated: 2025-01-25T16:42:38.833Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for 'Windows Cannot Reach Specified File Location Error'
excerpt: This Article Describes Step-by-Step Solution for 'Windows Cannot Reach Specified File Location Error'
thumbnail: https://thmb.techidaily.com/2e98346ae0ee2e0559c5260d992a7113232d0df75bda10dff9dc91899db94103.jpg
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-essential-steps-for-embedding-facebook-streams-online/"><u>[New] 2024 Approved Essential Steps for Embedding Facebook Streams Online</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-meme-crafters-companion/"><u>2024 Approved Meme Crafter's Companion</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-premier-top-youtube-views-monitor-for-content-success/"><u>2024 Approved Premier Top YouTube Views Monitor for Content Success</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-premium-screens-at-their-peak-top-10-listings-for-4k-monitors/"><u>2024 Approved Premium Screens at Their Peak Top #10 Listings for 4K Monitors</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-ways-to-convert-mp4-videos-to-mp3-audio-files/"><u>Best Ways to Convert MP4 Videos to MP3 Audio Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-for-windows-11s-tricky-0x80072efd-problem/"><u>Comprehensive Solutions for Windows 11'S Tricky 0X80072EFD Problem</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-essential-steps-for-resizing-videos-in-igtv/"><u>In 2024, Essential Steps for Resizing Videos in IGTV</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-your-pcs-sudden-shutdown-issue-a-step-by-step-guide/"><u>Resolving Your PC's Sudden Shutdown Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-unfreezing-your-mouse-on-a-computer/"><u>Solving the Issue: Unfreezing Your Mouse on a Computer</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-itel-a60-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Itel A60 to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-overcome-windows-11-update-error-code-0x80240034-easily/"><u>Troubleshooting Guide: Overcome Windows 11 Update Error Code 0X80240034 Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-windows-update-database-glitch-solutions-for-windows-10-users/"><u>Troubleshooting the Windows Update Database Glitch – Solutions for Windows 10 Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ultimate-slomo-videography-tool-assessment/"><u>Ultimate SloMo Videography Tool Assessment</u></a></li>
<li><a href="https://some-approaches.techidaily.com/umwandlung-von-dvds-zu-digitalen-videoversionen-unter-windows-11-und-macos/"><u>Umwandlung Von DVDs Zu Digitalen Videoversionen Unter Windows 11 Und macOS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-to-do-when-you-encounter-a-missing-component-error-message/"><u>What to Do When You Encounter a Missing Component Error Message</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206260715-why-wont-your-surface-charge-heres-how-to-fix-it/"><u>Why Won't Your Surface Charge? Here's How to Fix It!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

