---
title: "Make Your Taskbar Stay: Winning the Battle Against Hiding on Windows 10"
date: 2024-09-19T00:00:52.661Z
updated: 2024-09-22T18:16:43.792Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Make Your Taskbar Stay: Winning the Battle Against Hiding on Windows 10"
excerpt: "This Article Describes Make Your Taskbar Stay: Winning the Battle Against Hiding on Windows 10"
thumbnail: https://thmb.techidaily.com/606acaddc3ba9faf4d73376f1e2c554744034ba5ad463dfb82faf3689dc358c1.jpg
---

## Winning the Battle Against MsMpEng.exe: Reducing CPU Usage in Windows 11 – Effective Strategies Inside

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948932/19272" target="_top" id="1948932">
  <img src="//a.impactradius-go.com/display-ad/19272-1948932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

## Want us to fix the problem for you?

 If the fix above didn’t work, and you don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

 That’s it – top 3 fixes for your **MsMpEng.exe-eating-up-too-much-CPU-in-Windows 10** problem. Hope this helps and feel free to comment below if you have any further questions. 🙂

* [high CPU](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-digital-influencers-riches-exceed-ages-kaji-ryan-story/"><u>[New] 2024 Approved Digital Influencer's Riches Exceed Ages Kaji Ryan Story</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-crafting-cinema-magic-with-fcps-top-10-plugin-choices/"><u>[New] Crafting Cinema Magic with FCP’s Top 10 Plugin Choices</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-crafting-instagram-reels-like-professionals-top-10-tools/"><u>[New] Crafting Instagram Reels Like Professionals - Top 10 Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tiny-film-plot-proposal/"><u>[New] Tiny Film Plot Proposal</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-augmenting-visual-appeal-implementing-black-bar-and-box-on-fb/"><u>[Updated] Augmenting Visual Appeal Implementing Black Bar & Box on FB</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726223732738-f4vflv-movavi/"><u>無料で高速F4VおよびFLV動画形式の安全なオンライン変換 - Movavi 利用方法ガイド</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comment-movavi-gere-t-il-les-achats-et-les-restitutions-decouvrez-nos-politiques-efficaces-pour-une-meilleure-experience-client/"><u>Comment Movavi Gère-T-Il Les Achats Et Les Restitutions ? Découvrez Nos Politiques Efficaces Pour Une Meilleure Expérience Client</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conversion-libre-en-ligne-convertissez-votre-fichier-qt-en-mp3-a-laide-de-la-solution-movavi/"><u>Conversion Libre en Ligne : Convertissez Votre Fichier QT en MP3 À L'aide De La Solution Movavi</u></a></li>
<li><a href="https://article-posts.techidaily.com/deciphering-the-art-of-cd-ripping-via-windows-media-player/"><u>Deciphering the Art of Cd Ripping via Windows Media Player</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/how-to-record-teams-video-meeting-in-2024/"><u>How to Record Teams Video Meeting, In 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-guide-extracting-vob-files-from-various-dvd-formats/"><u>Step-by-Step Guide: Extracting VOB Files From Various DVD Formats</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trasforma-i-tuoi-audiolibri-m4a-in-mp3m4b-via-web-scopri-il-metodo-di-conversione-libero/"><u>Trasforma I Tuoi Audiolibri M4A in MP3/M4B Via Web: Scopri Il Metodo Di Conversione Libero!</u></a></li>
</ul></div>

