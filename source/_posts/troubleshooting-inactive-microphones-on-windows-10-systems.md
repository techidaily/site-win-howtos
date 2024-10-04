---
title: Troubleshooting Inactive Microphones on Windows 10 Systems
date: 2024-10-03T09:20:02.326Z
updated: 2024-10-04T10:23:08.940Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Inactive Microphones on Windows 10 Systems
excerpt: This Article Describes Troubleshooting Inactive Microphones on Windows 10 Systems
thumbnail: https://thmb.techidaily.com/0a6fdf457b7ae04c7271bb5ef452861b60d681e9fcfecf39700de5889b22829e.jpg
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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-ultimate-guide-to-choosing-winning-screen-recording-software-for-windows/"><u>[New] In 2024, Ultimate Guide to Choosing Winning Screen Recording Software for Windows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-effortless-guide-to-adding-banners-on-gaming-channels/"><u>[Updated] 2024 Approved Effortless Guide to Adding Banners on Gaming Channels</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-ultimate-playbook-for-exceptional-obs-studio-content-for-2024/"><u>[Updated] The Ultimate Playbook for Exceptional OBS Studio Content for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/affluent-streaming-stars-for-2024/"><u>Affluent Streaming Stars for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/asus-ax6000-rt-ax88u-wireless-gigabit-router-evaluation-the-ultimate-smart-wifi-6-device/"><u>Asus AX6000 RT-AX88U Wireless Gigabit Router Evaluation - The Ultimate Smart WiFi 6 Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/battleye-service-installed-properly-addressing-previous-installation-challenges-with-confidence/"><u>BattlEye Service Installed Properly: Addressing Previous Installation Challenges with Confidence</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-the-ultimate-matchmaker-toolkit/"><u>ChatGPT: The Ultimate Matchmaker Toolkit</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquering-the-persistent-error-0x80072efd-on-windows-11-effective-fix-methods-revealed/"><u>Conquering the Persistent Error 0X80072EFD on Windows 11 - Effective Fix Methods Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeating-ps4-network-errors-an-in-depth-stepwise-strategy-for-nat-success/"><u>Defeating PS4 Network Errors: An In-Depth Stepwise Strategy for NAT Success</u></a></li>
<li><a href="https://os-tips.techidaily.com/discover-how-cash-app-upgrades-offer-parallel-benefits-to-apple-cards-robust-savings-options/"><u>Discover How Cash App Upgrades Offer Parallel Benefits to Apple Card's Robust Savings Options</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hard-drive-is-not-detected-solved/"><u>Hard Drive Is Not Detected [SOLVED]</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-filming-friends-directly-share-videos-on-twitter/"><u>In 2024, Filming Friends Directly Share Videos on Twitter</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/navigating-the-world-of-smartwatches-in-depth-analysis-of-the-amazfit-bip/"><u>Navigating the World of Smartwatches: In-Depth Analysis of the Amazfit Bip</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-identifying-and-fixing-windows-update-db-issues-on-windows-10/"><u>Resolved: Identifying and Fixing Windows Update DB Issues on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-not-found-errors-at-bootup-fixes-for-windows-systems/"><u>Troubleshooting 'Not Found' Errors at Bootup – Fixes for Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-startup-problems-with-minecraft-in-windows/"><u>Troubleshooting Guide: Resolving Startup Problems with Minecraft in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-unlocking-the-fix-for-constant-reboot-on-windows-1011-systems/"><u>Troubleshooting: Unlocking the Fix for Constant Reboot on Windows 10/11 Systems</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-xiaomi-14-ultra-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Xiaomi 14 Ultra.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-the-0x80072efd-glitch-in-windows-11-proven-strategies-and-solutions/"><u>Winning Against the 0X80072EFD Glitch in Windows 11: Proven Strategies and Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

