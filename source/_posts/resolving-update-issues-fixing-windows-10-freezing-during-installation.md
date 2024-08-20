---
title: "Resolving Update Issues: Fixing Windows 10 Freezing During Installation"
date: 2024-08-19T07:05:26.180Z
updated: 2024-08-20T07:05:26.180Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Update Issues: Fixing Windows 10 Freezing During Installation"
excerpt: "This Article Describes Resolving Update Issues: Fixing Windows 10 Freezing During Installation"
thumbnail: https://thmb.techidaily.com/e66e28dff9a78d29ac6c41d0e2dd487a7c339d734ca57b3143f21e9c629c5f8e.jpg
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
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
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 3: Run the DISM utility

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-unlocking-social-media-success-rising-through-the-facebook-leaderboard/"><u>[New] 2024 Approved  Unlocking Social Media Success  Rising Through the Facebook Leaderboard</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-smooth-media-transfer-twitvideos-to-whatsapp-guide-for-2024/"><u>[New] Smooth Media Transfer  TwitVideos to WhatsApp Guide for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-top-easytime-timer-solutions-at-zero-cost-for-2024/"><u>[New] Top EasyTime Timer Solutions at Zero Cost for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-cutting-edge-8-streaming-selectors-for-2024/"><u>[Updated] Cutting-Edge 8 Streaming Selectors for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-elevate-your-content-strategy-premier-ranks-apps-explored/"><u>[Updated] In 2024, Elevate Your Content Strategy - Premier Ranks Apps Explored</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-get-hooked-on-fast-forward-finesse-in-snapchat-writes/"><u>2024 Approved  Get Hooked on Fast-Forward Finesse in Snapchat' Writes</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-the-route-to-collecting-pictorial-frame-downloads/"><u>2024 Approved  The Route to Collecting Pictorial Frame Downloads</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/5-best-ps1-emulators-for-pc/"><u>5 Best PS1 Emulators for PC</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avoid-overheating-in-your-hp-spectre-x360-top-techniques-for-cooler-performance/"><u>Avoid Overheating in Your HP Spectre X360: Top Techniques for Cooler Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-walkthrough-correcting-faulty-configuration-files-on-windows-1011/"><u>Complete Walkthrough: Correcting Faulty Configuration Files on Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-steps-to-solve-your-monitors-video-signal-failure/"><u>Comprehensive Steps to Solve Your Monitor's Video Signal Failure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eradicate-your-valorant-screen-shake-or-tear-problem-now/"><u>Eradicate Your Valorant Screen Shake or Tear Problem Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-87-on-loadlibrary-how-to-fix-the-parameter-is-incorrect-issues/"><u>Error 87 on LoadLibrary: How to Fix 'The Parameter Is Incorrect' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolved-fixing-system-resources-too-low-issue/"><u>Error Resolved: Fixing 'System Resources Too Low' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-troubleshooting-and-solving-power-state-driver-mistakes-on-pc/"><u>Expert Advice: Troubleshooting and Solving Power State Driver Mistakes on PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-resolve-the-windows-camera-malfunction-code-0xa00f4292-explained/"><u>Expert Tips to Resolve the Windows Camera Malfunction: Code 0xA00f4292 Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-enable-windows-hello-authentication-on-incompatible-devices-in-windows-10/"><u>How to Enable Windows Hello Authentication on Incompatible Devices in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-non-responsive-synaptics-touchpad-scroll-wheel-under-windows-10/"><u>How to Fix a Non-Responsive Synaptics Touchpad Scroll Wheel Under Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unresponsive-usb-connectors-in-windows-operating-systems-windows-10-11/"><u>How to Fix Unresponsive USB Connectors in Windows Operating Systems (Windows 10, 11)</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-13-key-tactics-for-enhanced-visibility-in-facebook-videography/"><u>In 2024, 13 Key Tactics for Enhanced Visibility in Facebook Videography</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-realme-narzo-60-5g-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Realme Narzo 60 5G Phone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-oppo-a1x-5g-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Oppo A1x 5G Device SIM</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-leveraging-snapchat-for-professional-networking-and-sales/"><u>In 2024, Leveraging Snapchat for Professional Networking & Sales</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-spectral-stories-telling-tales-through-color/"><u>In 2024, Spectral Stories  Telling Tales Through Color</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-asus-rog-phone-7-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Asus ROG Phone 7 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-iphone-13-pro-max-without-passcode-easily-by-drfone-ios/"><u>In 2024, Unlock iPhone 13 Pro Max Without Passcode Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/instant-solutions-for-when-windows-11-wont-proceed-past-the-initial-display/"><u>Instant Solutions for When Windows 11 Won't Proceed Past the Initial Display</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-trackpad-not-functioning-heres-how-to-fix-it-on-windows-11-8-and-7-solved/"><u>Laptop Trackpad Not Functioning? Here's How to Fix It on Windows 11, 8 & 7 – SOLVED!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-airpod-connectivity-with-windows-11-advanced-solutions-for-a-seamless-experience/"><u>Mastering AirPod Connectivity with Windows 11: Advanced Solutions for a Seamless Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/maximize-your-pcs-potential-a-guide-to-faster-and-smoother-gaming-on-windows-11/"><u>Maximize Your PC's Potential: A Guide to Faster and Smoother Gaming on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimize-your-system-fixing-svchostexes-extreme-cpu-usage-on-windows-11/"><u>Optimize Your System: Fixing Svchost.exe's Extreme CPU Usage on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-your-pcs-health-on-windows-10-via-system-file-checker-and-deployment-image-service-module-commands/"><u>Optimizing Your PC's Health on Windows 10 via System File Checker and Deployment Image Service Module Commands</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-game-interruptions-why-your-pc-powers-down-while-running-windows-11107818/"><u>Overcoming Game Interruptions: Why Your PC Powers Down While Running Windows 11/10/7/8.1/8?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/ps-gaming-audio-masterclass-vocal-tweaks-for-2024/"><u>PS Gaming Audio Masterclass - Vocal Tweaks for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-overcoming-hurdles-in-microsofts-windows-1903-update-process/"><u>Resolved: Overcoming Hurdles in Microsoft's Windows 1903 Update Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revitalizing-your-pc-with-sfc-and-dism-tools-in-windows-11/"><u>Revitalizing Your PC with SFC & DISM Tools in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sculpt-your-vision-editing-videos-using-story-remix-and-windows-photos-for-2024/"><u>Sculpt Your Vision  Editing Videos Using Story Remix and Windows Photos for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/spectacular-imagery-narrative-engine-for-2024/"><u>Spectacular Imagery Narrative Engine for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speedy-fixes-resolving-sluggish-startup-times-on-your-windows-7-pc/"><u>Speedy Fixes: Resolving Sluggish Startup Times on Your Windows 7 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-troubleshooting-tactics-for-driverpowerstatefailure/"><u>The Ultimate Troubleshooting Tactics for DRIVER_POWER_STATE_FAILURE</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-eliminate-kodis-buffering-problems-with-these-simple-fixes/"><u>Troubleshoot and Eliminate Kodi's Buffering Problems with These Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-fix-windows-update-error-code-0x802n02e/"><u>Troubleshooting Guide: How to Fix Windows Update Error Code 0X802n02E</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-usb-mouse-issues-solutions-when-it-wont-connect-to-your-laptop/"><u>Troubleshooting USB Mouse Issues: Solutions When It Won't Connect to Your Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-the-reason-behind-teredos-inability-to-connect-successfully/"><u>Understanding the Reason Behind Teredo's Inability to Connect Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208089290-valorant-perpetual-boot-loop-heres-how-to-resolve-it/"><u>Valorant Perpetual Boot Loop? Here's How to Resolve It!</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Realme Note 50? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wired-back-to-life-logitech-mouse-restsore/"><u>Wired Back to Life: Logitech Mouse Restsore</u></a></li>
</ul></div>
