---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2024-12-08T20:39:45.954Z
updated: 2024-12-13T18:37:52.135Z
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
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-clubbing-essentials-top-rated-dj-template-vids/"><u>[Updated] In 2024, Clubbing Essentials Top-Rated DJ Template Vids</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-reimagining-administrative-protocols-on-windows/"><u>Breaking Barriers: Reimagining Administrative Protocols on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bring-back-the-bass-easy-ways-to-correct-netflix-audio-issues-fast/"><u>Bring Back the Bass: Easy Ways to Correct Netflix Audio Issues Fast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-troubleshooting-steps-resolving-non-responsive-xbox-one-controller-issues/"><u>Complete Troubleshooting Steps: Resolving Non-Responsive Xbox One Controller Issues</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/1722629709644-get-ready-for-action-dive-into-a-vibrant-new-season-of-fortnite-review-and-strategy/"><u>Get Ready for Action! Dive Into a Vibrant New Season of Fortnite Review and Strategy</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-repair-your-pcs-rec-room-microphone-step-by-step-fix/"><u>How To Repair Your PC's Rec Room Microphone - Step-by-Step Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restart-and-fix-a-stalled-hamachi-vpn-service-easily/"><u>How to Restart and Fix a Stalled Hamachi VPN Service Easily</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-4-effective-methods-fake-gps-location-on-apple-iphone-11-pro-maxipad-drfone-by-drfone-virtual-ios/"><u>In 2024, 4 Effective Methods Fake GPS Location on Apple iPhone 11 Pro Max/iPad | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-a-step-by-step-guide-to-finding-your-apple-id-from-your-apple-iphone-12-by-drfone-ios/"><u>In 2024, A Step-by-Step Guide to Finding Your Apple ID From Your Apple iPhone 12</u></a></li>
<li><a href="https://driver-install.techidaily.com/instantly-improve-windows-visuals-graphical-method-3/"><u>Instantly Improve Windows Visuals - Graphical Method 3</u></a></li>
<li><a href="https://extra-information.techidaily.com/mememorph-machine/"><u>MemeMorph Machine</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-sony-vegas-not-your-cup-of-tea-try-these-windows-alternatives/"><u>New Sony Vegas Not Your Cup of Tea? Try These Windows Alternatives</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-automatic-restarts-in-windows-11-top-strategies-and-solutions-explained/"><u>Resolve Automatic Restarts in Windows 11: Top Strategies and Solutions Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-what-to-do-when-numbers-on-keyboard-wont-work/"><u>Solution Found! What to Do When Numbers on Keyboard Won't Work</u></a></li>
<li><a href="https://win-able.techidaily.com/star-wars-taming-the-turbulence-of-fighter-collisions-solved-techniques-revealed/"><u>Star Wars: Taming the Turbulence of Fighter Collisions - Solved Techniques Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-ending-total-war-rome-remastereds-persistent-crash-problem/"><u>Step-by-Step Fix for Ending Total War: Rome Remastered's Persistent Crash Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-the-windows-10-update-fails-with-error-0xc1900208-problem/"><u>Step-by-Step Solution for the 'Windows 10 Update Fails with Error 0xC1900208' Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-restore-functionality-to-broken-hp-laptop-keyboard-effortlessly/"><u>Troubleshoot and Restore Functionality to Broken HP Laptop Keyboard – Effortlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unraveling-the-mystery-of-fixing-an-unrecoverable-error-in-directx/"><u>Unraveling the Mystery of Fixing an 'Unrecoverable Error' In DirectX</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

