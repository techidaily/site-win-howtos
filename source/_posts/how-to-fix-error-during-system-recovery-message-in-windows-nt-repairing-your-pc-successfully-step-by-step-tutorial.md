---
title: How to Fix 'Error During System Recovery' Message in Windows nT-Repairing Your PC Successfully [Step-by-Step Tutorial]
date: 2024-09-16T16:46:41.369Z
updated: 2024-09-18T02:04:14.891Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix 'Error During System Recovery' Message in Windows nT-Repairing Your PC Successfully [Step-by-Step Tutorial]
excerpt: This Article Describes How to Fix 'Error During System Recovery' Message in Windows nT-Repairing Your PC Successfully [Step-by-Step Tutorial]
thumbnail: https://thmb.techidaily.com/2dd4d8c9b9a89a48c334c5f220a58a13ed27cebc631991e7d2875a1b4897165f.jpg
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
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-save-instastories-infinite-the-liberation-app/"><u>[Updated] 2024 Approved Save InstaStories Infinite The Liberation App</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-game-on-and-store-more-top-5-ssd-reviews-for-xbox/"><u>2024 Approved Game On & Store More Top 5 SSD Reviews for Xbox</u></a></li>
<li><a href="https://program-issues.techidaily.com/diagnose-and-fix-incompatible-version-problems-when-playing-valheim-on-windows/"><u>Diagnose & Fix 'Incompatible Version' Problems When Playing Valheim on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-samsung-galaxy-f14-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Samsung Galaxy F14 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/installing-the-morpheus-extension-for-enhanced-kodi-viewing-experience-is-it-matrix-ready/"><u>Installing the Morpheus Extension for Enhanced Kodi Viewing Experience - Is It Matrix Ready?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/m4riphonewav/"><u>M4R形式でiPhone着信音にWAVを転換する手順</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-quick-h264-edits-the-ultimate-tutorial-on-cutting-videos-with-ease/"><u>Mastering Quick H.264 Edits: The Ultimate Tutorial on Cutting Videos with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mkv-to-itunes-transformation-learn-the-top-three-techniques-for-seamless-playback/"><u>MKV to iTunes Transformation: Learn the Top Three Techniques for Seamless Playback</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movae/"><u>MOV形式でAEが認識できなくなった時、効果的なトラブルシューティング手順</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mp4mp3wav/"><u>MP4/MP3ビデオ音声をWAVフォーマットにアップコンバートする詳細ガイド</u></a></li>
<li><a href="https://win-howtos.techidaily.com/new-release-alert-enhanced-watermarks-with-wonderfoxs-latest-photography-software-v11/"><u>New Release Alert: Enhanced Watermarks with WonderFox's Latest Photography Software V1.1</u></a></li>
<li><a href="https://review-topics.techidaily.com/oppo-data-retrieval-tool-restore-lost-data-from-oppo-f23-5g-by-fonelab-android-recover-data/"><u>Oppo Data Retrieval tool – restore lost data from Oppo F23 5G</u></a></li>
<li><a href="https://win-solutions.techidaily.com/optimizing-your-play-fixing-fps-drop-problems-on-forza-horizon-5-pc/"><u>Optimizing Your Play: Fixing FPS Drop Problems on Forza Horizon 5 (PC)</u></a></li>
<li><a href="https://techtrends.techidaily.com/remote-access-mastery-how-to-stream-from-phone-or-pc-to-your-samsung-tv/"><u>Remote Access Mastery: How to Stream From Phone or PC to Your Samsung TV</u></a></li>
<li><a href="https://extra-hints.techidaily.com/step-by-step-guide-turn-onoff-picture-in-picture-mode-in-youtube-app/"><u>Step by Step Guide Turn On/Off Picture In Picture Mode in YouTube App</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094419/7443" target="_top" id="2094419">
  <img src="//a.impactradius-go.com/display-ad/7443-2094419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094419/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

