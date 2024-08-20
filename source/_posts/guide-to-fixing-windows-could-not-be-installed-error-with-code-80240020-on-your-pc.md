---
title: Guide to Fixing 'Windows Could Not Be Installed' Error with Code 80240020 on Your PC
date: 2024-08-19T06:59:06.663Z
updated: 2024-08-20T06:59:06.663Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Guide to Fixing 'Windows Could Not Be Installed' Error with Code 80240020 on Your PC
excerpt: This Article Describes Guide to Fixing 'Windows Could Not Be Installed' Error with Code 80240020 on Your PC
thumbnail: https://thmb.techidaily.com/f98fdaf89e4bdea6c294906b1ec441a8350731ced113bf3e78f52392f565d416.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
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
<li><a href="https://win-howtos.techidaily.com/resolution-tackle-the-stealthy-culprit-of-elevated-system-load-the-invisible-impacts-of-shell-infra-on-your-windows/"><u>(Resolution) Tackle the Stealthy Culprit of Elevated System Load: The Invisible Impacts Of Shell Infra on Your Windows.</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-educational-journey-through-time-with-top-history-yt-channels/"><u>[New] 2024 Approved  Educational Journey Through Time with Top History YT Channels</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-enhancing-team-call-aesthetics-before-and-after/"><u>[New] In 2024, Enhancing Team Call Aesthetics  Before & After</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-the-ultimate-blueprint-for-permanent-instagram-exit-strategy/"><u>[New] In 2024, The Ultimate Blueprint for Permanent Instagram Exit Strategy</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-intro-excellence-app-your-device-friendly-solution/"><u>[New] Intro Excellence App  Your Device-Friendly Solution</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-top-ios-emulators-reviving-classic-psp-game-experiences-2023-guide/"><u>[Updated] 2024 Approved  Top iOS Emulators Reviving Classic PSP Game Experiences - 2023 Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-simplified-background-editing-in-google-meet-chats/"><u>[Updated] In 2024, Simplified Background Editing in Google Meet Chats</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-laymans-land-easy-to-construct-mc-homes-unlocked-for-2024/"><u>[Updated] Layman's Land  Easy-to-Construct MC Homes Unlocked for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-navigating-the-new-world-of-facebook-updates-for-2024/"><u>[Updated] Navigating the New World of Facebook Updates for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-mysterious-virtual-trove-anonymitys-hidden-gems-of-2023/"><u>2024 Approved  The Mysterious Virtual Trove - Anonymity's Hidden Gems of 2023</u></a></li>
<li><a href="https://android-unlock.techidaily.com/5-solutions-for-htc-unlock-without-password-by-drfone-android/"><u>5 Solutions For HTC Unlock Without Password</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solution-for-the-windows-11-updating-problem-error-code-0xc1900208/"><u>Comprehensive Solution for the Windows 11 Updating Problem - Error Code 0xC1900208</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0xc1900208-on-windows-11-updates-heres-how-you-can-fix-it/"><u>Error 0xC1900208 on Windows 11 Updates? Here’s How You Can Fix It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/halo-4-ue4-debugging-eradicating-the-catastrophic-bug-that-triggered-crashes/"><u>Halo 4 UE4 Debugging: Eradicating the Catastrophic Bug That Triggered Crashes</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-vivo-v27-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-enable-miracast-functionality-on-unsupported-devices-tips-for-2e24/"><u>How to Enable Miracast Functionality on Unsupported Devices - Tips for 2E24</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-missing-mouse-cursor-on-your-windows-10-pc-easily/"><u>How to Fix a Missing Mouse Cursor on Your Windows 10 PC Easily</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-a15-4g-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Samsung Galaxy A15 4G Phone with Broken Screen</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Poco M6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-guide-how-to-check-icloud-activation-lock-status-from-your-apple-iphone-6s-plus-by-drfone-ios/"><u>In 2024, New Guide How To Check iCloud Activation Lock Status From Your Apple iPhone 6s Plus</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-wont-boot-troubleshooting-the-all-too-common-bright-display-problem/"><u>Laptop Won’t Boot? Troubleshooting the All-Too-Common Bright Display Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-technique-of-resolving-critical-fatal-error-during-install-issues-code-1603/"><u>Master the Technique of Resolving Critical 'Fatal Error During Install' Issues (Code 1603)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207304266-no-more-stuttering-screens-just-gameplay/"><u>No More Stuttering Screens, Just Gameplay!</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/t-prospects-analyzing-youtubes-monetization-mechanisms/"><u>Profit Prospects  Analyzing YouTube's Monetization Mechanisms</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212279696-quick-fixes-for-your-non-functioning-mac-webcam-simple-solutions/"><u>Quick Fixes for Your Non-Functioning Mac Webcam – Simple Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207172659-resolve-the-bluetooth-not-found-error-on-windows-10-with-simple-fixes/"><u>Resolve the 'Bluetooth Not Found' Error on Windows 10 with Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-application-unable-to-boot-correctly-a-user-friendly-guide-to-handling-the-0xc000007b-problem/"><u>Resolving 'Application Unable to Boot Correctly' - A User-Friendly Guide to Handling the 0xC000007B Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-microsoft-compatibility-telemetry-memory-and-storage-surges-in-windows-10/"><u>Resolving Microsoft Compatibility Telemetry Memory and Storage Surges in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-geforce-experience-launch-error-a-comprehensive-guide/"><u>Resolving the GeForce Experience Launch Error: A Comprehensive Guide</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/retro-charm-meets-modern-marvels-in-the-latest-ratchet-and-clank-adventure/"><u>Retro Charm Meets Modern Marvels in the Latest Ratchet & Clank Adventure</u></a></li>
<li><a href="https://extra-skills.techidaily.com/simplified-techniques-for-blurring-faces-in-pictures-for-2024/"><u>Simplified Techniques for Blurring Faces in Pictures for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-in-place-eliminate-d3dx939dll-disappearance-troubles-once-and-for-all/"><u>Solution in Place: Eliminate d3dx9_39.dll Disappearance Troubles Once and For All</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-is-getting-ready-stuck-screen-a-step-by-step-guide/"><u>Solving 'Windows Is Getting Ready' Stuck Screen: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-errcachemiss-issue-a-step-by-step-guide-for-chrome-users/"><u>Solving the ERR_CACHE_MISS Issue: A Step-by-Step Guide for Chrome Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-taming-the-beast-of-high-disk-usage-by-microsoft-compatibility-telemetry-on-windows-11-devices/"><u>Step-by-Step Guide: Taming the Beast of High Disk Usage by Microsoft Compatibility Telemetry on Windows 11 Devices</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/top-5-timelapse-recording-software/"><u>Top 5 Timelapse Recording Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-apex-legends-solving-the-anti-cheat-error-quickly-and-easily/"><u>Troubleshooting Apex Legends: Solving the Anti-Cheat Error Quickly & Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-common-csgo-performance-issues-and-crashes/"><u>Troubleshooting Guide for Common CS:GO Performance Issues & Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-restoring-light-on-your-corsair-keyboard/"><u>Troubleshooting Guide: Restoring Light on Your Corsair Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-unsuccessful-attempts-to-connect-to-a-distant-server/"><u>Troubleshooting Unsuccessful Attempts to Connect to a Distant Server</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-obtaining-trustedinstaller-permission-for-file-editing-on-your-pc/"><u>Understanding and Obtaining TrustedInstaller Permission for File Editing on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-update-woes-heres-how-to-tackle-the-failed-version-1803-upgrade-successfully/"><u>Windows 11 Update Woes? Here's How to Tackle the Failed Version 1803 Upgrade Successfully</u></a></li>
</ul></div>
