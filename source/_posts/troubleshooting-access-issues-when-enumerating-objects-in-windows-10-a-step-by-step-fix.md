---
title: Troubleshooting Access Issues When Enumerating Objects in Windows 10 - A Step-by-Step Fix
date: 2024-09-15T19:21:18.020Z
updated: 2024-09-23T00:04:35.306Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Access Issues When Enumerating Objects in Windows 10 - A Step-by-Step Fix
excerpt: This Article Describes Troubleshooting Access Issues When Enumerating Objects in Windows 10 - A Step-by-Step Fix
thumbnail: https://thmb.techidaily.com/105583134b01cefeafa4fc25f0d100c3206487cae2d19190125a50a9ecf80d6e.jpg
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
<li><a href="https://extra-resources.techidaily.com/updated-10-best-screenshot-enhancers-iphoneandroid-sticker-magic/"><u>[Updated] 10 Best Screenshot Enhancers IPhone/Android Sticker Magic</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-ios-meets-classic-play-best-ps2-game-emulators-reviewed-for-2024/"><u>[Updated] IOS Meets Classic Play Best PS2 Game Emulators Reviewed for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-maximize-views-the-art-of-timestamp-integration-on-youtube-for-2024/"><u>[Updated] Maximize Views The Art of Timestamp Integration on YouTube for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-seamlessly-convert-youtube-videos-to-mp3-on-mac/"><u>2024 Approved Seamlessly Convert YouTube Videos to MP3 on Mac</u></a></li>
<li><a href="https://win-howtos.techidaily.com/apex-legends-easy-anti-cheat-error-solved/"><u>Apex Legends Easy Anti-Cheat Error [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-11-how-to-eliminate-persistent-keyboard-delays/"><u>Fixing Windows 11: How to Eliminate Persistent Keyboard Delays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-and-restore-night-light-feature-on-modern-windows-systems/"><u>How to Repair and Restore Night Light Feature on Modern Windows Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/prime-days-most-unbeatable-tech-discounts-on-amazon/"><u>Prime Day's Most Unbeatable Tech Discounts On Amazon</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-pcs-xbox-one-control-connection/"><u>Revive Your PC's Xbox One Control Connection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-keypad-malfunctions-for-your-laptop-under-windows-environments-windows-11-8-and-7/"><u>Solving Keypad Malfunctions for Your Laptop Under Windows Environments [Windows 11, 8 & 7]</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/troubleshooting-guide-resolving-windows-10-usb-recognition-issues/"><u>Troubleshooting Guide: Resolving Windows 10 USB Recognition Issues</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/turn-your-old-kindle-into-an-e-ink-display-instructions-for-successful-hacking/"><u>Turn Your Old Kindle Into an E Ink Display: Instructions for Successful Hacking</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398449/3022" target="_top" id="398449">
  <img src="//a.impactradius-go.com/display-ad/3022-398449" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398449/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

