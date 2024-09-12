---
title: Troubleshooting Steps for 'Service Failed' Errors on Your Windows 10/11 Account Login
date: 2024-09-11T15:37:35.912Z
updated: 2024-09-12T15:37:35.912Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps for 'Service Failed' Errors on Your Windows 10/11 Account Login
excerpt: This Article Describes Troubleshooting Steps for 'Service Failed' Errors on Your Windows 10/11 Account Login
thumbnail: https://thmb.techidaily.com/f0ebef61d0b2c8908bbc43dc1da12abaf166bb4f6229b3a45bf569455ab91d1f.jpg
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
<li><a href="https://some-techniques.techidaily.com/2024-approved-highpoint-masterpiece-suite/"><u>2024 Approved Highpoint Masterpiece Suite</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-quick-twitterscape-snag-gifs-with-these-tips/"><u>2024 Approved Quick Twitterscape Snag Gifs with These Tips</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-updated-interview-playbook-for-audience-allure/"><u>2024 Approved Updated Interview Playbook for Audience Allure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207222250-accelerate-your-league-of-legends-installations-no-more-sluggish-downloads/"><u>Accelerate Your League of Legends Installations: No More Sluggish Downloads!</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevating-videography-mastery-of-the-green-screen-effect/"><u>Elevating Videography Mastery of the Green Screen Effect</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-setting-up-your-microsoft-wireless-display-adapter-for-optimal-performance-on-windows-10-devices/"><u>Expert Advice on Setting Up Your Microsoft Wireless Display Adapter for Optimal Performance on Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hit-compliant-resolution-enhanced-missing-touch-sensitivity/"><u>HIT Compliant Resolution - Enhanced Missing Touch Sensitivity</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pixel-magic-transforming-still-images-to-video-with-pixiz/"><u>In 2024, Pixel Magic Transforming Still Images to Video with Pixiz</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-of-the-best-airflow-ssd-cooler-the-unbeatable-teamgroup-t-force/"><u>In-Depth Analysis of the Best Airflow SSD Cooler: The Unbeatable TeamGroup T-Force</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-mp3-optimization-101-top-editing-practices-for-sound-quality/"><u>New 2024 Approved MP3 Optimization 101 Top Editing Practices for Sound Quality</u></a></li>
<li><a href="https://buynow-help.techidaily.com/reinventing-mobile-working-space-dive-into-the-features-of-the-msi-pro-mp161-e2-portable-display/"><u>Reinventing Mobile Working Space: Dive Into the Features of the MSI PRO MP161 E2 Portable Display</u></a></li>
<li><a href="https://win-howtos.techidaily.com/startup-issues-resolved-for-your-troubled-computing-device/"><u>Startup Issues Resolved for Your Troubled Computing Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/success-story-diagnosing-and-repairing-failed-connections-with-dhcp-servers/"><u>Success Story: Diagnosing and Repairing Failed Connections with DHCP Servers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-errors-resolving-failed-to-load-in-hardware-monitor-drivers/"><u>Troubleshooting Errors: Resolving 'Failed to Load' In Hardware Monitor Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-logitech-keyboard-wont-connect-with-windows-10/"><u>Troubleshooting Steps When Logitech Keyboard Won’t Connect with Windows 10</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1424529">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424529.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424529">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424529.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424529%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424529/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

