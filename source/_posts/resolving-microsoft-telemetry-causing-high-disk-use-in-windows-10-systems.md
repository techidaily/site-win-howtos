---
title: Resolving Microsoft Telemetry Causing High Disk Use in Windows 10 Systems
date: 2024-08-19T07:01:54.411Z
updated: 2024-08-20T07:01:54.411Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Microsoft Telemetry Causing High Disk Use in Windows 10 Systems
excerpt: This Article Describes Resolving Microsoft Telemetry Causing High Disk Use in Windows 10 Systems
thumbnail: https://thmb.techidaily.com/6a865e452463a91a0991eeba9d7367cf47a6e9f955045ec39458749fd03f02a9.jpg
---

## Microsoft Compatibility Telemetry Eating Up Too Much Disk Space on Windows 10 – Solutions and Fixes Available Now

Does this look familiar?

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b61598e9c1bf.jpg)

 If the Microsoft Compatibility Telemetry process has recently started causing very high disk or high CPU usage on your Windows 10 system, it could be very frustrating. But there’s no need to panic – it’s usually easy to fix. You’ll learn 3 easy methods to troubleshoot the Microsoft Compatibility Telemetry high disk or high CPU problem.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Try these fixes

 **Method 1:[ Using Group Policy Editor ](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 1. Using Group Policy Editor) Method 2:[ Using Registry Editor](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 2. Using Registry Editor)**
 **Method 3:[Updating your device drivers](https://tools.techidaily.com/drivereasy/download/)**

### Method 1: Using Group Policy Editor

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) Type **gpedit.msc**  and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279bde5ee8d.png)

**Note:**  If you cannot find gpedit.msc on your Windows 10,[here is the method to got it.](https://tools.techidaily.com/drivereasy/download/)
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``
 3) Go to **Computer Configuration** \> **Administrative** **Templates** \>**Windows Components** \> **Data Collection and Preview Builds** .

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279c6c18122.png)

`
` `
` `
` `
` `
`

 4) Double-click**Allow Telemetry** .

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279cc82eec5.jpg)

`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``

 5) Select **Disabled** , then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279d1cdc304.jpg)

 6) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.  
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` `` `
` `
` `
` `
` `
` `
` `
` `
` `
`

### Method 2: Using Registry Editor

 1)On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) T ype**regedit**  in the box and click **OK** .

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a22807d2e.png)

 3) Click **YES**  when prompted by User Account Control.

 4) Go to **HKEY\_LOCAL\_MACHINE** \> **SOFTWARE** \>**Policies** \>**Microsoft** \>**Windows** \>**DataCollection.**

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a4ede532e.jpg)

 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)

**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)

 6) Set**Value date** to **0** (zero) and click**OK** .

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

### Method 3: Update your device drivers

 If, after trying the above, the issue still exists or your PC is still running slow, it’s time to update your device drivers.

 There are two ways you can get the right drivers for all your devices:  
 manually or automatically.

**Manual driver update** – You can update your drivers manually by going to the manufacturer’s website for your devices, and searching for the most recent correct driver for each. Be sure to choose only drivers that are compatible with your variant of Windows 10.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for your devices, and your variant of Windows 10, and it will download and install them correctly :

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae696a52856.jpg)

 3) Click the **Update**  button next toany flagged driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money back guarantee. You’ll be prompted to upgrade when you click Update All.)

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae6a0c3f690.jpg)

4) Reboot your Windows 10 PC.

