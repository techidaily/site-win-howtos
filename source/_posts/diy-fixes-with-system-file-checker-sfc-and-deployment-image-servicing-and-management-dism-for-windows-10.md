---
title: DIY Fixes with System File Checker (SFC) & Deployment Image Servicing & Management (DISM) for Windows 10
date: 2024-08-15T11:32:06.857Z
updated: 2024-08-16T11:32:06.857Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes DIY Fixes with System File Checker (SFC) & Deployment Image Servicing & Management (DISM) for Windows 10
excerpt: This Article Describes DIY Fixes with System File Checker (SFC) & Deployment Image Servicing & Management (DISM) for Windows 10
thumbnail: https://thmb.techidaily.com/613172768f05bc30ced4453cadcdb6862cbaab1d05b995774101e68045c480a9.png
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
<li><a href="https://win-howtos.techidaily.com/fixed-windows-host-process-rundll32-has-stopped-working/"><u>[Fixed] Windows Host Process (Rundll32) Has Stopped Working</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-display-driver-stopped-responding-and-has-recovered/"><u>[Solved] Display Driver Stopped Responding and Has Recovered</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-prime-camcorder-selections-in-depth-insights/"><u>[Updated] 2024 Approved  Prime Camcorder Selections – In-Depth Insights</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-bits-and-bytes-to-subtitles-the-zip-to-srt-pathway/"><u>[Updated] From Bits and Bytes to Subtitles  The ZIP To SRT Pathway</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-who-are-the-biggest-watchers-top-amazon-series-liked-by-twitter-2023/"><u>[Updated] Who Are the Biggest Watchers? Top Amazon Series Liked by Twitter, 2023</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-the-ultimate-ig-music-companion/"><u>2024 Approved  The Ultimate IG Music Companion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-twitch-error-4000-once-and-for-all-with-these-effective-fixes/"><u>Beat Twitch Error 4000 Once and For All with These Effective Fixes</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/best-investment-selecting-the-top-5-pro-drones/"><u>Best Investment - Selecting the Top 5 Pro Drones</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clear-explanation-correcting-and-preventing-future-occurrences-of-livekernelevent-issue-code-amoeba/"><u>Clear Explanation: Correcting and Preventing Future Occurrences of LiveKernelEvent Issue (Code Amoeba)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-broken-keyboard-input-in-windows-11-a-step-by-step-repair-manual/"><u>Dealing with Broken Keyboard Input in Windows 11: A Step-by-Step Repair Manual</u></a></li>
<li><a href="https://win-howtos.techidaily.com/detailed-walkthrough-to-correctly-diagnose-and-resolve-error-code-31-on-windows/"><u>Detailed Walkthrough to Correctly Diagnose and Resolve Error Code 31 on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-what-to-do-when-the-at-sign-is-unresponsive/"><u>Easy Fixes: What To Do When The 'At Sign' Is Unresponsive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-overcome-the-not-ready-gadget-warning/"><u>Effective Solutions to Overcome the 'Not Ready' Gadget Warning</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/efficient-image-capturing-made-simple-the-best-pc-snipers-listed-for-2024/"><u>Efficient Image Capturing Made Simple  The Best PC Snipers Listed for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-techniques-to-release-held-up-window-update-on-obsolete-os-like-win7-a-complete-solution-walkthrough-troubleshooting-guide-solutions-and-step-by-s57/"><u>Efficient Techniques to Release Held-Up Window Update on Obsolete OS Like Win7 – A Complete Solution Walkthrough (Troubleshooting Guide, Solutions and Step by Step Guide)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolution-guide-fixing-driver-failed-message-in-user-settings/"><u>Error Resolution Guide: Fixing 'Driver Failed' Message in User Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-fixes-to-get-your-destiny-2-past-the-stuck-initialization-screen/"><u>Fast Fixes to Get Your Destiny 2 Past The Stuck Initialization Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-laptop-trackpad-issues-on-windows-11-8-and-7-a-step-by-step-guide/"><u>Fixing Laptop Trackpad Issues on Windows 11, 8 & 7: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208700605-fixing-non-responsive-arrow-keys-on-your-keyboard-expert-solutions/"><u>Fixing Non-Responsive Arrow Keys on Your Keyboard - Expert Solutions!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-black-screen-problem-in-obs-a-comprehensive-guide/"><u>Fixing the 'Black Screen' Problem in OBS - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/google-chrome-freezing-problem-solved-top-strategies-and-tips/"><u>Google Chrome Freezing Problem Solved - Top Strategies and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-update-error-code-0x80240017-once-and-for-all/"><u>How to Fix Windows Update Error Code 0X80240017 Once and For All</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-8-plus-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 8 Plus to other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-zte-nubia-flip-5g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your ZTE Nubia Flip 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-laughs-lab-innovator/"><u>In 2024, Laughs Lab Innovator</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-battleye-service-integration-no-more-failed-attempts/"><u>Mastering the BattlEye Service Integration: No More Failed Attempts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/netflix-speed-management-for-enhanced-viewing-for-2024/"><u>Netflix Speed Management for Enhanced Viewing for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/outlook-troubleshooting-repairing-connection-errors-with-microsoft-exchange-services/"><u>Outlook Troubleshooting: Repairing Connection Errors with Microsoft Exchange Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-lenovo-fn-key-issues-a-step-by-step-guide-for-immediate-results/"><u>Overcoming Lenovo Fn Key Issues: A Step-by-Step Guide for Immediate Results</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-obstacles-a-guide-to-successful-windows-patching/"><u>Overcoming Obstacles: A Guide to Successful Windows Patching</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issues-with-system-boot-up-prevented/"><u>Resolved: Issues with System Boot-Up Prevented</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-monster-hunter-worlds-black-screen-problem-on-your-pc/"><u>Resolving Monster Hunter World’s Black Screen Problem on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-sound-to-your-xbox-one-setup-effective-troubleshooting-steps/"><u>Restore Sound to Your Xbox One Setup - Effective Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-unsupported-miracast-error-with-easy-graphics-drivers-fixes/"><u>Solving the 'Unsupported Miracast' Error with Easy Graphics Drivers Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-when-your-windows-11-cant-find-bluetooth-gadgets/"><u>Step-by-Step Fixes for When Your Windows 11 Can't Find Bluetooth Gadgets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-the-annoying-cursor-flicker-with-easy-solutions/"><u>Stop the Annoying Cursor Flicker with Easy Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210628219-troubleshoot-and-overcome-windows-update-error-0x80070002-effortlessly/"><u>Troubleshoot and Overcome Windows Update Error 0X80070002 Effortlessly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-chrome-access-problems-how-to-solve-this-site-cant-be-reached/"><u>Troubleshooting Chrome Access Problems: How To Solve 'This Site Can't Be Reached'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-windows-error-0x80071ac3-volume-corruption-fixes/"><u>Troubleshooting Guide for Windows Error 0X80071AC3 - Volume Corruption Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-high-cpu-demands-caused-by-wudfhost-in-windows-11-systems/"><u>Troubleshooting High CPU Demands Caused by WUDFHost in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-windows-11-error-0x8024401c-during-updates/"><u>Troubleshooting Steps for Windows 11 Error 0X8024401c During Updates</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlocking-solutions-what-to-do-when-your-iphone-freezes-up/"><u>Unlocking Solutions: What to Do When Your iPhone Freezes Up</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unravel-the-mysteries-of-color-grading-with-cs6cc-luts-for-2024/"><u>Unravel the Mysteries of Color Grading with CS6/CC LUTs for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-volume-key-issues-diagnose-and-repair-steps-for-better-sound-management/"><u>Windows 11 Volume Key Issues: Diagnose & Repair Steps for Better Sound Management</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->