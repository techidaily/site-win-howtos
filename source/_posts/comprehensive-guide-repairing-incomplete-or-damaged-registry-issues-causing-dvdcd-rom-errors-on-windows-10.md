---
title: "Comprehensive Guide: Repairing Incomplete or Damaged Registry Issues Causing DVD/CD-ROM Errors on Windows 10"
date: 2024-08-23T14:08:48.242Z
updated: 2024-08-24T14:08:48.242Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Comprehensive Guide: Repairing Incomplete or Damaged Registry Issues Causing DVD/CD-ROM Errors on Windows 10"
excerpt: "This Article Describes Comprehensive Guide: Repairing Incomplete or Damaged Registry Issues Causing DVD/CD-ROM Errors on Windows 10"
thumbnail: https://thmb.techidaily.com/61c513946ca67c4ebe171c06eca13adeadd0c93b5bf89d5e42f26ac56570469b.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afe2f523108.jpg)

When you met boot error with Windows 10, you hoped that automatic repair will help fix the problem. But it got you more troubles. The worse thing is that repair process seems never end. Then what to do to end the loop? Read on to find the solutions.  

 Since the Windows keeps restarting, it is impossible for you access Advanced Options, that you can fix the problem there. In this case, you can boot from a USB or DVD.
  
 To use the solutions below, you’ll need to prepare a bootable USB or a DVD with an installation file on it. If you are not sure how to create a bootable USB, refer [How to Burn Windows 10 ISO to USB](https://tools.techidaily.com/drivereasy/download/) . Note you need to do this on another computer.
  
 **First start your PC from the USB or DVD and open Command Prompt**
  
 1.  
  
 For USB bootable way:  
  
 Plug the USB the computer that has the problem.After you power on the computer, press function key, usually F2 or F12, to enter boot menu. The key to enter boot menu depends on the computers that you are using. You can go to the PC manufacturer’s website to check for it.
  
 For DVD bootable way:  
  
 Insert the DVD to the computer that has the problem. Wait until you see the message “Press any key to boot from CD or DVD”. Press any key to continue. If you don’t see this message, you probably have to change the boot order in the BIOS (Basic Input/Output System) .  
  
 Learn[How to Boot from a USB Drive, DVD or CD](https://tools.techidaily.com/drivereasy/download/) .  
  
 2\. When you go to the setup screen, select the Language that you wish to use.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff3f6500f3.jpg)
  
 2\. Type **bcdedit /set GUID recoveryenabled No** and hit**Enter** . Replace GUID with the number that you noted in last step. (For example, if the number is 7ce0dd34-d277-11e4-8263-68f7286346fb, the full command will be “bcdedit /set 7ce0dd34-d277-11e4-8263-68f7286346fb recoveryenabled No”)  
  
 3\. Reboot your PC and Windows should start without no problem.

 **Solution 3: Remove Your RAM**
  
 The loop error can be fixed by simply removing the RAM. You can try this solution. Before removing, remember to turn off the PC.If you have more than one RAM, remove one at a time then start your PC without it. You might need to do this a few times until you test every RAM module.

 After entering Windows, run a disk check to check if there is any problem with the disk, and run a system file check to check if some system files are corrupted. If neither of them work, try to restore Windows registry.  
  
**Run a disk check**
  
 Follow steps below:  
  
 1\. Open[**Command Prompt**](https://tools.techidaily.com/drivereasy/download/) as an administrator.
  
 2\. Type**chkdsk /f /r** and hit**Enter** . You need to wait a while until the process completes.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affd826668f.png)
  
**Run a system file check**
  
 Follow steps below:  
  
 1\. Open**Command Prompt** as an administrator.  
  
 2\. Type or paste**sfc /scannow** and hit**Enter** . The process will also take some time to complete.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affee4bc504.png)
  
 Hope the solutions here will help you fix the Windows 10 Automatic Repair loop error.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-activity-recording.techidaily.com/new-elite-console-emulation-top-5-ps3-options-for-2024/"><u>[New] Elite Console Emulation  Top 5 PS3 Options for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-maximizing-call-recording-20plus-techniques-for-windowsmac-users/"><u>[New] Maximizing Call Recording  20+ Techniques for Windows/Mac Users</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-melody-management-and-legalities-on-social-media/"><u>[Updated] In 2024, Melody Management and Legalities on Social Media</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-picscanner-tricks-uncomplicated-approaches-to-image-anonymity/"><u>[Updated] In 2024, PicScanner Tricks  Uncomplicated Approaches to Image Anonymity</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-micro-videos-in-the-spotlight-who-wins-youtube-shorts-or-tiktok/"><u>[Updated] Micro-Videos in the Spotlight  Who Wins, YouTube Shorts or TikTok?</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-perfecting-fade-out-techniques-in-audacity/"><u>[Updated] Perfecting Fade-Out Techniques in Audacity</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-craft-your-logo-legacy-affordable-and-flexible-templates-for-customization/"><u>2024 Approved  Craft Your Logo Legacy  Affordable & Flexible Templates for Customization</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-top-picks-hilarity-driven-ringtones-for-laughter-lovers/"><u>2024 Approved  Top Picks  Hilarity-Driven Ringtones for Laughter Lovers</u></a></li>
