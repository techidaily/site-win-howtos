---
title: Solution Steps for the 'vcruntime140.dll Could Not Be Located' Error Message
date: 2024-10-02T12:26:47.327Z
updated: 2024-10-04T03:14:27.278Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solution Steps for the 'vcruntime140.dll Could Not Be Located' Error Message
excerpt: This Article Describes Solution Steps for the 'vcruntime140.dll Could Not Be Located' Error Message
thumbnail: https://thmb.techidaily.com/ad7d05b0030775951042fde08b0fbde9a0ebb4cf05f0435bf5618af5d7b42ae3.jpg
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
<li><a href="https://youtube-web.techidaily.com/mplifying-impact-youtube-visibility-techniques-for-2024/"><u>[New] Amplifying Impact YouTube Visibility Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-elevate-your-digital-footprint-with-effective-fb-page-management/"><u>[New] In 2024, Elevate Your Digital Footprint with Effective FB Page Management</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-ultimate-guide-to-indoor-android-games-no-internet-required-for-2024/"><u>[Updated] The Ultimate Guide to Indoor Android Games (No Internet Required) for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gifmp4-movavi/"><u>免費在線變更GIF到MP4 - 利用 Movavi 工具進行轉換</u></a></li>
<li><a href="https://win-howtos.techidaily.com/vob3gpmovavi/"><u>直接在線上免費移動VOB到3GP：簡便的Movavi視頻轉換方法</u></a></li>
<li><a href="https://win-howtos.techidaily.com/aiff-bestandsen-omzetten-intoe-gratis-vaardigheden-verkregen-door-movavi/"><u>AIFF-Bestandsen Omzetten Intoe: Gratis, Vaardigheden Verkregen Door Movavi</u></a></li>
<li><a href="https://extra-hints.techidaily.com/clear-image-purchases-no-more-watermarks-for-2024/"><u>Clear Image Purchases No More Watermarks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-high-dpi-displays-a-windows-guide/"><u>Dealing with High DPI Displays: A Windows Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratis-instant-converting-from-flac-to-wav-formats-via-movavi-onlinelogik/"><u>Gratis Instant Converting From FLAC to WAV Formats via Movavi - Onlinelogik</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guia-completa-para-conversion-de-video-mpg-a-m4v-sin-gastos-mediante-la-herramienta-en-linea-de-movavi/"><u>Guía Completa Para Conversión De Video MPG a M4V Sin Gastos Mediante La Herramienta en Línea De Movavi</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-windows-playback-system-for-2024/"><u>Ultimate Windows Playback System for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-efficiency-crafted-keybinds-for-snippet-pasting-in-windows-11/"><u>Unleashing Efficiency: Crafted Keybinds for Snippet Pasting in Windows 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948895/19272" target="_top" id="1948895">
  <img src="//a.impactradius-go.com/display-ad/19272-1948895" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948895/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

