---
title: Laptop Microphone Malfunction? Here's the Solution!
date: 2025-02-04T10:32:23.022Z
updated: 2025-02-07T09:49:20.599Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-ultimate-showdown-battle-royales-top-titles/"><u>[New] 2024 Approved Ultimate Showdown Battle Royale's Top Titles</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-perfecting-iphone-screen-exposure/"><u>[New] Perfecting iPhone Screen Exposure</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-10plus-best-instagram-video-editor-for-pc-online-android/"><u>[Updated] 10+ Best Instagram Video Editor for PC, Online, Android</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-top-vr-treadmills-review/"><u>[Updated] In 2024, Top VR Treadmills Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-resolve-your-cs-go-game-crashes-fast/"><u>Easy Steps to Resolve Your CS: GO Game Crashes Fast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-overcoming-wow-stuttering-problems/"><u>Expert Advice on Overcoming WOW Stuttering Problems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-audio-editing-with-ape-essential-tips-for-opening-and-manipulating-ape-files-using-an-ape-player/"><u>Exploring Audio Editing with APE: Essential Tips for Opening & Manipulating APE Files Using an APE Player</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-xiaomi-civi-3-disney-100th-anniversary-edition-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Xiaomi Civi 3 Disney 100th Anniversary Edition Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-the-art-of-video-to-animation-stepwise-guide-for-efficient-gif-creation-for-2024/"><u>Learn The Art Of Video to Animation Stepwise Guide for Efficient Gif Creation for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/maximizing-your-frame-rate-tips-and-tricks-for-enhanced-performance-in-ring-of-elysium/"><u>Maximizing Your Frame Rate: Tips & Tricks for Enhanced Performance in Ring of Elysium</u></a></li>
<li><a href="https://win11.techidaily.com/neutralizing-windows-update-triggers/"><u>Neutralizing Windows Update Triggers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-hdcp-limitations-on-your-display-unit-a-guide-to-enhanced-performance/"><u>Overcoming HDCP Limitations on Your Display Unit - A Guide to Enhanced Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repairing-your-lenovos-unresponsive-mouse-pad-in-different-windows-environments-1187-expert-fixes/"><u>Repairing Your Lenovo's Unresponsive Mouse Pad in Different Windows Environments (11/8/7) - Expert Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-how-to-fix-a-computer-that-cant-close-windows-10/"><u>Solved: How to Fix a Computer That Can't Close Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-correcting-forbidden-responses-http-error-403-in-web-servers/"><u>Troubleshooting and Correcting 'Forbidden' Responses (HTTP Error ⁩ 403) in Web Servers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-power-surge-issues-in-your-usb-ports-on-windows-10/"><u>Troubleshooting Guide: Resolving 'Power Surge' Issues in Your USB Ports on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-a-non-responsive-windows-10-computer/"><u>Troubleshooting Steps for a Non-Responsive Windows 10 Computer</u></a></li>
</ul></div>

