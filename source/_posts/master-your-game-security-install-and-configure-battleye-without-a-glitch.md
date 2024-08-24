---
title: Master Your Game Security - Install and Configure BattlEye Without a Glitch
date: 2024-08-23T14:09:38.343Z
updated: 2024-08-24T14:09:38.343Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Master Your Game Security - Install and Configure BattlEye Without a Glitch
excerpt: This Article Describes Master Your Game Security - Install and Configure BattlEye Without a Glitch
thumbnail: https://thmb.techidaily.com/aea0b058dad5a8a78b7176f739897c106c85c82d6e617b0cdb68b3405d4743da.png
---

## LSA Safety Measures Fully Operational Again - Secure Your System Now

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-24.png)

Local Security Authority Protection is off

 No need to worry if your Local Security Authority Protection is toggled off: in most cases, it was a UI bug with a certain Windows update patch, meaning that it’s not off, just appears to be off, and you can install another update patch to get it fixed. In other rare cases, you can change your computer settings to get it enabled again. Read on and see how you can fix the Local Security Authority Protection being off problem.

## Try these fixes to enable the Local Security Authority Protection

 As mentioned, in most cases, your Local Security Authority is off because of a UI bug with a Windows patch, so the first method should be enough to help. If it doesn’t, please move on to methods 2 and 3.

1. **[Install Windows Update patch KB5007651](#m1)**
2. **[Modify Registry Editor](#m2)**
3. **[Configure Group Policy Editor](#m3)**

---

## 1\. Install Windows Update patch KB5007651

 The Local Security Authority Protection being off bug was actually a bug that shipped with Windows 11’s March 2023 mandatory security update, patch KB5007651\. Windows then released the updated version of this patch that fixed this problem. So if you still haven’t already, please update your Windows now for the latest patch KB5007651 to install.

To do so:

1. On your keyboard, hit the**Windows** key, then type**check for update** s, then click C**heck for updates** .  

![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-18.png)
2. Click**Check for updates** , and Windows will scan for any available updates.  
![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-19.png)
3. If there are available updates, Windows will automatically download them for you. Restart your computer for the update to take effect if needed.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-20.png)
4. If there are_no_ available updates, you’ll see**You’re up to date** like this.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-21.png)

Then see if the Local Security Authority Protection is still off.

 If so, please download the installation file for KB5007651 from[here](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5007651) , then double-click the installation file to get it installed.

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-25.png)

 If the “Local Security protection is off” notification is still there when you manually install the KB5007651 update, please move on to the next fix.

---

## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

 Then see if your Local Security Authority protection can be toggled back on.

---

