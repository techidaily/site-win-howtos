---
title: "Winning the Battle Against Failed Windows Updates: Tips & Tricks"
date: 2024-08-28T00:27:26.166Z
updated: 2024-08-29T00:27:26.166Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Winning the Battle Against Failed Windows Updates: Tips & Tricks"
excerpt: "This Article Describes Winning the Battle Against Failed Windows Updates: Tips & Tricks"
thumbnail: https://thmb.techidaily.com/259362f05442761cee2c53bd4a987280fdd7ced53308719769d03bba8108cbbd.png
---

## Winning the Battle Against MsMpEng.exe: Resolve Its CPU Hogging on Windows 10

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

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

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
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
<li><a href="https://extra-lessons.techidaily.com/new-best-instant-windows-photograph-gazing-tool/"><u>[New] Best Instant Windows Photograph Gazing Tool</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-capturewiz-windows-10s-snapshot-hero-for-2024/"><u>[New] CaptureWiz  Windows 10'S Snapshot Hero for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-eye-catching-tiktok-personalities-30-pfp-strategies-for-2024/"><u>[New] Eye-Catching TikTok Personalities  30 PFP Strategies for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-compreenas-an-insightful-guide-to-photography-mastery/"><u>[Updated] 2024 Approved  Compreenas  An Insightful Guide to Photography Mastery</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-100-killer-facebook-bios-to-make-profile-attractive2/"><u>2024 Approved  100 Killer Facebook Bios to Make Profile Attractive2</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bringing-harmony-to-your-screen-fixing-microsofts-display-connections-in-windows-10/"><u>Bringing Harmony to Your Screen: Fixing Microsoft's Display Connections in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-overcoming-the-0x80072efd-error-in-windows-10-environments/"><u>Comprehensive Fixes for Overcoming the 0X80072EFD Error in Windows 10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/definitive-guide-to-overcome-stalled-100-progress-in-windows-updates-fixed/"><u>Definitive Guide to Overcome Stalled 100%% Progress in Windows Updates [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-a-non-responsive-steam-store-page-error/"><u>Easy Fixes for a Non-Responsive Steam Store Page Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-combat-and-correct-valorants-persistent-screen-distortion-problem/"><u>Easy Steps to Combat and Correct Valorant's Persistent Screen Distortion Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211881676-end-the-frustration-of-spontaneous-hibernation-on-your-computer-smart-fixes-inside/"><u>End the Frustration of Spontaneous Hibernation on Your Computer - Smart Fixes Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolved-fix-for-semaphore-error-code-0x80070079-now-available/"><u>Error Resolved: Fix for Semaphore Error Code 0X80070079 Now Available</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-amd-gpu-drivers-for-bitcoin-mining-on-windows-systems/"><u>Get the Latest AMD GPU Drivers for Bitcoin Mining on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-reactivate-windows-smartscreen-when-it-fails-to-load/"><u>How to Reactivate Windows SmartScreen When It Fails to Load</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-d3d-device-failure-issues-on-windows-platforms-efficiently/"><u>How To Resolve D3D Device Failure Issues on Windows Platforms Efficiently</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-oppo-reno-9a-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Oppo Reno 9A to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ideal-suggestions-superior-mobile-melody-designers/"><u>In 2024, Ideal Suggestions  Superior Mobile Melody Designers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-stability-how-to-fix-continuous-crashes-of-nier-automata-on-your-computer-system/"><u>Mastering Stability: How to Fix Continuous Crashes of Nier Automata on Your Computer System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-dark-display-challenges-expert-strategies-for-your-dell-computer/"><u>Overcoming Dark Display Challenges: Expert Strategies for Your Dell Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-system-restore-challenges-in-windows-10-a-step-by-step-guide/"><u>Overcoming System Restore Challenges in Windows 10 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-pink-hue-dilemma-in-your-windows-11-interface/"><u>Overcoming the Pink Hue Dilemma in Your Windows 11 Interface</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-a-broken-screen-boosting-touch-responsiveness-on-windows-10-systems/"><u>Quick Fixes for a Broken Screen: Boosting Touch Responsiveness on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207155655-quick-fixes-for-common-wi-fi-connection-failures-expert-tips-inside/"><u>Quick Fixes for Common Wi-Fi Connection Failures – Expert Tips Inside</u></a></li>
<li><a href="https://tech-haven.techidaily.com/quit-comparing-siri-with-chatgpt-contrast-revealed/"><u>Quit Comparing Siri with ChatGPT: Contrast Revealed</u></a></li>
<li><a href="https://screen-recording.techidaily.com/recording-your-browsers-video-call-for-2024/"><u>Recording Your Browser's Video Call for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reinstating-the-vanished-speaker-icon-on-windows-11-a-picture-perfect-guide/"><u>Reinstating the Vanished Speaker Icon on Windows 11 - A Picture Perfect Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-youtube-sound-issues-a-guide-to-fixing-audio-renderer-errors-in-windows-11/"><u>Resolving YouTube Sound Issues: A Guide to Fixing Audio Renderer Errors in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-repairing-failed-logins-to-user-profile-service-an-in-depth-tutorial/"><u>Successfully Repairing Failed Logins to User Profile Service: An In-Depth Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/technical-collapse-terminal-hardware-problem/"><u>Technical Collapse: Terminal Hardware Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-solve-file-explorer-not-working-errors-for-windows-11-users/"><u>Troubleshoot and Solve File Explorer Not Working Errors for Windows 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-faulty-hp-laptop-cameras-under-windows-11-operating-system/"><u>Troubleshooting Guide for Faulty HP Laptop Cameras Under Windows 11 Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-noise-issues-in-acer-laptops-quick-guide/"><u>Troubleshooting Noise Issues in Acer Laptops - Quick Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-why-does-my-mouse-keep-losing-signal/"><u>Troubleshooting Steps: Why Does My Mouse Keep Losing Signal?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unsticking-the-spacebar-in-windows-11-effective-solutions-for-a-smooth-typing-experience/"><u>Unsticking the Spacebar in Windows 11: Effective Solutions for a Smooth Typing Experience</u></a></li>
</ul></div>
