---
title: Solving Charging Issues for Windows Surface PCs – Quick Tips & Tricks
date: 2025-02-05T23:49:48.208Z
updated: 2025-02-07T02:28:29.262Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving Charging Issues for Windows Surface PCs – Quick Tips & Tricks
excerpt: This Article Describes Solving Charging Issues for Windows Surface PCs – Quick Tips & Tricks
thumbnail: https://thmb.techidaily.com/20d5859d1451225abaa94d6d3c8c9cdada02fd525d9a47948cb889f866ae7774.jpg
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`` Click **Yes**  when prompted by User Account Control.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-17.png)

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

4) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

``

 2) Click **System** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8-12.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 5: Disable iCloud

 Some users reported that to disable iCloud in Task Manager fix the error for them. So make sure to try to disable icloud if you install one on Windows 10.

 1) Press**Shift** +**Ctrl** +**Esc** keys at the same time to open**Task Manager** .

 2) On Task Manager window, tap on the **Startup** pane. Then find and right-click on **iCloud Services** . Click **Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10-7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-web.techidaily.com/astering-fb-sharing-youtube-videos-directly/"><u>[New] Mastering FB Sharing YouTube Videos Directly</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-evaluating-earnings-the-effective-3-step-process-for-youtube-financial-analysis/"><u>[Updated] Evaluating Earnings The Effective 3-Step Process for YouTube Financial Analysis</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-free-frameworks-for-every-movie-epilogue-you-dream/"><u>2024 Approved Free Frameworks for Every Movie Epilogue You Dream</u></a></li>
<li><a href="https://fox-shield.techidaily.com/des-solutions-innovantes-pour-renforcer-la-securite-et-lintegrite-de-vos-backups/"><u>Des Solutions Innovantes Pour Renforcer La Sécurité Et L'Intégrité De Vos Backups</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-the-green-light-back-repairing-asus-laptop-webcam-issues-in-windows-10/"><u>Getting the Green Light Back: Repairing ASUS Laptop Webcam Issues in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-windows-update-failed-error-code-0x800705b4-on-windows-11/"><u>How to Fix the 'Windows Update Failed' Error (Code: 0X800705b4) on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-analysis-and-fixes-for-the-new-world-wont-start-with-eas-easy-anti-cheat/"><u>In Depth Analysis and Fixes for the 'New World Won't Start with EA's Easy Anti-Cheat'</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1726225578324-jpg-png/"><u>JPG, PNG 등을 포함한 다양한 형식으로 원시 이미지를 관리하는 강력한 온라인 도구</u></a></li>
<li><a href="https://extra-tips.techidaily.com/masterful-manipulation-speedy-stylization-techniques-for-win10-apps/"><u>Masterful Manipulation Speedy Stylization Techniques for WIN10 Apps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210014237-monitor-not-responding-fix-unsupported-signal-timings-now/"><u>Monitor Not Responding? Fix Unsupported Signal Timings Now</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/photo-flips-and-twists-essential-guide-to-ph-warping/"><u>Photo Flips & Twists Essential Guide to PH Warping</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-common-file-explorer-issues-in-windows-11/"><u>Quick Fixes for Common File Explorer Issues in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reboot-and-repair-windows-explorer-error/"><u>Reboot & Repair: Windows Explorer Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-required-incompatible-display-timeout-detected-on-your-screen/"><u>Solution Required: Incompatible Display Timeout Detected on Your Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-user-profile-service-sign-in-issues-in-windows-1011/"><u>Troubleshooting User Profile Service Sign-In Issues in Windows 10/11</u></a></li>
<li><a href="https://games-able.techidaily.com/update-home-screen-with-new-photo-ps5/"><u>Update Home Screen with New Photo (PS5)</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-get-noticed-the-top-10-animated-text-tools-for-social-media-and-more/"><u>Updated 2024 Approved Get Noticed The Top 10 Animated Text Tools for Social Media and More</u></a></li>
</ul></div>

