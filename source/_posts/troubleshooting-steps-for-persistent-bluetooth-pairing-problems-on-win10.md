---
title: Troubleshooting Steps for Persistent Bluetooth Pairing Problems on Win10
date: 2024-08-28T00:27:47.382Z
updated: 2024-08-29T00:27:47.382Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps for Persistent Bluetooth Pairing Problems on Win10
excerpt: This Article Describes Troubleshooting Steps for Persistent Bluetooth Pairing Problems on Win10
thumbnail: https://thmb.techidaily.com/d0b73eb28e24a2f2ed6215d7e2c211efc75eaeb77baea06879d148a0fe930510.jpg
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
<li><a href="https://instagram-clips.techidaily.com/new-harnessing-instagram-video-power-strategizing-for-impact-for-2024/"><u>[New] Harnessing Instagram Video Power  Strategizing for Impact for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-deciphering-youtube-monetization-success-codes/"><u>[New] In 2024, Deciphering YouTube Monetization Success Codes</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-enhancing-speed-for-vimeo-playback/"><u>[New] In 2024, Enhancing Speed for Vimeo Playback</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-ultimate-path-to-stunning-instagram-posts-for-2024/"><u>[New] The Ultimate Path to Stunning Instagram Posts for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-humble-beginnings-jake-paul-on-youtube-triumph/"><u>[Updated] 2024 Approved  From Humble Beginnings  Jake Paul on YouTube Triumph</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-optimizing-control-switch-pro-for-steam-gaming/"><u>[Updated] In 2024, Optimizing Control  Switch Pro for Steam Gaming</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-maximize-mp4-audio-quality-with-srt-integration-your-comprehensive-guide/"><u>[Updated] Maximize MP4 Audio Quality with SRT Integration - Your Comprehensive Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-achieve-cinematic-quality-with-ipad-time-lapses/"><u>2024 Approved  Achieve Cinematic Quality with iPad Time-Lapses</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquer-constant-buffering-essential-fixes-for-stalled-valorant-launch/"><u>Conquer Constant Buffering: Essential Fixes for Stalled Valorant Launch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeating-the-device-doesnt-receive-miracast-advanced-techniques-and-updates/"><u>Defeating the 'Device Doesn't Receive Miracast': Advanced Techniques and Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-loudness-issues-in-playstation-4-systems-tips-and-fixes/"><u>Diagnosing Loudness Issues in PlayStation 4 Systems – Tips & Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-no-device-drivers-detected-error-when-installing-windows-7/"><u>Easy Fixes for 'No Device Drivers Detected' Error When Installing Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-ways-to-switch-off-the-touchpad-in-windows-10-while-your-external-mouse-is-connected/"><u>Effective Ways to Switch Off the Touchpad in Windows 10 While Your External Mouse Is Connected</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-fix-it-methods-using-system-file-checker-and-deployment-image-servicing-on-win11/"><u>Essential Fix-It Methods: Using System File Checker and Deployment Image Servicing on Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-dim-or-overly-bright-screen-correcting-brightness-issues-on-windows-10/"><u>Fix Your Dim or Overly-Bright Screen: Correcting Brightness Issues on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-unable-to-activate-hosted-wifi-on-windows-10/"><u>Fixing the Issue: Unable to Activate Hosted WiFi on Windows 10</u></a></li>
<li><a href="https://win-answers.techidaily.com/get-the-best-fps-in-valheim-with-our-ultimate-ping-reduction-guide-windows/"><u>Get the Best FPS in Valheim with Our Ultimate Ping Reduction Guide (Windows)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-detect-dual-monitors/"><u>How to Correctly Detect Dual Monitors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-persistent-red-screen-problem-on-your-windows-11-pc/"><u>How to Fix a Persistent Red Screen Problem on Your Windows 11 PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-samsung-galaxy-f54-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Samsung Galaxy F54 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-vivo-y78plus-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Vivo Y78+ Phone? | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-the-ultimate-guide-to-pc-game-screenshots/"><u>In 2024, The Ultimate Guide to PC Game Screenshots</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-transform-your-gopro-footage-mac-video-editing-essentials/"><u>In 2024, Transform Your GoPro Footage Mac Video Editing Essentials</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/installing-updated-drivers-for-your-amd-radeon-hd-7870-on-windows-10/"><u>Installing Updated Drivers for Your AMD Radeon HD 7870 on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-not-working-heres-how-you-can-fix-it-on-windows-11-7-or-8/"><u>Keyboard Not Working? Here's How You Can Fix It on Windows 11, 7, or 8</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-retrieving-and-repositioning-hidden-system-windows/"><u>Master the Art of Retrieving and Repositioning Hidden System Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-bluetooth-pairing-expert-advice-for-windows-7-users/"><u>Mastering Bluetooth Pairing: Expert Advice for Windows 7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-exe-file-failure-fixing-applications-that-have-crashed/"><u>Resolved: Exe File Failure - Fixing Applications That Have Crashed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211802354-resolving-audio-problems-get-back-control-of-windows-10-speaker-volume-now/"><u>Resolving Audio Problems: Get Back Control of Windows 10 Speaker Volume Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205783555-revive-your-touchpad-a-device-mastering-quest/"><u>Revive Your Touchpad: A Device Mastering Quest!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/seeking-a-perfect-match-cameras-and-windows-hello/"><u>Seeking a Perfect Match: Cameras & Windows Hello</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-unregistered-program-components-in-windows-11-a-step-by-step-tutorial/"><u>Solve Unregistered Program Components in Windows 11: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-common-issues-with-non-responsive-at-sign-functionality/"><u>Solving Common Issues with Non-Responsive 'At Sign' Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-client-launcher-trouble-discover-how-to-fix-and-get-back-in-action-today/"><u>Steam Client Launcher Trouble? Discover How to Fix and Get Back in Action Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-better-game-speeds-on-a-windows-11-system/"><u>Step-by-Step Guide to Better Game Speeds on a Windows 11 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205382179-stop-your-device-from-falling-asleep-simple-solutions/"><u>Stop Your Device From Falling Asleep: Simple Solutions</u></a></li>
<li><a href="https://driver-download.techidaily.com/the-speedy-way-to-download-your-wacoms-essential-drivers-today/"><u>The Speedy Way to Download Your Wacom's Essential Drivers Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-restore-windows-11-touchscreen-functionality-with-these-5-techniques/"><u>Troubleshooting Guide: Restore Windows 11 Touchscreen Functionality with These 5 Techniques</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-free-timers-for-daily-use/"><u>Ultimate Free Timers for Daily Use</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-how-to-use-emojis-on-windows-10-and-windows-11-in-2024/"><u>Updated How to Use Emojis on Windows 10 and Windows 11, In 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->