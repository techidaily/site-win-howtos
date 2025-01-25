---
title: Step-by-Step Solution for Correcting '0xC0000005' Fatal Exception Errors in Windows Operating System
date: 2025-01-24T16:45:38.893Z
updated: 2025-01-25T18:37:28.577Z
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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-blue.techidaily.com/new-3dr-navigating-the-single-user-realm-of-3d-tech/"><u>[New] '3DR' Navigating the Single User Realm of 3D Tech</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-the-ultimate-comparison-top-screen-recorders-focusing-on-recmeister-for-2024/"><u>[New] The Ultimate Comparison Top Screen Recorders, Focusing on Recmeister for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-humor-at-your-fingertips-complimentary-toolset-for-2024/"><u>[Updated] Humor at Your Fingertips - Complimentary Toolset for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-the-ultimate-strategy-for-high-quality-remote-recordings/"><u>2024 Approved The Ultimate Strategy for High-Quality Remote Recordings</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-look-at-the-samsung-galaxy-z-fold4-top-tier-specs-with-a-touch-of-nostalgia/"><u>In-Depth Look at the Samsung Galaxy Z Fold4: Top-Tier Specs with a Touch of Nostalgia</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-based-itunes-freeze-problems/"><u>Overcoming Windows-Based iTunes Freeze Problems</u></a></li>
<li><a href="https://win-solutions.techidaily.com/quick-guide-how-to-terminate-a-frozen-application-in-windows-10/"><u>Quick Guide: How to Terminate a Frozen Application in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-opening-and-watching-mkv-movies-on-your-apple-device/"><u>Step-by-Step Guide: Opening & Watching MKV Movies on Your Apple Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-transferring-your-dvd-content-to-an-external-hard-drive/"><u>Step-by-Step Guide: Transferring Your DVD Content to an External Hard Drive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-on-bulk-transformation-of-m2p-footage-to-high-quality-mp4-files/"><u>Step-by-Step Tutorial on Bulk Transformation of M2P Footage to High-Quality MP4 Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-on-file-importation-techniques-for-optimal-performance/"><u>Step-by-Step Tutorial on File Importation Techniques for Optimal Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-on-how-to-transform-blu-rays-to-mp4-without-costs/"><u>Step-by-Step Tutorial on How to Transform Blu-Rays to MP4 Without Costs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-on-moving-dvd-media-files-to-a-portable-tablet/"><u>Step-by-Step Tutorial on Moving DVD Media Files to a Portable Tablet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-using-the-iso-ripper-software-for-effortless-dvd-iso-extraction-and-multi-format-file-conversion/"><u>Step-by-Step Tutorial: Using the ISO Ripper Software for Effortless DVD ISO Extraction and Multi-Format File Conversion</u></a></li>
<li><a href="https://win-help.techidaily.com/story-2-misconceptions-about-grounding-in-high-interference-areas-answer-c/"><u>Story 2: Misconceptions About Grounding in High Interference Areas (Answer C)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-list-of-top-rated-free-tools-for-dividing-your-videos-into-sections/"><u>The Ultimate List of Top-Rated Free Tools for Dividing Your Videos Into Sections</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Honor Magic5 Ultimate | Dr.fone</u></a></li>
</ul></div>

