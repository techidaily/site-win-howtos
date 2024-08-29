---
title: How to Fix svchost.exe Consuming Too Much CPU in Windows 10
date: 2024-08-28T00:36:28.688Z
updated: 2024-08-29T00:36:28.688Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix svchost.exe Consuming Too Much CPU in Windows 10
excerpt: This Article Describes How to Fix svchost.exe Consuming Too Much CPU in Windows 10
thumbnail: https://thmb.techidaily.com/8e1219109f6e569a973b3c46c3d9e23c1f4eabc6e42aa2cadb4595040f5c4520.jpg
---

## Win 10 High CPU Drain by svchost.exe? Here’s How to Optimize It

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

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
 4) Restart your computer after this.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-bridge-the-gap-between-viewers-and-wide-angles-posting-on-facebook/"><u>[New] 2024 Approved  Bridge the Gap Between Viewers and Wide Angles  Posting on Facebook</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-channel-success-story-turning-budget-into-brands/"><u>[New] 2024 Approved  Channel Success Story  Turning Budget Into Brands</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-navigating-instagrams-video-landscape-a-detailed-look-for-2024/"><u>[New] Navigating Instagram's Video Landscape  A Detailed Look for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/solved-logitech-c615-driver-issues-quickly-and-easily/"><u>[SOLVED] Logitech C615 Driver Issues| Quickly & Easily</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-viral-potential-in-tiktok-unboxer-videos/"><u>[Updated] Mastering Viral Potential in TikTok Unboxer Videos</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-social-media-savvy-how-to-download-status-vids-on-fb/"><u>[Updated] Social Media Savvy  How to Download Status Vids on FB</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-pc-configurations-and-reviews-by-toms-technology-hub/"><u>Advanced PC Configurations & Reviews by Tom's Technology Hub</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-svchostexe-netsvcs-how-to-address-network-resource-drain-and-improve-system-performance/"><u>Decoding svchost.exe (Netsvcs): How to Address Network Resource Drain and Improve System Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-fix-overcoming-the-challenge-of-stuck-keys-in-your-window-based-keyboard/"><u>DIY Fix: Overcoming the Challenge of Stuck Keys in Your Window-Based Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-error-code-0x800f020b-during-your-xerox-update-on-pcs-running-windows/"><u>Expert Tips to Overcome Error Code 0X800F020B During Your Xerox Update on PCs Running Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hassle-free-methods-to-get-past-a-paused-0-windows-update-problem/"><u>Hassle-Free Methods to Get Past a Paused 0%% Windows Update Problem</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-fix-page-not-available-errors-on-chrome-browser/"><u>How to Fix 'Page Not Available' Errors on Chrome Browser</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-transforming-pedagogy-through-vr-innovation/"><u>In 2024, Transforming Pedagogy Through VR Innovation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-efficient-resource-usage-control-your-desktop-window-managers-gpu-demands-on-windows-1011/"><u>Mastering Efficient Resource Usage: Control Your Desktop Window Manager's GPU Demands on Windows 10/11</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-realme-narzo-60x-5g-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Realme Narzo 60x 5G.</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-realme-12-5g-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/proactive-zoom-meeting-strategies-for-improved-skype-interactions/"><u>Proactive Zoom Meeting Strategies for Improved Skype Interactions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-resolving-steam-cant-write-to-disk-issues/"><u>Quick Solutions: Resolving 'Steam Can't Write to Disk' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-access-denied-why-you-can-now-enter/"><u>Resolved: Access Denied – Why You Can Now Enter</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-identifying-and-fixing-windows-update-database-issues-on-windows-11/"><u>Resolved: Identifying and Fixing Windows Update Database Issues on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-unregistered-class-errors-on-your-windows-10-pc-solutions-inside/"><u>Resolving Unregistered Class Errors on Your Windows 10 PC - Solutions Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-lenovos-stuck-or-broken-fn-key-issue-quickly-and-efficiently/"><u>Solve Your Lenovo's Stuck or Broken Fn Key Issue Quickly & Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-permanent-lag-on-valorants-launch-screen-steps-for-a-smooth-start/"><u>Solved! Permanent Lag on Valorant's Launch Screen: Steps for a Smooth Start</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-of-unintended-letter-presses-during-typing/"><u>Solving the Problem of Unintended Letter Presses During Typing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-silent-issue-effective-solutions-to-make-corsair-hs50-speaker-mic-work-again/"><u>Solving the Silent Issue: Effective Solutions to Make Corsair HS50 Speaker Mic Work Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fixing-missing-audiovideo-drivers/"><u>Step-by-Step Guide to Fixing Missing Audio/Video Drivers!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-correcting-the-0x800705b4-error-during-windows-10-updates/"><u>Step-by-Step Solution: Correcting the 0X800705B4 Error During Windows 10 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-repairing-windows-11-pc-reset-errors-a-complete-guide/"><u>Successfully Repairing Windows 11 PC Reset Errors - A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-repair-touchpad-issues-on-windows-10-a-step-by-step-guide/"><u>Troubleshoot and Repair Touchpad Issues on Windows 10 – A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-astro-a40-microphone-issues/"><u>Troubleshooting Guide: Fixing Astro A40 Microphone Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-over-chrome-plugin-loading-problems-on-windows-10-a-comprehensive-guide/"><u>Winning Over Chrome Plugin Loading Problems on Windows 10 - A Comprehensive Guide</u></a></li>
</ul></div>
