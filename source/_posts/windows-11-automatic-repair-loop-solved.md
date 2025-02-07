---
title: Windows 11 Automatic Repair Loop [Solved]
date: 2025-02-05T01:42:10.389Z
updated: 2025-02-06T20:22:45.400Z
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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-inside-out-a-thorough-examination-of-dji-phantom-4/"><u>[New] 2024 Approved Inside Out A Thorough Examination of DJI Phantom 4</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-twilight-tales-top-hdr-sky-captures-from-leading-portals/"><u>[New] 2024 Approved Twilight Tales - Top HDR Sky Captures From Leading Portals</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-dive-into-digital-green-magic-top-4-youtube-sources-for-no-cost-background-workshops-for-2024/"><u>[Updated] Dive Into Digital Green Magic Top 4 YouTube Sources for No-Cost Background Workshops for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-from-beginner-to-pro-the-top-tips-for-instagram-stories/"><u>[Updated] In 2024, From Beginner to Pro The Top Tips for Instagram Stories</u></a></li>
<li><a href="https://win-howtos.techidaily.com/answered-troubleshooting-directx-device-instantiation-mishap/"><u>Answered: Troubleshooting DirectX Device Instantiation Mishap</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-to-fix-your-stuck-touchpad-scroll-wheel/"><u>Comprehensive Solutions to Fix Your Stuck Touchpad Scroll Wheel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/geforce-experience-wont-open-issue-solved/"><u>GeForce Experience Won't Open Issue [Solved]</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-websites-and-software-to-add-frames-to-photos/"><u>In 2024, Best Websites and Software to Add Frames to Photos</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-bring-life-to-graphics-adobe-blur-masterclass/"><u>In 2024, Bring Life to Graphics Adobe Blur Masterclass</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-xs-max-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, How to Unlock iPhone XS Max without Passcode or Face ID</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-usb-dropout-effective-strategies-for-stable-connectivity-fixes/"><u>Overcoming USB Dropout: Effective Strategies for Stable Connectivity Fixes</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209933396-9781722524159-the-miracle-month/"><u>The Miracle Month | Free Book</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-functional-function-key-issues-on-your-asus-laptop/"><u>Troubleshooting Non-Functional Function Key Issues on Your ASUS Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-teredo-did-not-make-the-cut-a-comprehensive-breakdown/"><u>Why Teredo Did Not Make the Cut: A Comprehensive Breakdown</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

