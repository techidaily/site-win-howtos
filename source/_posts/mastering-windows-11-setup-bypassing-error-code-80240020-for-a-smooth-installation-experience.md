---
title: "Mastering Windows 11 Setup: Bypassing Error Code 80240020 for a Smooth Installation Experience"
date: 2024-10-14T23:05:39.495Z
updated: 2024-10-16T06:29:46.561Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Mastering Windows 11 Setup: Bypassing Error Code 80240020 for a Smooth Installation Experience"
excerpt: "This Article Describes Mastering Windows 11 Setup: Bypassing Error Code 80240020 for a Smooth Installation Experience"
thumbnail: https://thmb.techidaily.com/2efc75770914ae3db1b269aa438526aea2b37f029f972da8e465d2fb4ae63f10.jpg
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
<li><a href="https://some-techniques.techidaily.com/new-ignite-your-design-prowess-top-14-text-animation-snapshots/"><u>[New] Ignite Your Design Prowess Top 14 Text Animation Snapshots</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tackling-texts-and-gifs-an-experts-meme-making-manual-for-9gag/"><u>[New] Tackling Texts and Gifs An Expert's Meme-Making Manual for 9GAG</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726222580563-wavaiff-movavi/"><u>無成本網路WAV到AIFF格式改造 - 利用Movavi進行音頻轉換</u></a></li>
<li><a href="https://tech-hub.techidaily.com/best-practices-for-maintaining-privacy-with-chatgpt-during-business-operations/"><u>Best Practices for Maintaining Privacy with ChatGPT During Business Operations</u></a></li>
<li><a href="https://vp-tips.techidaily.com/blu-ray-e-dvd-una-comparazione-dettagliata-per-fare-la-scelta-giusta/"><u>Blu-Ray E DVD: Una Comparazione Dettagliata per Fare La Scelta Giusta</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratuit-verbale-conversie-van-ogv-naar-gif-de-veilige-en-eenvoudige-movavi-solutiestool/"><u>Gratuit Verbale Conversie Van OGV Naar GIF: De Veilige en Eenvoudige Movavi Solutiestool</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratuito-conversao-de-video-online-mp4-para-m2ts-com-a-ferramenta-mais-ampla-do-mundo/"><u>Gratuito: Conversão De Vídeo Online - MP4 Para M2TS Com a Ferramenta Mais Ampla Do Mundo</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-bypass-apple-iphone-6-passcode-easily-video-inside-by-drfone-ios/"><u>How to Bypass Apple iPhone 6 Passcode Easily Video Inside</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-flash-dead-vivo-t2-5g-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Vivo T2 5G Safely | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-the-activation-lock-on-your-ipad-and-iphone-15-pro-max-without-apple-account-by-drfone-ios/"><u>How to Remove the Activation Lock On your iPad and iPhone 15 Pro Max without Apple Account</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oneplus-open-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from OnePlus Open to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-ultimate-10-plugins-to-enhance-fcp/"><u>In 2024, Ultimate 10 Plugins to Enhance FCP</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-zooms-best-alternatives-on-laptops-and-tablets/"><u>In 2024, Zoom's Best Alternatives on Laptops & Tablets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movavi-convertendo-de-graca-wmv-para-aac-on-line-sem-custo-algum/"><u>Movavi - Convertendo De Graça WMV Para AAC On-Line Sem Custo Algum!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movavis-free-audio-file-converter-effortless-switch-from-m4a-to-wav/"><u>Movavi's Free Audio File Converter – Effortless Switch From M4A to WAV</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mp4-file-transformation-from-3gpp-made-simple-and-free-discover-the-power-of-movavis-online-conversion-tool/"><u>MP4 File Transformation From 3GPP Made Simple and Free – Discover the Power of Movavi's Online Conversion Tool</u></a></li>
<li><a href="https://win-howtos.techidaily.com/online-konverteren-van-m4a-naar-wav-vrije-dienst-met-movavi-convertereer-nl/"><u>Online Konverteren Van M4A Naar WAV - Vrije Dienst Met Movavi Convertereer NL</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transformer-des-fichiers-mp4-en-videos-mpeg-sur-internet-de-gratuiciel-convertisseur-video-movavi/"><u>Transformer Des Fichiers MP4 en Vidéos MPEG Sur Internet De Gratuiciel - Convertisseur Vidéo Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trasforma-i-video-flv-in-mp4-liberamente-on-line-utilizzando-lestensione-di-movavi/"><u>Trasforma I Video FLV in MP4 Liberamente On-Line Utilizzando L'Estensione Di Movavi</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027176/19272" target="_top" id="2027176">
  <img src="//a.impactradius-go.com/display-ad/19272-2027176" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027176/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

