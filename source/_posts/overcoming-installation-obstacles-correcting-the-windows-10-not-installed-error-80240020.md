---
title: "Overcoming Installation Obstacles: Correcting the 'Windows 10 Not Installed' Error 80240020"
date: 2024-09-05T10:05:33.497Z
updated: 2024-09-06T10:05:33.497Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming Installation Obstacles: Correcting the 'Windows 10 Not Installed' Error 80240020"
excerpt: "This Article Describes Overcoming Installation Obstacles: Correcting the 'Windows 10 Not Installed' Error 80240020"
thumbnail: https://thmb.techidaily.com/f96105d1405f7c845f75622429456df69e9791ebea6985dfc0c6d939ebdaa395.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123482/16836" target="_top" id="2123482">
  <img src="//a.impactradius-go.com/display-ad/16836-2123482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123482/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115918/19272" target="_top" id="2115918">
  <img src="//a.impactradius-go.com/display-ad/19272-2115918" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115918/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-the-best-hashtags-for-youtube-gaming-videos/"><u>[New] 2024 Approved  The Best Hashtags for YouTube Gaming Videos</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-the-complete-snapchat-gif-connoisseurs-guidebook/"><u>[New] 2024 Approved  The Complete Snapchat GIF Connoisseur's Guidebook</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-access-your-favorites-anytime-the-leading-6-free-video-downloaders/"><u>[New] Access Your Favorites Anytime  The Leading 6 Free Video Downloaders</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-captivating-gamer-content-through-obs-streaming-for-2024/"><u>[New] Captivating Gamer Content Through OBS Streaming for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-capturing-life-in-motion-ipad-timelapse-guide/"><u>[New] Capturing Life in Motion  IPad Timelapse Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-advanced-strategies-for-screen-recording-on-ipad/"><u>[New] In 2024, Advanced Strategies for Screen Recording on iPad</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-pair-phonetablet-and-computer-calendars-for-seamless-zoom-scheduling/"><u>[Updated] In 2024, Pair Phone/Tablet & Computer Calendars for Seamless Zoom Scheduling</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-woes-solved-making-sure-your-paired-gadgets-connect-properly-on-windows-11/"><u>Bluetooth Woes Solved: Making Sure Your Paired Gadgets Connect Properly on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208848320-expert-tips-for-resolving-the-windows-10-couldnt-be-installed-error-eb80240020-dilemma-step-by-step-solutions-included/"><u>Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211841404-get-your-windows-10-bluetooth-back-on-track-with-our-step-by-step-guide/"><u>Get Your Windows 10 Bluetooth Back on Track with Our Step-by-Step Guide!</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-pivot-table-field-name-is-not-valid-error-in-excel-2010-by-stellar-guide/"><u>How to fix Pivot Table Field Name is not Valid error in Excel 2010?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-the-0x80070490-error-during-windows-updates-step-by-step-solutions/"><u>How to Overcome the 0X80070490 Error During Windows Updates: Step-by-Step Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-fixing-a-broken-connection-between-windows-and-bluetooth-devices/"><u>How To Restore Functionality: Fixing a Broken Connection Between Windows and Bluetooth Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-resolve-xerox-printers-infamous-error-0x800f020b-on-your-windows-device/"><u>How to Successfully Resolve Xerox Printer's Infamous Error 0X800f020b on Your Windows Device</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-12-pro-max-to-iphone-81111-pro-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer from Apple iPhone 12 Pro Max to iPhone 8/11/11 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-comprehensive-strategies-for-tracking-yt-traffic-and-gains/"><u>In 2024, Comprehensive Strategies for Tracking YT Traffic and Gains</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-consolidated-calendar-management-merge-mobile-and-pc-zoom-dates/"><u>In 2024, Consolidated Calendar Management  Merge Mobile and PC Zoom Dates</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Nubia Red Magic 8S Pro+? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-tracing-your-instagram-fanbase-shifts/"><u>In 2024, Tracing Your Instagram Fanbase Shifts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/managing-windows-11-performance-reducing-msmpengexes-impact-on-your-cpu/"><u>Managing Windows 11 Performance: Reducing MsMpEng.exe’s Impact on Your CPU</u></a></li>
<li><a href="https://win-howtos.techidaily.com/minecraft-opengl-problems-heres-how-to-resolve-them-successfully/"><u>Minecraft OpenGL Problems? Here's How to Resolve Them Successfully!</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-onedrive-sign-in-snags-with-windows-steps/"><u>Navigate Past OneDrive Sign-In Snags with Windows Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-cl-dll-non-existence-errors/"><u>Overcoming Cl-DLL Non-Existence Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-hang-ups-fixes-for-sluggish-or-nonresponsive-chrome-sessions/"><u>Overcoming Hang-Ups: Fixes for Sluggish or Nonresponsive Chrome Sessions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-speed-up-your-league-of-legends-downloads/"><u>Resolved: How to Speed Up Your League of Legends Downloads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-erratic-pixel-dances-in-windows-10-machines/"><u>Resolving Erratic Pixel Dances in Windows 10 Machines</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-comprehensive-guide-on-fixing-windows-update-error-code-80070103/"><u>Resolving the Issue: Comprehensive Guide on Fixing Windows Update Error Code 80070103</u></a></li>
<li><a href="https://techtrends.techidaily.com/restore-power-effective-solutions-when-ps5-controllers-fail-to-charge/"><u>Restore Power: Effective Solutions When PS5 Controllers Fail to Charge</u></a></li>
<li><a href="https://vp-tips.techidaily.com/setting-the-stage-for-success-zoom-configuration-101-for-2024/"><u>Setting the Stage for Success  Zoom Configuration 101 for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-malfunctioning-fn-buttons-on-asus-computer-systems/"><u>Solving Malfunctioning Fn Buttons on Asus Computer Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-halted-diagnostics-policy-application-a-complete-guide/"><u>Troubleshooting a Halted Diagnostics Policy Application: A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210676763-troubleshooting-failed-casting-from-pc-to-peripheral-in-windows-11-resolved/"><u>Troubleshooting Failed Casting From PC to Peripheral in Windows 11 - Resolved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-a-stalled-windows-11-system/"><u>Troubleshooting Guide for a Stalled Windows 11 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-unregistered-classes-on-your-windows-10-system-solved/"><u>Troubleshooting Unregistered Classes on Your Windows 10 System [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-repair-nonfunctioning-keys-on-windows-1011/"><u>Troubleshooting: How to Repair Nonfunctioning Keys on Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-spacebar-malfunction-a-step-by-step-solution-guide/"><u>Windows 10 Spacebar Malfunction - A Step-by-Step Solution Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-startup-black-screen-problem-fixes-and-solutions/"><u>Windows 11 Startup Black Screen Problem – Fixes and Solutions</u></a></li>
</ul></div>
