---
title: Diagnosing and Repairing Unresponsive USB Connections on Windows 11 Systems
date: 2024-09-21T20:36:38.878Z
updated: 2024-09-22T21:29:22.594Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Repairing Unresponsive USB Connections on Windows 11 Systems
excerpt: This Article Describes Diagnosing and Repairing Unresponsive USB Connections on Windows 11 Systems
thumbnail: https://thmb.techidaily.com/1b2195440e349b5f0884d1401c71f047053f6f52811a1360983fce9511380f91.jpg
---

## Fixing Missing Desktop Icons on Windows 11 - Complete Solution

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf526e8ebcab-1024x552.jpg)

If your desktop icons somehow disappear on your Windows 10 computer, don’t worry, you can try the tips below to fix the issue. Quickly and easily.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these tips

You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Enable Show desktop icons**](#t1)
2. [**Check your desktop icon settings**](#t2)
3. [**Rebuild icon cache**](#t4)
4. [**Perform a system restore**](#t5)
5. [**Reset your computer**](#t6)
6. [**Bonus tip**](#t7)

### Tip 1: Enable Show desktop icons

Make sure you have enabled the “Show desktop icon” feature on Windows 10:

1. Right-click your desktop, click **View**, and check **Show desktop icons**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf52ca259fe4.jpg)
2. Check to see if your desktop icons are back. If not, try Tip 2, below.

---

### Tip 2: Check your desktop icon settings

1. Right-click your desktop and click **Personalize**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf531bcea206.jpg)
2. Click **Themes** \> **Desktop icon settings**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53220a4552.jpg)
3. Select the icons you want to show on desktop, then click **OK**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53279e9206.jpg)
4. Check if your “desktop icons missing” problem is resolved. If not, try Tip 3, below.

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938693/19272" target="_top" id="1938693">
  <img src="//a.impactradius-go.com/display-ad/19272-1938693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938693/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Tip 3: Rebuild icon cache

You can also try these steps to rebuild the icon cache:

1. Run **Command Prompt** as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53d32cc341.jpg)
2. Copy-paste the following commands one at a time and press **Enter** after each command.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080312/19272" target="_top" id="2080312">
  <img src="//a.impactradius-go.com/display-ad/19272-2080312" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080312/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

taskkill /F /IM explorer.exe  
cd /d %userprofile%\AppData\Local  
attrib –h IconCache.db  
del IconCache.db  
start explorer.exe
3. Check if it helps restore your desktop icons. If not, try Tip 4, below.

---

### Tip 4: Perform a system restore

If your desktop icons still don’t show up, you can perform a system restore to return your system to a date when the icons appeared normally on the desktop. Here’s how to perform a system restore to help fix your “desktop icons disappeared in Windows 10” issue:

1. Type **recovery** in the Windows search box, then press **Enter**.
2. At Recovery, click **Open System Restore**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a2728a7e.jpg)
3. Select **Choose a different restore point**, and click **Next**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a34c35bc.jpg)
4. Check the box beside **Show more restore points**. You should see a list of ‘restore points’. These are like backups of your computer, as it was at that particular date and time. Think back to a date when your desktop icons showed up, and **select a restore point** from that date or slightly earlier (but no later).  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049382/7443" target="_top" id="2049382">
  <img src="//a.impactradius-go.com/display-ad/7443-2049382" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049382/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a4d84f3c.jpg)
5. Click **Next** \> **Finish**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Check to see if your desktop icons are now restored on Windows 10\. If not, try Tip 5, below.

---

### Tip 5: Reset your computer

If the steps above didn’t work for you. Resetting your computer is worth a try. It fixed the desktop icon issue for some users.

1. Click the **Start** button > the **Settings** icon.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b790f639.jpg)
2. Click **Update & security** \> **Recovery**.
3. In the **Reset this PC** area, click the **Get started** button. Then follow the on-screen instructions to reset your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b9dab56d.jpg)

---

### Bonus tip

A missing or outdated graphics driver may also stop items from appearing properly on PC. You should make sure your graphics card driver is up to date. There are two ways to update your graphics driver: **manually** and **automatically**.

