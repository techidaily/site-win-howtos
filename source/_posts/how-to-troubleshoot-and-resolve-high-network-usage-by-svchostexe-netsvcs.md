---
title: How to Troubleshoot & Resolve High Network Usage by svchost.exe NETSVCS
date: 2024-08-15T11:21:54.074Z
updated: 2024-08-16T11:21:54.074Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Troubleshoot & Resolve High Network Usage by svchost.exe NETSVCS
excerpt: This Article Describes How to Troubleshoot & Resolve High Network Usage by svchost.exe NETSVCS
thumbnail: https://thmb.techidaily.com/b21b5439f80b1a102ace85a9da59aeae7943c3afff9ae70d9fb6a7745b13a600.jpg
---

## Win 10 High CPU Drain by svchost.exe? Here’s How to Optimize It

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

### **What is svchost.exe?**

 According to Microsoft,**svchost.exe** is:

> “a generic host process name for services that run from dynamic-link libraries”.

 In simpler words, it’ s a legitimate Windows process when running certain Windows operations. But in certain cases, you may see the **svchost.exe**  process hogging the CPU or memory resources in **Task Manager**  without apparent reasons.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **PRO TIP**

 If, after trying the above, your PC is still hogging by**svchost.exe** programs, it’s time to update your device drivers.

 If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21f9606b83.png)

 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
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
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-convert-youtube-tracks-to-mp3-safely-the-3-best-ways-for-2024/"><u>[New] How To Convert YouTube Tracks to MP3 Safely - The 3 Best Ways for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-video-editor-battle-is-inshot-reigning-supreme/"><u>[New] Top Video Editor Battle  Is InShot Reigning Supreme?</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-crafting-atmospheres-with-cinematic-hues/"><u>[Updated] Crafting Atmospheres with Cinematic Hues</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-elevate-your-video-storytelling-on-tiktok-with-5-key-caption-techniques-for-2024/"><u>[Updated] Elevate Your Video Storytelling on TikTok With 5 Key Caption Techniques for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-undead-uprising-top-8-unleashed-in-video-game-realm/"><u>[Updated] Undead Uprising - Top 8 Unleashed in Video Game Realm</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-explore-the-difference-basic-plus-and-pro-in-vimeo-services/"><u>2024 Approved  Explore The Difference  Basic, Plus & Pro in Vimeo Services</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-infallible-steps-to-tiktok-bio-link-integration-without-error/"><u>2024 Approved  Infallible Steps to TikTok Bio-Link Integration Without Error</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-understanding-instagram-video-count-constraints/"><u>2024 Approved  Understanding Instagram  Video Count Constraints</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-startup-blues-effective-ways-to-resolve-freezing-problems-in-your-windows-10-system/"><u>Beat Startup Blues: Effective Ways to Resolve Freezing Problems in Your Windows 10 System</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-mkv-solvers-on-macos-for-2024/"><u>Best MKV Solvers on macOS for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210348631-bypass-the-missing-bluetooth-hurdle-on-windows-10-effective-tips-and-tricks-inside/"><u>Bypass the 'Missing Bluetooth' Hurdle on Windows 10: Effective Tips & Tricks Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decrease-system-load-in-windows-11-by-tackling-svchostexes-excessive-cpu-utilization-a-practical-guide/"><u>Decrease System Load in Windows 11 by Tackling svchost.exe's Excessive CPU Utilization - A Practical Guide</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-best-8-no-cost-music-apps-on-your-iphone-today/"><u>Discover the Best 8 No-Cost Music Apps on Your iPhone Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-synaptics-touchpad-not-responding-to-scroll-gestures-on-windows-11/"><u>Effective Solutions for Synaptics Touchpad Not Responding to Scroll Gestures on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0x80072f8f-on-windows-11-and-10-comprehensive-troubleshooting-guide/"><u>Error 0X80072F8F on Windows 11 & 10: Comprehensive Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-fixes-for-windows-11-users-with-unresponsive-airpods-latest-strategies/"><u>Essential Fixes for Windows 11 Users with Unresponsive AirPods - Latest Strategies</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-harmony-sourcing-perfect-dj-video-templates-for-2024/"><u>Event Harmony  Sourcing Perfect DJ Video Templates for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/exclusive-overlooked-the-creme-de-la-creme-mac-transcribers/"><u>Exclusive, Overlooked  The Crème De La Crème Mac Transcribers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-solutions-to-failed-to-update-messages-in-warframe-now-resolved/"><u>Expert Solutions to 'Failed to Update' Messages in Warframe – Now Resolved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-non-responsive-huion-pen-instantly-with-these-5-tips/"><u>Fix Your Non-Responsive Huion Pen Instantly with These 5 Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207235478-fix-your-overwatch-chatter-breakdowns-effortlessly-with-these-tricks/"><u>Fix Your Overwatch Chatter-Breakdowns Effortlessly with These Tricks!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-tutorial-to-bypass-your-htc-u23-pro-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your HTC U23 Pro Face Lock?</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-does-atandt-handle-international-roaming-services/"><u>How Does AT&T Handle International Roaming Services?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-pairing-process-how-to-get-your-airpods-working-on-windows-11-latest-fixes/"><u>Master the Pairing Process: How to Get Your AirPods Working on Windows 11 – Latest Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-art-of-fixing-broken-system-components-and-registry-issues-in-windows-1011/"><u>Mastering the Art of Fixing Broken System Components and Registry Issues in Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mouse-cursor-disappears-on-windows-11-solved/"><u>Mouse Cursor Disappears on Windows 11 [Solved]</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-how-to-improve-sound-quality-on-a-home-recorded-video-for-2024/"><u>New How to Improve Sound Quality on a Home Recorded Video for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-league-of-legends-lag-speedy-solutions-for-downloads-and-more/"><u>Overcome League of Legends Lag: Speedy Solutions for Downloads and More</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-startup-problems-solutions-for-your-computer-failed-to-boot/"><u>Overcoming Startup Problems: Solutions for 'Your Computer Failed to Boot'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-wacom-tablet-challenges-step-by-step-fixes-for-non-working-devices/"><u>Overcoming Wacom Tablet Challenges: Step-by-Step Fixes for Non-Working Devices</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-apple-iphone-15-and-browser-drfone-by-drfone-virtual-ios/"><u>Prevent Cross-Site Tracking on Apple iPhone 15 and Browser | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-wont-start-expert-troubleshooting-steps-for-the-latest-update-2024/"><u>PUBG Won't Start? Expert Troubleshooting Steps for the Latest Update - 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-when-your-hp-laptops-keys-stop-functioning-correctly/"><u>Quick Solutions When Your HP Laptop's Keys Stop Functioning Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/random-key-dysfunction/"><u>Random Key Dysfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-no-audio-output-device-found-issue-on-your-windows-11-pc/"><u>Resolving the 'No Audio Output Device Found' Issue on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210260738-skyrim-stuck-on-loading-forever-heres-how-you-can-break-free/"><u>Skyrim Stuck on Loading Forever? Here’s How You Can Break Free</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-keyboard-malfunctions-a-guide-for-windows-11-7-and-8-users/"><u>Solving Keyboard Malfunctions: A Guide for Windows 11, 7, and 8 Users</u></a></li>
<li><a href="https://win-able.techidaily.com/step-by-step-fix-resolving-itunes-recognition-problems-for-your-iphone-in-windows-11/"><u>Step-by-Step Fix: Resolving iTunes Recognition Problems for Your iPhone in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-continuous-reboots-on-your-windows-11-pc/"><u>Step-by-Step Guide: Resolving Continuous Reboots on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/svchostexe-high-usage-problem-an-in-depth-look-at-netsvcs-services-and-effective-strategies-for-optimization/"><u>svchost.exe High Usage Problem: An In-Depth Look at Netsvcs Services & Effective Strategies for Optimization</u></a></li>
<li><a href="https://win-howtos.techidaily.com/system-idle-process-high-cpu-usage-solved/"><u>System Idle Process High CPU Usage [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-guide-for-restoring-function-keys-in-dell-laptops-tips-tricks-and-solutions/"><u>The Ultimate Guide for Restoring Function Keys in Dell Laptops: Tips, Tricks & Solutions.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208040703-troubleshoot-and-repair-resolving-keyboard-problems-on-hp-computers-fast/"><u>Troubleshoot & Repair: Resolving Keyboard Problems on HP Computers Fast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-pairing-problems-with-windows-11-bluetooth-devices-tips-and-tricks/"><u>Troubleshoot Pairing Problems with Windows 11 Bluetooth Devices, Tips and Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-high-network-latency-in-counter-strike-global-offensive/"><u>Troubleshooting High Network Latency in Counter-Strike Global Offensive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-invalid-directory-paths-for-optimal-site-functionality/"><u>Troubleshooting Invalid Directory Paths for Optimal Site Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unveiling-the-mystery-of-msda80dll-essential-for-your-pc/"><u>Unveiling the Mystery of MSDA80.DLL - Essential for Your PC?</u></a></li>
<li><a href="https://techtrends.techidaily.com/usb-20-demystified-an-in-depth-look-at-transfer-rates-cord-types-and-plug-ins/"><u>USB 2.0 Demystified: An In-Depth Look at Transfer Rates, Cord Types & Plug-Ins</u></a></li>
<li><a href="https://extra-resources.techidaily.com/winning-at-movie-watching-leading-windows-phone-apps/"><u>Winning at Movie Watching  Leading Windows Phone Apps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wow-reimagined-thriving-with-advanced-3d-graphics/"><u>WoW Reimagined: Thriving with Advanced 3D Graphics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wwe-2k-fixing-and-understanding-the-issue-with-the-dx11-feature-level-100-problem/"><u>WWE 2K: Fixing and Understanding the Issue with the DX11 Feature Level 10.0 Problem</u></a></li>
</ul></div>
