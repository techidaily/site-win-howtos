---
title: "Troubleshooting and Solving Hang-Ups in Windows 11 Systems: A Comprehensive Guide"
date: 2024-09-05T10:16:13.113Z
updated: 2024-09-06T10:16:13.113Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting and Solving Hang-Ups in Windows 11 Systems: A Comprehensive Guide"
excerpt: "This Article Describes Troubleshooting and Solving Hang-Ups in Windows 11 Systems: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/0656fd665c6180b1a80265c93dba7068c3a0cbd851c23bc5b8909b9f9daa190b.jpg
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
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5\. Then select**Advanced options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff3f6500f3.jpg)
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-seamless-podcast-experience-for-iphone-users/"><u>[Updated] 2024 Approved  Seamless Podcast Experience for iPhone Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-50plus-best-text-techniques-in-film-making/"><u>[Updated] 50+ Best Text Techniques in Film-Making</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209817150-beat-error-0x800f0922-in-windows-10-updates-with-these-proven-fixes/"><u>Beat Error 0X800f0922 in Windows 10 Updates with These Proven Fixes</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/boost-your-sites-traffic-with-customized-analytics-smart-solutions-from-cookiebot/"><u>Boost Your Site's Traffic with Customized Analytics: Smart Solutions From Cookiebot</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-windows-system-faults-addressing-the-device-unavailable-issue-code-24/"><u>Diagnosing and Fixing Windows System Faults - Addressing the Device Unavailable Issue (Code 24)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-and-tips-for-resolving-wacom-drawing-pad-issues/"><u>Effective Fixes and Tips for Resolving Wacom Drawing Pad Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-managing-microsofts-compatibility-telemetry-and-saving-storage-in-windows-11/"><u>Effective Solutions for Managing Microsoft's Compatibility Telemetry and Saving Storage in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-steps-to-resolve-your-csgo-game-crashes-fast/"><u>Effortless Steps to Resolve Your CSGO Game Crashes Fast</u></a></li>
<li><a href="https://video-capture.techidaily.com/expert-advice-on-iphone-7-display-recording-for-2024/"><u>Expert Advice on iPhone 7 Display Recording for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-restoring-functionality-to-a-malfunctioning-lenovo-keyboard/"><u>Expert Advice on Restoring Functionality to a Malfunctioning Lenovo Keyboard</u></a></li>
<li><a href="https://extra-hints.techidaily.com/expert-routines-for-volume-balancing-in-fl-studio/"><u>Expert Routines for Volume Balancing in FL Studio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-overcoming-windows-could-not-install-fast-fixes-and-hacks/"><u>Expert Tips For Overcoming 'Windows Could Not Install': Fast Fixes & Hacks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-unresponsive-touchscreen-in-windows-11-a-step-by-step-guide-to-5-solutions/"><u>Fix Your Unresponsive Touchscreen in Windows 11 - A Step-by-Step Guide to 5 Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-and-eliminate-the-infamous-red-screen-error-on-your-new-windows-11-pc/"><u>How to Fix and Eliminate the Infamous Red Screen Error on Your New Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-patch-your-system-fixing-the-windows-10-0x80nf0922-setback/"><u>How To Successfully Patch Your System: Fixing The Windows 10 0X80nf0922 Setback</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-oneplus-nord-ce-3-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to OnePlus Nord CE 3 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/instant-remedy-steps-to-fix-detected-no-power-source-error/"><u>Instant Remedy Steps to Fix 'Detected No Power Source' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-mousepad-problems-solved-tips-for-restoring-functionality-on-windows-platforms/"><u>Laptop Mousepad Problems Solved! Tips for Restoring Functionality on Windows Platforms</u></a></li>
<li><a href="https://win-howtos.techidaily.com/league-of-legends-boost-trick-get-your-game-running-faster-now/"><u>League of Legends Boost Trick - Get Your Game Running Faster Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-recovery-techniques-utilizing-sfc-and-dism-in-windows-11-repairs/"><u>Mastering Recovery Techniques: Utilizing SFC and DISM in Windows 11 Repairs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-10-updates-a-comprehensive-guide-to-fixing-the-0x800705b4-error-for-good/"><u>Mastering Windows 10 Updates: A Comprehensive Guide to Fixing the 0X800705b4 Error for Good</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-high-graphics-load-from-desktop-window-manager-on-windows-tips-for-win10-and-win11/"><u>Overcoming High Graphics Load From Desktop Window Manager on Windows: Tips for Win10 & Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-msvcr71-absence/"><u>Overcoming MSVCR71 Absence</u></a></li>
<li><a href="https://extra-resources.techidaily.com/quadcopter-mechanics-decoded-flight-patterns-and-functionality/"><u>Quadcopter Mechanics Decoded  Flight Patterns & Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-resolutions-for-rapid-cs-go-software-failures/"><u>Quick Resolutions for Rapid CS: GO Software Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-with-shutting-down-windows-11-on-your-computer-effective-fixes/"><u>Resolving Issues with Shutting Down Windows 11 on Your Computer – Effective Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-random-shutdown-malfunctions-in-computers-proven-fixes-inside/"><u>Resolving Random Shutdown Malfunctions in Computers - Proven Fixes Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-dell-bluetooth-mouse-how-to-fix-connection-issues/"><u>Reviving Your Dell Bluetooth Mouse: How To Fix Connection Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-laptop-microphone-proven-fixes-to-get-it-back-on-track/"><u>Reviving Your Laptop Microphone: Proven Fixes to Get It Back on Track</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-fixes-to-get-your-usb-flash-drive-working-again/"><u>Simple Fixes to Get Your USB Flash Drive Working Again</u></a></li>
<li><a href="https://hardware-help.techidaily.com/smarter-longer-lasting-computing-qualcomms-snapdragon-chips-double-dell-xps-13-plus-laptop-battery-efficiency-while-halving-costs-over-intel-counterparts/"><u>Smarter, Longer-Lasting Computing: Qualcomm’s Snapdragon Chips Double Dell XPS 13 Plus Laptop Battery Efficiency While Halving Costs Over Intel Counterparts</u></a></li>
<li><a href="https://youtube-data.techidaily.com/h-sound-transformation-essential-ios-apps-to-convert-youtube-mp3-wise-for-2024/"><u>Smooth Sound Transformation  Essential iOS Apps to Convert YouTube MP3-Wise for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-error-in-writing-to-the-0x-referenced-memory-location/"><u>Solution Found: Error in Writing to the 0X Referenced Memory Location</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-issues-with-your-hp-laptops-camera-in-windows-10-a-step-by-step-guide/"><u>Solving Issues with Your HP Laptop's Camera in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fix-unresponsive-external-devices-in-windows/"><u>Step-by-Step Guide to Fix Unresponsive External Devices in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-windows-11-and-the-non-pairing-bluetooth-device-problem-of-2024/"><u>Step-by-Step Solutions for Windows 11 and the Non-Pairing Bluetooth Device Problem of 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/success-story-overcoming-microsoft-wireless-display-adapter-connection-hurdles-on-windows-10/"><u>Success Story: Overcoming Microsoft Wireless Display Adapter Connection Hurdles on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tap-typers-take-heart/"><u>Tap Typers, Take Heart</u></a></li>
<li><a href="https://win-howtos.techidaily.com/touchpad-problems-heres-how-you-can-restore-functionality/"><u>Touchpad Problems? Here's How You Can Restore Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-repair-unresponsive-external-mouse-connectivity-with-this-guide/"><u>Troubleshoot and Repair Unresponsive External Mouse Connectivity with This Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-unresponsive-usb-keyboard-and-mouse-on-windows-7/"><u>Troubleshooting & Fixing: Unresponsive USB Keyboard & Mouse on Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-the-0x80072efd-error-on-windows-10/"><u>Troubleshooting Guide: Resolving the 0X80072EFD Error on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-registered-classes-in-windows-10-easy-steps-for-a-smooth-solution/"><u>Troubleshooting Non-Registered Classes in Windows 10 – Easy Steps for a Smooth Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-10-fixing-unresponsive-touchpad-scroll-issues/"><u>Troubleshooting Windows 10: Fixing Unresponsive Touchpad Scroll Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-successful-implementation-after-failed-d3d-device-instantiation/"><u>Troubleshooting: Successful Implementation After Failed D3D Device Instantiation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-fixing-errconnectionrefused-errors-a-picture-perfect-guide/"><u>Understanding and Fixing ERR_CONNECTION_REFUSED Errors – A Picture-Perfect Guide</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/sh-potential-deciding-between-studio-and-beta-version/"><u>Unleash Potential  Deciding Between Studio and Beta Version</u></a></li>
</ul></div>
