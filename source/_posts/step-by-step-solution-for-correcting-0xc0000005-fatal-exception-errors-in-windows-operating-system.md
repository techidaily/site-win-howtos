---
title: Step-by-Step Solution for Correcting '0xC0000005' Fatal Exception Errors in Windows Operating System
date: 2024-08-28T00:22:29.512Z
updated: 2024-08-29T00:22:29.512Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for Correcting '0xC0000005' Fatal Exception Errors in Windows Operating System
excerpt: This Article Describes Step-by-Step Solution for Correcting '0xC0000005' Fatal Exception Errors in Windows Operating System
thumbnail: https://thmb.techidaily.com/f7daaa5e7a3a1ec4897e8ae51e5f1c3364a7e01e0179c0dfb3737d31036a1fde.jpg
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

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
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-elite-scripting-developing-a-countdown-mechanism-in-obs/"><u>[Updated] 2024 Approved  Elite Scripting  Developing a Countdown Mechanism in OBS</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-8-trendsetting-tools-that-every-startup-should-prioritize-today/"><u>[Updated] 8 Trendsetting Tools That Every Startup Should Prioritize Today</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-strategies-for-closing-down-a-forgotten-linkedin-profile/"><u>2024 Approved  Strategies for Closing Down a Forgotten LinkedIn Profile</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-infinix-hot-40-pro-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Infinix Hot 40 Pro to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-itel-p55t-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Itel P55T to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clearing-up-unreadable-text-in-windows-n-quick-troubleshooting-tips/"><u>Clearing Up Unreadable Text in Windows N - Quick Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/combat-svchostexes-extreme-cpu-drain-on-windows-11-effective-fixes-and-tips-unveiled/"><u>Combat svchost.exe's Extreme CPU Drain on Windows 11: Effective Fixes and Tips Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-svchostexe-netsvcs-how-to-address-network-resource-drain-and-improve-system-performance/"><u>Decoding svchost.exe (Netsvcs): How to Address Network Resource Drain and Improve System Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhanced-protection-settings-unlocking-your-file-downloading-capabilities-after-update/"><u>Enhanced Protection Settings: Unlocking Your File Downloading Capabilities After Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/feature-update-to-windows-11-version-1607-failed-to-install/"><u>Feature Update to Windows 11 Version 1607 Failed to Install</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/full-scale-examination-unboxing-the-dji-phantom-4/"><u>Full-Scale Examination  Unboxing the DJI Phantom 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hassle-free-methods-to-get-past-a-paused-0-windows-update-problem/"><u>Hassle-Free Methods to Get Past a Paused 0%% Windows Update Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-speaker-distortion-on-windows-11-and-7-solutions/"><u>How to Fix Speaker Distortion on Windows 11 and 7 - Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-vanishing-mouse-pointer-in-windows-10/"><u>How to Fix the Vanishing Mouse Pointer in Windows 10</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-honor-x8b-to-mac-drfone-by-drfone-android/"><u>How to Mirror Honor X8b to Mac? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-correct-error-code-0x80240017-in-your-windows-updates/"><u>How to Successfully Correct Error Code 0X80240017 in Your Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723200832245-local-safeguard-protocols-need-activation-action-steps-inside/"><u>Local Safeguard Protocols Need Activation – Action Steps Inside</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/obs-vs-shadowplay-which-to-choose-for-2024/"><u>OBS vs ShadowPlay - Which to Choose for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-resolving-steam-cant-write-to-disk-issues/"><u>Quick Solutions: Resolving 'Steam Can't Write to Disk' Issues</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-xiaomi-13t-pro-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Xiaomi 13T Pro Screen | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-access-denied-why-you-can-now-enter/"><u>Resolved: Access Denied – Why You Can Now Enter</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-a-disk-read-malfunction-on-your-windows-11-pc-proven-solutions/"><u>Resolving a Disk Read Malfunction on Your Windows 11 PC - Proven Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-connectivity-issues-for-your-xbox-one-gamepad-expert-advice/"><u>Resolving Connectivity Issues for Your Xbox One Gamepad: Expert Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-unregistered-class-errors-on-your-windows-10-pc-solutions-inside/"><u>Resolving Unregistered Class Errors on Your Windows 10 PC - Solutions Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-the-connection-effective-methods-to-rectify-a-non-functional-usb-port-on-an-hp-laptop/"><u>Revive the Connection: Effective Methods to Rectify a Non-Functional USB Port on an HP Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-implemented-correcting-uncooperative-keyboard-inputs/"><u>Solution Implemented: Correcting Uncooperative Keyboard Inputs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-for-the-common-vcruntime140dll-error-message-on-windows-computers/"><u>Solution Steps for the Common 'VCRUNTIME140.dll' Error Message on Windows Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-typing-troubles-fix-unresponsive-letter-keys-in-windows-10-and-11/"><u>Solve Your Typing Troubles: Fix Unresponsive Letter Keys in Windows 10 and 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-permanent-lag-on-valorants-launch-screen-steps-for-a-smooth-start/"><u>Solved! Permanent Lag on Valorant's Launch Screen: Steps for a Smooth Start</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-dilemma-of-your-unresponsive-corsair-keyboard-easily/"><u>Solving the Dilemma of Your Unresponsive Corsair Keyboard Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-installation-problems-with-audio-devices-on-windows-11/"><u>Step-by-Step Guide: Correcting Installation Problems with Audio Devices on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-restoring-lenovo-biometric-sensor-functionality/"><u>Step-by-Step Guide: Restoring Lenovo Biometric Sensor Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-windows-users-dealing-with-unresponsive-bluetooth-mice/"><u>Step-by-Step Solution for Windows Users Dealing With Unresponsive Bluetooth Mice</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-oppo-find-x7-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Oppo Find X7 ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/swift-resolution-guide-correcting-change-rendering-api-mistake-in-dota-2-error-202/"><u>Swift Resolution Guide: Correcting 'Change Rendering API' Mistake in Dota 2 (Error 202)</u></a></li>
<li><a href="https://games-able.techidaily.com/tricks-to-project-an-invisible-presence-in-steam/"><u>Tricks to Project an Invisible Presence in Steam</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-astro-a40-microphone-issues/"><u>Troubleshooting Guide: Fixing Astro A40 Microphone Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-invalid-registry-values-preventing-photos-access-in-windows-11/"><u>Troubleshooting Invalid Registry Values Preventing Photos Access in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tip-resolving-set-user-settings-to-driver-failed-mistake/"><u>Troubleshooting Tip: Resolving 'Set User Settings To Driver Failed' Mistake</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/ultimate-asmr-content-guides-for-2024/"><u>Ultimate ASMR Content Guides for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-12-5g-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi 12 5G Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->