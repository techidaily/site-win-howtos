---
title: "Fix 'Windows Cannot Start Device' Error for DVD/CD-ROM in Windows 지원(11): A Step-by-Step Troubleshooting Tutorial"
date: 2024-09-24T23:25:51.403Z
updated: 2024-09-29T01:32:58.371Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fix 'Windows Cannot Start Device' Error for DVD/CD-ROM in Windows 지원(11): A Step-by-Step Troubleshooting Tutorial"
excerpt: "This Article Describes Fix 'Windows Cannot Start Device' Error for DVD/CD-ROM in Windows 지원(11): A Step-by-Step Troubleshooting Tutorial"
thumbnail: https://thmb.techidaily.com/95f65ec843e39dc81b80b6ffcbfef45d788958cee2b82fb5803fb90b93482a66.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2052062/7443" target="_top" id="2052062">
  <img src="//a.impactradius-go.com/display-ad/7443-2052062" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052062/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2006919/19272" target="_top" id="2006919">
  <img src="//a.impactradius-go.com/display-ad/19272-2006919" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006919/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-stream.techidaily.com/new-framefixer-editor/"><u>[New] FrameFixer Editor</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-image-editing-with-these-top-8-tablets-beyond-filmoras-reach/"><u>[New] Master Image Editing with These Top 8 Tablets Beyond Filmora's Reach</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unseen-elements-in-instagram-stories-for-the-curious-viewer-for-2024/"><u>[New] Unseen Elements in Instagram Stories For the Curious Viewer for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-channel-transformation-unleash-potential-with-tubebuddy/"><u>[Updated] In 2024, Channel Transformation Unleash Potential with TubeBuddy</u></a></li>
<li><a href="https://buynow-help.techidaily.com/discovering-the-world-with-canons-elegant-powershot-g9-x-ii-review/"><u>Discovering the World with Canon's Elegant PowerShot G9 X II Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207313268-lenovo-f-key-malfunction-heres-a-simple-guide-to-fixing-it-fast/"><u>Lenovo F-Key Malfunction? Here's a Simple Guide to Fixing It Fast</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mac-graphics-revolution-top-10-freeware-drawings/"><u>Mac Graphics Revolution Top 10 Freeware Drawings</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/mastering-account-management-unfollow-steps-for-2024/"><u>Mastering Account Management Unfollow Steps for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-resolving-initialization-errors-in-directx/"><u>Quick Solutions: Resolving Initialization Errors in DirectX</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-high-disk-usage-caused-by-microsoft-compatibility-telemetry-on-windows-10-systems/"><u>Resolving High Disk Usage Caused by Microsoft Compatibility Telemetry on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-problems-with-windows-sound-enhancements-tips-and-solutions/"><u>Resolving Problems with Windows Sound Enhancements - Tips and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-typing-speed-simple-tricks-for-a-faster-keyboard-reaction-time/"><u>Revive Your Typing Speed: Simple Tricks for a Faster Keyboard Reaction Time</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/smooth-and-swift-designing-your-best-thumbnails-for-2024/"><u>Smooth & Swift Designing Your Best Thumbnails for 2024</u></a></li>
</ul></div>

