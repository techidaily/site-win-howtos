---
title: Resolving Slow Typing Response Time for Windows 10 Users
date: 2024-09-16T17:06:00.335Z
updated: 2024-09-22T17:58:34.583Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Slow Typing Response Time for Windows 10 Users
excerpt: This Article Describes Resolving Slow Typing Response Time for Windows 10 Users
thumbnail: https://thmb.techidaily.com/77bfb2c7f1c1fe0360a8a12d5582bbafa6a377d533d7c690d2e56cf6d1507405.jpg
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
<li><a href="https://some-approaches.techidaily.com/new-unveiling-the-wonders-mastering-firefox-x-pie-mode/"><u>[New] Unveiling the Wonders Mastering Firefox X-Pie Mode</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-handling-haters-strategies-for-content-creators/"><u>[Updated] Handling Haters Strategies for Content Creators</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-master-your-audience-smooth-screen-sharing-on-social-livestreams/"><u>[Updated] Master Your Audience Smooth Screen Sharing on Social Livestreams</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-top-editors-for-virtual-backgrounds-spectrumswitch-studio-for-2024/"><u>[Updated] Top Editors for Virtual Backgrounds SpectrumSwitch Studio for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/converti-i-tuoi-file-avi-in-mp3-senza-costi-guida-di-conversione-online-gratuita-con-movavi/"><u>Converti I Tuoi File AVI in MP3 Senza Costi: Guida Di Conversione Online Gratuita Con Movavi</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-or-update-nvidias-mx150-graphics-drivers-for-windows-systems/"><u>Install or Update NVIDIA's MX150 Graphics Drivers for Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-11-best-hd-display-screen-capture-tools-of-2024-updated-list-by-movavi/"><u>Top 11 Best HD Display Screen Capture Tools of 2024 - Updated List by Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transcodificar-archivos-de-video-de-formato-avi-al-formato-wav-sin-coste-guia-simple/"><u>Transcodificar Archivos De Vídeo De Formato AVI Al Formato WAV Sin Coste: Guía Simple</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

