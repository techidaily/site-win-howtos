---
title: Troubleshooting 'Desktop Not Available' Error in Windows System Profile
date: 2024-08-19T07:53:40.686Z
updated: 2024-08-20T07:53:40.686Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting 'Desktop Not Available' Error in Windows System Profile
excerpt: This Article Describes Troubleshooting 'Desktop Not Available' Error in Windows System Profile
thumbnail: https://thmb.techidaily.com/a6ef7d238dd7bb214a3984e4799089ad86b5e4b6f433cd32ec9f580258b7206c.jpg
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-unveiling-the-secrets-to-captioning-stories-and-reels/"><u>[New] 2024 Approved  Unveiling the Secrets to Captioning Stories and Reels</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-lead-the-way-in-streaming-your-guide-to-youtubes-full-sphere-video-trends/"><u>[New] Lead the Way in Streaming  Your Guide to YouTube's Full-Sphere Video Trends</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-low-profile-youtubing-broadcasting-without-a-huge-sublist/"><u>[New] Low Profile YouTubing  Broadcasting without a Huge Sublist</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-ultimate-selection-economical-hd-action-recordings/"><u>[New] Ultimate Selection  Economical HD Action Recordings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-what-is-svchostexe-netsvcs-and-fix-its-high-network-usage-issue/"><u>[Solved] What Is svchost.exe (Netsvcs) and Fix Its High Network Usage Issue</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-add-and-record-audio-to-powerpoint/"><u>[Updated] How to Add & Record Audio to PowerPoint</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-affordable-easy-to-use-video-capture-tools-for-windows/"><u>[Updated] In 2024, Affordable, Easy-to-Use Video Capture Tools for Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-investigating-changes-over-time-in-windows-movie-maker/"><u>2024 Approved  Investigating Changes Over Time in Windows Movie Maker</u></a></li>
<li><a href="https://win-howtos.techidaily.com/banish-troublesome-glitches-proven-methods-to-correct-0x80072efd-mishaps-on-your-windows-11-machine/"><u>Banish Troublesome Glitches: Proven Methods to Correct 0X80072EFD Mishaps on Your Windows 11 Machine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-address-fatal-installation-error-understanding-error-1603/"><u>Effective Solutions to Address Fatal Installation Error: Understanding Error 1603</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-techniques-to-repair-camera-not-working-on-a-lenovo-device/"><u>Effective Techniques to Repair Camera Not Working on a Lenovo Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-fixes-for-malfunctioning-system-components-in-windows-11-pcs/"><u>Efficient Fixes for Malfunctioning System Components in Windows 11 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-handling-and-correcting-critical-directx-error-situations/"><u>Expert Tips on Handling and Correcting Critical DirectX Error Situations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-unresponsive-file-explorer-problem-in-windows-10-step-by-step-solution/"><u>Fixing the Unresponsive File Explorer Problem in Windows 10 - Step by Step Solution</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-basic-to-breakthrough-a-youtube-live-thumbnail-journey-for-2024/"><u>From Basic to Breakthrough  A YouTube Live Thumbnail Journey for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-ethernet-not-working-issues-on-windows-11-and-7/"><u>How to Fix Ethernet Not Working Issues on Windows 11 & 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-open-apps-using-your-systems-default-admin-profile/"><u>How To Successfully Open Apps Using Your System's Default Admin Profile</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-13-pro-max-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 13 Pro Max to the Latest iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-motorola-moto-g04-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Motorola Moto G04 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-nokiawithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Nokiawith/without a PC</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-make-the-most-of-your-apple-iphone-11-pro-max-lock-screen-with-notifications-by-drfone-ios/"><u>In 2024, How to Make the Most of Your Apple iPhone 11 Pro Max Lock Screen with Notifications?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-keyboard-malfunction-heres-how-you-can-resolve-it/"><u>Lenovo Keyboard Malfunction? Here's How You Can Resolve It!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-touchpad-navigation-resolve-stuckunresponsive-scroll-wheel-issues/"><u>Mastering Touchpad Navigation: Resolve Stuck/Unresponsive Scroll Wheel Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-non-responsive-file-explorer-on-windows-10/"><u>Quick Fixes for Non-Responsive File Explorer on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-cpu-consumption-caused-by-wudfhostexe-on-windows-10-systems/"><u>Resolve Excessive CPU Consumption Caused by wudfhost.exe on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixes-for-unresponsive-google-chrome-browser-issues/"><u>Resolved: Fixes for Unresponsive Google Chrome Browser Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-connectivity-problems-your-guide-to-making-bluetooth-keyboards-work-with-pcs/"><u>Solving Connectivity Problems: Your Guide to Making Bluetooth Keyboards Work with PCs</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-a-windows-11-system-update/"><u>Step-by-Step Guide: Removing a Windows 11 System Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-for-activating-bluetooth-connectivity-in-windows-11-and-10/"><u>Step-by-Step Tutorial for Activating Bluetooth Connectivity in Windows 11 & 10</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-oppo-a78-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Oppo A78 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://article-helps.techidaily.com/top-5-best-monitors-for-playstation5-for-2024/"><u>Top 5 Best Monitors for PlayStation5 for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-keyboard-delay-issues-in-windows-10-effective-solutions-applied/"><u>Troubleshooting Keyboard Delay Issues in Windows 10: Effective Solutions Applied</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-computers-fail-to-detect-audio-devices/"><u>Troubleshooting Steps When Computers Fail to Detect Audio Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-your-bootstrapper-keeps-crashing-on-startup/"><u>Troubleshooting Steps When Your Bootstrapper Keeps Crashing on Startup</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ultimate-guide-to-cost-free-high-quality-slo-mo-photography-tools/"><u>Ultimate Guide to Cost-Free, High-Quality Slo-Mo Photography Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unfreezing-stuck-windows-update-on-win7-resolution-guide-helpful-tips/"><u>Unfreezing Stuck Windows Update on Win7 - Resolution Guide (Helpful Tips)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-hidden-how-to-find-missing-wi-fi-networks-in-windows-11/"><u>Unveiling the Hidden: How to Find Missing Wi-Fi Networks in Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-alternative-video-editing-software-to-powerdirector-for-mobile/"><u>Updated 2024 Approved Alternative Video Editing Software to PowerDirector for Mobile</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210807114-usb-tethering-on-windows-10-easily/"><u>USB Tethering on Windows 10 Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-1011-missing-visual-settings/"><u>Windows 10/11: Missing Visual Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-stuck-heres-how-you-can-get-your-computer-to-properly-power-off/"><u>Windows 11 Stuck? Here's How You Can Get Your Computer to Properly Power Off</u></a></li>
<li><a href="https://win-howtos.techidaily.com/yac539-yamahaaturbosound-ii-sound-module-based-on-the-ymf768ymu768-dsp-plus-midi-synthesizer-plus-codec-and-128-mb-of-spiram-for-sample-storage-instead-of-r145/"><u>YAC539 - Yamaha'aturboSound II Sound Module Based on the YMF768/YMU768 (DSP + MIDI Synthesizer + Codec) and 128 MB of SPIRAM for Sample Storage Instead of ROM. It Also Includes a Second Audio Input Connector</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->