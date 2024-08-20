---
title: Troubleshooting a Stalled Diagnostics Policy Service – Expert Advice
date: 2024-08-19T07:10:41.918Z
updated: 2024-08-20T07:10:41.918Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting a Stalled Diagnostics Policy Service – Expert Advice
excerpt: This Article Describes Troubleshooting a Stalled Diagnostics Policy Service – Expert Advice
thumbnail: https://thmb.techidaily.com/b65c1700fc3be6103fe73469bcdff9ebd5593034f3622d27aea03408c9719ceb.jpg
---

## Diagnostic Policy Service Malfunction? Here's the Solution

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

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
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-from-free-to-profitable-a-video-marketing-masterclass-for-vimeo/"><u>[New] 2024 Approved  From Free to Profitable  A Video Marketing Masterclass for Vimeo</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-supercharge-your-content-consumption-these-best-free-online-video-downloaders-for-youtube-shorts/"><u>[New] 2024 Approved  Supercharge Your Content Consumption  These Best Free, Online Video Downloaders for YouTube Shorts</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-the-best-mobile-recording-software-roundup/"><u>[New] In 2024, The Best Mobile Recording Software Roundup</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unmasking-the-top-10-clandestine-story-gurus-for-2024/"><u>[New] Unmasking the Top 10 Clandestine Story Gurus for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-harness-the-power-of-instagrams-hidden-features/"><u>[Updated] 2024 Approved  Harness the Power of Instagram's Hidden Features</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-the-right-approach-to-uploading-photos-from-your-device-to-snapchat/"><u>[Updated] 2024 Approved  The Right Approach to Uploading Photos From Your Device to Snapchat</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/5-solutions-for-nubia-z50-ultra-unlock-without-password-by-drfone-android/"><u>5 Solutions For Nubia Z50 Ultra Unlock Without Password</u></a></li>
<li><a href="https://article-files.techidaily.com/audio-tempo-control-gear-guide-mobile-pc-for-2024/"><u>Audio Tempo Control Gear Guide (Mobile, PC) for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/computer-boot-error-heres-how-to-fix-your-machine-when-it-wont-turn-on/"><u>Computer Boot Error? Here's How to Fix Your Machine When It Won't Turn On</u></a></li>
<li><a href="https://win-howtos.techidaily.com/definitive-solutions-for-fixing-the-perplexing-unknown-usb-and-failed-port-reset-challenges-on-windows-11-devices/"><u>Definitive Solutions for Fixing the Perplexing Unknown USB and Failed Port Reset Challenges on Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210209964-fixing-windows-installation-failed-fast-solutions/"><u>Fixing 'Windows Installation Failed' – Fast Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-circumventing-the-persistent-windows-10-0x800f0922-update-hurdle/"><u>Guide To Circumventing The Persistent Windows 10 0X800f0922 Update Hurdle</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-overcome-signal-loss-in-logitechs-g93-groove-headset/"><u>Guide to Overcome Signal Loss in Logitech's G93 Groove Headset</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hearthstone-performance-boost-effortless-lag-fixes/"><u>Hearthstone Performance Boost: Effortless Lag Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-handle-the-error-code-0x80070643-during-windows-updatesinstallations/"><u>How to Correctly Handle the Error Code 0X80070643 During Windows Updates/Installations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-bluetooth-disabled-issue/"><u>How To Fix Bluetooth Disabled Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-d3dx942dll-missing-or-not-found-errors/"><u>How to Fix d3dx9_42.dll Missing or Not Found Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-total-war-rome-remastered-game-crashing-issues-easily/"><u>How to Fix Total War: Rome Remastered Game Crashing Issues Easily</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-oneplus-11-5g-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From OnePlus 11 5G to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-13-withwithout-sim-card-by-drfone-ios/"><u>How to Unlock iPhone 13 with/without SIM Card</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-poco-x5-pro-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Poco X5 Pro?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-palette-excellence-editor/"><u>In 2024, Palette Excellence Editor</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-artists-ascent-a-guide-to-professional-growth-in-graphic-design/"><u>In 2024, The Artist's Ascent  A Guide to Professional Growth in Graphic Design</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-information-and-speculations-surrounding-the-new-sony-car-model-afeela/"><u>Inside Information and Speculations Surrounding the New Sony Car Model, Afeela</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202694347-kodi-buffering-solved-ensuring-continuous-and-stable-streams-every-time/"><u>Kodi Buffering Solved: Ensuring Continuous and Stable Streams Every Time</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-oculus-repair-strategies-to-tackle-errors-and-enhance-your-vr-experience/"><u>Mastering Oculus Repair Strategies to Tackle Errors and Enhance Your VR Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-technique-repair-methods-for-windows-startup-issues/"><u>Mastering the Technique: Repair Methods for Windows Startup Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-waiting-just-gameplay-in-fortnite/"><u>No More Waiting, Just Gameplay in Fortnite</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimize-and-accelerate-your-windows-7-systems-boot-speed/"><u>Optimize and Accelerate Your Windows 7 System's Boot Speed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/proper-techniques-for-addressing-msvcp140dll-lack/"><u>Proper Techniques for Addressing MSVCP140.dll Lack</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-for-dell-notebook-black-display-error-a-comprehveiw-guide/"><u>Quick Fix for Dell Notebook Black Display Error - A Comprehveiw [Guide]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211652366-quick-fixes-for-unresponsive-hp-laptop-keyboards-learn-how/"><u>Quick Fixes for Unresponsive HP Laptop Keyboards – Learn How</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-computers-stuck-at-windows-setup-a-step-by-step-guide/"><u>Resolve Your Computer's 'Stuck at Windows Setup': A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-insufficient-system-resources-errors-in-your-application/"><u>Resolved: Fixing 'Insufficient System Resources' Errors in Your Application</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-error-code-0x80072f8f-a-step-by-step-guide-for-windows-11-and-10-users/"><u>Resolving Error Code 0X80072F8F: A Step-by-Step Guide for Windows 11 & 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-minecraft-performance-issues-ultimate-guide/"><u>Resolving Minecraft Performance Issues: Ultimate Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-for-correcting-steams-unavailable-file-rights-issue/"><u>Solution Guide for Correcting Steam's Unavailable File Rights Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-shift-key-failure-expert-troubleshooting-tips/"><u>Solving 'Shift Key Failure': Expert Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-plugged-in-but-not-charging-problems-on-your-microsoft-surface/"><u>Solving Plugged In But Not Charging Problems on Your Microsoft Surface</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-windows-11s-malfunctioning-start-screen-interface/"><u>Step-by-Step Fix for Windows 11'S Malfunctioning Start Screen Interface</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-installing-the-latest-feature-update-on-windows-10-build-1607/"><u>Trouble Installing the Latest Feature Update on Windows 10 Build 1607</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-huion-tablet-issues-top-5-quick-solutions/"><u>Troubleshoot Huion Tablet Issues: Top 5 Quick Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-complete-standstill-in-windows-10-at-boot-time-a-guide-to-quick-fixes/"><u>Troubleshooting Complete Standstill in Windows 10 at Boot Time: A Guide to Quick Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-microsoft-print-to-pdf-issues-on-windows-10-and-11/"><u>Troubleshooting Microsoft Print to PDF Issues on Windows 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-responsive-prtscn-shortcut-in-microsofts-latest-operating-systems/"><u>Troubleshooting Non-Responsive PrtScn Shortcut in Microsoft's Latest Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-correcting-the-monitor-has-no-video-output-error/"><u>Troubleshooting Tips: Correcting the 'Monitor Has No Video Output' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-update-service-failures-quick-and-effective-fixes/"><u>Troubleshooting Windows Update Service Failures - Quick and Effective Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-fixing-total-war-rome-remastered-game-crashes/"><u>Ultimate Guide: Fixing Total War: Rome Remastered Game Crashes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-itel-p55-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Itel P55 Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-the-best-apps-for-recording-and-editing-reaction-videos-on-the-go-for-2024/"><u>Updated The Best Apps for Recording and Editing Reaction Videos on the Go for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-10-audio-issue-overcome-how-to-guide/"><u>Win 10 Audio Issue Overcome - How To Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-blue-screen-blues-heres-how-to-end-the-loop-of-unexpected-reboots/"><u>Windows 10 Blue Screen Blues? Here's How to End the Loop of Unexpected Reboots!</u></a></li>
</ul></div>
