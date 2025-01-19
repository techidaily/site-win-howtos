---
title: How to Fix Windows 11 'System Restore Failed' Error (Error 0X80070091) - Complete Solution
date: 2025-01-12T16:49:13.438Z
updated: 2025-01-19T19:26:35.314Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Windows 11 'System Restore Failed' Error (Error 0X80070091) - Complete Solution
excerpt: This Article Describes How to Fix Windows 11 'System Restore Failed' Error (Error 0X80070091) - Complete Solution
thumbnail: https://thmb.techidaily.com/6f8c62fe2349a0f207bb9e67da92ccbc024b72458dedec8efed25d3d7ef6c0d1.png
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-glue.techidaily.com/new-in-2024-introduction-to-effective-telegram-promotion-for-rookies/"><u>[New] In 2024, Introduction to Effective Telegram Promotion for Rookies</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-x-media-converter-desktop-application/"><u>[New] In 2024, X-Media Converter Desktop Application</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-discord-mic-not-working/"><u>[Solved] Discord Mic Not Working</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-mastering-fpv-drones-picking-perfect-propellers/"><u>[Updated] 2024 Approved Mastering FPV Drones Picking Perfect Propellers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-incremental-introduction/"><u>[Updated] Incremental Introduction</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-reimagining-time-flow-a-thorough-2024-app-review/"><u>[Updated] Reimagining Time Flow A Thorough 2024 App Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-boot-issues-expert-advice-to-get-you-up-and-running-again/"><u>Beat Boot Issues: Expert Advice to Get You Up and Running Again</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/or-mirrorless-for-high-quality-video-recording-in-2024/"><u>DSLR or Mirrorless for High-Quality Video Recording, In 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/halo-4-fatal-system-crash-on-unreal-engine-4-here-are-your-ultimate-solutions/"><u>Halo 4 Fatal System Crash on Unreal Engine 4? Here Are Your Ultimate Solutions</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-hevc-h-265-files-on-redmi-k70e-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How do you play HEVC/H.265 files on Redmi K70E?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-malfunctioning-keyboard-light-on-windows-and-macos-devices/"><u>How to Fix Malfunctioning Keyboard Light on Windows and macOS Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-fix-overcoming-no-battery-detected-issues-swiftly/"><u>Immediate Fix: Overcoming 'No Battery Detected' Issues Swiftly</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-lava-blaze-2-pro-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Lava Blaze 2 Pro to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/musks-mystery-the-future-of-gpt-revealed/"><u>Musk's Mystery: The Future of GPT Revealed?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-non-upgradable-problems-for-smooth-operation/"><u>Resolving Windows 11 Non-Upgradable Problems for Smooth Operation</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/snap-into-fb-shorts-saga-for-2024/"><u>Snap Into FB Shorts Saga for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-addressing-problems-when-your-computer-cant-communicate-with-the-system-events-service/"><u>Solved: Addressing Problems When Your Computer Can't Communicate With the System Events Service</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-operation-prompts-easily-navigate-administrator-privileges-on-your-computers-operating-system/"><u>Solving Operation Prompts: Easily Navigate Administrator Privileges on Your Computer's Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-windows-update-error-0x802e200d-successfully-diy/"><u>Troubleshooting and Resolving Windows Update Error 0X802e200d Successfully [DIY]</u></a></li>
</ul></div>

