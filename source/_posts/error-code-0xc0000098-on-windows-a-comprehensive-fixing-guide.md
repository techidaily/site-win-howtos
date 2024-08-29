---
title: "Error Code 0XC0000098 on Windows: A Comprehensive Fixing Guide"
date: 2024-08-28T00:33:37.629Z
updated: 2024-08-29T00:33:37.629Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 0XC0000098 on Windows: A Comprehensive Fixing Guide"
excerpt: "This Article Describes Error Code 0XC0000098 on Windows: A Comprehensive Fixing Guide"
thumbnail: https://thmb.techidaily.com/4d7dde3a99efac5f6bdb879d88148e0d5b48fb1025ad045c8786c79687920a30.jpg
---

## Fixing Error 1068 in Windows: A Comprehensive Guide - SOLUTION FOUND

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Right-click**Dhcp** under the Services section to select**Export** .  
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

### Solution 3: Update your network adapter driver

 This problem could be also due to**a corrupted, old or missing network driver** on your system. So you can solve it through updating your network driver.

 Updating drivers require Internet connection on your computer. If your computer can’t access the wireless network, try to connect your computer to a wired network connection or, you can try the[Offline Scan](https://tools.techidaily.com/drivereasy/download/) feature of Driver Easy.

You can update your network driver either manually or automatically.

#### Manual driver update

 You can update your network driver manually by going to the manufacturer’s website for your network adapter, say,**Realtek** , and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

#### Automatic driver update

 If you don’t have the time, patience or computer skills to update your network driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly.

 You can click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the Pro version which comes with**full support** and a**30-day money back guarantee** . You’ll be prompted to upgrade when you click Update All.)  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b891580f3aca.jpg)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
You’re done. Feel free to comment below if you have any question.

