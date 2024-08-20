---
title: "Resolving the 0X800705b4 Fault During Windows 11 Updates: A Comprehensive Guide"
date: 2024-08-19T07:24:39.007Z
updated: 2024-08-20T07:24:39.007Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the 0X800705b4 Fault During Windows 11 Updates: A Comprehensive Guide"
excerpt: "This Article Describes Resolving the 0X800705b4 Fault During Windows 11 Updates: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/ee549b864de6102ff48675fa7bf1a7613a21bc32bbc71908950ecf0a34fbb345.jpg
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

**2)** In Command Prompt, type the following lines of command and press**Enter**on your keyboard after typing each:

* _**net stop bits**_
* _**net stop wuauserv**_
* _**net stop appidsvc**_
* _**net stop cryptsvc**_
(These commands will stop the services that Windows Update requires to download and install updates.)**3)** Type these lines of command and press**Enter** after typing each in Command Prompt:
* _**Ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old**_
* _**Ren %systemroot%\\system32\\catroot2 catroot2.old**_
(This will rename the_SoftwareDistribution_and_catroot2_folder, which are used by Windows Update to store data and temporary files. Your system will detect that these folders are missing, and then it’ll create new ones. The purpose of this is to make the system use the new_SoftwareDistribution_and _catroot2_folders so that Windows Update can avoid issues from the old ones.)**4)**Still in Command Prompt, type these commands and press Enter after each to restart the services you closed just now:
* _**net start bits**_
* _**net start wuauserv**_
* _**net start appidsvc**_
* _**net start cryptsvc**_
**5)**Run Windows Update and check to see if your computer can install the 1607 update.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

## Method 4: Temporarily disable your antivirus software

