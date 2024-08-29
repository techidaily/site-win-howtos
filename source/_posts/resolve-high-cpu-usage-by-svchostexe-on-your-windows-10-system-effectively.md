---
title: Resolve High CPU Usage by svchost.exe on Your Windows 10 System Effectively
date: 2024-08-28T00:24:44.073Z
updated: 2024-08-29T00:24:44.073Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolve High CPU Usage by svchost.exe on Your Windows 10 System Effectively
excerpt: This Article Describes Resolve High CPU Usage by svchost.exe on Your Windows 10 System Effectively
thumbnail: https://thmb.techidaily.com/934c09a684ad314c00e00ed21a2e7539ae4858551b2266da80c837988bee503d.jpg
---

## Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved

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
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
 4) Restart your computer after this.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://win-howtos.techidaily.com/fixed-step-by-step-solutions-for-rectifying-the-infamous-red-screen-malfunction/"><u>[FIXED] Step-by-Step Solutions for Rectifying the Infamous Red Screen Malfunction</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-the-digital-divide-demystifying-virtualitys-kin-mr-ar-and-vr-for-2024/"><u>[New] The Digital Divide  Demystifying Virtuality's Kin (MR, AR, & VR) for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-virtuscreen-clear-plastic-sheeting/"><u>[Updated] 2024 Approved  VirtuScreen Clear Plastic Sheeting</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-best-6-modern-homes-for-minecraft-enthusiasts/"><u>[Updated] In 2024, Best 6 Modern Homes for Minecraft Enthusiasts</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-10-viral-tweets-dominating-social-media/"><u>2024 Approved  10 Viral Tweets Dominating Social Media</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-dive-deep-into-the-digital-world-adding-panoramic-photos-to-your-feed/"><u>2024 Approved  Dive Deep Into the Digital World  Adding Panoramic Photos to Your Feed</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-gionee-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Gionee FRP Bypass Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/buffer-free-viewing-permanent-solution-to-kodis-playback-problem/"><u>Buffer-Free Viewing: Permanent Solution to Kodi's Playback Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-fixing-the-0x800705b4-issue-during-windows-11-updates/"><u>Comprehensive Guide: Fixing the 0X800705b4 Issue During Windows 11 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-to-get-your-embedded-webcam-working-again-in-windows/"><u>Comprehensive Solutions to Get Your Embedded Webcam Working Again in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/copy-pasting-woes-heres-how-to-fix-it-on-your-windows-11-machine/"><u>Copy-Pasting Woes? Here's How to Fix It on Your Windows 11 Machine</u></a></li>
<li><a href="https://tech-hub.techidaily.com/effective-techniques-for-leveraging-chatgpt-in-multilingual-translations/"><u>Effective Techniques for Leveraging ChatGPT in Multilingual Translations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-touchpad-to-respond-fixing-scroll-issues-effectively/"><u>Getting Your Touchpad to Respond: Fixing Scroll Issues Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723201428080-how-to-fix-oculus-hardware-error-2024/"><u>How to Fix Oculus Hardware Error - 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-the-sudden-stop-of-your-hamachi-service-a-users-handbook/"><u>How To Repair The Sudden Stop of Your Hamachi Service - A User's Handbook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-access-denied-by-device-path-error-in-windows-systems/"><u>How to Resolve the 'Access Denied by Device Path' Error in Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-constant-connectivity-for-a-frequently-dropping-mouse/"><u>How To Restore Constant Connectivity for a Frequently Dropping Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hp-laptops-unresponsive-keys-master-the-rapid-restoration-methods-today/"><u>HP Laptops' Unresponsive Keys? Master the Rapid Restoration Methods Today!</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/innovative-approaches-to-keeping-your-snaps-connected-for-2024/"><u>Innovative Approaches to Keeping Your Snaps Connected for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-malfunction-in-windows-11-heres-the-solution-to-unresponsive-characters/"><u>Keyboard Malfunction in Windows 11? Here's the Solution to Unresponsive Characters!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205526286-keyboard-trouble-heres-how-you-can-get-your-number-pad-back-in-action/"><u>Keyboard Trouble? Here's How You Can Get Your Number Pad Back in Action</u></a></li>
<li><a href="https://win-howtos.techidaily.com/masterful-solutions-for-handling-sudden-termination-in-windows-tackle-error-1067-efficiently/"><u>Masterful Solutions for Handling Sudden Termination in Windows - Tackle Error 1067 Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-fixes-for-error-code-0x800f0922-on-your-windows-10-system/"><u>Mastering Fixes for Error Code 0X800F0922 on Your Windows 10 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-library-absence-msvcr71/"><u>Overcoming Library Absence - MSVCR71</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-oppo-reno-11-pro-5g-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Oppo Reno 11 Pro 5G on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-audio-issues-fixing-the-logitech-g930-earbuds/"><u>Resolving Audio Issues: Fixing the Logitech G930 Earbuds</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-dll-dilemma-msvcr71/"><u>Resolving DLL Dilemma - MSVCR71</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-performance-lag-and-freezes-in-windows-10-operating-systems/"><u>Resolving Performance Lag and Freezes in Windows 10 Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-of-excessive-disk-space-consumed-by-microsoft-telemetry-in-windows-10/"><u>Resolving the Issue of Excessive Disk Space Consumed by Microsoft Telemetry in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-connection-refused-error-on-your-device-a-visual-guide/"><u>Solving the Issue of Connection Refused Error on Your Device – A Visual Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-windows-11-mic-troubles-expert-tips-for-restoring-voice-input/"><u>Tackling Windows 11 Mic Troubles - Expert Tips for Restoring Voice Input</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-tech-digest-insights-from-toms-hardware-chronicles/"><u>The Ultimate Tech Digest: Insights From Tom's Hardware Chronicles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-disk-read-errors-on-your-windows-10-pc-today/"><u>Troubleshoot and Fix Disk Read Errors on Your Windows 10 PC Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-getting-miracast-to-work-on-systems-with-incorrect-graphic-card-support/"><u>Troubleshoot and Fix: Getting Miracast to Work on Systems with Incorrect Graphic Card Support</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-laptop-that-wont-charge-simple-steps-for-an-immediate-fix/"><u>Troubleshooting a Laptop That Won't Charge: Simple Steps for an Immediate Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-audio-glitches-in-youtube-videos-on-windows-11/"><u>Troubleshooting and Fixing Audio Glitches in YouTube Videos on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-vanishing-touchpad-pointer-in-windows-11/"><u>Troubleshooting the Vanishing Touchpad Pointer in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-successful-activation-of-new-world-despite-easy-anti-cheat-glitches/"><u>Troubleshooting Tips: Successful Activation of New World Despite Easy Anti-Cheat Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-razer-keyboard-illumination-issues/"><u>Troubleshooting Your Razer Keyboard Illumination Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-successfully-complete-windows-installations/"><u>Troubleshooting: How To Successfully Complete Windows Installations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-windows-update-error-code-0x802eb3ae/"><u>Ultimate Guide: Resolving Windows Update Error Code 0X802eb3ae</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-might-a-windows-11-computer-begin-to-boot-automatically/"><u>Why Might a Windows 11 Computer Begin to Boot Automatically?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win11s-efficiency-upgrade-lowering-provider-host-cpu-load/"><u>Win11's Efficiency Upgrade: Lowering Provider Host CPU Load</u></a></li>
</ul></div>
