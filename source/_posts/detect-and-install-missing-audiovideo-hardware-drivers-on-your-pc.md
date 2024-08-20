---
title: Detect & Install Missing Audio/Video Hardware Drivers on Your PC
date: 2024-08-19T07:44:22.230Z
updated: 2024-08-20T07:44:22.230Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Detect & Install Missing Audio/Video Hardware Drivers on Your PC
excerpt: This Article Describes Detect & Install Missing Audio/Video Hardware Drivers on Your PC
thumbnail: https://thmb.techidaily.com/0aeedb6f0e08290ddfa4945f77d0426cb986cac7f0c8ef179d1c62c13237705d.jpg
---

## Resolving Unregistered Class Errors on Your Windows 10 PC - Solutions Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a90d415e22e7.jpg)

 If you want to open an app or program on your Windows 10, but if fails, and you’re seeing this error saying: **Class not registered** . Reset assured, you’re not alone. Many Windows users encounter this error. More importantly, you can fix it easily by yourself.

 This error occurs on your Windows 10 mainly due to the app or the program with**unregistered DLL files** . You can probably fix it by these following solutions:

 **Try one at a time:**

1. [  Fix DCOM(Distributed Component Object Model) errors ](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 1. Fix DCOM%28Distributed Component Object Model%29 errors)
2. [ Re-register ExplorerFrame.dll file](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 2. Re-register ExplorerFrame.dll file)
3. [ Start Internet Explorer ETW Collector Service](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 3. Start Internet Explorer ETW Collector Service)
4. [ Set Windows Photo Viewer as a default image viewer ](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 4. Set Windows Photo Viewer as a default image viewer)
5. [ Disable iCloud](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 5. Disable iCloud) ``

## Fix 1: Fix DCOM(**Distributed Component Object Model)** errors

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

`` 2) Type **dcomcnfg**  and press Enter to open **Component Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-19.png)

``

``

`` 2) Go to **Component Services**  \> **Computers**  \> **My Computer**  on the Component Services window. Then double-click on **DCOM Config** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-17.png)

``

``

`` 3) Then a few DCOM Configuration warning messages will pop up. Click **Yes**  for each one.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-18.png)

``

``

`` 4) Reboot your Windows 10 and open the app again to see if it goes fine.

``

## Fix 2: Re-register the ExplorerFrame.dll file

``

`
` ``

 1) Press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  +**X** key together, then click**Command Prompt(Admin)** .

`` Click **Yes**  when prompted by User Account Control.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-17.png)

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

``

``

`` 3) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
4) Open the app again to see if it goes fine.

``

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

``

 2) Click **System** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8-12.png)

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

``

`` 3) Click **Default apps**  on the left pane. Then on the right pane, scroll down to click **Reset**  under the **Reset to the Microsoft recommended defaults**  section.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7-11.png)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
``

``

4) Open the app again to see if it goes fine.

 Note: If you’ve installed iCloud on your Windows 10, you can try the fix below if all the fixes above don’t help.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 5: Disable iCloud

 Some users reported that to disable iCloud in Task Manager fix the error for them. So make sure to try to disable icloud if you install one on Windows 10.

 1) Press**Shift** +**Ctrl** +**Esc** keys at the same time to open**Task Manager** .

 2) On Task Manager window, tap on the **Startup** pane. Then find and right-click on **iCloud Services** . Click **Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10-7.png)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
3) Open the app again to see if it goes fine.

That’s it!

 Hopefully you have got your Windows 10 out of Class not registered error.

