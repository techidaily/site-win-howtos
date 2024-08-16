---
title: Diagnosing and Fixing the wudfhost.exe High Resource Demand on Windows nT 10 Machines
date: 2024-08-15T11:33:09.765Z
updated: 2024-08-16T11:33:09.765Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Fixing the wudfhost.exe High Resource Demand on Windows nT 10 Machines
excerpt: This Article Describes Diagnosing and Fixing the wudfhost.exe High Resource Demand on Windows nT 10 Machines
thumbnail: https://thmb.techidaily.com/c034702b6853ed2a4a2c12ebcf392d7c9cb1e9d881720223713ec11ba7474c3a.jpg
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

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
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
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-a-comprehensive-guide-to-superior-valheim-saplings/"><u>[New] 2024 Approved  A Comprehensive Guide to Superior Valheim Saplings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-pro-video-illumination-top-strategies-for-immaculate-cinematography/"><u>[New] 2024 Approved  Pro Video Illumination  Top Strategies for Immaculate Cinematography</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-chuckle-factory-spooky-androids/"><u>[New] Chuckle Factory  Spooky Androids</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-maximize-your-mobile-top-10-free-image-enhancement-tools/"><u>[New] Maximize Your Mobile  Top 10 Free Image Enhancement Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-overwatch-could-not-locate-resources/"><u>[Solved] Overwatch Could Not Locate Resources</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-scrolling-on-touchpad-not-working-on-windows-11/"><u>[Solved] Scrolling on Touchpad Not Working on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-wacom-tablet-not-working-issues/"><u>[Solved] Wacom Tablet Not Working Issues</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2023-how-to-watch-facebook-live/"><u>[Updated] 2023 | How to Watch Facebook Live?</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-beat-the-purchase-free-fb-playlists-download/"><u>[Updated] Beat the Purchase  Free FB Playlists Download</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-mastering-photo-color-reversal-techniques-for-2024/"><u>[Updated] Mastering Photo Color Reversal Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-navigating-the-social-media-labyrinth-30-marketing-secrets/"><u>[Updated] Navigating the Social Media Labyrinth  30 Marketing Secrets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeating-the-scarlet-screen-blues-step-by-step-fix-for-common-errors/"><u>Defeating the Scarlet Screen Blues: Step-by-Step Fix for Common Errors</u></a></li>
<li><a href="https://program-issues.techidaily.com/destiny-2-graphics-failed-to-initialize-solved/"><u>Destiny 2 Graphics Failed to Initialize [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-repair-tackling-the-persistent-sound-crackles-in-windows-11-and-windows-abcdessors-win7/"><u>Diagnose & Repair: Tackling the Persistent Sound Crackles in Windows 11 & Windows Abcdessors (Win7)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-getting-your-igfxem-module-back-up-and-running/"><u>Expert Tips on Getting Your Igfxem Module Back Up and Running</u></a></li>
<li><a href="https://tech-revival.techidaily.com/explore-fun-top-6-game-experiences-with-chatgpt-revealed/"><u>Explore Fun: Top 6 Game Experiences with ChatGPT Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-critical-error-in-google-chrome-a-step-by-step-guide/"><u>Fixing the 'Critical Error' In Google Chrome: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/forgotten-sd-card-discover-remedies/"><u>Forgotten SD Card, Discover Remedies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-device-manager-error-code-28-on-windows-pcs/"><u>How to Fix a Device Manager Error: Code 28 on Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-offscreen-window-issues-a-comprehensive-walkthrough/"><u>How To Fix Offscreen Window Issues: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-10-may-update-version-1903-installation-problems-a-comprehensive-guide/"><u>How to Fix Windows 10 May Update (Version 1903) Installation Problems: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-copy-paste-functionality-on-your-windows-11-pc/"><u>How To Restore Copy-Paste Functionality on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-reconnect-to-the-steam-shop-after-unexpected-disruptions/"><u>How To Successfully Reconnect to The Steam Shop After Unexpected Disruptions</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Vivo S18? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-exploring-the-creme-de-la-creme-instas-influential-elite/"><u>In 2024, Exploring the Crème De La Crème  Insta's Influential Elite</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-poco-x6-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Poco X6 to Apple TV | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-poco-m6-pro-5g-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Poco M6 Pro 5G Phone</u></a></li>
<li><a href="https://driver-install.techidaily.com/install-updated-hp-graphics-on-windows-11-pc/"><u>Install Updated HP Graphics on Windows 11 PC</u></a></li>
<li><a href="https://data-wizards.techidaily.com/repairtool-reclaim-your-distorted-videos-at-no-cost/"><u>RepairTool: Reclaim Your Distorted Videos at No Cost</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-dxgkrnl-fatal-error-in-videos-under-windows/"><u>Resolve DXGKRNL Fatal Error in Videos Under Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-latency-problems-with-your-keyboard-in-windows-11-systems/"><u>Resolving Latency Problems with Your Keyboard in Windows 11 Systems</u></a></li>
<li><a href="https://techidaily.com/secure-your-free-amd-gpio-driver-start-now/"><u>Secure Your Free AMD GPIO Driver - Start Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-winning-against-kb4056892-installation-woes-in-windows-11/"><u>Step-by-Step Fix for Winning Against KB4056892 Installation Woes in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-to-fix-windows-installation-failure-error-0x80code0x080070643-on-windows-systems/"><u>Step-by-Step Solutions to Fix 'Windows Installation Failure Error 0X80([code]0X080070643) on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixes-for-nonfunctional-brightness-settings-on-windows-10/"><u>Troubleshooting Fixes for Nonfunctional Brightness Settings on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-error-1053-service-unresponsive-issues/"><u>Troubleshooting Guide: Resolving Error 1053 - Service Unresponsive Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-overcoming-d3derr-not-available-issues/"><u>Troubleshooting Tips for Overcoming 'D3DERR Not Available' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-overactive-msmpengexe-eating-cpu-on-your-windows-10-system-fixed/"><u>Troubleshooting: Overactive MsMpEng.exe Eating CPU on Your Windows 10 System (FIXED)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/udemy-alternatives-10-best-online-learning-sites-like-udemy-for-2024/"><u>Udemy Alternatives  10 Best Online Learning Sites Like Udemy for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/yac540-yamahaaturbosound-ii-sound-module-based-on-the-ymf769ymu769-dsp-plus-midi-synthesizer-plus-codec-and-128-mb-of-spiram-for-sample-storage-instead-of-r116/"><u>YAC540 - Yamaha'aturboSound II Sound Module Based on the YMF769/YMU769 (DSP + MIDI Synthesizer + Codec) and 128 MB of SPIRAM for Sample Storage Instead of ROM. It Also Includes a Second Audio Input Connector</u></a></li>
</ul></div>
