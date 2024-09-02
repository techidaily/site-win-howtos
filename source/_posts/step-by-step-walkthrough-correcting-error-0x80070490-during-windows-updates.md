---
title: "Step-by-Step Walkthrough: Correcting Error 0X80070490 During Windows Updates"
date: 2024-09-01T04:52:43.198Z
updated: 2024-09-02T04:52:43.198Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Walkthrough: Correcting Error 0X80070490 During Windows Updates"
excerpt: "This Article Describes Step-by-Step Walkthrough: Correcting Error 0X80070490 During Windows Updates"
thumbnail: https://thmb.techidaily.com/114b6bfca9f928095e8da2f7f3417492afac50bf37b6d4d36fe64b43b43e9aea.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

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
<li><a href="https://extra-hints.techidaily.com/new-breathing-life-into-your-ig-story-text-with-animation/"><u>[New] Breathing Life Into Your IG Story Text with Animation</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-cyber-celebrity-surge-2024/"><u>[New] Cyber Celebrity Surge 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/iy-templates-for-affordable-youtube-intros/"><u>[New] DIY Templates for Affordable YouTube Intros</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-perfectly-smooth-window-snap-tool/"><u>[New] In 2024, Perfectly Smooth Window Snap Tool</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-next-gen-homes-in-minecraft-top-6-concepts-for-2024/"><u>[New] Next-Gen Homes in Minecraft  Top 6 Concepts for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-quick-fix-guide-repair-and-enhance-your-iphoneipadmacs-airdrop/"><u>[New] Quick-Fix Guide  Repair and Enhance Your iPhone/iPad/Mac's AirDrop</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-top-5-psone-emulators-perfect-play-on-your-pc/"><u>[New] Top 5 PsOne Emulators  Perfect Play on Your PC</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-ultimate-guide-top-free-youtube-video-openers/"><u>[New] Ultimate Guide  Top Free YouTube Video Openers</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-mac-users-guide-the-full-spectrum-of-screenflow-pro/"><u>[Updated] 2024 Approved  Mac Users Guide  The Full Spectrum of ScreenFlow Pro</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-building-a-cohesive-tiktok-ending-spectacle/"><u>[Updated] Building a Cohesive TikTok Ending Spectacle</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-ideas-for-creating-sequences-of-iphone-burst-images/"><u>[Updated] In 2024, Ideas for Creating Sequences of iPhone Burst Images</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-sky-high-savings-the-least-expensive-drones-on-market/"><u>[Updated] Sky-High Savings  The Least Expensive Drones on Market</u></a></li>
<li><a href="https://win-howtos.techidaily.com/application-failure-due-to-missing-dll/"><u>Application Failure Due to Missing DLL</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/beyond-the-surface-10-under-the-radar-facts-about-reels-for-2024/"><u>Beyond the Surface  10 Under-the-Radar Facts About Reels for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corsair-keyboard-lighting-problem-heres-how-to-get-those-lights-back/"><u>Corsair Keyboard Lighting Problem? Here’s How to Get Those Lights Back!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205369662-cursor-blues-discover-simple-solutions-to-end-the-annoying-blinking/"><u>Cursor Blues? Discover Simple Solutions to End the Annoying Blinking</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/decoding-the-differences-between-amazon-echo-pop-and-echo-dot/"><u>Decoding the Differences Between Amazon Echo Pop and Echo Dot</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203787743-dell-laptop-keyboard-malfunction-heres-what-you-can-do/"><u>Dell Laptop Keyboard Malfunction? Here's What You Can Do!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosis-and-repair-of-electricity-overloads-in-network-connection-port-areas/"><u>Diagnosis & Repair of Electricity Overloads in Network Connection Port Areas</u></a></li>
<li><a href="https://fox-access.techidaily.com/discovering-best-steadicams-for-enhanced-dslr-shooting-experience/"><u>Discovering Best Steadicams for Enhanced DSLR Shooting Experience</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/dissecting-godfall-for-playstation-5-the-promising-debut-that-ends-in-narrative-confusion/"><u>Dissecting Godfall for PlayStation 5 - The Promising Debut that Ends in Narrative Confusion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-user-profile-service-failed-sign-in-glitches-on-windows-1011-systems/"><u>Effective Solutions for 'User Profile Service Failed' Sign-In Glitches on Windows 10/11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eliminating-aw-snap-crashes-effective-fixes-for-google-chrome-users/"><u>Eliminating Aw, Snap! Crashes: Effective Fixes for Google Chrome Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolution-tactics-restarting-your-computer-after-critical-failures/"><u>Error Resolution Tactics: Restarting Your Computer After Critical Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-0x80070490-error-codes-for-seamless-windows-update-experience/"><u>Fixing 0X80070490 Error Codes for Seamless Windows Update Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-of-non-functional-internet-explorer-on-your-pc/"><u>Fixing the Issue of Non-Functional Internet Explorer on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-of-unidentified-usb-gadget-with-descriptor-query-failure/"><u>Fixing the Issue of Unidentified USB Gadget with Descriptor Query Failure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-how-to-overcome-windows-camera-error-0xa00f4292/"><u>Fixing the Issue: How to Overcome Windows Camera Error 0xA00F4292</u></a></li>
<li><a href="https://screen-recording.techidaily.com/gameplay-narratives-6-compelling-ways-to-document-your-virtual-worlds-for-2024/"><u>Gameplay Narratives  6 Compelling Ways to Document Your Virtual Worlds for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/geforce-experience-setup-glitch-solved-retrieve-your-custom-configurations-now/"><u>GeForce Experience Setup Glitch Solved - Retrieve Your Custom Configurations Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-bringing-an-hidden-or-missing-window-back-onto-the-screen/"><u>Guide: Bringing an Hidden or Missing Window Back Onto the Screen</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-tecno-spark-20c-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Tecno Spark 20C Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-svchostexe-causing-high-cpu-use-on-your-windows-11-pc/"><u>How to Fix svchost.exe Causing High CPU Use on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-usb-device-not-detected-issue-once-and-for-all/"><u>How to Fix the 'USB Device Not Detected' Issue Once and For All</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-flashlight-from-apple-iphone-se-2020-lock-screen-by-drfone-ios/"><u>How To Remove Flashlight From Apple iPhone SE (2020) Lock Screen</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Vivo S18 Pro? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-i-screen-mirroring-apple-iphone-14-to-tvlaptop-drfone-by-drfone-ios/"><u>In 2024, How Can I Screen Mirroring Apple iPhone 14 to TV/Laptop? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-samsung-galaxy-a05s-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Samsung Galaxy A05s?</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-sharefake-gps-on-uber-for-nokia-xr21-drfone-by-drfone-virtual-android/"><u>In 2024, How to share/fake gps on Uber for Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-vivo-y27-4g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Vivo Y27 4G Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-realme-c67-4g-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Realme C67 4G Device</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/in-depth-analysis-of-nintendo-switch-top-pick-for-on-the-go-gamers/"><u>In-Depth Analysis of Nintendo Switch - Top Pick for On-the-Go Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-dx11-and-wwe-2k-battlegrounds-level-100-functionality-glitches/"><u>Overcoming DX11 and WWE 2K: Battlegrounds Level 10.0 Functionality Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-calculator-precedence-on-windows-systems/"><u>Preserving Calculator Precedence on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-compatibility-woes-a-guide-to-correcting-unknown-usb-device-failed-communication-problems/"><u>Resolving Compatibility Woes: A Guide to Correcting 'Unknown USB Device (Failed Communication)' Problems</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-windows-issues-steps-to-remove-amd-drivers-successfully/"><u>Resolving Windows Issues: Steps to Remove AMD Drivers Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-logitech-mouse-battery/"><u>Reviving Your Logitech Mouse Battery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guidelines-resolving-unresponsive-computer-shutdown-in-windows-11-systems/"><u>Solution Guidelines: Resolving Unresponsive Computer Shutdown in Windows 11 Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solve-counter-strike-audio-problems-mic-malfunction-resolved/"><u>Solve Counter-Strike Audio Problems: Mic Malfunction Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-of-microsoft-update-failure-a-guide-to-overcoming-error-code-0x8024a105/"><u>Solving the Mystery of Microsoft Update Failure: A Guide to Overcoming Error Code 0X8024a105</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-persistent-common-dll-has-stopped-working-in-windows-systems/"><u>Solving the Persistent 'Common Dll Has Stopped Working' In Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fix-your-rotated-laptop-monitor/"><u>Step-by-Step Guide to Fix Your Rotated Laptop Monitor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-malfunctioning-microphone-in-windows-11-systems/"><u>Step-by-Step Solution for Malfunctioning Microphone in Windows 11 Systems</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ultimate-guide-to-the-google-pixel-4a-smartphone-simplified/"><u>The Ultimate Guide to the Google Pixel 4a – Smartphone Simplified</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-8-solutions-to-overcome-windows-11-error-0x800f0922-during-updates/"><u>Top 8 Solutions to Overcome Windows 11 Error 0X800f0922 During Updates</u></a></li>
<li><a href="https://games-able.techidaily.com/top-tier-gaming-setup-with-modular-keyboard-akkos-mod007b/"><u>Top-Tier Gaming Setup with Modular Keyboard - Akko's MOD007B</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-0x80070490-error-during-windows-update-process/"><u>Troubleshooting and Fixing 0X80070490 Error During Windows Update Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-successfully-repairing-windows-component-configuration-failures/"><u>Troubleshooting Guide: Successfully Repairing Windows Component Configuration Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-nonfunctional-spacebar-keys-on-windows-10-pcs/"><u>Troubleshooting Nonfunctional Spacebar Keys on Windows 10 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-how-to-repair-an-unresponsive-aoc-monitor-on-windows-11/"><u>Troubleshooting Steps: How to Repair an Unresponsive AOC Monitor on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fixes-overcoming-the-0x800705b4-hurdle-in-windows-11s-patching-process/"><u>Ultimate Fixes: Overcoming the 0X800705b4 Hurdle in Windows 11'S Patching Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-airpods-connection-issues-on-windows-10-and-11/"><u>Ultimate Guide: Resolving AirPods Connection Issues on Windows 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-taskbar-visibility-issues-heres-how-to-solve-them/"><u>Windows 10 Taskbar Visibility Issues? Here's How to Solve Them</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->