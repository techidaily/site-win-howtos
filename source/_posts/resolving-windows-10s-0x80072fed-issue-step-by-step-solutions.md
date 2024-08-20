---
title: "Resolving Windows 10'S 0X80072FED Issue: Step-by-Step Solutions"
date: 2024-08-19T06:26:16.052Z
updated: 2024-08-20T06:26:16.052Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Windows 10'S 0X80072FED Issue: Step-by-Step Solutions"
excerpt: "This Article Describes Resolving Windows 10'S 0X80072FED Issue: Step-by-Step Solutions"
thumbnail: https://thmb.techidaily.com/1276dd3e47443d01d60ef92ceafe65883b1431cf0aceea8f20ef4307f66fd914.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://win-howtos.techidaily.com/1723209908371-resolution-tackle-the-stealthy-culprit-of-elevated-system-load-the-invisible-impacts-of-shell-infra-on-your-windows/"><u>(Resolution) Tackle the Stealthy Culprit of Elevated System Load: The Invisible Impacts Of Shell Infra on Your Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-make-your-gaming-great-not-stressful/"><u>[Updated] In 2024, Make Your Gaming Great, Not Stressful</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-pioneering-patterns-screen-cast-with-loom-pro/"><u>[Updated] In 2024, Pioneering Patterns  Screen Cast with Loom Pro</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-best-approaches-to-capture-and-share-compelling-customer-experiences/"><u>2024 Approved  Best Approaches to Capture and Share Compelling Customer Experiences</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exclusive-listing-top-15-platforms-for-gopro-optimal-use/"><u>2024 Approved  Exclusive Listing  Top 15 Platforms for GoPro Optimal Use</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-malfunctioning-at-signs-in-text-input-devices-how-to/"><u>Addressing Malfunctioning At Signs in Text Input Devices: How-To</u></a></li>
<li><a href="https://win-howtos.techidaily.com/audio-puzzle-solved-pc-and-headphones-reconcile/"><u>Audio Puzzle Solved: PC & Headphones Reconcile</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-data-buffering-option-for-sony-a7c/"><u>Best Data Buffering Option for Sony A7C</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-repair-igfxem-problems-for-improved-system-performance/"><u>Diagnose & Repair igfxEM Problems for Improved System Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210421278-expert-advice-on-handling-unavailable-dhcp-servers-get-connected-again/"><u>Expert Advice on Handling Unavailable DHCP Servers - Get Connected Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-cant-open-geforce-experience-a-comprehensive-solution/"><u>Fixing 'Can't Open GeForce Experience': A Comprehensive Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-internet-explorer-launch-issues-a-comprehensive-guide/"><u>Fixing Internet Explorer Launch Issues - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-library-loading-failures-dealing-with-error-87-incorrect-parameter-issue/"><u>Fixing Library Loading Failures: Dealing with Error 87 - Incorrect Parameter Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-and-fix-the-high-resource-demand-of-wudfhostexe-on-windows-11-devices/"><u>How to Address and Fix the High Resource Demand of Wudfhost.exe on Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-and-solve-dhcp-server-offline-connectivity-problems/"><u>How to Address and Solve 'DHCP Server Offline' Connectivity Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-a-non-functional-scroll-wheel-on-your-logitech-mouse/"><u>How to Repair a Non-Functional Scroll Wheel on Your Logitech Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-touchpad-scrolling-functionality-in-windows-10/"><u>How to Restore Touchpad Scrolling Functionality in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-touchscreen-functionality-when-its-not-responding/"><u>How to Restore Touchscreen Functionality When It's Not Responding</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-stop-excessive-cpu-consumption-by-msmpengine-in-windows-10/"><u>How to Stop Excessive CPU Consumption by MsMpEngine in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-we-solved-the-igfxem-module-malfunction-problem/"><u>How We Solved the Igfxem Module Malfunction Problem</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-get-free-green-screen-effects-from-4-youtube-channels/"><u>In 2024, Get Free Green Screen Effects From 4 YouTube Channels</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-poco-x6-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Poco X6? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/in-depth-guide-to-correcting-chrome-screen-flutter-on-your-pc/"><u>In Depth Guide to Correcting Chrome Screen Flutter on Your PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-oppo-find-n3-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Oppo Find N3? Fixed | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-for-windows-update-error-0x80244-proven-methods-and-tips/"><u>Mastering the Fix for Windows Update Error 0X80244#: Proven Methods and Tips</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/optimize-your-pc-with-stellar-file-eraser-version-5-customized-window-based-auto-purge-features/"><u>Optimize Your PC with Stellar File Eraser Version 5 - Customized Window-Based Auto Purge Features</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-windows-11-reducing-disk-impact-of-compatibility-telemetry-services/"><u>Optimizing Windows 11: Reducing Disk Impact of Compatibility Telemetry Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-overcoming-challenges-in-reaching-dhcp-services/"><u>Resolved! Overcoming Challenges in Reaching DHCP Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-key-illumination-step-by-step-solutions-for-malfunctioning-backlit-keys-on-macos-and-windows/"><u>Restore Key Illumination: Step-by-Step Solutions For Malfunctioning Backlit Keys on macOS and Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simplify-your-workflow-with-these-essential-windows-10-file-explorer-hacks/"><u>Simplify Your Workflow with These Essential Windows 10 File Explorer Hacks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-puzzle-a-detailed-guide-to-turning-on-bluetooth-in-windows-7/"><u>Solving the Puzzle: A Detailed Guide to Turning On Bluetooth in Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-stuck-keyboard-arrows-essential-troubleshooting-tips/"><u>Solving Your Stuck Keyboard Arrows: Essential Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-instructions-getting-your-laptop-mic-back-online/"><u>Step-by-Step Instructions: Getting Your Laptop Mic Back Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-techniques-to-correct-videodxgkrnlfatalerror-issues-in-windows/"><u>Step-by-Step Techniques to Correct Video_Dxgkrnl_Fatal_Error Issues in Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-essential-handbook-to-professional-screen-recordings-for-2024/"><u>The Essential Handbook to Professional Screen Recordings for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-correcting-twitch-error-code-4000-issues/"><u>Troubleshooting and Correcting Twitch Error Code 4000 Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-to-overcoming-windows-file-permission-errors/"><u>Ultimate Guide to Overcoming Windows File Permission Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-icon-troubleshooting-solutions-for-missing-desktop-icons/"><u>Windows 10 Icon Troubleshooting: Solutions for Missing Desktop Icons</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wwe-2k-fixing-the-gameplay-error-on-dx11-with-feature-level-100/"><u>WWE 2K: Fixing the Gameplay Error on DX11 with Feature Level 10.0</u></a></li>
</ul></div>
