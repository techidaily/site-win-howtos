---
title: Troubleshooting Steps for Persistent Bluetooth Pairing Problems on Win10
date: 2025-01-13T19:50:46.661Z
updated: 2025-01-19T18:49:19.056Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps for Persistent Bluetooth Pairing Problems on Win10
excerpt: This Article Describes Troubleshooting Steps for Persistent Bluetooth Pairing Problems on Win10
thumbnail: https://thmb.techidaily.com/d0b73eb28e24a2f2ed6215d7e2c211efc75eaeb77baea06879d148a0fe930510.jpg
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
<li><a href="https://win-howtos.techidaily.com/directory-name-not-recognized-steps-for-resolution-and-prevention/"><u>'Directory Name Not Recognized': Steps for Resolution and Prevention</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-swift-transformation-androids-best-vid-upgrades/"><u>[New] 2024 Approved Swift Transformation Android's Best Vid Upgrades</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-strategies-for-effective-screen-sharing-via-skype-at-home/"><u>[Updated] In 2024, Strategies for Effective Screen Sharing via Skype at Home</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-filmmakers-handbook-building-effective-luts/"><u>2024 Approved A Filmmaker's Handbook Building Effective LUTs</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-resolving-disconnected-sound-on-obs-broadcast/"><u>2024 Approved Resolving Disconnected Sound on OBS Broadcast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/adjusted-permissions-enable-secure-download-access-with-updated-security-preferences/"><u>Adjusted Permissions: Enable Secure Download Access with Updated Security Preferences</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dell-notebook-keyboard-failure-heres-how-to-restore-functionality/"><u>Dell Notebook Keyboard Failure? Here's How to Restore Functionality</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Samsung Galaxy XCover 7? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-internet-access-with-windows-11s-built-in-usb-tethering-feature/"><u>Effortless Internet Access with Windows 11'S Built-In USB Tethering Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-2021-graphics-renderer-start-up-issue-steps-and-tips/"><u>Fixing the 2021 Graphics Renderer Start-Up Issue: Steps and Tips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-prime-10-applications-for-real-time-sporting-events-and-football-games/"><u>In 2024, Prime 10 Applications for Real-Time Sporting Events & Football Games</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-xiaomi-mix-fold-3-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Xiaomi Mix Fold 3 Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/movavi-como-cambiar-videoclips-wmv-por-avi-sin-costo-guia-simple/"><u>Movavi: Cómo Cambiar Videoclips WMV Por AVI Sin Costo - Guía Simple</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-essential-3d-video-editing-tools-every-creator-should-use/"><u>New Essential 3D Video Editing Tools Every Creator Should Use</u></a></li>
<li><a href="https://win-howtos.techidaily.com/printer-setup-solutions-deciphering-and-addressing-the-error-code-30-dilemma/"><u>Printer Setup Solutions: Deciphering and Addressing the 'Error Code -30' Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-game-installation-errors-heres-how-to-fix-them/"><u>Steam Game Installation Errors? Here's How to Fix Them!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-the-persistent-windows-10-update-failure-code-0x80070541/"><u>Troubleshooting and Fixing the Persistent 'Windows 10 Update Failure: Code 0X80070541'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-resolve-windows-10s-0x80072efd-error-efficiently/"><u>Troubleshooting Tips: Resolve Windows 10'S 0X80072EFD Error Efficiently</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-blurry-text-heres-how-to-fix-it/"><u>Windows 10 Blurry Text? Here’s How to Fix It</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

