---
title: "The Endgame: Resolving NVIDIA Installation Issues"
date: 2024-08-19T07:28:55.578Z
updated: 2024-08-20T07:28:55.578Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes The Endgame: Resolving NVIDIA Installation Issues"
excerpt: "This Article Describes The Endgame: Resolving NVIDIA Installation Issues"
thumbnail: https://thmb.techidaily.com/897a54d20c0fe274d0937962de97f84511515ba57539d3344fb75e1f209995c6.png
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-serenity-in-strings-the-top-20-calming-country-songs-tiktok/"><u>[New] 2024 Approved  Serenity in Strings  The Top 20 Calming Country Songs (TikTok)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-address-tweets-stuck-while-watching-online/"><u>[New] Address  Tweets Stuck While Watching Online</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-the-leading-edge-in-online-advertising-fb-insights/"><u>[New] In 2024, The Leading Edge in Online Advertising   FB Insights</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-perfect-your-video-calls-essential-10-free-recording-solutions-for-slack/"><u>[Updated] 2024 Approved  Perfect Your Video Calls  Essential 10 Free Recording Solutions for Slack</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-proven-methods-to-improve-macro-video-quality-and-aesthetics/"><u>[Updated] Proven Methods to Improve Macro Video Quality and Aesthetics</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-uncover-5-powerful-speech-recognition-tools-for-your-mac/"><u>[Updated] Uncover 5 Powerful Speech Recognition Tools for Your Mac</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-alternate-escapades-where-the-gta-v-lives-are-missing/"><u>2024 Approved  Alternate Escapades - Where the GTA V Lives Are Missing</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-top-10-best-drones-for-kids-and-beginners/"><u>2024 Approved  Top 10 Best Drones for Kids and Beginners</u></a></li>
<li><a href="https://win-howtos.techidaily.com/acer-quiet-mode-dilemma-solved-bring-back-the-boom-with-easy-fixes/"><u>Acer Quiet Mode Dilemma Solved: Bring Back the Boom with Easy Fixes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/audio-interface-innovations-for-optimal-podcasting/"><u>Audio Interface Innovations for Optimal Podcasting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/connect-microsoft-display-adapter-to-windows-10-successfully-a-comprehensive-fix/"><u>Connect Microsoft Display Adapter to Windows 10 Successfully – A Comprehensive Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-non-functional-aoc-monitors-in-windows-10-environments/"><u>Diagnosing and Repairing Non-Functional AOC Monitors in Windows 10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-your-steelseries-arctis-5-headset-microphone-expert-advice/"><u>Diagnosing and Repairing Your SteelSeries Arctis 5 Headset Microphone: Expert Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/discord-voice-channels-now-responsive/"><u>Discord Voice Channels Now Responsive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-address-xerox-printing-software-update-issue-facing-error-0x800f020b-on-windows-pcs/"><u>Effective Solutions to Address Xerox Printing Software Update Issue – Facing Error 0X800F020B on Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-fix-the-scroll-wheel-on-a-logitech-mouse-failure/"><u>Effective Solutions to Fix the Scroll Wheel on a Logitech Mouse Failure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-visuals-on-windows-10-a-guide-to-resolving-pixelated-characters-and-text/"><u>Enhance Visuals on Windows 10: A Guide to Resolving Pixelated Characters & Text</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-how-to-bypass-preparing-to-configure-windows-dilemma/"><u>Fixed! How to Bypass 'Preparing to Configure Windows' Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-nonfunctional-laptop-trackpad-on-windows-11-8-and-7-expert-solutions/"><u>Fixing a Nonfunctional Laptop Trackpad on Windows 11, 8 & 7 – Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-error-code-0x8024200d-successful-resolution-of-windows-update-issues/"><u>Fixing Error Code 0X8024200D: Successful Resolution of Windows Update Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-why-copy-paste-functionality-isnt-working-on-windows-11/"><u>Fixing the Issue: Why Copy-Paste Functionality Isn't Working on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unregistered-class-errors-in-windows-11-efficiently/"><u>How to Fix Unregistered Class Errors in Windows 11 Efficiently</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-xiaomi-mix-fold-3-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Xiaomi Mix Fold 3</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-failed-windows-1n-update-problems-on-your-pc/"><u>How to Resolve Failed Windows 1N Update Problems on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-stop-windows-10-from-stuck-on-looping-system-recovery-mode-and-constant-restarts/"><u>How to Stop Windows 10 From Stuck on Looping System Recovery Mode and Constant Restarts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-stop-your-pc-from-continuously-restarting-on-win-11-and-win-10/"><u>How to Stop Your PC From Continuously Restarting on Win 11 and Win 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-repair-windows-1011s-update-error-decode-and-fix-error-0x802errordescription-solutionkeyword/"><u>How to Successfully Repair Windows 10/11'S Update Error: Decode and Fix Error 0X802([error_description]) [Solution_keyword]</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-note-30i-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Note 30i to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/identifying-and-resolving-high-sound-levels-in-your-ps4-system/"><u>Identifying & Resolving High Sound Levels in Your PS4 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-solutions-stop-counter-strike-go-from-crashing-now/"><u>Immediate Solutions: Stop Counter-Strike Go From Crashing Now!</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-apple-iphone-6-in-3-ways-drfone-by-drfone-virtual-ios/"><u>In 2024, Edit and Send Fake Location on Telegram For your Apple iPhone 6 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-motorola-razr-40-ultra-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Motorola Razr 40 Ultra in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/kernel32dll-fixes-and-tips-for-win/"><u>Kernel32.dll: Fixes and Tips for Win</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-fixes-for-error-8007000e-during-windows-updates/"><u>Mastering Fixes for Error 8007000E During Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-windows-11-bluetooth-connectivity-problems-with-these-simple-fixes/"><u>Resolve Your Windows 11 Bluetooth Connectivity Problems with These Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-fortnite-on-incompatible-windows-graphics-cards/"><u>Resolved: Fixing Fortnite on Incompatible Windows Graphics Cards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-steps-for-failed-windows-10-may-2019-version-updates/"><u>Resolved: Troubleshooting Steps for Failed Windows 10 May 2019 Version Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-for-applicationexe-has-stopped-working-issue-on-your-computer/"><u>Solution Steps for 'Application.exe Has Stopped Working' Issue on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-defective-usb-ports-in-windows-11-systems/"><u>Solving the Issue of Defective USB Ports in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-resolved-fixes-for-non-functional-hardware-connected-to-your-computer/"><u>Successfully Resolved: Fixes for Non-Functional Hardware Connected to Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-troubleshooting-unresponsive-google-chrome-expert-advice-and-solutions/"><u>Successfully Troubleshooting Unresponsive Google Chrome: Expert Advice & Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackle-common-dll-errors-proven-fixes-for-windows-users-expert-guide/"><u>Tackle Common Dll Errors: Proven Fixes for Windows Users [Expert Guide]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/touch-deficit-on-hid-certified-device-rectified/"><u>Touch Deficit on HID-Certified Device Rectified</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-failed-initialization-of-newly-fixed-renderer-features/"><u>Troubleshooting and Resolving Failed Initialization of Newly Fixed Renderer Features</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212125104-troubleshooting-audio-issues-on-windows-11-get-your-volume-back/"><u>Troubleshooting Audio Issues on Windows 11 - Get Your Volume Back</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-fixed-video-file-cannot-be-displayed-error-code-224003/"><u>Troubleshooting Guide for Fixed 'Video File Cannot Be Displayed' Error (Code #224003)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-device-detection-issues-in-windows-10s-bluetooth/"><u>Troubleshooting Guide: Fixing Device Detection Issues in Windows 10'S Bluetooth</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-device-detection-issues-in-windows-11-via-bluetooth/"><u>Troubleshooting Guide: Resolving Device Detection Issues in Windows 11 via Bluetooth</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-when-your-printscreen-key-fails-on-win10win11-systems/"><u>Troubleshooting Tips for When Your PrintScreen Key Fails on Win10/Win11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-correcting-the-libraries-loaderror-code-1114-on-pcs/"><u>Understanding and Correcting the Libraries LoadError (Code: 1114) on PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-frozen-steam-software-enhancement-with-these-simple-tips/"><u>Unstick Your Frozen Steam Software Enhancement with These Simple Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-curbing-unwanted-processes/"><u>Windows 10: Curbing Unwanted Processes</u></a></li>
</ul></div>
