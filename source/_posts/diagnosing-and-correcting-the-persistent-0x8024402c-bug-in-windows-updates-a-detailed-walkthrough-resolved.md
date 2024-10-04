---
title: Diagnosing and Correcting the Persistent 0X8024402C Bug in Windows Updates – A Detailed Walkthrough [Resolved]
date: 2024-10-03T13:09:35.718Z
updated: 2024-10-04T13:28:14.214Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Correcting the Persistent 0X8024402C Bug in Windows Updates – A Detailed Walkthrough [Resolved]
excerpt: This Article Describes Diagnosing and Correcting the Persistent 0X8024402C Bug in Windows Updates – A Detailed Walkthrough [Resolved]
thumbnail: https://thmb.techidaily.com/6db3345e6b05b14e1b02d624eebb2a2ce8b63469f2261321211e5e8c5934467b.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2087408/7443" target="_top" id="2087408">
  <img src="//a.impactradius-go.com/display-ad/7443-2087408" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087408/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948881/19272" target="_top" id="1948881">
  <img src="//a.impactradius-go.com/display-ad/19272-1948881" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948881/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-posts.techidaily.com/new-pilots-toolkit-top-drones-must-have-gear-and-replacements/"><u>[New] Pilot's Toolkit Top Drones Must-Have Gear and Replacements</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-unpacking-obss-full-spectrum-of-video-capturing-tools/"><u>[Updated] 2024 Approved Unpacking OBS's Full Spectrum of Video Capturing Tools</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-expert-insights-bridging-obs-and-facebook-live-streaming/"><u>[Updated] Expert Insights Bridging OBS and Facebook Live Streaming</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-initiating-understanding-of-screen-resolution-and-quality/"><u>[Updated] Initiating Understanding of Screen Resolution and Quality</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-leading-8-android-calling-apps-more-than-four-people/"><u>[Updated] Leading 8 Android Calling Apps More Than Four People</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-solution-for-an-unresponsive-usb-connection-in-your-hp-notebook/"><u>DIY Solution for an Unresponsive USB Connection in Your HP Notebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eliminating-erratic-scrolling-in-file-explorer-on-windows-10-a-comprehensive-guide/"><u>Eliminating Erratic Scrolling in File Explorer on Windows 10 - A Comprehensive Guide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/ignite-interest-a-list-of-30-video-themes-for-2024/"><u>Ignite Interest A List of 30 Video Themes for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/optimizing-startup-performance-in-windows-10-and-11-expert-troubleshooting-tips/"><u>Optimizing Startup Performance in Windows 10 and 11: Expert Troubleshooting Tips</u></a></li>
<li><a href="https://discover-guides.techidaily.com/rapido-e-facile-scarica-i-tuoi-dvd-antichi-o-nuovi-con-questa-tutorial-di-instant-duplicazione-senza-perdite/"><u>Rapido E Facile, Scarica I Tuoi DVD Antichi O Nuovi Con Questa Tutorial Di Instant Duplicazione Senza Perdite</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-stop-the-continuous-reboot-cycle-on-windows-11/"><u>Ultimate Guide: Stop the Continuous Reboot Cycle on Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/who-should-programmers-pick-for-efficiency-copilotchatgpt-discussion/"><u>Who Should Programmers Pick for Efficiency? Copilot/ChatGPT Discussion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-fix-corrupted-files-using-sfc-and-dism-utilities/"><u>Windows 11: Fix Corrupted Files Using SFC and DISM Utilities</u></a></li>
</ul></div>

