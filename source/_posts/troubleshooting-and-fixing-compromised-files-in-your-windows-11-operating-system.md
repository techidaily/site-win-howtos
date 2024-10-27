---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2024-10-24T16:42:53.975Z
updated: 2024-10-27T17:05:24.949Z
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
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-webcam-and-monitor-recording-how-to-combine/"><u>[New] In 2024, Webcam & Monitor Recording How to Combine</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-gecata-game-recorder-review-complete/"><u>[Updated] In 2024, Gecata Game Recorder Review [Complete]</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-social-media-strategists-guide-top-10-ig-video-editing-apps/"><u>[Updated] In 2024, Social Media Strategists' Guide Top 10 IG Video Editing Apps</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-walking-deadlines-the-ultimate-selection-of-excellent-zombie-games/"><u>2024 Approved Walking Deadlines The Ultimate Selection of Excellent Zombie Games</u></a></li>
<li><a href="https://fox-http.techidaily.com/avoidance-tactics-no-more-recommended-podcasts-on-spotify/"><u>Avoidance Tactics No More Recommended Podcasts on Spotify</u></a></li>
<li><a href="https://win-howtos.techidaily.com/can-you-watch-netflix-right-now-how-to-check-for-service-interruptions/"><u>Can You Watch Netflix Right Now? How to Check for Service Interruptions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-resolving-non-functional-wacom-tablet-dilemmas/"><u>Diagnosing and Resolving Non-Functional Wacom Tablet Dilemmas</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-resolving-problems-with-minecraft-local-area-network-play/"><u>Expert Tips for Resolving Problems with Minecraft Local Area Network Play</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-stop-nier-automata-from-crashing-on-windows-systems-solutions/"><u>How to Stop Nier: Automata From Crashing on Windows Systems: Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-common-file-explorer-issues-in-windows-11-get-expert-advice/"><u>Quick Fixes for Common File Explorer Issues in Windows 11 - Get Expert Advice!</u></a></li>
<li><a href="https://solve-lab.techidaily.com/recadrez-vos-clips-videos-avec-ces-10-gratuites-logiciels-de-montage-video-maitres-2024/"><u>Recadrez Vos Clips Vidéos Avec Ces 10 Gratuites Logiciels De Montage Vidéo Maîtres 2024 !</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-hurdles-during-steam-game-update-installations/"><u>Resolving Hurdles During Steam Game Update Installations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-11-screen-interaction-problems-five-essential-solutions/"><u>Solving Windows 11 Screen Interaction Problems: Five Essential Solutions</u></a></li>
<li><a href="https://fox-tips.techidaily.com/step-by-step-guide-converting-vrtbe-streams-into-multiple-video-formats/"><u>Step-by-Step Guide: Converting VRT.be Streams Into Multiple Video Formats</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/top-30-metaverse-meme-creation-tips-and-trends/"><u>Top 30 Metaverse Meme Creation Tips & Trends</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948876/19272" target="_top" id="1948876">
  <img src="//a.impactradius-go.com/display-ad/19272-1948876" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948876/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

