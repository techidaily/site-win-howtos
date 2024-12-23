---
title: "Successfully Resolved: Diagnostic Services System Failure"
date: 2024-12-19T17:35:20.694Z
updated: 2024-12-22T22:17:16.685Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-optimal-energy-kits-for-gopro-hero5-genuine-and-third-party-brands/"><u>[Updated] 2024 Approved Optimal Energy Kits for GoPro Hero5 – Genuine and Third-Party Brands</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-under-the-waves-best-practices-in-underwater-filming-with-a-gopro-for-2024/"><u>[Updated] Under the Waves Best Practices in Underwater Filming with a GoPro for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-upload-like-a-pro-the-ultimate-guide-to-photo-videos-and-online-success/"><u>[Updated] Upload Like a Pro The Ultimate Guide to Photo Videos and Online Success</u></a></li>
<li><a href="https://discover-great.techidaily.com/10-professionelle-tipps-und-tricks/"><u>10 - Professionelle Tipps Und Tricks</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-tips-for-radial-blur-techniques-in-photoshop/"><u>2024 Approved Expert Tips for Radial Blur Techniques in Photoshop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/compreh-ensive-strategies-for-diagnosing-and-repairing-windows-driver-power-problem/"><u>Compreh Ensive Strategies for Diagnosing & Repairing Window's Driver Power Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210600140-constraint-a-do-not-redact-any-percentages-or-numerical-values/"><u>Constraint A: Do Not Redact Any Percentages or Numerical Values.</u></a></li>
<li><a href="https://fox-links.techidaily.com/decoding-subtitles-from-srt-to-xml-ssa-and-more-for-2024/"><u>Decoding Subtitles From SRT to XML, SSA & More for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ips-for-instant-custom-youtube-shorts-coverage/"><u>DIY Tips for Instant Custom YouTube Shorts Coverage</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-and-fix-error-144-in-livekernel-event/"><u>Expert Tips to Overcome and Fix Error 144 in LiveKernel Event</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-ensure-your-touchpad-cursor-remains-active-in-windows-11/"><u>How To Ensure Your Touchpad Cursor Remains Active In Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/insights-on-the-most-frequently-asked-questions-user-inquiries-explained/"><u>Insights on the Most Frequently Asked Questions: User Inquiries Explained</u></a></li>
<li><a href="https://fox-useful.techidaily.com/master-the-art-of-document-conversion-turn-your-ms-word-excel-and-powerpoint-files-into-engaging-physical-flipbooks-infused-with-audiovideo-discover-more-at15/"><u>Master the Art of Document Conversion: Turn Your MS Word, Excel & PowerPoint Files Into Engaging Physical Flipbooks Infused with Audio/Video - Discover More at FlipBuilder.com</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-cannot-reset-this-computer-issue-in-windows-10/"><u>Solving the 'Cannot Reset This Computer' Issue in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-netflix-connectivity-issues-is-it-just-you/"><u>Understanding Netflix Connectivity Issues - Is It Just You?</u></a></li>
</ul></div>

