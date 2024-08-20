---
title: Diagnosing and Solving High MsMpEng CPU Usage on Windows 11 – Step by Step
date: 2024-08-19T07:10:56.199Z
updated: 2024-08-20T07:10:56.199Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Solving High MsMpEng CPU Usage on Windows 11 – Step by Step
excerpt: This Article Describes Diagnosing and Solving High MsMpEng CPU Usage on Windows 11 – Step by Step
thumbnail: https://thmb.techidaily.com/0ac17e49979c72a050b377ffc6f63723ef10196944c0e4d0e8d090140eaead92.jpg
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

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-elevate-your-videography-with-top-seo-gadgets/"><u>[New] 2024 Approved  Elevate Your Videography with Top SEO Gadgets</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-enhancing-visuals-tips-for-recording-ppt-effectively/"><u>[New] Enhancing Visuals  Tips for Recording PPT Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-intermittent-logitech-mouse-connection/"><u>[Resolved] Intermittent Logitech Mouse Connection</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-audio-mastery-in-visual-storytelling-vimeo-edition/"><u>[Updated] Audio Mastery in Visual Storytelling  Vimeo Edition</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-explore-top-10-no-cost-digital-photography-tools/"><u>[Updated] Explore Top 10 No-Cost Digital Photography Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-melodic-mastery-mac-studio-tips/"><u>[Updated] Melodic Mastery  Mac Studio Tips</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-live-feed-obs-on-instagram-app/"><u>2024 Approved  Live Feed  OBS on Instagram App</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-scrutinizing-instagrams-video-post-limit/"><u>2024 Approved  Scrutinizing Instagram's Video Post Limit</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-visionary-art-top-10-apps-for-vector-enthusiasts-for-2024/"><u>Crafting Visionary Art  Top 10 Apps for Vector Enthusiasts for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/curing-the-persistent-youtube-sound-renderer-malfunction-in-modern-windows-os/"><u>Curing the Persistent YouTube Sound Renderer Malfunction in Modern Windows OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-windows-update-problem-code-8007000e-explained/"><u>Effective Fixes for Windows Update Problem - Code 8007000E Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-excessive-cpu-load-by-svchostexe-in-windows-10-solutions-and-tips/"><u>Fixing Excessive CPU Load by svchost.exe in Windows 10 – Solutions and Tips</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-on-apple-iphone-6-by-drfone-ios/"><u>How to Fix Locked Apple ID on Apple iPhone 6</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-missing-power-symbols-in-windows-11-expert-troubleshooting-steps/"><u>How to Fix Missing Power Symbols in Windows 11: Expert Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-update-error-0x8024402c-solved/"><u>How to Fix Windows Update Error 0X8024402c [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-issues-with-windows-and-system-event-services-connection/"><u>How to Overcome Issues with Windows and System Event Services Connection</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-nokia-c110-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Nokia C110</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-social-network-harmony-integrating-instagram-and-facebook/"><u>In 2024, Social Network Harmony  Integrating Instagram & Facebook</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unleash-bright-potential-in-your-android-videos/"><u>In 2024, Unleash Bright Potential in Your Android Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fixes-for-deadly-errors-in-black-ops-latest-edition/"><u>Mastering the Fixes for Deadly Errors in Black Op's Latest Edition</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-transform-your-gopro-clips-a-comprehensive-mac-editing-tutorial-for-2024/"><u>New Transform Your GoPro Clips A Comprehensive Mac Editing Tutorial for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-visual-output-fix-unsupported-time-codes-in-your-current-monitor-setup/"><u>Optimizing Visual Output - Fix Unsupported Time Codes in Your Current Monitor Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-problem-enable-and-fix-disabled-wireless-capabilities-easily/"><u>Overcoming the Problem: Enable and Fix Disabled Wireless Capabilities Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/playstation-4-trouble-solve-the-mystery-of-error-code-ce-34878-0-today/"><u>PlayStation 4 Trouble? Solve the Mystery of Error Code CE-34878-0 Today</u></a></li>
<li><a href="https://win-able.techidaily.com/resolved-how-to-fix-excessive-cpu-consumption-in-google-chrome/"><u>Resolved: How to Fix Excessive CPU Consumption in Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-specified-module-not-found-errors-a-step-by-step-guide/"><u>Resolving 'Specified Module Not Found' Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-the-problem-night-light-feature-malfunction-in-recent-windows-os-versions/"><u>Solve the Problem: Night Light Feature Malfunction in Recent Windows OS Versions</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-overcoming-the-game-breaking-bug-causing-dauntless-to-crash-on-desktop/"><u>Solved: Overcoming the Game-Breaking Bug Causing Dauntless to Crash on Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211840975-solving-your-pdf-printing-issues-in-seconds/"><u>Solving Your PDF Printing Issues in Seconds!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-thawing-your-computer-from-a-freeze/"><u>Step-by-Step Guide: Thawing Your Computer From a Freeze</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/tech-tales-of-triumph-repairing-your-pc-with-chatai/"><u>Tech Tales of Triumph - Repairing Your PC with ChatAI</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-computer-components-expert-reviews-and-buying-guides/"><u>Tom's Computer Components - Expert Reviews and Buying Guides</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-8-chrome-enhancers-leveraging-ai-for-efficiency-boosts/"><u>Top 8 Chrome Enhancers Leveraging AI for Efficiency Boosts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-cod-wwii-fixing-error-4220/"><u>Troubleshooting Guide for COD WWII - Fixing Error 4220</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-non-functional-laptop-microphone/"><u>Troubleshooting Guide: Fixing a Non-Functional Laptop Microphone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-to-launch-minecraft-successfully-on-windows-systems/"><u>Troubleshooting Steps to Launch Minecraft Successfully on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-how-to-fix-a-non-responsive-razer-keyboard/"><u>Troubleshooting Tips: How To Fix A Non-Responsive Razer Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-touchpad-dealing-with-missing-cursor-on-windows-nx/"><u>Troubleshooting Your Touchpad: Dealing with Missing Cursor on Windows nX</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-solutions-to-resolve-binkyw32-dll-file-disappearance/"><u>Ultimate Solutions to Resolve Binkyw32 DLL File Disappearance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooter-for-computers-unable-to-shutdown-windows-10-fixed/"><u>Ultimate Troubleshooter for Computers Unable to Shutdown Windows 10 - FIXED</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-are-my-keyboard-arrow-keys-failing-discover-the-fixes-you-need/"><u>Why Are My Keyboard Arrow Keys Failing? Discover the Fixes You Need</u></a></li>
</ul></div>
