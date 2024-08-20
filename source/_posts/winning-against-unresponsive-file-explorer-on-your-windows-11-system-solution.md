---
title: Winning Against Unresponsive File Explorer on Your Windows 11 System [Solution]
date: 2024-08-19T06:47:40.165Z
updated: 2024-08-20T06:47:40.165Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Winning Against Unresponsive File Explorer on Your Windows 11 System [Solution]
excerpt: This Article Describes Winning Against Unresponsive File Explorer on Your Windows 11 System [Solution]
thumbnail: https://thmb.techidaily.com/bfe8f97d519484170998bced830c25ea7c96c9f9fefb2b304db02c765d66484d.jpg
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-apeaksoft-screen-recorder-review/"><u>[New] 2024 Approved  Apeaksoft Screen Recorder Review</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-streamlining-group-chats-on-skype-for-dual-os-environments/"><u>[New] In 2024, Streamlining Group Chats on Skype for Dual OS Environments</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-experience-the-old-school-games-anywhere-with-best-in-class-pc-gb-emulators/"><u>[Updated] 2024 Approved  Experience the Old School Games Anywhere with Best-in-Class PC GB Emulators</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-top-3d-gold-text-effect-sites-on-the-web/"><u>[Updated] 2024 Approved  Top 3D Gold Text Effect Sites on the Web</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-crafting-the-perfect-introduction-15-viral-youtube-video-intros-for-2024/"><u>[Updated] Crafting the Perfect Introduction  15 Viral YouTube Video Intros for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-srt-revisited-direct-conversion-to-subcap/"><u>[Updated] SRT Revisited  Direct Conversion to SUBCAP</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-itel-a05s-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Itel A05s Wont Charge | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/advanced-tutorial-embedding-srt-into-mp4-content/"><u>Advanced Tutorial  Embedding SRT Into MP4 Content</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205342105-arctis-5-mic-not-working-heres-the-ultimate-fix/"><u>Arctis 5 Mic Not Working? Here's The Ultimate Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decode-and-fix-twitch-error-4000-your-comprehensive-guide-to-a-smooth-streaming-experience/"><u>Decode and Fix Twitch Error 4000 - Your Comprehensive Guide to a Smooth Streaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-valorant-gameplay-fps-fixes-and-tips/"><u>Elevate Valorant Gameplay: FPS Fixes and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eliminate-game-disruptions-solving-valorants-screen-tearing-problem-efficiently/"><u>Eliminate Game Disruptions: Solving Valorant's Screen Tearing Problem Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-solutions-to-accelerate-windows-7-booting-performance/"><u>Expert Solutions to Accelerate Windows 7 Booting Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-failed-creation-of-d3d-graphics-device-in-windows-applications-step-by-step-solution/"><u>Fixing Failed Creation of D3D Graphics Device in Windows Applications: Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-error-driver-not-found-for-wacom-pen-and-touchpad-on-windows-10/"><u>Fixing the Error: 'Driver Not Found' For Wacom Pen & Touchpad on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-when-your-screen-doesnt-accept-certain-inputs/"><u>Fixing the Issue When Your Screen Doesn’t Accept Certain Inputs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-repairing-your-windows-stores-damaged-cache-issue-resolved/"><u>Guide to Repairing Your Windows Store's Damaged Cache (ISSUE RESOLVED)</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-4-ways-to-trace-apple-iphone-13-mini-location-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 4 Ways to Trace Apple iPhone 13 mini Location | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-walkthrough-correcting-errors-in-user-profile-logon-services/"><u>In-Depth Walkthrough: Correcting Errors in User Profile Logon Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-keyboards-failing-top-tips-and-tricks-to-restore-your-typing-experience/"><u>Lenovo Keyboards Failing? Top Tips and Tricks to Restore Your Typing Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lsa-defense-reactivated-how-to-secure-your-system-effectively/"><u>LSA Defense Reactivated: How to Secure Your System Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-missing-dll-in-steam-games/"><u>Overcoming Missing DLL in Steam Games</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-guide-to-fixed-kernel32-crashes/"><u>Quick Guide to Fixed Kernel32 Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reinstating-sound-capabilities-on-your-windows-7-pc-restored/"><u>Reinstating Sound Capabilities on Your Windows 7 PC ([Restored])</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repairing-your-lenovos-fn-key-swift-solutions/"><u>Repairing Your Lenovo's FN Key: Swift Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-input-not-recognized-issues-displayed-on-monitors/"><u>Resolving 'Input Not Recognized' Issues Displayed on Monitors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-failed-feature-updates-for-windows-10-v1607-a-step-by-step-guide/"><u>Resolving Failed Feature Updates for Windows 10 v1607: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speaker-noise-elimination-techniques-for-windows-11-and-7-users/"><u>Speaker Noise Elimination Techniques for Windows 11 and 7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-overcoming-hamachi-halted-error/"><u>Step-by-Step Guide to Overcoming Hamachi Halted Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-overcoming-0x80070652-windows-update-errors-easily/"><u>Step-by-Step Guide: Overcoming 0X80070652 Windows Update Errors Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-error-unable-to-access-windows-installer-issues/"><u>Step-by-Step Solution for Error: Unable to Access Windows Installer Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-non-functional-brightness-settings-on-windows-11-devices/"><u>Step-by-Step Solutions for Non-Functional Brightness Settings on Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-overcoming-unexpected-crashes-in-directx-applications/"><u>Troubleshooting Guide: Overcoming Unexpected Crashes in DirectX Applications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-to-resolve-error-8007000e-in-windows-update-without-delay/"><u>Troubleshooting Tips to Resolve Error 8007000E in Windows Update Without Delay</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-making-your-aoc-screen-function-again-in-windows-10-environment/"><u>Troubleshooting Tips: Making Your AOC Screen Function Again in Windows 10 Environment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-why-is-my-spacebar-unresponsive-in-windows-11/"><u>Troubleshooting: Why Is My Spacebar Unresponsive in Windows 11?</u></a></li>
</ul></div>
