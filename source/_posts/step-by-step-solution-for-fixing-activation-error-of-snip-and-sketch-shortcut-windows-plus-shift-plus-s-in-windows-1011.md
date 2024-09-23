---
title: Step-by-Step Solution for Fixing Activation Error of Snip & Sketch Shortcut (Windows + Shift + S) in Windows 10/11
date: 2024-09-18T18:46:13.784Z
updated: 2024-09-23T01:16:51.540Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for Fixing Activation Error of Snip & Sketch Shortcut (Windows + Shift + S) in Windows 10/11
excerpt: This Article Describes Step-by-Step Solution for Fixing Activation Error of Snip & Sketch Shortcut (Windows + Shift + S) in Windows 10/11
thumbnail: https://thmb.techidaily.com/2151304b15358b5e0486365b1b4e0f5fc2185a4452deb2b08eaf2b9d1e47c0a1.jpg
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
<li><a href="https://vp-tips.techidaily.com/new-maintain-eye-contact-this-helps-establish-rapport-with-the-speaker-and-shows-your-engagement/"><u>[New] Maintain Eye Contact This Helps Establish Rapport with the Speaker and Shows Your Engagement</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-premier-screen-capture-apps-for-windows-free-1-5-listing/"><u>[Updated] In 2024, Premier Screen Capture Apps for Windows Free #1-5 Listing</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-unveiling-the-top-10-historic-content-creators-on-youtube-for-2024/"><u>[Updated] Unveiling the Top 10 Historic Content Creators on YouTube for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/4-things-you-must-know-about-apple-iphone-8-plus-activation-lock-by-drfone-ios/"><u>4 Things You Must Know About Apple iPhone 8 Plus Activation Lock</u></a></li>
<li><a href="https://games-able.techidaily.com/explore-the-best-1440p-gaming-screens-for-all-prices/"><u>Explore the Best 1440P Gaming Screens for All Prices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratis-mp4-videos-in-flac-format-converteren-online-zeer-veilig/"><u>Gratis MP4-Video's in FLAC Format Converteren - Online Zeer Veilig</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-tecno-spark-10c-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Tecno Spark 10C to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/how-to-shrink-m2t-files-into-mp4-without-losing-high-definition-quality/"><u>How to Shrink M2T Files Into MP4 without Losing High-Definition Quality</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-the-sound-enthusiasts-companion-high-quality-recording-tips/"><u>In 2024, The Sound Enthusiast's Companion High-Quality Recording Tips</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/resolved-mystery-of-absentee-shorts/"><u>Resolved Mystery of Absentee Shorts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trasforma-file-opus-in-formato-aac-online-e-liberamente-movavi/"><u>Trasforma File OPUS in Formato AAC Online E Liberamente - Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trier-gratuitement-un-fichier-wav-vers-le-format-m4r-sur-internet-movavi/"><u>Trier Gratuitement Un Fichier WAV Vers Le Format M4R Sur Internet - Movavi</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

