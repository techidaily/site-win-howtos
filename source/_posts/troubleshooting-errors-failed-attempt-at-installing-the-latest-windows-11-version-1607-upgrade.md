---
title: "Troubleshooting Errors: Failed Attempt at Installing the Latest Windows 11 (Version 1607) Upgrade"
date: 2024-10-06T21:51:46.646Z
updated: 2024-10-09T20:32:50.020Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Errors: Failed Attempt at Installing the Latest Windows 11 (Version 1607) Upgrade"
excerpt: "This Article Describes Troubleshooting Errors: Failed Attempt at Installing the Latest Windows 11 (Version 1607) Upgrade"
thumbnail: https://thmb.techidaily.com/214adb491c46e660f7414c50c0b43fa707653a1bb501fab4eb3e1c0ad873052e.jpg
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
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2105863/7443" target="_top" id="2105863">
  <img src="//a.impactradius-go.com/display-ad/7443-2105863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105863/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<span id="1983575">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983575.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983575">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983575.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983575%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983575/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134500/19576" target="_top" id="2134500">
  <img src="//a.impactradius-go.com/display-ad/19576-2134500" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134500/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-support.techidaily.com/new-premium-line-up-top-5-slow-motion-models/"><u>[New] Premium Line-Up Top 5 Slow Motion Models</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-personalized-settings-not-responding/"><u>[SOLVED] Personalized Settings (Not Responding)</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-augment-your-design-abilities-the-10-most-powerful-android-graphics-tools/"><u>[Updated] Augment Your Design Abilities The 10 Most Powerful Android Graphics Tools</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-carminati-ajay-mastering-the-art-and-science-of-online-income/"><u>[Updated] Carminati (Ajay) Mastering the Art and Science of Online Income</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-tailoring-your-vtubers-tone-best-app-recommendations-unveiled/"><u>[Updated] Tailoring Your Vtuber's Tone Best App Recommendations Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/catastrophic-closure-fatal-glitch/"><u>Catastrophic Closure: Fatal Glitch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/echoes-of-victory-laptop-finds-lost-headphone-link/"><u>Echoes of Victory: Laptop Finds Lost Headphone Link</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-to-correct-not-found-error-messages-when-running-applications-in-windows/"><u>Effective Strategies to Correct 'Not Found' Error Messages When Running Applications in Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/efficiently-transforming-tiktok-videos-into-gif-format-for-2024/"><u>Efficiently Transforming TikTok Videos Into GIF Format for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-connection-interruptions-during-downloads/"><u>How to Overcome Connection Interruptions During Downloads</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-poco-m6-pro-4g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Poco M6 Pro 4G</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-vivo-y200e-5g-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Vivo Y200e 5G to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/navigating-classic-gaming-on-modern-computers-with-5-top-gb-advance-emulators-for-2024/"><u>Navigating Classic Gaming on Modern Computers with 5 Top GB Advance Emulators for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208938495-revive-your-bluetooth-functionality-on-windows-10-fast-and-straightforward-fixes-inside/"><u>Revive Your Bluetooth Functionality on Windows 10: Fast and Straightforward Fixes Inside.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-non-functioning-voice-chat-in-overwatch-with-simple-steps/"><u>Troubleshoot Non-Functioning Voice Chat in Overwatch with Simple Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-correcting-google-chromes-errcachemiss-cache-failure/"><u>Troubleshooting and Correcting Google Chrome's ERR_CACHE_MISS Cache Failure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missing-classes-in-windows-11-step-by-step-solutions/"><u>Troubleshooting Missing Classes in Windows 11: Step-by-Step Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-solving-the-puzzle-of-twitch-error-code-4000/"><u>Ultimate Guide: Solving the Puzzle of Twitch Error Code 4000</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/upgrading-made-simple-the-ios-15-guidebook/"><u>Upgrading Made Simple: The iOS 15 Guidebook</u></a></li>
</ul></div>

