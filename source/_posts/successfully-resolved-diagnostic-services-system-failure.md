---
title: "Successfully Resolved: Diagnostic Services System Failure"
date: 2025-01-11T16:43:22.151Z
updated: 2025-01-13T16:37:56.398Z
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

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-discover-the-elite-live-streaming-platforms/"><u>[New] 2024 Approved Discover the Elite Live Streaming Platforms</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-tales-of-trial-by-fire-vs-innovative-challenges/"><u>[New] 2024 Approved Tales of Trial by Fire Vs. Innovative Challenges</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-rhythm-and-reel-incorporating-tunes-on-instagram/"><u>[New] Rhythm & Reel Incorporating Tunes on Instagram</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-simplify-storytelling-transform-vimeo-into-captivating-gifs-for-2024/"><u>[New] Simplify Storytelling Transform Vimeo Into Captivating GIFs for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressed-halt-error-of-print-driver-host-while-using-32-bit-application/"><u>Addressed: Halt Error of Print Driver Host While Using 32-Bit Application</u></a></li>
<li><a href="https://win-howtos.techidaily.com/audio-disruption-in-win-10-rectified/"><u>Audio Disruption in Win 10 Rectified</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/effective-solutions-for-internal-power-malfunction-in-windows-10-devices/"><u>Effective Solutions for Internal Power Malfunction in Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-wdf-implementation-lowering-high-cpu-consumption-in-windows-systems/"><u>Efficient WDF Implementation - Lowering High CPU Consumption in Windows Systems</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/free-converter-web-service-transform-wmv-files-into-asf-format/"><u>Free Converter Web Service - Transform WMV Files Into ASF Format</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-fixing-usb-terminal-voltage-problems-on-windows-11-devices/"><u>Guide to Fixing USB Terminal Voltage Problems on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-11-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 11 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-challenges-when-your-dhcp-server-is-not-responding-solution/"><u>How to Overcome Challenges When Your DHCP Server Is Not Responding (Solution)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/inside-virtuality-metaverse-vs-omniverse-in-focus-for-2024/"><u>Inside Virtuality Metaverse Vs. Omniverse in Focus for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/left-click-not-responding-heres-how-you-can-resolve-the-issue-quickly/"><u>Left Click Not Responding? Here's How You Can Resolve the Issue Quickly</u></a></li>
<li><a href="https://tech-revival.techidaily.com/securing-your-information-against-potential-leaks-in-custom-gpt-applications-including-chatgpt/"><u>Securing Your Information Against Potential Leaks in Custom GPT Applications Including ChatGPT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-restoring-audio-on-your-acer-notebook/"><u>Troubleshooting Steps: Restoring Audio on Your Acer Notebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fallout-4-performance-tips-say-goodbye-to-lag/"><u>Ultimate Fallout 4 Performance Tips - Say Goodbye to Lag!</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-storage-solution-for-sony-a7s-ii/"><u>Ultimate Storage Solution for Sony A7S II</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-taskbar-not-hiding-solved/"><u>Windows 10 Taskbar Not Hiding [Solved]</u></a></li>
</ul></div>

