---
title: "Step-by-Step Walkthrough: Correcting Error 0X80070490 During Windows Updates"
date: 2025-01-11T17:32:51.433Z
updated: 2025-01-13T16:11:07.441Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Walkthrough: Correcting Error 0X80070490 During Windows Updates"
excerpt: "This Article Describes Step-by-Step Walkthrough: Correcting Error 0X80070490 During Windows Updates"
thumbnail: https://thmb.techidaily.com/114b6bfca9f928095e8da2f7f3417492afac50bf37b6d4d36fe64b43b43e9aea.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-rise-and-shine-on-these-overlooked-meme-platforms/"><u>[New] Rise and Shine on These Overlooked Meme Platforms</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-comic-creators-charter-zero-cost-endless-laughs/"><u>[Updated] In 2024, Comic Creators' Charter Zero Cost, Endless Laughs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-eye-catching-youtube-most-followed-channels/"><u>[Updated] In 2024, Eye-Catching YouTube Most Followed Channels</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-video-anonymization-strategies/"><u>[Updated] Video Anonymization Strategies</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hide-and-stream-avoiding-the-spotlight-on-instagram/"><u>2024 Approved Hide and Stream Avoiding the Spotlight on Instagram</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-maintain-uninterrupted-youtube-experience-on-phones/"><u>2024 Approved Maintain Uninterrupted YouTube Experience on Phones</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effectively-managing-svchostexes-elevated-cpu-use-on-your-windows-10-device/"><u>Effectively Managing svchost.exe's Elevated CPU Use on Your Windows 10 Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fixes-for-improved-keyboard-responsiveness/"><u>Effortless Fixes for Improved Keyboard Responsiveness</u></a></li>
<li><a href="https://win-howtos.techidaily.com/high-efficiency-drivers-overcoming-wdfs-excessive-cpu-consumption/"><u>High-Efficiency Drivers: Overcoming WDF's Excessive CPU Consumption</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-crafting-unique-valorant-thumbnails-with-style-and-flair/"><u>In 2024, Crafting Unique Valorant Thumbnails with Style and Flair</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-user-profile-and-authentication-correcting-failures-in-windows-1011-logins/"><u>Mastering User Profile and Authentication: Correcting Failures in Windows 10/11 Logins</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-common-oculus-hardware-challenges/"><u>Overcoming Common Oculus Hardware Challenges</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-common-windows-11-hang-challenges-expert-advice/"><u>Overcoming Common Windows 11 Hang Challenges: Expert Advice</u></a></li>
</ul></div>

