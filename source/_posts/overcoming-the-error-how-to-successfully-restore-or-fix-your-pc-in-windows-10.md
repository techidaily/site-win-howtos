---
title: "Overcoming the Error: How to Successfully Restore or Fix Your PC in Windows 10"
date: 2024-08-15T11:28:56.560Z
updated: 2024-08-16T11:28:56.560Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming the Error: How to Successfully Restore or Fix Your PC in Windows 10"
excerpt: "This Article Describes Overcoming the Error: How to Successfully Restore or Fix Your PC in Windows 10"
thumbnail: https://thmb.techidaily.com/c92572eed4dd2bbe96a0af1968717f74dd3686117855d1fc2a4babce9d7f3f12.png
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-discovering-if-quick-youtube-subscriptions-really-work/"><u>[New] Discovering if Quick YouTube Subscriptions Really Work.</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-pro-streamers-choice-the-top-5-gaming-webcams-to-own/"><u>[New] In 2024, Pro Streamer's Choice  The Top 5 Gaming Webcams to Own</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-obs-guide-seamless-youtube-and-twitch-streaming-for-2024/"><u>[New] OBS Guide  Seamless YouTube and Twitch Streaming for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-the-ultimate-selection-top-voice-recorders-for-macos/"><u>[New] The Ultimate Selection  Top Voice Recorders for MacOS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-tier-auditory-theatre-plays/"><u>[New] Top-Tier Auditory Theatre Plays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-msvcr120dll-is-missing-in-windows-1110/"><u>[SOLVED] MSVCR120.dll Is Missing in Windows 11/10</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-streamlined-method-for-crafting-mobile-focused-youtube-channels/"><u>[Updated] 2024 Approved  Streamlined Method for Crafting Mobile-Focused YouTube Channels</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-how-to-transcribe-speech-to-text-in-microsoft-word-learn-it-here/"><u>[Updated] In 2024, How to Transcribe Speech to Text in Microsoft Word Learn It Here</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-streamline-slides-to-cinematic-content/"><u>[Updated] In 2024, Streamline Slides to Cinematic Content</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-which-recording-tool-excels-more-bandicam-vs-camtasia/"><u>[Updated] In 2024, Which Recording Tool Excels More? - Bandicam Vs. Camtasia</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-smart-shopping-for-cloud-storages-best-price-secrets-revealed/"><u>[Updated] Smart Shopping for Cloud Storages  Best Price Secrets Revealed</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-high-definition-aesthetics-exclusive-top-15-lut-selection-for-gopro/"><u>2024 Approved  High-Definition Aesthetics  Exclusive Top 15 LUT Selection for GOPRO</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-most-effective-5-image-editing-programs-on-iphone-x-7-8/"><u>2024 Approved  Most Effective 5 Image Editing Programs on iPhone (X, 7, 8)</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-navigating-the-latest-in-360-cameras/"><u>2024 Approved  Navigating the Latest in 360 Cameras</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-the-sudden-peaks-in-cpu-usage-on-windows-11/"><u>Addressing the Sudden Peaks in CPU Usage on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/breeze-through-windows-11s-persistent-restart-issue-easy-solutions-inside/"><u>Breeze Through Windows 11'S Persistent Restart Issue - Easy Solutions Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-blockades-strategies-for-successful-torrent-downloads/"><u>Bypassing Blockades: Strategies for Successful Torrent Downloads</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-oppo-a79-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Oppo A79 5G | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/comprehensive-lenovo-yoga-a940-laptop-analysis-and-evaluation/"><u>Comprehensive Lenovo Yoga A940 Laptop Analysis and Evaluation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-tips-to-correct-could-not-connect-error-on-steam/"><u>Comprehensive Tips to Correct Could Not Connect Error on Steam</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-high-cpu-consumption-by-antivirus-on-windows-11-fixed/"><u>Dealing with High CPU Consumption by Antivirus on Windows 11 [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723200653667-dell-laptop-keyboard-malfunction-heres-how-you-can-fix-it-quickly/"><u>Dell Laptop Keyboard Malfunction? Here's How You Can Fix It Quickly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-rectifying-unexpected-bootup-problems-with-windows-11-pcs/"><u>Diagnosing and Rectifying Unexpected Bootup Problems with Windows 11 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-repair-guide-for-corsair-hs50-headset-with-malfunctioning-mic/"><u>DIY Repair Guide for Corsair HS50 Headset with Malfunctioning Mic</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fix-to-your-pc-cant-project-to-another-screen-error/"><u>Easy Fix to Your PC Can't Project to Another Screen Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solution-for-excessive-cpu-usage-in-wdf-operations/"><u>Effective Solution for Excessive CPU Usage in WDF Operations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-re-establishing-connection-between-ps4-and-mic/"><u>Effective Solutions: Re-Establishing Connection Between PS4 and Mic</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-customer-reports-understanding-the-nh-d15-g2-fan-vibration-concerns-raised-by-users/"><u>Exploring Customer Reports: Understanding the NH-D15 G2 Fan Vibration Concerns Raised by Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-pc-hiccups-solutions-to-overcome-freezing-issues-effectively/"><u>Fixing PC Hiccups: Solutions to Overcome Freezing Issues Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-flickering-overcoming-brightness-problems-in-windows-10/"><u>Fixing the Flickering: Overcoming Brightness Problems in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-windows-11-screen-brightness-under-control-again/"><u>Getting Your Windows 11 Screen Brightness Under Control Again</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Meizu 21 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Nokia C12 Plus? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-dll-discrepencies-in-steam-apps/"><u>How to Address Dll Discrepencies in Steam Apps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-the-persistent-system-error-5-issue-across-various-windows-versions-fixed/"><u>How to Address the Persistent 'System Error 5' Issue Across Various Windows Versions [Fixed]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-class-registration-issues-in-windows-10-a-step-by-step-guide/"><u>How to Fix Class Registration Issues in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-of-apple-iphone-15-pro-max-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of Apple iPhone 15 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-ce-34878-0-issue-on-sonys-ps4-console-fixed/"><u>How to Resolve the CE-34878-0 Issue on Sony's PS4 Console [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-windows-update-problem-decode-error-0x8007001f/"><u>How to Resolve Windows Update Problem – Decode Error 0X8007001f</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Samsung Galaxy A24? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-zte-nubia-z60-ultra-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset ZTE Nubia Z60 Ultra phone? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-resetting-dns-cache-to-solve-internet-connectivity-issues-on-windows-platforms/"><u>How-To: Resetting DNS Cache to Solve Internet Connectivity Issues on Windows Platforms</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-honor-90-gt-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Honor 90 GT FRP?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-ipad-or-apple-iphone-se-2022-stuck-on-activation-lock-by-drfone-ios/"><u>In 2024, How to Fix iPad or Apple iPhone SE (2022) Stuck On Activation Lock?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-recovery-how-to-restore-typing-capabilities-pre-login-problem/"><u>Keyboard Recovery: How to Restore Typing Capabilities Pre-Login Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mac-user-problem-solved-restoring-mouse-action-on-your-device/"><u>Mac User Problem Solved: Restoring Mouse Action on Your Device</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/precision-and-savings-combined-top-asmr-microphones-within-reach-for-2024/"><u>Precision & Savings Combined  Top ASMR Microphones Within Reach for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-cure-to-console-clunkiness-while-gaming/"><u>Quick Cure to Console Clunkiness While Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solution-for-rdr2-memory-crash-how-to-expand-page-file-size-efficiently/"><u>Quick Solution for RDR2 Memory Crash: How to Expand Page File Size Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-not-found-rockalldlldll-on-windows/"><u>Rectifying 'Not Found' Rockalldll.dll on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-graphics-card-usage-by-desktop-window-manager-in-windows-1011-with-these-5-techniques/"><u>Resolve Excessive Graphics Card Usage by Desktop Window Manager in Windows 10/11 with These 5 Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issue-understanding-and-fixing-error-code-0x80004005/"><u>Resolved Issue: Understanding and Fixing Error Code 0X80004005</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-the-nospinlockavailable-error-a-step-by-step-guide/"><u>Resolving the NO_SPIN_LOCK_AVAILABLE Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/seamless-video-playback-on-kodi-master-the-art-of-fixing-buffering-woes/"><u>Seamless Video Playback on Kodi - Master the Art of Fixing Buffering Woes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-restoring-functionality-when-your-keyboard-fails-on-startup/"><u>Solution Steps: Restoring Functionality When Your Keyboard Fails on Startup</u></a></li>
<li><a href="https://tech-revival.techidaily.com/speculating-on-the-future-gpt-5s-expected-release/"><u>Speculating on the Future: GPT-5's Expected Release?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-fixing-driver-power-cycle-errors-in-windows/"><u>Step-by-Step Solutions for Fixing Driver Power Cycle Errors in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-making-your-bluetooth-mouse-function-again-on-windows/"><u>Step-by-Step Solutions: Making Your Bluetooth Mouse Function Again on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-crashes-of-shockwave-flash-plugin-on-chrome-browser/"><u>Troubleshooting and Fixing Crashes of Shockwave Flash Plugin on Chrome Browser</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-casting-issues-how-to-fix-cannot-cast-to-device-errors-in-windows-11/"><u>Troubleshooting Casting Issues: How to Fix 'Cannot Cast to Device' Errors in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-fixing-the-issue-of-windowsplusshiftpluss-malfunction-in-windows-11-and-10/"><u>Troubleshooting Steps: Fixing the Issue of Windows+Shift+S Malfunction in Windows 11 and 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-how-to-repair-aoc-display-issue-on-win10/"><u>Troubleshooting Steps: How to Repair AOC Display Issue on Win10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-non-functioning-integrated-webcams-in-windows/"><u>Ultimate Guide: Resolving Non-Functioning Integrated Webcams in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooting-guide-resolving-persistent-screen-freezes-on-your-pc/"><u>Ultimate Troubleshooting Guide: Resolving Persistent Screen Freezes on Your PC</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-infinix-gt-10-pro-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Infinix GT 10 Pro Offline? Troubleshooting Guide | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->