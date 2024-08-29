---
title: Step-by-Step Tutorial to Correctly Install Windows 11 Despite Encountering Error Code 80240020
date: 2024-08-28T00:28:44.989Z
updated: 2024-08-29T00:28:44.989Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Tutorial to Correctly Install Windows 11 Despite Encountering Error Code 80240020
excerpt: This Article Describes Step-by-Step Tutorial to Correctly Install Windows 11 Despite Encountering Error Code 80240020
thumbnail: https://thmb.techidaily.com/e68430bcb106e10e6ed671e16682f01d022f0799c626556c343ddc595fa9cde5.jpg
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

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
<li><a href="https://some-knowledge.techidaily.com/new-game-console-sound-amplification-and-modifications-for-ps4ps5/"><u>[New] Game Console Sound Amplification and Modifications for PS4/PS5</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-syncing-tunes-with-video-posts-on-facebook/"><u>[New] In 2024, Syncing Tunes with Video Posts on Facebook</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2023s-finest-top-ps3-game-simulations-for-pc-users-for-2024/"><u>[Updated] 2023'S Finest - Top PS3 Game Simulations for PC Users for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-reimagining-creation-in-the-crypto-world-a-guide-to-top-nft-generating-platforms/"><u>2024 Approved  Reimagining Creation in the Crypto World - A Guide to Top NFT-Generating Platforms</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-hidden-world-of-your-online-footprint-unveiling-facebooks-secrets/"><u>2024 Approved  The Hidden World of Your Online Footprint - Unveiling Facebook’s Secrets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-winodws-update-error-0x8024401c-effective-solutions-for-windows-10-and-11-users/"><u>Beat Winodws Update Error 0X8024401c: Effective Solutions for Windows 10 & 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-methods-to-get-your-usb-flash-drive-recognized-by-windowsmac-quickly/"><u>Effective Methods to Get Your USB Flash Drive Recognized by Windows/Mac Quickly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-when-windows-cant-identify-suitable-printer-drivers/"><u>Effective Solutions for When Windows Can't Identify Suitable Printer Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0xc00solved-troubleshooting-and-fixes-for-windows-users/"><u>Error Code 0XC00#Solved: Troubleshooting and Fixes for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-solutions-to-eliminate-error-0x8024401c-and-restore-seamless-updates-on-your-windows-11-machine/"><u>Expert Solutions to Eliminate Error 0X8024401c & Restore Seamless Updates on Your Windows 11 Machine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-your-steelseries-arctis-5-headsets-broken-microphone-no-more-sorry/"><u>Expert Tips for Repairing Your SteelSeries Arctis 5 Headset's Broken Microphone (NO MORE SORRY)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-problem-what-to-do-when-logitechs-scroll-wheel-malfunctions/"><u>Fixing the Problem: What to Do When Logitech's Scroll Wheel Malfunctions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-secure-connection-failed-errors-in-mozilla-firefox/"><u>How to Fix 'Secure Connection Failed' Errors in Mozilla Firefox</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-realme-v30t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Realme V30T | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-an-airtag-from-your-apple-id-account-from-apple-iphone-15-pro-max-by-drfone-ios/"><u>How to Remove an AirTag from Your Apple ID Account From Apple iPhone 15 Pro Max?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-windows-ts-11-bluetooth-connection-problem-and-start-pairing-your-gadgets/"><u>How to Resolve Windows T's 11 Bluetooth Connection Problem and Start Pairing Your Gadgets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/illuminate-your-pc-effective-solutions-for-overcoming-windows-11s-black-screen-troubles/"><u>Illuminate Your PC: Effective Solutions for Overcoming Windows 11'S Black Screen Troubles</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-behind-the-scenes-unpacking-instagram-stories/"><u>In 2024, Behind the Scenes  Unpacking Instagram Stories</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-xiaomi-redmi-12-5g-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Poco F5 5G? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-vivo-y100-5g-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Vivo Y100 5G Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/level-up-with-no-hassle-the-prime-free-voice-change-for-valorant-gamers-for-2024/"><u>Level Up with No Hassle  The Prime Free Voice Change for Valorant Gamers for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/master-the-art-of-fixing-an-http-500-internal-server-error-with-these-expert-tips/"><u>Master the Art of Fixing an HTTP 500 Internal Server Error with These Expert Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-your-game-security-install-and-configure-battleye-without-a-glitch/"><u>Master Your Game Security - Install and Configure BattlEye Without a Glitch</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/optimizing-your-creative-process-windows-movie-maker-on-windows-8-unveiled-for-2024/"><u>Optimizing Your Creative Process  Windows Movie Maker on Windows 8 Unveiled for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-issues-with-starting-your-hosted-network-feature-on-windows-10-devices/"><u>Overcoming Issues with Starting Your Hosted Network Feature on Windows 10 Devices</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-htc-u23-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on HTC U23 | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/ps5-expansion-leading-external-drives-unveiled/"><u>Ps5 Expansion  Leading External Drives Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210538704-resolving-problem-during-restore-mistake-in-windows-10-fixed/"><u>Resolving 'Problem During Restore' Mistake in Windows 10 – Fixed!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-geforce-experience-launch-problem-a-comprehensive-fix-guide/"><u>Resolving the GeForce Experience Launch Problem: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723201180829-resolving-windows-update-error-code-0x80cuh0002-quickly-and-easily/"><u>Resolving Windows Update Error Code 0X80cuh0002 Quickly and Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-laptop-mousepad-a-resolved-guide-for-windows-11-8-and-7-users/"><u>Reviving Your Laptop Mousepad: A Resolved Guide for Windows 11, 8 & 7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/securing-system-with-proper-msvcp140dll-management/"><u>Securing System with Proper MSVCP140.dll Management</u></a></li>
<li><a href="https://win-howtos.techidaily.com/sharpen-your-windows-11-viewing-experience-fixes-for-unclear-characters/"><u>Sharpen Your Windows 11 Viewing Experience - Fixes for Unclear Characters</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-fixes-for-windows-11-users-struggling-with-the-disappearing-bluetooth-feature/"><u>Simple Fixes for Windows 11 Users Struggling with the Disappearing Bluetooth Feature!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-lenovo-mouse-pad-malfunctions-across-all-windows-os-variants-windows-10-8-and-7/"><u>Solving Lenovo Mouse Pad Malfunctions Across All Windows OS Variants (Windows 10, 8 & 7)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-dilemma-how-to-overcome-windows-update-error-code-0x80070643/"><u>Solving the Dilemma: How to Overcome Windows Update Error Code 0X80070643</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/step-inside-music-agptek-a01-tiny-tech-review/"><u>Step Inside Music: AGPTEK A01 Tiny Tech Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fixing-a-malfunctioning-integrated-webcam-on-a-windows-device/"><u>Step-by-Step Guide to Fixing a Malfunctioning Integrated Webcam on a Windows Device</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-complete-blueprint-record-whatsapp-conversations-effectively-for-2024/"><u>The Complete Blueprint  Record WhatsApp Conversations Effectively for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trimming-unnecessary-processes-in-win10/"><u>Trimming Unnecessary Processes in Win10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-resolve-overwatch-voip-problems-instantly/"><u>Troubleshoot and Resolve Overwatch VOIP Problems Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-missing-bluetooth-settings-in-windows-10-quick-and-easy-methods/"><u>Troubleshoot Missing Bluetooth Settings in Windows 10 - Quick & Easy Methods!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-rdr2-errors-by-expanding-the-virtual-memory-size/"><u>Troubleshoot RDR2 Errors by Expanding the Virtual Memory Size</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-non-functional-usb-ports-on-a-dell-device/"><u>Troubleshooting and Repairing Non-Functional USB Ports on a Dell Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-a-successful-windows-11-patch-application-issue-resolved/"><u>Troubleshooting Steps for a Successful Windows 11 Patch Application: [ISSUE RESOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-successfully-update-your-pc-with-fixes-for-error-0x800f0922-on-windows-11/"><u>Troubleshooting Tips: Successfully Update Your PC with Fixes for Error 0X800f0922 on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fix-for-windows-10-users-solving-google-chrome-cant-load-plugins-errors-easily/"><u>Ultimate Fix for Windows 10 Users: Solving 'Google Chrome Can't Load Plugins' Errors Easily</u></a></li>
<li><a href="https://buynow-info.techidaily.com/1722701037883-unbeatable-prime-day-discounts-sweet-apple-savings-await/"><u>Unbeatable Prime Day Discounts: Sweet Apple Savings Await!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-correcting-unable-to-qualify-in-teredo-networking-scenarios/"><u>Understanding and Correcting 'Unable to Qualify' In Teredo Networking Scenarios</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unsticking-windows-11-updates-solutions-for-when-your-system-freezes/"><u>Unsticking Windows 11 Updates: Solutions for When Your System Freezes</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->