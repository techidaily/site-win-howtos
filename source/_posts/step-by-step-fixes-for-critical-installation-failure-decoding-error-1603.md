---
title: Step-by-Step Fixes for Critical Installation Failure - Decoding Error 1603
date: 2024-08-15T11:32:22.303Z
updated: 2024-08-16T11:32:22.303Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Fixes for Critical Installation Failure - Decoding Error 1603
excerpt: This Article Describes Step-by-Step Fixes for Critical Installation Failure - Decoding Error 1603
thumbnail: https://thmb.techidaily.com/a4cc32918e39c53ac0181d3e14c0cb7c5573f6c68460130a6a8de8214128380d.jpg
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-seek-out-stimulating-youtube-snippets/"><u>[New] 2024 Approved  Seek Out Stimulating YouTube Snippets</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-from-bystander-to-leader-in-the-world-of-insta-essential-tips-and-examples/"><u>[New] From Bystander to Leader in the World of Insta  Essential Tips & Examples</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-momentum-at-rest-best-idle-pc-games/"><u>[New] In 2024, Momentum at Rest  Best Idle PC Games</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-lore-legends-top-10-roguelike-experiences-for-2024/"><u>[New] Lore Legends  Top 10 Roguelike Experiences for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-mastering-close-up-mode-in-roblox-playground/"><u>[New] Mastering Close-Up Mode in Roblox Playground</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-chromecast-not-connecting-easily/"><u>[Solved] Chromecast Not Connecting. Easily</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fostering-friendship-through-conversations-with-viewers/"><u>[Updated] Fostering Friendship Through Conversations With Viewers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-how-to-stand-out-your-top-10-guide-to-youtubes-best-music-videos-for-2024/"><u>[Updated] How to Stand Out  Your Top 10 Guide to YouTube's Best Music Videos for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-innovative-frameworks-for-efficient-iptv-recording-for-2024/"><u>[Updated] Innovative Frameworks for Efficient IPTV Recording for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-the-social-network-crossroad-instagram-and-tiktok/"><u>[Updated] Navigating the Social Network Crossroad  Instagram & TikTok</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-skype-audio-archive-mp3-techniques-free-edition/"><u>[Updated] Skype Audio Archive  MP3 Techniques, Free Edition</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-speedy-instagram-video-views-desktop-methods-for-2024/"><u>[Updated] Speedy Instagram Video Views  Desktop Methods for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-spotlight-series-celebrating-top-10-game-bloggers-for-2024/"><u>[Updated] Spotlight Series  Celebrating Top 10 Game Bloggers for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-best-80s-movie-magic-for-contemporary-edits/"><u>2024 Approved  Best 80S Movie Magic for Contemporary Edits</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-exclusive-list-best-free-videos-for-pc-macos/"><u>2024 Approved  Exclusive List  Best Free Videos for PC, MacOS</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-innovators-designing-online-marvel-experiences/"><u>2024 Approved  Innovators Designing Online Marvel Experiences</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-mastering-snapchat-sharing-with-twitter-videos/"><u>2024 Approved  Mastering Snapchat Sharing with Twitter Videos</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensive-guide-to-elgatos-stream-deck-range/"><u>A Comprehensive Guide to Elgato's Stream Deck Range</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-motorola-g24-power-frp-bypass-by-drfone-android/"><u>About Motorola G24 Power FRP Bypass</u></a></li>
<li><a href="https://win-howtos.techidaily.com/battleye-setup-overcoming-previous-failures-with-these-proven-fixes/"><u>BattlEye Setup: Overcoming Previous Failures with These Proven Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-problems-effective-strategies-for-establishing-directx-device-creation-solved/"><u>Bypassing Problems: Effective Strategies for Establishing DirectX Device Creation [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-ps4-network-issues-ultimate-step-by-step-resolution/"><u>Bypassing PS4 Network Issues: Ultimate Step-by-Step Resolution</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-vivo-t2-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dell-keyboard-woes-solve-power-connectivity-and-response-problems-effectively/"><u>Dell Keyboard Woes? Solve Power, Connectivity, and Response Problems Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-strategies-to-address-and-repair-fatal-errors-in-cxfreeze/"><u>Effortless Strategies to Address and Repair Fatal Errors in Cx_Freeze</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-repairing-the-interruption-in-hamachi-network-services/"><u>Expert Guide: Repairing the Interruption in Hamachi Network Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-restoring-microphone-functionality-on-windows-10-systems/"><u>Expert Tips: Restoring Microphone Functionality on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-unresponsive-right-click-function-in-your-windows-10-mouse/"><u>Fixing the Unresponsive Right-Click Function in Your Windows 10 Mouse</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-nokia-c12-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Nokia C12 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-pixel-fold-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Google Pixel Fold FRP In 3 Different Ways</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-bypass-user-account-control-prompts-for-system-changes-on-win11-10-and-till-v7/"><u>How to Bypass User Account Control Prompts for System Changes on Win11, 10 and Till V7</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-vivo-x-fold-2-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Vivo X Fold 2 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correct-error-code-24-device-unavailable-in-your-window-os/"><u>How to Correct Error Code 24: Device Unavailable in Your Window OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-ensure-a-smooth-shut-down-process-in-windows-10-issues-fixed/"><u>How to Ensure a Smooth Shut Down Process in Windows 10 [ISSUES FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-connected-yet-disconnected-bluetooth-issues-on-your-windows-10-pc/"><u>How to Fix 'Connected' Yet Disconnected Bluetooth Issues on Your Windows 10 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-speaker-distortion-on-windows-10-and-7-systems-step-by-step-guide/"><u>How to Fix Speaker Distortion on Windows 10 & 7 Systems: Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-missing-or-unsupported-operating-system-error-a-step-by-step-guide/"><u>How to Fix the 'Missing or Unsupported Operating System' Error – A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-reactivate-the-night-light-functionality-on-your-pc-running-windows-10-or-11/"><u>How to Reactivate the Night Light Functionality on Your PC Running Windows 10 or 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-hot-40i-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Infinix Hot 40i Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://win-howtos.techidaily.com/important-note-ensure-your-system-has-a-directx-11-gpu-before-installation/"><u>Important Note: Ensure Your System Has a DirectX 11 GPU Before Installation</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-budget-buyers-guide-to-drone-tech-under-100/"><u>In 2024, Budget Buyers' Guide to Drone Tech Under $100</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-grandest-clash-of-titans-a-compilation-of-the-top-7-total-war-skirmishes/"><u>In 2024, Grandest Clash of Titans  A Compilation of the Top 7 Total War Skirmishes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-superior-hd-video-capture-options-reviewed-here/"><u>In 2024, Superior HD Video Capture Options Reviewed Here</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unlock-high-quality-viewing-with-youtubes-latest-av1-feature/"><u>In 2024, Unlock High-Quality Viewing with YouTube’s Latest AV1 Feature</u></a></li>
<li><a href="https://facebook.techidaily.com/like-count-anonymity-the-new-standard-for-fbig-users/"><u>Like Count Anonymity: The New Standard for FB/IG Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-bluetooth-compatibility-avoidance-of-windows-10-pairing-failures/"><u>Mastering Bluetooth Compatibility: Avoidance of Windows 10 Pairing Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mended-windows-explorer-app-failure/"><u>Mended: Windows Explorer App Failure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-touchpad-scroll-problems-on-your-device-expert-tips-and-tricks/"><u>Overcoming Touchpad Scroll Problems on Your Device – Expert Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/printer-not-activated-error-code-30-solved/"><u>Printer Not Activated, Error Code -30 [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-resolving-the-error-code-0x80070652-in-windows-updates/"><u>Quick Solutions for Resolving the Error Code 0X80070652 in Windows Updates</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/recordwise-gettingmaximumoutofyourcam-for-2024/"><u>RecordWise  GettingMaximumOutOfYourCam for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-the-windows-connectivity-issue-fixing-error-code-0x800704cf/"><u>Resolve the Windows Connectivity Issue: Fixing Error Code 0X800704CF</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-frozen-windows-update-steps-to-fix-when-its-stuck-at-0/"><u>Resolving Frozen Windows Update: Steps to Fix When It's Stuck at 0%%</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-microsoft-compatibility-telemetrys-excessive-disk-use-in-windows-11/"><u>Resolving Microsoft Compatibility Telemetry's Excessive Disk Use in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-ce-34878-0-issue-on-your-playstation-4-a-step-by-step-guide/"><u>Solving the CE-34878-0 Issue on Your PlayStation 4: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-a-broken-spacebar-under-windows-11/"><u>Solving the Issue of a Broken Spacebar Under Windows 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-capturing-and-sharing-your-nintendo-switch-gameplay/"><u>Step-by-Step Guide: Capturing & Sharing Your Nintendo Switch Gameplay</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-solve-the-rpc-server-not-responding-error-in-windows/"><u>Step-by-Step Guide: Solve the RPC Server Not Responding Error in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/streamlining-your-setup-ensuring-microsoft-wireless-display-adapter-works-perfectly-with-windows-11/"><u>Streamlining Your Setup: Ensuring Microsoft Wireless Display Adapter Works Perfectly with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-definitive-strategy-to-stop-usb-disconnect-annoyances-once-and-for-all/"><u>The Definitive Strategy to Stop USB Disconnect Annoyances Once and For All</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-directors-toolkit-youtube-lessons-on-film-making-for-2024/"><u>The Director's Toolkit  YouTube Lessons on Film Making for 2024</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-tecno-phantom-v-flip-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Tecno Phantom V Flip Reset Code | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-solutions-to-fix-a-stuck-windows-10-taskbar/"><u>Top Solutions to Fix a Stuck Windows 10 Taskbar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-destiny-2-server-connection-failures-for-gamers/"><u>Troubleshooting Destiny 2 Server Connection Failures for Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-energy-spike-issues-in-network-switches/"><u>Troubleshooting Guide: Resolving Energy Spike Issues in Network Switches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missing-desktop-icons-on-windows-11-complete-solution/"><u>Troubleshooting Missing Desktop Icons on Windows 11 - Complete Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-windows-task-scheduler/"><u>Troubleshooting Non-Functional Windows Task Scheduler</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/ultimate-troubleshooting-tips-for-bsod-errors-on-windows-11-systems/"><u>Ultimate Troubleshooting Tips for BSOD Errors on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-fixing-the-incorrect-parameter-mistake-for-windows-library-loading-error-87/"><u>Understanding and Fixing the 'Incorrect Parameter' Mistake for Windows Library Loading (Error 87)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/visionary-vr-game-engines-transforming-2023s-gaming-landscape/"><u>Visionary VR Game Engines Transforming 2023'S Gaming Landscape</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-isnt-my-usb-mouse-working-discover-simple-fixes-to-restore-functionality/"><u>Why Isn't My USB Mouse Working? Discover Simple Fixes to Restore Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/yac599-yamahaaturbosound-ii-sound-module-based-on-the-ymf7a1eymu3x-dsp-plus-midi-synthesader-plus-codec-and-256-mb-of-spiram-for-sample-storage-instead-of-r147/"><u>YAC599 - Yamaha'aturboSound II Sound Module Based on the YMF7A1E/YMU^3X (DSP + MIDI Synthesader + Codec) and 256 MB of SPIRAM for Sample Storage Instead of ROM. It Also Includes a Second Audio Input Connector</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->