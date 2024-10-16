---
title: Troubleshooting and Fixing Sluggish Windows 10 Closing Problems
date: 2024-10-09T22:30:06.368Z
updated: 2024-10-16T06:54:36.819Z
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
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137224/26400" target="_top" id="2137224">
  <img src="//a.impactradius-go.com/display-ad/26400-2137224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137224/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-exemplary-video-capture-top-5-slow-motion-cams/"><u>[New] Exemplary Video Capture Top 5 Slow Motion Cams</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-optimizing-storage-spend-best-prices-in-cloud-services-for-2024/"><u>[New] Optimizing Storage Spend Best Prices in Cloud Services for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-blank-screen-bound-logitech-mouse/"><u>[Solved] Blank Screen Bound Logitech Mouse</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-youtube-ad-elimination-techniques-for-chrome-and-safari-users/"><u>[Updated] In 2024, YouTube Ad Elimination Techniques for Chrome & Safari Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effectively-repairing-fn-key-dysfunctions-in-your-computer-system/"><u>Effectively Repairing Fn-Key Dysfunctions in Your Computer System</u></a></li>
<li><a href="https://buynow-info.techidaily.com/exploring-wi-fi-6-capabilities-with-the-netgear-nighthawk-rax80-a-users-perspective/"><u>Exploring Wi-Fi 6 Capabilities with the Netgear Nighthawk RAX80 – A User's Perspective</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-missing-dll-issue-in-windows-overcoming-entrypointnotfounderror/"><u>Fixing the Missing DLL Issue in Windows: Overcoming 'EntryPointNotFoundError'</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-narzo-60-pro-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Realme Narzo 60 Pro 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-influencers-blueprint-rapidly-amass-a-million-fans-with-our-top-15-instagram-tips/"><u>In 2024, The Influencer's Blueprint Rapidly Amass a Million Fans with Our Top 15 Instagram Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-troubleshooting-failed-windows-update-errors/"><u>Master the Art of Troubleshooting Failed Windows Update Errors</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-xstudio-complete-video-setup-analysis/"><u>Mastering XStudio Complete Video Setup Analysis</u></a></li>
<li><a href="https://win-howtos.techidaily.com/noise-coming-from-your-ps4-find-out-why-and-how-you-can-repair-it/"><u>Noise Coming From Your PS4? Find Out Why and How You Can Repair It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-windows-10-setup-error-code-80240020-a-comprehensive-guide/"><u>Step-by-Step Solution for Windows 10 Setup Error Code 80240020: A Comprehensive Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-ultimate-guide-to-nokia-105-classic-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Nokia 105 Classic Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://tech-revival.techidaily.com/upgrade-your-talking-game-premium-gpt-plus-plan-for-us-aficionados/"><u>Upgrade Your Talking Game: Premium GPT-Plus Plan for U.S. Aficionados</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-stuttering-file-explorer-in-windows-11-proven-fixes/"><u>Winning the Battle Against Stuttering File Explorer in Windows 11 – Proven Fixes</u></a></li>
</ul></div>

