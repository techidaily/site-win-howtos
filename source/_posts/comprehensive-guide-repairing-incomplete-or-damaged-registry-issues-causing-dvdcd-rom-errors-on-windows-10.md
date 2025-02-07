---
title: "Comprehensive Guide: Repairing Incomplete or Damaged Registry Issues Causing DVD/CD-ROM Errors on Windows 10"
date: 2025-02-01T19:59:00.412Z
updated: 2025-02-06T22:47:16.048Z
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
<li><a href="https://youtube-web.techidaily.com/n-2024-craft-engaging-streams-for-success-the-ultimate-youtube-broadcast-blueprint-using-wirecast/"><u>[New] In 2024, Craft Engaging Streams for Success The Ultimate Youtube Broadcast Blueprint Using WireCast</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-ultimate-collection-of-top-asmr-microphones/"><u>[New] The Ultimate Collection of Top ASMR Microphones</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-new-buzzwords-for-vlogger-dialogues/"><u>[Updated] In 2024, New Buzzwords for Vlogger Dialogues</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-fresh-approaches-to-instagram-collages-made-simple/"><u>2024 Approved Fresh Approaches to Instagram Collages Made Simple</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/bringing-your-instagram-aesthetic-to-life-with-square-videos-in-imovie-for-2024/"><u>Bringing Your Instagram Aesthetic to Life with Square Videos in iMovie for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/cutting-edge-openings-at-no-cost-the-best-youtube-intro-makers-for-2024/"><u>Cutting-Edge Openings at No Cost The Best YouTube Intro Makers for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203930565-fix-implemented-now-your-graphics-card-supports-easy-miracast-streaming/"><u>Fix Implemented: Now Your Graphics Card Supports Easy Miracast Streaming!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-tearing-issues-ultimate-solution-guide-for-valorant-gameplay/"><u>Fixing Tearing Issues: Ultimate Solution Guide for Valorant Gameplay</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/mastering-mobile-and-professional-cameras-producing-igtv-excellence-for-2024/"><u>Mastering Mobile and Professional Cameras Producing IGTV Excellence for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-10-touchpad-scroll-malfunctions-step-by-step-guide/"><u>Resolving Windows 10 Touchpad Scroll Malfunctions - Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-solutions-resolve-your-netflix-audio-problems-quickly/"><u>Simple Solutions: Resolve Your Netflix Audio Problems Quickly</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/the-essential-funimate-guidebook-for-2024/"><u>The Essential Funimate Guidebook for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-corrupted-images-in-windows-11-and-windows-10-operating-systems/"><u>Troubleshooting Corrupted Images in Windows 11 and Windows 10 Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-non-responsive-file-explorer-issues-in-windows-11/"><u>Troubleshooting Guide: Resolving Non-Responsive File Explorer Issues in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-unfreezing-your-pc-or-laptop-easily/"><u>Ultimate Guide: Unfreezing Your PC or Laptop Easily</u></a></li>
<li><a href="https://facebook.techidaily.com/unraveling-the-legality-of-upload-photographs/"><u>Unraveling the Legality of Upload Photographs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-cujosso-11-steps-to-repair-bluetooth-connection-and-detect-peripherals/"><u>Windows Cujosso 11: Steps to Repair Bluetooth Connection and Detect Peripherals</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

