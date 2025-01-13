---
title: "Troubleshooting Laptop TrackPad Problems in Windows Operating Systems (10/8/7): Expert Tips"
date: 2025-01-08T17:00:59.434Z
updated: 2025-01-13T16:52:24.522Z
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-top-10-steps-youtube-to-mp3mpeg-conversion-process/"><u>[New] 2024 Approved Top 10 Steps YouTube to MP3/MPEG Conversion Process</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-prime-business-sky-storage-choice/"><u>[New] Prime Business Sky-Storage Choice</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-samsung-galaxy-m54-5g-frp-bypass-by-drfone-android/"><u>About Samsung Galaxy M54 5G FRP Bypass</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205620823-constraint-a-the-footnotes-must-be-numbered-sequentially-starting-with-1/"><u>Constraint A: The Footnotes Must Be Numbered Sequentially Starting with [^1].</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/eliminating-rockaldlldll-missing-error-comprehensive-troubleshooting-guide/"><u>Eliminating 'rockaldll.dll' Missing Error – Comprehensive Troubleshooting Guide</u></a></li>
<li><a href="https://media-tips.techidaily.com/enjoy-your-favorite-films-and-shows-anywhere-with-step-by-step-tips-on-securely-downloading-content-for-offline-use/"><u>Enjoy Your Favorite Films and Shows Anywhere with Step-by-Step Tips on Securely Downloading Content for Offline Use</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-working-usb-flash-drive-simple-and-effective-methods/"><u>Fixing a Non-Working USB Flash Drive: Simple and Effective Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-when-task-manager-wont-respond-expert-advice/"><u>Fixing the Issue When Task Manager Won't Respond - Expert Advice</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-delete-all-photos-from-iphone-11-beyond-scope-of-recovery-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Delete All Photos from iPhone 11 Beyond Scope of Recovery? | Stellar</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-drones-deciphered-understanding-their-functions-and-designs/"><u>In 2024, Drones Deciphered Understanding Their Functions & Designs</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-realme-v30t-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Realme V30T to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-connectivity-problems-making-your-wacom-pen-work-with-windows-1110/"><u>Overcoming Connectivity Problems: Making Your Wacom Pen Work with Windows 11/10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-file-explorer-freezes-and-crashes-on-windows-11-a-step-by-step-guide/"><u>Resolving File Explorer Freezes and Crashes on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-module-cannot-be-found-problem-effectively/"><u>Troubleshooting the 'Module Cannot Be Found' Problem Effectively</u></a></li>
<li><a href="https://win-answers.techidaily.com/untangle-your-gaming-experience-by-solving-anthems-infinite-load-issue/"><u>Untangle Your Gaming Experience by Solving Anthem's Infinite Load Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208755069-why-wont-my-spacebar-work-in-windows-10-find-out-how-to-resolve-it-today/"><u>Why Won't My Spacebar Work in Windows 10? Find Out How to Resolve It Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win11-strategies-for-lowering-provider-host-cpu-load/"><u>Win11: Strategies for Lowering Provider Host CPU Load</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

