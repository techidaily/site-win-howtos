---
title: Diagnosing and Resolving USB Port Failures in Windows 10 & 11 Computers Efficiently
date: 2025-01-14T16:14:45.099Z
updated: 2025-01-19T20:08:35.738Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Resolving USB Port Failures in Windows 10 & 11 Computers Efficiently
excerpt: This Article Describes Diagnosing and Resolving USB Port Failures in Windows 10 & 11 Computers Efficiently
thumbnail: https://thmb.techidaily.com/97308f979ef9767cdb33e037debbc9d1c528c201fc8946139de7109bd3d44499.jpg
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  
5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-the-compreeved-list-of-non-bandicamp-capture-software-on-mac/"><u>[New] 2024 Approved The Compreeved List of Non-Bandicamp Capture Software on Mac</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-vlogs-to-virality-jake-paul-the-online-phenomenon-for-2024/"><u>[Updated] From Vlogs to Virality Jake Paul, the Online Phenomenon for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-troubleshooting-restoring-device-recognition-capabilities-on-windows-nt/"><u>Bluetooth Troubleshooting: Restoring Device Recognition Capabilities on Windows nT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-and-repair-addressing-the-lenovo-function-key-issues-effectively/"><u>Bypass and Repair: Addressing the Lenovo Function Key Issues Effectively</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-motorola-razr-40-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-high-disk-usage-caused-by-microsoft-compatibility-telemetry-on-windows-10-computers/"><u>How to Fix High Disk Usage Caused by Microsoft Compatibility Telemetry on Windows 10 Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-audio-error-0xc00d36b4-in-windows-10-and-11/"><u>How to Fix the Audio Error 0Xc00d36b4 in Windows 10 & 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-solution-overcoming-initializing-delays-in-destiny-2-gaming-experience/"><u>Master the Solution: Overcoming 'Initializing' Delays in Destiny 2 Gaming Experience</u></a></li>
<li><a href="https://program-issues.techidaily.com/mastering-lag-free-gaming-on-pc-essential-fixes-and-optimization-tactics/"><u>Mastering Lag-Free Gaming on PC : Essential Fixes & Optimization Tactics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-quick-fixes-for-critical-cxfreeze-software-crashes/"><u>Resolved: Quick Fixes for Critical Cx_Freeze Software Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-dilemma-effective-solutions-for-persistent-mouse-disconnection-issues/"><u>Solving the Dilemma: Effective Solutions for Persistent Mouse Disconnection Issues</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-4-fantastic-no-cost-web-based-calendar-apps/"><u>Top 4 Fantastic No-Cost Web-Based Calendar Apps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-non-functional-windows-key-issues-on-windows-10/"><u>Troubleshooting Guide: Resolving Non-Functional Windows Key Issues on Windows 10</u></a></li>
<li><a href="https://fox-pages.techidaily.com/windows-regional-configuration-tips-and-tricks-by-yl-software-for-optimal-user-experience/"><u>Windows Regional Configuration Tips and Tricks by YL Software for Optimal User Experience</u></a></li>
</ul></div>

