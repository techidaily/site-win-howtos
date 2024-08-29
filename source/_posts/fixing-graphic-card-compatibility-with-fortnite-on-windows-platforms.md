---
title: Fixing Graphic Card Compatibility with Fortnite on Windows Platforms
date: 2024-08-28T00:38:09.001Z
updated: 2024-08-29T00:38:09.001Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing Graphic Card Compatibility with Fortnite on Windows Platforms
excerpt: This Article Describes Fixing Graphic Card Compatibility with Fortnite on Windows Platforms
thumbnail: https://thmb.techidaily.com/a8a2eae7840110809ce01981ae6ddd7381e7680b0d93e29805eecd4b92108f79.jpg
---

## Microsoft Compatibility Telemetry Eating Up Too Much Disk Space on Windows 10 – Solutions and Fixes Available Now

Does this look familiar?

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b61598e9c1bf.jpg)

 If the Microsoft Compatibility Telemetry process has recently started causing very high disk or high CPU usage on your Windows 10 system, it could be very frustrating. But there’s no need to panic – it’s usually easy to fix. You’ll learn 3 easy methods to troubleshoot the Microsoft Compatibility Telemetry high disk or high CPU problem.

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

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279c6c18122.png)

`
` `
` `
` `
` `
`

 4) Double-click**Allow Telemetry** .

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

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Method 2: Using Registry Editor

 1)On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) T ype**regedit**  in the box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a22807d2e.png)

 3) Click **YES**  when prompted by User Account Control.

 4) Go to **HKEY\_LOCAL\_MACHINE** \> **SOFTWARE** \>**Policies** \>**Microsoft** \>**Windows** \>**DataCollection.**

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a4ede532e.jpg)

 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
 6) Set**Value date** to **0** (zero) and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Method 3: Update your device drivers

 If, after trying the above, the issue still exists or your PC is still running slow, it’s time to update your device drivers.

 There are two ways you can get the right drivers for all your devices:  
 manually or automatically.

