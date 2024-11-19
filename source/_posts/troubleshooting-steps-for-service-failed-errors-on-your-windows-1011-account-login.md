---
title: Troubleshooting Steps for 'Service Failed' Errors on Your Windows 10/11 Account Login
date: 2024-11-14T22:48:58.431Z
updated: 2024-11-18T16:30:57.059Z
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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-top-7-strategies-for-delicious-food-vids/"><u>[New] 2024 Approved Top 7 Strategies for Delicious Food Vids</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-free-video-player-face-off-vlc-against-mpc/"><u>[New] Free Video Player Face-Off VLC Against MPC</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-discovering-6-interactive-workout-ideas-for-social-media-success/"><u>2024 Approved Discovering 6 Interactive Workout Ideas for Social Media Success</u></a></li>
<li><a href="https://win-answers.techidaily.com/achieving-buttery-smooth-gaming-how-to-overcome-stuttering-challenges-s-high-fps-titles/"><u>Achieving Buttery-Smooth Gaming: How to Overcome Stuttering Challenges 'S High FPS Titles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avoid-upgrade-headaches-with-this-guide-to-fixing-the-0x80070002-windows-update-error/"><u>Avoid Upgrade Headaches with This Guide to Fixing the 0X80070002 Windows Update Error!</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/crafting-visual-stories-select-the-best-ig-video-editors/"><u>Crafting Visual Stories Select the Best IG Video Editors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ensure-smooth-gaming-overcoming-nier-automata-pc-freezes-and-crashes/"><u>Ensure Smooth Gaming: Overcoming Nier Automata PC Freezes and Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-resolving-your-hp-laptop-webcam-problems-with-windows-11/"><u>Expert Tips: Resolving Your HP Laptop Webcam Problems with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-lag-woes-pro-tips-for-smooth-gameplay-in-fallout/"><u>Fixing Lag Woes: Pro Tips for Smooth Gameplay in Fallout</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-t2x-5g-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo T2x 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-fix-geforce-experience-not-opening-glitch-guide/"><u>How to Successfully Fix 'GeForce Experience Not Opening' Glitch [Guide]</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-ispoofer-on-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Poco F5 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-fixes-for-when-your-huion-stylus-fails-discover-5-effective-tips/"><u>Immediate Fixes for When Your Huion Stylus Fails - Discover 5 Effective Tips</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-easy-to-follow-steps-crafting-animated-gifs-from-youtube-content-pcmobile/"><u>In 2024, Easy-to-Follow Steps Crafting Animated GIFs From YouTube Content (PC/Mobile)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-upgrade-your-iphones-ringtone-selection/"><u>In 2024, How to Upgrade Your iPhone's Ringtone Selection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-11-solving-stuck-scrolling-problems-with-touchpad/"><u>Troubleshooting Windows 11: Solving Stuck Scrolling Problems with Touchpad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winupdate-trouble-heres-how-to-fix-error-0x80240017-for-good/"><u>WinUpdate Trouble? Here's How to Fix Error 0X80240017 for Good</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

