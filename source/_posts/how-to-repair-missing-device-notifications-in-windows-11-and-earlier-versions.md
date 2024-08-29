---
title: How to Repair Missing Device Notifications in Windows 11 and Earlier Versions
date: 2024-08-28T00:38:20.649Z
updated: 2024-08-29T00:38:20.649Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Repair Missing Device Notifications in Windows 11 and Earlier Versions
excerpt: This Article Describes How to Repair Missing Device Notifications in Windows 11 and Earlier Versions
thumbnail: https://thmb.techidaily.com/9f23cf12f736b9e556e25d78842b81c2a897e31ac3cc784dccd607926f3ba0ca.jpg
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
<li><a href="https://screen-recording.techidaily.com/new-advanced-mac-photo-tips-5-efficient-snapshot-techniques-for-2024/"><u>[New] Advanced Mac Photo Tips  5 Efficient Snapshot Techniques for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-claim-the-crown-strategies-for-staff-picked-videos-at-vimeo/"><u>[New] Claim the Crown  Strategies for Staff-Picked Videos at Vimeo</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleashing-time-management-mastery-with-zero-cost-clocks/"><u>[Updated] Unleashing Time Management Mastery with Zero Cost Clocks</u></a></li>
<li><a href="https://tech-revival.techidaily.com/0x80248007-error-in-windows-update-in-windows-10-solved/"><u>0X80248007 Error in Windows Update in Windows 10 [Solved]</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/advanced-guide-to-mastering-the-art-of-morphvox-audio-transformation-for-2024/"><u>Advanced Guide to Mastering the Art of MorphVOX Audio Transformation for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/coding-excellence-with-chatgpt-and-vs-code-synergy/"><u>Coding Excellence with ChatGPT & VS Code Synergy</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-nokia-c12-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on Nokia C12.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-guide-to-overcome-initializing-issues-in-destiny-2/"><u>Complete Guide to Overcome Initializing Issues in Destiny 2</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-svchostexe-netsvcs-how-to-fix-excessive-bandwidth-usage-and-improve-your-pcs-efficiency/"><u>Decoding svchost.exe (NETsvcs) - How to Fix Excessive Bandwidth Usage & Improve Your PC's Efficiency</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-mending-broken-operating-system-files-in-windows-10-and-11/"><u>Diagnosing and Mending Broken Operating System Files in Windows 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/end-crackling-audio-from-computer-speakers-effective-techniques-for-windows-users/"><u>End Crackling Audio From Computer Speakers: Effective Techniques for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-track-guide-to-fixing-errors-in-directx-setup-processes-effortlessly/"><u>Fast Track Guide to Fixing Errors in DirectX Setup Processes Effortlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/file-explorer-tricks-for-windows-11-users-quick-help-and-easy-fixes/"><u>File Explorer Tricks for Windows 11 Users - Quick Help & Easy Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-applicationexe-has-stopped-error-a-complete-guide/"><u>Fixing 'Application.exe Has Stopped' Error – A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-high-disk-utilization-by-microsoft-compatibility-telemetry-on-windows-11/"><u>How to Fix High Disk Utilization by Microsoft Compatibility Telemetry on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-when-your-hp-laptops-mouse-pad-wont-work/"><u>How to Fix When Your HP Laptop's Mouse Pad Won't Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-werfaultexe-malfunction-a-step-by-step-guide/"><u>How to Fix Windows werFault.exe Malfunction: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-seamlessly-update-your-microsoft-device-drivers-for-windows-11-8-or-7-users/"><u>How to Seamlessly Update Your Microsoft Device Drivers for Windows 11, 8, or 7 Users</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oneplus-open-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock OnePlus Open Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-htc-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass HTC FRP Without Computer</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-strategic-instagram-video-marketing-secrets-to-captivating-audiences/"><u>In 2024, Strategic Instagram Video Marketing  Secrets to Captivating Audiences</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-game-dev-challenges-fixing-pixel-format-not-accelerated-in-lwjgl-environment/"><u>Mastering Game Dev Challenges: Fixing 'Pixel Format Not Accelerated' In LWjGL Environment</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectified-stretched-screens-on-windows-os/"><u>Rectified Stretched Screens on Windows OS</u></a></li>
<li><a href="https://driver-install.techidaily.com/rejuvenate-mouse-operation-on-winx-10-and-11/"><u>Rejuvenate Mouse Operation on WINX, 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-cannot-start-hardware-device-error-due-to-damaged-registry-configuration-code-19/"><u>Resolving 'Windows 11 Cannot Start Hardware Device' Error Due to Damaged Registry Configuration - Code 19</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-trackpad-effective-fixes-for-windows-11-8-and-7-not-working-scenarios/"><u>Revive Your Trackpad: Effective Fixes for Windows 11, 8 & 7 Not Working Scenarios</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guided-overcoming-laptop-keyboard-issues-at-logon/"><u>Solution Guided: Overcoming Laptop Keyboard Issues at Logon</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-microsoft-wireless-adapter-connectivity-error-in-windows-10-environments/"><u>Step-by-Step Solutions for Microsoft Wireless Adapter Connectivity Error in Windows 10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-mpengineexe-from-hogging-your-cpu-resources-a-winning-strategy-for-windows-11-users/"><u>Stop MPengine.exe From Hogging Your CPU Resources: A Winning Strategy for Windows 11 Users</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ltimate-guide-to-live-recording-best-15-video-resources/"><u>The Ultimate Guide to Live Recording - Best 15 Video Resources</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-the-limitations-of-non-hdcp-certified-displays/"><u>Understanding the Limitations of Non-HDCP Certified Displays</u></a></li>
<li><a href="https://facebook.techidaily.com/understanding-the-ramifications-of-facebooks-oculus-go-decision/"><u>Understanding the Ramifications of Facebook's Oculus Go Decision</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-computer-during-windows-installation-professional-fixes-and-tips/"><u>Unstick Your Computer During Windows Installation: Professional Fixes and Tips</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-make-an-impression-top-video-invitation-tools-for-ios-and-android/"><u>Updated 2024 Approved Make an Impression Top Video Invitation Tools for iOS and Android</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-svchostexes-heavy-load-on-windows-11-solution/"><u>Winning the Battle Against Svchost.exe's Heavy Load on Windows 11 [Solution]</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->