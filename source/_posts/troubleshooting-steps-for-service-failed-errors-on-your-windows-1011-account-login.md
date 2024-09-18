---
title: Troubleshooting Steps for 'Service Failed' Errors on Your Windows 10/11 Account Login
date: 2024-09-11T16:58:52.597Z
updated: 2024-09-17T16:24:39.658Z
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
<li><a href="https://visual-screen-recording.techidaily.com/new-spotifys-1-hit-list-update/"><u>[New] Spotify's #1 Hit List Update</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-trailblazers-in-auditory-and-visual-creation-list/"><u>2024 Approved Trailblazers in Auditory & Visual Creation List</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-resolving-unresponsive-touchpad-issues/"><u>Effective Solutions for Resolving Unresponsive Touchpad Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-logilda-missing-dll-quickly/"><u>Fix LogiLDA Missing DLL Quickly</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-vivo-v27-pro-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Vivo V27 Pro Quickly | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-fix-usb-device-not-detected-error/"><u>Resolved: How to Fix 'USB Device Not Detected' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-common-problems-with-minecrafts-lan-gaming-mode/"><u>Solving Common Problems with Minecraft's LAN Gaming Mode</u></a></li>
<li><a href="https://win-able.techidaily.com/step-by-step-solution-overcoming-directdraw-error-in-windows-applications/"><u>Step-by-Step Solution: Overcoming DirectDraw Error in Windows Applications</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/streamlining-vimeo-uploads-from-moviemaker-projects/"><u>Streamlining Vimeo Uploads From Moviemaker Projects</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackle-laptop-screen-malfunctions-white-screen-error-fixes/"><u>Tackle Laptop Screen Malfunctions: White Screen Error Fixes</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-selection-celebrating-johnny-depps-outstanding-performances-in-film-1985-2015/"><u>The Ultimate Selection: Celebrating Johnny Depp's Outstanding Performances in Film (1985 - 2015)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-solve-ps4-mic-problems-with-these-expert-tips/"><u>Troubleshoot and Solve PS4 Mic Problems with These Expert Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unravel-the-mystery-of-livekernelevent-error-117-and-learn-how-to-correct-it/"><u>Unravel the Mystery of LiveKernelEvent Error 117 and Learn How to Correct It</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/whats-buzzing-the-social-sphere-tiktok-and-twitter-hits-for-2024/"><u>What's Buzzing the Social Sphere? TikTok & Twitter Hits for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

