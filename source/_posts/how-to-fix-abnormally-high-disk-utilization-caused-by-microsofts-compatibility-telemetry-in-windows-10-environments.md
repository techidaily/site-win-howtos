---
title: How to Fix Abnormally High Disk Utilization Caused by Microsoft's Compatibility Telemetry in Windows 10 Environments
date: 2024-08-15T11:33:06.717Z
updated: 2024-08-16T11:33:06.717Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Abnormally High Disk Utilization Caused by Microsoft's Compatibility Telemetry in Windows 10 Environments
excerpt: This Article Describes How to Fix Abnormally High Disk Utilization Caused by Microsoft's Compatibility Telemetry in Windows 10 Environments
thumbnail: https://thmb.techidaily.com/a018e8a9f0d428a05e6f8e5f431115fbc243ce5256805ecd4c390c919b578ebe.jpg
---

## Microsoft Compatibility Telemetry Eating Up Too Much Disk Space on Windows 10 – Solutions and Fixes Available Now

Does this look familiar?

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b61598e9c1bf.jpg)

 If the Microsoft Compatibility Telemetry process has recently started causing very high disk or high CPU usage on your Windows 10 system, it could be very frustrating. But there’s no need to panic – it’s usually easy to fix. You’ll learn 3 easy methods to troubleshoot the Microsoft Compatibility Telemetry high disk or high CPU problem.

## Try these fixes

 **Method 1:[ Using Group Policy Editor ](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 1. Using Group Policy Editor) Method 2:[ Using Registry Editor](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 2. Using Registry Editor)**
 **Method 3:[Updating your device drivers](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

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
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Method 2: Using Registry Editor

 1)On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->

2) T ype**regedit**  in the box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a22807d2e.png)

 3) Click **YES**  when prompted by User Account Control.

 4) Go to **HKEY\_LOCAL\_MACHINE** \> **SOFTWARE** \>**Policies** \>**Microsoft** \>**Windows** \>**DataCollection.**

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a4ede532e.jpg)

 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->

