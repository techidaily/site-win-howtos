---
title: "Expert Tips: Correctly Resolving the System Exception Handler Problem (Error 0xC0n00000E9)"
date: 2024-08-15T11:22:46.665Z
updated: 2024-08-16T11:22:46.665Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Expert Tips: Correctly Resolving the System Exception Handler Problem (Error 0xC0n00000E9)"
excerpt: "This Article Describes Expert Tips: Correctly Resolving the System Exception Handler Problem (Error 0xC0n00000E9)"
thumbnail: https://thmb.techidaily.com/cf88e87b734b5b9f59ddbd2f8f99680f9b1ec3ba8de831308f2fd3fe15c5bbed.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-choreographing-a-stellar-tiktok-wrap-up/"><u>[New] 2024 Approved  Choreographing a Stellar TikTok Wrap-Up</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-navigating-the-obscured-realm-of-youtube-a-methodical-approach/"><u>[New] 2024 Approved  Navigating the Obscured Realm of YouTube  A Methodical Approach</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-seamless-transfer-of-high-definition-fb-media/"><u>[New] 2024 Approved  Seamless Transfer of High Definition FB Media</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/oosting-sales-through-effective-strategies-for-channel-trailer-creation-for-2024/"><u>[New] Boosting Sales Through Effective Strategies for Channel Trailer Creation for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-brief-but-bold-short-videos-on-fb/"><u>[New] In 2024, Brief but Bold  Short Videos on FB</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-exclusive-recording-gadgets-for-windows-10-gamers/"><u>[New] In 2024, Exclusive Recording Gadgets for Windows 10 Gamers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-mastering-game-capture-fbx-filming-techniques-for-2024/"><u>[New] Mastering Game Capture  FBX Filming Techniques for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/erfect-guide-youtube-videos-on-instagram-feed-for-2024/"><u>[New] Perfect Guide  YouTube Videos on Instagram Feed for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-tips-for-crafting-effective-igtv-titles-and-summaries/"><u>[New] Tips for Crafting Effective IGTV Titles & Summaries</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-your-complete-reference-to-durecorders-features/"><u>[Updated] In 2024, Your Complete Reference to DuRecorder’s Features</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pro-level-hdr-mastery-your-compre-point-of-entry/"><u>2024 Approved  Pro Level HDR Mastery  Your Compre Point of Entry</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-the-unboxing-game-crafting-winning-strategies/"><u>2024 Approved  The Unboxing Game  Crafting Winning Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/best-practices-solving-windows-11-bluetooth-connection-issues/"><u>Best Practices: Solving Windows 11 Bluetooth Connection Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corsair-keyboard-backlight-failure-heres-how-to-get-your-board-glowing-again/"><u>Corsair Keyboard Backlight Failure? Here’s How to Get Your Board Glowing Again!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-huggingchat-the-costless-community-driven-substitute-for-chatgpt/"><u>Discover HuggingChat - The Costless, Community-Driven Substitute for ChatGPT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dota-2-graphics-glitch-error-2024-fix-without-hacking/"><u>Dota 2 Graphics Glitch: Error 2024 Fix Without Hacking</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-to-stop-frequent-usb-dropout-problems/"><u>Easy Fixes to Stop Frequent USB Dropout Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-when-your-windows-update-gets-jammed-at-zero-percentage/"><u>Effective Fixes for When Your Windows Update Gets Jammed at Zero Percentage</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-get-your-frozen-trackpad-or-external-mouse-working-again-on-your-laptop/"><u>Expert Tips to Get Your Frozen Trackpad or External Mouse Working Again on Your Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-troubleshooting-the-silent-streets-forza-horizon-4-audio-fixes/"><u>Fixed: Troubleshooting the Silent Streets - Forza Horizon 4 Audio Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-eliminate-red-screen-disruption-on-electronics/"><u>How to Eliminate Red Screen Disruption on Electronics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-non-responsive-keyboard-on-your-dell-laptop/"><u>How to Fix a Non-Responsive Keyboard on Your Dell Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-dell-speakers-not-working/"><u>How To Fix Dell Speakers Not Working</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-error-program-was-not-loaded-into-memory-properly-error-code-0xc000007b/"><u>How to Fix the Error: Program Was Not Loaded Into Memory Properly ([Error Code 0xC000007B])</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-handle-undefined-classes-on-windows-10-systems-guide/"><u>How to Handle Undefined Classes on Windows 10 Systems [Guide]</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-vivo-y36i-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Vivo Y36i Without Password | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-illumination-to-your-faulty-corsair-board/"><u>How to Restore Illumination to Your Faulty Corsair Board</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206584186-hp-laptop-usb-issues-heres-how-you-can-get-them-fixed/"><u>HP Laptop USB Issues? Here's How You Can Get Them Fixed</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Motorola Edge 40 Neo? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-swiftly-fix-red-eyes-in-iphone-photography-at-no-cost/"><u>In 2024, Swiftly Fix Red Eyes in iPhone Photography at No Cost</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-media-connection-repair-for-a-seamless-window-experience/"><u>Mastering Media Connection Repair for a Seamless Window Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-error-0x8024401c-expert-fixes-for-windows-1011-updates-gone-wrong/"><u>Overcoming Error 0X8024401C: Expert Fixes for Windows 10/11 Updates Gone Wrong</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-resolve-your-google-hangouts-microphone-issues-immediately/"><u>Quick Solutions: Resolve Your Google Hangouts Microphone Issues Immediately</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-pubg-launch-problems-expert-tips-for-the-2024-update/"><u>Resolve Your PUBG Launch Problems - Expert Tips for the 2024 Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-device-detection-issues-with-bluetooth-on-microsofts-latest-os-windows-n11/"><u>Resolving Device Detection Issues with Bluetooth on Microsoft's Latest OS, Windows N11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-excessive-disk-space-consumption-by-microsoft-compatibility-telemetry-in-windows-10/"><u>Resolving Excessive Disk Space Consumption by Microsoft Compatibility Telemetry in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-geforce-experience-launch-problem-step-by-step-guide/"><u>Resolving the GeForce Experience Launch Problem: Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-store-cache-issues-a-comprehensive-fix-guide/"><u>Resolving Windows Store Cache Issues - A Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-computer-how-to-restore-functionality-to-malfunctioning-usb-ports-on-win-10-and-11/"><u>Reviving Your Computer: How to Restore Functionality to Malfunctioning USB Ports on Win 10 and 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-passion-for-learning-strategies-to-combat-school-apathy/"><u>Reviving Your Passion for Learning: Strategies to Combat School Apathy</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-oddworld-soulstorm-pc-crash-issues-a-comprehensive-guide/"><u>Solving Oddworld: Soulstorm PC Crash Issues – A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-a-nonfunctional-webcam-on-an-hp-laptop-in-windows-11/"><u>Solving the Issue of a Nonfunctional Webcam on an HP Laptop in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-steam-games-missing-files-and-privileges-problem/"><u>Solving Your Steam Game's Missing Files and Privileges Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-making-your-computers-fn-buttons-work-again/"><u>Step-by-Step Guide: Making Your Computer’s Fn Buttons Work Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-the-no-video-signal-monitor-issue/"><u>Step-by-Step Guide: Resolving the 'No Video Signal' Monitor Issue</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlined-printing-upgrade-to-the-latest-hp-drivers-for-win10/"><u>Streamlined Printing: Upgrade to the Latest HP Drivers for WIN10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-brightness-issues-in-windows-11/"><u>Troubleshooting Guide: Fixing Brightness Issues in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-functional-usb-ports-on-windows-10-and-11-systems/"><u>Troubleshooting Non-Functional USB Ports on Windows 10 & 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-hdcp-ready-monitor-connection-errors/"><u>Troubleshooting Non-HDCP Ready Monitor Connection Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-controlled-windows-settings-a-comprehensive-guide/"><u>Understanding Controlled Windows Settings: A Comprehensive Guide</u></a></li>
</ul></div>
