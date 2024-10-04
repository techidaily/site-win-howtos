---
title: "Resolving the HTTP Error 403: Forbidden - A Step-by-Step Guide"
date: 2024-10-02T16:00:04.169Z
updated: 2024-10-04T16:00:07.992Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the HTTP Error 403: Forbidden - A Step-by-Step Guide"
excerpt: "This Article Describes Resolving the HTTP Error 403: Forbidden - A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/933460ab5e97c9ff94ee3e62c125239a5731074d09b9d43607b3861f48a7087e.jpg
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
<li><a href="https://article-helps.techidaily.com/updated-elevate-your-visual-narrative-with-top-ae-text-configurations-for-2024/"><u>[Updated] Elevate Your Visual Narrative with Top AE Text Configurations for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-evolution-of-engagement-key-post-vidcon-events-for-2024/"><u>[Updated] Evolution of Engagement Key Post-VidCon Events for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-top-10-youtube-video-grabber-apps-best-in-class-compatibility-for-2024/"><u>[Updated] Top 10 YouTube Video Grabber Apps, Best-in-Class Compatibility for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726225667681-2024-mov/"><u>2024 MOV 파일 소개: 무엇이고, 구현하는 방법</u></a></li>
<li><a href="https://win-howtos.techidaily.com/descargue-la-herramienta-de-conversion-sin-coste-para-transformar-video-3gp-en-clipas-jpg-online/"><u>Descargue La Herramienta De Conversión Sin Coste Para Transformar Video 3GP en Clipas JPG Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratuit-gratuicam-converteren-van-3gpp-naar-mp4-online-movavi/"><u>Gratuit Gratuicam-Converteren Van 3GPP Naar MP4 Online - Movavi</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-by-checkra1n-even-from-iphone-se-2022-if-youve-tried-everything-by-drfone-ios/"><u>How To Bypass iCloud By Checkra1n Even From iPhone SE (2022) If Youve Tried Everything</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-djis-innovation-race-how-mavic-air-shifts-the-scene-against-spark/"><u>In 2024, DJI’s Innovation Race How Mavic Air Shifts the Scene Against Spark</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-youtubers-unite-with-these-17-top-tier-lights/"><u>In 2024, Youtubers Unite with These 17 Top-Tier Lights</u></a></li>
<li><a href="https://hardware-help.techidaily.com/instant-guide-to-installing-intel-nuc-driver-updates-with-ease/"><u>Instant Guide to Installing Intel NUC Driver Updates with Ease</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/nvidia-connection-controversy-unveiled-corsair-power-unit-specialist-jonny-gurus-insights/"><u>NVIDIA Connection Controversy Unveiled: Corsair Power Unit Specialist Jonny Guru's Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/onziembote-de-sleutelschip-papier-mkb-lidt-uit-vob-tuin-van-gefreezeert-te-lesten-en-profect-zweetlijk-internet-converter-movavi/"><u>ONZIEMBOTE DE SLEUTELSCHIP PAPIER MKB LIDT UIT VOB TUIN VAN GEFREEZEERT TE LESTEN EN PROFECT: ZWEETLIJK INTERNET-CONVERTER - MOVAVI</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-connectivity-hurdles-in-your-minecraft-lan-gameplay/"><u>Overcoming Connectivity Hurdles in Your Minecraft LAN Gameplay</u></a></li>
<li><a href="https://tech-hub.techidaily.com/safeguarding-sensitive-information-best-practices-for-securely-utilizing-chatgpt-in-professional-settings/"><u>Safeguarding Sensitive Information: Best Practices for Securely Utilizing ChatGPT in Professional Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-steps-to-reduce-video-size-for-optimal-upload-on-youtube/"><u>Simple Steps to Reduce Video Size for Optimal Upload on YouTube</u></a></li>
<li><a href="https://screen-capture.techidaily.com/top-5-chromebook-sniping-apps-essential-clients-reviewed/"><u>Top 5 Chromebook Sniping Apps Essential Clients Reviewed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transformez-votre-fichier-audio-en-m4a-gratuitement-enligne-guide-video-conversion-avec-movavi/"><u>Transformez Votre Fichier Audio en M4A Gratuitement Enligne - Guide Vidéo Conversion Avec Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mkv-m4v-onlinetool-movavi/"><u>무료 MKV에서 M4V로 전환해주는 Onlinetool - Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wmv3g/"><u>オンラインで簡単! フリー版WMVビデオを3G形式に変換 - 動画美化の革命</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925468/19272" target="_top" id="1925468">
  <img src="//a.impactradius-go.com/display-ad/19272-1925468" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925468/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

