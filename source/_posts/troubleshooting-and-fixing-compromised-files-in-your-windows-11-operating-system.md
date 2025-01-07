---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2024-12-31T17:43:49.903Z
updated: 2025-01-06T22:58:37.061Z
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
<li><a href="https://facebook-clips.techidaily.com/new-seeking-clearance-can-you-upload-media-on-fb-for-2024/"><u>[New] Seeking Clearance Can You Upload Media on FB for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-concoct-laughter-in-image-format-giphy-style/"><u>[Updated] Concoct Laughter in Image Format, Giphy Style</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-safeguarding-photos-best-software-guide-uncovered/"><u>[Updated] Safeguarding Photos Best Software Guide Uncovered</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-unlock-your-potential-mastering-the-art-of-youtube-edits-for-2024/"><u>[Updated] Unlock Your Potential Mastering the Art of YouTube Edits for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-deciphering-your-social-media-shadows-privacy-on-facebook/"><u>2024 Approved Deciphering Your Social Media Shadows Privacy on Facebook</u></a></li>
<li><a href="https://data-wizards.techidaily.com/data-dormancy-defeated-by-stellar-recovery-pros/"><u>Data Dormancy Defeated by Stellar Recovery Pros</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-correcting-critical-errors-within-directx-systems/"><u>Diagnosing and Correcting Critical Errors Within DirectX Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-dota-2-error-code-2024-change-rendering-api-quick-guide/"><u>Fix Dota 2 Error Code 2024: Change Rendering API Quick Guide</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-rotate-mov-files-for-free-top-5-options-for-2024/"><u>New Rotate MOV Files for Free Top 5 Options for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-high-cpu-usage-in-win10-systems/"><u>Overcoming High CPU Usage in Win10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revolutionize-screen-timing-overcoming-current-input-latency-limitations/"><u>Revolutionize Screen Timing: Overcoming Current Input Latency Limitations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/streamlined-process-to-reinstall-windows-11-from-scratch/"><u>Streamlined Process to Reinstall Windows 11 From Scratch</u></a></li>
<li><a href="https://program-issues.techidaily.com/unlocking-solutions-for-launch-failures-in-games-verify-and-resolve-issues-now/"><u>Unlocking Solutions for Launch Failures in Games – Verify and Resolve Issues Now</u></a></li>
<li><a href="https://win-deluxe.techidaily.com/unraveling-the-reasons-for-constructing-chinas-iconic-great-wall-a-perspective-by-yl-technologies/"><u>Unraveling the Reasons for Constructing China's Iconic Great Wall: A Perspective by YL Technologies</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

