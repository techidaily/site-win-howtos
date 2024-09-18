---
title: Quick Solutions for Tackling Unwanted Restart Cycles in Windows 10 Computers
date: 2024-09-15T17:49:16.473Z
updated: 2024-09-17T20:50:20.758Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Quick Solutions for Tackling Unwanted Restart Cycles in Windows 10 Computers
excerpt: This Article Describes Quick Solutions for Tackling Unwanted Restart Cycles in Windows 10 Computers
thumbnail: https://thmb.techidaily.com/5e9bfb6a7e4a347d52ac2274763d8cb00a024229f1f3b2af38f5058bc81f8e98.jpg
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
<li><a href="https://article-files.techidaily.com/new-discovering-soft-amplification-techniques-in-garageband/"><u>[New] Discovering Soft Amplification Techniques in Garageband</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-best-7-dslr-cameras-for-vlogging/"><u>[New] In 2024, Best 7 DSLR Cameras for Vlogging</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-top-tier-iphone-camera-apps-for-amateurs-and-experts-alike/"><u>[Updated] In 2024, Top-Tier iPhone Camera Apps for Amateurs & Experts Alike</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-essentials-of-creating-share-worthy-instagram-videos/"><u>2024 Approved Essentials of Creating Share-Worthy Instagram Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-x3daudio17dll-recovery-techniques/"><u>Efficient X3DAudio1_7.dll Recovery Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-system-error-5-has-occurred-error-on-windows-11-7-and-8-solved/"><u>Fix System Error 5 Has Occurred Error on Windows 11, 7 & 8 [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/identifying-and-solving-errors-in-your-windows-software-installers/"><u>Identifying and Solving Errors in Your Windows Software Installers</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-icloud-lock-on-your-apple-iphone-12-and-ipad-by-drfone-ios/"><u>In 2024, How to fix iCloud lock on your Apple iPhone 12 and iPad</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722894063034-solving-the-mystery-recover-from-msstdfmtdll-error-not-found/"><u>Solving the Mystery: Recover From msstdfmt.dll Error - Not Found!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-the-0x80072efd-error-on-your-pc-windows-10-guide/"><u>Troubleshooting and Repairing the 0X80072EFD Error on Your PC - Windows 10 Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-nonfunctional-microphone-problems-on-windows-11-computers/"><u>Troubleshooting Nonfunctional Microphone Problems on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-the-missing-binkw32dll-error-message/"><u>Troubleshooting Tips for The Missing binkw32.dll Error Message</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/standing-youtubes-earnings-structure/"><u>Understanding YouTube's Earnings Structure</u></a></li>
<li><a href="https://facebook.techidaily.com/young-users-in-the-spotlight-balancing-digital-consumption-with-real-life-experiences-as-suggested-by-facebook/"><u>Young Users in the Spotlight: Balancing Digital Consumption with Real-Life Experiences, as Suggested by Facebook</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132161/7443" target="_top" id="2132161">
  <img src="//a.impactradius-go.com/display-ad/7443-2132161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132161/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

