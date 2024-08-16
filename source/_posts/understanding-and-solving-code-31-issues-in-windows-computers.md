---
title: Understanding and Solving Code 31 Issues in Windows Computers
date: 2024-08-15T11:30:48.959Z
updated: 2024-08-16T11:30:48.959Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Understanding and Solving Code 31 Issues in Windows Computers
excerpt: This Article Describes Understanding and Solving Code 31 Issues in Windows Computers
thumbnail: https://thmb.techidaily.com/9f80d4896e94eaecc9b9d2fa222d6b7ea517f0365f103fdcf83c4e1528970c2b.jpg
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-live-transmission-directly-to-instagram-via-obs/"><u>[New] In 2024, Live Transmission Directly to Instagram via OBS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagrams-hottest-meme-accounts-laughter-and-sorrow-sideshow/"><u>[New] Instagram's Hottest Meme Accounts  Laughter & Sorrow Sideshow</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-navigating-the-concealed-commentary-on-online-media/"><u>[New] Navigating the Concealed Commentary on Online Media</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-ranking-top-online-tutorial-providers-excluding-udemy/"><u>[New] Ranking Top Online Tutorial Providers Excluding Udemy</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-5-inspiring-book-tt-showcases/"><u>[New] Top 5 Inspiring Book TT Showcases</u></a></li>
<li><a href="https://win-howtos.techidaily.com/shutoff-initiated-during-gaming/"><u>[SHUTOFF] Initiated During Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206025152-solved-crash-the-high-cpu-usage-of-your-system-with-these-tricks-no-matter-if-you-are-using-windows-10linux/"><u>[Solved] Crash the High CPU Usage of Your System with These Tricks, No Matter if You Are Using Windows 10/Linux.</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-10-gaming-wonders-offline-ios-masterpieces-without-internet-for-2024/"><u>[Updated] 10 Gaming Wonders – Offline iOS Masterpieces Without Internet for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-animate-and-make-your-own-effects/"><u>[Updated] 2024 Approved  How to Animate and Make Your Own Effects</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-fbx-recorder-alternatives-the-new-era-of-gaming-capture-for-2024/"><u>[Updated] FBX Recorder Alternatives  The New Era of Gaming Capture for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-essential-tech-for-effective-pc-image-capture-the-5-best/"><u>[Updated] In 2024, Essential Tech for Effective PC Image Capture, The 5 Best</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-personalized-packaging-par-excellence-top-shopping-sites-uncovered/"><u>[Updated] Personalized Packaging Par Excellence  Top Shopping Sites Uncovered</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-honor-play-7t-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Honor Play 7T to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-samsung-galaxy-m14-4g-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Samsung Galaxy M14 4G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-windows-11s-constant-cycling-easy-repair-tips-for-persistent-shutdown-problems/"><u>Beat Windows 11'S Constant Cycling - Easy Repair Tips for Persistent Shutdown Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/buffer-free-entertainment-in-kodi-effective-techniques-to-ensure-seamless-playback/"><u>Buffer-Free Entertainment in Kodi: Effective Techniques to Ensure Seamless Playback</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bugs-and-glitches-the-challenges-of-installing-the-newest-windows-10-v1607-patch/"><u>Bugs and Glitches: The Challenges of Installing the Newest Windows 10 v1607 Patch</u></a></li>
<li><a href="https://extra-tips.techidaily.com/building-a-strong-introduction-examples-and-methods-for-2024/"><u>Building a Strong Introduction  Examples & Methods for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-solving-the-unretrievable-preferences-issue-on-geforce-experience/"><u>Diagnosing and Solving the 'Unretrievable Preferences' Issue on GeForce Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-windows-7-launch-speed-top-solutions-to-combat-delays/"><u>Enhance Windows 7 Launch Speed: Top Solutions to Combat Delays!</u></a></li>
<li><a href="https://data-wizards.techidaily.com/expert-approaches-to-healing-video-glitches/"><u>Expert Approaches to Healing Video Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-overcoming-steam-store-connectivity-problems-and-getting-it-running-smoothly/"><u>Expert Guide: Overcoming Steam Store Connectivity Problems and Getting It Running Smoothly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-resolving-power-plugs-detected-yet-no-charge-on-windows-os/"><u>Expert Tips for Resolving Power Plugs Detected, Yet No Charge on Windows OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-restore-ethernet-functionality-in-windows-117-systems/"><u>Expert Tips to Restore Ethernet Functionality in Windows 11/7 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211038452-explorer-down-restore-it-now/"><u>Explorer Down? Restore It Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-unresponsive-screen-interaction-pen-and-touch-solutions/"><u>Fixing Unresponsive Screen Interaction – Pen and Touch Solutions</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-xiaomi-redmi-note-13-5g-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Xiaomi Redmi Note 13 5G Phone | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203802097-how-to-fix-battleye-installation-errors-and-get-back-in-action/"><u>How to Fix BattlEye Installation Errors and Get Back in Action</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-when-your-computer-runs-into-issues-with-windows-10-freezing/"><u>How to Fix When Your Computer Runs Into Issues with Windows 10 Freezing?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-motorola-edge-40-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Motorola Edge 40 by Name | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-precision-audio-picks-top-10-video-to-mp3-convertors/"><u>In 2024, Precision Audio Picks  Top 10 Video-to-Mp3 Convertors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/missing-msvcr71dll-fix-in-sight/"><u>Missing MSVCR71.dll: Fix in Sight</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-errors-in-establishing-a-link-to-remote-servers-effective-fixes/"><u>Overcoming Errors in Establishing a Link to Remote Servers: Effective Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-darkness-how-to-correctly-fix-a-black-screen-in-google-chrome/"><u>Overcoming the Darkness: How to Correctly Fix a Black Screen in Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-11-hurdles-for-a-successful-launch-of-a-virtual-wi-fi-hotspot-insider-tips-and-tricks/"><u>Overcoming Windows 11 Hurdles for a Successful Launch of a Virtual Wi-Fi Hotspot: Insider Tips and Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-how-to-resolve-safari-cant-load-webpage-issues/"><u>Quick Solutions: How to Resolve 'Safari Can't Load Webpage' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quickly-resolve-the-notorious-windows-update-bug-0x80070002/"><u>Quickly Resolve the Notorious Windows Update Bug 0X80070002</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-xiaomi-redmi-12-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Xiaomi Redmi 12</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-keyboard-malfunctions-during-system-boot-up/"><u>Resolved: Keyboard Malfunctions During System Boot-Up</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-invisible-windows-extra-display/"><u>Resolving Invisible Windows Extra Display</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-of-unresponsive-right-clicks-in-windows-11/"><u>Resolving the Issue of Unresponsive Right Clicks in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-the-power-of-a-lazy-logitech-mouse/"><u>Reviving the Power of a Lazy Logitech Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-for-inaccessible-write-operation-in-specific-memory-space-hex-reference/"><u>Solution Found for Inaccessible Write Operation in Specific Memory Space (Hex Reference)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-youtube-sound-issue-fixing-audioplayer-glitches-in-windows-11/"><u>Solving the YouTube Sound Issue: Fixing Audioplayer Glitches in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-microsoft-widi-adapter-connection-failures-on-windows-11-systems/"><u>Step-by-Step Fix: Microsoft WiDi Adapter Connection Failures on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-d3derr-not-available-errors-on-your-pc/"><u>Step-by-Step Guide: Correcting 'D3DERR Not Available' Errors on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-ensuring-smooth-device-integration-post-windows-11-update/"><u>Step-by-Step Guide: Ensuring Smooth Device Integration Post Windows 11 Update</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-oppo-reno-10-5g-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Oppo Reno 10 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-frequent-usb-connection-drops/"><u>Troubleshooting Guide: Resolving Frequent USB Connection Drops</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-initializer-not-starting-updated-fixes-2021-problem/"><u>Troubleshooting the 'Initializer Not Starting [Updated Fixes, 2021]' Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-complete-fix-guide-for-when-vcruntime14tdll-is-undetected/"><u>Troubleshooting: The Complete Fix Guide for When VCRUNTIME14tDLL Is Undetected</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-from-oppo-find-x7-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Oppo Find X7 FRP Bypass</u></a></li>
<li><a href="https://driver-install.techidaily.com/unleash-pc-potential-introducing-fwu-ve1659aoc/"><u>Unleash PC Potential: Introducing FWU vE1659AOC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-valorant-startup-a-guide-to-fixing-infinite-loading-screens/"><u>Unstick Your Valorant Startup: A Guide to Fixing Infinite Loading Screens</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-to-do-when-accessing-windows-security-features-like-smartscreen-is-temporarily-hindered/"><u>What to Do When Accessing Windows Security Features, Like SmartScreen, Is Temporarily Hindered</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-steams-endless-update-loop-solutions-revealed/"><u>Winning the Battle Against Steam's Endless Update Loop - Solutions Revealed</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->