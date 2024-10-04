---
title: Expert Troubleshooting Steps for Windows Display Malfunctions
date: 2024-09-27T02:42:40.225Z
updated: 2024-10-03T18:40:53.857Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Troubleshooting Steps for Windows Display Malfunctions
excerpt: This Article Describes Expert Troubleshooting Steps for Windows Display Malfunctions
thumbnail: https://thmb.techidaily.com/06411bb0a4ac0185fbc154f8c0ddc984322d7b8bfe4f5c8cf3dfa60ab70bed43.jpg
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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-choosing-gopro-wisely-a-comparative-examination/"><u>[New] In 2024, Choosing GoPro Wisely A Comparative Examination</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ten-strategies-for-controlling-a-twitch-broadcast/"><u>2024 Approved Ten Strategies for Controlling a Twitch Broadcast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ensuring-seamless-sleep-in-windows-11/"><u>Ensuring Seamless Sleep in Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-picks-leading-portable-screening-devices-cnet-insights/"><u>Expert Picks: Leading Portable Screening Devices | CNET Insights</u></a></li>
<li><a href="https://fix-guide.techidaily.com/huawei-p60-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Huawei P60 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-activation-lock-on-iphone-8-plus-4-easy-ways-by-drfone-ios/"><u>In 2024, Bypass Activation Lock On iPhone 8 Plus - 4 Easy Ways</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-future-is-now-equip-yourself-with-these-7-devices/"><u>In 2024, The Future Is Now - Equip Yourself with These 7 Devices</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/playstation-5s-one-of-a-kind-game-library-unveiled/"><u>PlayStation 5'S One-of-a-Kind Game Library Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-driver-failure-message-due-to-incorrect-user-settings/"><u>Resolving the 'Driver Failure' Message Due to Incorrect User Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-login-issues-fixing-user-profile-service-failures/"><u>Resolving Windows 11 Login Issues: Fixing User Profile Service Failures</u></a></li>
<li><a href="https://unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-vivo-v30-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Vivo V30</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-making-your-dvd-playable-on-a-windows-system/"><u>Step-by-Step Guide to Making Your DVD Playable on a Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-unresponsive-file-explorer-in-windows-10-environments/"><u>Step-by-Step Solutions for Unresponsive File Explorer in Windows 10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-windows-media-source-errors-for-games/"><u>Troubleshooting and Resolving Windows Media Source Errors for Games</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-the-leading-gratis-converters-srt-edition-for-2024/"><u>Unveiling the Leading Gratis Converters SRT Edition for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

