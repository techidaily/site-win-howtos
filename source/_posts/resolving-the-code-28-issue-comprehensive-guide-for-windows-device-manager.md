---
title: "Resolving the 'Code 28' Issue: Comprehensive Guide for Windows Device Manager"
date: 2024-08-15T11:20:04.177Z
updated: 2024-08-16T11:20:04.177Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the 'Code 28' Issue: Comprehensive Guide for Windows Device Manager"
excerpt: "This Article Describes Resolving the 'Code 28' Issue: Comprehensive Guide for Windows Device Manager"
thumbnail: https://thmb.techidaily.com/290fdfbe7988bc73a9658535e5e89697be7bda898900fabab3b9425630194609.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-the-future-of-game-logging-exciting-alternatives-to-fbx-centric-apps/"><u>[New] 2024 Approved  The Future of Game Logging  Exciting Alternatives to FBX-Centric Apps</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-things-that-you-should-know-about-youtube-keyword-research/"><u>[New] 2024 Approved  Things That You Should Know About YouTube Keyword Research</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-saving-window-views-on-pcs-from-winxp-to-11/"><u>[New] Saving Window Views on PCs From WinXP to 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-revamp-your-tone-7-premier-vocal-modification-tools-for-2024/"><u>[Updated] Revamp Your Tone  7 Premier Vocal Modification Tools for 2024</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/3-solutions-to-find-your-apple-iphone-12-mini-current-location-of-a-mobile-number-drfone-by-drfone-virtual-ios/"><u>3 Solutions to Find Your Apple iPhone 12 mini Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Vivo X100 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/apex-legends-cheats-detected-warning-fixed/"><u>Apex Legends Cheats Detected Warning Fixed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/breezing-through-troubleshooting-fatal-glitches-in-cxfreeze/"><u>Breezing Through Troubleshooting Fatal Glitches in Cx_Freeze</u></a></li>
<li><a href="https://android-frp.techidaily.com/complete-mac-hdd-setup-via-visual-instructional-video/"><u>Complete Mac HDD Setup via Visual Instructional Video</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decode-and-correct-the-144-kernel-event-problem-in-your-system-with-ease/"><u>Decode and Correct the 144 Kernel Event Problem in Your System with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-fix-non-working-windows-key-errors-on-windows-10-devices/"><u>Diagnose and Fix Non-Working Windows Key Errors on Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-solutions-to-resolve-safari-cant-load-webpage-issue/"><u>Easy Solutions to Resolve 'Safari Can't Load Webpage' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-reducing-wudfhostexes-heavy-cpu-demand-on-windows-10/"><u>Effective Solutions for Reducing wudfhost.exe's Heavy CPU Demand on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-no-more-overcome-print-driver-host-malfunction-on-32-bit-platforms/"><u>Error No More! Overcome 'Print Driver Host' Malfunction on 32-Bit Platforms</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-reviving-a-failed-corsair-keyboard-a-step-by-step-guide/"><u>Expert Advice: Reviving a Failed Corsair Keyboard - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-lenovo-mouse-pad-issues-on-windows-10-8-and-7-step-by-step-solutions/"><u>Fix Lenovo Mouse Pad Issues on Windows 10, 8 & 7: Step-by-Step Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-there-was-a-problem-resetting-your-pc-error-on-windows-11-solved/"><u>Fix There Was a Problem Resetting Your PC Error on Windows 11 [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-how-to-get-your-corsair-keyboard-back-in-action/"><u>Fixing the Issue: How to Get Your Corsair Keyboard Back in Action</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fortnite-successfully-started-now/"><u>Fortnite: Successfully Started Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-resetting-issues-and-solve-reset-failed-due-to-an-issue-in-windows-11-systems/"><u>How to Overcome Resetting Issues & Solve 'Reset Failed Due To An Issue' In Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-dvd-playback-problems-on-a-windows-operated-computer/"><u>How to Resolve DVD Playback Problems on a Windows-Operated Computer</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-a-step-by-step-guide-to-finding-your-apple-id-on-your-iphone-x-by-drfone-ios/"><u>In 2024, A Step-by-Step Guide to Finding Your Apple ID On Your iPhone X</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-explore-the-10-most-powerful-drawing-tools-on-chrome-os/"><u>In 2024, Explore the 10 Most Powerful Drawing Tools on Chrome OS</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-poco-x6-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Poco X6? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-access-hurdles-proven-strategies-for-approval/"><u>Navigating Access Hurdles: Proven Strategies for Approval</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-windows-update-challenge-clear-error-8007000e-effortlessly/"><u>Overcome Windows Update Challenge: Clear Error 8007000E Effortlessly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/persistent-windows-update-problems-heres-what-you-need-to-do/"><u>Persistent Windows Update Problems? Here's What You Need To Do</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-the-missing-dilemma-a-step-by-step-guide-to-restoring-d3dxtoolkitdll/"><u>Resolve the 'Missing' Dilemma: A Step-by-Step Guide to Restoring d3dxtoolkit.dll</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-of-unplanned-reboots-in-windows-11-a-complete-guide/"><u>Resolving the Issue of Unplanned Reboots in Windows 11 – A Complete Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/smooth-horizontal-fix-on-laptop-screens-quick-and-painless/"><u>Smooth Horizontal Fix on Laptop Screens: Quick & Painless</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210246674-squamous-cell-carcinoma-usually-appears-as-a-central-tumor-and-can-lead-to-local-obstruction-symptoms/"><u>Squamous Cell Carcinoma Usually Appears as a Central Tumor and Can Lead to Local Obstruction Symptoms.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-troubleshooting-inputoutput-device-issues/"><u>Step-by-Step Guide: Troubleshooting Input/Output Device Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stuck-on-a-pdf-that-wont-print-easy-remedies-inside/"><u>Stuck On A PDF That Won't Print? Easy Remedies Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/surface-keyboard-not-working-solved/"><u>Surface Keyboard Not Working [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/swiftly-resolve-missing-dll-errors-on-gaming-platforms/"><u>Swiftly Resolve Missing DLL Errors on Gaming Platforms</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/the-costless-conundrum-of-final-cut-pro-access-for-2024/"><u>The Costless Conundrum of Final Cut Pro Access for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-win-10win-11-scrolling-advantage/"><u>The Win 10/Win 11 Scrolling Advantage</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-resolve-the-irritating-0x80072efd-issue-on-your-windows-11-machine/"><u>Troubleshoot and Resolve the Irritating 0X80072EFD Issue on Your Windows 11 Machine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-igfxem-module-failure-cases/"><u>Troubleshooting Steps for iGFXem Module Failure Cases</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-to-overcome-window-11s-black-screen-dilemma/"><u>Troubleshooting Tips to Overcome Window 11'S Black Screen Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-huion-tablet-5-quick-solutions-when-the-pen-stops-responding/"><u>Troubleshooting Your Huion Tablet: 5 Quick Solutions When the Pen Stops Responding</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-to-do-if-windows-11-doesnt-recognize-your-logitech-keyboard/"><u>What to Do if Windows 11 Doesn't Recognize Your Logitech Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-usb/"><u>Windows 지소프트에서 운영하는 USB 포트가 아무렇지도 않고 사용자의 경우: 해결 방법</u></a></li>
</ul></div>
