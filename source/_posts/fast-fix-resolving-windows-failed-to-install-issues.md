---
title: "Fast Fix: Resolving 'Windows Failed To Install' Issues"
date: 2024-08-19T07:27:34.913Z
updated: 2024-08-20T07:27:34.913Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fast Fix: Resolving 'Windows Failed To Install' Issues"
excerpt: "This Article Describes Fast Fix: Resolving 'Windows Failed To Install' Issues"
thumbnail: https://thmb.techidaily.com/6244e9865f3cd047c2f60d5d60d859b9d635a96ea7300f114708b93a9cc09aeb.JPG
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-effortless-webcam-recording-with-vlc-streaming-capabilities/"><u>[New] 2024 Approved  Effortless Webcam Recording with VLC Streaming Capabilities</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-the-gamers-playbook-4-essential-steps-for-recording-games/"><u>[New] 2024 Approved  The Gamer's Playbook  4 Essential Steps for Recording Games</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-how-to-buy-1-million-youtube-views-safely-from-trusted-providers/"><u>[Updated] How to Buy 1 Million YouTube Views Safely From Trusted Providers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-insta-twist-techniques-for-tailoring-your-photos-on-the-fly-for-2024/"><u>[Updated] Insta-Twist Techniques for Tailoring Your Photos on the Fly for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-10-creative-ai-solutions-for-podcast-names-online/"><u>[Updated] Top 10 Creative AI Solutions for Podcast Names Online</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-iphones-easy-path-to-picture-softness-four-key-steps/"><u>2024 Approved  IPhone's Easy Path to Picture Softness (Four Key Steps)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-guide-to-resolving-the-paired-but-not-connected-dilemma-in-windows-11-bluetooth-setup/"><u>A Guide to Resolving the 'Paired but Not Connected' Dilemma in Windows 11 Bluetooth Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-wows-performance-hiccups-learn-how-to-fix-lag-problems-once-and-for-all/"><u>Beat Wow's Performance Hiccups - Learn How To Fix Lag Problems Once And For All</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204758975-bring-back-your-windows-10-bluetooth-effective-solutions-that-work-instantly/"><u>Bring Back Your Windows 10 Bluetooth: Effective Solutions That Work Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208004395-chrome-troubles-eradicate-errnamenotresolved-with-this-easy-method/"><u>Chrome Troubles? Eradicate 'ERR_NAME_NOT_RESOLVED' With This Easy Method</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722966165856-easy-download-and-setup-of-wacom-intuos-pro-driver-for-enhanced-performance-on-windows-nix-systems/"><u>Easy Download and Setup of Wacom Intuos Pro Driver for Enhanced Performance on Windows Nix Systems!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-restore-bluetooth-functionality-on-your-windows-11-system-today/"><u>Easy Steps to Restore Bluetooth Functionality on Your Windows 11 System Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x80072f8f-easy-fix-steps-for-windows-1110-users/"><u>Error Code 0X80072F8F - Easy Fix Steps for Windows 11/10 Users</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/essential-insights-into-valheim-planting-methods-for-2024/"><u>Essential Insights Into Valheim Planting Methods for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-correcting-this-file-cannot-be-played-overcoming-error-224003/"><u>Expert Tips on Correcting 'This File Cannot Be Played' - Overcoming Error 224003</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-d3dxt939dll-error-not-found-heres-how-to-solve-it-effectively/"><u>Fix d3dxt9_39.dll Error Not Found? Here's How to Solve It Effectively!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210007407-fix-invalid-value-for-registry-error-when-opening-photos-on-windows-10/"><u>Fix: “Invalid Value for Registry” Error When Opening Photos on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-malfunctioning-camera-on-lenovo-laptops-practical-solutions/"><u>Fixing a Malfunctioning Camera on Lenovo Laptops - Practical Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-malfunctioned-function-keys-a-step-by-step-guide/"><u>Fixing Malfunctioned Function Keys: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-unregistered-class-errors-in-windows-11-a-step-by-step-guide/"><u>Fixing Unregistered Class Errors in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-successfully-overcoming-the-notorious-0x80244022-error-during-windows-updates/"><u>Guide: Successfully Overcoming the Notorious 0X80244022 Error During Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-error-code-0x80004005-in-microsoft-exchange-step-by-step-guide/"><u>How to Fix the Error Code 0X80004005 in Microsoft Exchange - Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-issue-when-your-print-driver-host-ceases-on-32-bit-software/"><u>How to Fix the Issue When Your Print Driver Host Ceases on 32 Bit Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-speaker-noise-interference-in-your-windows-pc-a-step-by-step-guide-for-win11win7-users/"><u>How to Resolve Speaker Noise Interference in Your Windows PC – A Step-by-Step Guide for Win11/Win7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-cast-feature-between-devices-on-windows-11-issue-solved/"><u>How to Restore Cast Feature Between Devices on Windows 11 (Issue Solved)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-volume-functionality-on-your-windows-10-pc-solved/"><u>How To Restore Volume Functionality On Your Windows 10 PC (Solved)</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-honor-x7b-by-fonelab-android-recover-music/"><u>How to retrieve erased music from Honor X7b</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-infinix-smart-8-plus-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Infinix Smart 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-se-2020-with-imei-code-by-drfone-ios/"><u>How to Unlock iPhone SE (2020) with IMEI Code?</u></a></li>
<li><a href="https://windows11.techidaily.com/identify-and-solve-hidden-disk-space-problems-in-windows/"><u>Identify & Solve Hidden Disk Space Problems in Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-samsung-galaxy-m34-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Samsung Galaxy M34 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-xiaomi-mix-fold-3frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Xiaomi Mix Fold 3FRP Lock</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-the-complete-guide-to-gopro-hero5/"><u>In 2024, The Complete Guide to GoPro Hero5</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unleash-your-stream-potential-on-youtube-with-just-a-handful-of-followers/"><u>In 2024, Unleash Your Stream Potential on YouTube with Just a Handful of Followers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-10-fix-guide-how-to-show-hidden-taskbar/"><u>Mastering Windows 10: Fix Guide - How To Show Hidden Taskbar</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pro-fishing-cams-ranked-your-ultimate-guide/"><u>Pro-Fishing Cams Ranked  Your Ultimate Guide</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-for-handling-the-lack-of-msvcr120dll-in-windows/"><u>Quick Tips for Handling the Lack of MSVCR120.DLL in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-ps4-controllers-ultimate-fixes-for-non-charging-problems/"><u>Revive Your PS4 Controllers! Ultimate Fixes for Non-Charging Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-an-inactive-google-chrome-browser-with-swift-reload-strategies/"><u>Reviving an Inactive Google Chrome Browser with Swift Reload Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-nvidia-web-helper-no-disk-error/"><u>Solved Nvidia Web Helper No Disk Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-lenovo-laptop-camera-issues-a-step-by-step-fix/"><u>Solving Lenovo Laptop Camera Issues - A Step-by-Step Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-lenovo-wireless-connectivity-issues-missing-or-incorrect-drivers/"><u>Solving Lenovo Wireless Connectivity Issues: Missing or Incorrect Drivers</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Nokia G22? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/the-detailed-review-comparing-amds-rx-7800xt-with-7700xt-series/"><u>The Detailed Review: Comparing AMD's RX 7800XT with 7700XT Series</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/top-budget-friendly-android-video-callers/"><u>Top Budget-Friendly Android Video Callers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/touchpad-not-scrolling-heres-how-to-get-it-working-again/"><u>Touchpad Not Scrolling? Here's How to Get It Working Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-fixing-a-stuck-warframe-game-update/"><u>Troubleshooting Steps: Fixing a Stuck Warframe Game Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unreal-and-d3d-a-precarious-future-relationship/"><u>Unreal and D3D: A Precarious Future Relationship</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-realme-12plus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-youtube-sound-glitches-learn-how-to-tackle-audio-renderer-troubles-effectively/"><u>Windows 11 YouTube Sound Glitches? Learn How to Tackle Audio Renderer Troubles Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-sluggish-keys-on-your-pcs-os-fixes-and-tips-for-windows-10/"><u>Winning the Battle Against Sluggish Keys on Your PC's OS: Fixes & Tips for Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/winstall-workflows-for-smooth-windows-11-app-installation/"><u>Winstall Workflows for Smooth Windows 11 App Installation</u></a></li>
</ul></div>