**Manual driver update** – You can update your drivers manually by going to the manufacturer’s website for your devices, and searching for the most recent correct driver for each. Be sure to choose only drivers that are compatible with your variant of Windows 10.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for your devices, and your variant of Windows 10, and it will download and install them correctly :

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae696a52856.jpg)

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the **Update**  button next toany flagged driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money back guarantee. You’ll be prompted to upgrade when you click Update All.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae6a0c3f690.jpg)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-the-compreenas-for-snapchat-success-stories/"><u>[New] 2024 Approved  The Compreenas for SnapChat Success Stories</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-top-10-youtube-video-grabber-apps-best-in-class-compatibility/"><u>[Updated] 2024 Approved  Top 10 YouTube Video Grabber Apps, Best-in-Class Compatibility</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-decode-instagram-visibility-whos-glancing-at-yours/"><u>2024 Approved  Decode Instagram Visibility  Who's Glancing at Yours?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-step-by-step-guide-pcmobile-save-meetings/"><u>2024 Approved  Step-by-Step Guide  PC/Mobile Save Meetings</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/a-comprehensive-guide-to-apple-iphone-8-plus-blacklist-removal-tips-and-tools-drfone-by-drfone-ios/"><u>A Comprehensive Guide to Apple iPhone 8 Plus Blacklist Removal Tips and Tools | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-the-blues-with-these-8-strategies-for-correcting-windows-10-update-error-code-0x800f0922/"><u>Beat the Blues with These 8 Strategies for Correcting Windows 10 Update Error Code 0X800F0922</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-windows-error-0xc0000098-heres-how-you-can-fix-it/"><u>Dealing with Windows Error 0Xc0000098? Here's How You Can Fix It</u></a></li>
<li><a href="https://tech-haven.techidaily.com/designing-future-web-services-with-ai-assistance-from-chatgpt/"><u>Designing Future Web Services with AI Assistance From ChatGPT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/determined-no-driver-affirms-opengl-use/"><u>Determined: No Driver Affirms OpenGL Use</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-the-common-d3de-error-not-available-problem/"><u>Diagnosing and Fixing the Common D3DE ERROR: Not Available Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-fixes-restoring-functionality-to-a-broken-dell-wireless-keyboard/"><u>DIY Fixes: Restoring Functionality to a Broken Dell Wireless Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-surface-tablets-that-wont-charge-while-plugged-in/"><u>Effective Fixes for Surface Tablets That Won't Charge While Plugged In</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-the-persistent-windows-10-failed-to-download-updates-problem-error-code-0xc1900208/"><u>Effective Fixes for the Persistent 'Windows 10 Failed to Download Updates' Problem (Error Code 0Xc1900208)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-download-issues-during-steam-platform-updates/"><u>Effective Solutions for Download Issues During Steam Platform Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortlessly-solve-the-bluetooth-disappearance-problem-in-windows-11-expert-advice/"><u>Effortlessly Solve the Bluetooth Disappearance Problem in Windows 11 - Expert Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-restoring-copy-and-paste-capabilities-in-windows-11-systems/"><u>Expert Guide: Restoring Copy & Paste Capabilities in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-invisible-mouse-icon-on-windows-11-without-breaking-a-sweat/"><u>Fix Your Invisible Mouse Icon on Windows 11 Without Breaking a Sweat!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-connection-unsecured-warning-in-firefox-easy-solutions/"><u>Fixing 'Connection Unsecured' Warning in Firefox: Easy Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-10-kb4019919-installation-issue-resolve-error-code-0x80240034/"><u>Fixing the Windows 10 KB4019919 Installation Issue - Resolve Error Code 0X80240034</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-diagnose-and-fix-rpc-communication-failures-in-your-windows-system/"><u>How to Diagnose and Fix RPC Communication Failures in Your Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-elevated-cpu-use-by-svchost-process-in-windows-10/"><u>How to Fix Elevated CPU Use by Svchost Process in Windows 10</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-14-plus-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 14 Plus System Issues? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-mic-functionality-on-your-steelseries-arctis-5-headset-easy-fix-tips-for-gamers/"><u>How to Restore Mic Functionality on Your SteelSeries Arctis 5 Headset - Easy Fix Tips for Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-fixes-for-unresponsive-lenovo-f-key-issues/"><u>Immediate Fixes for Unresponsive Lenovo F-Key Issues</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-15-pro-apples-new-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 15 Pro, Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-art-of-amplifying-popularity-on-youtube/"><u>In 2024, The Art of Amplifying Popularity on YouTube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/key-specification-for-game-engine-launch-ensure-you-have-a-d3d1n-supported-gpu-installed/"><u>Key Specification for Game Engine Launch: Ensure You Have a D3D1n-Supported GPU Installed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-fix-of-error-0x8024401c-on-windows-update-for-users-of-windows-10-and-11-systems/"><u>Master the Fix of Error 0X8024401c on Windows Update for Users of Windows 10 and 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/microsoft-store-opening-troubleshooting-successful-fixes-revealed/"><u>Microsoft Store Opening Troubleshooting: Successful Fixes Revealed</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915240817-navigating-the-big-four-facebook-twitter-instagram-and-youtube-strategies/"><u>Navigating the Big Four: Facebook, Twitter, Instagram & YouTube Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-performance-fixing-high-resource-demand-from-wudfhostexe-on-windows-11/"><u>Optimizing Performance: Fixing High Resource Demand From WUDFHost.exe on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-device-driver-issues-in-world-of-warcraft-successful-update-and-compatibility-guide/"><u>Overcome Device Driver Issues in World of Warcraft - Successful Update and Compatibility Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-d3dxx939dll-missing-error-a-step-by-step-repair-manual-for-windows-users/"><u>Overcoming the d3dxx9_39.dll Missing Error: A Step-by-Step Repair Manual for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reboot-anomalies-in-win10-environment/"><u>Reboot Anomalies in Win10 Environment</u></a></li>
<li><a href="https://os-tips.techidaily.com/regain-access-3-straightforward-techniques-for-retrieving-deleted-photos-on-ios-devices/"><u>Regain Access: 3 Straightforward Techniques for Retrieving Deleted Photos on iOS Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-disconnected-network-cable-issues-on-your-windows-pc/"><u>Resolve Disconnected Network Cable Issues on Your Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207629009-resolving-audio-glitches-speaker-issues-on-windows-operating-systems-solved/"><u>Resolving Audio Glitches: Speaker Issues on Windows Operating Systems Solved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-eliminating-slow-response-times-from-your-windows-11-keyboard/"><u>Solution Found: Eliminating Slow Response Times From Your Windows 11 Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-overcoming-issues-with-uninstalling-windows-10-updates/"><u>Solution Guide: Overcoming Issues with Uninstalling Windows 10 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-limited-memory-issues-fixing-command-cannot-be-processed-due-to-inadequate-storage/"><u>Solve Limited Memory Issues: Fixing 'Command Cannot Be Processed Due to Inadequate Storage'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210599306-solving-error-code-224003-now-your-video-plays-smoothly/"><u>Solving 'Error Code 224003': Now Your Video Plays Smoothly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-ps4-mic-problems-top-fixes-for-a-quiet-console/"><u>Solving PS4 Mic Problems: Top Fixes For A Quiet Console</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-laptops-endless-boot-loop-problem/"><u>Solving Your Laptop's Endless Boot Loop Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-to-correct-the-darkness-defeating-windows-11-black-screen-glitches/"><u>Step-by-Step Solutions to Correct the Darkness: Defeating Windows 11 Black Screen Glitches</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-best-way-to-keep-your-system-chilled-an-in-depth-look-at-the-havit-5-laptop-cooling-pad/"><u>The Best Way to Keep Your System Chilled: An In-Depth Look at the HAVIT #5 Laptop Cooling Pad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-stickynon-functioning-keys-on-hp-laptops-a-step-by-step-guide/"><u>Troubleshoot Sticky/Non-Functioning Keys on HP Laptops: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-deal-with-excessive-energy-on-a-hub-connection/"><u>Troubleshooting Guide: How to Deal with Excessive Energy on a Hub Connection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/updated-reactivate-the-local-user-account-verification-mechanism/"><u>Updated: Reactivate the Local User Account Verification Mechanism</u></a></li>
<li><a href="https://win-howtos.techidaily.com/xbox-one-audio-woes-discover-how-to-restore-headset-functionality-today/"><u>Xbox One Audio Woes? Discover How to Restore Headset Functionality Today</u></a></li>
</ul></div>
