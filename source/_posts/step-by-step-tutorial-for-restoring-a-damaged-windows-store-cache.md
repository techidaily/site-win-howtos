---
title: Step-by-Step Tutorial for Restoring a Damaged Windows Store Cache
date: 2024-09-29T02:36:59.058Z
updated: 2024-10-03T18:33:11.146Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Tutorial for Restoring a Damaged Windows Store Cache
excerpt: This Article Describes Step-by-Step Tutorial for Restoring a Damaged Windows Store Cache
thumbnail: https://thmb.techidaily.com/9bd169ce317850079833c4c232eaa6d389f824b0ea7ef26122a9f26ae8562eda.jpg
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
<li><a href="https://some-knowledge.techidaily.com/new-from-flat-to-360-comparing-googles-cardboard-and-samsungs-gear/"><u>[New] From Flat to 360 Comparing Google's Cardboard & Samsung's Gear</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-picture-perfection-apply-filters-to-your-videos/"><u>[Updated] Picture Perfection Apply Filters to Your Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mpegflv-movavi/"><u>立即在線無限MPEG到FLV的自由變更 - Movavi影片轉換器</u></a></li>
<li><a href="https://win-howtos.techidaily.com/m4am4r-movavi/"><u>全自動オンラインで優雅にM4A・M4Rフォーマット音楽変換 - 完全無料 Movaviサービス</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movavi-pgm-jpeg/"><u>移動畫中心：用 Movavi 自由下載 - PGM到 JPEG 無限制轉換</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/breaking-down-claude-2-features-unveiled/"><u>Breaking Down Claude 2: Features Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/como-convertir-archivos-3gp-a-formatos-de-audio-wav-sin-coste-con-conversor-online-movavi/"><u>Cómo Convertir Archivos .3GP a Formatos De Audio WAV Sin Coste Con Conversor Online - Movavi</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/decoding-the-future-how-forefront-ai-stacks-up-against-chatgpt/"><u>Decoding the Future: How Forefront AI Stacks Up Against ChatGPT</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-vivo-y36-lock-screen-password-by-drfone-android/"><u>How to Reset your Vivo Y36 Lock Screen Password</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-the-gif-to-sticker-methodology-how-to-express-yourself-better-on-discord/"><u>In 2024, The GIF-to-Sticker Methodology How to Express Yourself Better on Discord</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528685/16446" target="_top" id="1528685">
  <img src="//a.impactradius-go.com/display-ad/16446-1528685" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528685/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

