---
title: Troubleshooting Windows Update Failures - Fixing Error 0X80072F8F on Win10/Win11
date: 2024-10-02T22:33:03.577Z
updated: 2024-10-09T16:42:03.756Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Windows Update Failures - Fixing Error 0X80072F8F on Win10/Win11
excerpt: This Article Describes Troubleshooting Windows Update Failures - Fixing Error 0X80072F8F on Win10/Win11
thumbnail: https://thmb.techidaily.com/6f6094ec46399b3ab308c1c10a0d303a8a2fe57d58887a0de4be9b5a76727ac2.jpg
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
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2049391/7443" target="_top" id="2049391">
  <img src="//a.impactradius-go.com/display-ad/7443-2049391" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049391/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-enhance-video-purity-optimal-watermark-eliminators/"><u>[New] In 2024, Enhance Video Purity Optimal Watermark Eliminators</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-transforming-footage-a-guide-to-gopro-color-tweaks/"><u>2024 Approved Transforming Footage A Guide to GoPro Color Tweaks</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/bgmpc/"><u>動画BGM抜き取り手順集:PC・スマホ・タブレット用の究極解法</u></a></li>
<li><a href="https://tech-haven.techidaily.com/accelerating-innovation-chatgpts-impact-on-3d-manufacturing/"><u>Accelerating Innovation: ChatGPT's Impact on 3D Manufacturing</u></a></li>
<li><a href="https://solve-hot.techidaily.com/enhance-web-analytics-with-the-power-of-cookiebot-technology/"><u>Enhance Web Analytics with the Power of Cookiebot Technology</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-8-plus-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 8 Plus without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-and-restore-your-compromised-windows-store-cache/"><u>How to Repair and Restore Your Compromised Windows Store Cache</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-honor-90-pro-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Honor 90 Pro to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-and-simple-guide-to-enable-wifi-hotspot-via-usb-on-windows-11/"><u>Quick and Simple Guide to Enable WiFi Hotspot via USB on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-how-to-restart-an-unresponsive-amd-catalyst-control-panel/"><u>Solving the Issue: How to Restart an Unresponsive AMD Catalyst Control Panel</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-process-to-buy-games-directly-on-oculus-meta-quest-2/"><u>Step-by-Step Process to Buy Games Directly on Oculus (Meta) Quest 2</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-definitive-trick-to-stop-skyrims-never-ending-launch-screen-and-enjoy-gaming/"><u>The Definitive Trick to Stop Skyrim's Never-Ending Launch Screen and Enjoy Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-unfreeze-file-explorer-on-windows-11/"><u>Troubleshooting Guide: How to Unfreeze File Explorer on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-unsticking-a-stuck-computing-system/"><u>Troubleshooting Tips: Unsticking a Stuck Computing System</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-11-fixing-unresponsive-volume-settings/"><u>Troubleshooting Windows 11: Fixing Unresponsive Volume Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-hacks-for-uninterrupted-gaming-eliminate-lag-in-minecraft-today/"><u>Ultimate Hacks for Uninterrupted Gaming: Eliminate Lag in Minecraft Today!</u></a></li>
</ul></div>

