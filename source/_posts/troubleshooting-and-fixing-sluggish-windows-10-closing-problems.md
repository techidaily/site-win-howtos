---
title: Troubleshooting and Fixing Sluggish Windows 10 Closing Problems
date: 2024-10-17T20:33:44.154Z
updated: 2024-10-21T18:27:00.470Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Fixing Sluggish Windows 10 Closing Problems
excerpt: This Article Describes Troubleshooting and Fixing Sluggish Windows 10 Closing Problems
thumbnail: https://thmb.techidaily.com/bf2709550851c34ad73e4e10402b84c4b2a66d4794566cc36dae676c4f05bd25.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/1868590/19272" target="_top" id="1868590">
  <img src="//a.impactradius-go.com/display-ad/19272-1868590" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868590/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1424533">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424533.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424533">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424533.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424533%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424533/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135406/19272" target="_top" id="2135406">
  <img src="//a.impactradius-go.com/display-ad/19272-2135406" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-the-ultimate-movie-companion-best-free-and-paid-iphone-apps/"><u>[New] 2024 Approved The Ultimate Movie Companion Best Free and Paid iPhone Apps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-cure-eliminating-the-flicker-effect-on-your-windows-11-monitor/"><u>Diagnose & Cure: Eliminating the Flicker Effect on Your Windows 11 Monitor</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-samsung-galaxy-s23-tactical-edition-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Samsung Galaxy S23 Tactical Edition FRP Android 10/11/12/13</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-windows-11-usb-connectivity-issues-for-seamless-device-integration/"><u>How to Resolve Windows 11 USB Connectivity Issues for Seamless Device Integration</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-stop-chrome-from-using-too-much-processor-power-solution/"><u>How to Stop Chrome From Using Too Much Processor Power (Solution)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-storage-space-used-for-daily-extended-videography/"><u>In 2024, Storage Space Used for Daily Extended Videography</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-why-apple-account-disabled-on-your-iphone-xs-how-to-fix-by-drfone-ios/"><u>In 2024, Why Apple Account Disabled On your iPhone XS? How to Fix</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-repair-damaged-pdf-v14-files-stellar-by-stellar-guide/"><u>Quickly Repair Damaged PDF v1.4 Files | Stellar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/random-key-disruption/"><u>Random Key Disruption</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/share-smart-techniques-for-youtube-playlist-dispersal-for-2024/"><u>Share Smart Techniques for YouTube Playlist Dispersal for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-error-code-0x80071ac3-methods-to-fix-a-corrupted-disk/"><u>Solving Error Code 0X80071AC3: Methods to Fix a Corrupted Disk</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-wifi-issues-a-users-manual-for-repairing-ethernet-connections-in-windows-11-and-7/"><u>Tackling WiFi Issues: A User's Manual for Repairing Ethernet Connections in Windows 11 & 7</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/the-beginners-guide-to-designing-engaging-and-shareable-fb-slideshows-for-2024/"><u>The Beginner's Guide to Designing Engaging and Shareable FB SlideShows for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fix-why-your-obs-recordings-are-showing-a-black-screen-resolved/"><u>The Ultimate Fix: Why Your OBS Recordings Are Showing a Black Screen (Resolved)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-your-windows-10-machine-springs-to-life-alone-and-how-to-fix-it/"><u>Why Your Windows 10 Machine Springs to Life Alone and How to Fix It</u></a></li>
</ul></div>