**Update your graphics driver manually** — You can update your driver manually by going to the hardware manufacturer’s website, and searching for the latest driver for your graphics card. But if you take this approach, be sure to choose the driver that’s compatible with the exact model number of your hardware, and your version of Windows.

OR

**Update your graphics driver automatically** — If you don’t have the time, patience, or computer skills to update your driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.
2. Run Driver Easy and click **Scan Now**. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-Scan-Needed.jpg)
3. Click **Update** next to any flagged devices to automatically download the correct version of their drivers, then you can install them manually. Or click **Update All** to automatically download and install them all automatically. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All. You get full support and a 30-day money-back guarantee.)  
![](https://www.drivereasy.com/wp-content/uploads/2022/02/de-update-all-rtx-3080.jpg)  
If you need assistance, please contact Driver Easy’s support team at **<support@drivereasy.com>**.

---

Hopefully, this can help you out.

If you have any other suggestions, please feel free to leave a comment below.

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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-uniform-visual-clarity-in-microsoft-teams-conferences/"><u>[New] 2024 Approved Uniform Visual Clarity in Microsoft Teams Conferences</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-advanced-photographic-distortion-tactics/"><u>[New] Advanced Photographic Distortion Tactics</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-crafting-a-viral-phenomenon-on-igtv-with-savvy-hash-tags/"><u>[Updated] In 2024, Crafting a Viral Phenomenon on IGTV with Savvy Hash Tags</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-elevate-your-video-rankings-with-effective-seo-tactics/"><u>2024 Approved Elevate Your Video Rankings with Effective SEO Tactics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/2024-mlhmh-alfydyo-tkhnyvt-kyvr-idafya-mghn-bbsata/"><u>2024 מלחמה الفيديو: תכניות קישור إضافية - مغنى ببساطة</u></a></li>
<li><a href="https://win-howtos.techidaily.com/5ycl5lq65oof5acx5lplusd6k235qmf6io944ks5ykz44gi44gf5lplush6ac85ocn44gu44gc44kl44oe44or44ob44oh44oh44kj44ki44k944ov44oi44km44kn44kiic0g44og44o844o044kh44o04419/"><u>個人情報保護機能を備えた信頼性のあるマルチメディアソフトウェア - ムーヴァヴィ</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-installation-guide-canon-printer-mg2520-drivers-for-windows/"><u>Download and Installation Guide: Canon Printer MG2520 Drivers for Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgotten-the-voicemail-password-of-infinix-smart-8-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Infinix Smart 8? Try These Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/free-online-webm-to-mp3-file-converter-easy-download-with-movavi/"><u>Free Online WebM to MP3 File Converter - Easy Download with Movavi</u></a></li>
<li><a href="https://extra-tips.techidaily.com/hero-11-and-max-360-gopro-challenge-video-quality-faceoff/"><u>Hero 11 & Max 360 GoPro Challenge - Video Quality Faceoff</u></a></li>
<li><a href="https://win-dash.techidaily.com/logitech-t630-driver-update-compatible-versions-for-windows-users-windows-781am/"><u>Logitech T630 Driver Update: Compatible Versions for Windows Users (Windows 7/8/1Am)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/otimizacao-detalhada-do-windows-nova-versao-11-para-ampliar-sua-experiencia-de-jogo-tutoriais-e-truques-especializados/"><u>Otimização Detalhada Do Windows Nova Versão (11) Para Ampliar Sua Experiência De Jogo - Tutoriais E Truques Especializados</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transferer-facilement-des-videos-flv-a-un-fichier-aac-en-ligne-convertissez-avec-movavi-sans-frais/"><u>Transférer Facilement Des Vidéos FLV À Un Fichier AAC en Ligne - Convertissez Avec Movavi Sans Frais</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/unificazione-o-combinazione-di-piu-file-video-in-formato-mp4/"><u>Unificazione O Combinazione Di Più File Video in Formato MP4</u></a></li>
</ul></div>

