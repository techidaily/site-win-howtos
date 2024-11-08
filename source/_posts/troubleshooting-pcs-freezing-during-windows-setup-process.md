---
title: Troubleshooting PCs Freezing During Windows Setup Process
date: 2024-11-01T18:54:52.672Z
updated: 2024-11-08T06:37:01.586Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting PCs Freezing During Windows Setup Process
excerpt: This Article Describes Troubleshooting PCs Freezing During Windows Setup Process
thumbnail: https://thmb.techidaily.com/128936f1237a7dae7d947e202ae29738fcba18f1e1925b63e660146e08554eaf.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  

## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  

3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135352/19272" target="_top" id="2135352">
  <img src="//a.impactradius-go.com/display-ad/19272-2135352" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135352/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://facebook-record-videos.techidaily.com/new-the-beginners-blueprint-for-youtube-trailers-via-filmora/"><u>[New] The Beginner's Blueprint for YouTube Trailers via Filmora</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-visual-ventures-free-themes-to-elevate-your-channel/"><u>[Updated] In 2024, Visual Ventures FREE Themes to Elevate Your Channel</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagrams-edge-the-best-practices-for-video-creation/"><u>[Updated] Instagram's Edge The Best Practices for Video Creation</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-smartest-podcast-renaming-options-through-ai-technology/"><u>[Updated] The Smartest Podcast Renaming Options Through AI Technology</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ape-aac-movavi/"><u>APE 파일을 AAC로 구독하기: 원거리 무료 솔루션 - Movavi</u></a></li>
<li><a href="https://os-tips.techidaily.com/experience-your-favorite-psp-titles-anywhere-using-ppsspp-for-ios-devices/"><u>Experience Your Favorite PSP Titles Anywhere Using PPSSPP for iOS Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-exhaustif-pour-convertir-un-fichier-m4v-en-formats-mp4-et-m4v/"><u>Guide Exhaustif Pour Convertir Un Fichier M4V en Formats MP4 Et M4V</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-expert-comment-realiser-et-partager-votre-premier-montage-video-en-quelques-etapes-simples/"><u>Guide Expert: Comment Réaliser Et Partager Votre Premier Montage Vidéo en Quelques Étapes Simples</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-poco-c51-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Poco C51 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-elevate-your-influence-mastering-instagram-engagement/"><u>In 2024, Elevate Your Influence Mastering Instagram Engagement</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-my-xiaomi-redmi-12-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix My Xiaomi Redmi 12 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/leading-video-editing-tools-for-professionals-optimized-for-windows-11-8-and-7-systems/"><u>Leading Video Editing Tools for Professionals: Optimized for Windows 11, 8, and 7 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/metodo-simple-y-sin-coste-para-transformar-vob-en-mp4-digitalmente-solucion-optimizada-por-movavi/"><u>Método Simple Y Sin Coste Para Transformar VOB en MP4 Digitalmente – Solución Optimizada Por Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/online-livre-transforme-arquivos-raw-para-png-gratuitamente-usando-a-ferramenta-do-movavi/"><u>Online Livre: Transforme Arquivos RAW Para PNG Gratuitamente Usando a Ferramenta Do Movavi</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203241341-trouble-with-your-wireless-mouse-on-windows-heres-how-to-fix-it-in-w11w10/"><u>Trouble with Your Wireless Mouse on Windows? Here's How to Fix It in W11/W10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/m4vwebm-obs-streamyard/"><u>무료 온라인 M4V/WEBM 이미지를 OBS에서 바인딩하기 - StreamYard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/flvm4a-online/"><u>원탁 무료 FLV/M4A 변환기: ONLINE 모바이비 소스로!</u></a></li>
</ul></div>

