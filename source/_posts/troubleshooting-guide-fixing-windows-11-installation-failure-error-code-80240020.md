---
title: "Troubleshooting Guide: Fixing Windows 11 Installation Failure - Error Code 80240020"
date: 2024-10-12T03:29:37.264Z
updated: 2024-10-15T17:35:09.004Z
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
<a href="https://appsumo.8odi.net/c/5597632/2075476/7443" target="_top" id="2075476">
  <img src="//a.impactradius-go.com/display-ad/7443-2075476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075476/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2082521/7443" target="_top" id="2082521">
  <img src="//a.impactradius-go.com/display-ad/7443-2082521" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082521/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896555/19272" target="_top" id="1896555">
  <img src="//a.impactradius-go.com/display-ad/19272-1896555" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896555/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/updated-viral-journey-top-tags-to-accelerate-views-in-short-form-videos/"><u>[Updated] Viral Journey Top Tags to Accelerate Views in Short Form Videos</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-expert-tips-for-effortless-green-screening-in-kinemaster-software/"><u>2024 Approved Expert Tips for Effortless Green Screening in KineMaster Software</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Google Pixel 7a | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/audio-ambiance-weaving-music-into-instagram-moments-for-2024/"><u>Audio Ambiance Weaving Music Into Instagram Moments for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-make-music-accessible-with-a-well-designed-youtube-playlist/"><u>In 2024, Make Music Accessible with a Well-Designed YouTube Playlist</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-honor-play-8t-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Honor Play 8T</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-acts-erratically/"><u>Keyboard Acts Erratically</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-11-cast-device-connection-problems-a-comprehensive-guide/"><u>Overcoming Windows 11 Cast Device Connection Problems – A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pc-game-crashes-fixed-steps-to-ensure-stable-performance-on-windows-versions-11-10-7-81-and-gro/"><u>PC Game Crashes? Fixed! Steps to Ensure Stable Performance on Windows Versions 11, 10, 7, 8.1 & Gro</u></a></li>
<li><a href="https://extra-resources.techidaily.com/perfecting-your-projects-proportions-with-aspect-ratio/"><u>Perfecting Your Project's Proportions with Aspect Ratio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-windows-keyboard-malfunction-issues/"><u>Step-by-Step Guide: Resolving Windows Keyboard Malfunction Issues</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/voice-clarity-overcoming-skype-noise-issues-for-2024/"><u>Voice Clarity Overcoming Skype Noise Issues for 2024</u></a></li>
</ul></div>

