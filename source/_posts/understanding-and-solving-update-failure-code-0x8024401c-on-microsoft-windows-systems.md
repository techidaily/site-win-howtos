---
title: "Understanding & Solving Update Failure: Code 0X8024401c on Microsoft Windows Systems"
date: 2025-01-08T17:22:59.444Z
updated: 2025-01-13T16:38:14.490Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Understanding & Solving Update Failure: Code 0X8024401c on Microsoft Windows Systems"
excerpt: "This Article Describes Understanding & Solving Update Failure: Code 0X8024401c on Microsoft Windows Systems"
thumbnail: https://thmb.techidaily.com/300ab8d5976ccf31b0d2970939ae583f50bd954e838c66ca43450f63be8d3d0c.jpg
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
<li><a href="https://facebook-video-footage.techidaily.com/new-mastering-360-degree-videos-secure-youtube-uploads/"><u>[New] Mastering 360-Degree Videos Secure YouTube Uploads</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-step-by-step-for-turning-your-vids-into-beats-on-insta/"><u>[New] The Step-by-Step for Turning Your Vids Into Beats on Insta</u></a></li>
<li><a href="https://extra-hints.techidaily.com/brighten-iphones-night-scenes-using-simple-tricks-for-2024/"><u>Brighten iPhone's Night Scenes Using Simple Tricks for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/critical-components-of-windows-update-identification-and-repair-techniques/"><u>Critical Components of Windows Update – Identification and Repair Techniques</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/essential-antivirus-solutions-for-ios-devices-top-picks-for-safeguarding-your-iphone/"><u>Essential Antivirus Solutions for iOS Devices – Top Picks for Safeguarding Your iPhone</u></a></li>
<li><a href="https://win-studio.techidaily.com/essential-strategies-for-efficient-image-data-preservation-in-windows-servers-ranked-4-techniques/"><u>Essential Strategies for Efficient Image Data Preservation in Windows Servers: Ranked #4 Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-laptops-non-charging-battery-in-no-time-simple-solutions/"><u>Fix Your Laptop's Non-Charging Battery in No Time: Simple Solutions</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-oppo-a79-5g-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Oppo A79 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-of-a-dead-razer-keyboard-that-wont-light-up/"><u>Solving the Mystery of a Dead Razer Keyboard That Won't Light Up</u></a></li>
<li><a href="https://win-solutions.techidaily.com/stardew-valley-stutter-fix-ensuring-smooth-playtime-on-your-desktop/"><u>Stardew Valley Stutter Fix: Ensuring Smooth Playtime on Your Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-windows-righ-click-not-responding-on-your-mouse/"><u>Step-by-Step Guide: Resolving Windows ˈrigh Click Not Responding on Your Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-solution-to-the-persistent-fatal-error-and-game-crash-issues-in-halo-4-ue4/"><u>The Ultimate Solution to the Persistent Fatal Error and Game Crash Issues in Halo 4 UE4</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-oneplus-nord-3-5g-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 OnePlus Nord 3 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fixes-guide-for-windows-users-resolving-the-frustrating-error-code-0x80072f8f-on-your-windows-1110-machine/"><u>Ultimate Fixes Guide for Windows Users: Resolving the Frustrating 'Error Code 0X80072F8F' On Your Windows 11/10 Machine</u></a></li>
<li><a href="https://games-able.techidaily.com/uncovering-java-games-standout-characteristics/"><u>Uncovering Java Games’ Standout Characteristics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/usb-woes-no-more-restore-compatibility-with-these-simple-fixes-for-your-hp-laptops-usb-problems/"><u>USB Woes No More: Restore Compatibility with These Simple Fixes for Your HP Laptop’s USB Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-error-resolved-fixing-class-not-registered-complications-successfully/"><u>Windows 11 Error Resolved: Fixing 'Class Not Registered' Complications Successfully</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

