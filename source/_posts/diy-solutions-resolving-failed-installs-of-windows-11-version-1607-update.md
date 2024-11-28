---
title: "DIY Solutions: Resolving Failed Installs of Windows 11 Version 1607 Update"
date: 2024-11-27T06:29:41.283Z
updated: 2024-11-28T08:35:00.973Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

4) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

``

 2) Click **System** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8-12.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 5: Disable iCloud

 Some users reported that to disable iCloud in Task Manager fix the error for them. So make sure to try to disable icloud if you install one on Windows 10.

 1) Press**Shift** +**Ctrl** +**Esc** keys at the same time to open**Task Manager** .

 2) On Task Manager window, tap on the **Startup** pane. Then find and right-click on **iCloud Services** . Click **Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10-7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-optimizing-personal-video-experience-building-an-organized-watch-later-list/"><u>[New] 2024 Approved Optimizing Personal Video Experience Building an Organized 'Watch Later' List</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-quick-recap-of-chromakey-and-green-screen-processes/"><u>[New] Quick Recap of Chromakey and Green Screen Processes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-fast-revenues-forecasting-toolkit-for-vids-for-2024/"><u>[Updated] Fast Revenues Forecasting Toolkit for Vids for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-create-compelling-images-on-iphone-with-these-10-principles/"><u>[Updated] In 2024, Create Compelling Images on iPhone with These 10 Principles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-the-port-reset-failed-error-on-windows-11s-usb-devices-tips-and-tricks/"><u>Dealing with the Port Reset Failed Error on Windows 11'S USB Devices – Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-recover-corrupt-system-components-on-your-windows-11-device/"><u>Effective Solutions to Recover Corrupt System Components on Your Windows 11 Device</u></a></li>
<li><a href="https://blog-min.techidaily.com/enhancing-gameplay-with-ai-driven-frame-generation-improved-fps-and-seamless-scene-changes/"><u>Enhancing Gameplay with AI-Driven Frame Generation: Improved FPS and Seamless Scene Changes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/exclusive-reviews-top-5-external-hdds-for-xbox-gamers-for-2024/"><u>Exclusive Reviews Top 5 External HDDs for Xbox Gamers for 2024</u></a></li>
<li><a href="https://media-tips.techidaily.com/experience-premium-surround-sound-with-the-bose-smart-bar-simple-yet-advanced-features-reviewed/"><u>Experience Premium Surround Sound with the Bose Smart Bar - Simple Yet Advanced Features Reviewed</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-xiaomi-14-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Tecno Spark 20? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-fix-how-to-address-could-not-write-crash-dump-glitches-in-wolfenstein-ii/"><u>In-Depth Fix: How to Address 'Could Not Write Crash Dump' Glitches in Wolfenstein II</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-overwatch-voice-connection-fixes-without-the-hassle/"><u>Mastering Overwatch Voice Connection Fixes Without the Hassle</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209636718-9781547573882-meditacao-aprenda-meditacao-permaneca-positivo-e-cure-se-embasado-cientificamente/"><u>Meditação: Aprenda Meditação, Permaneça Positivo E Cure-se (Embasado Cientificamente) | Free Book</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-ps4-sync-errors-effective-solutions-for-your-gaming-control-pad/"><u>Overcoming PS4 Sync Errors: Effective Solutions for Your Gaming Control Pad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-boot-not-detected-issues-on-your-device-easy-troubleshooting-steps-inside/"><u>Resolve Boot Not Detected Issues on Your Device - Easy Troubleshooting Steps Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-when-microsoft-defender-smartscreen-is-unresponsive/"><u>Troubleshooting Guide: When Microsoft Defender SmartScreen Is Unresponsive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-solutions-to-prevent-total-war-rome-remastered-from-crashing/"><u>Ultimate Solutions to Prevent Total War: Rome Remastered From Crashing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-miracast-on-incompatible-devices-essential-tips-for-a-smooth-connection/"><u>Unlocking Miracast on Incompatible Devices: Essential Tips for a Smooth Connection</u></a></li>
</ul></div>

