---
title: Laptop Mousepad Not Working in Windows 10/8/7 [SOLVED]
date: 2024-11-23T21:45:17.995Z
updated: 2024-11-28T03:11:36.540Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Laptop Mousepad Not Working in Windows 10/8/7 [SOLVED]
excerpt: This Article Describes Laptop Mousepad Not Working in Windows 10/8/7 [SOLVED]
thumbnail: https://thmb.techidaily.com/5584d777e110cbdbb48713bd82133ccfd2417ed4baa291781cd47c73ffc42e1f.jpeg
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-crafting-stunning-youtubers-imagery-a-comprehensive-walkthrough/"><u>[New] 2024 Approved Crafting Stunning YouTubers' Imagery A Comprehensive Walkthrough</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-elevate-your-presence-instagrams-path-to-prominence/"><u>[New] Elevate Your Presence Instagram's Path to Prominence</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-theme-that-stands-out-crafting-banners-for-gamers/"><u>[New] Theme That Stands Out Crafting Banners for Gamers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-craft-your-countdown-adding-time-management-to-obs-sessions/"><u>[Updated] 2024 Approved Craft Your Countdown Adding Time Management to OBS Sessions</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-rise-in-search-results-mastering-podcast-seo/"><u>[Updated] Rise in Search Results Mastering Podcast SEO</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212469732-computer-wont-shut-down-windows-10-solved/"><u>Computer Won't Shut Down Windows 10 [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cutting-down-on-ps4-sound-identifying-issues-and-implementing-solutions/"><u>Cutting Down on PS4 Sound: Identifying Issues and Implementing Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207100044-error-1603-decoded-expert-strategies-for-a-seamless-and-successful-software-setup/"><u>Error 1603 Decoded: Expert Strategies for a Seamless and Successful Software Setup.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expertly-tackle-windows-10-taskbar-issues-top-fixes-revealed/"><u>Expertly Tackle Windows 10 Taskbar Issues: Top Fixes Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-unresponsive-chrome-browser-quick-refresh-tips/"><u>Fixing Unresponsive Chrome Browser - Quick Refresh Tips</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-pictures-files-from-samsung-galaxy-z-fold-5-by-fonelab-android-recover-pictures/"><u>How To Restore Missing Pictures Files from Samsung Galaxy Z Fold 5.</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-best-free-avi-video-rotators-multi-platform-solutions-compared/"><u>New In 2024, Best Free AVI Video Rotators Multi-Platform Solutions Compared</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-driver-not-found-issue-with-your-wacom-tablet-on-windows-11/"><u>Resolving the 'Driver Not Found' Issue with Your Wacom Tablet on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/safari-not-working-here-are-5-easy-ways-to-get-pages-opened-quickly/"><u>Safari Not Working? Here Are 5 Easy Ways to Get Pages Opened Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-guide-overcoming-windows-network-error-code-0x800704cf/"><u>Solved Guide: Overcoming Windows Network Error Code 0X800704CF</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-tutorial-transforming-dvd-audio-into-premium-dolby-digitaldts-for-surround-sound-enthusiasts/"><u>Step-by-Step Tutorial: Transforming DVD Audio Into Premium Dolby Digital/DTS for Surround Sound Enthusiasts</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-solving-issues-with-your-corsair-void-microphone/"><u>Troubleshooting Guide: Solving Issues with Your Corsair Void Microphone</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-wizardry-unlock-15-life-saving-fixes-for-your-iphone/"><u>Troubleshooting Wizardry: Unlock 15 Life-Saving Fixes for Your iPhone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-bluetooth-device-shows-as-pairing-in-windows-11-but-wont-connect/"><u>Troubleshooting: Bluetooth Device Shows as Pairing in Windows 11, But Won't Connect</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

