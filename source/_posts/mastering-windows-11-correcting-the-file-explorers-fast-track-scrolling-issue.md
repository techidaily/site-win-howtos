---
title: "Mastering Windows 11: Correcting the File Explorer's Fast Track Scrolling Issue"
date: 2025-02-10T20:05:09.510Z
updated: 2025-02-16T16:40:22.901Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Mastering Windows 11: Correcting the File Explorer's Fast Track Scrolling Issue"
excerpt: "This Article Describes Mastering Windows 11: Correcting the File Explorer's Fast Track Scrolling Issue"
thumbnail: https://thmb.techidaily.com/56026dcff0736582c2fe4e321c8c74705a564d75fd36c3fc8b04cf6e73d4d3c9.jpg
---

## Master the Fix for 'Class Not Registered' Problem in Windows 11 - Effective Solutions Await

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 1: Fix DCOM(**Distributed Component Object Model)** errors

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

`` 2) Type **dcomcnfg**  and press Enter to open **Component Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-19.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Click **Default apps**  on the left pane. Then on the right pane, scroll down to click **Reset**  under the **Reset to the Microsoft recommended defaults**  section.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7-11.png)

``

``

4) Open the app again to see if it goes fine.

 Note: If you’ve installed iCloud on your Windows 10, you can try the fix below if all the fixes above don’t help.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 5: Disable iCloud

 Some users reported that to disable iCloud in Task Manager fix the error for them. So make sure to try to disable icloud if you install one on Windows 10.

 1) Press**Shift** +**Ctrl** +**Esc** keys at the same time to open**Task Manager** .

 2) On Task Manager window, tap on the **Startup** pane. Then find and right-click on **iCloud Services** . Click **Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10-7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-docs.techidaily.com/treamlining-visual-storytelling-with-youtube-videos/"><u>[New] Streamlining Visual Storytelling with YouTube Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-windows-10-wont-shut-down-restarts-instead/"><u>[Solved] Windows 10 Won’t Shut Down, Restarts Instead</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-a-comprehensive-guide-to-changing-avatars-and-statuses-on-discord-for-2024/"><u>[Updated] A Comprehensive Guide to Changing Avatars & Statuses on Discord for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-optimal-5-filters-for-deep-blue-cinematography-for-2024/"><u>[Updated] Optimal 5 Filters for Deep Blue Cinematography for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-login-obstacles-in-microsoft-store-quickly/"><u>Bypass Login Obstacles in Microsoft Store Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-methods-to-get-your-usb-flash-drive-recognized-by-windowsmac-quickly/"><u>Effective Methods to Get Your USB Flash Drive Recognized by Windows/Mac Quickly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-your-steelseries-arctis-5-headsets-broken-microphone-no-more-sorry/"><u>Expert Tips for Repairing Your SteelSeries Arctis 5 Headset's Broken Microphone (NO MORE SORRY)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-airpods-not-connecting-to-windows-1011-2024-tips/"><u>How to Fix AirPods Not Connecting to Windows 10/11 – 2024 Tips</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-disseminating-tweeted-videos-on-the-worlds-biggest-social-site/"><u>In 2024, Disseminating Tweeted Videos on the World's Biggest Social Site</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-from-zero-to-hero-rising-in-popularity-with-vimeo-experts/"><u>In 2024, From Zero to Hero Rising in Popularity with Vimeo Experts</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-depth-review-of-budget-friendly-clouds-for-2024/"><u>In-Depth Review of Budget-Friendly Clouds for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/mastering-facebook-8-top-movie-downloader-rankings/"><u>Mastering Facebook #8 Top Movie Downloader Rankings</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/meet-the-game-changer-in-budget-gaming-minisforums-innovative-affordable-156-144-hz-1440p-portable-monitor-for-just-189/"><u>Meet the Game-Changer in Budget Gaming - Minisforum’s Innovative, Affordable 15.6” 144 Hz 1440P Portable Monitor for Just $189</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-issues-with-starting-your-hosted-network-feature-on-windows-10-devices/"><u>Overcoming Issues with Starting Your Hosted Network Feature on Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210538704-resolving-problem-during-restore-mistake-in-windows-10-fixed/"><u>Resolving 'Problem During Restore' Mistake in Windows 10 – Fixed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723201180829-resolving-windows-update-error-code-0x80cuh0002-quickly-and-easily/"><u>Resolving Windows Update Error Code 0X80cuh0002 Quickly and Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-fixes-for-windows-11-users-struggling-with-the-disappearing-bluetooth-feature/"><u>Simple Fixes for Windows 11 Users Struggling with the Disappearing Bluetooth Feature!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-fix-for-nonfunctional-steam-voice-chatting-feature/"><u>Step-by-Step Fix for Nonfunctional Steam Voice Chatting Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-successfully-update-your-pc-with-fixes-for-error-0x800f0922-on-windows-11/"><u>Troubleshooting Tips: Successfully Update Your PC with Fixes for Error 0X800f0922 on Windows 11</u></a></li>
</ul></div>

