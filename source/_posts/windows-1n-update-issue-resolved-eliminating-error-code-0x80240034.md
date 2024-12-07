---
title: "Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
date: 2024-12-03T16:37:49.122Z
updated: 2024-12-07T16:00:05.738Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
excerpt: "This Article Describes Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
thumbnail: https://thmb.techidaily.com/d44c84cbf0699642eded061365e62aa884811112a5aa8ff88c8335f623b0d0e8.jpg
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
<li><a href="https://youtube-docs.techidaily.com/rafting-captivating-cinematic-experiences-in-youtube-videos/"><u>[New] Crafting Captivating Cinematic Experiences in YouTube Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ideo-success-stories-maximizing-income-with-youtube-adsense/"><u>[New] Video Success Stories Maximizing Income with YouTube AdSense</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-mastering-motion-clearer-captures/"><u>[Updated] 2024 Approved Mastering Motion Clearer Captures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/webmwav/"><u>網站直接WEBM到WAV自由轉化 - 動靠轉換器</u></a></li>
<li><a href="https://win-howtos.techidaily.com/convert-wmv-file-in-m4a-format-free-online-converter-by-movavi/"><u>Convert WMV File in M4A Format Free - Online Converter by Movavi</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/ghoul-gags-generator-for-2024/"><u>Ghoul Gags Generator for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/online-avi-movavi/"><u>Online 무료 원형/AVI 텍스트 이미지 전환 - MOVAVI</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transformar-gratuitamente-imagenes-bmp-a-linea-con-convertidor-de-archivos-de-movavi/"><u>Transformar Gratuitamente Imágenes BMP a Línea Con Convertidor De Archivos De Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transforme-seus-arquivos-m4b-em-mp3-gratuitamente-com-o-online-convert-mp3movavi/"><u>Transforme Seus Arquivos M4B Em MP3 Gratuitamente Com O OnLine Convert MP3/Movavi!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/ultimate-plan-for-livestream-and-document-sports-contests/"><u>Ultimate Plan for Livestream & Document Sports Contests</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-lava-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Lava Phones</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

