---
title: "Step-by-Step Solution for Fixing Windows 10'S Update Error: 0Xc1900208"
date: 2024-09-20T16:45:50.909Z
updated: 2024-09-22T20:37:54.374Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Solution for Fixing Windows 10'S Update Error: 0Xc1900208"
excerpt: "This Article Describes Step-by-Step Solution for Fixing Windows 10'S Update Error: 0Xc1900208"
thumbnail: https://thmb.techidaily.com/5164fa265fad5df086cc8d529b2f3b17fbfd4164208e747d807661e727a6e5b2.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-enhancing-viewer-interest-with-thumbnails/"><u>[New] 2024 Approved Enhancing Viewer Interest with Thumbnails</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-global-leaders-in-digital-education-beyond-udemy/"><u>[New] Global Leaders in Digital Education Beyond Udemy</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-virtual-tournament-gear-showcase-series/"><u>[Updated] 2024 Approved Virtual Tournament Gear Showcase Series</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-iconic-after-effects-techniques-for-impressive-titles/"><u>2024 Approved Iconic After Effects Techniques for Impressive Titles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comparing-editors-windows-movie-maker-vs-movavi-video-suite/"><u>Comparing Editors: Windows Movie Maker Vs. Movavi Video Suite</u></a></li>
<li><a href="https://win-howtos.techidaily.com/convertissez-facilement-un-audio-mp3-en-video-swf-gratuite-avec-movavi-en-ligne/"><u>Convertissez Facilement Un Audio MP3 en Vidéo SWF Gratuite Avec Movavi en Ligne</u></a></li>
<li><a href="https://win-howtos.techidaily.com/forst-oversvangas-inspellningarna-i-snapchat-enkeltvis-du-far-skara-dig-eget/"><u>Först Översvängas Inspellningarna I Snapchat? Enkeltvis Du Får Skära Dig Eget!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/free-online-tool-transforming-wma-files-into-3gp-format-with-ease/"><u>Free Online Tool: Transforming WMA Files Into 3GP Format with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratis-scannen-van-cr2-biljetten-in-digitale-beeldvorming-omzetten-en-opslaan-via-movavi/"><u>Gratis Scannen Van CR2-Biljetten in Digitale Beeldvorming - Omzetten en Opslaan via Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gratuit-online-konverteren-van-mpe-naar-gif-veilig-en-efficient-met-movavi/"><u>Gratuit Online Konverteren Van MPE Naar GIF - Veilig en Efficiënt Met Movavi</u></a></li>
<li><a href="https://extra-information.techidaily.com/how-to-captivate-audiences-in-youtube-live-with-tiny-subscriber-counts/"><u>How to Captivate Audiences in YouTube Live with Tiny Subscriber Counts</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-smart-7-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Smart 7 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-realme-narzo-n55-drfone-by-drfone-virtual-android/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Realme Narzo N55 | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionize-your-business-with-these-essential-five-ai-tools/"><u>Revolutionize Your Business With These Essential Five AI Tools</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

