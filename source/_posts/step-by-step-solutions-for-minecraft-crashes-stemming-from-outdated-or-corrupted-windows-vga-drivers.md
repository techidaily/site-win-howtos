---
title: Step-by-Step Solutions for Minecraft Crashes Stemming From Outdated or Corrupted Windows VGA Drivers
date: 2024-08-19T06:23:17.657Z
updated: 2024-08-20T06:23:17.657Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for Minecraft Crashes Stemming From Outdated or Corrupted Windows VGA Drivers
excerpt: This Article Describes Step-by-Step Solutions for Minecraft Crashes Stemming From Outdated or Corrupted Windows VGA Drivers
thumbnail: https://thmb.techidaily.com/79265524b64a96a355aa9c66ef040a78b4c61cd77b813b963d28880dc313d729.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->

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
<li><a href="https://win-howtos.techidaily.com/fixed-alert-the-active-input-timing-specification-is-ignored-by-the-display-unit/"><u>[FIXED] Alert! The Active Input Timing Specification Is Ignored by the Display Unit</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-lighten-your-sentence-with-satire-ranking-funniest-facebook-detentions/"><u>[New] In 2024, Lighten Your Sentence with Satire  Ranking Funniest Facebook Detentions</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-innovative-8-android-video-chat-apps-beyond-duostrios-for-2024/"><u>[New] Innovative 8 Android Video Chat Apps Beyond Duos/Trios for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/kyrocket-your-streams-earnings-universal-strategies-for-success-for-2024/"><u>[New] Skyrocket Your Stream's Earnings  Universal Strategies for Success for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-prime-7-free-screen-recorders-for-old-computers/"><u>[Updated] Prime 7 Free Screen Recorders for Old Computers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-satiating-the-social-hangry-with-hilarious-9gag-memes/"><u>[Updated] Satiating the Social Hangry With Hilarious 9GAG Memes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-evaluating-max-360-and-hero-11-the-ultimate-gopro-video-battle/"><u>2024 Approved  Evaluating Max 360 & Hero 11  The Ultimate GoPro Video Battle</u></a></li>
<li><a href="https://buynow-info.techidaily.com/8-things-to-consider-when-buying-a-tablet/"><u>8 Things to Consider When Buying a Tablet</u></a></li>
<li><a href="https://extra-resources.techidaily.com/affinity-photo-demystified-for-2024/"><u>Affinity Photo Demystified for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/barriers-to-success-unveiling-the-reasons-behind-teredos-non-qualification/"><u>Barriers to Success: Unveiling the Reasons Behind Teredo's Non-Qualification</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clear-expert-tips-to-overcome-no-input-detected-screen-challenges/"><u>Clear Expert Tips to Overcome 'No Input Detected' Screen Challenges</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-strategies-to-resolve-oculus-hardware-issues/"><u>Comprehensive Strategies to Resolve Oculus Hardware Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-and-remedying-the-service-unavailable-a-guide-for-tackling-http-error-503/"><u>Decoding and Remedying the 'Service Unavailable' - A Guide for Tackling HTTP Error 503</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-corsair-hs50-users-with-unresponsive-microphones/"><u>Effective Solutions for Corsair HS50 Users with Unresponsive Microphones</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-resolving-windows-11-freezing-issues/"><u>Effective Solutions: Resolving Windows 11 Freezing Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-troubleshooting-guide-reviving-your-malfunctioning-usb-connectors/"><u>Effortless Troubleshooting Guide: Reviving Your Malfunctioning USB Connectors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ensuring-successful-driver-installation-for-your-printers-on-a-windows-pc/"><u>Ensuring Successful Driver Installation for Your Printers on a Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-rectified-device-not-found-code-eb-for-users-of-windows-11-8-and-7/"><u>Error Rectified: 'Device Not Found' (Code Eb) for Users of Windows 11, 8 & 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-ethernet-network-errors-on-your-pc-tips-for-windows-10-and-7-operating-systems/"><u>Fixing Ethernet Network Errors on Your PC: Tips for Windows 10 & 7 Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-resolving-computer-hangs-during-startup/"><u>Fixing the Issue: Resolving Computer Hangs During Startup</u></a></li>
<li><a href="https://techtrends.techidaily.com/getting-started-with-the-latest-mozilla-thunderbird-52-for-faster-email-management/"><u>Getting Started with the Latest Mozilla Thunderbird (52) for Faster Email Management</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/global-viewer-count-triumphs-play-button-honors/"><u>Global Viewer Count Triumphs  Play Button Honors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-troubleshoot-and-solve-error-0x80n4005-a-step-by-step-guide/"><u>How to Correctly Troubleshoot and Solve Error 0X80n4005 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-ensure-your-hardware-is-synced-with-world-of-warcraft-driver-update-solutions/"><u>How to Ensure Your Hardware Is Synced with World of Warcraft - Driver Update Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-device-drivers-not-installed-on-windows-7/"><u>How to Resolve 'Device Drivers Not Installed' On Windows 7</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-advanced-filmmaking-techniques-selecting-top-notch-lenses/"><u>In 2024, Advanced Filmmaking Techniques  Selecting Top-Notch Lenses</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-instant-aspect-ratio-tuning-for-youtube-on-mac/"><u>In 2024, Instant Aspect Ratio Tuning for Youtube on Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/join-the-fallout-saga-beyond-the-screen-adventures/"><u>Join the Fallout Saga Beyond The Screen Adventures</u></a></li>
<li><a href="https://hardware-help.techidaily.com/keeping-your-connectivity-smooth-how-to-install-latest-wireless-drivers-on-microsoft-oses/"><u>Keeping Your Connectivity Smooth: How to Install Latest Wireless Drivers on Microsoft OSes</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/mobile-reaction-video-creation-top-tools-and-apps-for-2024/"><u>Mobile Reaction Video Creation Top Tools and Apps for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/perfecting-your-streamgame-recording-in-obs-fixes-for-blackout-troubles/"><u>Perfecting Your Stream/Game Recording in OBS – Fixes for Blackout Troubles</u></a></li>
<li><a href="https://fox-glue.techidaily.com/perfectly-pivoted-videos-the-ultimate-android-editing-guide-for-2024/"><u>Perfectly Pivoted Videos  The Ultimate Android Editing Guide for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/present-evidence-such-as-studies-or-expert-opinions-to-support-this-point/"><u>Present Evidence Such as Studies or Expert Opinions to Support This Point.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-deactivated-led-lights-on-mac-and-pc-keyboards/"><u>Quick Solutions for Deactivated LED Lights on Mac and PC Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reboot-call-when-playing-games/"><u>Reboot Call When Playing Games</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fix-guide-when-the-printer-driver-host-hangs-up-on-32-bit-os/"><u>Resolved: Fix Guide - When the Printer Driver Host Hangs Up on 32-Bit OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-typing-experience-with-a-quick-keyboard-reset-method/"><u>Revive Your Typing Experience with a Quick Keyboard Reset Method</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-solutions-to-reset-and-optimize-your-keyboard-performance/"><u>Simple Solutions to Reset and Optimize Your Keyboard Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-unknown-usb-device-detected-error-port-reset-failure-on-windows-10/"><u>Solving the 'Unknown USB Device Detected' Error: Port Reset Failure on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-restoring-bluetooth-functionality-on-windows-11-when-devices-arent-recognized/"><u>Step-by-Step Guide: Restoring Bluetooth Functionality on Windows 11 When Devices Aren't Recognized</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-stabilizing-your-battle-royale-gaming-experience/"><u>Step-by-Step Guide: Stabilizing Your Battle Royale Gaming Experience</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-elite-collection-of-data-center-shelving-units-s-tech-landscape/"><u>The Elite Collection of Data Center Shelving Units 'S Tech Landscape</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-5-methods-to-resolve-high-gpu-consumption-by-the-desktop-window-manager-on-windows-11/"><u>Top 5 Methods to Resolve High GPU Consumption by the Desktop Window Manager on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-eliminating-lag-time-on-windows-11-keyboards/"><u>Troubleshooting and Eliminating Lag Time on Windows 11 Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-restoring-mouse-right-click-functionality-in-windows-10/"><u>Troubleshooting Guide: Restoring Mouse Right-Click Functionality in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-rpc-server-unreachable-errors-on-pc/"><u>Troubleshooting Steps for 'RPC Server Unreachable' Errors on PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-fixing-a-broken-lenovo-print-recognition-feature/"><u>Troubleshooting Tips for Fixing a Broken Lenovo Print Recognition Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-correcting-the-0x802n40034-error-on-windows-10-os/"><u>Understanding and Correcting the 0X802n40034 Error on Windows 10 OS</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-windows-11-app-error-afc/"><u>Understanding and Remedying Windows 11 APP Error AFC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unity-graphics-error-solved-overcome-the-failed-to-initialize-hurdle-easily/"><u>Unity Graphics Error Solved: Overcome the 'Failed to Initialize' Hurdle Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210885957-winning-the-battle-against-failed-feature-updates-in-windows-10-v1803-now-solved/"><u>Winning the Battle Against Failed Feature Updates in Windows 10 v1803 - Now Solved!</u></a></li>
</ul></div>
