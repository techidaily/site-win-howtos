---
title: Windows 11 Automatic Repair Loop [Solved]
date: 2024-08-23T14:01:54.960Z
updated: 2024-08-24T14:01:54.960Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 11 Automatic Repair Loop [Solved]
excerpt: This Article Describes Windows 11 Automatic Repair Loop [Solved]
thumbnail: https://thmb.techidaily.com/af1734dc2b0a9d3bcad9faa3494b27c219c63253c502adbe4dde73c3482b6b83.jpg
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
<li><a href="https://youtube-web.techidaily.com/024-approved-discover-world-wonders-with-these-top-10-videos/"><u>[New] 2024 Approved  Discover World Wonders with These Top 10 Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-discovering-instagram-de-follows-quickly/"><u>[New] In 2024, Discovering Instagram De-Follows Quickly</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-optimized-processes-for-effective-live-streaming-on-computer/"><u>[New] Optimized Processes for Effective Live Streaming on Computer</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/nlocking-youtubes-full-potential-advanced-banner-strategies-for-2024/"><u>[New] Unlocking YouTube's Full Potential  Advanced Banner Strategies for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-the-ultimate-watch-list-top-10-music-clips-on-facebook/"><u>[Updated] 2024 Approved  The Ultimate Watch List  Top 10 Music Clips on Facebook</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-audio-clips-to-written-content-harnessing-ms-words-transcription-features/"><u>[Updated] From Audio Clips to Written Content  Harnessing MS Word's Transcription Features</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pinnacle-capture-gear-for-visual-media-2024/"><u>[Updated] Pinnacle Capture Gear for Visual Media, 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-strategic-planning-for-effective-virtual-meetings-on-win11/"><u>[Updated] Strategic Planning for Effective Virtual Meetings on Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-vivo-y56-5g-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Vivo Y56 5G by Name | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-the-crash-gameplay-of-oddworld-soulstorm-on-pc-issues-resolved/"><u>Beat the Crash Gameplay of Oddworld: Soulstorm on PC [Issues Resolved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/deciphering-msdia80dll-why-its-essential-and-how-to-handle-it/"><u>Deciphering msdia80.dll: Why It's Essential and How to Handle It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209123405-diagnosing-and-correcting-the-frequent-disconnection-problem-in-your-personal-computer-mouse/"><u>Diagnosing and Correcting the Frequent Disconnection Problem in Your Personal Computer Mouse.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/directx-1112-setup-woes-fixing-the-infamous-failed-d3d-device-issue/"><u>DirectX 11/12 Setup Woes? Fixing the Infamous Failed D3D Device Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-nonfunctional-lenovo-mousepads-on-windows-operating-systems/"><u>Effective Fixes for Nonfunctional Lenovo Mousepads on Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eliminate-sluggish-typing-experience-fix-keyboard-latency-in-windows-10/"><u>Eliminate Sluggish Typing Experience: Fix Keyboard Latency in Windows 10</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/enhance-presentations-with-proper-screenshotting-via-ezvid/"><u>Enhance Presentations with Proper Screenshotting via Ezvid</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-41-in-windows-kernel-resolution-found/"><u>Error 41 in Windows Kernel - Resolution Found</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-free-updating-the-definitive-solution-for-windows-error-code-80244019/"><u>Error-Free Updating: The Definitive Solution for Windows Error Code 80244019</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-the-cwindowssystemprofiledesktop-not-available-error/"><u>How to Overcome the C:\\Windows\\SystemProfile\\Desktop Not Available Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-fix-for-the-notorious-stop-error-0xc0000005-in-microsoft-windows-systems/"><u>Master the Fix for the Notorious 'STOP' Error 0xC0000005 in Microsoft Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-art-of-lowering-dwms-impact-on-gpu-in-windows-11-through-five-key-tips/"><u>Mastering the Art of Lowering DWM's Impact on GPU in Windows 11 Through Five Key Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-interruptions-ultimate-guide-to-stop-buffering-in-kodi/"><u>No More Interruptions: Ultimate Guide to Stop Buffering in Kodi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211756961-overcome-pdf-printing-issues-effective-remedies-in-minutes/"><u>Overcome PDF Printing Issues: Effective Remedies in Minutes</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-oppo-a1x-5g-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Oppo A1x 5G Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-codmw2-performance-problems-with-lagging-frames-and-hitches-on-windows/"><u>Resolved! CoD:MW2 Performance Problems with Lagging Frames & Hitches on Windows</u></a></li>
<li><a href="https://article-helps.techidaily.com/simplify-tech-transitions-smartphone-vr-integration-guide-for-2024/"><u>Simplify Tech Transitions  Smartphone-VR Integration Guide for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/smooth-sailing-post-nvidia-installer-troubles/"><u>Smooth Sailing Post-NVIDIA Installer Troubles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-take-if-your-windows-11-operating-system-keeps-crashing-or-freezing/"><u>Steps to Take if Your Windows 11 Operating System Keeps Crashing or Freezing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixes-to-stop-screen-tearing-while-playing-valorant/"><u>Troubleshooting and Fixes to Stop Screen Tearing While Playing VALORANT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-common-issues-with-the-windows-1903-feature-update/"><u>Troubleshooting Common Issues with the Windows 1903 Feature Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-overcoming-restricted-input-issues-with-monitors/"><u>Troubleshooting Guide: Overcoming Restricted Input Issues with Monitors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-high-resource-consumption-by-msmpengine-in-windows-11/"><u>Troubleshooting High Resource Consumption by MsMpEngine in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-fixing-windows-host-rundll32-stopped-functioning-errors-in-windows-os/"><u>Understanding and Fixing 'Windows Host (Rundll32) Stopped Functioning' Errors in Windows OS</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-tecno-pova-5-pro-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Tecno Pova 5 Pro Phone Network-Ready</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-is-my-ps4-so-loud-uncovering-reasons-and-implementing-solutions-for-quieter-gameplay/"><u>Why Is My PS4 So Loud? Uncovering Reasons and Implementing Solutions for Quieter Gameplay</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-mastered-achieving-restful-sleep/"><u>Windows 11 Mastered: Achieving Restful Sleep</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-windows-update-error-0x80240017-a-comprehensive-fix/"><u>Winning the Battle Against Windows Update Error 0X80240017: A Comprehensive Fix</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->