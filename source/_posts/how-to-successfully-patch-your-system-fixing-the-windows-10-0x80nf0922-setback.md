---
title: "How To Successfully Patch Your System: Fixing The Windows 10 0X80nf0922 Setback"
date: 2025-01-01T16:39:50.990Z
updated: 2025-01-06T16:29:50.884Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How To Successfully Patch Your System: Fixing The Windows 10 0X80nf0922 Setback"
excerpt: "This Article Describes How To Successfully Patch Your System: Fixing The Windows 10 0X80nf0922 Setback"
thumbnail: https://thmb.techidaily.com/2d67e14b0eb8d4077153a676b64f0ce1665316566b80f80c4fccfcd9a772edaa.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-beginning-the-video-odyssey-how-to-create-an-engaging-youtube-channel/"><u>[New] 2024 Approved Beginning the Video Odyssey How to Create an Engaging YouTube Channel</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-top-8-windows-11-video-snatchers-unveiled/"><u>[New] In 2024, Top 8 Windows 11 Video Snatchers Unveiled</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-optimize-your-presence-mastering-snapchat-business-use-for-2024/"><u>[New] Optimize Your Presence Mastering Snapchat Business Use for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-the-ultimate-guide-to-earning-through-youtubing-enabling-monetization-on-mobile-devices/"><u>[Updated] 2024 Approved The Ultimate Guide to Earning Through YouTubing Enabling Monetization on Mobile Devices</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-digital-learning-session-replays/"><u>[Updated] In 2024, Digital Learning Session Replays</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-easy-steps-to-alter-story-video-playback-speed/"><u>2024 Approved Easy Steps to Alter Story Video Playback Speed</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/7-top-ways-to-resolve-apple-id-not-active-issue-for-apple-iphone-12-pro-max-drfone-by-drfone-ios/"><u>7 Top Ways To Resolve Apple ID Not Active Issue For Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726222260753-avi-mp4-movavi/"><u>立即將 AVI 影片轉換成 MP4 的線上免費方法 - 運用 Movavi 技術</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726225772103-bmppng-movavi/"><u>網路直接無成本 BMP到PNG 轉換 - 使用Movavi的方法</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conversion-de-mp2-vers-flac-pour-free-online-utilisez-le-service-de-conversion-gratuit-de-movavi/"><u>Conversion De MP2 Vers FLAC Pour Free Online - Utilisez Le Service De Conversion Gratuit De Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/create-gifs-from-tiff-files-without-cost-discover-the-magic-of-movavis-web-based-tool/"><u>Create GIFs From TIFF Files Without Cost - Discover the Magic of Movavi's Web-Based Tool</u></a></li>
<li><a href="https://location-social.techidaily.com/does-xiaomi-redmi-13c-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Xiaomi Redmi 13C 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/free-online-converter-effortlessly-transforming-3gp3g2-files-into-mp4-format-with-movavi/"><u>Free Online Converter: Effortlessly Transforming 3GP/3G2 Files Into MP4 Format with Movavi</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-can-you-unlock-apple-iphone-6s-plus-after-forgetting-the-passcode-drfone-by-drfone-ios/"><u>In 2024, Can You Unlock Apple iPhone 6s Plus After Forgetting the Passcode? | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-farm-frenzy-the-ultimate-group-game-guide-for-farms/"><u>In 2024, Farm Frenzy The Ultimate Group Game Guide for Farms</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movavis-no-cost-tool-for-easy-offline-editing-of-mxf-videos-to-mpg/"><u>Movavi's No-Cost Tool for Easy Offline Editing of MXF Videos to MPG</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movavimpeg3g2/"><u>Movaviアプリを使った無料MPEGから3G2への簡単なオンライン変換方法</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movavipng-raw/"><u>MovaviでシームレスなオンラインPNG画像を無料変更 - RAWへの即時変換</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-18-best-free-video-compression-tools-of-2e24-windows-and-mac-compatible/"><u>Top 18 Best Free Video Compression Tools of 2E24 - Windows & Mac Compatible</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

