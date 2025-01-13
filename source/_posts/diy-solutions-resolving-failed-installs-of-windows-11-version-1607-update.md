---
title: "DIY Solutions: Resolving Failed Installs of Windows 11 Version 1607 Update"
date: 2025-01-12T17:16:13.587Z
updated: 2025-01-13T17:22:59.673Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes DIY Solutions: Resolving Failed Installs of Windows 11 Version 1607 Update"
excerpt: "This Article Describes DIY Solutions: Resolving Failed Installs of Windows 11 Version 1607 Update"
thumbnail: https://thmb.techidaily.com/defd396607cd2975fa174c851525eeb9f0360235bf9d5ed977ea6af47a5ef4bb.jpg
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

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Then a few DCOM Configuration warning messages will pop up. Click **Yes**  for each one.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-18.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 4) Reboot your Windows 10 and open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 2: Re-register the ExplorerFrame.dll file

``

`
` ``

 1) Press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  +**X** key together, then click**Command Prompt(Admin)** .

`` Click **Yes**  when prompted by User Account Control.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-17.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Open the app again to see if it goes fine.

``

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

``

``

4) Open the app again to see if it goes fine.

 Note: If you’ve installed iCloud on your Windows 10, you can try the fix below if all the fixes above don’t help.

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
<li><a href="https://some-guidance.techidaily.com/new-unlock-movie-magic-with-cg-centrals-look-up-tables-luts/"><u>[New] Unlock Movie Magic with CG Central's Look-Up Tables (Luts)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-vanishing-in-the-crowd-how-to-peruse-instagram-stories-on-various-platforms-anonymously/"><u>[New] Vanishing in the Crowd How to Peruse Instagram Stories on Various Platforms Anonymously</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-dominating-viewers-spaces-channel-empire-rules/"><u>[Updated] 2024 Approved Dominating Viewers' Spaces Channel Empire Rules</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-6-video-styles-for-maximum-viewer-engagement-for-2024/"><u>[Updated] 6 Video Styles for Maximum Viewer Engagement for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/display-problem-alert-current-refresh-rate-is-unsupported-by-your-screen/"><u>Display Problem Alert: Current Refresh Rate Is Unsupported by Your Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-when-system-cant-access-required-modules/"><u>Effective Solutions for When System Can’t Access Required Modules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-audio-to-video-conversion-convert-your-wav-recordings-into-avi-gratis/"><u>Effortless Audio-to-Video Conversion: Convert Your WAV Recordings Into AVI - Gratis!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-10-troubleshooting-non-functional-right-click-on-your-mouse/"><u>Fixing Windows 10: Troubleshooting Non-Functional Right Click on Your Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-skyrims-eternal-launch-screen-bug-for-smooth-gaming-experience/"><u>How to Resolve Skyrim’s Eternal Launch Screen Bug for Smooth Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-missing-desktop-icons-on-windows-11-solutions/"><u>How to Restore Missing Desktop Icons on Windows 11 - Solutions</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-realme-gt-3-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Realme GT 3 Fingerprint Lock</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, Does find my friends work on Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/newly-updated-anydvd-version-overcomes-previous-limitations-with-complete-css-key-deciphering-capabilities/"><u>Newly Updated AnyDVD Version Overcomes Previous Limitations with Complete CSS Key Deciphering Capabilities</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-problem-of-broken-touchpad-gestures-and-scrolls/"><u>Resolving the Problem of Broken Touchpad Gestures and Scrolls</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-nplus1-access-denied-when-listing-items-inside-containers-issue-easy-steps-and-tips/"><u>Solving Windows N+1: Access Denied When Listing Items Inside Containers Issue - Easy Steps and Tips</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/transform-your-ride-with-these-top-10-macwindows-srt-boosters-for-2024/"><u>Transform Your Ride with These Top 10 Mac/Windows SRT Boosters for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-resolving-issues-when-the-function-keys-arent-responding/"><u>Troubleshooting Steps: Resolving Issues When The Function Keys Aren't Responding</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-why-your-pc-wont-update-windows-easy-fixes-inside/"><u>Troubleshooting: Why Your PC Won't Update Windows – Easy Fixes Inside!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/video-organizer-software-efficient-content-management-system/"><u>Video Organizer Software - Efficient Content Management System</u></a></li>
</ul></div>

