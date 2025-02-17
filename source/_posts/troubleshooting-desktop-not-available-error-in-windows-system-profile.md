---
title: Troubleshooting 'Desktop Not Available' Error in Windows System Profile
date: 2025-02-15T20:07:33.638Z
updated: 2025-02-16T18:27:30.212Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting 'Desktop Not Available' Error in Windows System Profile
excerpt: This Article Describes Troubleshooting 'Desktop Not Available' Error in Windows System Profile
thumbnail: https://thmb.techidaily.com/a6ef7d238dd7bb214a3984e4799089ad86b5e4b6f433cd32ec9f580258b7206c.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-data.techidaily.com/n-2024-5-best-youtube-video-marketing-strategies/"><u>[New] In 2024, 5 Best YouTube Video Marketing Strategies</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-crafting-a-perfect-paradise-the-top-stardew-valley-mods-7-14/"><u>[Updated] Crafting a Perfect Paradise The Top Stardew Valley Mods (#7-14)</u></a></li>
<li><a href="https://common-error.techidaily.com/addressed-wdf-concerns-strategies-for-reducing-high-resource-demands-on-windows-operating-systems/"><u>Addressed WDF Concerns - Strategies for Reducing High Resource Demands on Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeat-pc-game-lag-in-oddworld-soulstorm-with-these-proven-troubleshooting-steps/"><u>Defeat PC Game Lag in Oddworld: Soulstorm with These Proven Troubleshooting Steps!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-fixes-eradicating-unwanted-lines-from-computer-visuals/"><u>DIY Fixes: Eradicating Unwanted Lines From Computer Visuals</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-unsupported-input-detected-on-display-screen/"><u>Error: Unsupported Input Detected on Display Screen</u></a></li>
<li><a href="https://win-able.techidaily.com/fix-your-sluggish-firefox-8-proven-strategies-for-enhanced-performance/"><u>Fix Your Sluggish Firefox: 8 Proven Strategies for Enhanced Performance</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/outstanding-graphic-revisions-for-2024/"><u>Outstanding Graphic Revisions for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/sealoc-55-inch-4k-outdoor-tv-a-comprehensive-review-and-guide/"><u>Sealoc 55-Inch 4K Outdoor TV: A Comprehensive Review and Guide.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-occurred-while-resetting-issue-in-windows-11-a-comprehensive-guide/"><u>Solving the 'Problem Occurred While Resetting' Issue in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fix-boot-problems-with-windows-getting-ready/"><u>Step-by-Step Guide to Fix Boot Problems with 'Windows Getting Ready'</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-samsung-galaxy-z-flip-5-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Samsung Galaxy Z Flip 5 Android SIM Unlock APK</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transformative-tiktok-video-techniques-that-work-for-2024/"><u>Transformative TikTok Video Techniques That Work for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixing-platform-not-supported-error-on-intel-serial-io-driver-installation/"><u>Troubleshooting: Fixing 'Platform Not Supported' Error on Intel Serial IO Driver Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/upping-the-ante-in-digital-playgrounds-advanced-techniques-for-faster-smoother-games-on-windows-11/"><u>Upping the Ante in Digital Playgrounds: Advanced Techniques for Faster, Smoother Games on Windows 11</u></a></li>
</ul></div>

