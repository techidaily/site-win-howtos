---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2024-11-27T01:30:36.743Z
updated: 2024-11-28T02:57:01.557Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
excerpt: This Article Describes Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
thumbnail: https://thmb.techidaily.com/a7dd9142f70f2e1fb0515e1b92c73345b73af0eebd789d21de62a66b954929b6.jpg
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
<li><a href="https://fox-http.techidaily.com/updated-in-2024-the-art-of-piecing-together-digital-images/"><u>[Updated] In 2024, The Art of Piecing Together Digital Images</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-understanding-the-basics-of-audio-crossfading/"><u>[Updated] Understanding the Basics of Audio Crossfading</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-the-red-screen-of-death-in-windows-11-systems/"><u>Addressing the Red Screen of Death in Windows 11 Systems</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95950843--be-here/"><u>Be Here | Free Book</u></a></li>
<li><a href="https://some-approaches.techidaily.com/comprehensive-customer-assistance-portal-for-winx-dvd-rip-and-convert-applications/"><u>Comprehensive Customer Assistance Portal for WinX DVD Rip & Convert Applications</u></a></li>
<li><a href="https://fox-that.techidaily.com/connectivity-concerns-resolved-a-guide-for-when-iphones-dont-receive-texts-from-android-devices/"><u>Connectivity Concerns Resolved: A Guide for When iPhones Don't Receive Texts From Android Devices</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/how-to-convert-facebook-video-to-mp4-720p1080phd-online-and-free/"><u>How to Convert Facebook Video to MP4 720P/1080p/HD Online and Free?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-corrupted-files-in-windows-10-using-sfc-and-deployment-image-servicing-management-dism/"><u>How to Repair Corrupted Files in Windows 10 Using SFC and Deployment Image Servicing Management (DISM)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-m34-5g-bootloader-easily-by-drfone-android/"><u>How to Unlock Samsung Galaxy M34 5G Bootloader Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-file-explorer-lag-and-non-responsiveness-in-windows-10-expert-tips/"><u>Overcome File Explorer Lag and Non-Responsiveness in Windows 10: Expert Tips</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-obstacles-in-tarkov-mastering-the-fix-for-error-103-grok003/"><u>Overcoming Obstacles in Tarkov: Mastering the Fix for Error 103 Grok003</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-of-sporadic-boot-ups-for-a-stable-computer-experience/"><u>Resolving the Issue of Sporadic Boot-Ups for a Stable Computer Experience</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/secrets-of-screen-grabs-exposed/"><u>Secrets of Screen Grabs Exposed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-repair-a-non-responsive-wacom-digital-art-pad/"><u>Step-by-Step Guide to Repair a Non-Responsive Wacom Digital Art Pad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-methods-for-restoring-your-ps4-headset-audio-functionality/"><u>Top Methods for Restoring Your PS4 Headset Audio Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-resolving-user-profile-service-failure-during-windows-1011-login/"><u>Troubleshooting Steps: Resolving 'User Profile Service' Failure During Windows 10/11 Login</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-went-wrong-insights-into-windows-10s-problematic-version-1607-update/"><u>What Went Wrong? Insights Into Windows 10'S Problematic Version 1ˈ607 Update</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

