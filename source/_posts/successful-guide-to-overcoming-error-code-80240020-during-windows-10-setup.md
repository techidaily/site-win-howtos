---
title: Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
date: 2024-10-28T23:21:35.901Z
updated: 2024-11-02T09:58:34.923Z
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
<li><a href="https://tiktok-clips.techidaily.com/new-20-popular-tiktok-country-songs-to-take-a-relax-and-dance-to/"><u>[New] 20 Popular TikTok Country Songs to Take a Relax and Dance To</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-immersion-redefined-vrs-cinematic-promise/"><u>[New] 2024 Approved Immersion Redefined VR's Cinematic Promise</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-stylish-profiles-easy-downloads/"><u>[New] 2024 Approved Stylish Profiles, Easy Downloads</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-crafting-serenity-a-spiritual-journey-through-6-intellectually-designed-minecraft-modern-houses/"><u>[New] In 2024, Crafting Serenity A Spiritual Journey Through 6 Intellectually Designed Minecraft Modern Houses</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-asus-rog-phone-8-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/64gb-ideal-for-light-video-content-for-2024/"><u>64Gb Ideal for Light Video Content for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-dvd-to-wmv-upgrades-secrets-to-achieving-top-notch-resolution-on-a-windows-pc/"><u>Mastering DVD to WMV Upgrades: Secrets to Achieving Top-Notch Resolution on a Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mp3-word/"><u>MP3への変換ガイド - Wordで読み上げ機能を利用する</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mp3iphone-voice-memo/"><u>MP3へのiPhone Voice Memoコンバート手順</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-minimum-and-maximum-hardware-needs-for-software-applications/"><u>Navigating Minimum and Maximum Hardware Needs for Software Applications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/seamless-conversion-guide-turning-powerpoint-decks-into-picture-enhanced-google-slides/"><u>Seamless Conversion Guide: Turning PowerPoint Decks Into Picture-Enhanced Google Slides</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-converting-gifs-to-mkv-files-both-offline-and-online/"><u>Step-by-Step Guide: Converting GIFs to MKV Files Both Offline and Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-mastering-the-art-of-bin-file-unpacking/"><u>Step-by-Step Guide: Mastering the Art of BIN File Unpacking</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/sync-your-emails-setting-up-gmail-on-the-apple-watch/"><u>Sync Your Emails: Setting up Gmail on the Apple Watch</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-tips-and-tricks-for-an-unforgettable-labor-day-bash-insights-from-zdnet/"><u>Ultimate Guide: Tips and Tricks for an Unforgettable Labor Day Bash - Insights From ZDNet</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

