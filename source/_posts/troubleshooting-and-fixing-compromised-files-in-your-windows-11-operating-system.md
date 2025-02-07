---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2025-02-02T11:32:25.732Z
updated: 2025-02-07T05:56:59.316Z
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-build-your-wealth-on-youtube-a-guide-to-creating-content-without-ads/"><u>[New] 2024 Approved Build Your Wealth on YouTube A Guide to Creating Content Without Ads</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-8-things-to-consider-before-buying-next-lens-for-4k-camera/"><u>[New] 8 Things to Consider Before Buying Next Lens for 4K Camera</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-secrets-of-the-social-elite-6-actionable-tips-for-growing-instagram-followers-for-2024/"><u>[New] Secrets of the Social Elite 6 Actionable Tips for Growing Instagram Followers for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-11-system-lag-and-hanging-problems/"><u>How to Fix Windows 11 System Lag and Hanging Problems?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-vivo-s17-pro-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Vivo S17 Pro to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-when-file-explorer-wont-respond-in-windows-11/"><u>Mastering the Fix: When File Explorer Won't Respond in Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/maximize-impact-mastering-igtv-content-submission/"><u>Maximize Impact Mastering IGTV Content Submission</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209914137-quick-guide-solve-your-sims-4-launching-issues-today/"><u>Quick Guide: Solve Your Sims 4 Launching Issues Today</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-xlivedll-file-absent-issues-a-step-by-step-guide/"><u>Resolving 'Xlive.dll File Absent' Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-unspecified-error-0x80004005-on-your-device-effortlessly/"><u>Resolving the Unspecified Error (0X80004005) on Your Device Effortlessly</u></a></li>
<li><a href="https://program-issues.techidaily.com/step-by-step-fix-for-non-functioning-tozo-t6-software-in-windows-11/"><u>Step-by-Step Fix for Non-Functioning Tozo T6 Software in Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/taking-down-cheats-in-digital-battles-microsofts-commitment-to-elevating-gamers-copilots/"><u>Taking Down Cheats in Digital Battles: Microsoft's Commitment to Elevating Gamer's Copilots</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-tips-for-solving-lag-in-world-of-warcraft-efficiently/"><u>Top Tips for Solving Lag in World of Warcraft Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-brightness-issues-on-windows-10/"><u>Troubleshooting Guide: Fixing Brightness Issues on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-responsive-fn-keys-on-dell-laptops-effective-solutions/"><u>Troubleshooting Non-Responsive Fn Keys on Dell Laptops: Effective Solutions</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-note-12r-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi Note 12R Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

