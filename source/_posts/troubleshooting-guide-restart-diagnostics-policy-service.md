---
title: "Troubleshooting Guide: Restart Diagnostics Policy Service"
date: 2024-08-19T07:03:21.693Z
updated: 2024-08-20T07:03:21.693Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: Restart Diagnostics Policy Service"
excerpt: "This Article Describes Troubleshooting Guide: Restart Diagnostics Policy Service"
thumbnail: https://thmb.techidaily.com/2df34b659b3c29b9db007fd6c1ae27a91d6916d58493c3cf7366c1e2985a1403.jpg
---

## Resolving Your System's Diagnostics Policy Service Problem Today

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<li><a href="https://win-howtos.techidaily.com/fixed-monster-hunter-world-pc-disconnect-problem/"><u>[Fixed] Monster Hunter World PC Disconnect Problem</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-a-comprehensive-walkthrough-setting-up-your-first-wirecast-livestream-to-youtube/"><u>[New] 2024 Approved  A Comprehensive Walkthrough  Setting Up Your First WireCast Livestream to Youtube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-memorable-narratives-in-book-videos/"><u>[New] In 2024, Memorable Narratives in Book Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-transform-your-live-broadcasting-skills-using-dslr-on-personal-computers/"><u>[New] Transform Your Live Broadcasting Skills Using DSLR on Personal Computers</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-top-5-hidden-media-extractor-apps/"><u>[Updated] 2024 Approved  Top 5 Hidden Media Extractor Apps</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-wiping-your-discord-servers-from-pc-and-android-devices/"><u>[Updated] 2024 Approved  Wiping Your Discord Servers From PC and Android Devices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expert-advice-for-staying-copyright-compliant-online/"><u>[Updated] Expert Advice for Staying Copyright Compliant Online</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-flip-photo-trail-on-fb-3-techniques-explored/"><u>[Updated] In 2024, Flip Photo Trail on FB - 3 Techniques Explored</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-streamlining-revenue-with-youtubes-mobile-monetization-features-for-creators/"><u>[Updated] Streamlining Revenue with YouTube's Mobile Monetization Features for Creators</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-synchronizing-sound-to-pixels-online/"><u>[Updated] Synchronizing Sound to Pixels Online</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-a-step-by-step-approach-to-incorporating-luts-in-obs-studio-projects/"><u>2024 Approved  A Step-by-Step Approach to Incorporating LUTs in OBS Studio Projects</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-the-complete-guide-to-mastering-games-with-kinemaster-android/"><u>2024 Approved  The Complete Guide to Mastering Games with KineMaster Android</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-blockade-a-step-by-step-guide-to-solve-windows-10-couldnt-be-installed-error-code-aturality-80240020/"><u>Bypassing the Blockade: A Step-by-Step Guide to Solve Windows 10 Couldn't Be Installed - Error Code Aturality | 80240020</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-oneplus-open-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on OnePlus Open.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/could-the-loss-of-d3d-devices-kill-unreal/"><u>Could the Loss of D3D Devices Kill Unreal?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/curing-csgos-crash-problems-with-these-swift-and-straightforward-fixes/"><u>Curing CSGO's Crash Problems with These Swift and Straightforward Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-invalid-input-alerts-on-your-visual-interface-device/"><u>Dealing with Invalid Input Alerts on Your Visual Interface Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decode-usb-trouble-overcome-unknown-usb-device-descr-request-failed-quickly/"><u>Decode USB Trouble: Overcome 'Unknown USB Device (Descr.) Request Failed' Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-rectifying-problematic-fn-keys-on-an-asus-notebook-system/"><u>Diagnosing and Rectifying Problematic Fn Keys on an ASUS Notebook System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-unable-to-launch-correctly-error-handling-0xc0031/"><u>Diagnosing and Repairing 'Unable to Launch Correctly' Error – Handling 0xC00^31</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208396498-disregarded-sd-card-dont-despair-solutions-await/"><u>Disregarded SD Card, Don't Despair! Solutions Await!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-prevent-and-resolve-csgo-system-crashes/"><u>Easy Steps to Prevent and Resolve CS:GO System Crashes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/engaging-content-the-ultimate-6-video-strategies/"><u>Engaging Content  The Ultimate 6 Video Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhancing-link-quality-between-epson-devices/"><u>Enhancing Link Quality Between Epson Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-how-to-resolve-a-stuck-white-or-black-screen-on-your-laptop/"><u>Expert Guide: How to Resolve a Stuck White or Black Screen on Your Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-issues-with-d3d-driver-setup-and-activation-a-comprehensive-guide/"><u>Fixing Issues with D3D Driver Setup and Activation: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-blackout-solutions-for-obs-recording-glitches-in-games/"><u>Fixing the Blackout - Solutions for OBS Recording Glitches in Games</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-11-update-issue-guide-through-the-0x800705b4-error/"><u>Fixing the Windows 11 Update Issue: Guide Through the 0X800705B4 Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-your-astro-a40-microphone-issues-easy-troubleshooting-steps/"><u>Fixing Your Astro A40 Microphone Issues: Easy Troubleshooting Steps</u></a></li>
<li><a href="https://some-techniques.techidaily.com/grasping-fcp-obtain-it-at-no-cost-for-2024/"><u>Grasping FCP  Obtain It at No Cost for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/guide-to-streamline-yt-playlist-integration-in-htmlcss/"><u>Guide to Streamline YT Playlist Integration in HTML/CSS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-ce-34878-0-error-code-on-your-playstation-4-a-comprehensive-guide/"><u>How to Fix the CE-34878-0 Error Code on Your PlayStation 4: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-lost-invisible-desktop-windows-back/"><u>How To Get Your Lost, Invisible Desktop Windows Back!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-nintendo-switchs-microphone-working-again-professional-repair-techniques/"><u>How To Get Your Nintendo Switch's Microphone Working Again: Professional Repair Techniques</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-blade-a73-5g-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from Blade A73 5G.</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-12-pro-passcode-without-computer-drfone-by-drfone-ios/"><u>How to Unlock iPhone 12 Pro Passcode without Computer? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Nokia C12 Plus? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-no-smudges-on-screens-keeping-your-gopro-crisp/"><u>In 2024, No Smudges on Screens  Keeping Your GoPro Crisp</u></a></li>
<li><a href="https://win-howtos.techidaily.com/insider-tips-conquering-the-complete-darkness-screens-on-startup-of-mhw/"><u>Insider Tips: Conquering the Complete Darkness Screens on Startup of MHW</u></a></li>
<li><a href="https://windows11.techidaily.com/lightweight-window-navigators-ram-usage-tested-and-rated/"><u>Lightweight Window Navigators: Ram Usage Tested and Rated</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-meet-the-top-lego-stop-motion-talent/"><u>New 2024 Approved Meet the Top Lego Stop Motion Talent</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-exploring-the-magic-of-ai-selfie-generators/"><u>New Exploring the Magic of AI Selfie Generators</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pdf-printer-problems-quick-fixes-for-immediate-relief/"><u>PDF Printer Problems: Quick Fixes for Immediate Relief</u></a></li>
<li><a href="https://win-howtos.techidaily.com/program-termination-requested/"><u>Program Termination Requested</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211775888-pubg-2024-master-the-art-of-fixing-game-launch-issues-and-start-enjoying-now/"><u>PUBG 2024: Master the Art of Fixing Game Launch Issues and Start Enjoying Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208936142-pubg-game-update-all-structures-now-function-correctly-no-more-missing-buildings/"><u>PUBG Game Update: All Structures Now Function Correctly – No More Missing Buildings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/realtek-driver-trouble-discover-how-to-restore-missing-controller-detection/"><u>Realtek Driver Trouble? Discover How to Restore Missing Controller Detection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-youtube-audio-rendering-issue-in-windows-10-a-step-by-step-guide/"><u>Resolving the YouTube Audio Rendering Issue in Windows 10 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tips-for-troubleshooting-frequent-usb-disconnections/"><u>Step-by-Step Tips for Troubleshooting Frequent USB Disconnections</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-a-non-responsive-huion-pen-with-these-five-effective-tips/"><u>Troubleshoot a Non-Responsive Huion Pen with These Five Effective Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-optimize-your-computer-addressing-the-low-on-memory-warning-on-windows-10/"><u>Troubleshoot and Optimize Your Computer: Addressing the Low on Memory Warning on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-keyboard-fixing-non-working-directional-buttons/"><u>Troubleshoot Your Keyboard: Fixing Non-Working Directional Buttons</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolve-unknown-usb-device-descriptor-request-failure-issues-easily/"><u>Troubleshooting Guide: Resolve 'Unknown USB Device - Descriptor Request Failure' Issues Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-responsive-keyboards-in-windows-10-solutions-and-tips/"><u>Troubleshooting Non-Responsive Keyboards in Windows 10: Solutions and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-dealing-with-hanging-windows-10-interfaces/"><u>Troubleshooting Tips for Dealing with Hanging Windows 10 Interfaces</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-when-you-cant-use-internet-explorer-anymore/"><u>Troubleshooting Tips When You Can’t Use Internet Explorer Anymore</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-resolving-a-warframe-update-failure-fix-your-game/"><u>Troubleshooting Tips: Resolving a 'Warframe Update Failure' - Fix Your Game</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207576089-uncover-your-missing-wi-fi-adapter-choices-in-windows-11-now-solved/"><u>Uncover Your Missing Wi-Fi Adapter Choices in Windows 11 - Now Solved!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-claude-pro-a-comparative-analysis-with-microsofts-chatgpt-plus/"><u>Understanding Claude Pro: A Comparative Analysis with Microsoft's ChatGPT Plus</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-best-free-video-hosting-services-for-online-storage-and-sharing/"><u>Updated 2024 Approved Best Free Video Hosting Services for Online Storage and Sharing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/warframe-update-issues-troubleshooting-failed-installation-errors/"><u>Warframe Update Issues - Troubleshooting Failed Installation Errors</u></a></li>
</ul></div>
