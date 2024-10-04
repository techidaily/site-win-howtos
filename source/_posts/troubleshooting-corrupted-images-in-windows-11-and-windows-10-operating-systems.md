---
title: Troubleshooting Corrupted Images in Windows 11 and Windows 10 Operating Systems
date: 2024-09-29T00:25:49.411Z
updated: 2024-10-04T02:53:25.254Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Corrupted Images in Windows 11 and Windows 10 Operating Systems
excerpt: This Article Describes Troubleshooting Corrupted Images in Windows 11 and Windows 10 Operating Systems
thumbnail: https://thmb.techidaily.com/9416939e5407a18ea81200cd7e119e61ff04e31fb3c5cd004cd4601ad28e3eb8.jpg
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151860/7443" target="_top" id="2151860">
  <img src="//a.impactradius-go.com/display-ad/7443-2151860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043597/7443" target="_top" id="2043597">
  <img src="//a.impactradius-go.com/display-ad/7443-2043597" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043597/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-elevate-your-social-media-presence-insta-videography/"><u>[Updated] 2024 Approved Elevate Your Social Media Presence Insta-Videography</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-diy-video-mastery-10-straightforward-concepts-everyone-should-try/"><u>[Updated] In 2024, DIY Video Mastery 10 Straightforward Concepts Everyone Should Try</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-snapchat-friendly-how-to-use-your-camera-roll-effectively/"><u>[Updated] Snapchat-Friendly How to Use Your Camera Roll Effectively</u></a></li>
<li><a href="https://fox-glue.techidaily.com/cutting-edge-methods-for-a-dominant-presence-on-spotify-for-2024/"><u>Cutting-Edge Methods for a Dominant Presence on Spotify for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/foremost-haptic-feedback-devices-providers-for-2024/"><u>Foremost Haptic Feedback Devices Providers for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205319181-getting-microsofts-latest-patches-reviving-your-stalled-windows-update-service/"><u>Getting Microsoft's Latest Patches? Reviving Your Stalled Windows Update Service.</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722972709038-hid-compliant-mouse-drivers-freshly-updated-for-optimal-performance/"><u>HID-Compliant Mouse Drivers - Freshly Updated for Optimal Performance</u></a></li>
<li><a href="https://sound-issues.techidaily.com/obs-microphone-not-working-heres-how-to-record-sound-again/"><u>OBS Microphone Not Working? Here's How to Record Sound Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issue-dragon-ball-fighterz-network-initialization-error/"><u>Resolved Issue: 'Dragon Ball FighterZ' Network Initialization Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-getting-destiny-2-servers-back-online/"><u>Step-by-Step Solution: Getting Destiny 2 Servers Back Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tech-savvy-tips-troubleshooting-steps-for-a-non-freezing-computer-experience/"><u>Tech Savvy Tips: Troubleshooting Steps for a Non-Freezing Computer Experience</u></a></li>
</ul></div>

