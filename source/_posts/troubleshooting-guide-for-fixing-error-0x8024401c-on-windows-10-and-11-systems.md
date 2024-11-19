---
title: Troubleshooting Guide for Fixing Error 0X8024401c on Windows 10 and 11 Systems
date: 2024-11-16T19:59:19.047Z
updated: 2024-11-18T22:45:48.238Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Guide for Fixing Error 0X8024401c on Windows 10 and 11 Systems
excerpt: This Article Describes Troubleshooting Guide for Fixing Error 0X8024401c on Windows 10 and 11 Systems
thumbnail: https://thmb.techidaily.com/a4224fc73a6465f58bae54c290236f5e5e431174596ef739d111ede45824dcdd.png
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137208/26400" target="_top" id="2137208">
  <img src="//a.impactradius-go.com/display-ad/26400-2137208" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137208/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2100537/7443" target="_top" id="2100537">
  <img src="//a.impactradius-go.com/display-ad/7443-2100537" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100537/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934288/19272" target="_top" id="1934288">
  <img src="//a.impactradius-go.com/display-ad/19272-1934288" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934288/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-pcs-top-choice-essential-ps1-emulators/"><u>[Updated] 2024 Approved PC's Top Choice Essential PS1 Emulators</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/a-comprehensive-guide-to-superior-valheim-saplings-for-2024/"><u>A Comprehensive Guide to Superior Valheim Saplings for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/cambia-da-ape-a-aiff-senza-costi-utilizzando-il-servizio-online-di-conversione-di-movavi/"><u>Cambia Da .ape a .aiff Senza Costi Utilizzando Il Servizio Online Di Conversione Di Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-fixing-a-broken-key-on-your-keyboard-or-smartphone/"><u>Expert Advice: Fixing a Broken '@' Key on Your Keyboard or Smartphone</u></a></li>
<li><a href="https://games-able.techidaily.com/explore-chatgpts-realm-crafting-a-text-based-rpg-experience/"><u>Explore ChatGPT's Realm: Crafting a Text-Based RPG Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-windows-11-users-report-surface-pro-4-camera-malfunction/"><u>Fixing the Issue: Windows 11 Users Report Surface Pro 4 Camera Malfunction</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-to-insert-youtube-playlists-seamlessly-into-a-website-for-2024/"><u>How to Insert YouTube Playlists Seamlessly Into a Website for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-for-iphone-se-2020-lock-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide For iPhone SE (2020) Lock Screen | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/inside-lenovos-revolutionary-transparent-laptop-a-hands-on-review-from-mobile-world-congress/"><u>Inside Lenovo's Revolutionary Transparent Laptop: A Hands-On Review From Mobile World Congress</u></a></li>
<li><a href="https://media-tips.techidaily.com/obtain-elusive-cinema-top-5-methods-for-accessing-non-streamable-movies/"><u>Obtain Elusive Cinema: Top 5 Methods for Accessing Non-Streamable Movies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-ftdi-driver-conflicts-restoring-memory-checks-and-data-safety/"><u>Resolving FTDI Driver Conflicts: Restoring Memory Checks and Data Safety</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-comprehensive-analysis-of-latest-tech-devices-and-performance-benchmarks/"><u>Tom's Comprehensive Analysis of Latest Tech Devices & Performance Benchmarks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-to-clear-up-the-windows-update-error-x0x800706f2-quickly/"><u>Troubleshooting Guide to Clear Up the Windows Update Error: X0x800706F2 Quickly</u></a></li>
</ul></div>

