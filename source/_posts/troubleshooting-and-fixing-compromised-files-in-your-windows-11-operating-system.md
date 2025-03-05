---
title: Troubleshooting and Fixing Compromised Files in Your Windows 11 Operating System
date: 2025-02-27T16:37:29.624Z
updated: 2025-03-05T16:55:38.662Z
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
<li><a href="https://extra-support.techidaily.com/new-mastering-pip-views-on-chrome-across-devices/"><u>[New] Mastering PIP Views on Chrome Across Devices</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-efficient-transfer-of-movie-maker-videos-to-vimeo/"><u>[Updated] In 2024, Efficient Transfer of Movie Maker Videos to Vimeo</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beating-the-booting-blues-fixing-your-computers-red-screen-issue/"><u>Beating the Booting Blues: Fixing Your Computer's Red Screen Issue</u></a></li>
<li><a href="https://discover-helper.techidaily.com/combining-multiple-mp4-clips-into-a-single-video-on-windows-step-by-step-tutorials-for-version-10-and-11/"><u>Combining Multiple MP4 Clips Into a Single Video on Windows: Step-by-Step Tutorials for Version 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-ways-to-enhance-your-keyboards-responsiveness/"><u>Effortless Ways to Enhance Your Keyboard's Responsiveness</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-persistent-pairing-errors-with-bluetooth-on-your-windows-10-pc-tips/"><u>How to Fix Persistent Pairing Errors with Bluetooth on Your Windows 10 PC - Tips</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-disabled-apple-iphone-6s-plus-how-to-unlock-a-disabled-apple-iphone-6s-plus-by-drfone-ios/"><u>In 2024, Disabled Apple iPhone 6s Plus How to Unlock a Disabled Apple iPhone 6s Plus?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-on-the-apple-iphone-14-plus-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock On the Apple iPhone 14 Plus Without Previous Owner?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-use-phone-clone-to-migrate-your-oppo-a78-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Use Phone Clone to Migrate Your Oppo A78 Data? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mkv-to-mp4-file-shift-in-windows-environment/"><u>Mastering MKV to MP4 File Shift in Windows Environment</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/methods-for-subtle-volume-reduction-in-fl-studio/"><u>Methods for Subtle Volume Reduction in FL Studio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-interruptions-easily-resolve-your-csgo-crash-issues/"><u>No More Interruptions: Easily Resolve Your CSGO Crash Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-steps-for-enabling-hosted-networks-in-windows-11/"><u>Resolved: Troubleshooting Steps for Enabling Hosted Networks in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-connectivity-issues-a-fix-for-hp-laptops-with-defective-usb-slots/"><u>Resolving Connectivity Issues: A Fix for HP Laptops with Defective USB Slots</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-problems-whenever-you-encounter-an-hiccup-on-steam-games-updateinstall/"><u>Resolving Problems Whenever You Encounter an Hiccup on Steam Games Update/Install</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-resolving-windows-update-error-0x80n0490-code-successfully/"><u>Troubleshooting Tips for Resolving Windows Update Error 0X80n0490 Code Successfully</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/troubleshooting-why-arent-your-recommended-fb-videos-displayed/"><u>Troubleshooting Why Aren't Your Recommended FB Videos Displayed?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-fix-a-non-functioning-backspace-key/"><u>Troubleshooting: How to Fix a Non-Functioning Backspace Key</u></a></li>
<li><a href="https://extra-hints.techidaily.com/vanguard-wearables-for-sporting-captures/"><u>Vanguard Wearables for Sporting Captures</u></a></li>
</ul></div>

