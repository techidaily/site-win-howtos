---
title: How to Fix Windows 10 Error Code 80240020 and Ensure a Smooth Installation Experience
date: 2024-08-15T11:37:00.197Z
updated: 2024-08-16T11:37:00.197Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Windows 10 Error Code 80240020 and Ensure a Smooth Installation Experience
excerpt: This Article Describes How to Fix Windows 10 Error Code 80240020 and Ensure a Smooth Installation Experience
thumbnail: https://thmb.techidaily.com/f0ebef61d0b2c8908bbc43dc1da12abaf166bb4f6229b3a45bf569455ab91d1f.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-ace-your-video-masterful-use-of-hash-tags-in-games/"><u>[New] 2024 Approved  Ace Your Video  Masterful Use of Hash Tags in Games</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-defeat-synthetic-followers-for-true-popularity-peak/"><u>[New] 2024 Approved  Defeat Synthetic Followers for True Popularity Peak</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-spark-interest-and-build-community-through-these-10-igtv-approaches/"><u>[New] 2024 Approved  Spark Interest and Build Community Through These 10 IGTV Approaches</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-a-comprehensive-walkthrough-of-adobe-presenter-recording/"><u>[New] A Comprehensive Walkthrough of Adobe Presenter Recording</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-charting-out-youtubes-financial-strategy-for-nurturing-short-videos/"><u>[New] Charting Out YouTube's Financial Strategy for Nurturing Short Videos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-sustainable-cinematic-solutions-catalog-for-2024/"><u>[New] Sustainable Cinematic Solutions Catalog for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-spacebar-not-working-on-windows-11/"><u>[Solved] Spacebar Not Working on Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-finding-the-sweet-spot-optimal-youtube-video-upload-rates-for-growth/"><u>[Updated] 2024 Approved  Finding the Sweet Spot  Optimal YouTube Video Upload Rates for Growth</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-experience-voice-transformation-list-of-the-best-android-recording-change-apps/"><u>[Updated] Experience Voice Transformation  List of the Best Android Recording Change Apps</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-enhance-editing-efficiency-the-finest-text-plugins-for-ae/"><u>[Updated] In 2024, Enhance Editing Efficiency  The Finest Text Plugins for AE</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-revolutionize-zoom-videos-with-key-conversion-methods-for-2024/"><u>[Updated] Revolutionize Zoom Videos with Key Conversion Methods for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-seamlessly-navigate-to-youtube-video-comments/"><u>[Updated] Seamlessly Navigate to YouTube Video Comments</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-melodies-of-matrimony-romantic-hits-for-the-big-moment/"><u>2024 Approved  Melodies of Matrimony  Romantic Hits for the Big Moment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205342105-arctis-5-mic-not-working-heres-the-ultimate-fix/"><u>Arctis 5 Mic Not Working? Here's The Ultimate Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dell-camera-malfunction-in-windows-solutions-for-reviving-image-capture-features/"><u>Dell Camera Malfunction in Windows - Solutions for Reviving Image Capture Features</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-remedies-for-windows-10-cast-to-device-malfunctions-solutions-inside/"><u>Effective Remedies for Windows 10 Cast To Device Malfunctions – Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fixes-for-when-your-laptop-keeps-docking-into-sleep-mode/"><u>Effortless Fixes for When Your Laptop Keeps Docking Into Sleep Mode</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/essential-finds-critical-6-fb-lite-downloads/"><u>Essential Finds  Critical 6 FB Lite Downloads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-to-repairing-usb-port-issues-in-windows-10-and-11-systems/"><u>Expert Guide to Repairing USB Port Issues in Windows 10 and 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-solutions-to-accelerate-windows-7-booting-performance/"><u>Expert Solutions to Accelerate Windows 7 Booting Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-fixes-for-overcoming-windows-persistent-update-error-code-0x80amelioration-of-update-malfunction/"><u>Fast Fixes for Overcoming Window's Persistent Update Error: Code 0X80amelioration of Update Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-failed-creation-of-d3d-graphics-device-in-windows-applications-step-by-step-solution/"><u>Fixing Failed Creation of D3D Graphics Device in Windows Applications: Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-unable-to-print-to-pdf-on-windows-11/"><u>Fixing the Issue: Unable to Print to PDF on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-automatic-updates-that-arent-working-comprehensive-guide/"><u>Fixing Windows Automatic Updates That Aren't Working – Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-repairing-your-windows-stores-damaged-cache-issue-resolved/"><u>Guide to Repairing Your Windows Store's Damaged Cache (ISSUE RESOLVED)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-lava-yuva-3-pro-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Lava Yuva 3 Pro | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-xiaomi-13t-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Xiaomi 13T Phones with/without a PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-frozen-google-chrome-and-reboot-successfully/"><u>How to Fix a Frozen Google Chrome and Reboot Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-maintain-constant-connection-for-your-wireless-mouse/"><u>How to Maintain Constant Connection for Your Wireless Mouse</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-your-apple-iphone-se-2022-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>How to Unlock Your Apple iPhone SE (2022) Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-iphone-12-pro-device-from-icloud-by-drfone-ios/"><u>In 2024, How to Remove iPhone 12 Pro Device from iCloud</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Lava Yuva 3? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-poco-x6-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Poco X6 Pro Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lsa-defense-reactivated-how-to-secure-your-system-effectively/"><u>LSA Defense Reactivated: How to Secure Your System Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/netflix-trouble-heres-how-to-fix-the-using-a-proxyvpn-error-message/"><u>Netflix Trouble? Here's How to Fix the 'Using a Proxy/VPN' Error Message</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-windows-8-video-editor-easy-avi-file-editing-made-possible-2023-edition/"><u>New 2024 Approved Windows 8 Video Editor Easy AVI File Editing Made Possible - 2023 Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-missing-dll-in-steam-games/"><u>Overcoming Missing DLL in Steam Games</u></a></li>
<li><a href="https://win-howtos.techidaily.com/render-engine-failed-to-launch-solutions-for-21-patching-needs/"><u>Render Engine Failed to Launch - Solutions for 2^1 Patching Needs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-windows-1011-acer-laptop-keys-please/"><u>Revive Windows 10/11 Acer Laptop Keys, Please!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speaker-noise-elimination-techniques-for-windows-11-and-7-users/"><u>Speaker Noise Elimination Techniques for Windows 11 and 7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-overcoming-hamachi-halted-error/"><u>Step-by-Step Guide to Overcoming Hamachi Halted Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-overcoming-0x80070652-windows-update-errors-easily/"><u>Step-by-Step Guide: Overcoming 0X80070652 Windows Update Errors Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-error-unable-to-access-windows-installer-issues/"><u>Step-by-Step Solution for Error: Unable to Access Windows Installer Issues</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/top-3-affordable-switch-game-duplicates-for-2024/"><u>Top 3 Affordable Switch Game Duplicates for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-successful-fixes-on-warframe-patch-errors/"><u>Troubleshooting Successful Fixes on Warframe Patch Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-why-is-my-spacebar-unresponsive-in-windows-11/"><u>Troubleshooting: Why Is My Spacebar Unresponsive in Windows 11?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-windows-bsod-beep-series-error-0xc00000e9/"><u>Ultimate Guide: Resolving the Windows BSOD (Beep Series) Error 0xC00000E9</u></a></li>
<li><a href="https://fox-access.techidaily.com/ultimate-introductory-editor-software-devices/"><u>Ultimate Introductory Editor Software (Devices)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-the-potential-of-file-explorer-in-windows-10-made-easy/"><u>Unlocking the Potential of File Explorer in Windows 10 Made Easy</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-is-my-razer-keyboard-not-lights-fix-and-prevent-this-common-problem/"><u>Why Is My Razer Keyboard Not Lights? Fix and Prevent This Common Problem!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-update-stuck-or-frozen-how-do-i-fix-it/"><u>Windows 10 Update Stuck or Frozen - How Do I Fix It?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->