**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Set**Value date** to **0** (zero) and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
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

 3) Click the **Update**  button next toany flagged driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money back guarantee. You’ll be prompted to upgrade when you click Update All.)

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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-essential-tips-to-avoid-obs-framing-errors/"><u>[New] 2024 Approved  Essential Tips to Avoid OBS Framing Errors</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-insights-into-premier-video-communication-tools-on-devices-for-2024/"><u>[New] Insights Into Premier Video Communication Tools on Devices for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-optimizing-playback-speed-with-professional-tactics/"><u>[Updated] In 2024, Optimizing Playback Speed with Professional Tactics</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-making-a-bold-statement-adding-neon-borders-to-youtubes/"><u>[Updated] Making a Bold Statement  Adding Neon Borders to YouTubes</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-2023-fb-live-stream-mp4-conversion-tool/"><u>2024 Approved  2023 FB Live Stream MP4 Conversion Tool</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-hdr-lighting-insight-does-it-merit-creation/"><u>2024 Approved  HDR Lighting Insight  Does It Merit Creation?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-memimagic-create-funny-images-on-the-go/"><u>2024 Approved  MemiMagic  Create Funny Images On-the-Go</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-balancing-act-creative-freedom-vs-major-company-support/"><u>2024 Approved  The Balancing Act  Creative Freedom vs Major Company Support</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-efficient-ways-to-turn-off-tiktok-audio-while-watching-videos/"><u>2024 Approved Efficient Ways to Turn Off TikTok Audio While Watching Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-and-repairing-game-set-up-mistakes-in-origin-titles-a-guide/"><u>Addressing and Repairing Game Set-Up Mistakes in Origin Titles - A Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-windows-update-issue-easy-solutions-to-correct-error-0x8024200d/"><u>Beat Windows Update Issue: Easy Solutions to Correct Error 0X8024200D</u></a></li>
<li><a href="https://win-answers.techidaily.com/complete-fix-tutorial-for-among-us-endless-loading-problems/"><u>Complete Fix Tutorial for 'Among Us' Endless Loading Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-overcome-livekernelevent-error-code-117/"><u>Comprehensive Guide: Overcome LiveKernelEvent Error Code 117</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/cutting-edge-image-editors-for-text-addition/"><u>Cutting-Edge Image Editors for Text Addition</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decoding-telegram-insights-into-this-global-chatting-platform/"><u>Decoding Telegram: Insights Into This Global Chatting Platform</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202724713-dell-laptop-keyboard-issues-here-are-effective-fixes/"><u>Dell Laptop Keyboard Issues? Here Are Effective Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dll-not-found-microsoft-c-runtime-error/"><u>DLL Not Found: Microsoft C Runtime Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-ways-to-tackle-and-fix-the-window-11-black-display-issue/"><u>Effective Ways to Tackle and Fix the Window 11 Black Display Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x80072f8f-expert-guide-to-resolving-it-on-windows-11-and-10/"><u>Error Code 0X80072f8f: Expert Guide to Resolving It on Windows 11 & 10</u></a></li>
<li><a href="https://fox-access.techidaily.com/fine-tuning-your-videos-shape-with-aspect-ratio/"><u>Fine-Tuning Your Video's Shape with Aspect Ratio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-problem-uncontrollable-repeated-mouse-clicks/"><u>Fixed Problem: Uncontrollable Repeated Mouse Clicks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-valorants-gameplay-issues-a-guide-to-eliminating-screen-tearing/"><u>Fixing Valorant's Gameplay Issues: A Guide to Eliminating Screen Tearing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-11s-low-memory-error-a-comprehensive-guide/"><u>Fixing Windows 11'S Low Memory Error: A Comprehensive Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/forgot-your-y100a-lock-screen-pattern-pin-or-password-here-s-what-to-do-by-drfone-android-unlock-android-unlock/"><u>Forgot your Y100A lock screen pattern, PIN or password? Here’s what to do</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-overcoming-failed-installation-of-windows-11-v1607-update/"><u>Guide to Overcoming Failed Installation of Windows 11 v1607 Update</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-vivo-v27e-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-no-playable-sources-detected-error-when-launching-apps-in-windows/"><u>How to Fix 'No Playable Sources Detected' Error When Launching Apps in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-samsung-galaxy-a24-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-vcruntime140dll-missing-file-issue-easy-guide/"><u>How to Fix VCRUNTIME140.dll Missing File Issue - Easy Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-memes-unleashed-ranking-the-best-templates-10/"><u>In 2024, Memes Unleashed  Ranking the Best Templates #10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/latest-fixes-for-the-device-cant-cast-with-miracast-problem/"><u>Latest Fixes for the 'Device Can't Cast With Miracast' Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-fix-step-by-step-strategy-to-correctly-handle-d3dx9tbd-error/"><u>Master the Fix: Step-by-Step Strategy to Correctly Handle D3dx9_tbd Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-nier-automata-on-your-computer-overcome-stutter-and-lag-problems-today/"><u>Mastering Nier: Automata on Your Computer - Overcome Stutter and Lag Problems Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-for-port-reset-failed-errors-in-windows-10-when-connecting-usb-devices/"><u>Mastering the Fix for 'Port Reset Failed' Errors in Windows 10 When Connecting USB Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-pause-on-progress-clearing-up-windows-update-error-code-0x80070002/"><u>No More Pause on Progress: Clearing Up Windows Update Error Code 0X80070002</u></a></li>
<li><a href="https://win-solutions.techidaily.com/overcoming-launch-problems-with-origin-app-in-windows-11-solutions-unveiled/"><u>Overcoming Launch Problems with Origin App in Windows 11 – Solutions Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-0x80070091-error-when-performing-a-system-restore-on-windows-10-solution/"><u>Overcoming the 0X80070091 Error When Performing a System Restore on Windows 10 [Solution]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/recovering-missing-bluetooth-icons-on-windows-10-devices-for-seamless-connectivity/"><u>Recovering Missing Bluetooth Icons on Windows 10 Devices for Seamless Connectivity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-access-denied-error-troubleshooting-failed-temp-folder-execution-and-setup-interruption/"><u>Resolve 'Access Denied' Error: Troubleshooting Failed Temp Folder Execution and Setup Interruption</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-n11-touchpad-scrolling-malfunctions-a-step-by-step-guide/"><u>Resolving Windows N11 Touchpad Scrolling Malfunctions: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restored-voice-clarity-in-discord/"><u>Restored Voice Clarity in Discord</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-gameplay-cured-dxgidll-in-pubg/"><u>Reviving Gameplay: Cured Dxgi.dll in PUBG</u></a></li>
<li><a href="https://win-howtos.techidaily.com/securing-trustinstaller-approval-your-guide-to-file-modification-authorization/"><u>Securing TrustInstaller Approval: Your Guide to File Modification Authorization</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-tricks-for-improving-delayed-keyboard-reaction-times/"><u>Simple Tricks for Improving Delayed Keyboard Reaction Times</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-added-tap-response-to-htc-display/"><u>SOLVED: Added Tap Response to HTC Display</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-troubleshooting-eradicating-fatal-glitches-from-call-of-duty-black-ops-4/"><u>Step-by-Step Troubleshooting: Eradicating Fatal Glitches From Call of Duty: Black Ops 4</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/the-art-of-sharing-online-videos-from-youtube-to-facebook-for-2024/"><u>The Art of Sharing Online Videos From YouTube to Facebook for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-5-methods-for-voice-activated-management-of-chatgpt/"><u>Top 5 Methods for Voice-Activated Management of ChatGPT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-laptop-mousepads-for-windows-systems-fixes-for-win11win8win7/"><u>Troubleshooting Laptop Mousepads for Windows Systems: Fixes for Win11/Win8/Win7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unsupported-monitor-incompatibility-with-latest-video-signal-standard/"><u>Unsupported Monitor: Incompatibility with Latest Video Signal Standard</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-2024-approved-easy-tutorial-how-to-record-and-send-talking-emoji-for-iphone/"><u>Updated 2024 Approved Easy Tutorial How to Record and Send Talking Emoji for iPhone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-isnt-the-classic-shortcut-key-combo-work-troubleshooting-steps-inside/"><u>Why Isn't the Classic Shortcut Key Combo Work? Troubleshooting Steps Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-10-audio-issue-resolution-steps-revealed/"><u>Win 10 Audio Issue Resolution Steps Revealed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/windows-10-ultimate-screen-capture-tool-for-2024/"><u>Windows 10  Ultimate Screen Capture Tool for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-media-playback-errors-solved-correcting-missing-source-issues-efficiently/"><u>Windows Media Playback Errors Solved: Correcting Missing Source Issues Efficiently</u></a></li>
</ul></div>
