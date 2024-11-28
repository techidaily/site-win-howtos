---
title: Troubleshooting PDF Printing Problems on Windows 11 Operating System
date: 2024-11-21T14:22:59.437Z
updated: 2024-11-27T18:43:24.636Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting PDF Printing Problems on Windows 11 Operating System
excerpt: This Article Describes Troubleshooting PDF Printing Problems on Windows 11 Operating System
thumbnail: https://thmb.techidaily.com/a3b5ab34eaf3f37a9a75db4fff942183c1ae755ba8565a3523ea779e463db4b2.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-videos.techidaily.com/new-broadcasting-wisdom-share-screen-seamlessly-on-fb-live-for-2024/"><u>[New] Broadcasting Wisdom Share Screen Seamlessly on FB Live for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-az-video-logger-full-application-scrutiny/"><u>[Updated] In 2024, AZ Video Logger - Full Application Scrutiny</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dhcp-connectivity-problems-understanding-and-solving-the-issue/"><u>DHCP Connectivity Problems – Understanding and Solving the Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-when-your-playstation-4-mic-stops-working-a-step-by-step-solution/"><u>Effective Fixes for When Your PlayStation 4 Mic Stops Working: A Step-by-Step Solution</u></a></li>
<li><a href="https://win-forum.techidaily.com/enabling-wake-on-lan-feature-on-windows-11-a-step-by-step-guide/"><u>Enabling Wake-on-LAN Feature on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-5-in-minecraft-easy-fixes-for-a-smooth-gaming-experience/"><u>Error Code 5 in Minecraft: Easy Fixes for a Smooth Gaming Experience</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-effortlessly-set-up-and-use-bluetooth-features-on-your-iphone/"><u>How to Effortlessly Set Up and Use Bluetooth Features on Your iPhone</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/ifind-data-restoration-expert-guide-on-retrieving-lost-information-from-your-hard-drive-with-ifind/"><u>IFind Data Restoration: Expert Guide on Retrieving Lost Information From Your Hard Drive with iFinD</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-youtube-profile-picture-templates-free-downloads/"><u>In 2024, YouTube Profile Picture Templates – Free Downloads!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-this-device-is-unavailable-error-code-24-on-windows-1087/"><u>Resolved: Fixing 'This Device Is Unavailable' Error Code 24 on Windows 10/8/7</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-poco-m6-pro-5g-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Poco M6 Pro 5G Phone Pattern Lock</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-17-unbeatable-cyber-monday-bargains-exclusive-offers-on-televisions-audio-gear-and-sound-systems-save-big-now/"><u>Top 17 Unbeatable Cyber Monday Bargains: Exclusive Offers on Televisions, Audio Gear & Sound Systems - Save Big Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-driver-failed-errors-in-user-setup-procedures/"><u>Troubleshooting and Fixing 'Driver Failed' Errors in User Setup Procedures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-solving-windows-10-and-7-ethernet-connectivity-problems/"><u>Troubleshooting Guide: Solving Windows 10 & 7 Ethernet Connectivity Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unshackle-your-console-stop-freeze-issues-now/"><u>Unshackle Your Console: Stop Freeze Issues Now</u></a></li>
</ul></div>

