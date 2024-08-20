---
title: Resolving Excessive CPU Consumption by MsMpEng.exe in Windows 10
date: 2024-08-19T07:08:35.615Z
updated: 2024-08-20T07:08:35.615Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Excessive CPU Consumption by MsMpEng.exe in Windows 10
excerpt: This Article Describes Resolving Excessive CPU Consumption by MsMpEng.exe in Windows 10
thumbnail: https://thmb.techidaily.com/5cbe5314b93a999758b5a00e2527a722031ccfee99834737192b083e09532191.jpg
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

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-stream.techidaily.com/new-from-concrete-jungles-to-eco-havens-rethinking-urban-living/"><u>[New] From Concrete Jungles to Eco Havens  Rethinking Urban Living</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-maximize-impact-with-professional-360-video-uploads-for-youtube/"><u>[New] In 2024, Maximize Impact with Professional 360° Video Uploads for YouTube</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-silent-youtube-browsing-for-iphones-and-androids/"><u>[New] Silent YouTube Browsing for iPhones and Androids</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-step-by-step-guide-recording-audio-on-the-internet-today/"><u>[New] Step-by-Step Guide  Recording Audio on the Internet Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-discord-mic-not-working/"><u>[Solved] Discord Mic Not Working</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-a-comprehensive-guide-to-producing-videos-for-social-media/"><u>[Updated] A Comprehensive Guide to Producing Videos For Social Media</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-az-screenshot-mastery-full-app-review-for-2024/"><u>[Updated] AZ Screenshot Mastery - Full App Review for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-digital-doppelganger-designs-sketching-an-animated-self/"><u>[Updated] Digital Doppelganger Designs  Sketching an Animated Self</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-showcase-your-story-premium-ig-covers-for-iphone-users/"><u>[Updated] In 2024, Showcase Your Story  Premium IG Covers for iPhone Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-master-your-music-collection-top-8-android-downloader-tools/"><u>[Updated] Master Your Music Collection - Top 8 Android Downloader Tools</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-advanced-techniques-for-gradual-volume-change/"><u>2024 Approved  Advanced Techniques for Gradual Volume Change</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-wisdom-waves-prime-ed-channels-online/"><u>2024 Approved  Wisdom Waves  Prime Ed Channels Online</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-xiaomis-precision-flight-insights-via-4k-lens/"><u>2024 Approved  Xiaomi's Precision Flight Insights via 4K Lens</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-guide-to-designing-spectacular-photo-tileworks-for-2024/"><u>A Guide to Designing Spectacular Photo Tileworks for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-ssltls-connection-problems-when-using-firefox-browser/"><u>Addressing SSL/TLS Connection Problems When Using Firefox Browser</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/android-call-history-recovery-recover-deleted-call-logs-from-xiaomi-redmi-note-12-4g-by-fonelab-android-recover-call-logs/"><u>Android Call History Recovery - recover deleted call logs from Xiaomi Redmi Note 12 4G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-boot-issues-expert-advice-to-get-you-up-and-running-again/"><u>Beat Boot Issues: Expert Advice to Get You Up and Running Again</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/correcting-missed-audio-segments-in-obs-recordings-for-2024/"><u>Correcting Missed Audio Segments in OBS Recordings for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/directx-11-unavailable-troubleshooting-steps-for-graphics-card-compatibility/"><u>DirectX 11 Unavailable? Troubleshooting Steps for Graphics Card Compatibility</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-stop-a-hanging-window-update-on-older-systems-troubleshooting-guide/"><u>Effective Solutions to Stop a Hanging Window Update on Older Systems (Troubleshooting Guide)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209943784-expert-tips-to-fix-continuous-operation-mode-on-windows-11-the-shutdown-problem-solved/"><u>Expert Tips to Fix Continuous Operation Mode on Windows 11 - The Shutdown Problem SOLVED</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-resolve-windows-updates-error-decoding-the-mystery-of-0x8007001f/"><u>Expert Tips to Resolve Windows Updates Error: Decoding the Mystery of 0X8007001F</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-common-issues-why-your-dvd-isnt-working-with-windows/"><u>Fixing Common Issues: Why Your DVD Isn't Working with Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/halo-4-fatal-system-crash-on-unreal-engine-4-here-are-your-ultimate-solutions/"><u>Halo 4 Fatal System Crash on Unreal Engine 4? Here Are Your Ultimate Solutions</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/how-the-aeiusny-inverter-transforms-solar-energy-for-critical-hospital-equipment/"><u>How the Aeiusny Inverter Transforms Solar Energy for Critical Hospital Equipment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-malfunctioning-keyboard-light-on-windows-and-macos-devices/"><u>How to Fix Malfunctioning Keyboard Light on Windows and macOS Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-of-your-steelseries-arctis-5s-built-in-mic/"><u>How to Restore Functionality of Your SteelSeries Arctis 5'S Built-In Mic</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-motorola-moto-g04-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Motorola Moto G04 Phone without Any Data Loss</u></a></li>
<li><a href="https://driver-install.techidaily.com/improve-visuals-revamping-hp-graphics-in-widgets/"><u>Improve Visuals: Revamping HP Graphics in WIDGETS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-a-comprehensive-quick-start-to-mastering-video-editing-win11s-movie-maker/"><u>In 2024, A Comprehensive Quick Start to Mastering Video Editing  Win11's Movie Maker</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-find-my-friends-work-on-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-no-device-drivers-detected-a-comprehensive-guide-to-troubleshoot-and-fix-during-windows-7-setup/"><u>Resolving 'No Device Drivers Detected': A Comprehensive Guide to Troubleshoot and Fix During Windows 7 Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-non-upgradable-problems-for-smooth-operation/"><u>Resolving Windows 11 Non-Upgradable Problems for Smooth Operation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-win11-non-stop-blue-screen/"><u>Resolving: Win11 Non-Stop Blue Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-addressing-problems-when-your-computer-cant-communicate-with-the-system-events-service/"><u>Solved: Addressing Problems When Your Computer Can't Communicate With the System Events Service</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-operation-prompts-easily-navigate-administrator-privileges-on-your-computers-operating-system/"><u>Solving Operation Prompts: Easily Navigate Administrator Privileges on Your Computer's Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-world-of-warcraft-lag-problems-for-seamless-quests-and-battles/"><u>Solving World of Warcraft Lag Problems for Seamless Quests and Battles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-solving-elevated-cpu-use-due-to-audio-device-graph-isolation-on-windows/"><u>Step-by-Step Guide: Solving Elevated CPU Use Due to Audio Device Graph Isolation on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-windows-update-error-0x802e200d-successfully-diy/"><u>Troubleshooting and Resolving Windows Update Error 0X802e200d Successfully [DIY]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-device-detection-issues-with-bluetooth-in-windows-11/"><u>Troubleshooting Guide: Fixing Device Detection Issues with Bluetooth in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-usb-reconnection-issues-solved/"><u>Troubleshooting Guide: USB Reconnection Issues Solved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-reactivating-your-devices-bluetooth-functionality/"><u>Troubleshooting Steps: Reactivating Your Device's Bluetooth Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-netsvc-how-to-troubleshoot-and-reduce-high-svchostexe-network-activity/"><u>Understanding NETsvc: How to Troubleshoot & Reduce High Svchost.exe Network Activity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212524940-windows-explorer-down-fix-now/"><u>Windows Explorer Down – Fix Now</u></a></li>
</ul></div>
