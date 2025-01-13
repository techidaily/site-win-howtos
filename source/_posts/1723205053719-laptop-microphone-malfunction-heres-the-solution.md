---
title: Laptop Microphone Malfunction? Here's the Solution!
date: 2025-01-07T16:17:50.394Z
updated: 2025-01-13T16:22:51.896Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6) Run the Network Diagnostics and see if it goes well.

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-cutting-edge-psd-outlines-effects/"><u>[New] 2024 Approved Cutting-Edge PSD Outlines Effects</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-from-novice-to-nirvana-transform-your-instagram-edits/"><u>[New] In 2024, From Novice to Nirvana Transform Your Instagram Edits</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-no-lag-top-8-screen-grab-essentials/"><u>[New] In 2024, No Lag Top 8 Screen Grab Essentials</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/uick-glimpse-youtube-shorts-insights/"><u>[New] Quick Glimpse YouTube Shorts Insights</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-the-leading-edge-in-social-media-video-capture-5-apps-reviewed/"><u>2024 Approved The Leading Edge in Social Media Video Capture (5 Apps Reviewed)</u></a></li>
<li><a href="https://win-dash.techidaily.com/bcm20702a0-windows-device-drivers-instant-download-and-installation-guide/"><u>BCM20702A0 Windows Device Drivers: Instant Download and Installation Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/breezy-video-capture-testimony/"><u>Breezy Video Capture Testimony</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-step-by-step-tutorial-resolving-the-dark-display-issue-on-your-dell-notebook/"><u>Complete Step-by-Step Tutorial: Resolving the Dark Display Issue on Your Dell Notebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-to-overcome-error-code-0x802n-2400d-on-your-pcs-updates/"><u>Comprehensive Solutions to Overcome Error Code 0X802n-2400D on Your PC's Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-resolving-the-unresponsive-start-menu-in-windows-11-systems/"><u>Diagnosing & Resolving the Unresponsive Start Menu in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-for-geforce-experience-cant-load-settings-issues/"><u>Fixes for 'GeForce Experience Can't Load Settings' Issues</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-selecting-the-perfect-screen-ultrawide-or-uhd-4k/"><u>In 2024, Selecting the Perfect Screen UltraWide or UHD 4K?</u></a></li>
<li><a href="https://win-webmaster.techidaily.com/methoden-zum-austausch-von-dateien-zwischen-zwei-pcs-mit-einem-ethernet-kabel/"><u>Methoden Zum Austausch Von Dateien Zwischen Zwei PCs Mit Einem Ethernet Kabel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overclocking-odds-on-your-side-again-fast-fixes/"><u>Overclocking Odds on Your Side Again - Fast Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-audio-glitches-with-speaker-pop-crackles-in-windows-operating-systems-solved/"><u>Resolve Audio Glitches with Speaker Pop-Crackles in Windows Operating Systems (Solved)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-volume-control-glitches-tips-and-tricks-for-windows-users/"><u>Resolving Volume Control Glitches: Tips and Tricks for Windows Users</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-a25-5g-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy A25 5G Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-fix-ensuring-wd-my-passport-ultra-is-compatible-and-visible-to-windows-systems/"><u>The Fix: Ensuring WD My Passport Ultra Is Compatible and Visible to Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-non-functional-keyboard-illumination-on-macbook-and-desktop-computers/"><u>Troubleshooting Guide: Non-Functional Keyboard Illumination on MacBook and Desktop Computers</u></a></li>
</ul></div>

