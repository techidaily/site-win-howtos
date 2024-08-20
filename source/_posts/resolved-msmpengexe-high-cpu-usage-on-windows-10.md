---
title: "Resolved: MsMpEng.exe High CPU Usage on Windows 10"
date: 2024-08-19T06:17:37.388Z
updated: 2024-08-20T06:17:37.388Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: MsMpEng.exe High CPU Usage on Windows 10"
excerpt: "This Article Describes Resolved: MsMpEng.exe High CPU Usage on Windows 10"
thumbnail: https://thmb.techidaily.com/6644f0a2d74892fa3a39d2d46d9f44395a7ca3377bb37001448c4704afb2e518.jpg
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
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
<li><a href="https://some-skills.techidaily.com/new-ultimate-powerdirector-guide/"><u>[New] Ultimate PowerDirector Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/best-techniques-for-unfreezing-the-windows-11-taskbar-issue/"><u>Best Techniques for Unfreezing the Windows 11 Taskbar Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/combat-blizzards-wow-lag-proven-strategies-for-smooth-gameplay/"><u>Combat Blizzard's Wow Lag: Proven Strategies for Smooth Gameplay</u></a></li>
<li><a href="https://win-howtos.techidaily.com/discord-voice-channels-now-responsive/"><u>Discord Voice Channels Now Responsive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-to-fix-amd-catalyst-control-center-cannot-be-started/"><u>Easy to Fix AMD Catalyst Control Center Cannot Be Started</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-address-xerox-printing-software-update-issue-facing-error-0x800f020b-on-windows-pcs/"><u>Effective Solutions to Address Xerox Printing Software Update Issue – Facing Error 0X800F020B on Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-fix-the-scroll-wheel-on-a-logitech-mouse-failure/"><u>Effective Solutions to Fix the Scroll Wheel on a Logitech Mouse Failure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-tackle-the-windows-11-update-error-0xc190n0028-a-users-manual/"><u>Effective Solutions to Tackle the Windows 11 Update Error 0XC190n0028: A User's Manual</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-visuals-on-windows-10-a-guide-to-resolving-pixelated-characters-and-text/"><u>Enhance Visuals on Windows 10: A Guide to Resolving Pixelated Characters & Text</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhancing-keyboard-responsiveness-on-your-windows-11-pc-a-comprehensive-guide-to-solving-latency-problems/"><u>Enhancing Keyboard Responsiveness on Your Windows 11 PC - A Comprehensive Guide to Solving Latency Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-fixing-the-minecraft-wont-start-error-in-windows-computers/"><u>Expert Advice: Fixing the 'Minecraft Won't Start' Error in Windows Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-successfully-connecting-bluetooth-gadgets-to-windows-10-this-year/"><u>Expert Advice: Successfully Connecting Bluetooth Gadgets to Windows 10 This Year</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-how-to-fix-your-pc-when-it-gets-stuck-on-initial-boot-display/"><u>Fixed: How to Fix Your PC When It Gets Stuck on Initial Boot Display</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-choose-an-ideal-surge-protector-for-home-electronics/"><u>How to Choose an Ideal Surge Protector for Home Electronics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-fix-windows-11-update-failure-error-code-0xc1e90208/"><u>How to Successfully Fix Windows 11 Update Failure (Error Code: 0XC1e90208)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-repair-windows-1011s-update-error-decode-and-fix-error-0x802errordescription-solutionkeyword/"><u>How to Successfully Repair Windows 10/11'S Update Error: Decode and Fix Error 0X802([error_description]) [Solution_keyword]</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-watch-avchd-mts-video-on-motorola-moto-g-5g-2023-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to watch AVCHD MTS video on Motorola Moto G 5G (2023)?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unlocking-skypes-full-capacity-with-effective-zoom-methods/"><u>In 2024, Unlocking Skype's Full Capacity with Effective Zoom Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/kernel32dll-fixes-and-tips-for-win/"><u>Kernel32.dll: Fixes and Tips for Win</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202987997-mac-camera-issues-resolve-them-with-these-easy-techniques/"><u>Mac Camera Issues? Resolve Them with These Easy Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-fixing-unexpected-shutdowns-in-windows-11-step-by-step-strategies/"><u>Master the Art of Fixing Unexpected Shutdowns in Windows 11 – Step by Step Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-a-guide-to-repairing-unknown-usb-and-port-reset-faults-in-windows-11-systems/"><u>Mastering the Fix: A Guide to Repairing Unknown USB and Port Reset Faults in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-system-challenges-with-absent-xinput13dll/"><u>Navigating System Challenges with Absent XINPUT1_3.dll</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-limited-memory-challenges-fixing-windows-10-errors/"><u>Overcoming Limited Memory Challenges: Fixing Windows 10 Errors</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-and-effective-solutions-for-when-your-wifi-stops-working/"><u>Quick and Effective Solutions for When Your WiFi Stops Working</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-windows-11-bluetooth-connectivity-problems-with-these-simple-fixes/"><u>Resolve Your Windows 11 Bluetooth Connectivity Problems with These Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-fortnite-on-incompatible-windows-graphics-cards/"><u>Resolved: Fixing Fortnite on Incompatible Windows Graphics Cards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-fix-minecraft-not-starting-on-windows-os/"><u>Resolved: How to Fix 'Minecraft Not Starting on Windows OS'</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/savvy-savers-for-your-instagram-treasures/"><u>Savvy Savers for Your Instagram Treasures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-of-missing-power-sources-in-electronics-easy-tips/"><u>Solving the Mystery of Missing Power Sources in Electronics: Easy Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-unfreezing-your-laptops-trackpad-or-external-mouse/"><u>Step-by-Step Solutions: Unfreezing Your Laptop's Trackpad or External Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-correct-a-non-working-lenovo-biometric-device-fast/"><u>Step-by-Step: Correct a Non-Working Lenovo Biometric Device Fast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-troubleshooting-unresponsive-google-chrome-expert-advice-and-solutions/"><u>Successfully Troubleshooting Unresponsive Google Chrome: Expert Advice & Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-excessive-sound-on-your-ps4-console-troubleshooting-steps/"><u>Tackling Excessive Sound on Your PS4 Console: Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-criticality-of-xinput13dll-and-troubleshooting-its-missing-status/"><u>The Criticality of XINPUT1_3.dll & Troubleshooting Its Missing Status</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolution-for-elevated-cpu-drain-by-microsofts-msmpeng-process-on-windows-10/"><u>Troubleshooting and Resolution for Elevated CPU Drain by Microsoft's MsMpEng Process on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-device-detection-issues-in-windows-10s-bluetooth/"><u>Troubleshooting Guide: Fixing Device Detection Issues in Windows 10'S Bluetooth</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-device-detection-issues-in-windows-11-via-bluetooth/"><u>Troubleshooting Guide: Resolving Device Detection Issues in Windows 11 via Bluetooth</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlock-touchpad-integrity-with-quick-fixes/"><u>Unlock Touchpad Integrity with Quick Fixes!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-frozen-steam-software-enhancement-with-these-simple-tips/"><u>Unstick Your Frozen Steam Software Enhancement with These Simple Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/vcruntime140dll-not-found-heres-how-to-quickly-correct-it/"><u>VCRUNTIME140.dll Not Found? Here's How to Quickly Correct It!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/verifying-microphone-function-on-windows/"><u>Verifying Microphone Function on Windows</u></a></li>
</ul></div>
