---
title: "Optimizing System Performance: Stop svchost.exe From Consuming Too Much CPU in Windows 10"
date: 2024-11-13T21:09:53.193Z
updated: 2024-11-18T19:54:54.469Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Optimizing System Performance: Stop svchost.exe From Consuming Too Much CPU in Windows 10"
excerpt: "This Article Describes Optimizing System Performance: Stop svchost.exe From Consuming Too Much CPU in Windows 10"
thumbnail: https://thmb.techidaily.com/2738dcb65655ca3023848f9ec7026a9cce211e70815a31f4f65d2f9ea9ded629.jpg
---

## Tackling High CPU Drain by svchost.exe on Windows 11: Solved

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### **What is svchost.exe?**

 According to Microsoft,**svchost.exe** is:

> “a generic host process name for services that run from dynamic-link libraries”.

 In simpler words, it’ s a legitimate Windows process when running certain Windows operations. But in certain cases, you may see the **svchost.exe**  process hogging the CPU or memory resources in **Task Manager**  without apparent reasons.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **How do I fix it?**

 Here are 4 solutions for you to try. You may not need to try them all; just work your way down until you find the one that works for you.

[**1: Scan your computer for viruses**](#1)

[**2: Disable certain svchost.exe services**](#2)

[**3: Empty event viewer log**](#3)

[**4: Troubleshoot Windows Updates issues**](#4)

## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1030129/11832" target="_top" id="1030129">
  <img src="//a.impactradius-go.com/display-ad/11832-1030129" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1030129/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657400/16446" target="_top" id="1657400">
  <img src="//a.impactradius-go.com/display-ad/16446-1657400" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657400/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151856/7443" target="_top" id="2151856">
  <img src="//a.impactradius-go.com/display-ad/7443-2151856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885947/19272" target="_top" id="1885947">
  <img src="//a.impactradius-go.com/display-ad/19272-1885947" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

## **PRO TIP**

 If, after trying the above, your PC is still hogging by**svchost.exe** programs, it’s time to update your device drivers.

 If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21f9606b83.png)

 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398455/3022" target="_top" id="398455">
  <img src="//a.impactradius-go.com/display-ad/3022-398455" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398455/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-cutting-edge-text-tools-for-immersive-storytelling/"><u>[New] In 2024, Cutting-Edge Text Tools for Immersive Storytelling</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-from-raw-to-rad-turning-up-the-heat-with-snapchat-filters/"><u>[Updated] 2024 Approved From Raw to Rad Turning Up the Heat with Snapchat Filters</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-seamless-streaming-experience-a-youtube-playlist-creation-guide/"><u>2024 Approved Seamless Streaming Experience A YouTube Playlist Creation Guide</u></a></li>
<li><a href="https://fox-where.techidaily.com/boost-your-computers-precision-essential-windows-11-mouse-drivers-upgrade-guide/"><u>Boost Your Computer's Precision: Essential Windows 11 Mouse Drivers Upgrade Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-i-get-responses-with-different-sizes-in-gpt-based-systems/"><u>Can I Get Responses with Different Sizes in GPT-Based Systems?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/crucial-specification-verify-your-pc-features-a-compatible-d3d11-gpu-to-function/"><u>Crucial Specification: Verify Your PC Features a Compatible D3D11 GPU to Function</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-excessive-cpu-use-by-svchostexe-on-windows-11-complete-guide/"><u>Fixing Excessive CPU Use by svchost.exe on Windows 11 - Complete Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-honor-magic-6-lite-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Honor Magic 6 Lite Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-turn-on-a-shut-down-network-adapter-and-solve-wi-fi-problems/"><u>How to Turn On a Shut Down Network Adapter and Solve Wi-Fi Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/identifying-the-cause-of-random-device-shutdowns-troubleshooting-steps-inside-out/"><u>Identifying the Cause of Random Device Shutdowns: Troubleshooting Steps Inside Out</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-gamecast-viewers-take/"><u>In 2024, GameCast Viewer's Take</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-windows-permissions-how-to-get-clearance-for-changing-files-by-trustedinstaller/"><u>Navigating Windows Permissions: How to Get Clearance for Changing Files by TrustedInstaller</u></a></li>
<li><a href="https://win-howtos.techidaily.com/nba-2k21-fixes-green-currency-bug-update-details-revealed/"><u>NBA 2K21 Fixes Green Currency Bug - Update Details Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/need-help-brightness-levels-unavailable-on-windows/"><u>Need Help: Brightness Levels Unavailable on Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/protect-yourself-from-surveillance-identifying-whether-apples-airtag-is-following-you/"><u>Protect Yourself From Surveillance: Identifying Whether Apple's AirTag Is Following You.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revitalizing-your-pc-with-sfc-and-dism-expert-windows-10-restoration-techniques/"><u>Revitalizing Your PC with SFC & DISM: Expert Windows 10 Restoration Techniques</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/safely-remove-confidential-data-from-your-iphone-with-our-advanced-wiping-software/"><u>Safely Remove Confidential Data From Your iPhone with Our Advanced Wiping Software</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-apple-iphone-12-mini-by-drfone-ios/"><u>Top 11 Free Apps to Check IMEI on Apple iPhone 12 mini</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205355136-ultimate-upgrade-witness-your-devices-accelerated-performance-now/"><u>Ultimate Upgrade: Witness Your Device's Accelerated Performance Now!</u></a></li>
</ul></div>

