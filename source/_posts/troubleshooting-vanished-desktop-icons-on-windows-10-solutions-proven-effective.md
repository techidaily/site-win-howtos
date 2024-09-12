---
title: "Troubleshooting Vanished Desktop Icons on Windows 10: Solutions Proven Effective"
date: 2024-09-11T15:24:00.779Z
updated: 2024-09-12T15:24:00.779Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Vanished Desktop Icons on Windows 10: Solutions Proven Effective"
excerpt: "This Article Describes Troubleshooting Vanished Desktop Icons on Windows 10: Solutions Proven Effective"
thumbnail: https://thmb.techidaily.com/9ca2eff6ae26123de716ede19623049b700dbda01116c41da9ae37331ba659b6.jpg
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
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-step-by-step-installed-vrecorder-software/"><u>[Updated] 2024 Approved Step-by-Step Installed VRecorder Software</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-sound-architects-guide-to-memo-mastery/"><u>[Updated] The Sound Architect's Guide to Memo Mastery</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-navigating-links-between-instagram-and-tiktok/"><u>2024 Approved Navigating Links Between Instagram and TikTok</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-visionary-dialogue-writer/"><u>2024 Approved Visionary Dialogue Writer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-fixes-to-eliminate-delayed-boot-times-in-windows-7/"><u>Essential Fixes to Eliminate Delayed Boot Times in Windows 7</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-music-files-from-infinix-zero-30-5g-by-fonelab-android-recover-music/"><u>How To Restore Missing Music Files from Infinix Zero 30 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hp-spectre-x360-troubleshooting-and-fixing-your-overheat-issues/"><u>HP Spectre X360: Troubleshooting & Fixing Your Overheat Issues</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-windows-stuck-at-error-e8024002e/"><u>Quick Fixes for Windows Stuck at Error E:8024002E</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-the-common-dll-stop-error-in-windows-a-complete-solution-guide/"><u>Resolve the 'Common DLL Stop' Error in Windows: A Complete Solution Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-game-freezes-in-psychonauts-2-how-to-prevent-your-pc-from-crashing/"><u>Resolving Game Freezes in Psychonauts 2 - How to Prevent Your PC From Crashing</u></a></li>
<li><a href="https://solve-hot.techidaily.com/seamless-document-capture-with-abbyy-flexiconnect-compatible-with-pegasystems-platform/"><u>Seamless Document Capture with ABBYY FlexiConnect: Compatible with Pegasystems Platform</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-this-site-cant-be-reached-chrome-error/"><u>Solved: “This Site Can’t Be Reached” Chrome Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-the-d3d9-graphics-device-failure-problem/"><u>Step-by-Step Solution for the D3D9 Graphics Device Failure Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solving-hang-ups-in-windows-11-systems-a-comprehensive-guide/"><u>Troubleshooting and Solving Hang-Ups in Windows 11 Systems: A Comprehensive Guide</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

