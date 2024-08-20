---
title: Navigate Files Easily on Windows 11 - A Comprehensive Help for File Explorer Users
date: 2024-08-19T06:19:50.024Z
updated: 2024-08-20T06:19:50.024Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Navigate Files Easily on Windows 11 - A Comprehensive Help for File Explorer Users
excerpt: This Article Describes Navigate Files Easily on Windows 11 - A Comprehensive Help for File Explorer Users
thumbnail: https://thmb.techidaily.com/b9b7665577f766113660c4c3c2e978c3705b755579fa83e6d4b9ffe0b41b7175.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://win-howtos.techidaily.com/fixed-monster-hunter-world-pc-disconnect-problem/"><u>[Fixed] Monster Hunter World PC Disconnect Problem</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-the-art-of-thumbnail-design-choosing-best-fonts/"><u>[New] 2024 Approved  The Art of Thumbnail Design  Choosing Best Fonts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-elevate-everyday-life-through-webcams/"><u>[New] Elevate Everyday Life Through Webcams</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-creating-masterpiece-canon-chrono-films/"><u>[New] In 2024, Creating Masterpiece Canon Chrono Films</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/p3-to-video-stream-mp3-to-youtube-in-3-easy-steps/"><u>[New] MP3 to Video  Stream MP3 to YouTube in 3 Easy Steps</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-step-by-step-audio-transformation-tips-for-enhanced-competitive-play-in-free-fire/"><u>[New] Step-by-Step Audio Transformation Tips for Enhanced Competitive Play in Free Fire</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-ultimate-digital-lecture-name-builder/"><u>[New] Ultimate Digital Lecture Name Builder</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-boost-engagement-stream-live-from-twitch-embed-on-fb/"><u>[Updated] 2024 Approved  Boost Engagement  Stream Live From Twitch, Embed on FB</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-easy-voice-adjustment-for-ps5-and-ps4-for-2024/"><u>[Updated] Easy Voice Adjustment for PS5 & PS4 for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-infuse-rhythm-to-instagram-music-guide/"><u>[Updated] In 2024, Infuse Rhythm to Instagram  Music Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-top-heavy-lift-uavs-for-global-industrial-use/"><u>[Updated] Top Heavy-Lift UAVs for Global Industrial Use</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-e-lecture-documentation/"><u>2024 Approved  E-Lecture Documentation</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-samsung-galaxy-s23-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Samsung Galaxy S23 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/audio-disruption-in-win-10-rectified/"><u>Audio Disruption in Win 10 Rectified</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/brands-on-the-rise-choose-the-best-ig-video-editing-apps/"><u>Brands on the Rise  Choose the Best IG Video Editing Apps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-blockade-a-step-by-step-guide-to-solve-windows-10-couldnt-be-installed-error-code-aturality-80240020/"><u>Bypassing the Blockade: A Step-by-Step Guide to Solve Windows 10 Couldn't Be Installed - Error Code Aturality | 80240020</u></a></li>
<li><a href="https://win-howtos.techidaily.com/could-the-loss-of-d3d-devices-kill-unreal/"><u>Could the Loss of D3D Devices Kill Unreal?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/curing-csgos-crash-problems-with-these-swift-and-straightforward-fixes/"><u>Curing CSGO's Crash Problems with These Swift and Straightforward Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-invalid-input-alerts-on-your-visual-interface-device/"><u>Dealing with Invalid Input Alerts on Your Visual Interface Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208396498-disregarded-sd-card-dont-despair-solutions-await/"><u>Disregarded SD Card, Don't Despair! Solutions Await!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-prevent-and-resolve-csgo-system-crashes/"><u>Easy Steps to Prevent and Resolve CS:GO System Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-wdf-implementation-lowering-high-cpu-consumption-in-windows-systems/"><u>Efficient WDF Implementation - Lowering High CPU Consumption in Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhancing-link-quality-between-epson-devices/"><u>Enhancing Link Quality Between Epson Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-how-to-resolve-a-stuck-white-or-black-screen-on-your-laptop/"><u>Expert Guide: How to Resolve a Stuck White or Black Screen on Your Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-blackout-solutions-for-obs-recording-glitches-in-games/"><u>Fixing the Blackout - Solutions for OBS Recording Glitches in Games</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-11-update-issue-guide-through-the-0x800705b4-error/"><u>Fixing the Windows 11 Update Issue: Guide Through the 0X800705B4 Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-your-astro-a40-microphone-issues-easy-troubleshooting-steps/"><u>Fixing Your Astro A40 Microphone Issues: Easy Troubleshooting Steps</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-vivo-x-fold-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/gopro-and-yi-the-2023-ultimate-actions-camera-verdict/"><u>GoPro & YI  The 2023 Ultimate Actions Camera Verdict</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-ce-34878-0-error-code-on-your-playstation-4-a-comprehensive-guide/"><u>How to Fix the CE-34878-0 Error Code on Your PlayStation 4: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-lost-invisible-desktop-windows-back/"><u>How To Get Your Lost, Invisible Desktop Windows Back!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-nintendo-switchs-microphone-working-again-professional-repair-techniques/"><u>How To Get Your Nintendo Switch's Microphone Working Again: Professional Repair Techniques</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-infinix-zero-30-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Infinix Zero 30 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-ios-leading-video-capture-solutions/"><u>In 2024, IOS Leading Video Capture Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/insider-tips-conquering-the-complete-darkness-screens-on-startup-of-mhw/"><u>Insider Tips: Conquering the Complete Darkness Screens on Startup of MHW</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pdf-printer-problems-quick-fixes-for-immediate-relief/"><u>PDF Printer Problems: Quick Fixes for Immediate Relief</u></a></li>
<li><a href="https://win-howtos.techidaily.com/program-termination-requested/"><u>Program Termination Requested</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211775888-pubg-2024-master-the-art-of-fixing-game-launch-issues-and-start-enjoying-now/"><u>PUBG 2024: Master the Art of Fixing Game Launch Issues and Start Enjoying Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208936142-pubg-game-update-all-structures-now-function-correctly-no-more-missing-buildings/"><u>PUBG Game Update: All Structures Now Function Correctly – No More Missing Buildings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/realtek-driver-trouble-discover-how-to-restore-missing-controller-detection/"><u>Realtek Driver Trouble? Discover How to Restore Missing Controller Detection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-a-dead-laptop-mouse-effective-solutions-for-stuck-or-non-responsive-usb-devices/"><u>Revive a Dead Laptop Mouse: Effective Solutions for Stuck or Non-Responsive USB Devices</u></a></li>
<li><a href="https://driver-install.techidaily.com/smooth-transition-for-pro-6-drivers/"><u>Smooth Transition for Pro 6 Drivers</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-process-to-forcefully-eliminate-files-in-windows-11-with-the-help-of-revo-uninstaller/"><u>Step-by-Step Process to Forcefully Eliminate Files in Windows 11 with the Help of Revo Uninstaller</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tips-for-troubleshooting-frequent-usb-disconnections/"><u>Step-by-Step Tips for Troubleshooting Frequent USB Disconnections</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-a-non-responsive-huion-pen-with-these-five-effective-tips/"><u>Troubleshoot a Non-Responsive Huion Pen with These Five Effective Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-optimize-your-computer-addressing-the-low-on-memory-warning-on-windows-10/"><u>Troubleshoot and Optimize Your Computer: Addressing the Low on Memory Warning on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-keyboard-fixing-non-working-directional-buttons/"><u>Troubleshoot Your Keyboard: Fixing Non-Working Directional Buttons</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-responsive-keyboards-in-windows-10-solutions-and-tips/"><u>Troubleshooting Non-Responsive Keyboards in Windows 10: Solutions and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-dealing-with-hanging-windows-10-interfaces/"><u>Troubleshooting Tips for Dealing with Hanging Windows 10 Interfaces</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-when-you-cant-use-internet-explorer-anymore/"><u>Troubleshooting Tips When You Can’t Use Internet Explorer Anymore</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207576089-uncover-your-missing-wi-fi-adapter-choices-in-windows-11-now-solved/"><u>Uncover Your Missing Wi-Fi Adapter Choices in Windows 11 - Now Solved!</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unveiling-the-performance-of-d-link-powerline-2000-swift-setup-brisk-speed-tests/"><u>Unveiling the Performance of D-Link Powerline 2000 – Swift Setup, Brisk Speed Tests</u></a></li>
<li><a href="https://win-howtos.techidaily.com/warframe-update-issues-troubleshooting-failed-installation-errors/"><u>Warframe Update Issues - Troubleshooting Failed Installation Errors</u></a></li>
</ul></div>
