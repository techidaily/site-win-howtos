---
title: Script Execution Prevented
date: 2024-09-01T04:56:08.093Z
updated: 2024-09-02T04:56:08.093Z
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

## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Restart your computer after this.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-enhancing-productivity-with-efficient-nvidia-capture/"><u>[New] 2024 Approved  Enhancing Productivity with Efficient NVIDIA Capture</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-free-vimeo-tutorial-to-craft-engaging-videos/"><u>[New] 2024 Approved  Free Vimeo Tutorial to Craft Engaging Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-incorporating-secondary-footage-a-filmmakers-guide/"><u>2024 Approved  Incorporating Secondary Footage  A Filmmaker's Guide</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-transform-your-youtube-channel-url-in-minutes/"><u>2024 Approved  Transform Your YouTube Channel URL in Minutes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-to-eliminate-keyboard-response-delay-in-windows-11/"><u>Comprehensive Fixes to Eliminate Keyboard Response Delay in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-repair-your-dota-2-game-bug-change-rendering-api-error-solved-swiftly/"><u>Diagnose & Repair Your Dota 2 Game Bug: Change Rendering API Error Solved Swiftly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-when-your-diagnostic-policy-service-wont-start/"><u>Effective Solutions for When Your Diagnostic Policy Service Won’t Start</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-diagnosing-and-fixing-the-windows-10-error-code-0x80solved-how-to-fix-the-0x80072efd-error-in-windows-10-into-a-smoothly-running-system/"><u>Expert Tips for Diagnosing and Fixing the Windows 10 Error Code 0X80([Solved] How to Fix the 0X80072EFD Error in Windows 10 Into a Smoothly Running System</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-the-features-and-benefits-of-using-telegram-app/"><u>Exploring the Features and Benefits of Using Telegram App</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-for-failed-attempts-at-updating-to-the-windows-version-1903/"><u>Fixes for Failed Attempts at Updating to the Windows Version 1903</u></a></li>
<li><a href="https://win-howtos.techidaily.com/google-chrome-stops-working-heres-the-solution/"><u>Google Chrome Stops Working? Here's the Solution</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-sending-voicemails-with-your-iphone/"><u>Guide: Sending Voicemails with Your iPhone</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-oneplus-open-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from OnePlus Open Phones with/without a PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-nubia-red-magic-9-pro-by-fonelab-android-recover-photos/"><u>How To  Restore Missing Photos Files from Nubia Red Magic 9 Pro.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-freezing-windows-11-system-essential-troubleshooting-steps/"><u>How to Fix a Freezing Windows 11 System: Essential Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-prevent-your-touchpad-from-activating-with-a-mouse-in-windows-11/"><u>How to Prevent Your Touchpad From Activating with a Mouse in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Motorola Moto G Stylus (2023) | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/innovative-image-editors-your-ultimate-text-companion-for-2024/"><u>Innovative Image Editors  Your Ultimate Text Companion for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208582886-mastering-nier-automata-on-your-computer-overcome-stutter-and-lag-problems-today/"><u>Mastering Nier: Automata on Your Computer - Overcome Stutter and Lag Problems Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimize-windows-11-for-better-gaming-results/"><u>Optimize Windows 11 for Better Gaming Results</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-common-errors-in-screen-mirroring-to-your-display-with-windows-11/"><u>Overcoming Common Errors in Screen Mirroring to Your Display with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solution-guide-resolving-the-80072ee2-microsoft-windows-update-issue/"><u>Quick Solution Guide: Resolving the 80072EE2 Microsoft Windows Update Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208942109-resistance-to-targeted-agents-can-develop-necessitating-ongoing-research-and-new-drug-development/"><u>Resistance to Targeted Agents Can Develop, Necessitating Ongoing Research and New Drug Development.</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-how-to-overcome-apex-legends-engine-trouble-for-a-seamless-gaming-experience/"><u>Resolved! How to Overcome Apex Legends' Engine Trouble for a Seamless Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-sound-problems-no-more-crackling-in-your-speakers-on-win107/"><u>Resolving Sound Problems - No More Crackling in Your Speakers on Win10/7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-overwatch-voice-communication-without-hassle/"><u>Revive Your Overwatch Voice Communication Without Hassle</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-no-dns-response-issue-top-4-fixes/"><u>Solving the 'No DNS Response' Issue: Top 4 Fixes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-buyers-guide-to-picking-a-motherboard-understanding-7-critical-components/"><u>The Buyer's Guide to Picking a Motherboard: Understanding 7 Critical Components</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-dvd-not-working-errors-on-windows-machines/"><u>Troubleshooting DVD Not Working Errors on Windows Machines</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-restoring-lighting-on-faulty-corsair-keyboards/"><u>Troubleshooting Guide: Restoring Lighting on Faulty Corsair Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-overcoming-casting-problems-on-windows-11-fixed/"><u>Ultimate Guide: Overcoming Casting Problems on Windows 11 [Fixed]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/untangling-the-mystery-of-error-0x800705b4-a-definitive-fix-guide-for-windows-10-users/"><u>Untangling The Mystery of Error 0X800705B4: A Definitive Fix Guide for Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wacom-malfunction-heres-how-to-repair-your-graphics-tablet/"><u>Wacom Malfunction? Here's How to Repair Your Graphics Tablet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-stuck-file-explorer-on-your-windows-10-pc-a-fixers-companion/"><u>Winning the Battle Against Stuck File Explorer on Your Windows 10 PC - A Fixer’s Companion</u></a></li>
<li><a href="https://extra-hints.techidaily.com/zodiac-wisdom-in-101-whatsapp-bio-ideas/"><u>Zodiac Wisdom in 101 WhatsApp Bio Ideas</u></a></li>
</ul></div>