* [error](https://tools.techidaily.com/drivereasy/download/)
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
<li><a href="https://win-howtos.techidaily.com/alert-msvcr120dll-absent-in-win1110/"><u>[ALERT] MSVCR120.dll Absent in Win11/10</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-a-comparative-analysis-androids-finest-video-downloaders/"><u>[New] A Comparative Analysis  Android's Finest Video Downloaders</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-explore-creativity-best-drawing-software-for-ipados/"><u>[New] Explore Creativity  Best Drawing Software for iPadOS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-effortless-guide-to-secure-and-free-youtube-music-downloads/"><u>[New] In 2024, Effortless Guide to Secure and Free YouTube Music Downloads</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-perfecting-your-podcast-name-strategies-and-ideas/"><u>[New] Perfecting Your Podcast Name  Strategies and Ideas</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-uncover-collective-media-on-messenger-networks/"><u>[Updated] 2024 Approved  Uncover Collective Media on Messenger Networks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-aerial-drone-transformation-trial-with-first-20-free-lutts/"><u>[Updated] Aerial Drone Transformation - Trial with First 20 FREE LUTTs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-discover-10-amazing-world-wanderlust-channels-for-2024/"><u>[Updated] Discover 10 Amazing World Wanderlust Channels for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-premiere-cinematic-glimpses-series/"><u>[Updated] Premiere Cinematic Glimpses Series</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-the-final-word-on-powerdirector-a-complete-review-for-2024/"><u>[Updated] The Final Word on PowerDirector  A Complete Review for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-expert-tips-for-effortless-ipodcast-downloads-on-iphone/"><u>2024 Approved  Expert Tips for Effortless IPodcast Downloads on iPhone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-navigating-google-translate-for-superior-speech-to-text/"><u>2024 Approved  Navigating Google Translate for Superior Speech-to-Text</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-selecting-the-right-video-recorder-for-teaching/"><u>2024 Approved  Selecting the Right Video Recorder for Teaching</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-streaming-showdown-is-streamlabs-or-obs-your-best-choice/"><u>2024 Approved  Streaming Showdown  Is Streamlabs or OBS Your Best Choice?</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-television-or-projector-for-peak-4k-performance/"><u>2024 Approved  Television or Projector for Peak 4K Performance?</u></a></li>
<li><a href="https://facebook.techidaily.com/a-heavy-investment-in-wordsmiths-fbs-strategic-5m-plan-against-substacks-rise/"><u>A Heavy Investment in Wordsmiths: FB's Strategic $5M Plan Against Substack’s Rise</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ace-your-pcs-stability-addressing-and-solving-the-vcruntime140dll-error-problem/"><u>Ace Your PC's Stability: Addressing and Solving the VCRUNTIME140.dll Error Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/application-stalls-due-to-dll-absence/"><u>Application Stalls Due to DLL Absence</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-huion-pen-problems-instantly-the-ultimate-5-step-guide-to-restoration/"><u>Bypass Huion Pen Problems Instantly: The Ultimate 5-Step Guide to Restoration</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/chromebook-video-editing-made-easy-top-android-apps/"><u>Chromebook Video Editing Made Easy Top Android Apps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-and-defeating-the-werfaultexe-error-in-windows-a-comprehensive-guide/"><u>Decoding and Defeating the werFault.exe Error in Windows - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-your-streams-with-ease-overcoming-twitch-error-4000/"><u>Diagnosing and Repairing Your Streams with Ease: Overcoming Twitch Error 4000</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diuril-ibuprofen-and-lipitor-in-that-order/"><u>Diuril, Ibuprofen, and Lipitor in that Order</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-resolving-the-life-threatening-videodxgkrnl-error-on-pcs-running-windows/"><u>Easy Fixes for Resolving the Life-Threatening Video_Dxgkrnl Error on PCs Running Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-a-quick-and-smooth-windows-10-power-down/"><u>Effective Solutions for a Quick and Smooth Windows 10 Power Down</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elevate-the-experience-top-accessories-for-phantom-4-drone/"><u>Elevate the Experience  Top Accessories for Phantom 4 Drone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/elevate-your-scroll-wheel-game/"><u>Elevate Your Scroll Wheel Game</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elevating-your-videography-through-audio-storytelling/"><u>Elevating Your Videography Through Audio Storytelling</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0x80071ac3-volume-is-dirty/"><u>Error 0X80071AC3: Volume Is Dirty</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x887a0006-a-step-by-step-guide-to-troubleshooting-and-resolution/"><u>Error Code 0X887A0006: A Step-by-Step Guide to Troubleshooting and Resolution</u></a></li>
<li><a href="https://fox-http.techidaily.com/exploring-asmrs-positive-impact-on-mental-health/"><u>Exploring ASMR’s Positive Impact on Mental Health</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-vcruntime1dle140dll-cannot-find-error-on-windows-step-by-step-solutions/"><u>Fixing the 'VCRUNTIME1ˈdle'140.dll Cannot Find Error on Windows: Step-by-Step Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-annoying-screen-tremor-on-your-windows-10-pc/"><u>Fixing the Annoying Screen Tremor on Your Windows 10 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-intel-realsense-technology-not-active-on-windows-10/"><u>Fixing the Issue: Intel RealSense Technology Not Active on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-and-correct-unsupported-command-errors-on-lcdled-displays/"><u>How to Address and Correct Unsupported Command Errors on LCD/LED Displays</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-the-soft-bricked-vivo-s18e-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Vivo S18e? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-reactivate-the-illumination-feature-on-a-malfunctioning-corsair-keyboard/"><u>How to Reactivate the Illumination Feature on a Malfunctioning Corsair Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-and-resolve-audio-glitches-on-youtube-with-windows-10-patches/"><u>How to Repair and Resolve Audio Glitches on YouTube with Windows 10 Patches</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/how-to-guide-elevating-gameplay-recordings-via-obs-for-2024/"><u>How-To Guide  Elevating Gameplay Recordings via OBS for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-best-free-apple-iphone-13-pro-imei-checker-by-drfone-ios/"><u>In 2024, Best Free Apple iPhone 13 Pro IMEI Checker</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-editcanvas-solutions/"><u>In 2024, EditCanvas Solutions</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-say-goodbye-to-watermarks-the-best-free-video-editing-software/"><u>In 2024, Say Goodbye to Watermarks The Best Free Video Editing Software</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/keep-your-shorts-viewer-friendly-fixing-image-absence-for-2024/"><u>Keep Your Shorts Viewer-Friendly  Fixing Image Absence for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210124096-laptop-keyboard-malfunction-heres-what-you-can-do-to-fix-it/"><u>Laptop Keyboard Malfunction? Here's What You Can Do To Fix It!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-pad-not-responding-get-it-up-and-running-on-your-pc-again/"><u>Lenovo Pad Not Responding? Get It Up & Running on Your PC Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-smooth-gameplay-expert-advice-on-solving-lags-in-pubg/"><u>Master Smooth Gameplay: Expert Advice on Solving Lags in PUBG!</u></a></li>
<li><a href="https://common-error.techidaily.com/mastery-in-correcting-error-0x887a0006-speedy-fixes-unveiled-here/"><u>Mastery in Correcting Error 0X887A0006 - Speedy Fixes Unveiled Here</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-darkness-in-gaming-solutions-for-obsgamecapture-screen-glitches/"><u>Overcoming Darkness in Gaming: Solutions for ObsGameCapture Screen Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-remote-server-connection-failures-effective-troubleshooting-techniques/"><u>Overcoming Remote Server Connection Failures: Effective Troubleshooting Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/remedy-for-missed-additional-monitor-win11/"><u>Remedy for Missed Additional Monitor (Win11)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/repaired-amd-directx-error/"><u>Repaired AMD DirectX Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-lag-issues-ultimate-guide-to-enhance-your-minecraft-performance/"><u>Resolve Your Lag Issues: Ultimate Guide to Enhance Your Minecraft Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-critical-failure-in-directx-system-detailed-analysis/"><u>Resolved: Critical Failure in DirectX System - Detailed Analysis</u></a></li>
<li><a href="https://extra-tips.techidaily.com/seconds-to-enjoy-a-look-at-20mb-video-files/"><u>Seconds to Enjoy - A Look at 20MB Video Files</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-the-opengl32dll-file-not-present-issue-a-step-by-step-guide/"><u>Solving the OpenGL32.dll File Not Present Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-repairing-malfunctioning-windows-update-processes-in-windows-10/"><u>Step-by-Step Guide: Repairing Malfunctioning Windows Update Processes in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-fixing-your-non-functional-usb-to-hdmi-converter/"><u>Troubleshooting Tips: Fixing Your Non-Functional USB-to-HDMI Converter</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-0x80070643-update-failures-expert-solutions/"><u>Troubleshooting Windows 0X80070#643 Update Failures - Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-repairing-the-startup-error-code-0xc000007b-for-smooth-running-applications/"><u>Understanding And Repairing The Startup Error Code 0xC000007b For Smooth Running Applications</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-and-utilizing-chatgpt-plugins/"><u>Understanding and Utilizing ChatGPT Plugins</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-the-mystery-behind-access-denied-to-device-path-or-file-in-windows-os/"><u>Unlocking the Mystery Behind 'Access Denied to Device Path or File' In Windows OS</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/windows-10-kernel-error-resolved-fixing-the-kernal-security-check-issue/"><u>Windows 10 Kernel Error Resolved: Fixing the 'Kernal Security Check' Issue</u></a></li>
</ul></div>
