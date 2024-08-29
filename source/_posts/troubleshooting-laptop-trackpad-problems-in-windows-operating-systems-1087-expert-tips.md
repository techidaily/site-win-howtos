---
title: "Troubleshooting Laptop TrackPad Problems in Windows Operating Systems (10/8/7): Expert Tips"
date: 2024-08-28T00:38:38.959Z
updated: 2024-08-29T00:38:38.959Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Laptop TrackPad Problems in Windows Operating Systems (10/8/7): Expert Tips"
excerpt: "This Article Describes Troubleshooting Laptop TrackPad Problems in Windows Operating Systems (10/8/7): Expert Tips"
thumbnail: https://thmb.techidaily.com/8edbdeedec707f11bb72a9ed7f55e988ffc8071bad7a0eaa9fbee4357c112fe7.jpg
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
<li><a href="https://win-howtos.techidaily.com/fixed-step-by-step-solutions-for-rectifying-the-infamous-red-screen-malfunction/"><u>[FIXED] Step-by-Step Solutions for Rectifying the Infamous Red Screen Malfunction</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-comprehensive-reference-for-efficient-screenshotting-with-zd-softwares-tools/"><u>[New] 2024 Approved  Comprehensive Reference for Efficient Screenshotting with ZD Software's Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-pivot-point-review-diversifying-video-tech/"><u>[New] 2024 Approved  Pivot Point Review  Diversifying Video Tech</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-building-a-sports-channel-via-macos-step-by-step-guide/"><u>[Updated] 2024 Approved  Building a Sports Channel via macOS  Step by Step Guide</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-mastering-discord-pics-download-and-edit-tutorial/"><u>[Updated] In 2024, Mastering Discord Pics  Download & Edit Tutorial</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-prime-facebook-extra-tools-secure-file-grabber-optimized-for-ff-for-2024/"><u>[Updated] Prime Facebook Extra Tools  Secure File Grabber, Optimized For FF for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-the-complete-blueprint-to-infuse-life-with-emojis-in-your-discord-statuses-for-2024/"><u>[Updated] The Complete Blueprint to Infuse Life with Emojis in Your Discord Statuses for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-transform-your-videos-presence-with-youtube-thumbnail-tailoring/"><u>2024 Approved  Transform Your Video's Presence with YouTube Thumbnail Tailoring</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/a-comprehensive-review-the-effortlessly-installed-d-link-powerline-2000-for-ultra-fast-networking/"><u>A Comprehensive Review: The Effortlessly Installed D-Link Powerline 2000 for Ultra-Fast Networking</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-paired-but-not-connected-on-windows-10/"><u>Bluetooth Paired but Not Connected on Windows 10</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/breaking-down-the-features-and-performance-of-asus-zenwifi-6e-xt8-ax6600-mesh-wi-fi-system-reviewed/"><u>Breaking Down the Features and Performance of Asus ZenWiFi 6E (XT8) AX6600 Mesh Wi-Fi System Reviewed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/buffer-free-viewing-permanent-solution-to-kodis-playback-problem/"><u>Buffer-Free Viewing: Permanent Solution to Kodi's Playback Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/copy-pasting-woes-heres-how-to-fix-it-on-your-windows-11-machine/"><u>Copy-Pasting Woes? Here's How to Fix It on Your Windows 11 Machine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/demystifying-the-ce-34878-0-error-for-ps4-users-troubleshooting-techniques-unveiled/"><u>Demystifying the CE-34878-0 Error for PS4 Users: Troubleshooting Techniques Unveiled</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722971636933-di-enables-higher-compression-ratios-for-better-thermal-efficiency-due-to-its-ability-to-cool-the-air-charge-and-reduce-knock-risk/"><u>DI Enables Higher Compression Ratios for Better Thermal Efficiency Due to Its Ability to Cool the Air Charge and Reduce Knock Risk</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-navigation-through-windows-11s-file-explorer-features/"><u>Effortless Navigation Through Windows 11'S File Explorer Features</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-solutions-stop-windows-10-from-continuously-restarting/"><u>Effortless Solutions: Stop Windows 10 From Continuously Restarting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-overcome-the-bad-module-information-flaw-leading-to-game-crashes-instantly/"><u>Expert Tips: Overcome the Bad Module Information Flaw Leading to Game Crashes Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-problem-with-microsoft-store-not-opening-correctly/"><u>Fixing the Problem with Microsoft Store Not Opening Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-connected-again-correct-driver-installation-for-overcoming-lenovos-wireless-issues/"><u>Get Connected Again: Correct Driver Installation for Overcoming Lenovo's Wireless Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hardware-hell-critical-breakdown-occurs/"><u>Hardware Hell: Critical Breakdown Occurs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-play-fortnite-on-unsupported-graphics-cards-under-windows-solution/"><u>How to Play Fortnite on Unsupported Graphics Cards Under Windows [Solution]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-constant-usb-device-not-detected-alerts-on-your-computer-solved/"><u>How to Resolve Constant 'USB Device Not Detected' Alerts on Your Computer (SOLVED)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-elevated-cpu-load-caused-by-windows-sound-system-glitches/"><u>How to Resolve Elevated CPU Load Caused by Windows Sound System Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-dell-webcam-functionality-on-your-windows-pc/"><u>How to Restore Dell Webcam Functionality on Your Windows PC</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-motorola-defy-2-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Motorola Defy 2 FRP Locks</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-nubia-z50-ultramirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Nubia Z50 UltraMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lowering-resource-overload-from-ntoskrnlexe-on-pcs/"><u>Lowering Resource Overload From ntoskrnl.exe on PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/masterful-solutions-for-handling-sudden-termination-in-windows-tackle-error-1067-efficiently/"><u>Masterful Solutions for Handling Sudden Termination in Windows - Tackle Error 1067 Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-fixes-for-error-code-0x800f0922-on-your-windows-10-system/"><u>Mastering Fixes for Error Code 0X800F0922 on Your Windows 10 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-solutions-to-get-your-amd-catalyst-control-center-running-smoothly-again/"><u>Simple Solutions to Get Your AMD Catalyst Control Center Running Smoothly Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-resolution-for-correcting-error-0x800705b4-in-windows-10s-installation-and-update-process/"><u>Step-by-Step Resolution for Correcting Error 0X800705b4 in Windows 10'S Installation and Update Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-troubleshooting-why-wont-my-laptop-mouse-respond-anymore/"><u>Step-by-Step Troubleshooting: Why Won't My Laptop Mouse Respond Anymore?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-list-8-superior-email-providers-as-alternatives-to-gmail/"><u>The Ultimate List: 8 Superior Email Providers as Alternatives to Gmail</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-smartphone-to-vr-makeover-tutorial-for-2024/"><u>The Ultimate Smartphone-to-VR Makeover Tutorial for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairs-fixing-a-non-responsive-corsair-mechanical-keyboard/"><u>Troubleshooting and Repairs: Fixing a Non-Responsive Corsair Mechanical Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-windows-10-update-issues/"><u>Troubleshooting Guide: Fixing Windows 10 Update Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-microsofts-print-to-pdf-feature-fails-on-windows-11/"><u>Troubleshooting Steps when Microsoft's Print to PDF Feature Fails on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-successful-activation-of-new-world-despite-easy-anti-cheat-glitches/"><u>Troubleshooting Tips: Successful Activation of New World Despite Easy Anti-Cheat Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-successfully-complete-windows-installations/"><u>Troubleshooting: How To Successfully Complete Windows Installations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-addressing-the-issue-of-microsoft-compatibility-telemetry-overusing-disk-space-on-windows-10-systems/"><u>Understanding and Addressing the Issue of Microsoft Compatibility Telemetry Overusing Disk Space on Windows 10 Systems</u></a></li>
<li><a href="https://article-helps.techidaily.com/virtual-reality-epics-the-most-captivating-sci-fi-cinematic-worlds/"><u>Virtual Reality Epics  The Most Captivating Sci-Fi Cinematic Worlds</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-audio-failure-no-more-win-1011-fixed/"><u>Windows Audio Failure No More - Win 10/11 Fixed</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->