## Bonus tip

 If turning on the Local Security Authority protection doesn’t help to fix your computer problems, you can always try to repair any damaged or corrupted system files, as**the integrity of Windows system files is** essential for proper operation and stability for your computer.

 Tools like **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  can automate the repair process by scanning system files and replacing corrupted ones.

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect. It will run a free scan of your PC and give you**a detailed report of your PC status** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-scan.jpg)
3. Once finished, you’ll see a report showing all the issues. To fix all the issues automatically, click**Start Repair** (You’ll need to purchase the full version. It comes with a**60-day Money-Back Guarantee** so you can refund anytime if Fortect doesn’t fix your problem).  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
 Fortect comes with a 60-day Money-Back Guarantee. If you’re not satisfied with Fortect, you can contact <support@fortect.com> for a full refund.

 Still unsure if Fortect is what you need? Check this [Fortec Review](https://tools.techidaily.com/drivereasy/download/) !

---

 The above is what we have to offer regarding “Local Security Authority protection is off” problem. If you have any other suggestions, please feel free to leave a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-guiding-principles-for-swapping-gender-on-instagram-facebook-and-snapchat-pics/"><u>[New] 2024 Approved  Guiding Principles for Swapping Gender on Instagram, Facebook & Snapchat Pics</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-tiktok-and-youtube-shorts-comparison-for-individual-social-media-users/"><u>[New] 2024 Approved  TikTok & YouTube Shorts Comparison for Individual Social Media Users</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-from-followers-to-fans-a-guide-to-thriving-instagram-presence/"><u>[New] In 2024, From Followers to Fans  A Guide to Thriving Instagram Presence</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-how-to-upload-gif-to-instagram-in-4-steps/"><u>[New] In 2024, How To Upload GIF to Instagram in 4 Steps</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-youtube-soundwaves-flow-into-imovie-effortlessly/"><u>[New] In 2024, YouTube Soundwaves Flow Into iMovie Effortlessly</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-streamline-screen-capturing-in-todays-remote-meetings/"><u>[Updated] 2024 Approved  Streamline Screen Capturing in Today’s Remote Meetings</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-a-step-by-step-guide-implementing-vimeo-end-cuts/"><u>[Updated] A Step-by-Step Guide  Implementing Vimeo End Cuts</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-best-look-ups-for-gopro-movies-select-15-luts/"><u>[Updated] Best Look-Ups for GoPro Movies  Select 15 LUTs</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-a-compreenasian-guide-to-obs-installation-on-apple-systems/"><u>[Updated] In 2024, A Compreenasian Guide to OBS Installation on Apple Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-10-ultimate-action-hunting-cameras-ranked/"><u>2024 Approved  10 Ultimate Action Hunting Cameras Ranked</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-jumping-from-sdr-to-hdr-the-ultimate-transformation-guide/"><u>2024 Approved  Jumping From SDR to HDR  The Ultimate Transformation Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-uncover-all-about-instagrams-video-cap/"><u>2024 Approved  Uncover All About Instagram's Video Cap</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/best-picks-for-powerful-and-user-friendly-twitter-client-applications/"><u>Best Picks for Powerful and User-Friendly Twitter Client Applications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-boosting-world-of-warcraft-speed-and-reducing-lag/"><u>Comprehensive Guide: Boosting World of Warcraft Speed & Reducing Lag</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209839104-csgo-crash-woes-heres-how-you-can-achieve-a-smooth-gaming-experience/"><u>CS:GO Crash Woes? Here's How You Can Achieve a Smooth Gaming Experience</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-steps-to-tackle-pcl-xl-setbacks/"><u>Effortless Steps to Tackle PCL XL Setbacks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhanced-navigation-tips-mastering-expandcollapse-menus-and-social-media-links-for-efficient-top-page-access/"><u>Enhanced Navigation Tips: Mastering Expand/Collapse Menus & Social Media Links for Efficient Top-Page Access</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eradicating-scam-alerts-solutions-for-google-chromes-fake-critical-error/"><u>Eradicating Scam Alerts: Solutions for Google Chrome's Fake Critical Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-requirement-compatible-with-directx-11-gpus-only-to-enable-engine-usage/"><u>Essential Requirement: Compatible with DirectX 11 GPUs Only to Enable Engine Usage</u></a></li>
<li><a href="https://win-howtos.techidaily.com/game-on-solving-your-origin-software-errors-for-an-uninterrupted-experience/"><u>Game On! Solving Your Origin Software Errors for an Uninterrupted Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-successfully-shutting-down-a-frozen-computer-running-windows-11-fixed/"><u>Guide to Successfully Shutting Down a Frozen Computer Running Windows 11 [FIXED]</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-realme-c67-5g-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Realme C67 5G?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-quickly-start-your-pc-addressing-windows-7-boot-latency-issues/"><u>How to Quickly Start Your PC: Addressing Windows 7 Boot Latency Issues</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-zte-nubia-flip-5g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your ZTE Nubia Flip 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-your-wacom-stylus-when-it-fails-to-work-on-windows-11-or-windows-10-systems/"><u>How to Repair Your Wacom Stylus When It Fails to Work on Windows 11 or Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-casting-functionality-on-windows-10-a-step-by-step-solution/"><u>How to Restore Casting Functionality on Windows 10 - A Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-when-your-computer-is-frozen-during-windows-setup/"><u>How to Troubleshoot When Your Computer Is Frozen During Windows Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mesothelioma-is-associated-with-asbestos-exposure-and-affects-the-pleura-rather-than-lung-parenchyma/"><u>Mesothelioma Is Associated with Asbestos Exposure and Affects the Pleura Rather than Lung Parenchyma.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reset-or-refresh-mastering-the-easy-ways-to-reboot-windows-10/"><u>Reset or Refresh? Mastering the Easy Ways to Reboot Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-device-not-found-error-code-24-on-windows-1087/"><u>Resolving 'Device Not Found' Error Code 24 on Windows 10/8/7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-elevated-cpu-consumption-troubleshooting-wudfhostexe-on-windows-11/"><u>Resolving Elevated CPU Consumption: Troubleshooting WUDFHost.exe on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/seamless-navigation-and-social-media-connectivity-on-your-website-dive-into-facebook-linkedin-and-youtube-integration/"><u>Seamless Navigation & Social Media Connectivity on Your Website - Dive Into Facebook, LinkedIn & YouTube Integration</u></a></li>
<li><a href="https://win-howtos.techidaily.com/securing-your-digital-footprint-rely-on-copernic-for-high-standard-data-retrieval-practices/"><u>Securing Your Digital Footprint: Rely on Copernic for High-Standard Data Retrieval Practices</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellar-solutions-for-qtp-corrections/"><u>Stellar Solutions for QTP Corrections</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-solving-minecrafts-troublesome-error-code-5/"><u>Step-by-Step Guide: Solving Minecraft’s Troublesome Error Code 5</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-best-web-based-video-editors-for-chrome-os/"><u>The Best Web-Based Video Editors for Chrome OS</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-14-pro-max-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue From Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-overcoming-slow-shutdown-woes-in-windows-11-systems/"><u>Troubleshooting and Overcoming Slow Shutdown Woes in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-non-responsive-shift-key/"><u>Troubleshooting Guide: Fixing a Non-Responsive Shift Key</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-overcoming-windows-10-build-1803-upgrade-failures/"><u>Troubleshooting Guide: Overcoming Windows 10 Build 1803 Upgrade Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missing-os-errors-on-your-computer-easy-fixes-and-best-practices/"><u>Troubleshooting Missing OS Errors on Your Computer - Easy Fixes and Best Practices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-the-failed-device-descriptor-request-on-usbs-guide/"><u>Troubleshooting Tips for the Failed Device Descriptor Request on USBs [Guide]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-11-issues-using-sfcdism-tools-a-comprehensive-guide/"><u>Troubleshooting Windows 11 Issues Using SFC/DISM Tools – A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-how-to-troubleshoot-and-repair-your-ps4-microphone/"><u>Ultimate Guide: How to Troubleshoot and Repair Your PS4 Microphone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-call-logs-from-150-2023-by-fonelab-android-recover-call-logs/"><u>Undelete lost call logs from 150 (2023)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-repairing-the-constant-usb-device-unrecognized-message/"><u>Understanding and Repairing the Constant 'USB Device Unrecognized' Message</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-svchostexe-navigating-netsvcs-and-addressing-excessive-network-consumption/"><u>Understanding svchost.exe: Navigating Netsvcs & Addressing Excessive Network Consumption</u></a></li>
<li><a href="https://extra-resources.techidaily.com/winning-at-love-one-swipe-at-a-time-top-tips-for-bold-biographies/"><u>Winning at Love, One Swipe at a Time  Top Tips for Bold Biographies</u></a></li>
</ul></div>
