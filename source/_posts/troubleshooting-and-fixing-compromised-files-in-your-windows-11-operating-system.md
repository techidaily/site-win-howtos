---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2024-11-15T19:48:52.934Z
updated: 2024-11-18T23:46:21.898Z
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-mastering-social-media-creating-effective-fb-videos/"><u>[New] 2024 Approved Mastering Social Media Creating Effective FB Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-overcoming-the-obstacle-of-windows-11s-error-code-0xc1900208/"><u>[SOLVED] Overcoming the Obstacle of Windows 11'S Error Code: 0XC1900208</u></a></li>
<li><a href="https://win-howtos.techidaily.com/astro-a40-audio-troubles-heres-how-you-can-make-your-mic-work-again/"><u>Astro A40 Audio Troubles? Here's How You Can Make Your Mic Work Again</u></a></li>
<li><a href="https://sound-issues.techidaily.com/cant-talk-problems-heres-how-you-can-enable-voice-chat-in-rainbow-six-siege-after-the-latest-upgrade/"><u>Can't Talk Problems? Here's How You Can Enable Voice Chat in Rainbow Six Siege After the Latest Upgrade</u></a></li>
<li><a href="https://win-howtos.techidaily.com/compatibility-issue-display-does-not-recognize-hdcp-protocols/"><u>Compatibility Issue: Display Does Not Recognize HDCP Protocols</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-fixing-windows-could-not-be-installed-error-with-code-80240020-on-your-pc/"><u>Guide to Fixing 'Windows Could Not Be Installed' Error with Code 80240020 on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-an-io-device-error/"><u>How to Fix an I/O Device Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-nvidia-share-not-responding-problems-effectively/"><u>How To Resolve NVIDIA Share Not Responding Problems Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-your-graphics-drivers-after-an-unexpected-reboot/"><u>How to Resolve Your Graphics Drivers After an Unexpected Reboot</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-huawei-p60-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Huawei P60 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-streamsavvy-exploring-alternatives-to-dacast/"><u>In 2024, StreamSavvy Exploring Alternatives to DaCast</u></a></li>
<li><a href="https://tech-haven.techidaily.com/innovative-strategies-to-perfect-your-resume-with-ai/"><u>Innovative Strategies to Perfect Your Resume with AI</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-chronicles-expert-tips-for-story-downloads-for-2024/"><u>Instagram Chronicles Expert Tips for Story Downloads for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/meta-quest-2-light-anticipated-costs-release-date-and-latest-specs-whats-next-for-oculus/"><u>Meta Quest 2 Light: Anticipated Costs, Release Date & Latest Specs - What's Next for Oculus?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repair-your-windows-10-with-sfc-and-dism-a-comprehensive-guide/"><u>Repair Your Windows 10 with SFC & DISM - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211779531-twitch-troubles-heres-how-you-can-resolve-error-4000-effectively/"><u>Twitch Troubles? Here's How You Can Resolve Error 4000 Effectively</u></a></li>
<li><a href="https://win-solutions.techidaily.com/ultimate-solution-preventing-ffxiv-pc-game-freezes-and-crashes/"><u>Ultimate Solution: Preventing FFXIV PC Game Freezes and Crashes</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

