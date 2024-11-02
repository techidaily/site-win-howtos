---
title: Laptop Microphone Malfunction? Here's the Solution!
date: 2024-10-25T20:59:57.396Z
updated: 2024-11-02T13:01:47.580Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Laptop Microphone Malfunction? Here's the Solution!
excerpt: This Article Describes Laptop Microphone Malfunction? Here's the Solution!
thumbnail: https://thmb.techidaily.com/e92d1325fd1f2f901796fdd1123502e68b5122756c762090fd4b289d5054368b.jpg
---

## Diagnostic Policy Service Malfunction? Here's the Solution

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
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997630/19272" target="_top" id="1997630">
  <img src="//a.impactradius-go.com/display-ad/19272-1997630" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997630/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151872/7443" target="_top" id="2151872">
  <img src="//a.impactradius-go.com/display-ad/7443-2151872" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151872/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
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

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-maximizing-instagram-video-exposure-for-2024/"><u>[New] Maximizing Instagram Video Exposure for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-most-reliable-speech-capture-for-ipads-3/"><u>[New] Most Reliable Speech Capture for iPads #3</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-best-practices-for-efficient-slide-capture/"><u>[Updated] 2024 Approved Best Practices for Efficient Slide Capture</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-intellectual-property-rules-for-instagram-beats/"><u>[Updated] 2024 Approved Intellectual Property Rules for Instagram Beats</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-premier-convert-kits-transforming-youtube-vids-into-text/"><u>[Updated] Premier Convert Kits Transforming YouTube Vids Into Text</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-essentials-of-hosting-a-zoom-event-via-android/"><u>[Updated] The Essentials of Hosting a Zoom Event via Android</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/apple-watch-series-9-versus-fitbit-charge-6-a-comparative-review/"><u>Apple Watch Series 9 versus Fitbit Charge 6: A Comparative Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corsair-keyboard-problems-heres-how-to-make-it-functional-once-more/"><u>Corsair Keyboard Problems? Here's How to Make It Functional Once More</u></a></li>
<li><a href="https://games-able.techidaily.com/debunking-the-myth-is-faster-always-better/"><u>Debunking the Myth: Is Faster Always Better?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/demystifying-and-solving-the-persistent-black-monitor-issue-on-windows-11-computers/"><u>Demystifying and Solving the Persistent Black Monitor Issue on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-erratic-behavior-of-bluetooth-mice-for-windows-11-and-10-users/"><u>Fixing Erratic Behavior of Bluetooth Mice for Windows 11 and 10 Users</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-vivo-y27s-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Vivo Y27s with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-get-your-diagnostic-policy-service-running-again/"><u>Resolved: How to Get Your Diagnostic Policy Service Running Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-overcoming-servers-not-available-in-destiny-2/"><u>Step-by-Step Solutions: Overcoming 'Servers Not Available' In Destiny 2</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-pairing-microsoft-wireless-dock-on-a-windows-10-system-solutions-and-tips/"><u>Successfully Pairing Microsoft Wireless Dock on a Windows 10 System: Solutions and Tips</u></a></li>
<li><a href="https://fox-http.techidaily.com/the-comprehensible-path-to-proficient-greenscreen-in-kinemaster/"><u>The Comprehensible Path to Proficient Greenscreen in KineMaster</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-step-by-step-how-to-fix-windows-11-store-error-code-0x80073cf9/"><u>Troubleshooting Step-by-Step: How to Fix Windows 11 Store Error Code 0X80073CF9</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-techniques-to-eliminate-window-10s-flickering-display-dilemma/"><u>Troubleshooting Techniques to Eliminate Window 10'S Flickering Display Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/valorant-gaming-fixes-eliminate-screen-distortion-and-enjoy-seamless-play/"><u>Valorant Gaming Fixes: Eliminate Screen Distortion & Enjoy Seamless Play</u></a></li>
</ul></div>