[](https://tools.techidaily.com/drivereasy/download/)

[](https://tools.techidaily.com/drivereasy/download/) [](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-guide-to-tape-twitch-streams-effectively/"><u>[New] In 2024, Guide to Tape Twitch Streams Effectively</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-step-by-step-guide-changing-voices-in-instagram-features/"><u>[New] Step-by-Step Guide  Changing Voices in Instagram Features</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-flipbook-of-facebook-feeds/"><u>[Updated] 2024 Approved  Flipbook of Facebook Feeds</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-webs-winners-circle-worlds-most-subscribed-youtubers/"><u>[Updated] 2024 Approved  Web's Winners Circle  World's Most Subscribed YouTubers</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-capturing-movie-scenes-as-single-image-snapshots-windows-10/"><u>[Updated] In 2024, Capturing Movie Scenes as Single Image Snapshots (Windows 10)</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-pioneering-business-through-virtual-realitiescape-for-2024/"><u>[Updated] Pioneering Business Through Virtual Realitiescape for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-ultimate-collection-20-chuckle-inducing-detention-cell-photos-for-a-better-day/"><u>[Updated] Ultimate Collection  20 Chuckle-Inducing Detention Cell Photos for a Better Day</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-ultimate-picks-the-best-online-tools-for-downloading-vimeo-videos/"><u>[Updated] Ultimate Picks  The Best Online Tools for Downloading Vimeo Videos</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-your-path-to-youtube-studio-the-editors-command-center/"><u>[Updated] Your Path to YouTube Studio  The Editor's Command Center</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-effortlessly-enhanced-images-learn-the-insider-snapchat-tactics/"><u>2024 Approved  Effortlessly Enhanced Images  Learn the Insider Snapchat Tactics</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-premier-video-breakdown-fifa-analysis-graphs/"><u>2024 Approved  Premier Video Breakdown  FIFA Analysis Graphs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-from-footage-to-film-how-to-make-a-dvd-with-the-best-software/"><u>2024 Approved From Footage to Film How to Make a DVD with the Best Software</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-apple-iphone-7-fix-now-drfone-by-drfone-virtual-ios/"><u>3uTools Virtual Location Not Working On Apple iPhone 7? Fix Now | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/asus-laptop-how-to-fix-unresponsive-fn-keys-problems/"><u>ASUS Laptop: How to Fix Unresponsive Fn Keys Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cast-to-device-not-working-on-windows-11-solved/"><u>Cast to Device Not Working on Windows 11 [Solved]</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/conceptual-mastery-combining-ai-and-brainstorming/"><u>Conceptual Mastery: Combining AI & Brainstorming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/configuration-system-failed-to-initialize-on-windows-10-solved/"><u>Configuration System Failed to Initialize on Windows 10 [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209008590-connectivity-hacks-for-your-xbox-one-controller-overcoming-synchronization-challenges-easily/"><u>Connectivity Hacks for Your Xbox One Controller – Overcoming Synchronization Challenges Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corrected-key-media-transfer-components-lacking-on-your-pcs-hardware-list/"><u>Corrected: Key Media Transfer Components Lacking on Your PC's Hardware List</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corrective-steps-when-your-hp-laptop-camera-fails-on-windows-11/"><u>Corrective Steps When Your HP Laptop Camera Fails on Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-the-new-magicard-rio-pro-driver-compatible-with-windows-10-81-and-7/"><u>Download the New Magicard Rio Pro Driver: Compatible with Windows 10, 8.1 & 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fixes-for-tackling-windows-update-standstill-at-zero-percent/"><u>Effortless Fixes for Tackling Windows Update Standstill at Zero Percent</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fixes-stop-windows-11-endless-reboots/"><u>Effortless Fixes: Stop Windows 11 Endless Reboots</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enable-detecting-of-bluetooth-gadgets-on-your-pc-running-windows-10/"><u>Enable Detecting of Bluetooth Gadgets on Your PC Running Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-8024020-successful-troubleshooting-steps-for-windows-11-setup-issues/"><u>Error Code 8024020 - Successful Troubleshooting Steps for Windows 11 Setup Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202547685-expert-tips-for-a-cheating-free-gaming-experience-on-apex-legends-fix-those-errors/"><u>Expert Tips for a Cheating-Free Gaming Experience on Apex Legends - Fix Those Errors!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208065872-fix-my-surface-wont-charge-problem-expert-tips-for-a-full-battery/"><u>Fix My Surface Won't Charge Problem – Expert Tips for a Full Battery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-stuck-keyboard-numbers-with-these-proven-methods/"><u>Fix Your Stuck Keyboard Numbers with These Proven Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-print-screen-key-malfunction-on-windows-11-and-10/"><u>Fixing the Issue: Print Screen Key Malfunction on Windows 11 & 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/forza-horizon-asterisk-4-noise-solutions-eliminate-silence-and-enjoy-the-race-again/"><u>Forza Horizon Asterisk 4 Noise Solutions - Eliminate Silence and Enjoy the Race Again</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-oppo-a1-5g-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Oppo A1 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-update-failure-in-warframe-solutions-and-tips/"><u>How to Resolve 'Update Failure' In Warframe - Solutions & Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-repair-windows-update-glitches-now/"><u>How To Successfully Repair Windows Update Glitches, Now</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-x-with-a-mask-on-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone X with a Mask On | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-5-reddit-marketing-tips-that-will-turn-beginners-into-experts/"><u>In 2024, 5 Reddit Marketing Tips that Will Turn Beginners Into Experts</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Nokia C12 Plus? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-samsung-galaxy-a05s-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Samsung Galaxy A05s? Fixed | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-reinvent-your-video-storytelling-in-obs-studio/"><u>In 2024, Reinvent Your Video Storytelling in OBS Studio</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-nokia-105-classic-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Nokia 105 Classic without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-pubg-top-solutions-for-eliminating-game-lags/"><u>Optimizing PUBG: Top Solutions for Eliminating Game Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-10-casting-hurdles-a-step-by-step-guide-to-a-smooth-setup/"><u>Overcoming Windows 10 Casting Hurdles: A Step-by-Step Guide to a Smooth Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-10s-failure-to-shutdown-a-comprehensive-guide/"><u>Overcoming Windows 10'S Failure to Shutdown - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/problem-solved-correcting-login-keyboard-connectivity-issues/"><u>Problem Solved: Correcting Login Keyboard Connectivity Issues</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>Reasons why Pokémon GPS does not Work On Apple iPhone SE (2020)? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-lenovo-mouse-pad-problems-in-windows-systems-a-step-by-step-fix/"><u>Resolve Your Lenovo Mouse Pad Problems in Windows Systems: A Step-by-Step Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-update-issues-fixes-and-tips/"><u>Resolving Windows 11 Update Issues: Fixes and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-input-devices-troubleshoot-unresponsive-mouse-and-keyboard-on-windows-7-systems/"><u>Reviving Input Devices: Troubleshoot Unresponsive Mouse and Keyboard on Windows 7 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/scrolling-gain-windows-mouse-mastery/"><u>Scrolling Gain: Windows Mouse Mastery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210723266-skype-microphone-not-working-follow-these-steps-for-a-quick-and-easy-resolution/"><u>Skype Microphone Not Working? Follow These Steps for a Quick and Easy Resolution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-usb-connection-issues-on-your-pc-running-windows-10-or-11/"><u>Solving USB Connection Issues on Your PC Running Windows 10 or 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-replacing-your-laptops-missing-keys/"><u>Step-by-Step Guide: Replacing Your Laptop's Missing Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-troubleshooting-the-livekernelevent-117-mistake/"><u>Step-by-Step Guide: Troubleshooting the LiveKernelEvent 117 Mistake</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missing-files-for-games-and-streamers-on-windows-systems-solved/"><u>Troubleshooting Missing Files for Games and Streamers on Windows Systems [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-repair-a-non-functional-microphone-in-a-laptop/"><u>Troubleshooting: How to Repair a Non-Functional Microphone in a Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-compatible-solutions-for-a-malfunctioning-laptop-touchpad-fixes-for-1187/"><u>Windows-Compatible Solutions for a Malfunctioning Laptop Touchpad: Fixes for 11/8/7</u></a></li>
<li><a href="https://apple-account.techidaily.com/your-account-has-been-disabled-in-the-app-store-and-itunes-from-apple-iphone-11-pro-by-drfone-ios/"><u>Your Account Has Been Disabled in the App Store and iTunes From Apple iPhone 11 Pro?</u></a></li>
</ul></div>
