---
title: "Troubleshooting Vanished Desktop Icons on Windows 10: Solutions Proven Effective"
date: 2024-12-15T23:29:17.084Z
updated: 2024-12-22T21:05:28.844Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Vanished Desktop Icons on Windows 10: Solutions Proven Effective"
excerpt: "This Article Describes Troubleshooting Vanished Desktop Icons on Windows 10: Solutions Proven Effective"
thumbnail: https://thmb.techidaily.com/9ca2eff6ae26123de716ede19623049b700dbda01116c41da9ae37331ba659b6.jpg
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
<li><a href="https://youtube-sure.techidaily.com/outubes-secrets-to-efficient-frame-viewing-free-for-2024/"><u>[New] YouTube's Secrets to Efficient Frame Viewing (FREE!) For 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-essential-software-for-live-video-recording/"><u>[Updated] Essential Software for Live Video Recording</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-unveil-top-10plus-platforms-for-virtual-worship-spaces-for-2024/"><u>[Updated] Unveil Top 10+ Platforms for Virtual Worship Spaces for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/capturing-magic-in-microphones-iphoneipad-tactics-for-superior-recordings/"><u>Capturing Magic in Microphones IPhone/iPad Tactics for Superior Recordings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-repair-internet-connections-using-ethernet-on-pcs-running-windows-11-or-7/"><u>Expert Tips to Repair Internet Connections Using Ethernet on PCs Running Windows 11 or 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-restore-ethernet-functionality-in-windows-117-systems/"><u>Expert Tips to Restore Ethernet Functionality in Windows 11/7 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-enable-and-launch-a-hosted-network-on-your-pc-windows-10/"><u>How to Successfully Enable and Launch a Hosted Network on Your PC (Windows 10)</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-more-than-clicks-what-determines-youtubes-view-numbers/"><u>In 2024, More than Clicks What Determines YouTube's View Numbers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-the-essential-pathway-to-hd-video-acquisition-on-fb/"><u>In 2024, The Essential Pathway to HD Video Acquisition on FB</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/modern-design-meets-advanced-illumination-dive-into-the-taotronics-tt-dl16-review/"><u>Modern Design Meets Advanced Illumination: Dive Into the TaoTronics TT-DL16 Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203956621-resolving-overwatch-voiceless-glitches-with-simple-steps/"><u>Resolving Overwatch Voiceless Glitches with Simple Steps!</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/trending-rap-anthems-from-tiktok-stars-for-2024/"><u>Trending Rap Anthems From TikTok Stars for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211952733-troubleshoot-and-successfully-install-battleye-anti-cheat-now/"><u>Troubleshoot and Successfully Install BattlEye Anti-Cheat Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-cast-failures-easy-fixes-and-tips-for-users/"><u>Windows 11 Cast Failures: Easy Fixes and Tips for Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-steams-endless-update-loop-solutions-revealed/"><u>Winning the Battle Against Steam's Endless Update Loop - Solutions Revealed</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1726226450232-aifc-m4a-moveavew/"><u>오피스에서 자원 지출 없이 AIFC M4A를 효과적으로 변환하는 방법: Moveavew</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

