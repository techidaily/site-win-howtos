---
title: Untangling the Mystery of High CPU Load by MsMpEng on Windows 11 [ISSUE SOLVED]
date: 2024-09-12T20:36:53.703Z
updated: 2024-09-17T19:24:57.020Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Untangling the Mystery of High CPU Load by MsMpEng on Windows 11 [ISSUE SOLVED]
excerpt: This Article Describes Untangling the Mystery of High CPU Load by MsMpEng on Windows 11 [ISSUE SOLVED]
thumbnail: https://thmb.techidaily.com/a81739d88952571f4be878bb2d8fbe2fb1485b177c9a393df6daef2f5895f8cc.png
---

## Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved

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
<a href="https://aligracehair.sjv.io/c/5597632/1896505/19272" target="_top" id="1896505">
  <img src="//a.impactradius-go.com/display-ad/19272-1896505" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896505/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148774/18498" target="_top" id="2148774">
  <img src="//a.impactradius-go.com/display-ad/18498-2148774" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148774/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://vimeo-videos.techidaily.com/new-soundscapes-for-vimeo-a-compreayers-manual-for-2024/"><u>[New] Soundscapes for Vimeo A Compreayer's Manual for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-google-photos-video-uploading-made-simple-discover-the-ultimate-guide/"><u>Effortless Google Photos Video Uploading Made Simple: Discover the Ultimate Guide!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/free-guide-perfect-steps-to-convert-and-import-mov-files-into-windows-movie-maker/"><u>Free Guide: Perfect Steps to Convert & Import MOV Files Into Windows Movie Maker</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-transforming-your-openoffice-impress-odp-presentations-into-watchable-videos/"><u>Guide: Transforming Your OpenOffice Impress (.odp) Presentations Into Watchable Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-easily-batch-convert-flac-files-to-wav-audio-format-on-your-pc/"><u>How to Easily Batch Convert FLAC Files to WAV Audio Format on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-effortlessly-extract-sound-from-video-captures-a-quick-3-step-guide/"><u>How to Effortlessly Extract Sound From Video Captures: A Quick 3-Step Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-tecno-spark-10-4g-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Tecno Spark 10 4G</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-the-smart-way-to-store-video-meetings-on-devices/"><u>In 2024, The Smart Way to Store Video Meetings on Devices</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/oneplus-6t-assessment-exceptional-features-meet-fantastic-pricing/"><u>OnePlus 6T Assessment: Exceptional Features Meet Fantastic Pricing</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-motorola-moto-g14-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Motorola Moto G14 and Browser | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-a1x-5g-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on A1x 5G without backup.</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-steps-why-your-iphoneipad-cant-connect-to-wi-fi-and-how-to-solve-it/"><u>Troubleshooting Steps: Why Your iPhone/iPad Can't Connect to Wi-Fi & How to Solve It</u></a></li>
<li><a href="https://fox-glue.techidaily.com/unleash-creativity-in-windows-10-how-to-trim-movies-and-more-for-2024/"><u>Unleash Creativity in Windows 10 How To Trim Movies and More for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hdfactory/"><u>フリーHDビデオコンバータFactory 成功設定完了！</u></a></li>
</ul></div>

