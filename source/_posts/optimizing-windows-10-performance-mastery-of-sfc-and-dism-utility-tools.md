---
title: "Optimizing Windows 10 Performance: Mastery of SFC and DISM Utility Tools"
date: 2024-09-26T00:45:06.503Z
updated: 2024-09-28T20:08:25.829Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Optimizing Windows 10 Performance: Mastery of SFC and DISM Utility Tools"
excerpt: "This Article Describes Optimizing Windows 10 Performance: Mastery of SFC and DISM Utility Tools"
thumbnail: https://thmb.techidaily.com/0dca80060c58b2b6bbf1021b5cfac76e3fa6cc6f30bafd7ebd2e3f93bc51e809.jpg
---

## Optimize Windows 11 Performance by Managing MsMpEngine CPU Drainage - Now Solved

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118315/7443" target="_top" id="2118315">
  <img src="//a.impactradius-go.com/display-ad/7443-2118315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118315/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036481/19272" target="_top" id="2036481">
  <img src="//a.impactradius-go.com/display-ad/19272-2036481" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036481/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-stream.techidaily.com/new-set-longer-duration-for-your-youtube-film/"><u>[New] Set Longer Duration for Your YouTube Film</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-explore-the-best-free-youtube-video-editor-apps-for-android-for-2024/"><u>[Updated] Explore the Best Free YouTube Video Editor Apps for Android for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-free-versatile-laptop-software-to-watch-dvds/"><u>2024 Approved Free, Versatile Laptop Software to Watch DVDs</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-best-10-final-cut-pro-plugins-ever/"><u>2024 Approved The Best 10 Final Cut Pro Plugins Ever</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-blockade-a-step-by-step-guide-to-solve-windows-10-couldnt-be-installed-error-code-aturality-80240020/"><u>Bypassing the Blockade: A Step-by-Step Guide to Solve Windows 10 Couldn't Be Installed - Error Code Aturality | 80240020</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-solutions-to-tackle-the-missing-haldll-file-problems-in-windows-xp/"><u>Comprehensive Solutions to Tackle the Missing hal.dll File Problems in Windows XP</u></a></li>
<li><a href="https://win-howtos.techidaily.com/could-the-loss-of-d3d-devices-kill-unreal/"><u>Could the Loss of D3D Devices Kill Unreal?</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/enhance-your-iphones-lifespan-shop-now-for-top-notch-stellar-erasers/"><u>Enhance Your iPhone's Lifespan - Shop Now for Top-Notch Stellar Erasers!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhancing-link-quality-between-epson-devices/"><u>Enhancing Link Quality Between Epson Devices</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/expert-advice-on-screen-casting-in-google-meet/"><u>Expert Advice on Screen Casting in Google Meet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-ce-34878-0-error-code-on-your-playstation-4-a-comprehensive-guide/"><u>How to Fix the CE-34878-0 Error Code on Your PlayStation 4: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-lost-invisible-desktop-windows-back/"><u>How To Get Your Lost, Invisible Desktop Windows Back!</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-unveiling-todays-drones-tomorrows-promise/"><u>In 2024, Unveiling Today's Drones Tomorrow's Promise</u></a></li>
<li><a href="https://win-amazing.techidaily.com/logitech-g402-mouse-drivers-and-installation-guides-free-download/"><u>Logitech G402 Mouse Drivers & Installation Guides - Free Download</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211775888-pubg-2024-master-the-art-of-fixing-game-launch-issues-and-start-enjoying-now/"><u>PUBG 2024: Master the Art of Fixing Game Launch Issues and Start Enjoying Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-optimize-your-computer-addressing-the-low-on-memory-warning-on-windows-10/"><u>Troubleshoot and Optimize Your Computer: Addressing the Low on Memory Warning on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-keyboard-fixing-non-working-directional-buttons/"><u>Troubleshoot Your Keyboard: Fixing Non-Working Directional Buttons</u></a></li>
</ul></div>

