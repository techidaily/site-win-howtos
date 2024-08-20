---
title: "Error Code 0X80070490 Demystified: Effective Solutions for Fixing Windows Update Glitches"
date: 2024-08-19T07:44:21.101Z
updated: 2024-08-20T07:44:21.101Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 0X80070490 Demystified: Effective Solutions for Fixing Windows Update Glitches"
excerpt: "This Article Describes Error Code 0X80070490 Demystified: Effective Solutions for Fixing Windows Update Glitches"
thumbnail: https://thmb.techidaily.com/e82cf746d7129d54494e27c7a2ced91643ff65f2f3b23f8677650a8fb00dc7f5.png
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
<li><a href="https://fox-helps.techidaily.com/new-in-2024-elevate-collaborative-workflow-enhancing-zoom-use-in-gmail-mail/"><u>[New] In 2024, Elevate Collaborative Workflow  Enhancing Zoom Use in Gmail Mail</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-the-ultimate-mix-of-youtube-and-instagram-feeds/"><u>[Updated] 2024 Approved  The Ultimate Mix of YouTube & Instagram Feeds</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-apexs-single-player-focus-how-to-optimize-your-game-experience/"><u>[Updated] Apex's Single Player Focus  How to Optimize Your Game Experience</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-launching-zoom-sessions-smoothly-with-android/"><u>[Updated] Launching Zoom Sessions Smoothly with Android</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-create-a-3d-text-art-effect-in-adobe-illustrator/"><u>2024 Approved  How to Create a 3D Text Art Effect in Adobe Illustrator</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-disruptions-in-connectivity-to-off-site-servers/"><u>Diagnosing and Repairing Disruptions in Connectivity to Off-Site Servers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-techniques-to-resolve-network-communication-breakdown-in-windows-error-code-0x800704cf/"><u>Effective Techniques to Resolve Network Communication Breakdown in Windows (Error Code 0X800704CF)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-dealing-with-unreachable-dhcp-server-situations-in-your-network/"><u>Expert Tips for Dealing with 'Unreachable DHCP Server' Situations in Your Network</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-the-lenovo-laptop-webcam-malfunction/"><u>Expert Tips for Fixing the Lenovo Laptop Webcam Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-eliminate-windows-10-setup-problem-decode-error-code-80240020/"><u>Expert Tips to Eliminate Windows 10 Setup Problem - Decode Error Code 80240020</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-oddworld-soulstorm-troubleshooting-pc-launch-issues/"><u>Fixing Oddworld: Soulstorm - Troubleshooting PC Launch Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hardware-breakdown-unrecoverable-issue/"><u>Hardware Breakdown: Unrecoverable Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-msmpengexe-high-cpu-usage-in-windows-11-complete-solution/"><u>How to Fix MsMpEng.exe High CPU Usage in Windows 11: Complete Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-initial-black-outages-when-playing-monster-hunter-world/"><u>How to Overcome Initial Black Outages When Playing Monster Hunter: World?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-empowering-tiktok-sharing-on-twitter-networks/"><u>In 2024, Empowering TikTok Sharing on Twitter Networks</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-open-your-iphone-14-without-a-home-button-by-drfone-ios/"><u>In 2024, How To Open Your iPhone 14 Without a Home Button</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-sharp-as-a-razor-toptools-to-unblur-and-enhance-images-online/"><u>In 2024, Sharp as a Razor  #TopTools to Unblur & Enhance Images Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-webcam-troubleshooting-quick-fixes-to-get-you-back-on-camera/"><u>Lenovo Webcam Troubleshooting: Quick Fixes to Get You Back on Camera</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-fixes-a-comprehensive-guide-to-handling-the-0xc0000005-issue/"><u>Mastering Windows Fixes: A Comprehensive Guide to Handling the 0xC0000005 Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mysterious-shade-monitor-malaise/"><u>Mysterious Shade: Monitor Malaise</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-issues-with-component-configuration-in-windows-operating-systems/"><u>Overcoming Issues with Component Configuration in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-lockup-solving-initialization-issues-in-destiny-2/"><u>Overcoming the Lockup: Solving Initialization Issues in Destiny 2</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/professional-tricks-to-fix-your-furry-friends-photo-eyes-flawlessly/"><u>Professional Tricks to Fix Your Furry Friend’s Photo Eyes Flawlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-common-issues-with-initializing-smartaudio/"><u>Resolved: Common Issues with Initializing SmartAudio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-user-profile-service-failures-and-sign-in-issues-on-windows-11/"><u>Resolving 'User Profile Service' Failures and Sign-In Issues on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revolutionized-gaming-pubg-plus-dxgidll-aligned/"><u>Revolutionized Gaming: PUBG + Dxgi.dll Aligned</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212093686-troubleshooting-guide-for-windows-7-10-understanding-event-id-1among-various-operating-systems/"><u>Troubleshooting Guide for Windows 7-10: Understanding Event ID 1Among Various Operating Systems.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-issues-with-your-non-responsive-laptop-trackpad/"><u>Troubleshooting Guide: Fixing Issues with Your Non-Responsive Laptop Trackpad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-fixing-your-laptops-malfunctioning-keyboard-light/"><u>Troubleshooting Steps: Fixing Your Laptop's Malfunctioning Keyboard Light</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-overcoming-the-vcruntime140dll-file-missing-dilemma-resolution-guide/"><u>Troubleshooting Tips: Overcoming the VCRuntime140.dll File Missing Dilemma [RESOLUTION GUIDE]</u></a></li>
<li><a href="https://network-issues.techidaily.com/winos-dxgkrnlsys-error-resolved-blue-screen/"><u>WinOS dxgkrnl.sys Error Resolved - Blue Screen</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->