---
title: "Optimizing MsMpEng.exe: Reducing High CPU Usage on Windows 11 - Solved"
date: 2024-09-30T04:09:14.340Z
updated: 2024-10-04T01:25:06.627Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Optimizing MsMpEng.exe: Reducing High CPU Usage on Windows 11 - Solved"
excerpt: "This Article Describes Optimizing MsMpEng.exe: Reducing High CPU Usage on Windows 11 - Solved"
thumbnail: https://thmb.techidaily.com/6f7d0e2a43b07618a84ad4bb4532a87360d4eb5cc4017e6eac185e39f8838773.jpg
---

## Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved

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

<!-- affiliate ads begin -->
<span id="1542129">
					<video width="864" height="1152" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1542129.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1542129">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1542129.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1542129%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1542129/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137224/26400" target="_top" id="2137224">
  <img src="//a.impactradius-go.com/display-ad/26400-2137224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137224/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014850/22899" target="_top" id="2014850">
  <img src="//a.impactradius-go.com/display-ad/22899-2014850" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014850/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151866/7443" target="_top" id="2151866">
  <img src="//a.impactradius-go.com/display-ad/7443-2151866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-top-10-female-youtubers/"><u>[New] 2024 Approved Top 10 Female YouTubers</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-shift-your-tiktok-style-dive-into-background-selection-for-2024/"><u>[New] Shift Your TikTok Style Dive Into Background Selection for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-the-complete-review-lg-360-camera-cutting-edge-2023-edition/"><u>[Updated] 2024 Approved The Complete Review LG 360 Camera - Cutting-Edge 2023 Edition</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-ultra-hd-revolution-dissecting-samsungs-ue590-tv/"><u>[Updated] The Ultra HD Revolution - Dissecting Samsung's UE590 TV</u></a></li>
<li><a href="https://solve-manuals.techidaily.com/exploring-personal-hotspots-and-band-tours-unveiling-the-impact-with-abbyy/"><u>Exploring Personal Hotspots & Band Tours: Unveiling the Impact with ABBYY</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-honor-magic-5-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Honor Magic 5? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-critical-installer-failure-error-code-1603-and-complete-setup-successfully/"><u>How to Fix the 'Critical Installer Failure (Error Code 1603) and Complete Setup Successfully</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-poco-x6-pro-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Poco X6 Pro Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-error-code-5-in-minecraft-tips-for-a-smooth-gaming-experience/"><u>Overcoming Error Code 5 in Minecraft: Tips for a Smooth Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-0x802n200d-windows-update-issue-a-comprehensive-guide/"><u>Resolving the 0X802n200D Windows Update Issue: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-wireless-mouse-issues-steps-for-windows-11-and-windows-10-users/"><u>Resolving Wireless Mouse Issues: Steps for Windows 11 and Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-of-inoperative-usb-connectors-in-hp-notebook-computers/"><u>Solving the Problem of Inoperative USB Connectors in HP Notebook Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-casting-issues-to-devices-in-windows-11-solutions-and-tips/"><u>Troubleshooting Casting Issues to Devices in Windows 11: Solutions and Tips</u></a></li>
</ul></div>

