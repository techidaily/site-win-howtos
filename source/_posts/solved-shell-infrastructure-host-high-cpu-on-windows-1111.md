---
title: "[SOLVED] Shell Infrastructure Host High CPU on Windows 11/11"
date: 2024-08-15T11:32:00.913Z
updated: 2024-08-16T11:32:00.913Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes [SOLVED] Shell Infrastructure Host High CPU on Windows 11/11
excerpt: This Article Describes [SOLVED] Shell Infrastructure Host High CPU on Windows 11/11
thumbnail: https://thmb.techidaily.com/2dc71f07a766ca604beda3fe20bd5fd81321c87e0ac1f0a29af15d53f14e15af.jpg
---

## Tackling High CPU Drain by svchost.exe on Windows 11: Solved

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

### **What is svchost.exe?**

 According to Microsoft,**svchost.exe** is:

> “a generic host process name for services that run from dynamic-link libraries”.

 In simpler words, it’ s a legitimate Windows process when running certain Windows operations. But in certain cases, you may see the **svchost.exe**  process hogging the CPU or memory resources in **Task Manager**  without apparent reasons.

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
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
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
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->

## **PRO TIP**

 If, after trying the above, your PC is still hogging by**svchost.exe** programs, it’s time to update your device drivers.

 If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21f9606b83.png)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-expert-tips-for-creating-dynamic-youtube-splits-for-2024/"><u>[New] Expert Tips for Creating Dynamic YouTube Splits for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-unveiling-the-secrets-to-slow-motion-screenshots-in-snapchat-for-2024/"><u>[New] Unveiling the Secrets to Slow-Motion Screenshots in Snapchat for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-fb-media-migration-tools-for-windowsmacos-users/"><u>[Updated] 2024 Approved  FB Media Migration Tools for Windows/macOS Users</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-how-augmentation-changes-our-reality-view/"><u>[Updated] 2024 Approved  How Augmentation Changes Our Reality View</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-navigating-asmrs-influence-on-your-life/"><u>[Updated] In 2024, Navigating ASMR’s Influence on Your Life</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-optimizing-googles-automatic-speech-recognition-features/"><u>[Updated] Optimizing Google's Automatic Speech Recognition Features</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-step-by-step-guide-on-acquiring-elite-hdr-cameras/"><u>[Updated] Step-by-Step Guide on Acquiring Elite HDR Cameras</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-honor-magic-5-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Honor Magic 5? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avoid-overheating-in-your-hp-spectre-x360-top-techniques-for-cooler-performance/"><u>Avoid Overheating in Your HP Spectre X360: Top Techniques for Cooler Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-walkthrough-correcting-faulty-configuration-files-on-windows-1011/"><u>Complete Walkthrough: Correcting Faulty Configuration Files on Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-steps-to-solve-your-monitors-video-signal-failure/"><u>Comprehensive Steps to Solve Your Monitor's Video Signal Failure</u></a></li>
