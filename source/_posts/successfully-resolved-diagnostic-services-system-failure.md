---
title: "Successfully Resolved: Diagnostic Services System Failure"
date: 2024-10-26T17:53:44.983Z
updated: 2024-10-27T18:37:11.830Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Successfully Resolved: Diagnostic Services System Failure"
excerpt: "This Article Describes Successfully Resolved: Diagnostic Services System Failure"
thumbnail: https://thmb.techidaily.com/ab68550bed8939ff878aaece9b28e90d8b0465006aaa80a48dab2ef20ecc47cd.jpg
---

## Resolving 'Diagnostics Policy Service Is Offline – Here’s What To Do

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137973/21526" target="_top" id="2137973">
  <img src="//a.impactradius-go.com/display-ad/21526-2137973" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137973/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482">
  <img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082527/7443" target="_top" id="2082527">
  <img src="//a.impactradius-go.com/display-ad/7443-2082527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)

3) Click the **Update**  button next to a flagged network adapter driver to automatically download and install the correct version of this driver (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **Pro** version – you’ll be prompted to upgrade when you click Update All).

 Driver Easy requires network connection to update drivers. If your windows can’t access the Internet, please use the Offline Scan feature of Driver Easy to help you.

 4) After updating your network adapter driver, please restart your computer.

 5) Run the Network Diagnostics to see if it goes well.

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
<li><a href="https://win-howtos.techidaily.com/solvedyour-device-driver-is-not-compatible-in-wow/"><u>[SOLVED]Your Device Driver Is Not Compatible in WoW</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-sharing-excellence-twitch-live-to-your-facebook-circle-for-2024/"><u>[Updated] Sharing Excellence Twitch Live to Your Facebook Circle for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/96-off-for-lifetime-access-to-mondly-premium/"><u>96% OFF For Lifetime Access To Mondly Premium</u></a></li>
<li><a href="https://win-amazing.techidaily.com/downloading-the-linksys-ae1200-driver-made-easy-and-quick-for-all-users/"><u>Downloading the Linksys AE1200 Driver Made Easy & Quick for All Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-the-persistent-dxgkrnl-error-in-your-windows-videos/"><u>Effective Fixes for the Persistent Dxgkrnl Error in Your Window's Videos</u></a></li>
<li><a href="https://driver-install.techidaily.com/elevate-display-performance-by-tweaking-win1011s-hdmi-driver/"><u>Elevate Display Performance by Tweaking Win10/11's HDMI Driver</u></a></li>
<li><a href="https://facebook.techidaily.com/has-someone-been-using-your-pc-is-someone-using-your-emails-heres-how-to-tell/"><u>Has Someone Been Using Your PC? Is Someone Using Your Emails? Here's How to Tell</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/how-to-create-compelling-content-for-facebook-reels-for-2024/"><u>How to Create Compelling Content for Facebook Reels for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-malfunctioning-buttons-in-microsofts-latest-operating-systems/"><u>How to Repair Malfunctioning Buttons in Microsoft's Latest Operating Systems</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Honor X9b | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ipad-showdown-choosing-between-the-m1-and-m2-models-the-ultimate-guide-zdnet-tech-reviews/"><u>IPad Showdown: Choosing Between the M1 and M2 Models - The Ultimate Guide | ZDNet Tech Reviews</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-beyond-windows-10-photos-8-excellent-image-viewing-options/"><u>New In 2024, Beyond Windows 10 Photos 8 Excellent Image Viewing Options</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-chromes-inaccessible-webpage-dilemma/"><u>Overcoming Chrome's Inaccessible Webpage Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-unintended-characters-while-typing/"><u>Solving the Issue of Unintended Characters While Typing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-of-the-ghostly-white-pixels-on-your-computer-monitor/"><u>Solving the Mystery of the Ghostly White Pixels on Your Computer Monitor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-techniques-for-overcoming-opengl-hiccups-in-minecraft/"><u>Troubleshooting Techniques for Overcoming OpenGL Hiccups in Minecraft</u></a></li>
<li><a href="https://win-howtos.techidaily.com/uncover-the-solution-to-restore-gone-icons-on-your-windows-11-pc-easily/"><u>Uncover the Solution to Restore Gone Icons on Your Windows 11 PC Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unexpected-computer-restarts-causes-and-solutions-for-a-steady-performance/"><u>Unexpected Computer Restarts – Causes & Solutions for a Steady Performance</u></a></li>
</ul></div>

