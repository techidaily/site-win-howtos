---
title: Script Execution Prevented
date: 2025-01-08T16:18:13.922Z
updated: 2025-01-13T16:24:31.175Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Script Execution Prevented
excerpt: This Article Describes Script Execution Prevented
thumbnail: https://thmb.techidaily.com/744014ffd50adb1d07a7a2940727b9c6e249d35c9b35474b3c5a660491ebe0a3.png
---

## Svchost.exe CPU Hogs in Windows 10? Discover Efficient Solutions for Immediate Relief

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-helps.techidaily.com/new-in-2024-premier-platform-for-seminar-titles/"><u>[New] In 2024, Premier Platform for Seminar Titles</u></a></li>
<li><a href="https://win-cloud.techidaily.com/best-practices-in-pairing-your-pc-with-windows-10-the-file-synchronization-duo-explained/"><u>Best Practices in Pairing Your PC with Windows 10 - The File Synchronization Duo Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dell-laptop-fix-how-to-restore-proper-functionality-of-fn-keys/"><u>Dell Laptop Fix: How to Restore Proper Functionality of Fn Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-windows-11s-notorious-red-screen-anomaly/"><u>Diagnosing and Repairing Windows 11'S Notorious Red Screen Anomaly</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/harness-power-of-persuasion-with-these-tips-for-reddit-for-2024/"><u>Harness Power of Persuasion with These Tips for Reddit for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-language-liberation-discover-the-top-25-apps-for-flawless-video-conversion/"><u>In 2024, Language Liberation Discover the Top 25 Apps for Flawless Video Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-exception-handling-breaking-point-solution/"><u>Mastering Windows Exception Handling: Breaking Point Solution</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-essential-list-top-10-costless-online-daw-options-to-explore/"><u>New In 2024, Essential List Top 10 Costless Online DAW Options to Explore</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-reset-failed-errors-during-a-windows-11-system-recovery/"><u>Overcoming 'Reset Failed' Errors During a Windows 11 System Recovery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-adobe-shockwave-flash-disruptions-in-google-chrome-expert-solutions/"><u>Overcoming Adobe Shockwave Flash Disruptions in Google Chrome: Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rev-up-your-soundscape-overcoming-sound-challenges-in-forza-horizon-4/"><u>Rev Up Your Soundscape: Overcoming Sound Challenges in Forza Horizon 4</u></a></li>
<li><a href="https://driver-install.techidaily.com/sync-drivers-ensuring-smooth-operation-of-hp-printer-on-win-os/"><u>Sync Drivers: Ensuring Smooth Operation of HP Printer on Win OS</u></a></li>
<li><a href="https://os-tips.techidaily.com/the-ultimate-guide-fix-your-unresponsive-facetime-connection-with-these-simple-6-steps/"><u>The Ultimate Guide: Fix Your Unresponsive FaceTime Connection with These Simple 6 Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-nonfunctional-surface-pen/"><u>Troubleshooting Guide: Fixing a Nonfunctional Surface Pen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolve-no-signal-screen-issue-detailed-steps/"><u>Troubleshooting Guide: Resolve 'No Signal' Screen Issue - Detailed Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-infamous-google-chrome-black-screen-tips-and-solutions/"><u>Troubleshooting the Infamous Google Chrome Black Screen: Tips & Solutions</u></a></li>
<li><a href="https://ai-video.techidaily.com/updated-in-2024-best-video-language-changers-to-make-your-videos-accessible/"><u>Updated In 2024, Best Video Language Changers to Make Your Videos Accessible</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-video-editing-dilemma-final-cut-pro-or-lumafusion-weve-got-the-answer/"><u>Updated Video Editing Dilemma? Final Cut Pro or LumaFusion - Weve Got the Answer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-windows-1ers-0x80072efd-error-unravel-the-mystery-and-solve-it-today/"><u>Winning Against Windows 1Er’s 0X80072EFD Error: Unravel the Mystery and Solve It Today</u></a></li>
</ul></div>

