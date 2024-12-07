---
title: Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
date: 2024-12-04T21:20:16.045Z
updated: 2024-12-07T18:03:40.437Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
excerpt: This Article Describes Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
thumbnail: https://thmb.techidaily.com/2e5cadcabaa5bc146e9286cd6ccf5e30c43742afdff538e1080a5add013b39bf.jpg
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

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
<li><a href="https://facebook-video-share.techidaily.com/updated-maximizing-youtube-revenue-understanding-adsense-payments-per-thousand-views/"><u>[Updated] Maximizing Youtube Revenue Understanding AdSense Payments per Thousand Views</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-ranking-the-top-10-stealth-story-fans-for-2024/"><u>[Updated] Ranking the Top 10 Stealth Story Fans for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1-effortless-video-downloads-from-crunchyroll-two-no-cost-techniques/"><u>1. Effortless Video Downloads From Crunchyroll: Two No-Cost Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028472447-pc2024/"><u>新解釈！PCで最新インスタグラムビデオをダウンロードする詳細手引き202#4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726029019327-windows-10/"><u>最新Windows 10でのマイクと内部オーディオ使用による録音プロセスガイド</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/breakthrough-in-youtube-saving-technology/"><u>Breakthrough in YouTube Saving Technology</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-nokia-150-2023-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Nokia 150 (2023) Location by Number | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-actions-cameras-reviewed-hero5-vs-yi-in-the-spotlight/"><u>Top Actions Cameras Reviewed Hero5 Vs. YI in the Spotlight</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-talkshoplive-reviews-and-pro-tips-is-this-the-live-commerce-tool-you-need-in-2024/"><u>Updated Talkshoplive Reviews & Pro Tips Is This the Live Commerce Tool You Need, In 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/vsdc-vs-alternatives-a-comprehensive-evaluation/"><u>VSDC vs Alternatives A Comprehensive Evaluation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-1011my-cinema-app/"><u>Windows 10/11版でMy Cinema Appをスムーズに動画録画するチュートリアル</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wmam4a/"><u>WMA音楽ファイルをM4A形式に効果的に変換する方法」</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028428055-youtube/"><u>ダウンロード可能なYouTube動画とその字幕:手引き</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-1/"><u>フリーかつ簡単な方法 - Windows 1</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

