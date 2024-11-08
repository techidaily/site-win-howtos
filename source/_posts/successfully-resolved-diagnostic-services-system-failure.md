---
title: "Successfully Resolved: Diagnostic Services System Failure"
date: 2024-11-04T16:10:48.690Z
updated: 2024-11-08T05:26:41.862Z
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

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886003/19272" target="_top" id="1886003">
  <img src="//a.impactradius-go.com/display-ad/19272-1886003" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886003/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6) Run the Network Diagnostics and see if it goes well.

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
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136620/26400" target="_top" id="2136620">
  <img src="//a.impactradius-go.com/display-ad/26400-2136620" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136620/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135315/14409" target="_top" id="2135315">
  <img src="//a.impactradius-go.com/display-ad/14409-2135315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135315/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-files.techidaily.com/new-in-2024-step-by-step-guide-for-font-integration-in-ae/"><u>[New] In 2024, Step-by-Step Guide for Font Integration in AE</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/he-ultimate-guide-to-saving-youtube-tracks-and-dialogues/"><u>[New] The Ultimate Guide to Saving YouTube Tracks & Dialogues</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-oneplus-nord-ce-3-5g-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your OnePlus Nord CE 3 5G? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-resolve-no-download-problems-with-torrents/"><u>Guide to Resolve No-Download Problems with Torrents</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-recover-vanished-desktop-symbols-in-windows-11-fixed/"><u>How to Recover Vanished Desktop Symbols in Windows 11 [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-of-the-quick-selection-tool-windows-plus-shift-plus-s-in-windows-11-and-earlier-versions/"><u>How to Restore Functionality of the Quick Selection Tool (Windows + Shift + S) in Windows 11 and Earlier Versions</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-mp4-enhancement-the-ultimate-srt-integration/"><u>In 2024, Mastering MP4 Enhancement The Ultimate SRT Integration</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/iphone-versus-samsung-phone-debate-a-comparison-that-guides-your-purchase-decision-successfully/"><u>IPhone Versus Samsung Phone Debate: A Comparison That Guides Your Purchase Decision Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206521094-solved-why-wont-my-hp-laptop-recognize-usb-devices-a-step-by-step-guide-to-repairing-usb-connectivity-issues/"><u>Solved! Why Won’t My HP Laptop Recognize USB Devices? A Step-by-Step Guide to Repairing USB Connectivity Issues</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/step-by-step-guide-posting-shorts-on-youtube-from-pcmobile-devices/"><u>Step-by-Step Guide Posting Shorts on YouTube From PC/Mobile Devices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-honor-play-7t-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Honor Play 7T Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-best-mts-video-editors-top-picks/"><u>Updated Best MTS Video Editors Top Picks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204999935-why-isnt-my-razer-keyboard-responding-solving-the-mystery/"><u>Why Isn't My Razer Keyboard Responding? Solving the Mystery!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-lacks-screen-contrast-slider/"><u>Windows Lacks Screen Contrast Slider</u></a></li>
</ul></div>

