---
title: "Troubleshooting Tips: Resolving Minecraft's Frustrating Error Code ✖️5"
date: 2024-10-15T04:39:00.996Z
updated: 2024-10-16T05:26:08.634Z
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
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959712/19272" target="_top" id="1959712">
  <img src="//a.impactradius-go.com/display-ad/19272-1959712" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959712/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043593/7443" target="_top" id="2043593">
  <img src="//a.impactradius-go.com/display-ad/7443-2043593" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043593/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-crafting-stunning-insta-films-templates-plus-hacks/"><u>[Updated] In 2024, Crafting Stunning Insta Films Templates + Hacks</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-xiaomi-redmi-12-5g-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-fix-for-when-your-cursor-gets-lost-in-windows-10/"><u>Complete Fix for When Your Cursor Gets Lost in Windows 10</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/complete-iphone-backup-solution-for-mac-securely-retrieve-erased-media-files-and-contacts/"><u>Complete iPhone Backup Solution for Mac: Securely Retrieve Erased Media Files and Contacts</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-vivo-s17-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Vivo S17</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-turn-on-your-inactive-printer-overcoming-error-code-30-hurdles/"><u>How to Turn On Your Inactive Printer: Overcoming Error Code -30 Hurdles</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-itel-p55t-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Itel P55T Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-petite-narrative-blueprint/"><u>In 2024, Petite Narrative Blueprint</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204118936-laptop-power-issues-heres-how-to-get-the-battery-charging-fast/"><u>Laptop Power Issues? Here’s How to Get the Battery Charging Fast!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolution-steps-correcting-game-session-failed-vac-checks/"><u>Resolution Steps: Correcting 'Game Session Failed VAC Checks'</u></a></li>
<li><a href="https://technical-tips.techidaily.com/save-80-on-a-quad-camera-security-system-with-integrated-floodlights-this-labor-day-deals-at-blink/"><u>Save $80 on a Quad-Camera Security System with Integrated Floodlights This Labor Day - Deals at Blink</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-eliminate-boot-loop-issues-for-a-smooth-computer-start-up/"><u>Solution: Eliminate Boot Loop Issues for a Smooth Computer Start-Up</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-overcome-the-xerox-update-failure-error-code-0x800f020b-in-windows/"><u>Step-by-Step Guide to Overcome the Xerox Update Failure (Error Code 0X800F020B) in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-repair-correcting-the-update-failure-on-your-pc-with-windows-11-error-code-0xc1900208/"><u>Step-by-Step Repair: Correcting the Update Failure on Your PC with Windows 11 (Error Code 0Xc1900208)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-repair-usb-to-hdmi-adapter-issues-and-how-to-resolve-them/"><u>Step-by-Step Repair: USB-to-HDMI Adapter Issues and How to Resolve Them</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-ultimate-selection-best-ergonomic-keyboard-wrist-pads-for-optimal-typing-comfort-2024-edition/"><u>The Ultimate Selection: Best Ergonomic Keyboard Wrist Pads for Optimal Typing Comfort - 2024 Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-connection-issues-with-airpods-on-windows-pcs-windows-10-and-11/"><u>Ultimate Guide: Resolving Connection Issues with AirPods on Windows PCs (Windows 10 & 11)</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlock-effective-voice-typing-on-your-iphone-with-these-5-essential-troubleshooting-steps/"><u>Unlock Effective Voice Typing on Your iPhone with These 5 Essential Troubleshooting Steps</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-missing-your-hardware-drivers-with-windows-device-manager-on-windows-10-by-drivereasy-guide/"><u>Use Device Manager to identify missing your hardware drivers with Windows Device Manager on Windows 10</u></a></li>
</ul></div>