<li><a href="https://tech-haven.techidaily.com/craft-exclusive-gpts-for-you/"><u>Craft Exclusive GPTs for You</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-vivo-y77t-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Vivo Y77t Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dota-2-how-to-resolve-the-changerenderingapi-error-code-2024-quickly/"><u>Dota 2: How to Resolve the ChangeRenderingApi Error Code 2024 Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/end-the-frustration-of-a-machine-that-keeps-docking-into-slumber-mode/"><u>End the Frustration of a Machine That Keeps Docking Into Slumber Mode</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eradicate-your-valorant-screen-shake-or-tear-problem-now/"><u>Eradicate Your Valorant Screen Shake or Tear Problem Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-87-on-loadlibrary-how-to-fix-the-parameter-is-incorrect-issues/"><u>Error 87 on LoadLibrary: How to Fix 'The Parameter Is Incorrect' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolved-fixing-system-resources-too-low-issue/"><u>Error Resolved: Fixing 'System Resources Too Low' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-troubleshooting-and-solving-power-state-driver-mistakes-on-pc/"><u>Expert Advice: Troubleshooting and Solving Power State Driver Mistakes on PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-resolve-the-windows-camera-malfunction-code-0xa00f4292-explained/"><u>Expert Tips to Resolve the Windows Camera Malfunction: Code 0xA00f4292 Explained</u></a></li>
<li><a href="https://some-techniques.techidaily.com/front-rows-of-recreation-beyond-the-sports-arena-for-2024/"><u>Front Rows of Recreation Beyond the Sports Arena for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/hands-on-with-the-new-klipsch-flexus-200-soundbar/"><u>Hands On With the New Klipsch Flexus 200 Soundbar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-non-responsive-synaptics-touchpad-scroll-wheel-under-windows-10/"><u>How to Fix a Non-Responsive Synaptics Touchpad Scroll Wheel Under Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unresponsive-usb-connectors-in-windows-operating-systems-windows-10-11/"><u>How to Fix Unresponsive USB Connectors in Windows Operating Systems (Windows 10, 11)</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-flashlight-from-apple-iphone-12-pro-lock-screen-by-drfone-ios/"><u>How To Remove Flashlight From Apple iPhone 12 Pro Lock Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-the-mysterious-black-screen-error-in-your-google-chrome-browser/"><u>How to Repair the Mysterious Black Screen Error in Your Google Chrome Browser</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-how-to-change-honor-magic-5-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Honor Magic 5 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-depth-analysis-of-best-no-fee-livestream-options-on-all-devices/"><u>In-Depth Analysis of Best No-Fee LiveStream Options on All Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/instant-solutions-for-when-windows-11-wont-proceed-past-the-initial-display/"><u>Instant Solutions for When Windows 11 Won't Proceed Past the Initial Display</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-trackpad-not-functioning-heres-how-to-fix-it-on-windows-11-8-and-7-solved/"><u>Laptop Trackpad Not Functioning? Here's How to Fix It on Windows 11, 8 & 7 – SOLVED!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-uninterrupted-viewing-with-these-pro-solutions-for-fixing-kodis-buffers/"><u>Master Uninterrupted Viewing with These Pro Solutions for Fixing Kodi's Buffers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-airpod-connectivity-with-windows-11-advanced-solutions-for-a-seamless-experience/"><u>Mastering AirPod Connectivity with Windows 11: Advanced Solutions for a Seamless Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/maximize-your-pcs-potential-a-guide-to-faster-and-smoother-gaming-on-windows-11/"><u>Maximize Your PC's Potential: A Guide to Faster and Smoother Gaming on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-computer-performance-addressing-the-challenge-of-system-idle-process-cpu-spikes/"><u>Optimizing Computer Performance: Addressing the Challenge of System Idle Process CPU Spikes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-your-pcs-health-on-windows-10-via-system-file-checker-and-deployment-image-service-module-commands/"><u>Optimizing Your PC's Health on Windows 10 via System File Checker and Deployment Image Service Module Commands</u></a></li>
<li><a href="https://howto.techidaily.com/reasons-for-oneplus-ace-2v-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for OnePlus Ace 2V Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speedy-fixes-resolving-sluggish-startup-times-on-your-windows-7-pc/"><u>Speedy Fixes: Resolving Sluggish Startup Times on Your Windows 7 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-why-are-my-airpods-not-syncing-with-windows-11-tips/"><u>Step-by-Step Fixes: Why Are My AirPods Not Syncing with Windows 11? Tips</u></a></li>
<li><a href="https://screen-recording.techidaily.com/streaming-platforms-battle-evaluating-streamlabs-and-obs-features/"><u>Streaming Platforms Battle  Evaluating Streamlabs & OBS Features</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-motorola-moto-e13-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Motorola Moto E13 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-troubleshooting-tactics-for-driverpowerstatefailure/"><u>The Ultimate Troubleshooting Tactics for DRIVER_POWER_STATE_FAILURE</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-eliminate-kodis-buffering-problems-with-these-simple-fixes/"><u>Troubleshoot and Eliminate Kodi's Buffering Problems with These Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-nonfunctional-updown-arrows-on-your-keyboard-here/"><u>Troubleshoot Nonfunctional Up/Down Arrows on Your Keyboard Here</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-fix-windows-update-error-code-0x802n02e/"><u>Troubleshooting Guide: How to Fix Windows Update Error Code 0X802n02E</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-usb-mouse-issues-solutions-when-it-wont-connect-to-your-laptop/"><u>Troubleshooting USB Mouse Issues: Solutions When It Won't Connect to Your Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-the-reason-behind-teredos-inability-to-connect-successfully/"><u>Understanding the Reason Behind Teredo's Inability to Connect Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208089290-valorant-perpetual-boot-loop-heres-how-to-resolve-it/"><u>Valorant Perpetual Boot Loop? Here's How to Resolve It!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wired-back-to-life-logitech-mouse-restsore/"><u>Wired Back to Life: Logitech Mouse Restsore</u></a></li>
</ul></div>
