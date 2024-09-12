---
title: Dealing with 'Class Not Registered' Problems in Windows 10 - A Comprehensive Solution
date: 2024-09-11T15:36:24.828Z
updated: 2024-09-12T15:36:24.828Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Dealing with 'Class Not Registered' Problems in Windows 10 - A Comprehensive Solution
excerpt: This Article Describes Dealing with 'Class Not Registered' Problems in Windows 10 - A Comprehensive Solution
thumbnail: https://thmb.techidaily.com/a9744aafdac80a7e4f169749236f6a9a3444533f48662a5ae5f051ec41bdae27.jpg
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
<li><a href="https://youtube-data.techidaily.com/n-2024-dissecting-youtubes-operational-model-post-upload/"><u>[New] In 2024, Dissecting YouTube's Operational Model Post-Upload</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-repairing-windows-update-failure-error-0x8024002e/"><u>Effective Solutions for Repairing Windows Update Failure (Error 0X8024002E)</u></a></li>
<li><a href="https://techtrends.techidaily.com/guida-completa-per-la-conversione-dei-tuoi-videoclip-in-formati-universali-windowsmacandroidiphone/"><u>Guida Completa per La Conversione Dei Tuoi Videoclip in Formati Universali (Windows/Mac/Android/iPhone)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-reactivate-and-repair-the-stalled-diagnostics-monitoring-service/"><u>How to Reactivate and Repair the Stalled Diagnostics Monitoring Service</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/lock-your-motorola-g24-power-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Motorola G24 Power Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/low-cost-4k-gear-for-pros-and-amateurs-for-2024/"><u>Low-Cost 4K Gear for Pros & Amateurs for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-resolving-issues-with-your-lenovo-fingerprint-sensor/"><u>Quick Fixes: Resolving Issues with Your Lenovo Fingerprint Sensor</u></a></li>
<li><a href="https://buynow-info.techidaily.com/samsung-galaxy-showdown-s24-ultra-vs-s23-ultra-specs-and-performance-review/"><u>Samsung Galaxy Showdown: S24 Ultra Vs. S23 Ultra Specs and Performance Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-strategies-against-window-woes-tackling-dead-screens-effectively/"><u>Winning Strategies Against Window Woes: Tackling Dead Screens Effectively</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137213/26400" target="_top" id="2137213">
  <img src="//a.impactradius-go.com/display-ad/26400-2137213" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137213/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