5) On your keyboard, press the **Ctrl**  +**Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

 **Note:** If you can’t find gpedit.msc on your Windows 10 computer, here’s how you can get it: 1\. Download gpedit.msc(Group Policy Editor) from Internet  
 2\. When it’s done, Go to C:\\Windows\\SysWOW64, and copy the followings:  
 folders: GroupPolicy  
 GroupPolicyUsers  
 gpedit.msc(console document)  
 3\. Paste them in the following locations:  
 C:\\Windows\\System  
 C:\\Windows\\System32

 Hopefully this article could help you fix the problem. Feel free to comment below with your own experiences.

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-pro-stock-market-strategies-in-yt-reviews/"><u>[New] 2024 Approved  Pro Stock Market Strategies in YT Reviews</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-cross-promotion-mastery-sharing-igtv-to-fb/"><u>[New] Cross-Promotion Mastery  Sharing IGTV to FB</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-insta-velocity-strategic-use-of-likes-and-videos-for-growth/"><u>[New] Insta Velocity  Strategic Use of Likes & Videos for Growth</u></a></li>
<li><a href="https://win-howtos.techidaily.com/post-system-stabilizes-post-gameplay/"><u>[POST] System Stabilizes Post-Gameplay</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-what-is-svchostexe-netsvcs-and-fix-its-high-network-usage-issue/"><u>[Solved] What Is svchost.exe (Netsvcs) and Fix Its High Network Usage Issue</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-diversifying-from-googles-ar-enhancements/"><u>2024 Approved  Diversifying From Google's AR Enhancements</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-the-runtime-library-fiasco-a-users-manual-for-overcoming-error-0xc00000e9-in-windows/"><u>Beat the Runtime Library Fiasco: A User's Manual for Overcoming Error 0xC00000E9 in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-hurdle-a-step-by-step-guide-to-resolve-error-0x80072f8f-in-windows-1110/"><u>Bypassing the Hurdle: A Step-by-Step Guide to Resolve Error 0X80072F8F in Windows 11/10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203390423-dell-laptop-fn-key-problem-heres-how-to-get-it-working-again/"><u>Dell Laptop Fn-Key Problem? Here’s How to Get It Working Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-fixes-for-malfunctioning-system-components-in-windows-11-pcs/"><u>Efficient Fixes for Malfunctioning System Components in Windows 11 PCs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elite-cameras-for-pixel-perfect-stop-motion/"><u>Elite Cameras for Pixel-Perfect Stop Motion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-handling-and-correcting-critical-directx-error-situations/"><u>Expert Tips on Handling and Correcting Critical DirectX Error Situations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-persistent-windows-update-issue-error-0x8024002e-successfully/"><u>Fixing the Persistent Windows Update Issue (Error 0X8024002e) Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-10s-0x80072efd-error-step-by-step-guide/"><u>Fixing Windows 10'S 0X80072EFD Error: Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-aoc-monitor-to-work-again-on-a-windows-10-system-expert-tips-and-fixes/"><u>Getting Your AOC Monitor to Work Again on a Windows 10 System: Expert Tips and Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-open-apps-using-your-systems-default-admin-profile/"><u>How To Successfully Open Apps Using Your System's Default Admin Profile</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-14-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone 14 Plus without iTunes? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/how-to-zoom-inout-in-instagram-stories/"><u>How to Zoom In/Out in Instagram Stories</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-gratuitous-green-backdrops-available/"><u>In 2024, Gratuitous Green Backdrops Available</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-display-repair-how-to-solve-the-persistent-white-screen-problem/"><u>Laptop Display Repair: How to Solve the Persistent White Screen Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-pubg-effective-strategies-to-combat-and-prevent-game-lags/"><u>Mastering PUBG: Effective Strategies to Combat and Prevent Game Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-your-system-addressing-the-audio-device-graphs-impact-on-cpu-load-in-windows/"><u>Optimizing Your System: Addressing the Audio Device Graph's Impact on CPU Load in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-the-obstacle-of-error-code-80240020-your-guide-to-a-smooth-windows-11-upgrade/"><u>Overcome the Obstacle of Error Code 80240020 – Your Guide to a Smooth Windows 11 Upgrade</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-frozen-windows-10-updates-a-step-by-step-fix-guide/"><u>Overcoming Frozen Windows 10 Updates: A Step-by-Step Fix Guide</u></a></li>
<li><a href="https://driver-install.techidaily.com/revive-your-system-amd-driver-update-for-various-windows-oss/"><u>Revive Your System: AMD Driver Update for Various Windows OSs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-windows-11-touchscreen-top-5-solutions/"><u>Reviving Your Windows 11 Touchscreen: Top 5 Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-device-wont-charge-despite-being-plugged-into-a-windows-710-system/"><u>Solving the Issue: Device Won't Charge Despite Being Plugged Into a Windows 7/10 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speed-unleashed-discover-how-this-gadget-achieves-lightning-fast-performance/"><u>Speed Unleashed: Discover How This Gadget Achieves Lightning-Fast Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-for-activating-bluetooth-connectivity-in-windows-11-and-10/"><u>Step-by-Step Tutorial for Activating Bluetooth Connectivity in Windows 11 & 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-fixes-and-tips-for-overcoming-error-1603-fatal-installation-issue/"><u>Successful Fixes & Tips for Overcoming Error 1603 - Fatal Installation Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-definitive-solution-for-fixing-non-running-audio-services-on-windows-7-pcs/"><u>The Definitive Solution for Fixing Non-Running Audio Services on Windows 7 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-restoring-icon-clarity-on-your-pcs-desktop/"><u>Tips for Restoring Icon Clarity on Your PC's Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-altplustab-windows-switching-problems/"><u>Troubleshooting Guide: Resolving Alt+Tab Windows Switching Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-loud-playstation-4-consoles-what-to-do/"><u>Troubleshooting Loud PlayStation 4 Consoles - What to Do?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-computers-fail-to-detect-audio-devices/"><u>Troubleshooting Steps When Computers Fail to Detect Audio Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-your-bootstrapper-keeps-crashing-on-startup/"><u>Troubleshooting Steps When Your Bootstrapper Keeps Crashing on Startup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-strategies-resolve-unknown-usb-device-and-port-reset-errors-on-windows-10/"><u>Troubleshooting Strategies: Resolve 'Unknown USB Device' And Port Reset Errors on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210807114-usb-tethering-on-windows-10-easily/"><u>USB Tethering on Windows 10 Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-1011-missing-visual-settings/"><u>Windows 10/11: Missing Visual Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-stuck-heres-how-you-can-get-your-computer-to-properly-power-off/"><u>Windows 11 Stuck? Here's How You Can Get Your Computer to Properly Power Off</u></a></li>
</ul></div>
