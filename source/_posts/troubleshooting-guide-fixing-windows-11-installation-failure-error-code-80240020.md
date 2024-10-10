---
title: "Troubleshooting Guide: Fixing Windows 11 Installation Failure - Error Code 80240020"
date: 2024-10-07T18:00:35.017Z
updated: 2024-10-09T21:14:07.413Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: Fixing Windows 11 Installation Failure - Error Code 80240020"
excerpt: "This Article Describes Troubleshooting Guide: Fixing Windows 11 Installation Failure - Error Code 80240020"
thumbnail: https://thmb.techidaily.com/ea5e8021512da560143621a6e45ed4b3d646d858089a4c1425190ddca7b5f2e2.png
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
<a href="https://unicoeye.pxf.io/c/5597632/2148772/18498" target="_top" id="2148772">
  <img src="//a.impactradius-go.com/display-ad/18498-2148772" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148772/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135373/19272" target="_top" id="2135373">
  <img src="//a.impactradius-go.com/display-ad/19272-2135373" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135373/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948932/19272" target="_top" id="1948932">
  <img src="//a.impactradius-go.com/display-ad/19272-1948932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151890/7443" target="_top" id="2151890">
  <img src="//a.impactradius-go.com/display-ad/7443-2151890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151890/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-files.techidaily.com/new-asus-mg28uq-monitor-unpacking-the-ultra-high-resolution-experience/"><u>[New] ASUS MG28UQ Monitor Unpacking the Ultra High-Resolution Experience</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-the-ultimate-guide-to-zdsoft-video-recording/"><u>[New] In 2024, The Ultimate Guide to ZDSoft Video Recording</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-tips-for-finding-christian-choir-songs-online-and-personalizing-them/"><u>[New] Tips for Finding Christian Choir Songs Online & Personalizing Them</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-inverting-video-order-on-snapchat/"><u>[Updated] Inverting Video Order on Snapchat</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/boosting-viewership-and-fanship-through-strategic-igtv-hashtag-use/"><u>Boosting Viewership and Fanship Through Strategic IGTV Hashtag Use</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-connectivity-for-your-minecraft-local-network-gameplay/"><u>How To Restore Connectivity For Your Minecraft Local Network Gameplay</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-tecno-pop-8-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Tecno Pop 8 to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/league-of-legends-download-accelerator-eliminating-slow-connection-woes/"><u>League of Legends Download Accelerator: Eliminating Slow Connection Woes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-function-fn-key-malfunction-fast-and-simple-solutions/"><u>Lenovo Function (Fn) Key Malfunction: Fast and Simple Solutions</u></a></li>
<li><a href="https://network-issues.techidaily.com/lenovo-gone-dark-solutions-await/"><u>Lenovo Gone Dark? Solutions Await</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcome-iphones-portable-hard-drive-issues-with-easy-usb-driver-fixes/"><u>Overcome iPhone's Portable Hard Drive Issues with Easy USB Driver Fixes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/pixel-watch-series-4-unveiled-anticipated-cost-launch-timeline-and-potential-features/"><u>Pixel Watch Series 4 Unveiled: Anticipated Cost, Launch Timeline & Potential Features</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-10s-0x80072fed-issue-step-by-step-solutions/"><u>Resolving Windows 10'S 0X80072FED Issue: Step-by-Step Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-0x80070490-issue-on-your-pc-complete-fix-guide/"><u>Solving the 0X80070490 Issue on Your PC - Complete Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-how-to-resolve-no-signal-screen-issue/"><u>Step-by-Step Guide: How to Resolve 'No Signal' Screen Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-loadlibrary-failed-fixing-the-problem-of-error-87-in-windows/"><u>Troubleshooting 'LoadLibrary Failed' - Fixing the Problem of Error 87 in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-adapting-to-organization-imposed-windows-system-settings-policies/"><u>Understanding and Adapting to Organization-Imposed Windows System Settings Policies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-1011-issue-frozen-acer-laptop-keys/"><u>Windows 10/11 Issue: Frozen Acer Laptop Keys</u></a></li>
</ul></div>

