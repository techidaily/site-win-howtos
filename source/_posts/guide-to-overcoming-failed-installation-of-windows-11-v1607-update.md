---
title: Guide to Overcoming Failed Installation of Windows 11 v1607 Update
date: 2024-08-19T06:59:50.085Z
updated: 2024-08-20T06:59:50.085Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Guide to Overcoming Failed Installation of Windows 11 v1607 Update
excerpt: This Article Describes Guide to Overcoming Failed Installation of Windows 11 v1607 Update
thumbnail: https://thmb.techidaily.com/add496faff3567ece40d0c0a25d683b37093fb191cb1e756a607d3720738205f.png
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-replicating-your-best-self-with-finesse-on-tiktok/"><u>[New] 2024 Approved  Replicating Your Best Self with Finesse on TikTok</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-decoding-aspect-ratios-for-effective-youtube-videos/"><u>[New] Decoding Aspect Ratios for Effective YouTube Videos</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-zooming-up-triad-of-effective-video-enhancement-practices/"><u>[New] In 2024, Zooming Up  Triad of Effective Video Enhancement Practices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-breakdown-of-essential-features-in-movie-maker-for-windows-8/"><u>[Updated] In 2024, Breakdown of Essential Features in Movie Maker for Windows 8</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-unlock-likes-by-perfecting-your-square-video-presentation/"><u>[Updated] Unlock Likes by Perfecting Your Square Video Presentation</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-jokes-aplenty-incorrante-guide-to-snapchats-cartoon-filters/"><u>2024 Approved  Jokes Aplenty  Incorrante Guide to Snapchat's Cartoon Filters</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/anaplastic-thyroid-carcinoma-exhibits-a-diverse-array-of-genetic-changes-that-contribute-to-its-aggressive-behavior-and-resistance-to-conventional-treatment152/"><u>Anaplastic Thyroid Carcinoma Exhibits a Diverse Array of Genetic Changes that Contribute to Its Aggressive Behavior and Resistance to Conventional Treatments.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/backspace-key-errors-heres-what-you-need-to-know-and-how-to-solve-it/"><u>Backspace Key Errors? Here's What You Need to Know and How to Solve It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210979060-beat-the-drowsiness-alert-keep-your-computer-awake-easily/"><u>Beat the Drowsiness Alert - Keep Your Computer Awake Easily!</u></a></li>
<li><a href="https://program-issues.techidaily.com/bypassing-fortnites-restrictions-fix-the-you-are-not-allowed-to-play/"><u>Bypassing Fortnite's Restrictions: Fix the 'You Are Not Allowed to Play'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cracking-the-code-on-missing-permissions-in-steam-gaming-software/"><u>Cracking the Code on Missing Permissions in Steam Gaming Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-free-computing-how-to-resolve-the-unable-to-start-dilemma/"><u>Error-Free Computing: How To Resolve the Unable to Start Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-to-stop-warframe-from-failing-on-your-computer/"><u>Expert Advice to Stop Warframe From Failing on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-resolving-minecraft-slowdown-and-improve-fps/"><u>Expert Tips for Resolving Minecraft Slowdown and Improve FPS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-resolving-windows-10-not-responding-during-updates/"><u>Expert Tips for Resolving Windows 10 Not Responding During Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-service-not-responding-on-your-pc-a-guide-to-reactivating-windows-updates/"><u>Fixing 'Service Not Responding' On Your PC - A Guide to Reactivating Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-constant-unrecognized-usb-errors-a-complete-troubleshooting-guide/"><u>Fixing Constant 'Unrecognized USB' Errors: A Complete Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-resolving-window-10-screen-vibrating-problems/"><u>Guide: Resolving Window 10 Screen Vibrating Problems</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/historical-imagery-unleashed-from-copyrights-for-2024/"><u>Historical Imagery Unleashed From Copyrights for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-failed-ssltls-handshake-error-in-firefox-browser/"><u>How to Fix a Failed SSL/TLS Handshake Error in Firefox Browser</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-speaker-distortion-on-windows-11-and-7-a-step-by-step-guide/"><u>How To Fix Speaker Distortion on Windows 11 & 7: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-lost-bluetooth-functionality-on-windows-10-fast-and-easy/"><u>How to Restore Lost Bluetooth Functionality on Windows 10, Fast and Easy</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-the-nuances-of-inshot-video-segments/"><u>In 2024, Navigating the Nuances of Inshot Video Segments</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-oppo-a78-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Oppo A78 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-compatibility-glitches-in-windows-1903-feature-upgrade/"><u>Overcoming Compatibility Glitches in Windows 1903 Feature Upgrade</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-obstacle-of-error-code-0x8024200d-a-troubleshooters-tutorial-for-efficient-windows-updates/"><u>Overcoming the Obstacle of Error Code 0X8024200D: A Troubleshooter's Tutorial for Efficient Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/preventing-unwanted-startups-in-windows-10-a-troubleshooting-guide/"><u>Preventing Unwanted Startups in Windows 10 - A Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-resolving-silent-netflix-a-guide/"><u>Quick Solutions for Resolving Silent Netflix: A Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repair-guide-reactivating-night-light-feature-in-windows-11-operating-system/"><u>Repair Guide: Reactivating Night Light Feature in Windows 11 Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-sudden-end-of-a-program-understanding-error-1067-in-windows/"><u>Resolving the Sudden End of a Program - Understanding Error 1067 in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-10-keyboard-delay-effective-techniques-and-tips/"><u>Resolving Windows 10 Keyboard Delay: Effective Techniques and Tips</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723013432454-solution-for-silent-screens-bring-the-audio-alive-to-roblox-on-your-win11win10-pcs/"><u>Solution for Silent Screens: Bring the Audio Alive to Roblox on Your Win11/Win10 PCs!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-pcs-built-in-camera-woes-a-comprehhavisnce-for-windows-users/"><u>Solve Your PC's Built-In Camera Woes: A Comprehhavisnce for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-common-problems-with-todays-advanced-networked-devices-for-easy-setup/"><u>Solving Common Problems with Today's Advanced Networked Devices for Easy Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speedy-fixes-to-tackle-the-low-battery-detected-error-with-ease/"><u>Speedy Fixes to Tackle the 'Low Battery Detected' Error with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-troubleshooting-tips-for-common-black-ops/"><u>Step-by-Step Troubleshooting Tips for Common Black Ops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-offon-windows-11s-online-scan-feature/"><u>Switching Off/On Windows 11'S Online Scan Feature</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-oppo-reno-10-proplus-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Oppo Reno 10 Pro+ 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-non-functional-print-screen-key-in-win11win10/"><u>Troubleshooting the Non-Functional Print Screen Key in Win11/Win10</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-your-vehicles-malfunctioning-audio-system/"><u>Troubleshooting Your Vehicle's Malfunctioning Audio System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixing-device-not-found-errors-on-windows-1187-systems/"><u>Troubleshooting: Fixing 'Device Not Found' Errors on Windows 11/8/7 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-correcting-the-incorrect-path-or-file-name-problem-in-your-system/"><u>Understanding & Correcting the 'Incorrect Path or File Name' Problem in Your System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unearth-the-missing-touchpad-icon-fix-now/"><u>Unearth the Missing Touchpad Icon, Fix Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-auto-start-discover-the-reasons-behind-your-pcs-self-booting/"><u>Windows 11 Auto-Start: Discover the Reasons Behind Your PC's Self-Booting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-update-error-diagnosis-and-fix-a-closer-look-at-the-database-issue/"><u>Windows 11 Update Error Diagnosis and Fix - A Closer Look at the Database Issue</u></a></li>
</ul></div>
