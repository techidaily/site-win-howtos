---
title: Diagnosing and Fixing svchost.exe's Heavy Data Transfer in Windows Systems
date: 2024-08-19T06:14:41.252Z
updated: 2024-08-20T06:14:41.252Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Fixing svchost.exe's Heavy Data Transfer in Windows Systems
excerpt: This Article Describes Diagnosing and Fixing svchost.exe's Heavy Data Transfer in Windows Systems
thumbnail: https://thmb.techidaily.com/97bc8f701c5a50640871957d35ec4f8e16308c84bcc3926e5048675a7dfb62d5.png
---

## Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7be8093704.jpg)

 Your computer startup very slow? or you cannot log in Windows on your computer with the standard user account? After you log in with an administrative account, you’re seeing an error saying:

**Failed to connect to a windows services**
  
 **Windows could not connect to the System Event Notification Service service.**

 I know you’re likely frustrating. But don’t worry. Usually it’s easy to solve out. Read on to see how…

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## Try these fixes

 The methods below have helped other users solve the problem. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. **[Check the setting of System Event Notification Service on your computer](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset your Winsock Catalog](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your video card driver](https://tools.techidaily.com/drivereasy/download/)**
4. **[Uninstall the KB2952664 update](https://tools.techidaily.com/drivereasy/download/)**
5. [**Remove klhkum.dll**](https://tools.techidaily.com/drivereasy/download/)

 The following screenshots are from Windows 10\. But you can also follow the steps if you’re having the problem on Windows 7.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
### Fix 1: Check the setting of System Event Notification Service on your computer

 You may have the problem due to the incorrect setting of System Event Notification Service.  
 Follow these steps to modify the setting:

1. On your keyboard, hold down the**Windows logo key** and**R** to invoke the Run box.
2. Type**services.msc** and press**Enter** .  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf596c06c.jpg)
3. Right-click**System Event Notification Service** , then select**Restart** . If Restart grayed out, click**Start** instead.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf9e2c9b8.jpg)
4. Right-click System Event Notification Service again, this time select**Properties** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bfcea31f4.jpg)
5. Set the**Startup type** to**Automatic** . Then click **Apply**  \> **OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c08c50e91.jpg)

 Restart your computer to see if the error has gone. If you still see the error, you have something else to try…

---

### Fix 2: Reset your Winsock Catalog

 You very likely have the problem on your computer that joins in a domain network. You could have problem due to some interference of your Winsock Catalog setting.

Follow these steps to reset your Winsock Catalog:

1. On your keyboard, hold down the**Windows logo key** and press**R** to invoke the Run box.
2. Type**cmd** , then press**Shift + Ctrl + Enter** keys together.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c0804d3b9.jpg)
3. An elevated Command Prompt would be open. Type the following command and press Enter.  
**netsh winsock reset**

 Restart your computer to see if the error has gone. If you still see the error, don’t worry, move onto the next methods.  
 If resetting Winsock worked temporarily, you can move to Fix 5.

---

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### Fix 3: Update your video card driver

 You could probably encounter this error if the video card driver on your computer is outdated, incompatible or corrupt. So you should**update your video card driver** to see if it fixes your problem. If you don’t have the time, patience or skills to update the driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to be troubled by the wrong driver you would be downloading, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the**FREE** or the**Pro version** of Driver Easy. But with the Pro version it takes just 2 steps (and you get**full support and a 30-day money back guarantee** ):

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c1c42f3f2.jpg)
3. C  lick **Update All** to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All).  
**Note** : You can do it for free if you like, but it’s partly manual.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2297ff06.jpg)

 Restart your computer to see if the error has gone. If the error persists, don’t give up hope, see if the last method could help you…

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
### Fix 4: Uninstall the KB2952664 update

 According to many users’ report, this error could be due to the**KB2952664** Windows Update. If none of the methods above helps you, go with the following steps to**uninstall the KB2952664 update** on your computer:

