---
title: Solutions for Resolving Windows Setup Hanging Issues on Your Laptop or Desktop
date: 2024-10-10T19:14:50.722Z
updated: 2024-10-16T00:25:11.797Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solutions for Resolving Windows Setup Hanging Issues on Your Laptop or Desktop
excerpt: This Article Describes Solutions for Resolving Windows Setup Hanging Issues on Your Laptop or Desktop
thumbnail: https://thmb.techidaily.com/749c8b13fba53b16e3cca7c517e32ea283379a232e31a28dc3a9b19edc9409b3.jpg
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-from-chords-to-clicks-mastering-music-on-ig-for-2024/"><u>[New] From Chords to Clicks Mastering Music on IG for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/approach-compare-symptoms-of-high-versus-low-wrist-ulnar-nerve-injuries/"><u>Approach: Compare Symptoms of High versus Low (Wrist) Ulnar Nerve Injuries.</u></a></li>
<li><a href="https://discover-great.techidaily.com/come-riparare-uno-schermo-touch-iphone-disfunzionale-post-aggiornamento-ai-sistemi-operativi-ios-15ios-16/"><u>Come Riparare Uno Schermo Touch iPhone Disfunzionale Post-Aggiornamento Ai Sistemi Operativi iOS 15/iOS 16</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conversion-de-archivos-libremente-en-linea-mp2mp3-a-mp4-mediante-movavi/"><u>Conversión De Archivos Libremente en Línea - MP2/MP3 a MP4 Mediante Movavi</u></a></li>
<li><a href="https://win-solutions.techidaily.com/easy-steps-to-troubleshoot-kernelbasedll-abrupt-shutdown-problems/"><u>Easy Steps to Troubleshoot KernelBase.dll Abrupt Shutdown Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratuit-konverteren-van-3gpp-naar-avi-formaat-mobavvi-online/"><u>Gratuit Konverteren Van 3GPP Naar AVI-Formaat - Mobavvi Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratuitamente-converterte-video-flv-para-web-con-movavi-descubre-tu-solucion/"><u>Gratuitamente Converterte Video FLV Para Web Con Movavi - ¡Descubre Tu Solución!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-apply-vignetting-techniques-for-enhanced-photography/"><u>How To Apply Vignetting Techniques For Enhanced Photography</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-the-soft-bricked-vivo-y200-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Vivo Y200? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-5-solutions-for-tecno-pova-5-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Tecno Pova 5 Unlock Without Password</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-honor-magic5-ultimate-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Honor Magic5 Ultimate to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/online-aiffwav-wmvmp3-converter-free-and-easy-upgrades-with-movavi/"><u>Online AIFF/WAV 투 WMV/MP3 Converter - Free & Easy Upgrades with Movavi</u></a></li>
<li><a href="https://program-issues.techidaily.com/step-by-step-instructions-to-get-your-minecraft-up-and-running-again/"><u>Step-by-Step Instructions to Get Your Minecraft Up and Running Again</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

