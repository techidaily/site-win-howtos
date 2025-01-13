---
title: "[Solved] Screen Flickering in Windows 11"
date: 2025-01-08T16:44:54.102Z
updated: 2025-01-13T16:41:03.243Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes [Solved] Screen Flickering in Windows 11
excerpt: This Article Describes [Solved] Screen Flickering in Windows 11
thumbnail: https://thmb.techidaily.com/9512aea1a507981ddcbdbe0823cb40f28338d2e0f0685c6e003300aac2dc1534.jpg
---

## Tackling High CPU Drain by svchost.exe on Windows 11: Solved

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-videos.techidaily.com/new-achieve-sharpness-camera-tips-without-a-tripod/"><u>[New] Achieve Sharpness Camera Tips Without a Tripod</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-combat-common-youtube-short-obstacles/"><u>[New] Combat Common YouTube Short Obstacles</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-your-words-powered-by-ai-free-of-cost/"><u>[Updated] 2024 Approved Your Words Powered by AI, Free of Cost</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-top-5-techniques-for-capturing-games-and-live-feeds-for-2024/"><u>[Updated] Top 5 Techniques for Capturing Games & Live Feeds for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-video-craft-decoding-filmora-questions/"><u>2024 Approved Mastering Video Craft Decoding Filmora Questions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723200653667-dell-laptop-keyboard-malfunction-heres-how-you-can-fix-it-quickly/"><u>Dell Laptop Keyboard Malfunction? Here's How You Can Fix It Quickly!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploiting-chatgpt-for-tailored-cognitive-behavioral-approaches/"><u>Exploiting ChatGPT for Tailored Cognitive Behavioral Approaches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-flickering-overcoming-brightness-problems-in-windows-10/"><u>Fixing the Flickering: Overcoming Brightness Problems in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-the-persistent-system-error-5-issue-across-various-windows-versions-fixed/"><u>How to Address the Persistent 'System Error 5' Issue Across Various Windows Versions [Fixed]</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-from-iphone-13-pro-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock From iPhone 13 Pro Online</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-filmora-coupon-code-2022-7-ways-to-find2022-full-list-for-2024/"><u>New Filmora Coupon Code 2022 - 7 Ways to Find(2022 Full List) for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-graphics-card-usage-by-desktop-window-manager-in-windows-1011-with-these-5-techniques/"><u>Resolve Excessive Graphics Card Usage by Desktop Window Manager in Windows 10/11 with These 5 Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/seamless-video-playback-on-kodi-master-the-art-of-fixing-buffering-woes/"><u>Seamless Video Playback on Kodi - Master the Art of Fixing Buffering Woes</u></a></li>
<li><a href="https://fox-that.techidaily.com/tackle-your-iphones-phantom-tap-issue-with-these-effective-10-techniques/"><u>Tackle Your iPhone's Phantom Tap Issue with These Effective 10 Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-casting-issues-how-to-fix-cannot-cast-to-device-errors-in-windows-11/"><u>Troubleshooting Casting Issues: How to Fix 'Cannot Cast to Device' Errors in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-non-functioning-integrated-webcams-in-windows/"><u>Ultimate Guide: Resolving Non-Functioning Integrated Webcams in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooting-guide-resolving-persistent-screen-freezes-on-your-pc/"><u>Ultimate Troubleshooting Guide: Resolving Persistent Screen Freezes on Your PC</u></a></li>
</ul></div>

