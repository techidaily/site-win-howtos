---
title: Disrupting High CPU Usage in Windows 11
date: 2024-08-19T07:55:12.261Z
updated: 2024-08-20T07:55:12.261Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Disrupting High CPU Usage in Windows 11
excerpt: This Article Describes Disrupting High CPU Usage in Windows 11
thumbnail: https://thmb.techidaily.com/f5d1594082aca6452dbc25a49388a37fc7e84721f123ecd76572cb92530c4365.jpg
---

## Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
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
<li><a href="https://facebook-video-share.techidaily.com/new-3-efficient-methods-for-saving-youtubes-standardized-images-for-2024/"><u>[New] 3 Efficient Methods for Saving YouTube's Standardized Images for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-base-to-pro-level-gopro-hero5-black-vs-hero4-silver-showdown/"><u>[New] From Base to Pro-Level  GoPro Hero5 Black vs Hero4 Silver Showdown</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-cracking-the-code-understanding-tiktok-and-snaps-similarities/"><u>[New] In 2024, Cracking the Code  Understanding TikTok & Snap's Similarities</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-marketing-unveiling-techniques/"><u>[New] Marketing Unveiling Techniques</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/outube-success-elevating-audience-count-for-2024/"><u>[New] YouTube Success  Elevating Audience Count for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-spacebar-not-working-on-windows-11/"><u>[Solved] Spacebar Not Working on Windows 11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-boosting-youtube-visibility-mastering-titles-and-tags/"><u>[Updated] Boosting YouTube Visibility  Mastering Titles & Tags</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-ultimate-offline-voice-processor/"><u>[Updated] Ultimate Offline Voice Processor</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-motorola-edge-40-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/5-outstanding-mkv-tools-for-macos-users/"><u>5 Outstanding MKV Tools for macOS Users</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-gionee-f3-pro-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Gionee F3 Pro</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205342105-arctis-5-mic-not-working-heres-the-ultimate-fix/"><u>Arctis 5 Mic Not Working? Here's The Ultimate Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decode-and-fix-twitch-error-4000-your-comprehensive-guide-to-a-smooth-streaming-experience/"><u>Decode and Fix Twitch Error 4000 - Your Comprehensive Guide to a Smooth Streaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dell-camera-malfunction-in-windows-solutions-for-reviving-image-capture-features/"><u>Dell Camera Malfunction in Windows - Solutions for Reviving Image Capture Features</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-guide-amd-vega-graphics-card-software-downloads-and-updates-optimized-for-gaming/"><u>Easy Guide: AMD Vega Graphics Card Software Downloads and Updates - Optimized for Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eliminate-game-disruptions-solving-valorants-screen-tearing-problem-efficiently/"><u>Eliminate Game Disruptions: Solving Valorant's Screen Tearing Problem Efficiently</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/employment-mastery-made-possible-by-smart-ai-tech/"><u>Employment Mastery Made Possible by Smart AI Tech</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-to-repairing-usb-port-issues-in-windows-10-and-11-systems/"><u>Expert Guide to Repairing USB Port Issues in Windows 10 and 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-solutions-to-accelerate-windows-7-booting-performance/"><u>Expert Solutions to Accelerate Windows 7 Booting Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-fixes-for-overcoming-windows-persistent-update-error-code-0x80amelioration-of-update-malfunction/"><u>Fast Fixes for Overcoming Window's Persistent Update Error: Code 0X80amelioration of Update Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-failed-creation-of-d3d-graphics-device-in-windows-applications-step-by-step-solution/"><u>Fixing Failed Creation of D3D Graphics Device in Windows Applications: Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-error-driver-not-found-for-wacom-pen-and-touchpad-on-windows-10/"><u>Fixing the Error: 'Driver Not Found' For Wacom Pen & Touchpad on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-when-your-screen-doesnt-accept-certain-inputs/"><u>Fixing the Issue When Your Screen Doesn’t Accept Certain Inputs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-automatic-updates-that-arent-working-comprehensive-guide/"><u>Fixing Windows Automatic Updates That Aren't Working – Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-repairing-your-windows-stores-damaged-cache-issue-resolved/"><u>Guide to Repairing Your Windows Store's Damaged Cache (ISSUE RESOLVED)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-maintain-constant-connection-for-your-wireless-mouse/"><u>How to Maintain Constant Connection for Your Wireless Mouse</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-lava-blaze-2-5g-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Lava Blaze 2 5G Back to Operation | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-watch-hulu-on-an-lg-smart-tv/"><u>How to Watch Hulu on an LG Smart TV</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-pros-choice-identifying-the-best-9-webmicrone-capture-gear-23/"><u>In 2024, Pro's Choice  Identifying the Best 9 Webmicrone Capture Gear ('23)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-oppo-find-x7-ultra-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Oppo Find X7 Ultra Location | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-keyboards-failing-top-tips-and-tricks-to-restore-your-typing-experience/"><u>Lenovo Keyboards Failing? Top Tips and Tricks to Restore Your Typing Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lsa-defense-reactivated-how-to-secure-your-system-effectively/"><u>LSA Defense Reactivated: How to Secure Your System Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/netflix-trouble-heres-how-to-fix-the-using-a-proxyvpn-error-message/"><u>Netflix Trouble? Here's How to Fix the 'Using a Proxy/VPN' Error Message</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-missing-dll-in-steam-games/"><u>Overcoming Missing DLL in Steam Games</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-guide-to-fixed-kernel32-crashes/"><u>Quick Guide to Fixed Kernel32 Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reinstating-sound-capabilities-on-your-windows-7-pc-restored/"><u>Reinstating Sound Capabilities on Your Windows 7 PC ([Restored])</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-input-not-recognized-issues-displayed-on-monitors/"><u>Resolving 'Input Not Recognized' Issues Displayed on Monitors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-failed-feature-updates-for-windows-10-v1607-a-step-by-step-guide/"><u>Resolving Failed Feature Updates for Windows 10 v1607: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speaker-noise-elimination-techniques-for-windows-11-and-7-users/"><u>Speaker Noise Elimination Techniques for Windows 11 and 7 Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/step-by-step-guide-to-creating-an-eye-catching-collage/"><u>Step-by-Step Guide to Creating an Eye-Catching Collage</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-overcoming-hamachi-halted-error/"><u>Step-by-Step Guide to Overcoming Hamachi Halted Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-overcoming-0x80070652-windows-update-errors-easily/"><u>Step-by-Step Guide: Overcoming 0X80070652 Windows Update Errors Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-error-unable-to-access-windows-installer-issues/"><u>Step-by-Step Solution for Error: Unable to Access Windows Installer Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-non-functional-brightness-settings-on-windows-11-devices/"><u>Step-by-Step Solutions for Non-Functional Brightness Settings on Windows 11 Devices</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/streaming-to-profit-youtube-policy-changes/"><u>Streaming to Profit  YouTube Policy Changes</u></a></li>
<li><a href="https://win-answers.techidaily.com/top-6-solutions-to-stop-modern-warfare-2-from-crashing-on-your-pc/"><u>Top 6 Solutions to Stop Modern Warfare 2 From Crashing on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-overcoming-unexpected-crashes-in-directx-applications/"><u>Troubleshooting Guide: Overcoming Unexpected Crashes in DirectX Applications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-successful-fixes-on-warframe-patch-errors/"><u>Troubleshooting Successful Fixes on Warframe Patch Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-to-resolve-error-8007000e-in-windows-update-without-delay/"><u>Troubleshooting Tips to Resolve Error 8007000E in Windows Update Without Delay</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-why-is-my-spacebar-unresponsive-in-windows-11/"><u>Troubleshooting: Why Is My Spacebar Unresponsive in Windows 11?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/visualverve-tips-for-resizing-images-in-instagram-for-2024/"><u>VisualVerve  Tips for Resizing Images in Instagram for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-is-my-razer-keyboard-not-lights-fix-and-prevent-this-common-problem/"><u>Why Is My Razer Keyboard Not Lights? Fix and Prevent This Common Problem!</u></a></li>
</ul></div>