<li><a href="https://data-recovery.techidaily.com/1720600397383-stellar-data-recovery-windows/"><u>失われたファイルを安全に取り戻せる - Stellar Data Recovery (ステラ・データリカバリ) Windows版無料ソフトウェア</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-the-blues-with-these-8-strategies-for-correcting-windows-10-update-error-code-0x800f0922/"><u>Beat the Blues with These 8 Strategies for Correcting Windows 10 Update Error Code 0X800F0922</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-windows-error-0xc0000098-heres-how-you-can-fix-it/"><u>Dealing with Windows Error 0Xc0000098? Here's How You Can Fix It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/determined-no-driver-affirms-opengl-use/"><u>Determined: No Driver Affirms OpenGL Use</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-the-common-d3de-error-not-available-problem/"><u>Diagnosing and Fixing the Common D3DE ERROR: Not Available Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-surface-tablets-that-wont-charge-while-plugged-in/"><u>Effective Fixes for Surface Tablets That Won't Charge While Plugged In</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-download-issues-during-steam-platform-updates/"><u>Effective Solutions for Download Issues During Steam Platform Updates</u></a></li>
<li><a href="https://win-dash.techidaily.com/efficiently-upgrade-your-workspace-with-hp-thunderbolt-dock-g2-drivers-and-download-now/"><u>Efficiently Upgrade Your Workspace with HP Thunderbolt Dock G2 Drivers and Download Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortlessly-solve-the-bluetooth-disappearance-problem-in-windows-11-expert-advice/"><u>Effortlessly Solve the Bluetooth Disappearance Problem in Windows 11 - Expert Advice</u></a></li>
<li><a href="https://solve-news.techidaily.com/enhance-website-traffic-with-cookiebots-powerful-analytics-tools/"><u>Enhance Website Traffic with Cookiebot's Powerful Analytics Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolution-correcting-a-faulty-directory-path-in-file-systems/"><u>Error Resolution: Correcting a Faulty Directory Path in File Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-restoring-copy-and-paste-capabilities-in-windows-11-systems/"><u>Expert Guide: Restoring Copy & Paste Capabilities in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-invisible-mouse-icon-on-windows-11-without-breaking-a-sweat/"><u>Fix Your Invisible Mouse Icon on Windows 11 Without Breaking a Sweat!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-connection-unsecured-warning-in-firefox-easy-solutions/"><u>Fixing 'Connection Unsecured' Warning in Firefox: Easy Solutions</u></a></li>
<li><a href="https://win-dash.techidaily.com/fixing-hp-laserjet-1020-printer-drivers-problems-on-windows-a-comprehensive-guide/"><u>Fixing HP LaserJet 1020 Printer Drivers Problems on Windows: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-10-kb4019919-installation-issue-resolve-error-code-0x80240034/"><u>Fixing the Windows 10 KB4019919 Installation Issue - Resolve Error Code 0X80240034</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-from-iphone-se-2020-by-drfone-ios/"><u>How to Bypass iCloud Lock from iPhone SE (2020)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-diagnose-and-fix-rpc-communication-failures-in-your-windows-system/"><u>How to Diagnose and Fix RPC Communication Failures in Your Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-elevated-cpu-use-by-svchost-process-in-windows-10/"><u>How to Fix Elevated CPU Use by Svchost Process in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-mic-functionality-on-your-steelseries-arctis-5-headset-easy-fix-tips-for-gamers/"><u>How to Restore Mic Functionality on Your SteelSeries Arctis 5 Headset - Easy Fix Tips for Gamers</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-any-nokia-c12-plus-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Nokia C12 Plus Phone Password Using Emergency Call</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-fixes-for-unresponsive-lenovo-f-key-issues/"><u>Immediate Fixes for Unresponsive Lenovo F-Key Issues</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-from-conference-call-to-online-showcase-google-meet-on-youtube/"><u>In 2024, From Conference Call to Online Showcase  Google Meet on YouTube</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-lava-blaze-2-pro-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Lava Blaze 2 Pro for Free? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-itel-p55-easily-by-drfone-android/"><u>In 2024, How To Unlock a Itel P55 Easily?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-jest-jacket-picture-fabricator/"><u>In 2024, Jest Jacket  Picture Fabricator</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Sony Xperia 1 V? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ipogo-will-be-the-new-ispoofer-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Poco M6 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/key-specification-for-game-engine-launch-ensure-you-have-a-d3d1n-supported-gpu-installed/"><u>Key Specification for Game Engine Launch: Ensure You Have a D3D1n-Supported GPU Installed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-fix-of-error-0x8024401c-on-windows-update-for-users-of-windows-10-and-11-systems/"><u>Master the Fix of Error 0X8024401c on Windows Update for Users of Windows 10 and 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/microsoft-store-opening-troubleshooting-successful-fixes-revealed/"><u>Microsoft Store Opening Troubleshooting: Successful Fixes Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-performance-fixing-high-resource-demand-from-wudfhostexe-on-windows-11/"><u>Optimizing Performance: Fixing High Resource Demand From WUDFHost.exe on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-device-driver-issues-in-world-of-warcraft-successful-update-and-compatibility-guide/"><u>Overcome Device Driver Issues in World of Warcraft - Successful Update and Compatibility Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-d3dxx939dll-missing-error-a-step-by-step-repair-manual-for-windows-users/"><u>Overcoming the d3dxx9_39.dll Missing Error: A Step-by-Step Repair Manual for Windows Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722979046707-quick-and-easy-windows-update-drivers-get-them-today/"><u>Quick & Easy Windows Update Drivers – Get Them Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-disconnected-network-cable-issues-on-your-windows-pc/"><u>Resolve Disconnected Network Cable Issues on Your Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207629009-resolving-audio-glitches-speaker-issues-on-windows-operating-systems-solved/"><u>Resolving Audio Glitches: Speaker Issues on Windows Operating Systems Solved!</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/s-best-mkv-editors-for-mac-trimming-made-easy-for-2024/"><u>S Best MKV Editors for Mac Trimming Made Easy for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-nokia-g42-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-overcoming-issues-with-uninstalling-windows-10-updates/"><u>Solution Guide: Overcoming Issues with Uninstalling Windows 10 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-limited-memory-issues-fixing-command-cannot-be-processed-due-to-inadequate-storage/"><u>Solve Limited Memory Issues: Fixing 'Command Cannot Be Processed Due to Inadequate Storage'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210599306-solving-error-code-224003-now-your-video-plays-smoothly/"><u>Solving 'Error Code 224003': Now Your Video Plays Smoothly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-ps4-mic-problems-top-fixes-for-a-quiet-console/"><u>Solving PS4 Mic Problems: Top Fixes For A Quiet Console</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-laptops-endless-boot-loop-problem/"><u>Solving Your Laptop's Endless Boot Loop Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-to-correct-the-darkness-defeating-windows-11-black-screen-glitches/"><u>Step-by-Step Solutions to Correct the Darkness: Defeating Windows 11 Black Screen Glitches</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-realme-narzo-60-5g-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Realme Narzo 60 5G Phone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-stickynon-functioning-keys-on-hp-laptops-a-step-by-step-guide/"><u>Troubleshoot Sticky/Non-Functioning Keys on HP Laptops: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-deal-with-excessive-energy-on-a-hub-connection/"><u>Troubleshooting Guide: How to Deal with Excessive Energy on a Hub Connection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-the-win32-exception-error-code-0xc0000098-in-windows/"><u>Troubleshooting Guide: Resolving the Win32 Exception Error (Code 0xC0000098) in Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/unleash-your-creativity-the-top-5-hd-video-editing-solutions/"><u>Unleash Your Creativity The Top 5 HD Video Editing Solutions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Huawei Nova Y91? | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/when-facebook-pulls-your-digital-plug-reasons/"><u>When Facebook Pulls Your Digital Plug: Reasons</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->