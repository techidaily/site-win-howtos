---
title: Troubleshooting High CPU Consumption by MsMpEng.exe on Windows 10 [COMPLETED]
date: 2024-08-19T06:33:19.754Z
updated: 2024-08-20T06:33:19.754Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting High CPU Consumption by MsMpEng.exe on Windows 10 [COMPLETED]
excerpt: This Article Describes Troubleshooting High CPU Consumption by MsMpEng.exe on Windows 10 [COMPLETED]
thumbnail: https://thmb.techidaily.com/72f83f594e8347a65931f8cd6726d7752e9fa455ebb805c1df40ab92a9a832b1.jpg
---

## Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-web.techidaily.com/nveiling-the-seven-best-youtube-live-streaming-tools-for-iphoneandroid/"><u>[New] Unveiling  The Seven Best YouTube Live Streaming Tools for iPhone/Android</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solvedyour-device-driver-is-not-compatible-in-wow/"><u>[SOLVED]Your Device Driver Is Not Compatible in WoW</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-4-seamless-steps-to-posting-and-uploading-gifs-on-instagram/"><u>[Updated] 4 Seamless Steps to Posting & Uploading GIFs on Instagram</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-acid-pro-analysis-and-related-tools-reviewed/"><u>[Updated] ACID Pro Analysis and Related Tools Reviewed</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-bridging-platforms-loop-ready-setups-for-youtube-and-tv/"><u>[Updated] Bridging Platforms  Loop-Ready Setups for YouTube and TV</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-innovative-tools-for-cutting-edge-xbox-gaming-recordings/"><u>[Updated] In 2024, Innovative Tools for Cutting-Edge Xbox Gaming Recordings</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-quick-and-simple-adding-youtube-songs-to-imovie-edit/"><u>[Updated] Quick and Simple  Adding Youtube Songs to iMovie Edit</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ace-your-installation-correcting-setup-hiccups-in-origin-games/"><u>Ace Your Installation: Correcting Setup Hiccups in Origin Games</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clear-troubles-away-how-to-successfully-address-and-remove-google-chromes-urgent-error-warning/"><u>Clear Troubles Away: How to Successfully Address and Remove Google Chrome's Urgent Error Warning</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-the-persistent-dxgkrnl-error-in-your-windows-videos/"><u>Effective Fixes for the Persistent Dxgkrnl Error in Your Window's Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-the-wwe-2k-battlegrounds-feature-level-100-directx-errors/"><u>Effective Solutions for the WWE 2K: Battlegrounds Feature Level 10.0 DirectX Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208522822-effortless-solutions-for-the-sudden-loss-of-bluetooth-on-windows-10/"><u>Effortless Solutions for the Sudden Loss of Bluetooth on Windows 10!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-guide-to-addressing-event-141-hardware-faults-2024/"><u>Essential Guide to Addressing Event 141 Hardware Faults, 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/essential-pitfalls-crafting-perfect-text-with-chatgpt/"><u>Essential Pitfalls: Crafting Perfect Text with ChatGPT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expanding-rdr2-storage-space-how-to-avoid-page-file-size-errors-efficiently/"><u>Expanding RDR2 Storage Space: How to Avoid Page File Size Errors Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206076732-fix-hp-keyboard-issues-fast-solutions-for-unresponsive-laptop-buttons/"><u>Fix HP Keyboard Issues Fast - Solutions for Unresponsive Laptop Buttons!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-night-light-feature-solutions-when-it-fails-in-windows-10-and-11/"><u>Fixing the Night Light Feature: Solutions When It Fails in Windows 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-windows-10-stuck-update-problems-easily/"><u>How to Overcome Windows 10 Stuck Update Problems Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-a-faulty-usb-connection-unknown-device-port-reset-failure-in-windows-10/"><u>How to Repair a Faulty USB Connection (Unknown Device - Port Reset Failure) in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-malfunctioning-buttons-in-microsofts-latest-operating-systems/"><u>How to Repair Malfunctioning Buttons in Microsoft's Latest Operating Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-firefox-screen-recorders-and-add-ons/"><u>In 2024, Firefox Screen Recorders and Add-Ons</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/install-latest-driver-for-logitech-mouse-windows-11/"><u>Install Latest Driver for Logitech Mouse (Windows 11)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-your-pubg-gameplay-avoid-incomplete-buildings-issue/"><u>Optimizing Your PUBG Gameplay: Avoid Incomplete Buildings Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-age-of-empires-3-launch-problems-a-comprehensive-guide/"><u>Overcoming Age of Empires 3 Launch Problems: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-chromes-inaccessible-webpage-dilemma/"><u>Overcoming Chrome's Inaccessible Webpage Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-ensuring-continuous-functionality-for-windows-updates/"><u>Resolved! Ensuring Continuous Functionality for Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-non-functional-issues-with-hp-laptop-trackpad/"><u>Resolving Non-Functional Issues with HP Laptop Trackpad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-couldnt-load-plugin-issue-in-google-chrome-on-windows-10-a-comprehensive-guide/"><u>Resolving the 'Couldn't Load Plugin' Issue in Google Chrome on Windows 10 - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-critical-error-and-preventing-halo-4-game-crashes-on-unreal-engine-4-release/"><u>Resolving the Critical Error and Preventing Halo 4 Game Crashes on Unreal Engine 4 Release</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-typing-troubles-overcoming-spacebar-malfunctions-in-windows-11/"><u>Resolving Typing Troubles: Overcoming Spacebar Malfunctions in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-tech-essential-strategies-for-repairing-damaged-computers-and-devices/"><u>Revive Your Tech: Essential Strategies for Repairing Damaged Computers and Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-windows-bad-graphics-drivers-causing-frequent-minecraft-game-crashes/"><u>Solve Window's Bad Graphics Drivers Causing Frequent Minecraft Game Crashes</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-alan-wake-iis-unavailable-status-a-step-by-step-guide/"><u>Solving Alan Wake II's Unavailable Status - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-persistent-crashes-in-necromunda-hired-gun-for-windows-users/"><u>Solving Persistent Crashes in 'Necromunda: Hired Gun' For Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-error-in-your-steam-game-update-process/"><u>Solving the 'Error' In Your Steam Game Update Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-unintended-characters-while-typing/"><u>Solving the Issue of Unintended Characters While Typing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-of-the-ghostly-white-pixels-on-your-computer-monitor/"><u>Solving the Mystery of the Ghostly White Pixels on Your Computer Monitor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-10-setup-issues-overcoming-initialization-problems-with-ease/"><u>Solving Windows 10 Setup Issues: Overcoming Initialization Problems with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-take-if-your-pc-runs-into-issues-with-windows-11/"><u>Steps to Take if Your PC Runs Into Issues with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-total-war-rome-remastered-heres-how-you-can-stabilize-it/"><u>Trouble with Total War: Rome Remastered? Here's How You Can Stabilize It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-overwatch-voice-chatting-fast-and-effective-solutions/"><u>Troubleshoot Overwatch Voice Chatting: Fast & Effective Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repairing-black-monitor-issues-in-dell-computers-a-comprehebiate-guide/"><u>Troubleshooting and Repairing Black Monitor Issues in Dell Computers - A Comprehebiate Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-fix-a-non-responsive-bluetooth-keyboard-connection-with-your-computer/"><u>Troubleshooting Guide: How to Fix a Non-Responsive Bluetooth Keyboard Connection with Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-successfully-completed-no-more-failed-to-initialize-network-in-dbfz/"><u>Troubleshooting Successfully Completed: No More 'Failed to Initialize Network' In DBFZ</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-techniques-for-overcoming-opengl-hiccups-in-minecraft/"><u>Troubleshooting Techniques for Overcoming OpenGL Hiccups in Minecraft</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-fixing-a-non-functional-wacom-stylus-on-windows-11-or-windows-10/"><u>Troubleshooting Tips: Fixing a Non-Functional Wacom Stylus on Windows 11 or Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208077072-ultimate-strategy-eradicate-your-livekernelevent-144-issues-today/"><u>Ultimate Strategy: Eradicate Your LiveKernelEvent 144 Issues Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/uncover-the-solution-to-restore-gone-icons-on-your-windows-11-pc-easily/"><u>Uncover the Solution to Restore Gone Icons on Your Windows 11 PC Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unexpected-computer-restarts-causes-and-solutions-for-a-steady-performance/"><u>Unexpected Computer Restarts – Causes & Solutions for a Steady Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204341501-windows-update-quandary-breaking-through-when-progress-halts-at-100/"><u>Windows Update Quandary - Breaking Through When Progress Halts at 100%%!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-windowss-0x80070490-update-error-comprehensive-fix-strategies/"><u>Winning Against Windows's 0X80070490 Update Error: Comprehensive Fix Strategies</u></a></li>
</ul></div>
