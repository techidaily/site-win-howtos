---
title: "Solving WiFi Connectivity Problems: A Guide for Windows 10 and #7 Users"
date: 2024-09-18T19:00:30.963Z
updated: 2024-09-22T21:30:52.024Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solving WiFi Connectivity Problems: A Guide for Windows 10 and #7 Users"
excerpt: "This Article Describes Solving WiFi Connectivity Problems: A Guide for Windows 10 and #7 Users"
thumbnail: https://thmb.techidaily.com/1c9229fb0800113350dfae57f612d2aef9036646b6591dcd5ed2f832a16cf380.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/updated-from-boring-to-buzzing-three-tactics-for-youtube-reaction-mastery/"><u>[Updated] From Boring to Buzzing Three Tactics for YouTube Reaction Mastery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1-best-free-platforms-discover-the-top-12-sites-streaming-korean-dramas-without-cost/"><u>1. Best Free Platforms: Discover the Top 12 Sites Streaming Korean Dramas Without Cost</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-sneak-peeks-stealthy-video-capture-techniques/"><u>2024 Approved Sneak Peeks Stealthy Video Capture Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/divisez-vos-fichiers-videovisuels-facilement-les-6-solutions-logiciels-de-bureau-vs-en-ligne/"><u>Divisez Vos Fichiers Videovisuels Facilement: Les 6 Solutions Logiciels De Bureau vs en Ligne</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dvacet-vehlasych-metu-pokusu-konverzovat-dat-na-mp4-kompletni-navod-s-movavi-konvertorem/"><u>Dvacet Věhlasých Métů Pokusu Konverzovat DAT Na MP4 - Kompletní Návod S Movavi Konvertorem</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-installation-hp-driver-downloads-compatible-with-windows-10/"><u>Easy Installation: HP Driver Downloads Compatible with Windows 10</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/te-video-consumption-constructing-an-ideal-watch-later-list-on-youtube/"><u>Elevate Video Consumption Constructing an Ideal 'Watch Later' List on YouTube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-detaille-comment-utiliser-le-convertisseur-audio-wav-de-movavi-pour-la-conversion-des-fichiers/"><u>Guide Détaillé : Comment Utiliser Le Convertisseur Audio WAV De Movavi Pour La Conversion Des Fichiers</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/learn-how-to-lock-stolen-your-iphone-8-plus-properly-drfone-by-drfone-ios/"><u>Learn How To Lock Stolen Your iPhone 8 Plus Properly | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068440/7443" target="_top" id="2068440">
  <img src="//a.impactradius-go.com/display-ad/7443-2068440" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068440/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

