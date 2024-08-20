---
title: "Winning the Battle Against MsMpEng.exe: Resolve Its CPU Hogging on Windows 10"
date: 2024-08-19T07:12:05.214Z
updated: 2024-08-20T07:12:05.214Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Winning the Battle Against MsMpEng.exe: Resolve Its CPU Hogging on Windows 10"
excerpt: "This Article Describes Winning the Battle Against MsMpEng.exe: Resolve Its CPU Hogging on Windows 10"
thumbnail: https://thmb.techidaily.com/bb9708a331c4c3dd31e799c079bb73652a9e75d1a08dd178d051b1af275cc7e6.jpg
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

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

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
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-expressive-commentary-utilizing-emojis-on-youtube-for-2024/"><u>[New] Expressive Commentary  Utilizing Emojis on YouTube for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-privacy-focused-instagram-story-insight-methodology/"><u>[New] In 2024, Privacy-Focused Instagram Story Insight Methodology</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-inspiring-video-concepts-for-impactful-presentations/"><u>[New] Inspiring Video Concepts for Impactful Presentations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-l1-1-core-library-loader-not-found/"><u>[Resolved] L1-1 Core Library Loader Not Found</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-capture-nostalgia-uploading-past-photos-as-snaps/"><u>[Updated] 2024 Approved  Capture Nostalgia - Uploading Past Photos as Snaps</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-enhancing-youtube-viewing-with-faster-or-slower-video-pace/"><u>[Updated] 2024 Approved  Enhancing YouTube Viewing with Faster or Slower Video Pace</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-androids-top-game-lineup-for-disconnected-device-enthusiasts/"><u>[Updated] Android's Top Game Lineup for Disconnected Device Enthusiasts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-fiery-firefox-screenshot-add-ons-for-2024/"><u>[Updated] Fiery Firefox Screenshot Add-Ons for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-maximizing-reach-sharing-igtv-to-fb-4-methods-for-2024/"><u>[Updated] Maximizing Reach  Sharing IGTV to FB (4 Methods) for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-optimal-techniques-to-record-your-snapchat-stories-for-2024/"><u>[Updated] Optimal Techniques to Record Your Snapchat Stories for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-pitch-perfect-how-to-add-songs-to-your-snapchat-content/"><u>[Updated] Pitch Perfect  How to Add Songs to Your Snapchat Content</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-samsung-galaxy-m54-5g-frp-bypass-by-drfone-android/"><u>About Samsung Galaxy M54 5G FRP Bypass</u></a></li>
<li><a href="https://win-howtos.techidaily.com/battle-common-battery-blunders-ensuring-your-windows-11-laptop-charges-correctly-with-easy-fixes/"><u>Battle Common Battery Blunders: Ensuring Your Windows 11 Laptop Charges Correctly with Easy Fixes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-wearable-action-cameras-for-extreme-sport-for-2024/"><u>Best Wearable Action Cameras For Extreme Sport for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-steps-for-resolving-problems-with-directx-device-creation-processes/"><u>Comprehensive Steps for Resolving Problems with DirectX Device Creation Processes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-svchostexes-heavy-data-transfer-in-windows-systems/"><u>Diagnosing and Fixing svchost.exe's Heavy Data Transfer in Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-resolving-windows-11-mic-failures-for-clear-audio-communication/"><u>Diagnosing and Resolving Windows 11 Mic Failures for Clear Audio Communication</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-troubleshooting-techniques-to-correct-microsofts-0x800f0831-issue-using-windows-update-features/"><u>Easy Troubleshooting Techniques to Correct Microsoft's 0X800F0831 Issue Using Windows Update Features</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-when-your-touchpad-scroll-function-fails-a-complete-guide/"><u>Effective Fixes When Your Touchpad Scroll Function Fails – A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209376293-expert-tips-and-tricks-easily-restoring-faulty-laptop-keys-on-hp-models/"><u>Expert Tips & Tricks - Easily Restoring Faulty Laptop Keys on HP Models</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-restoring-functionality-in-a-malfunctioning-corsair-keyboard/"><u>Expert Tips for Restoring Functionality in a Malfunctioning Corsair Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-fix-a-sluggish-or-non-responsive-file-explorer-experience-on-your-windows-10-device/"><u>Expert Tips: Fix a Sluggish or Non-Responsive File Explorer Experience on Your Windows 10 Device</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-hp-deskjet-3630-driver-software-compatible-with-windows-10-systems/"><u>Get the Latest HP Deskjet 3630 Driver Software Compatible with Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-resolving-touchpad-scrolling-issues-on-laptops-a-step-by-step-solution/"><u>Guide to Resolving Touchpad Scrolling Issues on Laptops: A Step-by-Step Solution</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-convert-avchd-mts-files-for-xiaomi-redmi-k70-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to convert AVCHD .mts files for Xiaomi Redmi K70? </u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-oppo-reno-8t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Oppo Reno 8T? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-vivo-v29-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/how-to-mark-yourself-as-safe-on-facebook/"><u>How to Mark Yourself as Safe on Facebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-right-click-capabilities-in-windows-11-for-smooth-navigation/"><u>How to Restore Right-Click Capabilities in Windows 11 for Smooth Navigation</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-gopro-hero5-black-evolution-from-hero4-silver/"><u>In 2024, GoPro Hero5 Black Evolution From Hero4 Silver</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-vivo-y100t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Vivo Y100t? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-lava-storm-5g-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Lava Storm 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-honor-magic-6-pro-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Honor Magic 6 Pro to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-on-xiaomi-redmi-note-12-proplus-5g-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Xiaomi Redmi Note 12 Pro+ 5G FRP Bypass</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-se-2020-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/"><u>iPhone SE (2020) Asking for Passcode after iOS 17/14 Update, What to Do?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-10-freezing-and-update-problems-solutions-inside/"><u>Overcoming Windows 10 Freezing and Update Problems - Solutions Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/persistent-issues-with-windows-11-version-1607-patch-implementation/"><u>Persistent Issues with Windows 11 Version 1607 Patch Implementation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-when-your-hp-laptops-keys-stop-functioning-correctly/"><u>Quick Solutions When Your HP Laptop's Keys Stop Functioning Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/realtek-high-cpu-drain-resolving-the-ravbg64exe-audio-processing-problem/"><u>Realtek High CPU Drain: Resolving the Ravbg64.exe Audio Processing Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-no-audio-output-device-found-issue-on-your-windows-11-pc/"><u>Resolving the 'No Audio Output Device Found' Issue on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-stuck-audio-service-on-win-1110/"><u>Reviving Stuck Audio Service on WIN 11/10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/say-goodbye-to-game-crashes-expert-fix-for-total-war-rome-remastered/"><u>Say Goodbye To Game Crashes – Expert Fix for Total War: Rome Remastered</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210260738-skyrim-stuck-on-loading-forever-heres-how-you-can-break-free/"><u>Skyrim Stuck on Loading Forever? Here’s How You Can Break Free</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-puzzle-of-repeated-data-verification-issues-cyclic-redundancy/"><u>Solving the Puzzle of Repeated Data Verification Issues (Cyclic Redundancy)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-repairing-your-oculus-headsets-technical-glitches/"><u>Step-by-Step Guide to Repairing Your Oculus Headset's Technical Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-repairing-the-issue-when-ie-fails/"><u>Step-by-Step Guide: Repairing the Issue When IE Fails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-microsoft-print-to-pdf-issues-on-windows-10-and-11/"><u>Step-by-Step Solutions for Microsoft Print to PDF Issues on Windows 10 and 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723201758012-surface-typing-snafu-resolved/"><u>Surface Typing Snafu, Resolved</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-meme-mechanic-generating-online-engagement-through-videos-for-2024/"><u>The Meme Mechanic  Generating Online Engagement Through Videos for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-solving-your-persistent-computer-mouse-connection-issues/"><u>Ultimate Guide: Solving Your Persistent Computer Mouse Connection Issues</u></a></li>
</ul></div>
