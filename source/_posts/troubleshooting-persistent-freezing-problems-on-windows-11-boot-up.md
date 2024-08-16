---
title: Troubleshooting Persistent Freezing Problems on Windows 11 Boot-Up
date: 2024-08-15T11:32:37.251Z
updated: 2024-08-16T11:32:37.251Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Persistent Freezing Problems on Windows 11 Boot-Up
excerpt: This Article Describes Troubleshooting Persistent Freezing Problems on Windows 11 Boot-Up
thumbnail: https://thmb.techidaily.com/f7eb32e30dabd1ecde240ae4f390a8ba724185aa17a13d5ef1b9d86c145dc8b7.jpg
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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-master-screen-integration-into-real-time-streaming/"><u>[New] 2024 Approved  Master Screen Integration Into Real-Time Streaming</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-what-is-the-best-frame-rate-for-slow-motion-video/"><u>[New] What Is The Best Frame Rate For Slow Motion Video?</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-smartphone-editing-10-top-tiktok-choices/"><u>[Updated] 2024 Approved  Smartphone Editing  10 Top TikTok Choices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevate-video-playback-with-youtubes-latest-feature-av1-for-2024/"><u>[Updated] Elevate Video Playback with YouTube's Latest Feature - AV1 for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-poco-m6-pro-4g-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Poco M6 Pro 4G</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-oppo-find-x7-ultra-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Oppo Find X7 Ultra Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-samsung-galaxy-a15-5g-frp-bypass-by-drfone-android/"><u>About Samsung Galaxy A15 5G FRP Bypass</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-tutorial-resolving-display-connections-and-no-video-errors/"><u>Comprehensive Tutorial: Resolving Display Connections and No Video Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fading-vision-visual-void/"><u>Fading Vision: Visual Void</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-easily-fix-the-troublesome-update-issue-windows-10s-0xc1900208-error-code-decoded/"><u>How to Easily Fix the Troublesome Update Issue - Windows 10'S 0Xc1900208 Error Code Decoded</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-solve-a-laptops-white-screen-dilemma-for-smooth-operations/"><u>How to Solve a Laptop's White Screen Dilemma for Smooth Operations</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-from-the-iphone-xr-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock From the iPhone XR Without Previous Owner?</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-film-guide-top-15-timeless-stop-motion-classics/"><u>In 2024, The Ultimate Film Guide - Top 15 Timeless Stop Motion Classics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-strategies-to-fix-the-unknowncertificate-problem-in-windows-11-error-id-0x80072efd/"><u>In-Depth Strategies to Fix the 'UNKNOWN_CERTIFICATE' Problem in Windows 11 (Error ID 0X80072EFD)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-navigation-downfall-restore-function-to-up-down-left-and-right-arrows-now/"><u>Keyboard Navigation Downfall: Restore Function to Up, Down, Left & Right Arrows Now!</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-fixes-for-halo-4-ue4-catastrophic-system-failures-your-comprehensive-guide/"><u>Master the Fixes for Halo 4 UE4 Catastrophic System Failures - Your Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastery-over-malfunction-correcting-sudden-shutdowns-caused-by-error-1067-in-windows-os/"><u>Mastery Over Malfunction: Correcting Sudden Shutdowns Caused by Error 1067 in Windows OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/maximizing-gameplay-boosting-your-pcs-power-in-windows-11/"><u>Maximizing Gameplay: Boosting Your PC's Power in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-go-for-code-run/"><u>No Go for Code Run</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-windows-update-issue-overcoming-error-8007000e-easily/"><u>Quick Fixes for Windows Update Issue: Overcoming Error 8007000E Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/recovering-an-off-screen-window-a-step-by-step-guide/"><u>Recovering an Off-Screen Window: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reverse-redaction-operation/"><u>Reverse Redaction Operation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-controlling-wudfhostexe-high-resource-use-on-windows-11-computers/"><u>Step-by-Step Solution for Controlling wudfhost.exe High Resource Use on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-changed-monitor-display-size-a-troubleshooting-guide/"><u>Successfully Changed Monitor Display Size - A Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-your-game-heres-how-to-fix-setup-problems-on-origin/"><u>Trouble With Your Game? Here's How to Fix Setup Problems on Origin</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-unwanted-windows-10-file-explorers-scroll-jumping-behavior/"><u>Troubleshooting Guide for Unwanted Windows 10 File Explorer's Scroll Jumping Behavior</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-0x8024a105-issue-with-windows-updates/"><u>Ultimate Guide: Resolving the 0X8024A105 Issue with Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-solutions-to-stop-your-pc-from-continuously-crashing/"><u>Ultimate Guide: Solutions to Stop Your PC From Continuously Crashing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-issues-with-applying-windows-11-update-version-1607/"><u>Understanding Issues with Applying Windows 11 Update Version 1607</u></a></li>
<li><a href="https://win-howtos.techidaily.com/usb-mouse-not-working-on-laptop-try-these-fixes/"><u>USB Mouse Not Working on Laptop? Try These Fixes</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->