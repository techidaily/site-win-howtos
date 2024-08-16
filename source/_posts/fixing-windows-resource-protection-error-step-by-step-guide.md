---
title: Fixing 'Windows Resource Protection Error' – Step-by-Step Guide
date: 2024-08-15T11:38:34.006Z
updated: 2024-08-16T11:38:34.006Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing 'Windows Resource Protection Error' – Step-by-Step Guide
excerpt: This Article Describes Fixing 'Windows Resource Protection Error' – Step-by-Step Guide
thumbnail: https://thmb.techidaily.com/61dcd74c9ca257bd7a3583ce0e08424eaf979002cdc0aa0e847be271477f189f.jpg
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-how-much-cash-can-you-score-for-watching-a-million-videos/"><u>[New] 2024 Approved  How Much Cash Can You Score for Watching A Million Videos?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-segment-screen-showdown-recorders-leader-status/"><u>[New] 2024 Approved  Segment Screen Showdown  Recorder's Leader Status</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-track-lost-friends-on-instagram/"><u>[New] 2024 Approved  Track Lost Friends on Instagram</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-laptop-battery-not-charging-quickly-and-easily/"><u>[SOLVED] | Laptop Battery Not Charging | Quickly & Easily!</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-boost-your-income-with-effective-vimeo-monetization-techniques-for-2024/"><u>[Updated] Boost Your Income with Effective Vimeo Monetization Techniques for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-shadows-and-highlights-through-photoshop-curves/"><u>[Updated] Mastering Shadows & Highlights Through Photoshop Curves</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-boomerang-edge-captivating-your-instagram-audience-for-2024/"><u>[Updated] The Boomerang Edge  Captivating Your Instagram Audience for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-insiders-guide-to-professional-gif-creation/"><u>[Updated] The Insider's Guide to Professional GIF Creation</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-the-spoken-word-unveiled-enhancing-expressiveness-on-slides-for-2024/"><u>[Updated] The Spoken Word Unveiled  Enhancing Expressiveness on Slides for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-transform-your-videos-into-revenue-streams-with-smart-vimeo-tactics/"><u>[Updated] Transform Your Videos Into Revenue Streams with Smart Vimeo Tactics</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/prehensive-list-of-8-authentic-propagation-tools-for-2024/"><u>A Comprehensive List of 8 Authentic Propagation Tools for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-step-by-step-guide-to-correcting-the-unknown-issuer-error-on-mozilla-firefox/"><u>A Step-by-Step Guide to Correcting the 'Unknown Issuer' Error on Mozilla Firefox</u></a></li>
<li><a href="https://win-howtos.techidaily.com/centralized-management-of-windows-settings-within-corporate-environments/"><u>Centralized Management of Windows Settings Within Corporate Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/coding-process-held/"><u>Coding Process Held</u></a></li>
<li><a href="https://win-howtos.techidaily.com/crackling-audio-issues-how-to-resolve-windows-107-speaker-distortion-problems/"><u>Crackling Audio Issues: How to Resolve Window's 10/7 Speaker Distortion Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeat-the-windows-10-update-hurdle-expert-fixes-for-error-code-0x800f0922/"><u>Defeat the Windows 10 Update Hurdle: Expert Fixes for Error Code 0X800f0922</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210918220-dell-wireless-keyboard-malfunction-heres-how-you-can-get-it-running-again/"><u>Dell Wireless Keyboard Malfunction? Here's How You Can Get It Running Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-the-elevated-cpu-usage-issue-with-wudfhostexe-in-windows-10/"><u>Diagnosing & Fixing the Elevated CPU Usage Issue with WUDFHost.exe in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dial-back-high-cpu-usage-by-wmi/"><u>Dial Back High CPU Usage by WMI</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-persistent-cursor-visibility-issues-on-windows-11-touchpads/"><u>Effective Solutions for Persistent Cursor Visibility Issues on Windows 11 Touchpads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-when-microsofts-print-to-pdf-feature-wont-start-up-on-windows-1011/"><u>Effective Solutions for When Microsoft's Print to PDF Feature Won't Start Up on Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ensuring-seamless-updates-on-windows-overcoming-service-not-running-issues/"><u>Ensuring Seamless Updates on Windows: Overcoming Service Not Running Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-for-nier-automata-pc-game-freezing-issues-resolved/"><u>Fixes for Nier: Automata PC Game Freezing Issues - Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-bring-back-your-missing-windows-10-taskbar-icons-proven-tips-and-techniques/"><u>Guide to Bring Back Your Missing Windows 10 Taskbar Icons: Proven Tips and Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-surface-when-its-plugged-in-but-wont-charge-a-comprehensive-guide/"><u>How to Fix Surface When It's Plugged in But Won't Charge: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-no-signal-on-your-monitor-a-comprehensive-guide/"><u>How To Resolve 'No Signal' On Your Monitor - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-connection-errors-with-microsoft-wireless-display-adapter-in-windows-11/"><u>How to Resolve Connection Errors with Microsoft Wireless Display Adapter in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-livekernelevent-code-144-issue-efficiently/"><u>How to Resolve LiveKernelEvent Code 144 Issue Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-for-winplusshiftpluss-shortcut-on-your-pc-running-windows-1110/"><u>How to Restore Functionality for Win+Shift+S Shortcut on Your PC Running Windows 11/10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-tackle-high-cpu-usage-by-the-system-idle-process-effective-solutions/"><u>How to Tackle High CPU Usage by the 'System Idle Process': Effective Solutions</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-disabled-apple-iphone-7-plusipad-without-computer-drfone-by-drfone-ios/"><u>How to Unlock Disabled Apple iPhone 7 Plus/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-does-find-my-friends-work-on-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-motorola-moto-g24-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Motorola Moto G24 Bootloader Easily</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-honor-v-purse-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Honor V Purse Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Tecno Spark Go (2024) | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/iphone-nightscape-techniques-unlocked/"><u>IPhone Nightscape Techniques Unlocked</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203255101-kb4056892-windows-10-update-wont-install-solved/"><u>KB4056892 Windows 10 Update Won't Install [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-oddworld-soulstorm-on-pc-overcoming-crash-dilemmas-with-simple-solutions/"><u>Mastering Oddworld: Soulstorm on PC – Overcoming Crash Dilemmas with Simple Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-overcoming-service-unavailable-http-error-503/"><u>Quick Fixes for Overcoming 'Service Unavailable' - HTTP Error #503</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-the-missing-d3dcompiler47dll-error-on-your-pc-easily/"><u>Resolve the Missing D3DCOMPILER_47.dll Error on Your PC Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-pcs-windows-update-issues-fixing-error-0x80070002-made-easy/"><u>Resolve Your PC's Windows Update Issues: Fixing Error 0X80070002 Made Easy!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-error-with-writing-to-addressed-memory-location-how-to-fix/"><u>Resolved: Error with Writing to Addressed Memory Location - How to Fix?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-geforce-experience-launch-problems-a-comprehensive-fix-guide/"><u>Resolving GeForce Experience Launch Problems: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-freezes-and-unresponsive-behavior-a-step-by-step-guide/"><u>Resolving Windows 11 Freezes and Unresponsive Behavior: A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/rethinking-recipes-squared-up-tutorials-for-youtube-and-facebook-success-for-2024/"><u>Rethinking Recipes  Squared-Up Tutorials for YouTube and Facebook Success for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-keyboard-functionality-for-windows-11-8-and-7-computers-expert-fixes/"><u>Revive Keyboard Functionality for Windows 11, 8 & 7 Computers: Expert Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/silence-no-more-troubleshooting-and-repairing-audio-failures-in-acer-devices/"><u>Silence No More: Troubleshooting and Repairing Audio Failures in Acer Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-your-pc-when-it-freezes/"><u>Step-by-Step Guide: Resolving Your PC When It Freezes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-strategies-to-fix-a-blocked-webpage-http-403-solutions/"><u>Step-by-Step Strategies to Fix a Blocked Webpage - HTTP 403 Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-enabling-bluetooth-functionality-on-your-pc-with-windows/"><u>Step-by-Step Tutorial: Enabling Bluetooth Functionality on Your PC with Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-the-interruptions-managing-and-correcting-unplanned-computer-sleep-mode/"><u>Stop the Interruptions: Managing and Correcting Unplanned Computer Sleep Mode</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-addressing-unknown-peripheral-device-error-missing-descriptors-handled-effectively/"><u>Successfully Addressing Unknown Peripheral Device Error: Missing Descriptors Handled Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-techniques-for-lowering-desktop-window-manager-resource-demand-on-windows-11-systems/"><u>Troubleshooting Techniques for Lowering Desktop Window Manager Resource Demand on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-solving-persistent-mouse-disconnection-issues/"><u>Troubleshooting: Solving Persistent Mouse Disconnection Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210531362-unstick-your-unresponsive-usb-mouse-laptop-troubleshooting-steps-for-immediate-relief/"><u>Unstick Your Unresponsive USB Mouse: Laptop Troubleshooting Steps for Immediate Relief!</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-nokia-130-music-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Nokia 130 Music Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-overcoming-connection-issues-with-microsoft-display-adapters/"><u>Windows 10: Overcoming Connection Issues with Microsoft Display Adapters</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->