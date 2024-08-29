---
title: Solving High MsMpEng.exe CPU Usage on Your Windows 10 Machine
date: 2024-08-28T00:38:04.194Z
updated: 2024-08-29T00:38:04.194Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving High MsMpEng.exe CPU Usage on Your Windows 10 Machine
excerpt: This Article Describes Solving High MsMpEng.exe CPU Usage on Your Windows 10 Machine
thumbnail: https://thmb.techidaily.com/8d1de21c666386207e0a2c0896dc0647ebc82a413cfdd6aa282a235213b145ee.jpg
---

## Solving MsMpEng.exe High CPU Usage Issue on Windows 10 - Fixed

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

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-seamlessly-engage-fb-live-on-your-roku-screen/"><u>[Updated] In 2024, Seamlessly Engage  FB Live on Your Roku Screen</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-retreat-from-macos-sierras-latest-upgrade/"><u>2024 Approved  How to Retreat From MacOS Sierra's Latest Upgrade</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-critical-dll-loss-restoring-mfc71u-on-pcs/"><u>Addressing Critical DLL Loss: Restoring Mfc71u on PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/battle-desktop-window-managers-excessive-gpu-load-five-key-fixes-for-windows-users/"><u>Battle Desktop Window Manager's Excessive GPU Load: Five Key Fixes for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-the-port-reset-failed-error-on-windows-11s-usb-devices-tips-and-tricks/"><u>Dealing with the Port Reset Failed Error on Windows 11'S USB Devices – Tips & Tricks</u></a></li>
<li><a href="https://android-unlock.techidaily.com/downloading-samfw-frp-tool-30-for-samsung-galaxy-xcover-6-pro-tactical-edition-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Samsung Galaxy XCover 6 Pro Tactical Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-recover-corrupt-system-components-on-your-windows-11-device/"><u>Effective Solutions to Recover Corrupt System Components on Your Windows 11 Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-24-decoded-addressing-the-missing-device-warning-in-windows-versions/"><u>Error Code 24 Decoded: Addressing the Missing Device Warning in Windows Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/flawless-typing-ahead-diagnosing-and-fixing-bluetooth-keyboard-pairing-failures-with-laptops-or-desktops/"><u>Flawless Typing Ahead: Diagnosing and Fixing Bluetooth Keyboard Pairing Failures with Laptops or Desktops</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-printer-driver-not-found-on-your-windows-pc-fixed/"><u>How to Overcome 'Printer Driver Not Found' On Your Windows PC [FIXED]</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-my-motorola-edge-2023-location-is-wrong-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix My Motorola Edge 2023 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-invest-in-quality-best-4k-mirrorless-under-1000/"><u>In 2024, Invest in Quality  Best 4K Mirrorless Under $1,000</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-pattern-locks-are-unsafe-secure-your-zte-blade-a73-5g-phone-now-with-these-tips-by-drfone-android/"><u>In 2024, Pattern Locks Are Unsafe Secure Your ZTE Blade A73 5G Phone Now with These Tips</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-vivo-s17-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Vivo S17 Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-fix-how-to-address-could-not-write-crash-dump-glitches-in-wolfenstein-ii/"><u>In-Depth Fix: How to Address 'Could Not Write Crash Dump' Glitches in Wolfenstein II</u></a></li>
<li><a href="https://win-howtos.techidaily.com/process-halted-no-execution/"><u>Process Halted: No Execution</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reactivating-hidden-displays-on-nvidia-graphics-device/"><u>Reactivating Hidden Displays on NVIDIA Graphics Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-boot-not-detected-issues-on-your-device-easy-troubleshooting-steps-inside/"><u>Resolve Boot Not Detected Issues on Your Device - Easy Troubleshooting Steps Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-repair-a-corrupted-windows-store-cache/"><u>Resolved: How to Repair a Corrupted Windows Store Cache</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-clipboard-problems-on-windows-11-computers/"><u>Resolved! Troubleshooting Clipboard Problems on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-the-hp-laptop-camera-in-windows-10-expert-tips-and-fixes/"><u>Reviving the HP Laptop Camera in Windows 10: Expert Tips & Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-this-device-is-not-present-error-code-24-in-windows-versions-11-8-and-7/"><u>Step-by-Step Fixes for 'This Device Is Not Present' - Error Code 24 in Windows Versions: 11, 8 and 7</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-infinix-note-30-vip-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Infinix Note 30 VIP Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-tips-for-optimal-audio-enhancement-using-windows-10-equalizer-tools/"><u>Top Tips for Optimal Audio Enhancement Using Windows 10 Equalizer Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-resolving-twitch-error-4000/"><u>Troubleshooting Guide for Resolving Twitch Error 4000</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-addressing-insufficient-resource-allocation-warnings/"><u>Troubleshooting Guide: Addressing Insufficient Resource Allocation Warnings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-solutions-to-prevent-total-war-rome-remastered-from-crashing/"><u>Ultimate Solutions to Prevent Total War: Rome Remastered From Crashing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-preventing-unexpected-restarts-on-your-windows-10-machine/"><u>Understanding & Preventing Unexpected Restarts on Your Windows 10 Machine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-msdia80dll-importance-and-whether-to-retain/"><u>Understanding msdia80.dll: Importance & Whether To Retain</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unveiling-how-to-regain-access-to-missing-bluetooth-icon-on-windows-11-os/"><u>Unveiling How to Regain Access to Missing Bluetooth Icon on Windows 11 OS</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-add-background-melody-to-imovie-sequence/"><u>Updated In 2024, Add Background Melody to iMovie Sequence</u></a></li>
</ul></div>
