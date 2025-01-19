---
title: "Troubleshooting: C:\\Windows\\System32\\Config\\SystemProfile\\Desktop Error Explained"
date: 2025-01-16T17:40:54.511Z
updated: 2025-01-19T16:41:44.563Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: C:\\Windows\\System32\\Config\\SystemProfile\\Desktop Error Explained"
excerpt: "This Article Describes Troubleshooting: C:\\Windows\\System32\\Config\\SystemProfile\\Desktop Error Explained"
thumbnail: https://thmb.techidaily.com/402a192fa8f9a76c25001597879db6a11d907dc8fe3db6a194aec02ff3403057.jpg
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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-posts.techidaily.com/new-in-2024-64gb-ideal-for-light-video-content/"><u>[New] In 2024, 64Gb Ideal for Light Video Content?</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-the-essential-guide-to-expanding-your-tiktok-reach-and-interactions/"><u>[New] In 2024, The Essential Guide to Expanding Your TikTok Reach & Interactions</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-power-of-precision-crafting-effective-video-titles/"><u>[Updated] The Power of Precision Crafting Effective Video Titles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-step-by-step-solution-resolving-issues-with-your-xbox-one-controller-guide/"><u>Complete Step-by-Step Solution: Resolving Issues with Your Xbox One Controller (Guide)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeating-the-frozen-screen-strategies-to-revive-your-computer/"><u>Defeating the Frozen Screen: Strategies to Revive Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fixes-for-dxgi-device-hung-errors-quick-solutions-and-tips/"><u>Effortless Fixes for DXGI Device Hung Errors: Quick Solutions & Tips</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-analysis-of-the-asus-b76n-csm-motherboard-how-its-csm-status-elevates-performance/"><u>Expert Analysis of the Asus B76n-CSM Motherboard: How Its CSM Status Elevates Performance</u></a></li>
<li><a href="https://technical-tips.techidaily.com/overcome-your-windows-11-hurdle-effective-fixes-for-the-sleep-feature-glitch/"><u>Overcome Your Windows 11 Hurdle: Effective Fixes for the Sleep Feature Glitch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-syncing-hurdles-for-your-xbox-one-controller-a-comprehensive-guide/"><u>Overcoming Syncing Hurdles for Your Xbox One Controller - A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/proper-techniques-for-cleaning-slate-displays-without-damage/"><u>Proper Techniques for Cleaning Slate Displays Without Damage</u></a></li>
<li><a href="https://article-helps.techidaily.com/speech-understanding-no-financial-requirement/"><u>Speech Understanding No Financial Requirement</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-non-functional-hdmi-connector-via-usb/"><u>Troubleshooting Guide: Fixing a Non-Functional HDMI Connector via USB</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-successfully-resolving-loadlibrary-error-code-87/"><u>Troubleshooting Guide: Successfully Resolving LoadLibrary Error Code 87</u></a></li>
</ul></div>

