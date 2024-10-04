---
title: "Resolved: Troubleshooting the 0xC19n0208 Error During Windows 10 Updates"
date: 2024-09-26T17:38:45.361Z
updated: 2024-10-04T05:28:15.823Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Troubleshooting the 0xC19n0208 Error During Windows 10 Updates"
excerpt: "This Article Describes Resolved: Troubleshooting the 0xC19n0208 Error During Windows 10 Updates"
thumbnail: https://thmb.techidaily.com/63fd599c9be37636882facc86b0d27ee700429a93697161a134c6af27a69e27e.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2144272/7443" target="_top" id="2144272">
  <img src="//a.impactradius-go.com/display-ad/7443-2144272" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144272/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/new-interpreting-the-significance-of-blue-emojis-on-messenger-for-2024/"><u>[New] Interpreting the Significance of Blue Emojis on Messenger for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-insight-into-how-luts-transform-your-digital-canvas-for-2024/"><u>[Updated] Insight Into How LUTs Transform Your Digital Canvas for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-top-rated-3d-tools-for-youtube-video-startups/"><u>2024 Approved Top-Rated 3D Tools for YouTube Video Startups</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-no-device-detected-error-on-your-iphoneipad/"><u>Fixing the 'No Device Detected' Error on Your iPhone/iPad</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-oppo-a58-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-timeout-issue-during-download-progress/"><u>How to Fix “Timeout” Issue During Download Progress</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-challenges-with-torrents-not-downloading-properly/"><u>How to Overcome Challenges with Torrents Not Downloading Properly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-errors-the-stop-working-problem-with-32bit-application-print-drivers-is-fixed/"><u>No More Errors - The 'Stop Working' Problem with 32Bit Application Print Drivers Is Fixed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/origin-games-solving-issues-in-your-game-configuration/"><u>Origin Games: Solving Issues in Your Game Configuration</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/simplified-approach-to-embedding-multiple-video-playlists-from-youtube/"><u>Simplified Approach to Embedding Multiple Video Playlists From YouTube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-windows-pcs-built-in-camera-issues-a-step-by-step-guide/"><u>Solving Your Windows PC's Built-In Camera Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/streamline-your-youtube-thumbnail-process-for-2024/"><u>Streamline Your YouTube Thumbnail Process for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/youtube-visual-impact-mastering-thumbnail-dimensions-for-2024/"><u>YouTube Visual Impact Mastering Thumbnail Dimensions for 2024</u></a></li>
</ul></div>

