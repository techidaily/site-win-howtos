---
title: "Master the Fix: Comprehensive Methods to Resolve Error 0X80072FED in Windows 10"
date: 2024-08-15T11:33:17.098Z
updated: 2024-08-16T11:33:17.098Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Master the Fix: Comprehensive Methods to Resolve Error 0X80072FED in Windows 10"
excerpt: "This Article Describes Master the Fix: Comprehensive Methods to Resolve Error 0X80072FED in Windows 10"
thumbnail: https://thmb.techidaily.com/fbcf05b0c32ba329cf6957ae3248e625c39ba58c1a53bbe9519d95b22a1c1295.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

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
<li><a href="https://facebook-video-recording.techidaily.com/new-directly-syncing-your-tiktok-videos-with-facebook/"><u>[New] Directly Syncing Your TikTok Videos with Facebook</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-jest-journal-chronicles-of-timely-laughter/"><u>[New] Jest Journal  Chronicles of Timely Laughter</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-firefox-secerrorunknownissuer-easily/"><u>[Solved] Firefox SEC_ERROR_UNKNOWN_ISSUER | Easily</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-disabling-youtube-ads-across-chrome-firefox-android-and-ios-browsers/"><u>[Updated] 2024 Approved  Disabling YouTube Ads Across Chrome, Firefox, Android & iOS Browsers</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-step-by-step-guide-to-mastering-streamlabs-obs-usage/"><u>[Updated] 2024 Approved  Step-by-Step Guide to Mastering Streamlabs OBS Usage</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-streamlining-workflow-efficient-tools-for-screencast-creation/"><u>[Updated] 2024 Approved  Streamlining Workflow  Efficient Tools for Screencast Creation</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-tech-savvy-approach-to-cutting-out-background-noise-in-google-meet/"><u>[Updated] 2024 Approved  Tech-Savvy Approach to Cutting Out Background Noise in Google Meet</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-iconic-story-arcs-in-cinemas-pantheon/"><u>[Updated] Iconic Story Arcs in Cinema’s Pantheon</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-how-to-record-lectures-on-mac/"><u>[Updated] In 2024, How to Record Lectures on Mac</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-farewell-to-friends-how-to-leave-a-discord-server/"><u>2024 Approved  Farewell to Friends  How to Leave a Discord Server</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-sony-xperia-10-v-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-step-by-step-solution-to-reactivating-a-printer-with-error-code-30/"><u>A Step-by-Step Solution to Reactivating a Printer with Error Code -30</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beating-sims-4-does-not-launch-top-solutions-explored/"><u>Beating 'Sims 4 Does Not Launch': Top Solutions Explored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cant-locate-your-sd-card-here-to-guide-you/"><u>Can't Locate Your SD Card? Here to Guide You!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-for-free-gigabytes-high-quality-sound-driver/"><u>Download for Free: Gigabyte's High-Quality Sound Driver</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-facing-werfaultexe-errors-on-your-pc/"><u>Easy Fixes for Facing werFault.exe Errors on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-dead-lenovo-mousepads-a-cross-platform-win-11-8-and-nw-solution/"><u>Expert Tips for Fixing Dead Lenovo Mousepads: A Cross-Platform Win 11, 8 & Nw Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-user-profile-service-failed-to-sign-in-error-on-windows-pcs/"><u>Fixing the 'User Profile Service Failed to Sign In' Error on Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-frustrating-frozen-windows-update-showing-zero-progress-made-simple/"><u>Fixing the Frustrating Frozen Windows Update Showing Zero Progress Made Simple</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-persistent-0x8024402c-error-during-your-windows-updates-complete-guide/"><u>Fixing the Persistent 0X8024402C Error During Your Windows Updates - Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-sluggish-closure-solutions-to-your-windows-10-shutdown-woes/"><u>Fixing the Sluggish Closure: Solutions to Your Windows 10 Shutdown Woes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212414297-forgotten-sd-card-reclaim-detection-with-ease/"><u>Forgotten SD Card? Reclaim Detection with Ease</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722957419681-get-your-amd-rx-6800-driver-update-now-optimized-for-windows-operating-systems-including-11-10-8-and-7/"><u>Get Your AMD RX 6800 Driver Update Now: Optimized for Windows Operating Systems Including 11, 10, 8 & 7</u></a></li>
<li><a href="https://fox-http.techidaily.com/gopro-hero-5-vs-nikon-km-170-for-adventurers-for-2024/"><u>GoPro HERO 5 vs Nikon KM-170 for Adventurers for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-rectifying-setup-problems-with-your-game-on-origin-platform/"><u>Guide to Rectifying Setup Problems with Your Game on Origin Platform</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hit-compliant-update-addressed-previous-missing-tap-response/"><u>HIT-Compliant Update: Addressed Previous Missing Tap Response</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-unresponsive-function-keys/"><u>How to Troubleshoot Unresponsive Function Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/improve-scanner-connectivity-with-epson-solutions/"><u>Improve Scanner Connectivity with Epson Solutions</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-vivo-s18e-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Vivo S18e Devices | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-itel-p40-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Itel P40 | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-in-game-footage-secrets-of-the-skilled-videographer/"><u>In 2024, In-Game Footage  Secrets of the Skilled Videographer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/local-authority-shield-restored-fortifying-your-defense-layers/"><u>Local Authority Shield Restored - Fortifying Your Defense Layers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastery-in-unfreezing-windows-7-stuck-updates-latest-strategies-for-users-seeking-help-edition-expert-advice-and-tips/"><u>Mastery in Unfreezing Windows 7 Stuck Updates - Latest Strategies for Users Seeking Help Edition (Expert Advice & Tips)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210757311-netflix-not-working-diagnose-and-solve-common-streaming-problems-today/"><u>Netflix Not Working: Diagnose & Solve Common Streaming Problems Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-pcs-to-prevent-win10-cpu-spike/"><u>Optimizing PCs to Prevent Win10 CPU Spike</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-how-to-setup-and-use-bluetooth-devices-with-windows-7/"><u>Quick Fix: How To Setup and Use Bluetooth Devices With Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-restore-flash-player-functionality-on-google-chrome/"><u>Resolved: How to Restore Flash Player Functionality on Google Chrome</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-device-manager-code-41-issues-a-step-by-step-guide/"><u>Resolving Device Manager Code 41 Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-display-connectivity-problems-aoc-usb-monitors-and-windows-11-solutions/"><u>Resolving Display Connectivity Problems: AOC USB Monitors and Windows 11 Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-dilemma-step-by-step-guide-to-overcoming-glexttexturecompression-level-compression-format-opengl-error-1281/"><u>Resolving the Dilemma: Step-by-Step Guide to Overcoming GL_EXT_texture_compression Level Compression Format OpenGL Error #1281</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-keyboard-delays-expert-troubleshooting-steps/"><u>Resolving Windows 11 Keyboard Delays - Expert Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-access-denied-to-device-pathfile-on-windows-troubleshooting-guide/"><u>Solve Access Denied to Device Path/File on Windows – Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-directx-d3d-creation-issues-a-step-by-step-tutorial/"><u>Solving DirectX D3D Creation Issues: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-guide-to-improve-graphic-stability-in-fix-forza-horizon-5-with-updated-drivers/"><u>Step-by-Step Guide to Improve Graphic Stability in Fix Forza Horizon 5 with Updated Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-windows-error-0xc0000098/"><u>Step-by-Step Guide: Resolving Windows Error 0xC0000098</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-restoring-usb-port-functionality-on-windows-1011-machines/"><u>Step-by-Step Guide: Restoring USB Port Functionality on Windows 10/11 Machines</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-7-future-security-insights-for-digital-landscapes/"><u>Top 7 Future Security Insights for Digital Landscapes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-continuous-shutdown-restart-cycles-for-windows-10-computers/"><u>Troubleshoot Continuous Shutdown-Restart Cycles for Windows 10 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-repair-windows-11s-non-working-night-light-mode/"><u>Troubleshooting Guide: How to Repair Windows 11'S Non-Working Night Light Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-malwarebytes-service-disconnect-issue-in-windows-11/"><u>Troubleshooting Malwarebytes Service Disconnect Issue in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-mouse-fixing-right-click-issues-on-windows-11/"><u>Troubleshooting the Mouse: Fixing Right-Click Issues on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-solving-the-problem-of-non-responsive-boot-sequence/"><u>Understanding and Solving the Problem of Non-Responsive Boot Sequence</u></a></li>
<li><a href="https://win-howtos.techidaily.com/victory-over-obs-capture-failures-say-goodbye-to-the-infamous-black-screen/"><u>Victory over OBS Capture Failures: Say Goodbye to the Infamous Black Screen</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/video-playback-time-estimate-a-20mb-file-size-for-2024/"><u>Video Playback Time Estimate  A 20MB File Size for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-groovy-guide-resolve-registry-error-while-opening-pictures/"><u>Windows Groovy Guide: Resolve 'Registry Error' While Opening Pictures</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->