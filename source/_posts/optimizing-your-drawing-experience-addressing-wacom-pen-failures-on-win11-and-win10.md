---
title: "Optimizing Your Drawing Experience: Addressing Wacom Pen Failures on Win11 & Win10"
date: 2024-09-26T05:52:52.343Z
updated: 2024-09-28T20:47:01.782Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Optimizing Your Drawing Experience: Addressing Wacom Pen Failures on Win11 & Win10"
excerpt: "This Article Describes Optimizing Your Drawing Experience: Addressing Wacom Pen Failures on Win11 & Win10"
thumbnail: https://thmb.techidaily.com/1fe7ff1c6ccc0ab7bc1dc02b033d67aea4e7d6e05ae451c6e295e56be2a3c200.jpg
---

## Optimizing System Performance by Reducing MsMpEngine.exe CPU Drainage in Windows 10

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135373/19272" target="_top" id="2135373">
  <img src="//a.impactradius-go.com/display-ad/19272-2135373" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135373/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151882/7443" target="_top" id="2151882">
  <img src="//a.impactradius-go.com/display-ad/7443-2151882" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151882/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186864/12108" target="_top" id="1186864">
  <img src="//a.impactradius-go.com/display-ad/12108-1186864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186864/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135361/19272" target="_top" id="2135361">
  <img src="//a.impactradius-go.com/display-ad/19272-2135361" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997648/19272" target="_top" id="1997648">
  <img src="//a.impactradius-go.com/display-ad/19272-1997648" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997648/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-premier-moba-experiences-on-your-android-device/"><u>[Updated] 2024 Approved Premier MOBA Experiences on Your Android Device</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-build-successful-youtube-advertisements-for-free-in-2024/"><u>[Updated] How to Build Successful YouTube Advertisements for Free, In 2024</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/driven-with-cutting-edge-cookiebot-technology/"><u>Driven with Cutting-Edge Cookiebot Technology</u></a></li>
<li><a href="https://extra-information.techidaily.com/editing-excellence-archive-your-qanda/"><u>Editing Excellence Archive Your Q&A</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-updating-or-locating-missing-printer-drivers-in-windows-fixed/"><u>Guide to Updating or Locating Missing Printer Drivers in Windows [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-no-playable-content-detected-in-windows-media-player/"><u>How to Resolve No Playable Content Detected in Windows Media Player</u></a></li>
<li><a href="https://win-howtos.techidaily.com/instant-repair-guide-for-dota-2-transform-rendering-protocol-bug-code-2026/"><u>Instant Repair Guide for Dota 2 Transform Rendering Protocol Bug - Code 2026</u></a></li>
<li><a href="https://vp-tips.techidaily.com/les-meilleurs-converters-mac-vers-mp4-gratuits-et-en-ligne-top-4-recommandes/"><u>Les Meilleurs Converters MAC Vers MP4 Gratuits Et en Ligne : Top 4 Recommandés</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-harmonious-humans-cutting-out-clamor-from-your-compiled-charts-digitally-for-2024/"><u>New Harmonious Humans Cutting Out Clamor From Your Compiled Charts Digitally for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-update-error-code-0x80cuh0002-quickly-and-easily/"><u>Resolving Windows Update Error Code 0X80cuh0002 Quickly and Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-disappeared-desktop-icons-for-windows-11-users-issue-resolved/"><u>Restore Disappeared Desktop Icons for Windows 11 Users [ISSUE RESOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revived-stalled-audio-in-discord/"><u>Revived Stalled Audio in Discord</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-for-missing-d3dcompiler-dll-files-error-code-43/"><u>Solution Guide for Missing D3DCompiler DLL Files (Error Code 43)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ai-journey-simplified-edition/"><u>The AI Journey, Simplified Edition</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-eus-digital-strategy-and-its-influence-on-the-development-of-ai-systems-such-as-chatgpt/"><u>The EU's Digital Strategy & Its Influence on the Development of AI Systems Such as ChatGPT</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/virtual-collaboration-share-your-screens-with-facebook-viewers/"><u>Virtual Collaboration Share Your Screens with Facebook Viewers</u></a></li>
</ul></div>

