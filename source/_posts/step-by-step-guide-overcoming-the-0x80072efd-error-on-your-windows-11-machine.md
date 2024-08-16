---
title: "Step-by-Step Guide: Overcoming the 0X80072EFD Error on Your Windows 11 Machine"
date: 2024-08-15T11:35:46.404Z
updated: 2024-08-16T11:35:46.404Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Guide: Overcoming the 0X80072EFD Error on Your Windows 11 Machine"
excerpt: "This Article Describes Step-by-Step Guide: Overcoming the 0X80072EFD Error on Your Windows 11 Machine"
thumbnail: https://thmb.techidaily.com/75f2f8c580c180a2b2853a51a56b59840e62a47f848cf8becd199a47e930b0cb.jpg
---

## Overcoming 'Class Unregistered on Windows 11' Error – Tips & Tricks Inside

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
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`` Click **Yes**  when prompted by User Account Control.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-17.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

``

``

`` 3) Open the app again to see if it goes fine.

``

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
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

``

 2) Click **System** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8-12.png)

``

``

`` 3) Click **Default apps**  on the left pane. Then on the right pane, scroll down to click **Reset**  under the **Reset to the Microsoft recommended defaults**  section.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7-11.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

``

``

4) Open the app again to see if it goes fine.

 Note: If you’ve installed iCloud on your Windows 10, you can try the fix below if all the fixes above don’t help.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 5: Disable iCloud

 Some users reported that to disable iCloud in Task Manager fix the error for them. So make sure to try to disable icloud if you install one on Windows 10.

 1) Press**Shift** +**Ctrl** +**Esc** keys at the same time to open**Task Manager** .

 2) On Task Manager window, tap on the **Startup** pane. Then find and right-click on **iCloud Services** . Click **Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10-7.png)

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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-recorded-tones-the-iphone-voicemail-keeper/"><u>[New] 2024 Approved  Recorded Tones  The iPhone Voicemail Keeper</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-dangerous-depths-top-10-roguelite-showdowns/"><u>[Updated] Dangerous Depths  Top 10 Roguelite Showdowns</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-unraveling-the-packaging-a-marketing-approach-for-2024/"><u>[Updated] Unraveling the Packaging  A Marketing Approach for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2023-endless-ears-on-facebook-downloads-for-2024/"><u>2023  Endless Ears on Facebook Downloads for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ace-your-brand-strategy-with-these-reddit-mastery-methods-for-2024/"><u>Ace Your Brand Strategy with These Reddit Mastery Methods for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/constraint-b-each-historical-event-chosen-for-the-footnotes-should-not-have-been-commonly-referenced-in-mainstream-media/"><u>Constraint B: Each Historical Event Chosen for the Footnotes Should Not Have Been Commonly Referenced in Mainstream Media.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeating-the-dilemma-of-a-dead-stylus-in-depth-strategies-for-xperia-and-tab-pro-users/"><u>Defeating the Dilemma of a Dead Stylus: In-Depth Strategies for Xperia and Tab Pro Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-repair-broken-arrow-keys-on-your-keyboard-proven-methods/"><u>Diagnose and Repair Broken Arrow Keys on Your Keyboard - Proven Methods</u></a></li>
<li><a href="https://games-able.techidaily.com/dialing-down-xbox-game-bar-on-your-computer/"><u>Dialing Down Xbox Game Bar on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fading-vision-visual-void/"><u>Fading Vision: Visual Void</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Nubia Z50 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-easily-fix-the-troublesome-update-issue-windows-10s-0xc1900208-error-code-decoded/"><u>How to Easily Fix the Troublesome Update Issue - Windows 10'S 0Xc1900208 Error Code Decoded</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-apple-id-verification-code-not-working-on-apple-iphone-12-mini-by-drfone-ios/"><u>How To Fix Apple ID Verification Code Not Working On Apple iPhone 12 mini</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-solve-a-laptops-white-screen-dilemma-for-smooth-operations/"><u>How to Solve a Laptop's White Screen Dilemma for Smooth Operations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/improve-your-pcs-graphics-efficiency-tackling-dwm-related-gpu-overuse-in-windows-11/"><u>Improve Your PC's Graphics Efficiency: Tackling DWM-Related GPU Overuse in Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-4-detailed-steps-to-flip-a-clip-in-final-cut-pro/"><u>In 2024, 4 Detailed Steps to Flip a Clip in Final Cut Pro</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-navigation-downfall-restore-function-to-up-down-left-and-right-arrows-now/"><u>Keyboard Navigation Downfall: Restore Function to Up, Down, Left & Right Arrows Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-fixes-for-halo-4-ue4-catastrophic-system-failures-your-comprehensive-guide/"><u>Master the Fixes for Halo 4 UE4 Catastrophic System Failures - Your Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/masterful-strategies-overcoming-writing-controller-challenges-on-xbox-platforms-a-detailed-walkthrough/"><u>Masterful Strategies: Overcoming Writing Controller Challenges on Xbox Platforms - A Detailed Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-go-for-code-run/"><u>No Go for Code Run</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-windows-update-issue-overcoming-error-8007000e-easily/"><u>Quick Fixes for Windows Update Issue: Overcoming Error 8007000E Easily</u></a></li>
<li><a href="https://win-amazing.techidaily.com/quick-guide-to-downloading-your-logitech-drivers-for-windows/"><u>Quick Guide to Downloading Your Logitech Drivers for Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/recovering-your-stolen-iphone-with-apples-find-my-application/"><u>Recovering Your Stolen iPhone with Apple's Find My Application</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reverse-redaction-operation/"><u>Reverse Redaction Operation</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ering-synthetic-statistics-on-youtube/"><u>Shattering Synthetic Statistics on YouTube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-controlling-wudfhostexe-high-resource-use-on-windows-11-computers/"><u>Step-by-Step Solution for Controlling wudfhost.exe High Resource Use on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-changed-monitor-display-size-a-troubleshooting-guide/"><u>Successfully Changed Monitor Display Size - A Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-your-game-heres-how-to-fix-setup-problems-on-origin/"><u>Trouble With Your Game? Here's How to Fix Setup Problems on Origin</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-unwanted-windows-10-file-explorers-scroll-jumping-behavior/"><u>Troubleshooting Guide for Unwanted Windows 10 File Explorer's Scroll Jumping Behavior</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-issues-with-applying-windows-11-update-version-1607/"><u>Understanding Issues with Applying Windows 11 Update Version 1607</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-free-music-production-software-top-picks-for-windowsmac-users/"><u>Updated In 2024, Free Music Production Software Top Picks for Windows/Mac Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/usb-mouse-not-working-on-laptop-try-these-fixes/"><u>USB Mouse Not Working on Laptop? Try These Fixes</u></a></li>
</ul></div>
