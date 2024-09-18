---
title: "Make Your Taskbar Stay: Winning the Battle Against Hiding on Windows 10"
date: 2024-09-16T22:01:26.661Z
updated: 2024-09-17T18:37:15.195Z
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
<a href="https://appsumo.8odi.net/c/5597632/2144308/7443" target="_top" id="2144308">
  <img src="//a.impactradius-go.com/display-ad/7443-2144308" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144308/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-ten-simple-steps-to-acquire-igtv-media/"><u>[New] 2024 Approved Ten Simple Steps to Acquire IGTV Media</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-engaging-audiences-with-smart-instavideo-marketing-tactics/"><u>[New] In 2024, Engaging Audiences with Smart InstaVideo Marketing Tactics</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-top-10-screen-free-android-apps-for-leisurely-gaming/"><u>[New] In 2024, Top 10 Screen-Free Android Apps for Leisurely Gaming</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-scholarly-screening-top-10-educational-equipment-to-preserve-lectures/"><u>[Updated] 2024 Approved Scholarly Screening Top 10 Educational Equipment to Preserve Lectures</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-stepwise-insta-story-image-integration-techniques-for-maximum-impact/"><u>[Updated] In 2024, Stepwise Insta Story Image Integration Techniques for Maximum Impact</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-optimizing-profits-on-youtube-studio-for-all-device-users-for-2024/"><u>[Updated] Optimizing Profits on YouTube Studio for All-Device Users for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clearing-the-microphone-hurdle-in-discord/"><u>Clearing the Microphone Hurdle in Discord</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-solution-for-an-unresponsive-usb-connection-in-your-hp-notebook/"><u>DIY Solution for an Unresponsive USB Connection in Your HP Notebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eliminating-erratic-scrolling-in-file-explorer-on-windows-10-a-comprehensive-guide/"><u>Eliminating Erratic Scrolling in File Explorer on Windows 10 - A Comprehensive Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-guide-on-how-to-remove-apple-id-from-apple-iphone-6s-plus-by-drfone-ios/"><u>In 2024, Guide on How To Remove Apple ID From Apple iPhone 6s Plus</u></a></li>
<li><a href="https://facebook.techidaily.com/platform-panic-fb-whatsapp-instagram-offline-today/"><u>Platform Panic: FB, WhatsApp, Instagram Offline Today</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/secrets-to-dynamic-and-effective-igtv-covers/"><u>Secrets to Dynamic & Effective IGTV Covers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-struggle-to-upgrade-navigating-troubled-waters-with-windows-10-version-1607s-failed-deployment/"><u>The Struggle to Upgrade: Navigating Troubled Waters with Windows 10 Version 1607'S Failed Deployment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-stop-the-continuous-reboot-cycle-on-windows-11/"><u>Ultimate Guide: Stop the Continuous Reboot Cycle on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-fix-corrupted-files-using-sfc-and-dism-utilities/"><u>Windows 11: Fix Corrupted Files Using SFC and DISM Utilities</u></a></li>
</ul></div>

