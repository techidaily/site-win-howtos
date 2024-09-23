---
title: "Windows 11 Optimization Tip: Lowering CPU Usage Spiked by wudfhost.exe Process"
date: 2024-09-17T19:20:04.961Z
updated: 2024-09-22T21:58:46.396Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Windows 11 Optimization Tip: Lowering CPU Usage Spiked by wudfhost.exe Process"
excerpt: "This Article Describes Windows 11 Optimization Tip: Lowering CPU Usage Spiked by wudfhost.exe Process"
thumbnail: https://thmb.techidaily.com/6d08ef0c51b7d66c7e631fe3667e11cb568cec8b149ae12a4fa97fbfe5c6637e.jpg
---

## Optimize Windows 11 Performance by Managing MsMpEngine CPU Drainage - Now Solved

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

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-recording.techidaily.com/new-clarifying-misleading-self-representations-on-fb/"><u>[New] Clarifying Misleading Self-Representations on FB</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastery-in-simulating-chrono-displacement/"><u>[New] Mastery in Simulating Chrono-Displacement</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-explore-cost-free-professional-cam-screen-recorders/"><u>[Updated] 2024 Approved Explore Cost-Free, Professional Cam Screen Recorders</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-navigating-video-data-in-high-capacity-drives-64128gb/"><u>[Updated] 2024 Approved Navigating Video Data in High-Capacity Drives (64/128GB)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1-efficiently-transform-mov-videos-into-high-quality-h265-a-step-by-step-guide/"><u>1. Efficiently Transform MOV Videos Into High-Quality H.265: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1-ultimate-guide-capturing-crystal-clear-sound-using-vlc-media-player-and-top-competitor-comparison/"><u>1. Ultimate Guide: Capturing Crystal-Clear Sound Using VLC Media Player & Top Competitor Comparison</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-12-pro-max-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 12 Pro Max System? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-cut-the-cost-not-the-creativity-best-free-editing-tools-top-9/"><u>In 2024, Cut The Cost, Not The Creativity Best Free Editing Tools (Top 9)</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-honor-magic-6-pro-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Honor Magic 6 Pro</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028219386-mov3/"><u>MOVファイルを別形式に変換する効果的な3手法 - ステップバイステップ解説</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-how-to-choose-the-most-effective-video-grabber-apps-featuring-flowplayer-technology/"><u>Ultimate Guide: How to Choose the Most Effective Video Grabber Apps Featuring Flowplayer Technology</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-list-of-trusted-sites-for-stress-free-mp3s-movies-and-more-downloads/"><u>Ultimate List of Trusted Sites for Stress-Free MP3s, Movies, and More Downloads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/updated-ultimate-guide-to-choosing-the-13-finest-mkv-file-conversion-tools-online/"><u>Updated Ultimate Guide to Choosing the 13 Finest MKV File Conversion Tools Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wav-to-mp3-mp3-to-wav-conversion-methods-with-windows-media-player/"><u>WAV to MP3 / MP3 to WAV Conversion Methods with Windows Media Player</u></a></li>
</ul></div>

