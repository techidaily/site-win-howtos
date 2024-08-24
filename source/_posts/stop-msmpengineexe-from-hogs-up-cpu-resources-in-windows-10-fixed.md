---
title: Stop MsMpEngine.exe From Hogs Up CPU Resources in Windows 10 – FIXED
date: 2024-08-23T14:08:44.228Z
updated: 2024-08-24T14:08:44.228Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Stop MsMpEngine.exe From Hogs Up CPU Resources in Windows 10 – FIXED
excerpt: This Article Describes Stop MsMpEngine.exe From Hogs Up CPU Resources in Windows 10 – FIXED
thumbnail: https://thmb.techidaily.com/534bcc01d626eec0183aff232f0c9e211e75d3b58d6731fdc6da8a1b96d39a6c.jpg
---

## Stop MsMpEngine.exe From Hogs Up CPU Resources in Windows 10 – FIXED

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
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-guidance.techidaily.com/new-transcending-boundaries-the-vr-evolutionary-journey/"><u>[New] Transcending Boundaries  The VR Evolutionary Journey</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-vision-to-reality-benqs-masterpiece-the-bl2711u-monitor-review/"><u>[Updated] From Vision to Reality  BenQ’s Masterpiece, the BL2711U Monitor Review</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-how-to-speed-up-tiktok-videos-simple-guide-for-2024/"><u>[Updated] How to Speed Up TikTok Videos? [Simple Guide] for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-through-gopros-time-lapse-potential/"><u>[Updated] Navigating Through GoPro's Time-Lapse Potential</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-how-to-keep-the-momentum-ios-and-android-gif-savings/"><u>2024 Approved  How to Keep the Momentum  IOS & Android GIF Savings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtubes-monetary-system-monthly-or-quarterly/"><u>2024 Approved  YouTube's Monetary System  Monthly or Quarterly?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-keyboard-input-mistakes-solutions-for-unintended-letters/"><u>Addressing Keyboard Input Mistakes: Solutions for Unintended Letters</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-vivo-y100-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Vivo Y100 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://tech-revival.techidaily.com/behind-the-scenes-the-techniques-empowering-bots-for-realistic-interactions-with-users/"><u>Behind the Scenes: The Techniques Empowering Bots for Realistic Interactions with Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/boosting-windows-7-launch-times-tips-and-solutions-to-combat-delayed-startups/"><u>Boosting Windows 7 Launch Times: Tips & Solutions to Combat Delayed Startups</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-the-unable-to-play-video-hurdle-a-step-by-step-guide-on-handling-code-224003/"><u>Bypass the 'Unable to Play Video' Hurdle: A Step-by-Step Guide on Handling Code 224003</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-the-port-reset-failed-error-on-windows-11s-usb-devices-tips-and-tricks/"><u>Dealing with the Port Reset Failed Error on Windows 11'S USB Devices – Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-fixes-to-get-your-logitech-mouse-scroll-wheel-back-on-track/"><u>DIY Fixes to Get Your Logitech Mouse Scroll Wheel Back on Track</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-beats-to-broadcast-a-compreesive-guide-to-editing-your-podcast-for-2024/"><u>From Beats to Broadcast  A Compreesive Guide to Editing Your Podcast for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-crashing-in-total-war-rome-remastered-complete-guide/"><u>How to Fix Crashing in Total War: Rome Remastered - Complete Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/1715860448760-huaweis-built-in-recorder-screen-capture-for-mate-and-p-series-for-2024/"><u>Huawei's Built-In Recorder  Screen Capture for Mate and P Series. For 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/illuminate-the-path-ahead-strategies-for-dealing-with-monster-hunter-worldcups-blackout-at-boot-and-ensuring-a-colorful-comeback/"><u>Illuminate the Path Ahead - Strategies for Dealing with Monster Hunter: World'cups Blackout at Boot and Ensuring a Colorful Comeback</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-honor-play-7t-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Honor Play 7T FRP In 3 Different Ways</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Life360 Circle Everything You Need to Know On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-runners-digital-dream-top-virtual-reality-walkers/"><u>In 2024, The Runner's Digital Dream  Top Virtual Reality Walkers</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-uniting-sight-and-sound-perfecting-videography-voiceovers/"><u>In 2024, Uniting Sight & Sound  Perfecting Videography Voiceovers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-fix-how-to-address-could-not-write-crash-dump-glitches-in-wolfenstein-ii/"><u>In-Depth Fix: How to Address 'Could Not Write Crash Dump' Glitches in Wolfenstein II</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-easy-underwater-film-making-top-7-hacks/"><u>Mastering Easy Underwater Film-Making  Top 7 Hacks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-overwatch-voice-connection-fixes-without-the-hassle/"><u>Mastering Overwatch Voice Connection Fixes Without the Hassle</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-ps4-sync-errors-effective-solutions-for-your-gaming-control-pad/"><u>Overcoming PS4 Sync Errors: Effective Solutions for Your Gaming Control Pad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-tips-mastering-file-explorer-on-windows-10/"><u>Quick Tips: Mastering File Explorer on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rectifying-the-missing-audio-hardware-message-in-windows-11-systems/"><u>Rectifying the Missing Audio Hardware Message in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-malfunctioning-keyboard-typing-issue/"><u>Resolved: Malfunctioning Keyboard Typing Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-correcting-the-youtube-audio-renderer-malfunction-on-your-windows-10-computer/"><u>Step-by-Step Guide to Correcting the Youtube Audio Renderer Malfunction on Your Windows 10 Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-repairing-damaged-system-files-on-windows-11/"><u>Step-by-Step Solutions: Repairing Damaged System Files on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/swift-techniques-for-repairing-problematic-directx-launch-scenarios/"><u>Swift Techniques for Repairing Problematic DirectX Launch Scenarios</u></a></li>
<li><a href="https://youtube-data.techidaily.com/r-made-melodies-assembling-your-own-youtube-playlist/"><u>Tailor-Made Melodies  Assembling Your Own YouTube Playlist</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-when-microsoft-defender-smartscreen-is-unresponsive/"><u>Troubleshooting Guide: When Microsoft Defender SmartScreen Is Unresponsive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-solutions-to-prevent-total-war-rome-remastered-from-crashing/"><u>Ultimate Solutions to Prevent Total War: Rome Remastered From Crashing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-miracast-on-incompatible-devices-essential-tips-for-a-smooth-connection/"><u>Unlocking Miracast on Incompatible Devices: Essential Tips for a Smooth Connection</u></a></li>
<li><a href="https://win-blog.techidaily.com/unlocking-new-content-a-look-at-rainbow-six-sieges-freezing-2024-patch-details/"><u>Unlocking New Content: A Look at Rainbow Six Siege's Freezing 2024 Patch Details</u></a></li>
</ul></div>
