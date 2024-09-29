---
title: Expert Tips on Using System File Checker (SFC) and Deployment Image Servicing (DISM) to Restore Windows 10
date: 2024-09-21T16:21:13.422Z
updated: 2024-09-28T22:31:53.330Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Tips on Using System File Checker (SFC) and Deployment Image Servicing (DISM) to Restore Windows 10
excerpt: This Article Describes Expert Tips on Using System File Checker (SFC) and Deployment Image Servicing (DISM) to Restore Windows 10
thumbnail: https://thmb.techidaily.com/0f034b01e896bfeb1b76fcb002ff3f08bf8065e806075d9660abdc53bcbc29eb.jpg
---

## Troubleshooting Tips for Windows 10 Issues with The Duo Approach: System File Checker (SFC) and Deployment Image Servicing (DISM)

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586c9a4e6db41.jpg)

 Windows 10 is equipped with some very handy tools that allow you to solve your computer problems.**System File Checker** and**Deployment Image & Servicing Management** tools are ones of them.

You should consider using these tools when:

**a) troubleshooting a buggy Windows system;**
**b) blue screen of death errors occur;**
**c) applications crash;**
**d) some Windows features are not working properly.**

and etc.

 In this post, we will show you some tools that you can use to solve your computer problems:

[**System File Checker tool**](#1)
[**Deployment Image & Servicing Management tool**](#2)
[**System Restore**](#3)

**Run SFC Command to Repair System Files**

 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca149cf04d.png)

 When prompted with the UAC, hit**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca13144fd3.jpg)

2) In the Command Prompt window, type in the following command:

sfc /scannow

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca221df44e.jpg)

Leave the Command Prompt window on until the command completes.

 3) If you see the message saying that   **Windows Resource Protection did not find any integrity violations** , then everything is fine with your system.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca520c7e49.png)

 4) If you see a message saying   **Windows Resource Protection found corrupt files but was unable to fix some of them** , then you need to go to[**safe mode**](https://tools.techidaily.com/drivereasy/download/) and run the system file checker again.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca59f1f21f.jpg)

 If the SFC command doesn’t work well, please mve on to the next section to run the DISM command to fix the SFC command problem and then run SFC command again.

**Run the DISM Command to Fix SFC Problems**

**DISM** stands for Deployment Image & Servicing Management, which is a tool that can fix component store corruption that prevents the SFC command from working properly.

 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca149cf04d.png)

 When prompted with the UAC, hit**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca13144fd3.jpg)

2) In the Command Prompt window, type in the following command:

DISM /Online /Cleanup-Image /RestoreHealth

 Make sure you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca8464439b.jpg)

Wait for a while for the whole process to finishes.

 3) When the whole process finishes, restart your computer. Then run SFC command again so it will help you replace any corrupted files with the correct ones.

 **System Refresh or Reset**

 If the above tools cannot help you solve your computer problems, you can have a try at refreshing or resetting your Windows 10.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586caacd9f489.jpg)

For more detailed information, please go to the posts below:

[**How to refresh Windows 10?**](https://tools.techidaily.com/drivereasy/download/)
[**How to reset Windows 10?**](https://tools.techidaily.com/drivereasy/download/)

**Pro Tip:**
 In many cases, most of your computer problems can be solved by updating your device drivers to their latest versions unless the problems are with the hardware, in which case, you will need to get your hardware replaced.

 To update device drivers, you can use[**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) for assistance. It automatically detects, downloads and updates your missing and outdated device drivers and allow you to finish the whole process in just a couple of minutes.

![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e8abc65e6ec.jpg)

 If you want to have your own professional tech support and tons of other features in Driver Easy such as driver back up and driver restore, by all means, have a try at the[**professional version of Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . It allows you to update all your device drivers in just ONE click and poof, your computer problems are gone!

 You can always ask for a refund thirty days within the purchase if you are not satisfied with it. What’s with the hold up, come on and have a try at[**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) now!

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
<li><a href="https://screen-capture.techidaily.com/new-essential-gaming-gear-keyboards-for-less-than-100-for-2024/"><u>[New] Essential Gaming Gear Keyboards for Less Than $100 for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-blocking-the-buzz-no-more-fb-video-ads-for-2024/"><u>[Updated] Blocking the Buzz No More FB Video Ads for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-poco-c51-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Poco C51</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-fix-a-blocked-or-unsecure-connection-issue-in-firefox/"><u>Easy Steps to Fix a Blocked or Unsecure Connection Issue in Firefox</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-techniques-for-restoring-compromised-system-data-on-latest-windows-versions/"><u>Effective Techniques for Restoring Compromised System Data on Latest Windows Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-free-updates-ahead-conquer-windows-update-glitch-0x80070002-with-ease/"><u>Error-Free Updates Ahead! Conquer Windows Update Glitch 0X80070002 With Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-a-d3d11-compatible-gpu-is-required-to-run-the-engine/"><u>Fix: A D3D11 Compatible GPU Is Required to Run the Engine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-troubleshoot-and-solve-disappearing-cursor-glitches-in-windows-11/"><u>Guide to Troubleshoot and Solve Disappearing Cursor Glitches in Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-copyrighted-chords-navigating-music-uploads-to-insta/"><u>In 2024, Copyrighted Chords Navigating Music Uploads to Insta</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-free-8-best-tools-to-make-animated-photo-easily/"><u>In 2024, FREE 8 Best Tools to Make Animated Photo Easily</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-gionee-f3-pro-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Gionee F3 Pro Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-top-10-secrets-for-recording-sports-events-live-online/"><u>In 2024, Top 10 Secrets for Recording Sports Events Live Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/problem-solved-on-screen-typing-options-and-touch-support-reinstated-to-device/"><u>Problem Solved: On-Screen Typing Options and Touch Support Reinstated to Device</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Vivo T2 Pro 5G? | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

