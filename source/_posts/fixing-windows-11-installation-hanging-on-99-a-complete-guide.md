---
title: Fixing Windows 11 Installation Hanging on 99%% - A Complete Guide
date: 2024-10-01T01:10:24.940Z
updated: 2024-10-04T15:41:46.298Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing Windows 11 Installation Hanging on 99%% - A Complete Guide
excerpt: This Article Describes Fixing Windows 11 Installation Hanging on 99%% - A Complete Guide
thumbnail: https://thmb.techidaily.com/0c878b30db98d758dc708e36a3a1a79c906ed9e88e0726b5c47115417927372d.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-a-detailed-exploration-youtubes-visionary-suite/"><u>[New] In 2024, A Detailed Exploration YouTube's Visionary Suite</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-picsart-secret-conceal-faces-easily/"><u>[New] Picsart Secret Conceal Faces Easily</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-comprehensive-guide-to-free-cloud-communication-software-for-2024/"><u>[Updated] Comprehensive Guide to Free Cloud Communication Software for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-keeping-up-with-the-screen-capturing-internet-television-online/"><u>[Updated] In 2024, Keeping Up With The Screen - Capturing Internet Television Online</u></a></li>
<li><a href="https://win-answers.techidaily.com/2024windows-108/"><u>2024年にリリースされたWindows 10向けのおすすめフリーで簡単な画面録画ツールトップ8選 -</u></a></li>
<li><a href="https://win-howtos.techidaily.com/2024-top-8/"><u>2024에 대한 Top 8 인공 지능 음성 매개된 언어 교정 소품화</u></a></li>
<li><a href="https://fox-direct.techidaily.com/8-best-free-websites-for-3d-text-psd-files-for-2024/"><u>8 Best Free Websites for 3D Text PSD Files for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/enhancing-your-macos-connectivity-by-configuring-various-network-places-expert-advice/"><u>Enhancing Your macOS Connectivity by Configuring Various Network Places | Expert Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movswfmov-movavi/"><u>MOV到SWF自由转换：简单的在线MOV文件转换工具-Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transforma-tus-audios-m4b-y-m4a-en-video-m4v-sin-coste-guia-detallada-con-el-utilizador-on-line-de-movavi/"><u>Transforma Tus Audios M4B Y M4A en Vídeo M4V Sin Coste: Guía Detallada Con El Utilizador On-Line De Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transformacion-sin-costo-de-wmv-al-formato-asf-utilizando-movavi-online/"><u>Transformación Sin Costo De WMV Al Formato ASF Utilizando Movavi Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/verknopt-harmonieuze-liedjes-vergelst-met-de-movavi-mp3-linkmaker/"><u>Verknopt Harmonieuze Liedjes Vergelst Met De Movavi MP3-Linkmaker</u></a></li>
<li><a href="https://win-howtos.techidaily.com/3gpp-3gp-movavi/"><u>무료 원조 - 3GPP 3GP 되착포를 위한 Movavi의 가상 서비스</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135358/19272" target="_top" id="2135358">
  <img src="//a.impactradius-go.com/display-ad/19272-2135358" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135358/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

