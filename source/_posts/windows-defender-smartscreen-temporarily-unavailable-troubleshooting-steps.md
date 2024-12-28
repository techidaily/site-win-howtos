---
title: Windows Defender SmartScreen Temporarily Unavailable - Troubleshooting Steps
date: 2024-12-24T14:18:51.589Z
updated: 2024-12-28T12:28:34.885Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows Defender SmartScreen Temporarily Unavailable - Troubleshooting Steps
excerpt: This Article Describes Windows Defender SmartScreen Temporarily Unavailable - Troubleshooting Steps
thumbnail: https://thmb.techidaily.com/e66e28dff9a78d29ac6c41d0e2dd487a7c339d734ca57b3143f21e9c629c5f8e.jpg
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-dial-up-beats-easy-audio-posting-to-youtubes/"><u>[New] 2024 Approved Dial-Up Beats Easy Audio Posting to YouTubes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-step-by-step-techniques-for-google-meet-coordination/"><u>[Updated] Step-by-Step Techniques for Google Meet Coordination</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-windows-update-trouble-clearing-code-8007000e-with-ease/"><u>Bypass Windows Update Trouble: Clearing Code 8007000E with Ease!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/device-demise-system-error-out-of-control/"><u>Device Demise: System Error Out of Control</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-issue-reinstate-protection-for-localized-credential-handling-processes/"><u>Fixed Issue: Reinstate Protection for Localized Credential Handling Processes</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-itel-p55plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-overcome-directx-graphic-device-initialization-issues/"><u>How to Successfully Overcome DirectX Graphic Device Initialization Issues</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-and-updated-drivers-for-epson-v500-free-download-now/"><u>Latest and Updated Drivers for Epson V500 - Free Download Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-11-v1803-update-issues-a-step-by-step-guide/"><u>Overcoming Windows 11 v1803 Update Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://os-tips.techidaily.com/quick-and-easy-tutorial-on-safeguarding-photographs-from-your-samsung-phone/"><u>Quick & Easy Tutorial on Safeguarding Photographs From Your Samsung Phone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-remedies-how-to-resolve-continuous-restarting-on-windows-11/"><u>Quick Remedies: How to Resolve Continuous Restarting on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issue-fixing-the-driver-failed-mistake-by-adjusting-user-preferences/"><u>Resolved Issue: Fixing the 'Driver Failed' Mistake by Adjusting User Preferences</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/review-of-dying-light-cooperative-first-person-and-parkour-action-in-a-zombie-apocalypse/"><u>Review of Dying Light - Cooperative, First-Person, and Parkour Action in a Zombie Apocalypse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-how-to-resolve-your-computer-stuck-during-windows-setup/"><u>Solutions: How to Resolve Your Computer Stuck During Windows Setup</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/stop-motion-mastery-the-top-5-online-tools/"><u>Stop Motion Mastery The Top 5 Online Tools</u></a></li>
<li><a href="https://solve-luxury.techidaily.com/troubleshooting-a-non-charging-laptop-expert-tips-from-yl-computing/"><u>Troubleshooting a Non-Charging Laptop: Expert Tips From YL Computing</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-snap-share-repeat-the-ultimate-ps4-screenshot-sharing-guide/"><u>Updated Snap, Share, Repeat The Ultimate PS4 Screenshot Sharing Guide</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

