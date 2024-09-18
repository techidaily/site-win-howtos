---
title: "Troubleshooting Tips: Resolving Minecraft's Frustrating Error Code ✖️5"
date: 2024-09-13T23:46:42.693Z
updated: 2024-09-17T19:20:22.969Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Tips: Resolving Minecraft's Frustrating Error Code ✖️5"
excerpt: "This Article Describes Troubleshooting Tips: Resolving Minecraft's Frustrating Error Code ✖️5"
thumbnail: https://thmb.techidaily.com/e73bb44e853b64ea13a3dc6d94705befdc354ca8d892b35c869decc7b55413a7.png
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  
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
<li><a href="https://extra-support.techidaily.com/2024-approved-srt-unveiled-essential-information-for-all-ages/"><u>2024 Approved SRT Unveiled Essential Information for All Ages</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-science-behind-auto-hdr-and-cameras-ai-powered-shooting-modes/"><u>2024 Approved The Science Behind Auto HDR and Camera's AI-Powered Shooting Modes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x80073cf9-in-windows-11-explained-understand-and-solve-the-issue-today/"><u>Error Code 0X80073CF9 in Windows 11 Explained - Understand and Solve the Issue Today!</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-from-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account From iPhone 15 Pro Max?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-troubleshooting-failed-windows-update-errors/"><u>Master the Art of Troubleshooting Failed Windows Update Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/system-disallows-execution/"><u>System Disallows Execution</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-source-unavailable-errors-in-windows-1011/"><u>Troubleshooting Steps for “Source Unavailable” Errors in Windows 10/11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://oneplusfr.sjv.io/c/5597632/1622438/14044" target="_top" id="1622438">
  <img src="//a.impactradius-go.com/display-ad/14044-1622438" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://oneplusfr.sjv.io/i/5597632/1622438/14044" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

