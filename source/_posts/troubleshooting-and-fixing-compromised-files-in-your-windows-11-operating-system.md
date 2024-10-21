---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2024-10-19T19:05:28.178Z
updated: 2024-10-21T18:10:33.474Z
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-navigating-the-tech-maze-screen-casting-sessions/"><u>[New] 2024 Approved Navigating the Tech Maze Screen Casting Sessions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-easy-media-sharing-on-twitter-no-retweets-required-for-2024/"><u>[Updated] Easy Media Sharing on Twitter - No Retweets Required for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/amend-deteriorated-webp-and-mpeg-1/"><u>Amend Deteriorated WebP and MPEG-1</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bringing-life-back-to-darkened-mac-and-windows-keyboards-fixes-inside/"><u>Bringing Life Back to Darkened Mac & Windows Keyboards – Fixes Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-tips-for-resolving-missing-binkw32dll-errors-on-your-pc/"><u>Essential Tips for Resolving Missing binkw32.dll Errors on Your PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/factory-reset-on-iphone-6s-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset on iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/fixed-youtube-shorts-not-showing-up-for-2024/"><u>Fixed YouTube Shorts Not Showing Up for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-10-online-tools-to-retrieve-youtube-graphics/"><u>In 2024, 10 Online Tools to Retrieve YouTube Graphics</u></a></li>
<li><a href="https://extra-resources.techidaily.com/innovative-ideas-to-boost-package-prelude-joy/"><u>Innovative Ideas to Boost Package Prelude Joy</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-msmpengexes-overuse-of-resources-a-guide-for-windows-11-users/"><u>Resolve MsMpEng.exe's Overuse of Resources: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-frustrating-lag-in-minecraft-a-comprehensive-fixing-manual/"><u>Stop Frustrating Lag in Minecraft: A Comprehensive Fixing Manual</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-non-responsive-lenovo-mouse-pads-in-windows-11-8-and-7-repair-guide/"><u>Troubleshooting Tips for Non-Responsive Lenovo Mouse Pads in Windows 11, 8 & #7; [REPAIR GUIDE]</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/tweeting-visual-stories-from-vids-to-interactive-gifs-for-2024/"><u>Tweeting Visual Stories From Vids to Interactive GIFs for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997662/19272" target="_top" id="1997662">
  <img src="//a.impactradius-go.com/display-ad/19272-1997662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997662/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

