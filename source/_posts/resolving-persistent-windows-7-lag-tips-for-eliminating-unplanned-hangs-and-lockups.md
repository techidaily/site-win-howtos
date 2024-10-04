---
title: "Resolving Persistent Windows 7 Lag: Tips for Eliminating Unplanned Hangs and Lockups"
date: 2024-09-30T03:55:15.073Z
updated: 2024-10-03T20:48:31.834Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Persistent Windows 7 Lag: Tips for Eliminating Unplanned Hangs and Lockups"
excerpt: "This Article Describes Resolving Persistent Windows 7 Lag: Tips for Eliminating Unplanned Hangs and Lockups"
thumbnail: https://thmb.techidaily.com/0c851aeff0505f93ab9210c28e47cf3dc2d61368996282399757ef6f40d2d48e.jpg
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
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-guide-to-youtubes-best-music-responses/"><u>2024 Approved The Ultimate Guide to YouTube's Best Music Responses</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-oppo-find-x7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-tips-for-fixing-broken-system-components-in-windows-1011/"><u>Comprehensive Tips for Fixing Broken System Components in Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-adjust-display-settings-when-encountered-with-non-standard-input-delays/"><u>How to Adjust Display Settings When Encountered With Non-Standard Input Delays</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-vivo-y100i-by-drfone-android/"><u>How to Bypass FRP from Vivo Y100i?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-sounds-in-forza-horizon-4-after-a-silent-ride-solutions-unveiled/"><u>How to Restore Sounds in Forza Horizon 4 After a Silent Ride – Solutions Unveiled!</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-interplatform-video-uploading-twitter-and-tumblr-synced/"><u>In 2024, Interplatform Video Uploading Twitter & Tumblr Synced</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-solution-for-overcoming-fatal-errors-in-software-installs-error-1603-included/"><u>Master Solution for Overcoming Fatal Errors in Software Installs, Error 1603 Included</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-oculus-hardware-maintenance-avoid-and-fix-the-top-errors-of-2024/"><u>Mastering Oculus Hardware Maintenance: Avoid and Fix the Top Errors of 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-the-stuck-startup-a-users-manual-for-windows-preparing-glitches-on-computers/"><u>Resolve the Stuck Startup: A User's Manual for Windows Preparing Glitches on Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-a-broken-start-menu-on-windows-11-step-by-step-tips-and-tricks/"><u>Reviving a Broken Start Menu on Windows 11 - Step-by-Step Tips & Tricks</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/settle-down-with-our-best-10-chill-titles-for-2024/"><u>Settle Down with Our Best 10 Chill Titles for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Motorola G24 Power? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-revive-the-lights-of-a-faulty-corsair-backlight-keyboard/"><u>Step-by-Step Guide to Revive the Lights of a Faulty Corsair Backlight Keyboard</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-interactive-index-for-ig-and-tiktok-connection/"><u>The Interactive Index for IG & TikTok Connection</u></a></li>
<li><a href="https://fox-useful.techidaily.com/the-ultimate-tutorial-on-moving-pictures-from-pc-to-iphone-xs-seamlessly/"><u>The Ultimate Tutorial on Moving Pictures From PC to iPhone XS Seamlessly</u></a></li>
<li><a href="https://tech-hub.techidaily.com/turing-test-explained-and-future-competitors/"><u>Turing Test Explained & Future Competitors?</u></a></li>
<li><a href="https://techidaily.com/turn-off-screen-lock-vivo-by-drfone-android-unlock-android-unlock/"><u>Turn Off Screen Lock - Vivo</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-a-step-by-step-guide-to-restoring-usb-port-functionality/"><u>Windows 11: A Step-by-Step Guide to Restoring USB Port Functionality</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

