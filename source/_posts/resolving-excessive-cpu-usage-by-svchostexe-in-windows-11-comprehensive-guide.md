---
title: Resolving Excessive Cpu Usage by svchost.exe in Windows 11 - Comprehensive Guide
date: 2024-09-26T00:30:53.492Z
updated: 2024-09-29T07:22:45.452Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Excessive Cpu Usage by svchost.exe in Windows 11 - Comprehensive Guide
excerpt: This Article Describes Resolving Excessive Cpu Usage by svchost.exe in Windows 11 - Comprehensive Guide
thumbnail: https://thmb.techidaily.com/6cbefc5821941765c64c748053e1b0a5829fef1524e233743a9045ce3a1167e9.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2049387/7443" target="_top" id="2049387">
  <img src="//a.impactradius-go.com/display-ad/7443-2049387" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049387/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **How do I fix it?**

 Here are 4 solutions for you to try. You may not need to try them all; just work your way down until you find the one that works for you.

[**1: Scan your computer for viruses**](#1)

[**2: Disable certain svchost.exe services**](#2)

[**3: Empty event viewer log**](#3)

[**4: Troubleshoot Windows Updates issues**](#4)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068433/7443" target="_top" id="2068433">
  <img src="//a.impactradius-go.com/display-ad/7443-2068433" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068433/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

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
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-amplifying-your-brand-the-famebit-approach-to-youtube-affiliates-for-2024/"><u>[New] Amplifying Your Brand The FameBit Approach to YouTube Affiliates for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-hero-vs-hero-a-technological-comparison-for-2024/"><u>[New] Hero Vs Hero A Technological Comparison for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-open-access-mindful-harmonies-for-2024/"><u>[Updated] Open Access Mindful Harmonies for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/connectivity-solutions-how-to-address-and-fix-a-broken-server-link/"><u>Connectivity Solutions: How to Address and Fix a Broken Server Link</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-bringing-back-your-shut-down-diagnostic-policy-service/"><u>Expert Tips on Bringing Back Your Shut Down Diagnostic Policy Service</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/hashtag-hacks-for-amplifying-gamer-content/"><u>Hashtag Hacks for Amplifying Gamer Content</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-motorola-moto-e13-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Motorola Moto E13 PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-audio-enhancement-for-online-video-creators/"><u>In 2024, Audio Enhancement for Online Video Creators</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-trackpad-troubleshooting-fixing-problems-on-windows-10-8-and-7/"><u>Laptop Trackpad Troubleshooting: Fixing Problems on Windows 10, 8 & 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/microsoft-print-to-pdf-not-working-in-windows-1011-heres-the-solution/"><u>Microsoft Print-to-PDF Not Working in Windows 10/11? Here's the Solution!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/missing-media-hardware-driver-restored-computer-functionality-enhanced/"><u>Missing Media Hardware Driver Restored, Computer Functionality Enhanced</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revolutionary-methods-to-stop-your-screens-blinding-blink-a-comprehensive-guide/"><u>Revolutionary Methods to Stop Your Screen's Blinding Blink: A Comprehensive Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/tutoriel-facile-pour-utiliser-le-kitkat-amazon-et-explorer-les-titres-librigoogle-au-format-ebook/"><u>Tutoriel Facile Pour Utiliser Le KitKat Amazon Et Explorer Les Titres LibriGoogle Au Format Ebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fixes-for-overcoming-the-0x80072efd-glitch-in-windows-11-systems/"><u>Ultimate Fixes for Overcoming the 0X80072EFD Glitch in Windows 11 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/unpacking-the-influential-four-a-deep-dive-into-facebook-twitter-instagram-and-youtube/"><u>Unpacking the Influential Four: A Deep Dive Into Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/usb-peripheral-troubles-restoring-mouse-and-keyboard-functionality-on-windows-7-computers/"><u>USB Peripheral Troubles: Restoring Mouse and Keyboard Functionality on Windows 7 Computers</u></a></li>
</ul></div>

