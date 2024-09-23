---
title: "Optimizing MsMpEng.exe: Reducing High CPU Usage on Windows 11 - Solved"
date: 2024-09-21T22:34:50.367Z
updated: 2024-09-23T00:20:43.598Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Optimizing MsMpEng.exe: Reducing High CPU Usage on Windows 11 - Solved"
excerpt: "This Article Describes Optimizing MsMpEng.exe: Reducing High CPU Usage on Windows 11 - Solved"
thumbnail: https://thmb.techidaily.com/6f7d0e2a43b07618a84ad4bb4532a87360d4eb5cc4017e6eac185e39f8838773.jpg
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

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148646/16836" target="_top" id="2148646">
  <img src="//a.impactradius-go.com/display-ad/16836-2148646" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148646/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044585/7443" target="_top" id="2044585">
  <img src="//a.impactradius-go.com/display-ad/7443-2044585" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044585/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-beyond-basics-professional-tips-from-vidas-features/"><u>[New] Beyond Basics Professional Tips From Vida's Features</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-ultimate-gear-premium-lenses-for-vloggers/"><u>[New] In 2024, Ultimate Gear Premium Lenses for Vloggers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-precision-in-online-viewing-a-zoomers-handbook/"><u>[Updated] Precision in Online Viewing A Zoomer's Handbook</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-complete-guide-to-sourcing-elite-instagram-ringtones-and-designing-noteworthy-ringtone-alarms/"><u>A Complete Guide to Sourcing Elite Instagram Ringtones & Designing Noteworthy Ringtone Alarms</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-need-for-elevated-permissions-on-your-windows-machine-windows-11107/"><u>Bypassing the Need for Elevated Permissions on Your Windows Machine (Windows 11/10/7)</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-captivating-intros-for-podcasts-for-2024/"><u>Crafting Captivating Intros for Podcasts for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-fix-the-elevated-cpu-usage-by-windows-sound-hardware-drivers-issue/"><u>Diagnose and Fix the Elevated CPU Usage by Windows Sound Hardware Drivers Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-flash-plugin-breakdowns-for-a-smooth-experience-in-google-chrome/"><u>Fixing Flash Plugin Breakdowns for a Smooth Experience in Google Chrome</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722973394495-flexural-bending-failure-occurs-when-bending-moments-exceed-material-capacity-leading-to-cracking-and-deformation-of-beams-and-columns/"><u>Flexural (Bending) Failure Occurs when Bending Moments Exceed Material Capacity, Leading to Cracking and Deformation of Beams and Columns</u></a></li>
<li><a href="https://facebook.techidaily.com/how-to-limit-who-can-see-your-facebook-posts-with-a-restricted-list/"><u>How to Limit Who Can See Your Facebook Posts With a Restricted List</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-device-not-found-error-codes-24-on-windows-1087/"><u>How to Repair 'Device Not Found' Error Codes 24 on Windows 10/8/7</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-samsung-galaxy-z-flip-5-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Samsung Galaxy Z Flip 5 FRP Bypass</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-system-maintenance-unlocking-the-potential-of-sfc-and-dism-for-troubleshooting-windows-10-issues/"><u>Mastering Windows System Maintenance: Unlocking the Potential of SFC & DISM for Troubleshooting Windows 10 Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207320626-minecraft-opengl-problems-heres-how-to-resolve-them-successfully/"><u>Minecraft OpenGL Problems? Here's How to Resolve Them Successfully</u></a></li>
</ul></div>

