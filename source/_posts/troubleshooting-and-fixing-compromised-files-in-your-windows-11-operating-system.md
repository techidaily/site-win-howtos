---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2025-02-15T01:02:23.340Z
updated: 2025-02-17T01:15:18.708Z
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
<li><a href="https://youtube-web.techidaily.com/apid-method-converting-images-into-desktop-thumbnails-for-youtube-for-2024/"><u>[New] Rapid Method Converting Images Into Desktop Thumbnails for YouTube for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-web-based-jest-architect-for-2024/"><u>[Updated] Web-Based Jest Architect for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-stream-youtube-in-the-background-using-iphone-and-android/"><u>2024 Approved Stream YouTube in the Background Using iPhone & Android</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-and-repair-windows-10-youtube-audio-renderer-error-for-smooth-viewing/"><u>Bypass and Repair Windows 10 YouTube Audio Renderer Error for Smooth Viewing</u></a></li>
<li><a href="https://techidaily.com/data-driven-strategies-harnessing-consumer-understanding-in-the-intelligent-enterprise-era/"><u>Data-Driven Strategies: Harnessing Consumer Understanding in the Intelligent Enterprise Era</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/delving-into-digital-innovation-with-toms-hardware-insights/"><u>Delving Into Digital Innovation with Tom's Hardware Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-fixing-unresponsive-keyboard-shortcuts-fn-on-an-asus-laptop/"><u>Effective Solutions for Fixing Unresponsive Keyboard Shortcuts (Fn) on an ASUS Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-touchscreen-working-in-windows-11-a-5-step-guide/"><u>Getting Your Touchscreen Working in Windows 11: A 5-Step Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-oneplus-ace-2-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My OnePlus Ace 2 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-prime-business-sky-storage-choice/"><u>In 2024, Prime Business Sky-Storage Choice</u></a></li>
<li><a href="https://fox-metric.techidaily.com/quick-solutions-how-to-identify-and-fix-screen-issues-in-windows-tips-by-yl-computing/"><u>Quick Solutions: How to Identify and Fix Screen Issues in Windows - Tips by YL Computing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-expert-advice-on-handling-and-resetting-your-computers-video-driver-error/"><u>Resolved! Expert Advice on Handling and Resetting Your Computer's Video Driver Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-audio-expert-tips-for-fixing-an-acer-laptop-without-sound-output/"><u>Reviving Audio: Expert Tips for Fixing an Acer Laptop Without Sound Output</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-addressing-wow-slow-down-and-hiccups/"><u>Step-by-Step Solutions for Addressing WoW Slow Down & Hiccups</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-recovery-from-0x8024200d-boosting-windows-update-functionality/"><u>Successful Recovery From 0X8024200d - Boosting Windows Update Functionality</u></a></li>
<li><a href="https://fox-direct.techidaily.com/the-ultimate-guide-to-iphone-gif-management/"><u>The Ultimate Guide to iPhone GIF Management</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/troubleshooting-network-issues-with-expert-advice-from-yl-software-experts/"><u>Troubleshooting Network Issues with Expert Advice From YL Software Experts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-defender-smartscreen-temporarily-unavailable/"><u>Troubleshooting: Windows Defender SmartScreen Temporarily Unavailable</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooting-for-error-0xc1900208-in-your-windows-11-updates/"><u>Ultimate Troubleshooting for Error 0Xc1900208 in Your Windows 11 Updates</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