Sometimes your system can’t install new updates due to the interference from your**antivirus software**. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.**IMPORTANT:**Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://vimeo-videos.techidaily.com/new-accelerate-engagement-through-vimeo-linking/"><u>[New] Accelerate Engagement Through Vimeo Linking</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-maximizing-your-marketing-mettle-on-youtube/"><u>[New] Maximizing Your Marketing Mettle on Youtube</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-optimal-budget-friendly-digital-video-reader/"><u>[New] Optimal Budget-Friendly Digital Video Reader</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-ultimate-guide-to-4k-capturing-applications-for-2024/"><u>[New] Ultimate Guide to 4K Capturing Applications for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-how-can-you-view-all-shared-videos-and-photos-on-messenger/"><u>[Updated] 2024 Approved  How Can You View All Shared Videos And Photos on Messenger?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-image-full-screen-webpage/"><u>[Updated] Image Full-Screen Webpage</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-top-picks-ultimate-tools-for-efficient-scheduling-screen-captures/"><u>[Updated] In 2024, Top Picks  Ultimate Tools for Efficient Scheduling Screen Captures</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/st-youtube-music-reaction-videos-2023-for-2024/"><u>10 Best YouTube Music Reaction Videos 2023 for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-4k-pads-for-ultimate-gameplay/"><u>2024 Approved  Best 4K Pads for Ultimate Gameplay</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-ultimate-ipad-360-video-creation-for-facebook/"><u>2024 Approved  The Ultimate iPad 360 Video Creation for Facebook</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/adept-adjustments-mastering-the-chromatic-dance-for-2024/"><u>Adept Adjustments  Mastering the Chromatic Dance for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-meizu-21-pro-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Meizu 21 Pro is off? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clearing-upset-user-settings-failure-with-efficient-driver-fixes/"><u>Clearing Upset User Settings Failure with Efficient Driver Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208745879-complete-fix-for-n64-controllers-that-arent-responding-expert-advice-inside/"><u>Complete Fix for N64 Controllers That Aren't Responding - Expert Advice Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-solution-resolving-the-persistent-windows-update-error-0x80240017/"><u>Complete Solution: Resolving the Persistent Windows Update Error 0X80240017</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquering-the-google-chrome-alarm-a-step-by-step-guide-to-scam-recovery/"><u>Conquering The Google Chrome Alarm: A Step-by-Step Guide to Scam Recovery</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/convert-and-save-webcam-images-in-vlc-for-2024/"><u>Convert and Save Webcam Images in VLC for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-to-resolve-windows-11-update-issue-error-code-0x800f0922/"><u>Effective Fixes to Resolve Windows 11 Update Issue (Error Code 0X800F0922)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-the-set-user-settings-to-driver-failed-issue-with-easy-steps/"><u>Fix the 'Set User Settings to Driver Failed' Issue with Easy Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-functional-corsair-keyboard-a-step-by-step-solution/"><u>Fixing a Non-Functional Corsair Keyboard - A Step-by-Step Solution</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-version-of-dell-display-adapters-quickly-and-safely-online/"><u>Get the Latest Version of Dell Display Adapters Quickly & Safely Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-fixing-the-critical-module-error-causing-your-games-to-freeze-and-crash/"><u>Guide: Fixing the Critical Module Error Causing Your Games to Freeze and Crash</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-xiaomi-redmi-note-13-pro-5g-by-drfone-android/"><u>How to Bypass FRP on Xiaomi Redmi Note 13 Pro 5G?</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-of-apple-iphone-x-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-camera-not-found-overcome-windows-error-0xa0nf4292/"><u>How to Resolve 'Camera Not Found' - Overcome Windows Error 0xA0nf4292</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-a-broken-connection-between-your-usb-and-hdmi-device/"><u>How to Resolve a Broken Connection Between Your USB and HDMI Device</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-vivo-v30-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Vivo V30 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Oppo Reno 8T 5G? | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-vimeo-revenue-a-step-by-step-money-making-blueprint/"><u>In 2024, Vimeo Revenue  A Step-by-Step Money-Making Blueprint</u></a></li>
<li><a href="https://youtube-data.techidaily.com/al-masterclasses-in-15-short-video-formats-on-youtube-for-2024/"><u>Musical Masterclasses in 15 Short Video Formats on YouTube for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-red-screen-of-error-a-step-by-step-guide/"><u>Resolving the Red Screen of Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-troubleshooting-guide-for-initializing-issues-with-smartaudio/"><u>Solved: Troubleshooting Guide for Initializing Issues with SmartAudio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-invalid-value-in-registry-issues-when-launching-photos-app-on-windows-10/"><u>Solving 'Invalid Value in Registry' Issues when Launching Photos App on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-repair-of-non-functional-usb-port-on-hp-laptop-models-step-by-step/"><u>Successful Repair of Non-Functional USB Port on HP Laptop Models - Step by Step</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-definitive-answer-to-solving-glexttexturencompression-level-format-problem-in-opengl-error-1281/"><u>The Definitive Answer to Solving GL_EXT_texture_ncompression Level Format Problem in OpenGL (Error 1281)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209681282-the-resolution-to-your-olive-obstacle-in-nba-2k21-solving-steps-unpacked/"><u>The Resolution to Your Olive Obstacle in NBA 2K21 - Solving Steps Unpacked</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/top-rated-wi-fi-signal-boosters-comprehensive-guide/"><u>Top Rated Wi-Fi Signal Boosters : Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solutions-for-automatic-mouse-double-clicks/"><u>Troubleshooting and Solutions for Automatic Mouse Double-Clicks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-bluetooth-connectivity-issues-in-windows-10/"><u>Troubleshooting Bluetooth Connectivity Issues in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-timely-response-error-in-system-services-code-1053/"><u>Troubleshooting Guide for Timely Response Error in System Services (Code 1053)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-player-error-no-source-available-on-windows/"><u>Troubleshooting Guide: Fixing 'Player Error - No Source Available' On Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-logitech-mouse-scroll-wheel-issues/"><u>Troubleshooting Guide: Resolving Logitech Mouse Scroll Wheel Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-unknown-usb-device-port-reset-failed-in-windows-11-a-comprehensive-fix-guide/"><u>Winning Against 'Unknown USB Device (Port Reset Failed)' In Windows 11: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-unsuccessful-windows-patches-solutions-proven-effective/"><u>Winning the Battle Against Unsuccessful Windows Patches: Solutions Proven Effective</u></a></li>
</ul></div>
