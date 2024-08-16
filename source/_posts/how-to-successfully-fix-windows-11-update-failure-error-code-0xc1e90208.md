---
title: "How to Successfully Fix Windows 11 Update Failure (Error Code: 0XC1e90208)"
date: 2024-08-15T11:41:12.587Z
updated: 2024-08-16T11:41:12.587Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Successfully Fix Windows 11 Update Failure (Error Code: 0XC1e90208)"
excerpt: "This Article Describes How to Successfully Fix Windows 11 Update Failure (Error Code: 0XC1e90208)"
thumbnail: https://thmb.techidaily.com/452af84849e74b7985a3e6edc7ef7272ddba7eb347d5e3359e01777aab493b95.png
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://facebook-clips.techidaily.com/new-prime-facebook-extra-tools-secure-file-grabber-optimized-for-ff-for-2024/"><u>[New] Prime Facebook Extra Tools  Secure File Grabber, Optimized For FF for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-guide-to-choosing-ideal-youtube-thumbnail-shapes/"><u>[Updated] 2024 Approved  Guide to Choosing Ideal Youtube Thumbnail Shapes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-top-mac-screen-recorders-ranked-a-comprehensive-analysis/"><u>[Updated] 2024 Approved  Top Mac Screen Recorders Ranked  A Comprehensive Analysis</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-iphone-tutorial-snap-and-stream-simultaneously/"><u>2024 Approved  IPhone Tutorial  Snap and Stream Simultaneously</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/a-roadmap-for-monetization-success-on-youtube-via-adsense-for-2024/"><u>A Roadmap for Monetization Success on YouTube via AdSense for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/achieving-profitability-at-half-a-million-viewers-for-2024/"><u>Achieving Profitability at Half a Million Viewers for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/activation-loop-breaker-engaged/"><u>Activation Loop Breaker Engaged</u></a></li>
<li><a href="https://win-howtos.techidaily.com/astro-a40-headset-mic-problems-effective-fixes-that-worked-for-me/"><u>Astro A40 Headset Mic Problems: Effective Fixes That Worked for Me</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210762505-bid-farewell-to-keyboard-delays-on-your-windows-10-machine-heres-the-solution/"><u>Bid Farewell to Keyboard Delays on Your Windows 10 Machine - Here's the Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-invalid-registry-error-on-windows-11-for-easy-image-file-access/"><u>Bypass 'Invalid Registry' Error on Windows 11 for Easy Image File Access</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-the-headache-of-werfaultexe-errors-with-these-effortless-repair-strategies/"><u>Bypass the Headache of werFault.exe Errors With These Effortless Repair Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-guide-to-restoring-d3dxt9v39dll-files-no-more-errors/"><u>Complete Guide to Restoring d3dxt9_v39.dll Files: No More Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-resolving-the-cannot-find-source-file-0x80070solved-windows-update-error/"><u>Comprehensive Guide: Resolving the 'Cannot Find Source File' - 0X80070^[SOLVED] Windows Update Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-strategies-to-address-and-correct-stop-error-0xc00000e9-in-microsoft-windows/"><u>Comprehensive Strategies to Address and Correct Stop Error 0xC00000E9 in Microsoft Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-to-fix-mouse-moving-on-its-own/"><u>Easy to Fix Mouse Moving on Its Own</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-to-reactivate-your-unresponsive-corsair-keyboard-now/"><u>Effective Fixes to Reactivate Your Unresponsive Corsair Keyboard Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-to-lower-dwms-heavy-gpu-load-in-windows-10-and-windows-11-environments/"><u>Effective Strategies to Lower DWM's Heavy GPU Load in Windows 10 and Windows 11 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ensure-crystal-clear-communication-on-ps4-solving-built-in-mic-malfunctions-effortlessly/"><u>Ensure Crystal Clear Communication on PS4: Solving Built-In Mic Malfunctions Effortlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-2024-on-dota-2-change-rendering-api-swift-tips-for-an-immediate-fix/"><u>Error 2024 on Dota 2 [Change Rendering API] - Swift Tips for an Immediate Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-correcting-the-frustrating-livekernelevent-144-fault/"><u>Expert Tips for Correcting the Frustrating 'LiveKernelEvent 144' Fault</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-issue-when-your-windows-10-lacks-a-coprocessor-driver/"><u>Fixing the Issue When Your Windows 10 Lacks a Coprocessor Driver</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unspecified-error-code-0x80004005-for-smooth-operations/"><u>How to Fix 'Unspecified Error' (Code 0X80004005) for Smooth Operations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-minecrafts-error-5-issue-effective-solutions-and-tips/"><u>How to Fix Minecraft's Error 5 Issue: Effective Solutions and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-a-malfunctioning-spacebar-key-in-microsofts-latest-operating-system/"><u>How to Repair a Malfunctioning Spacebar Key in Microsoft's Latest Operating System</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-xr-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-drfone-by-drfone-ios/"><u>How to Unlock iPhone XR With an Apple Watch & What to Do if It Doesnt Work | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/m1-advantages-in-high-quality-video-production-workstations-for-2024/"><u>M1 Advantages in High-Quality Video Production Workstations for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-fix-for-persistent-oddworld-soulstorm-pc-malfunctions-now-playable/"><u>Master the Fix for Persistent Oddworld: Soulstorm PC Malfunctions – Now Playable!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-for-nonfunctional-ethernet-ports-tips-and-tricks-for-windows-117-operating-systems/"><u>Mastering the Fix for Nonfunctional Ethernet Ports: Tips and Tricks for Windows 11/7 Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210445757-multiracial-americans/"><u>Multiracial Americans</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-speeding-up-your-windows-7-startup/"><u>Quick Fixes for Speeding Up Your Windows 7 Startup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-fix-no-device-detected-error-in-icue/"><u>Resolved: How to Fix 'No Device Detected' Error in ICUE</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-gameplay-disruptions-fixing-unsupported-graphic-card-errors-in-fortnite-on-pc/"><u>Resolving Gameplay Disruptions: Fixing Unsupported Graphic Card Errors in Fortnite on PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-svchostexes-excessive-cpu-consumption-issue-in-windows-11/"><u>Resolving Svchost.exe's Excessive CPU Consumption Issue in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-of-disappeared-desktop-icon-clutter-in-windows-11-systems/"><u>Resolving the Issue of Disappeared Desktop Icon Clutter in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speedy-tips-for-overcoming-a-lagging-keyboard-issue/"><u>Speedy Tips for Overcoming a Lagging Keyboard Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-troubleshooting-fixing-ps4-nat-issues-once-and-for-all/"><u>Step-by-Step Troubleshooting: Fixing PS4 NAT Issues Once and For All</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-awake-averse-pc-windows-1011-locked-in-slumber/"><u>The Awake-Averse PC: Windows 10/11 Locked in Slumber</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-future-of-resin-3d-printing-with-elegoos-saturn-4-ultra-a-detailed-review-exploring-its-technological-advancements/"><u>The Future of Resin 3D Printing with Elegoo's Saturn 4 Ultra - A Detailed Review Exploring Its Technological Advancements</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fixes-for-a-broken-or-unresponsive-laptop-trackpad/"><u>The Ultimate Fixes for a Broken or Unresponsive Laptop Trackpad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-tips-for-resolving-a-stalled-torrent-download-problem/"><u>Top Tips for Resolving a Stalled Torrent Download Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-the-e-34878-error-code-in-ps4-systems/"><u>Troubleshooting and Fixing the E-34878 Error Code in PS4 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-unsuccessful-windows-11-build-1607-upgrade-issues/"><u>Troubleshooting Guide: Unsuccessful Windows 11 Build 1607 Upgrade Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-mouse-right-click-issues-on-windows-10-a-step-by-step-guide/"><u>Troubleshooting Mouse Right-Click Issues on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-to-address-parameter-errors-accurately/"><u>Troubleshooting Steps to Address Parameter Errors Accurately</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unplugged-how-to-keep-your-usb-devices-stable-and-connected/"><u>Unplugged? How to Keep Your USB Devices Stable and Connected</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-your-mouse-cursor-keeps-vanishing-in-windows-10-and-how-to-fix-it/"><u>Why Your Mouse Cursor Keeps Vanishing in Windows 10 & How to Fix It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-svchostexe-spikes-in-cpu-utilization-troubleshooting-steps-and-solutions/"><u>Windows 10 Svchost.exe Spikes in CPU Utilization: Troubleshooting Steps & Solutions</u></a></li>
<li><a href="https://buynow-info.techidaily.com/your-essential-buyers-guide-to-premium-portable-gaming-devices/"><u>Your Essential Buyer's Guide to Premium Portable Gaming Devices</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->