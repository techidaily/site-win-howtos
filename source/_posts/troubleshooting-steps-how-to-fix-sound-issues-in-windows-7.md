---
title: "Troubleshooting Steps: How to Fix Sound Issues in Windows 7"
date: 2024-08-19T07:36:41.960Z
updated: 2024-08-20T07:36:41.960Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Steps: How to Fix Sound Issues in Windows 7"
excerpt: "This Article Describes Troubleshooting Steps: How to Fix Sound Issues in Windows 7"
thumbnail: https://thmb.techidaily.com/3a0ddaab1602f9aac9589130fbb24dc40e59a2711040c0e283860347f1ffa1fb.jpg
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
  
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
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
<li><a href="https://win-howtos.techidaily.com/fixed-kodi-buffering-issue/"><u>[FIXED] Kodi Buffering Issue</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-mastering-youtubes-ecosystem-with-optimal-video-formats/"><u>[New] 2024 Approved  Mastering YouTube's Ecosystem with Optimal Video Formats</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-expert-review-best-15-cameras-in-4k-resolution-for-2024/"><u>[New] Expert Review  Best 15 Cameras in 4K Resolution for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-explore-mp4-recording-tools-today-for-2024/"><u>[New] Explore MP4 Recording Tools Today for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-free-video-embedding-techniques-for-online-articles/"><u>[New] In 2024, Free Video Embedding Techniques for Online Articles</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-correct-fb-chat-display-revealed-as-yourself-for-2024/"><u>[Updated] Correct FB Chat Display  Revealed as Yourself for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-elite-10-audio-amplifiers-desktops-to-smartphones/"><u>[Updated] Elite 10 Audio Amplifiers  Desktops to Smartphones</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-unlocking-crypto-potential-the-ultimate-list-of-nft-engines/"><u>[Updated] Unlocking Crypto Potential  The Ultimate List of NFT Engines</u></a></li>
<li><a href="https://win-howtos.techidaily.com/aoc-screen-issues-on-windows-10-heres-your-step-by-step-solution/"><u>AOC Screen Issues on Windows 10? Here's Your Step-by-Step Solution!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/batterypower-icon-missing-windows-10-solved/"><u>Battery/Power Icon Missing Windows 10 [Solved]</u></a></li>
<li><a href="https://win-answers.techidaily.com/beat-the-waiting-game-quick-fixes-for-long-loading-on-fallout-4/"><u>Beat the Waiting Game - Quick Fixes for Long Loading on Fallout 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-and-repairing-the-persistent-0x802n40017-issue-in-windows-updates/"><u>Bypassing and Repairing the Persistent 0X802n40017 Issue in Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-when-your-windows-10-mouse-ignores-the-right-click/"><u>Comprehensive Fixes for When Your Windows 10 Mouse Ignores the Right Click</u></a></li>
<li><a href="https://article-posts.techidaily.com/crafting-a-unified-brand-presence-on-youtube-for-2024/"><u>Crafting a Unified Brand Presence on YouTube for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/end-buffering-problems-for-good-with-these-kodi-tweaks/"><u>End Buffering Problems for Good with These Kodi Tweaks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-it-the-ultimate-solution-for-warframe-update-failed-issues/"><u>Fix It! The Ultimate Solution for 'Warframe Update Failed' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/from-incomplete-to-complete-wow-mastered-3d-visualization/"><u>From Incomplete to Complete: WoW Mastered 3D Visualization</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ftdi-bus-error-driver-mismatch-causes-memory-integrity-issue/"><u>FTDI Bus Error: Driver Mismatch Causes Memory Integrity Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-correct-scrollbar-glitch-in-windows-10-file-explorer-that-hits-top-when-moving-up/"><u>Guide to Correct Scrollbar Glitch in Windows 10 File Explorer That Hits Top When Moving Up</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/hardcore-headset-test-jabra-bluetooth-model-scores-high/"><u>Hardcore Headset Test: Jabra Bluetooth Model Scores High</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-messages-from-motorola-moto-g-5g-2023-by-fonelab-android-recover-messages/"><u>How to Rescue Lost Messages from Motorola Moto G 5G (2023)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-v30-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Vivo V30</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-the-art-of-instagram-live-broadcasting-made-simple-via-obs/"><u>In 2024, The Art of Instagram Live Broadcasting Made Simple via OBS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203188320-laptop-battery-woes-discover-easy-methods-to-restore-charging-power-today/"><u>Laptop Battery Woes? Discover Easy Methods to Restore Charging Power Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-solution-eradicating-livekernel-event-mishap-no-144/"><u>Mastering the Solution: Eradicating LiveKernel Event Mishap No. 144</u></a></li>
<li><a href="https://win-howtos.techidaily.com/nba-2k21-green-hiccup-patch-details-and-how-its-gone/"><u>NBA 2K21 Green Hiccup: Patch Details & How It's Gone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209290778-no-more-pdf-printing-woes-swift-solutions-that-work/"><u>No More PDF Printing Woes - Swift Solutions That Work</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/optimal-repair-strategies-for-gpus-only/"><u>Optimal Repair Strategies for GPUs Only</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-connection-hurdles-a-users-guide-to-fixing-microsoft-dp-adapter-issues-on-windows-11/"><u>Overcoming Connection Hurdles: A User's Guide to Fixing Microsoft DP Adapter Issues on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-network-hurdles-corrective-measures-for-error-0x800704cf-in-windows/"><u>Overcoming Network Hurdles: Corrective Measures for Error 0X800704CF in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-your-non-functioning-mac-webcam-simple-solutions/"><u>Quick Fixes for Your Non-Functioning Mac Webcam – Simple Solutions!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206122003-resolve-bluetooth-not-detected-on-windows-10-simple-fixes/"><u>Resolve 'Bluetooth Not Detected' On Windows 10 - Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-persistent-windows-error-a-comprehensive-fix-for-error-0x8000ffff/"><u>Resolving the Persistent Windows Error: A Comprehensive Fix for Error 0X8000ffff</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-silent-dell-speakers-a-comprehensive-guide/"><u>Reviving Silent Dell Speakers: A Comprehensive Guide</u></a></li>
<li><a href="https://buynow-info.techidaily.com/sabrent-compact-mouse-uniting-accurate-navigation-with-a-retractable-cord-for-ultimate-on-the-go-usability/"><u>Sabrent Compact Mouse: Uniting Accurate Navigation with a Retractable Cord for Ultimate On-the-Go Usability</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-the-instruction-at-0xreferenced-memory-at-0x-the-memory-could-not-be-written/"><u>SOLVED: The Instruction at 0Xreferenced Memory at 0X. The Memory Could Not Be Written</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-correct-xerox-error-code-0x800f020b-for-windows-users/"><u>Step-by-Step Guide to Correct Xerox Error Code 0X800F020B for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-troubleshooting-windows-0xc0000005-faults/"><u>Step-by-Step Solutions for Troubleshooting Windows 0xC0000005 Faults</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-troubleshooting-steps-when-microsoft-store-doesnt-launch/"><u>Successful Troubleshooting Steps When Microsoft Store Doesn't Launch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/surface-laptop-stuck-at-0-is-it-truly-plugged-in-and-why/"><u>Surface Laptop Stuck at 0%% - Is It Truly Plugged in and Why?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-excessive-gpu-drain-by-the-desktop-window-manager-in-windows-1011/"><u>Troubleshooting Guide for Excessive GPU Drain by the Desktop Window Manager in Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-not-responding-errors-for-file-explorer-in-windows-11/"><u>Ultimate Guide: Resolving 'Not Responding' Errors for File Explorer in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-repairing-windows-media-player-server-problem-on-your-pc-solved/"><u>Understanding and Repairing Windows Media Player Server Problem on Your PC [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unraveled-addressing-the-write-failure-in-referenced-memory-location-x/"><u>Unraveled: Addressing the Write Failure in Referenced Memory Location X</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-help-fixing-the-secured-c-drive-accessibility/"><u>Windows 11 Help: Fixing the Secured C:\\ Drive Accessibility</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wireless-internet-sharing-made-simple-with-usb-tethering-on-windows-11/"><u>Wireless Internet Sharing Made Simple with USB Tethering on Windows 11</u></a></li>
</ul></div>
