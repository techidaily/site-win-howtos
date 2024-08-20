---
title: "[SOLVED] Explorer.exe Application Error on Windows 11/10"
date: 2024-08-19T06:44:02.514Z
updated: 2024-08-20T06:44:02.514Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes [SOLVED] Explorer.exe Application Error on Windows 11/10
excerpt: This Article Describes [SOLVED] Explorer.exe Application Error on Windows 11/10
thumbnail: https://thmb.techidaily.com/d9567f73a6de787d2d45f5ed6e24adff2914444a4a5e563757f01047c1bbc480.jpg
---

## Tackling High CPU Drain by svchost.exe on Windows 11: Solved

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

### **What is svchost.exe?**

 According to Microsoft,**svchost.exe** is:

> “a generic host process name for services that run from dynamic-link libraries”.

 In simpler words, it’ s a legitimate Windows process when running certain Windows operations. But in certain cases, you may see the **svchost.exe**  process hogging the CPU or memory resources in **Task Manager**  without apparent reasons.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
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

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-video-files.techidaily.com/new-enhance-ig-visuals-with-our-top-10-grid-making-tools-selection-for-2024/"><u>[New] Enhance IG Visuals with Our Top 10 Grid Making Tools Selection for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-funniest-faces-learning-kinemaster/"><u>[New] Funniest Faces  Learning KineMaster</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-get-your-tweets-right-comply-with-aspect-ratio-standards-for-2024/"><u>[New] Get Your Tweets Right  Comply with Aspect Ratio Standards for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-keyboard-lag-windows-10/"><u>[SOLVED] Keyboard Lag Windows 10</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-x-mix-master-pro-for-computer-users/"><u>[Updated] 2024 Approved  X-Mix Master Pro for Computer Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-translate-speech-to-text-the-right-way-with-google-translate/"><u>[Updated] In 2024, Translate Speech to Text the Right Way with Google Translate</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-balanced-flights-7-leading-gimbals-reviewed/"><u>2024 Approved  Balanced Flights  7 Leading Gimbals Reviewed</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-modern-techniques-record-idevice-screen-effortlessly/"><u>2024 Approved  Modern Techniques  Record iDevice Screen Effortlessly</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-vmix-mover-for-apple-and-pcs/"><u>2024 Approved  VMix Mover for Apple and PCs</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-oppo-find-n3-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/clarifying-misleading-self-representations-on-fb/"><u>Clarifying Misleading Self-Representations on FB</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fix-for-broken-usb-ports-on-hp-computers-a-user-friendly-tutorial/"><u>Comprehensive Fix for Broken USB Ports on HP Computers - A User-Friendly Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhanced-windows-drivers-lower-systems-cpu-load-fixes/"><u>Enhanced Windows Drivers Lower System's CPU Load Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-connect-your-airpods-to-windows-pcs-seamlessly-updated-solutions/"><u>Expert Advice: Connect Your AirPods to Windows PCs Seamlessly - Updated Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-connectivity-issues-for-aoc-usb-monitors-compatible-with-windows-10-systems/"><u>Fixing Connectivity Issues for AOC USB Monitors Compatible with Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-audio-device-missing-errors-in-windows-10-and-11-effective-solutions/"><u>Fixing Windows Audio Device Missing Errors in Windows 10 and 11: Effective Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-past-the-error-seamless-launch-of-new-worlds-latest-update-explained/"><u>Getting Past the Error: Seamless Launch of New World's Latest Update Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-fixing-unexpected-interruptions-during-windows-11-initialization-process/"><u>Guide to Fixing Unexpected Interruptions During Windows 11 Initialization Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-i-combat-and-correct-electrical-surges-throughout-my-devices-main-interface/"><u>How I Combat and Correct Electrical Surges Throughout My Device's Main Interface</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-oppo-reno-11f-5g-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Oppo Reno 11F 5G Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-hp-laptop-camera-not-working-in-windows-10/"><u>How To Fix HP Laptop Camera Not Working In Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-reinstall-and-configure-audio-drivers-in-windows-1011-when-no-sound-devices-are-recognized/"><u>How to Reinstall and Configure Audio Drivers in Windows 10/11 When No Sound Devices Are Recognized</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-to-a-broken-mic-on-your-computer-expert-tips/"><u>How to Restore Functionality to a Broken Mic on Your Computer - Expert Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-intermittent-wireless-mouse-failures-on-windows-1110-computers/"><u>How to Troubleshoot Intermittent Wireless Mouse Failures on Windows 11/10 Computers</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-understanding-audio-confluence-the-essence-of-crossfade/"><u>In 2024, Understanding Audio Confluence  The Essence of Crossfade</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-the-spotlight-overcoming-the-challenge-of-a-non-illuminated-razer-keyboard/"><u>In The Spotlight: Overcoming the Challenge of a Non-Illuminated Razer Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/monster-hunter-world-how-to-resolve-complete-blackout-at-game-onset/"><u>Monster Hunter: World – How to Resolve Complete Blackout at Game Onset</u></a></li>
<li><a href="https://win-howtos.techidaily.com/obs-streaming-hitch-lets-tackle-that-troublesome-black-screen-issue/"><u>OBS Streaming Hitch? Let’s Tackle That Troublesome Black Screen Issue!</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-vivo-y02t-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Vivo Y02T Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repair-guide-reactivating-night-light-feature-in-windows-11-operating-system/"><u>Repair Guide: Reactivating Night Light Feature in Windows 11 Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resetting-windows-11-made-easy-step-by-step-instructions-and-tips/"><u>Resetting Windows 11 Made Easy: Step-by-Step Instructions & Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-secure-connection-failure-issue-in-mozilla-firefox/"><u>Resolving the 'Secure Connection Failure' Issue in Mozilla Firefox</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-your-devices-critical-failure-the-red-screen-blueprint/"><u>Resolving Your Device's Critical Failure: The Red Screen Blueprint</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-broken-huion-pen-top-5-quick-fixes-for-immediate-relief/"><u>Revive Your Broken Huion Pen - Top 5 Quick Fixes for Immediate Relief</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-quick-access-menu-problems-with-this-step-by-step-windowplusshiftpluss-fix/"><u>Solve Your Quick Access Menu Problems with This Step-by-Step Window+Shift+S Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-to-eliminate-monitor-not-receiving-signal-issues/"><u>Step-by-Step Solutions to Eliminate 'Monitor Not Receiving Signal' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-configuration-yet-device-remains-quiet/"><u>Successful Configuration, Yet Device Remains Quiet</u></a></li>
<li><a href="https://some-guidance.techidaily.com/syncing-soundscapes-to-pixelated-portraits-for-2024/"><u>Syncing Soundscapes to Pixelated Portraits for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-ultimate-ig-music-companion/"><u>The Ultimate IG Music Companion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-connection-effective-ways-to-resolve-internet-disconnection-errors/"><u>Troubleshoot Your Connection: Effective Ways to Resolve Internet Disconnection Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-dealing-with-windows-cannot-access-device-paths/"><u>Troubleshooting Steps: Dealing with 'Windows Cannot Access Device Paths'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-what-to-do-when-your-dell-keyboard-stops-responding/"><u>Troubleshooting Tips: What to Do When Your Dell Keyboard Stops Responding</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-website-access-denied-errors-http-403/"><u>Ultimate Guide: Resolving Website Access Denied Errors (HTTP 403)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unleash-your-creative-edge-with-adjustable-story-videos/"><u>Unleash Your Creative Edge with Adjustable Story Videos</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-elevate-your-vlog-game-the-top-10-mobile-video-editing-apps/"><u>Updated 2024 Approved Elevate Your Vlog Game The Top 10 Mobile Video Editing Apps</u></a></li>
</ul></div>
