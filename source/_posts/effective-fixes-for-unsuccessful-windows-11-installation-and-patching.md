---
title: Effective Fixes for Unsuccessful Windows 11 Installation and Patching
date: 2024-12-22T14:38:24.125Z
updated: 2024-12-28T08:36:47.086Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Effective Fixes for Unsuccessful Windows 11 Installation and Patching
excerpt: This Article Describes Effective Fixes for Unsuccessful Windows 11 Installation and Patching
thumbnail: https://thmb.techidaily.com/3e64ab7fbedf01adf094c0f7a07b62ec8466f937073c7188969d1624a01e5f53.jpg
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
<li><a href="https://article-files.techidaily.com/new-in-2024-downgrading-tips-from-sierra-to-os-x-el-capitan-version/"><u>[New] In 2024, Downgrading Tips From Sierra to OS X El Capitan Version</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-insights-on-constructing-high-quality-srt-files/"><u>[Updated] Expert Insights on Constructing High-Quality SRT Files</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-mastery-of-video-sharing-a-guide-to-utilizing-zoom-on-the-youtube-platform/"><u>[Updated] In 2024, Mastery of Video Sharing A Guide to Utilizing Zoom on the YouTube Platform</u></a></li>
<li><a href="https://fox-that.techidaily.com/cant-scan-qr-codes-here-are-10-tips-to-restore-functionality-on-your-iphone/"><u>Can't Scan QR Codes? Here Are 10 Tips to Restore Functionality on Your iPhone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-overcoming-the-403-forbidden-error-challenge/"><u>Effective Solutions for Overcoming the '403 Forbidden Error' Challenge</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-usb-connectivity-interruptions-and-power-surges-in-windows-11-systems/"><u>Expert Tips to Overcome USB Connectivity Interruptions and Power Surges in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209354271-fix-pc-stuck-on-getting-windows-ready/"><u>Fix PC Stuck on “Getting Windows Ready”</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-tecno-phantom-v-flip-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-xiaomi-redmi-12-5g-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Xiaomi Redmi 12 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-valentines-day-2023-a-step-by-step-guide-to-making-a-romantic-video/"><u>In 2024, Valentines Day 2023 A Step-by-Step Guide to Making a Romantic Video</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-fresh-renderer-launch-issues-apply-the-latest-fix/"><u>Overcome Fresh Renderer Launch Issues - Apply the Latest Fix!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

