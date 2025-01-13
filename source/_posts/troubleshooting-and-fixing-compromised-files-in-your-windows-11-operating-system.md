---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2025-01-09T17:33:33.470Z
updated: 2025-01-13T16:07:04.464Z
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
<li><a href="https://tiktok-clips.techidaily.com/new-tap-into-the-quickest-way-for-downloading-musically-videos-for-2024/"><u>[New] Tap Into the Quickest Way for Downloading Musical.ly Videos for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-navigating-phantoms-reverse-video-capabilities/"><u>[Updated] 2024 Approved Navigating Phantom's Reverse Video Capabilities</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-source-unlimited-stock-media-from-top-tier-4-youtube-channels/"><u>2024 Approved Source Unlimited Stock Media From Top-Tier 4 YouTube Channels</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-troubleshooting-steelseries-x50x70-keyboard-solutions-when-the-pen-stops-responding/"><u>Complete Troubleshooting SteelSeries X50/X70 Keyboard: Solutions When The Pen Stops Responding</u></a></li>
<li><a href="https://win-able.techidaily.com/expert-advice-fixing-crashes-and-hitches-in-your-gta-5-gameplay-experience/"><u>Expert Advice: Fixing Crashes and Hitches in Your GTA 5 Gameplay Experience</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/vlogger-to-earnest-by-year-end-following-sourav-joshis-examples/"><u>From Vlogger to Earnest by Year End - Following Sourav Joshi's Examples</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-enable-night-light-when-it-wont-start-on-your-pc-windows-1011/"><u>How to Enable Night Light When It Won't Start on Your PC (Windows 10/11)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-honor-100-pro-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Honor 100 Pro</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-honor-play-40cfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Honor Play 40CFRP Lock</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-rdr2-out-of-memory-mistake-by-boosting-your-pagefile-a-swift-solution/"><u>Resolve 'RDR2 - Out Of Memory' Mistake by Boosting Your Pagefile: A Swift Solution</u></a></li>
<li><a href="https://article-files.techidaily.com/shades-of-success-color-grading-fundamentals-for-2024/"><u>Shades of Success Color Grading Fundamentals for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-frozen-windows-updates-at-100-progress/"><u>Solving the Issue of Frozen Windows Updates at 100% Progress</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206814151-total-war-rome-remastered-game-crash-troubles-discover-these-fixes/"><u>Total War: Rome Remastered Game Crash Troubles? Discover These Fixes!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-out-of-memory-errors-for-a-smoother-gaming-experience-in-rdr2/"><u>Troubleshoot Out-Of-Memory Errors for a Smoother Gaming Experience in RDR2</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-get-your-dell-camera-back-to-work-on-a-windows-pc/"><u>Troubleshooting: How to Get Your Dell Camera Back to Work on a Windows PC</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

