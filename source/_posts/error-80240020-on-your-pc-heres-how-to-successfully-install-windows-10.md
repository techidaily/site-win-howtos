---
title: Error 80240020 on Your PC? Here's How to Successfully Install Windows 10
date: 2024-09-20T00:13:13.190Z
updated: 2024-09-22T22:01:42.932Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Error 80240020 on Your PC? Here's How to Successfully Install Windows 10
excerpt: This Article Describes Error 80240020 on Your PC? Here's How to Successfully Install Windows 10
thumbnail: https://thmb.techidaily.com/1501cba3c5f4c4b803b623584f546bd1f9723b8ea081222f679c45ec271effc3.jpg
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
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-capture-games-effortlessly-with-nvidia/"><u>[Updated] 2024 Approved Capture Games Effortlessly with NVIDIA</u></a></li>
<li><a href="https://win-howtos.techidaily.com/converta-seus-arquivos-wmv-sem-custo-com-o-moveavi-convertidor-gratuito/"><u>Converta Seus Arquivos WMV Sem Custo Com O Moveavi Convertidor Gratuito!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/descargar-y-convertir-videos-mov-a-formato-mp4-gratuitamente-con-online-movie-converter/"><u>Descargar Y Convertir Videos MOV a Formato MP4 Gratuitamente Con Online Movie Converter</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-video-downloading-techniques-using-movavi-across-all-sites/"><u>Easy Video Downloading Techniques Using Movavi Across All Sites</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhancing-meditation-with-chatgpt-suggestions/"><u>Enhancing Meditation With ChatGPT Suggestions</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-tecno-camon-20-pro-5g-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratis-online-converter-alterne-mkv-e-3gp-para-mp4-com-o-programa-de-conversao-do-movavi/"><u>Gratis Online Converter: Alterne MKV E 3GP Para MP4 Com O Programa De Conversão Do Movavi</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-ultimate-list-for-capturing-instagram-vids-pcmac/"><u>In 2024, The Ultimate List for Capturing Instagram Vids (PC/Mac)</u></a></li>
<li><a href="https://fox-info.techidaily.com/mastering-multi-image-compositions-photo-montages-guide-for-2024/"><u>Mastering Multi-Image Compositions Photo Montages Guide for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/quick-guide-transforming-ts-files-into-premium-mp4-format/"><u>Quick Guide: Transforming TS Files Into Premium MP4 Format</u></a></li>
<li><a href="https://win-howtos.techidaily.com/scaricabile-conversione-pcx-a-gif-livello-di-prova-movavi/"><u>Scaricabile Conversione PcX a Gif Livello Di Prova - Movavi</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-premier-list-of-free-online-venues-for-live-sports-action/"><u>The Premier List of Free Online Venues for Live Sports Action</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transforma-tus-videos-flv-en-formatos-compatibles-sin-coste-con-movavis-herramienta-de-cambio-gratuito-online/"><u>Transforma Tus Videos FLV en Formatos Compatibles Sin Coste Con Movavi's Herramienta De Cambio Gratuito Online</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Samsung Galaxy A05? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mpeg-jpeg-movavi/"><u>자이프트라 내부에서 MPEG 및 JPEG 파일을 제공적으로 바꾸는 방법 - Movavi 가이드</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

