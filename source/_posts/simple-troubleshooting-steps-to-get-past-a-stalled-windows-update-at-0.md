---
title: Simple Troubleshooting Steps to Get Past a Stalled Windows Update at 0%%
date: 2024-08-19T07:09:56.907Z
updated: 2024-08-20T07:09:56.907Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Simple Troubleshooting Steps to Get Past a Stalled Windows Update at 0%%
excerpt: This Article Describes Simple Troubleshooting Steps to Get Past a Stalled Windows Update at 0%%
thumbnail: https://thmb.techidaily.com/69b1d610dfac71b4ad43b5c58d93dcc4f9582f39ed2f8ffdd69954aaaa5a12ae.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-video-capture.techidaily.com/new-record-everything-pay-nothing-screen-tools-for-all-users/"><u>[New] Record Everything, Pay Nothing - Screen Tools for All Users</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-smilesketcher-easy-to-use-digital-comedy-tool/"><u>[New] SmileSketcher  Easy-to-Use Digital Comedy Tool</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206100989-solved-airdrop-not-working-quickly-and-easily/"><u>[SOLVED] AirDrop Not Working | Quickly & Easily.</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-prime-stabilization-techniques-for-youtubers/"><u>[Updated] 2024 Approved  Prime Stabilization Techniques for YouTubers</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-pro-tips-for-sub4sub-beginners-review-our-complete-guide/"><u>2024 Approved  Pro Tips for Sub4sub Beginners - Review Our Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209511095-boot-loop-blues-quick-tips-to-unstick-your-pc-from-boot-screen-deadlock/"><u>Boot Loop Blues? Quick Tips to Unstick Your PC From Boot Screen Deadlock</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquering-new-world-effective-solutions-to-the-frustrating-easy-anti-cheat-launch-error/"><u>Conquering New World: Effective Solutions to the Frustrating Easy Anti-Cheat Launch Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoded-troubleshooting-failed-writes-to-0x-pointed-out-memory-slot-0x/"><u>Decoded: Troubleshooting Failed Writes to 0X Pointed-Out Memory Slot (0X)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-intelligence-easy-setup-of-intels-ac-7260-dual-band-wireless-driver/"><u>Download Intelligence: Easy Setup of Intel's AC 7260 Dual Band Wireless Driver</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-resolving-a-malfunctioning-usb-hdmi-adapter/"><u>Expert Tips on Resolving a Malfunctioning USB-HDMI Adapter</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-rectifying-audio-device-not-found-in-microsoft-operating-systems/"><u>Guide to Rectifying 'Audio Device Not Found' In Microsoft Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-reactivate-a-non-functional-diagnostic-policy-service-solved/"><u>How to Reactivate a Non-Functional Diagnostic Policy Service (Solved)</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-designcut-pro/"><u>In 2024, DesignCut Pro</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-mastering-simple-multi-snap-chat-video-creation-and-editing/"><u>In 2024, Mastering Simple Multi-Snap Chat Video Creation & Editing</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-perfecting-your-screen-recording-during-games/"><u>In 2024, Perfecting Your Screen Recording During Games</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-the-ultimate-guide-to-downloading-facebook-stories-anywhere/"><u>In 2024, The Ultimate Guide to Downloading Facebook Stories Anywhere</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-illumination-restoration-tips-for-mac-and-windows-users/"><u>Keyboard Illumination Restoration Tips for Mac and Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-issues-at-login-how-to-restore-functionality/"><u>Keyboard Issues at Login – How to Restore Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-fix-for-your-vanished-steam-library-privileges-detailed-tutorial-inside/"><u>Master the Fix for Your Vanished Steam Library Privileges - Detailed Tutorial Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/personalized-configuration-options-not-loading-correctly-solutions/"><u>Personalized Configuration Options Not Loading Correctly - Solutions</u></a></li>
<li><a href="https://fox-helps.techidaily.com/precision-cuts-and-transitions-for-premier-users/"><u>Precision Cuts & Transitions for Premier Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-for-when-your-usb-mouse-wont-connect-to-your-pc-fix-guide/"><u>Solutions for When Your USB Mouse Won't Connect to Your PC – Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-how-to-fix-unintended-characters-on-your-keyboard/"><u>Solved: How to Fix Unintended Characters on Your Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-cod-addressing-and-correcting-the-wwii-game-bug-error-4220/"><u>Troubleshooting Cod: Addressing and Correcting the WWII Game Bug (Error 4220)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-elevation-requests-in-windows-fixes-for-win11-win10-and-win7-error-messages/"><u>Troubleshooting Elevation Requests in Windows: Fixes for Win11, Win10 & Win7 Error Messages</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-the-keyboard-backspace-issue/"><u>Troubleshooting Guide: Fixing the Keyboard Backspace Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-repairing-your-mouse-when-the-left-click-fails/"><u>Troubleshooting Guide: Repairing Your Mouse When the Left-Click Fails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-1n-11s-0x800f0922-update-error-step-by-step-guide/"><u>Troubleshooting Windows 1N 11'S 0X800f0922 Update Error: Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-does-your-windows-11-pc-boot-alone-exploring-possible-causes-and-solutions/"><u>Why Does Your Windows 11 PC Boot Alone? Exploring Possible Causes and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-copy-paste-malfunction-heres-how-to-restore-it/"><u>Windows 11 Copy-Paste Malfunction? Here's How to Restore It</u></a></li>
</ul></div>
