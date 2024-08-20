---
title: Resolving High Disk Usage Caused by Microsoft Compatibility Telemetry on Windows 10 Systems
date: 2024-08-19T07:18:14.868Z
updated: 2024-08-20T07:18:14.868Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving High Disk Usage Caused by Microsoft Compatibility Telemetry on Windows 10 Systems
excerpt: This Article Describes Resolving High Disk Usage Caused by Microsoft Compatibility Telemetry on Windows 10 Systems
thumbnail: https://thmb.techidaily.com/34983eeb01d46447a2aa80e2d1b0eee6f876f53497144fdec843045cc8106d3c.jpg
---

## Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
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
<li><a href="https://fox-helps.techidaily.com/new-21-edition-breakdown-analyzing-the-revolution-in-vegas-pro-gaming-for-2024/"><u>[New] '21 Edition Breakdown – Analyzing the Revolution in Vegas Pro Gaming for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-a-step-by-step-guide-to-youtube-comms-management/"><u>[New] 2024 Approved  A Step-by-Step Guide to YouTube Comms Management</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-the-ultimate-checklist-for-protecting-your-digital-assets/"><u>[New] 2024 Approved  The Ultimate Checklist for Protecting Your Digital Assets</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snaps-for-cash-a-guide-to-profitability-for-2024/"><u>[New] Snaps for Cash  A Guide to Profitability for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-system-interrupts-high-cpu-usage-on-windows-10/"><u>[Solved] System Interrupts High CPU Usage on Windows 10</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-revolutionize-tech-connectivity-top-free-speech-conversion-tools-for-macos/"><u>2024 Approved  Revolutionize Tech Connectivity  Top Free Speech Conversion Tools for MacOS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/definitive-fixes-overcoming-windows-media-player-server-error-woes-on-windows-os/"><u>Definitive Fixes: Overcoming Windows Media Player Server Error Woes on Windows OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-intermittent-sounds-in-your-logitech-g930-headset/"><u>Effective Fixes for Intermittent Sounds in Your Logitech G930 Headset</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-overcome-the-0x80070490-hurdle-during-system-updates-on-windows/"><u>Effective Solutions to Overcome the 0X80070490 Hurdle During System Updates on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-remedies-correcting-undetected-battery-problems/"><u>Effortless Remedies: Correcting Undetected Battery Problems</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/enhance-live-footage-overcoming-blurry-video-issues-in-chrome-for-2024/"><u>Enhance Live Footage  Overcoming Blurry Video Issues in Chrome for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-your-gpu-experience-by-fixing-inadequate-alpha-blending-support/"><u>Enhance Your GPU Experience by Fixing Inadequate Alpha Blending Support</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0x887a0006-no-more-fast-fixes-at-your-fingertips/"><u>Error 0X887A0006 No More: Fast Fixes at Your Fingertips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0xc0000098-troubleshooting-for-windows-users-effective-fixes-explained/"><u>Error 0xC0000098 Troubleshooting for Windows Users – Effective Fixes Explained</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-iphone-12-pro-max-backup-password-heres-what-to-do-drfone-by-drfone-ios/"><u>Forgot iPhone 12 Pro Max Backup Password? Heres What to Do | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-create-an-apple-developer-account-on-iphone-14-by-drfone-ios/"><u>How To Create an Apple Developer Account On iPhone 14</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204731127-how-to-fix-call-of-duty-ww2-error-code-4220-and-get-back-in-battle-asap/"><u>How to Fix Call of Duty WW2 Error Code 4220 & Get Back in Battle ASAP!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-csgo-high-ping-issues/"><u>How to Fix CS:GO High Ping Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-the-one-or-more-components-cant-be-configured-by-windows-error/"><u>How to Overcome the 'One or More Components Can't Be Configured by Windows' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-sound-quality-problems-fixing-windows-speaker-glitches/"><u>How to Resolve Sound Quality Problems: Fixing Window's Speaker Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-to-a-defective-shift-key-guide/"><u>How to Restore Functionality to a Defective Shift Key (Guide)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-repair-a-malfunctioning-lenovo-keyboard/"><u>How To Troubleshoot and Repair A Malfunctioning Lenovo Keyboard</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-cloaked-observer-of-facebook-snapshots/"><u>In 2024, Cloaked Observer of Facebook Snapshots</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-top-edge-video-editing-programs-for-instagram-on-android/"><u>In 2024, Top Edge Video Editing Programs for Instagram on Android</u></a></li>
<li><a href="https://win-howtos.techidaily.com/kodi-troubleshooting-mastery-overcoming-errors-and-enjoying-media-again/"><u>Kodi Troubleshooting Mastery: Overcoming Errors and Enjoying Media Again</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>Life360 Circle Everything You Need to Know On Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-metas-portal-to-vr-how-to-establish-an-oculus-questquest-2-identity/"><u>Navigating Meta's Portal to VR: How To Establish An Oculus Quest/Quest 2 Identity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/opaque-oscillation-device-mystery/"><u>Opaque Oscillation: Device Mystery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-destiny-2-boot-issues-effective-solutions-unveiled/"><u>Overcome Destiny 2 Boot Issues: Effective Solutions Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-frustrating-0x80070490-barrier-in-windows-updates-a-complete-fix/"><u>Overcoming the Frustrating 0X80070490 Barrier in Windows Updates - A Complete Fix</u></a></li>
<li><a href="https://extra-tips.techidaily.com/radiance-routines-pro-tips-for-video-illumination/"><u>Radiance Routines  Pro Tips for Video Illumination</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-unresponsive-external-mouse-problems-for-windows-and-mac/"><u>Resolve Unresponsive External Mouse Problems for Windows and Mac</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-vcruntime140dll-missing-file-issue-comprehensive-fix-guide/"><u>Resolve Your VCRUNTIME140.dll Missing File Issue - Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-typing-issues-on-keyboard-no-longer-a-problem/"><u>Resolved: Typing Issues on Keyboard No Longer a Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-windows-update-issue-code-0x8024402c-explained-and-solved/"><u>Resolving the Windows Update Issue: Code 0X8024402C Explained and Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-pad-scrolling-malfunction-a-step-by-step-guide/"><u>Resolving Windows 11 Pad Scrolling Malfunction: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-steam-store-wont-load-effective-troubleshooting-tips/"><u>Solving the Issue of 'Steam Store Won't Load': Effective Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-undetected-bluetooth-hardware-in-windows-11/"><u>Solving the Issue of Undetected Bluetooth Hardware in Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/spot-the-scam-tips-for-facebook-security-hygiene/"><u>Spot the Scam: Tips for Facebook Security Hygiene</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-restoring-function-key-response-on-asus-laptops/"><u>Step-by-Step Guide: Restoring Function Key Response on ASUS Laptops</u></a></li>
<li><a href="https://games-able.techidaily.com/top-quality-gadgets-at-ifa-expo/"><u>Top-Quality Gadgets at IFA Expo</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-windows-error-0xc00n0000098-expert-tips-for-quick-fixes/"><u>Troubleshooting and Resolving Windows Error 0xC00n0000098: Expert Tips for Quick Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-non-functional-wacom-pen-in-windows-11-and-windows-10/"><u>Troubleshooting Guide: Fixing a Non-Functional Wacom Pen in Windows 11 and Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-solving-windows-camera-not-working-error-0xa00febec6-issue/"><u>Troubleshooting Guide: Solving Windows Camera Not Working (Error 0xA00Febec6) Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-win32-exception-not-handled-error-0xc0000005-in-windows/"><u>Ultimate Guide: Resolving Win32 Exception Not Handled (Error 0xC0000005) in Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/unlocking-sound-potential-mastering-mac-audio-with-audacity-for-2024/"><u>Unlocking Sound Potential  Mastering Mac Audio with Audacity for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207172245-usb-peripherals-failure-in-windows-7-heres-how-you-can-repair-them/"><u>USB Peripherals Failure in Windows 7? Here's How You Can Repair Them</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-machine-stops-unannounced/"><u>Windows 11: Machine Stops Unannounced</u></a></li>
</ul></div>
