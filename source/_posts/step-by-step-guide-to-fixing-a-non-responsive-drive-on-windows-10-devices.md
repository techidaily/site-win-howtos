---
title: Step-by-Step Guide to Fixing a Non-Responsive Drive on Windows 10 Devices
date: 2024-08-19T06:47:57.289Z
updated: 2024-08-20T06:47:57.289Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Guide to Fixing a Non-Responsive Drive on Windows 10 Devices
excerpt: This Article Describes Step-by-Step Guide to Fixing a Non-Responsive Drive on Windows 10 Devices
thumbnail: https://thmb.techidaily.com/9042a37d5d2c8af9496ec8a51e895c3285abaf5142ec54106a5ba432af4fcf01.jpg
---

## Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
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
<li><a href="https://win-howtos.techidaily.com/fixed-unplanned-windows-interruption-curbs-cpu-usage/"><u>[FIXED] Unplanned Windows Interruption Curbs CPU Usage</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-expressive-authenticity-learning-to-alter-voice-on-ig/"><u>[New] Expressive Authenticity  Learning to Alter Voice on IG</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-the-complete-breakdown-of-downloading-status-videos-on-fb/"><u>[Updated] 2024 Approved  The Complete Breakdown of Downloading Status Videos on Fb</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-how-to-pin-someone-on-snapchat-all-you-need-to-know/"><u>[Updated] How to Pin Someone on Snapchat  All You Need to Know</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-step-by-step-guide-to-defining-your-aesthetic-for-2024/"><u>[Updated] Step-by-Step Guide to Defining Your Aesthetic for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-pathway-to-popular-youtube-thumbnails-mac-edition/"><u>[Updated] The Pathway to Popular Youtube Thumbnails  Mac Edition</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-premium-aerial-camera-crew-the-best-10-drones/"><u>2024 Approved  Premium Aerial Camera Crew  The Best 10 Drones</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-zoom-optimization-coordinating-remote-gatherings/"><u>2024 Approved  Zoom Optimization  Coordinating Remote Gatherings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avoid-rdr2-crashes-due-to-high-memory-usage-tips-on-increasing-your-pagefile-size/"><u>Avoid RDR2 Crashes Due to High Memory Usage - Tips on Increasing Your Pagefile Size</u></a></li>
<li><a href="https://win-howtos.techidaily.com/can-you-watch-netflix-right-now-how-to-check-for-service-interruptions/"><u>Can You Watch Netflix Right Now? How to Check for Service Interruptions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-walkthrough-correcting-windows-10s-troubling-update-bug-0x80240034/"><u>Complete Walkthrough: Correcting Windows 10'S Troubling Update Bug 0X80240034</u></a></li>
<li><a href="https://win-howtos.techidaily.com/connectivity-issue-blizzard-downed/"><u>Connectivity Issue: Blizzard Downed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/destiny-2-launch-issue-resolved-conquering-the-persistent-initializing-error/"><u>Destiny 2 Launch Issue Resolved: Conquering the Persistent Initializing Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-the-youtube-sound-output-issue-in-windows-11-environments/"><u>Diagnosing & Fixing the Youtube Sound Output Issue in Windows 11 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-for-dealing-with-hang-ups-in-windows-10/"><u>Effective Strategies for Dealing with Hang-Ups in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effectively-decreasing-high-cpu-demands-in-wdf-based-systems/"><u>Effectively Decreasing High CPU Demands in WDF-Based Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202021194-expert-advice-on-correcting-windows-update-failure-with-error-code-0x8024402c-learn-how-here/"><u>Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-diagnosing-and-correcting-the-0x80072efd-glitch-in-windows-11-systems/"><u>Expert Advice on Diagnosing and Correcting the 0X80072EFD Glitch in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-troubleshooting-and-overcoming-windows-mysterious-blackout-problems/"><u>Expert Tips on Troubleshooting and Overcoming Windows' Mysterious Blackout Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hid-integrity-rectified-missing-touch-element/"><u>HID Integrity: Rectified Missing Touch Element</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-apple-iphone-se-2022-location-is-wrong-drfone-by-drfone-virtual-ios/"><u>How to Fix My Apple iPhone SE (2022) Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-passcode-from-apple-iphone-11-complete-guide-drfone-by-drfone-ios/"><u>How To Remove Passcode From Apple iPhone 11? Complete Guide | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/issue-addressed-successfully-gaining-entry-where-once-rejected/"><u>Issue Addressed: Successfully Gaining Entry Where Once Rejected</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-white-screen-error-fixes-and-troubleshooting-steps-for-effective-solutions/"><u>Laptop White Screen Error Fixes and Troubleshooting Steps for Effective Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/latest-fixes-for-miracast-not-recognized-on-this-device/"><u>Latest Fixes for 'Miracast Not Recognized on This Device'</u></a></li>
<li><a href="https://extra-information.techidaily.com/lightning-fast-lore-resurrecting-reddit-articles-lost/"><u>Lightning-Fast Lore  Resurrecting Reddit Articles Lost</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-quick-remedies-for-easy-anti-cheat-troubles-in-apee-legends/"><u>Master the Quick Remedies for Easy Anti-Cheat Troubles in Apee Legends</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210046270-persistent-windows-update-problems-heres-what-you-need-to-do/"><u>Persistent Windows Update Problems? Here's What You Need To Do!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-2024-troubleshooting-a-comprehensive-guide-on-fixing-startup-issues/"><u>PUBG 2024 Troubleshooting: A Comprehensive Guide on Fixing Startup Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-construction-errors-how-to-ensure-complete-building-loads/"><u>PUBG Construction Errors: How to Ensure Complete Building Loads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-hurdles-during-steam-game-update-installations/"><u>Resolving Hurdles During Steam Game Update Installations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/sfc-and-dism-windows-10-repair-options/"><u>SFC and DISM: Windows 10 Repair Options</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-11-screen-interaction-problems-five-essential-solutions/"><u>Solving Windows 11 Screen Interaction Problems: Five Essential Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-remedies-for-a-broken-usb-mouse-connection-on-your-notebook/"><u>Step-by-Step Remedies for a Broken USB Mouse Connection on Your Notebook</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-8-gold-text-wonders-in-the-vast-world-of-3d-sites-for-2024/"><u>Top 8 Gold-Text Wonders in the Vast World of 3D Sites for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/total-war-rome-remastered-how-to-fix-the-latest-game-crash-issues/"><u>Total War Rome Remastered - How To Fix The Latest Game Crash Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-arrow-keys-discover-easy-fixes-to-restore-functionality/"><u>Trouble with Arrow Keys? Discover Easy Fixes to Restore Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-repaired-minecraft-performance-lags/"><u>Troubleshooting & Resolving [REPAIRED] Minecraft Performance Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-stuck-spacebar-key-under-windows-10/"><u>Troubleshooting a Stuck Spacebar Key Under Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-the-expired-semaphore-time-limit-error-0x80070079/"><u>Troubleshooting and Repairing the Expired Semaphore Time Limit (Error 0X80070079)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-pubg-loads-failure-for-in-game-structures/"><u>Troubleshooting PUBG Loads Failure for In-Game Structures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-techniques-for-fixing-laptop-mouse-freezing-issues/"><u>Troubleshooting Techniques for Fixing Laptop Mouse Freezing Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-overcome-the-extended-semaphore-connection-timeout-error-code-0x80070079/"><u>Troubleshooting: Overcome the Extended Semaphore Connection Timeout (Error Code 0X80070079)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-repairing-the-0x80072efd-error-tips-and-tricks-for-windows-10-users/"><u>Understanding and Repairing the 0X80072EFD Error: Tips & Tricks for Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-wont-update-discover-the-steps-to-resolve-update-freezing-issues/"><u>Windows 10 Won’t Update? Discover the Steps to Resolve Update Freezing Issues</u></a></li>
</ul></div>
