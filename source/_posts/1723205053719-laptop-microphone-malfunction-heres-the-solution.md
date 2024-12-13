---
title: Laptop Microphone Malfunction? Here's the Solution!
date: 2024-12-07T18:03:25.193Z
updated: 2024-12-13T16:12:52.768Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-conquer-joining-on-tiktok-with-confidence-and-flair/"><u>[New] 2024 Approved Conquer Joining on TikTok with Confidence and Flair</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-discovering-facebooks-quintessential-updates/"><u>[Updated] Discovering Facebook's Quintessential Updates</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-legacy-os-to-innovative-windows-11/"><u>[Updated] From Legacy OS to Innovative Windows 11</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-solutions-to-mitigate-vibrational-jello-in-uav-recordings/"><u>[Updated] In 2024, Solutions to Mitigate Vibrational Jello in UAV Recordings</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-streamlining-your-zoom-collaboration-calendar/"><u>[Updated] Streamlining Your Zoom Collaboration Calendar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/banish-the-blight-of-error-code-0xc0000098-with-these-simple-repair-steps-for-windows-users/"><u>Banish the Blight of Error Code 0Xc0000098 with These Simple Repair Steps for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-infinite-loading-in-valorant-with-these-tips/"><u>Bypassing Infinite Loading in Valorant with These Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/class-not-registered-on-windows-11-solved/"><u>Class Not Registered on Windows 11 [Solved]</u></a></li>
<li><a href="https://screen-recording.techidaily.com/crafting-quality-content-setting-up-your-mac-for-minecraft-sessions-for-2024/"><u>Crafting Quality Content Setting Up Your Mac for Minecraft Sessions for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-1067-decoded-why-your-windows-application-ended-prematurely-and-how-to-avoid-it/"><u>Error Code 1067 Decoded: Why Your Windows Application Ended Prematurely and How to Avoid It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-fix-path-not-found-errors-when-using-windows-operating-system/"><u>Expert Tips to Fix 'Path Not Found' Errors When Using Windows Operating System</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/get-to-know-the-new-arrival-fresh-on-the-market-the-newest-macbook-uncovered/"><u>Get to Know the New Arrival: Fresh on the Market, The Newest MacBook Uncovered</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correct-the-wwe-2k-battlegrounds-feature-level-100-and-dx11-error-messages/"><u>How to Correct the WWE 2K: Battlegrounds Feature Level 10.0 and DX11 Error Messages</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-broken-or-damaged-windows-store-cache-a-comprehensive-guide/"><u>How to Fix a Broken or Damaged Windows Store Cache: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-copy-and-paste-failures-on-windows-10-system/"><u>Resolving Copy and Paste Failures on Windows 10 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-resolve-sluggish-keyboard-responses-instantly/"><u>Step-by-Step Tutorial: Resolve Sluggish Keyboard Responses Instantly</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/steps-to-set-up-the-zilt-addon-collection-on-kodi-version-190-leia/"><u>Steps to Set Up the Zilt Addon Collection on Kodi Version 19.0 Leia</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-chatgpts-text-input-restrictions-bypassing-the-cap/"><u>Understanding ChatGPT's Text Input Restrictions: Bypassing the Cap</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/upload-and-transform-mp4-videos-to-movquicktime-formats-for-free-online-conversion-services/"><u>Upload & Transform MP4 Videos to MOV/QuickTime Formats for Free Online Conversion Services</u></a></li>
</ul></div>