1. On your keyboard, press the**Windows logo key** and**R** to invoke the Run box.
2. Type**control** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c29a46965.jpg)
3. Select**Uninstall a program** under**Programs** when**View by Category** selected.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2c7bbb7b.jpg)
4. Click View installed updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2f3ae739.jpg)
5. Find and right-click the update with KB2952664, then Uninstall.

Restart your computer to see if the error has gone.

---

### Fix 5: Remove klhkum.dll

 If you have to reset Winsock tens of times a day, you need to try this method. What you should do is checking whether you have “klhkum.dll” or not.

 klhkum.dll’s description is “**System Interceptors PDK usermode service interceptor** ” and it’s intercepting the system when it shouldn’t.  
 So how to remove it? Follow the guide:

1. Press**Ctrl+Shift+Esc** to open the Task Manager.
2. Click the**Startup** tab and find**klhkum.dll** process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-52-10.jpg)
3. Right-click on it and choose**Disable** . You can also open its file location and delete it permanently.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-55-36.jpg)
4. Restart your computer to see if the error has gone.

 One more tip: If you’re using Kaspersky security software and possibly on Windows 7, you need to turn off Kaspersky manually to fix the issue.

---

 Tada! Hopefully this helps. Feel free to comment below with your own experiences.

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-how-to-mergecombinejoin-youtube-flv-videos/"><u>[New] 2024 Approved  How to Merge/Combine/Join YouTube (FLV) Videos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-to-tailor-youtube-thumbnails-for-maximum-impact/"><u>[New] How to Tailor YouTube Thumbnails for Maximum Impact</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-oceanic-visionaries-selecting-the-top-5-cameras-for-2024/"><u>[New] Oceanic Visionaries  Selecting the Top 5 Cameras for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-the-inverse-photo-journey-through-facebooks-vast-web/"><u>[New] The Inverse Photo Journey Through Facebook’s Vast Web</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unveiling-this-years-premier-trivia-broadcasting-titles/"><u>[New] Unveiling This Year's Premier Trivia Broadcasting Titles</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-apex-legends-solo-play-tips-and-platform-preference-guide/"><u>[Updated] Apex Legends Solo Play Tips & Platform Preference Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-how-to-eliminate-your-instagram-existence-a-comprehensive-walkthrough-for-2024/"><u>[Updated] How to Eliminate Your Instagram Existence  A Comprehensive Walkthrough for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-quick-tips-screen-recording-made-simple-for-mac-users/"><u>[Updated] In 2024, Quick Tips  Screen Recording Made Simple for Mac Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-live-broadcasting-on-fb-tips-for-success/"><u>[Updated] Live Broadcasting on FB  Tips for Success</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-quintessential-zooid-startup-top-10/"><u>[Updated] Quintessential Zooid Startup Top 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clearing-upset-user-settings-failure-with-efficient-driver-fixes/"><u>Clearing Upset User Settings Failure with Efficient Driver Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208745879-complete-fix-for-n64-controllers-that-arent-responding-expert-advice-inside/"><u>Complete Fix for N64 Controllers That Aren't Responding - Expert Advice Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-solution-resolving-the-persistent-windows-update-error-0x80240017/"><u>Complete Solution: Resolving the Persistent Windows Update Error 0X80240017</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquering-the-google-chrome-alarm-a-step-by-step-guide-to-scam-recovery/"><u>Conquering The Google Chrome Alarm: A Step-by-Step Guide to Scam Recovery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-reducing-microsoft-compatibility-telemetrys-impact-on-hard-drive-space-in-windows-10/"><u>Diagnosing and Reducing Microsoft Compatibility Telemetry's Impact on Hard Drive Space in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosis-and-fixes-restoring-function-key-capabilities/"><u>Diagnosis and Fixes: Restoring Function Key Capabilities</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-12-no-cost-mobile-apps-for-endless-movie-entertainment/"><u>Discover 12 No-Cost Mobile Apps for Endless Movie Entertainment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-to-resolve-windows-11-update-issue-error-code-0x800f0922/"><u>Effective Fixes to Resolve Windows 11 Update Issue (Error Code 0X800F0922)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-the-set-user-settings-to-driver-failed-issue-with-easy-steps/"><u>Fix the 'Set User Settings to Driver Failed' Issue with Easy Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-functional-corsair-keyboard-a-step-by-step-solution/"><u>Fixing a Non-Functional Corsair Keyboard - A Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-fixing-the-critical-module-error-causing-your-games-to-freeze-and-crash/"><u>Guide: Fixing the Critical Module Error Causing Your Games to Freeze and Crash</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-infinix-zero-30-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Infinix Zero 30 5G Phones with/without a PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-camera-not-found-overcome-windows-error-0xa0nf4292/"><u>How to Resolve 'Camera Not Found' - Overcome Windows Error 0xA0nf4292</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-a-broken-connection-between-your-usb-and-hdmi-device/"><u>How to Resolve a Broken Connection Between Your USB and HDMI Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-screen-mirroring-glitches-in-windows-10-environments/"><u>How to Resolve Screen Mirroring Glitches in Windows 10 Environments</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-oppo-a58-4g-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Oppo A58 4G without App | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-quick-fixes-for-privacy-concerns-in-piscart-images/"><u>In 2024, Quick Fixes for Privacy Concerns in PiscArt Images</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-motorola-razr-40-ultra-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Motorola Razr 40 Ultra Phones</u></a></li>
<li><a href="https://win-howtos.techidaily.com/requirement-unlocked-only-certain-gpus-can-run-this-engine-check-compatibility-with-d3d11/"><u>Requirement Unlocked: Only Certain GPUs Can Run This Engine - Check Compatibility with D3D11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-red-screen-of-error-a-step-by-step-guide/"><u>Resolving the Red Screen of Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-troubleshooting-guide-for-initializing-issues-with-smartaudio/"><u>Solved: Troubleshooting Guide for Initializing Issues with SmartAudio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-invalid-value-in-registry-issues-when-launching-photos-app-on-windows-10/"><u>Solving 'Invalid Value in Registry' Issues when Launching Photos App on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-restoring-bluetooth-on-your-computers-system-manager/"><u>Step-by-Step Solution: Restoring Bluetooth on Your Computer's System Manager</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-repair-of-non-functional-usb-port-on-hp-laptop-models-step-by-step/"><u>Successful Repair of Non-Functional USB Port on HP Laptop Models - Step by Step</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-definitive-answer-to-solving-glexttexturencompression-level-format-problem-in-opengl-error-1281/"><u>The Definitive Answer to Solving GL_EXT_texture_ncompression Level Format Problem in OpenGL (Error 1281)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209681282-the-resolution-to-your-olive-obstacle-in-nba-2k21-solving-steps-unpacked/"><u>The Resolution to Your Olive Obstacle in NBA 2K21 - Solving Steps Unpacked</u></a></li>
<li><a href="https://os-tips.techidaily.com/top-6-tips-to-troubleshoot-persistent-snapchat-app-crashes-on-ios-and-android-devices/"><u>Top 6 Tips to Troubleshoot Persistent Snapchat App Crashes on iOS and Android Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solutions-for-automatic-mouse-double-clicks/"><u>Troubleshooting and Solutions for Automatic Mouse Double-Clicks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-bluetooth-connectivity-issues-in-windows-10/"><u>Troubleshooting Bluetooth Connectivity Issues in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-timely-response-error-in-system-services-code-1053/"><u>Troubleshooting Guide for Timely Response Error in System Services (Code 1053)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-player-error-no-source-available-on-windows/"><u>Troubleshooting Guide: Fixing 'Player Error - No Source Available' On Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-logitech-mouse-scroll-wheel-issues/"><u>Troubleshooting Guide: Resolving Logitech Mouse Scroll Wheel Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-unknown-usb-device-port-reset-failed-in-windows-11-a-comprehensive-fix-guide/"><u>Winning Against 'Unknown USB Device (Port Reset Failed)' In Windows 11: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-unsuccessful-windows-patches-solutions-proven-effective/"><u>Winning the Battle Against Unsuccessful Windows Patches: Solutions Proven Effective</u></a></li>
</ul></div>
