---
title: "[Fixed] Solving the Problem of Frequent Freezing When Starting Windows 10"
date: 2024-09-18T20:47:34.915Z
updated: 2024-09-22T19:53:03.005Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes [Fixed] Solving the Problem of Frequent Freezing When Starting Windows 10
excerpt: This Article Describes [Fixed] Solving the Problem of Frequent Freezing When Starting Windows 10
thumbnail: https://thmb.techidaily.com/d1114cdd62049ffd7653e7094748e36a17e96d6070583d2a1a451841876e1401.jpg
---

## Winning the Battle Against MsMpEng.exe: Resolve Its CPU Hogging on Windows 10

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

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938745/19272" target="_top" id="1938745">
  <img src="//a.impactradius-go.com/display-ad/19272-1938745" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938745/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111994/7443" target="_top" id="2111994">
  <img src="//a.impactradius-go.com/display-ad/7443-2111994" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111994/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/new-enhancing-online-presence-obs-and-facebook-synergy/"><u>[New] Enhancing Online Presence OBS & Facebook Synergy</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-engaging-in-the-moment-of-a-tiktok-life/"><u>[Updated] 2024 Approved Engaging in the Moment of a TikTok Life</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-premium-zero-cost-switch-gaming-experience/"><u>[Updated] 2024 Approved Premium Zero Cost Switch Gaming Experience</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-the-ultimate-mac-dvd-authorization-handbook/"><u>[Updated] The Ultimate Mac DVD Authorization Handbook</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-realities-of-youtube-view-calculation/"><u>2024 Approved The Realities of YouTube View Calculation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-to-resolving-issues-with-your-logitech-clips-digital-pen-on-xp/"><u>Comprehensive Guide To Resolving Issues With Your Logitech Clip's Digital Pen On XP</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-class-not-registered-problems-in-windows-10-a-comprehensive-solution/"><u>Dealing with 'Class Not Registered' Problems in Windows 10 - A Comprehensive Solution</u></a></li>
<li><a href="https://win-solutions.techidaily.com/dying-light-2-pc-struggles-optimizing-gameplay-and-improving-frame-rate/"><u>Dying Light 2 PC Struggles: Optimizing Gameplay & Improving Frame Rate</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correct-the-bad-module-information-to-stop-game-malfunctions/"><u>How To Correct the 'Bad Module Information' To Stop Game Malfunctions</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-apple-iphone-15-plus-location-without-installing-software-drfone-by-drfone-virtual-ios/"><u>How to Track Apple iPhone 15 Plus Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-oppo-find-x6-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Oppo Find X6 Devices | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/power-fluctuation-addressed-and-stabilized-in-distribution-hub/"><u>Power Fluctuation Addressed and Stabilized in Distribution Hub</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-resolve-launch-errors-of-new-world-issues-with-enabling-eas-easy-anti-cheat/"><u>Step-by-Step Guide to Resolve Launch Errors of New World - Issues with Enabling EA's Easy Anti-Cheat</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unexpected-computer-shuts-off-heres-how-to-diagnose-and-resolve-it/"><u>Unexpected Computer Shuts Off? Here's How to Diagnose and Resolve It.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-booting-woes-discover-how-to-overcome-unexpected-freezes-upon-startup/"><u>Windows 10 Booting Woes? Discover How to Overcome Unexpected Freezes Upon Startup</u></a></li>
</ul></div>

