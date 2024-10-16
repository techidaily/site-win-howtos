---
title: Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix
date: 2024-10-12T19:35:32.899Z
updated: 2024-10-16T00:10:10.625Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix
excerpt: This Article Describes Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix
thumbnail: https://thmb.techidaily.com/6ac471d87db668dcc4b6f87c6982a3ef4bb37e3fbffe0068ce8a47124a8a8199.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-discover-prime-streaming-options-for-churches-today/"><u>[New] 2024 Approved Discover Prime Streaming Options for Churches Today</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-visual-storytelling-enhanced-by-these-top-7-graders-flair/"><u>2024 Approved Visual Storytelling Enhanced by These Top 7 Graders' Flair</u></a></li>
<li><a href="https://win-howtos.techidaily.com/oma-movavi/"><u>完全無料のOMAファイルオンラインコンバーター - Movaviプロジェクト</u></a></li>
<li><a href="https://win-howtos.techidaily.com/aacmp3-movavi/"><u>AACファイルを無料MP3へ自動変換: Movaviオンラインサービス</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conversione-gratuita-da-aac-ad-mpeg-online-tutorial-di-movavi/"><u>Conversione Gratuita Da AAC Ad MPEG Online - Tutorial Di Movavi</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-oppo-reno-11-pro-5g-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Oppo Reno 11 Pro 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-guide-transforming-mkv-videos-into-mp4-format-using-your-mac/"><u>Effortless Guide: Transforming MKV Videos Into MP4 Format Using Your Mac</u></a></li>
<li><a href="https://tech-revival.techidaily.com/evaluating-the-benefits-of-auto-gpt-as-an-alternative-to-waiting-for-gpt-4/"><u>Evaluating the Benefits of Auto-GPT as an Alternative to Waiting for GPT-4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratis-aif-naar-mp3-konverter-professioneel-onderhoud-van-je-musik-online/"><u>Gratis AIF Naar MP3 Konverter - Professioneel Onderhoud Van Je Musik Online</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6s-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6s to other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-11-pro-max-without-passcode-4-easy-methods-drfone-by-drfone-ios/"><u>How To Unlock iPhone 11 Pro Max Without Passcode? 4 Easy Methods | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-realme-c55-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Realme C55 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-how-to-double-down-on-your-youtube-success-in-a-month/"><u>In 2024, How to Double Down on Your YouTube Success in a Month</u></a></li>
<li><a href="https://win-howtos.techidaily.com/jpeg-vers-png-enligne-et-gratuit-changement-de-format-image-avec-movavi/"><u>JPEG Vers PNG: Enligne Et Gratuit Changement De Format Image Avec Movavi</u></a></li>
<li><a href="https://buynow-help.techidaily.com/professional-photography-essentials-discover-the-leading-tripods-on-the-market-2023-edition/"><u>Professional Photography Essentials: Discover the Leading Tripods on the Market - 2023 Edition</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-hand-tracking-reference-guide-for-2024/"><u>The Ultimate Hand-Tracking Reference Guide for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-21-gratis-ip-camera-software-di-settembre-2024-revisione-comparativa-con-movavi/"><u>Top 21 Gratis IP Camera Software Di Settembre 2024 - Revisione Comparativa Con Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transforma-tus-dvd-en-mp4-con-estos-5-mejores-programas-soluciones-tanto-para-computadoras-como-online-recomendadas-por-movavi/"><u>Transforma Tus DVD en MP4 Con Estos 5 Mejores Programas: Soluciones Tanto Para Computadoras Como Online Recomendadas Por Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/flv-3gp-movavi/"><u>권장: 웹 페이지에서 자연스럽고 무료로 FLV, 3GP 형식 전환 - Movavi</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

