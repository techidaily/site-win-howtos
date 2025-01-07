---
title: Laptop Microphone Malfunction? Here's the Solution!
date: 2025-01-04T17:12:33.131Z
updated: 2025-01-06T16:59:08.515Z
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

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-exclusive-reveals-on-securing-high-quality-live-cricket-broadcasting/"><u>[New] 2024 Approved Exclusive Reveals on Securing High-Quality Live Cricket Broadcasting</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-bring-imagination-alive-start-with-microsofts-movie-maker-on-w11/"><u>[New] In 2024, Bring Imagination Alive Start with Microsoft's Movie Maker on W11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-surpassing-the-ranks-essential-factors-uncovered/"><u>[New] In 2024, Surpassing the Ranks Essential Factors Uncovered</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-essential-image-protection-top-watermarkers-listed/"><u>2024 Approved Essential Image Protection Top Watermarkers Listed</u></a></li>
<li><a href="https://extra-resources.techidaily.com/beginning-virtual-conversations-zoom-meeting-setup-for-android-users-for-2024/"><u>Beginning Virtual Conversations Zoom Meeting Setup for Android Users for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/boost-your-gameplay-optimizing-pc-settings-for-ultimate-windows-11-gaming-experience/"><u>Boost Your Gameplay: Optimizing PC Settings for Ultimate Windows 11 Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-driver-power-state-failure-on-windows/"><u>How to Fix Driver Power State Failure on Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-elevating-selfies-and-pics-on-snapchat-edit-like-a-pro/"><u>In 2024, Elevating Selfies and Pics on Snapchat – Edit Like a Pro</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-infinix-note-30i-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Infinix Note 30i Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-top-5-free-video-rotator-apps-for-iphone-users-2023-edition/"><u>New 2024 Approved Top 5 Free Video Rotator Apps for iPhone Users 2023 Edition</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-install-lenovo-x220-driver-download-guide/"><u>Quick Install: Lenovo X220 Driver Download Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-sluggish-boot-times-on-your-windows-7-pc-a-step-by-step-guide/"><u>Resolving Sluggish Boot Times on Your Windows 7 PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209174326-solved-shockwave-flash-no-longer-compatible-with-google-chrome-fix-now/"><u>Solved: Shockwave Flash No Longer Compatible with Google Chrome - Fix Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-non-working-print-screen-problem-in-windows-11-and-windows-10-computers/"><u>Solving the Non-Working Print Screen Problem in Windows 11 and Windows 10 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-enhance-text-readability-in-windows-11-systems/"><u>Troubleshoot and Enhance Text Readability in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-stuck-keyboard-arrows-essential-solutions/"><u>Troubleshooting Stuck Keyboard Arrows: Essential Solutions!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-solving-diagnostics-policy-service-crashes/"><u>Understanding and Solving 'Diagnostics Policy Service' Crashes</u></a></li>
</ul></div>

