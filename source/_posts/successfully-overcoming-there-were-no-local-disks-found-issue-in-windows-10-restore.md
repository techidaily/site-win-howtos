---
title: Successfully Overcoming 'There Were No Local Disks Found' Issue in Windows 10 Restore
date: 2024-08-19T07:10:15.654Z
updated: 2024-08-20T07:10:15.654Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Successfully Overcoming 'There Were No Local Disks Found' Issue in Windows 10 Restore
excerpt: This Article Describes Successfully Overcoming 'There Were No Local Disks Found' Issue in Windows 10 Restore
thumbnail: https://thmb.techidaily.com/caa6cead2c370efcf0282829aeb71cf5fae19a07fa272224ebe494dc43e30123.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-culinary-carousel-swirling-up-top-food-network-names/"><u>[New] 2024 Approved  Culinary Carousel  Swirling Up Top Food Network Names</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-pathway-to-free-final-cut-pro/"><u>[New] The Pathway to Free Final Cut Pro</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-ultimate-story-blueprints-across-8-movie-sectors/"><u>[New] Ultimate Story Blueprints Across 8 Movie Sectors</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-unlocking-full-potential-the-laptop-recording-manual-for-2024/"><u>[New] Unlocking Full Potential  The Laptop Recording Manual for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-step-by-step-guide-to-synchronized-camscreen-capture/"><u>[Updated] 2024 Approved  Step-by-Step Guide to Synchronized Cam/Screen Capture</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-building-a-sustainable-income-via-youtube-and-adsense/"><u>[Updated] In 2024, Building a Sustainable Income via YouTube and AdSense</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-precision-screen-capturing-top-tools-reviewed-on-pcmac/"><u>[Updated] In 2024, Precision Screen Capturing  Top Tools Reviewed on PC/Mac</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-no-cost-joke-factory-making-laughter-easy-for-2024/"><u>[Updated] No Cost Joke Factory  Making Laughter Easy for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-taking-the-plunge-a-beginners-guide-to-metaverse-memes-and-gags/"><u>[Updated] Taking the Plunge  A Beginner's Guide to Metaverse Memes and Gags</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-simplify-your-marine-movie-projects-top-7-hacks/"><u>2024 Approved  Simplify Your Marine Movie Projects  Top 7 Hacks</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-the-social-media-roadmap-for-business-growth/"><u>2024 Approved  The Social Media Roadmap for Business Growth</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-this-troubleshooting-steps-for-windows-10s-persistent-update-error-0x800f0922/"><u>Beat This: Troubleshooting Steps for Windows 10'S Persistent Update Error 0X800F0922</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-0x80072efd-error-in-windows-11-with-proven-solutions/"><u>Bypassing the 0X80072EFD Error in Windows 11 with Proven Solutions</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/capturing-clarity-a-look-at-screensnapelite-for-2024/"><u>Capturing Clarity  A Look at 'ScreenSnapElite' For 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206298676-complete-guide-to-overcome-the-error-5-notification-in-windows-1178-systems-now-solved/"><u>Complete Guide to Overcome the Error 5 Notification in Windows 11/7/8 Systems – Now Solved!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/conquering-interviews-a-compreayers-journey-to-success-for-2024/"><u>Conquering Interviews  A Compreayer's Journey to Success for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corsair-hs50-headset-mic-repair-guide-troubleshooting-tips-for-improved-audio-output/"><u>Corsair HS50 Headset Mic Repair Guide - Troubleshooting Tips for Improved Audio Output</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-issues-with-your-steelseries-x70-mouse-pen-not-responding-detailed-tutorial-inside/"><u>Diagnosing and Repairing Issues with Your SteelSeries X70 Mouse Pen Not Responding – Detailed Tutorial Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-solutions-for-oculus-tech-hiccups-how-to-tackle-hardware-errors/"><u>DIY Solutions for Oculus Tech Hiccups: How to Tackle Hardware Errors</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/essential-windows-11-webcams-for-excellent-recordings/"><u>Essential Windows 11 Webcams for Excellent Recordings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-restoring-pen-and-touch-sensitivity-after-screen-malfunction/"><u>Expert Advice: Restoring Pen and Touch Sensitivity After Screen Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-unresponsive-apple-magic-mouse-on-macos/"><u>Expert Tips for Repairing Unresponsive Apple Magic Mouse on macOS</u></a></li>
<li><a href="https://win-dash.techidaily.com/find-and-download-the-perfect-hp-printer-driver-beginner-friendly-guide/"><u>Find And Download The Perfect HP Printer Driver - Beginner Friendly Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/from-dead-screen-to-battlefield-fortnite-launches/"><u>From Dead Screen to Battlefield: Fortnite Launches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gameplay-glitches-be-gone-now-easily/"><u>Gameplay Glitches Be Gone, Now Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-back-in-control-resolving-power-issues-with-your-ps4-controllers-battery/"><u>Get Back in Control - Resolving Power Issues with Your PS4 Controller's Battery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-the-night-light-feature-up-and-running-again-on-your-windows-1011-device/"><u>Getting the Night Light Feature Up and Running Again on Your Windows 10/11 Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-minimize-dwm-gpu-usage-a-5-step-approach-for-windows-users/"><u>How to Minimize DWM GPU Usage: A 5-Step Approach for Windows Users</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-data-from-apple-iphone-11-to-new-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>How To Transfer Data from Apple iPhone 11 to New iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-hit-list-top-10-songs-in-one-place/"><u>In 2024, Hit List  Top 10 Songs in One Place</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-selective-cinematic-forecast-collection/"><u>In 2024, Selective Cinematic Forecast Collection</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-vivo-s17e-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Vivo S17e Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-why-cant-i-watch-video-on-sony-a6400-camera/"><u>In 2024, Why Can't I Watch Video on Sony A6400 Camera?</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/instant-fix-how-to-swiftly-install-the-newest-intel-dual-band-ac-3160-wi-fi-driver/"><u>Instant Fix: How to Swiftly Install the Newest Intel Dual Band AC 3160 Wi-Fi Driver</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212531767-keypad-issues-on-your-notebook-running-windows-solutions-for-all-versions/"><u>Keypad Issues on Your Notebook Running Windows? Solutions for All Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/locate-and-install-required-media-driver-quickly-fixed-solution/"><u>Locate & Install Required Media Driver Quickly | Fixed Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203247138-lost-the-icons-on-your-taskbar-revive-them-with-these-4-secrets-for-windows-11-users/"><u>Lost The ICONS on Your Taskbar? Revive Them with These 4 Secrets for Windows 11 Users!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-windows-store-cache-recovery-proven-fixes-revealed/"><u>Master the Art of Windows Store Cache Recovery - Proven Fixes Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/maximize-your-gaming-experience-in-windows-11-with-these-key-optimization-techniques/"><u>Maximize Your Gaming Experience in Windows 11 with These Key Optimization Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-scroll-wheel-troubleshooting-tips-for-restoring-functionality-on-a-logitech-mouse/"><u>Overcoming Scroll Wheel Troubleshooting: Tips for Restoring Functionality on a Logitech Mouse.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ps4-network-type-trouble-follow-this-comprehensive-fix-tutorial/"><u>PS4 Network Type Trouble? Follow This Comprehensive Fix Tutorial!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-when-your-steam-store-wont-open-correctly/"><u>Quick Fixes when Your Steam Store Won't Open Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fix-your-kodi-streams-say-goodbye-to-buffering/"><u>Resolved: Fix Your Kodi Streams - Say Goodbye to Buffering</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolved-troubleshooting-steps-for-fixing-ring-of-elysium-game-crashes/"><u>Resolved: Troubleshooting Steps for Fixing Ring of Elysium Game Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-overcoming-setbacks-in-installing-the-windows-10-may-2019-update-v1903/"><u>Resolved! Overcoming Setbacks in Installing the Windows 10 May 2019 Update (V1903)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-excessive-cpu-consumption-by-wudfhostexe-on-windows-11/"><u>Resolving Excessive CPU Consumption by wudfhost.exe on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-lost-touchpad-device-masters-mission/"><u>Restore Lost Touchpad: Device Master's Mission</u></a></li>
<li><a href="https://extra-information.techidaily.com/share-todays-enlightening-voice-lesson/"><u>Share Today's Enlightening Voice Lesson</u></a></li>
<li><a href="https://fix-guide.techidaily.com/solved-warning-camera-failed-on-realme-c67-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-connection-errors-a-guide-to-reconnecting-with-a-distant-server/"><u>Solving Connection Errors: A Guide to Reconnecting with a Distant Server</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-overcoming-the-80072ee2-error-in-windows-updates/"><u>Step-by-Step Fixes for Overcoming the 80072EE2 Error in Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-repairing-damaged-windows-system-files/"><u>Step-by-Step Guide: Repairing Damaged Windows System Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tips-for-correcting-the-rpc-server-unavailable-error-on-windows-machines/"><u>Step-by-Step Tips for Correcting the 'RPC Server Unavailable Error' On Windows Machines</u></a></li>
<li><a href="https://some-skills.techidaily.com/strategies-for-incorporating-b-roll-in-video-projects-for-2024/"><u>Strategies for Incorporating B-Roll in Video Projects for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-resolving-the-windows-update-failed-with-error-80244019/"><u>Troubleshooting Guide for Resolving the 'Windows Update Failed with Error 80244019'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-when-google-chrome-wont-respond/"><u>Troubleshooting Guide for When Google Chrome Won't Respond</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/ultimate-gear-guide-for-streaming-sensations-for-2024/"><u>Ultimate Gear Guide for Streaming Sensations for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-file-explorer-guide-enhance-your-organization-and-efficiency-skills/"><u>Windows 11 File Explorer Guide: Enhance Your Organization & Efficiency Skills!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winupdate-trouble-learn-how-to-restart-and-resolve-issues-quickly/"><u>WinUpdate Trouble? Learn How to Restart and Resolve Issues Quickly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/your-sd-card-not-detected-heres-the-fix/"><u>Your SD Card Not Detected? Here’s the Fix</u></a></li>
</ul></div>
