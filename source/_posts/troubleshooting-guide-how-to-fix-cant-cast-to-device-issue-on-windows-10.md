---
title: "Troubleshooting Guide: How to Fix 'Can't Cast to Device' Issue on Windows 10"
date: 2024-12-09T22:35:48.706Z
updated: 2024-12-13T16:37:56.344Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: How to Fix 'Can't Cast to Device' Issue on Windows 10"
excerpt: "This Article Describes Troubleshooting Guide: How to Fix 'Can't Cast to Device' Issue on Windows 10"
thumbnail: https://thmb.techidaily.com/6604e06a9acd007eaa4a4b27af2a49c5989610b00458bd7fc4b8189171f1981b.jpg
---

## How to Fix 'Class Not Registered' Errors on Your Windows 10 Device - Solutions Inside

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 1: Fix DCOM(**Distributed Component Object Model)** errors

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Open the app again to see if it goes fine.

``

## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-footage.techidaily.com/new-boost-your-content-reach-the-expert-guide-to-youtubes-featured-channels-for-2024/"><u>[New] Boost Your Content Reach The Expert Guide to Youtube's Featured Channels for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-what-is-svchostexe-netsvcs-and-fix-its-high-network-usage-issue/"><u>[Solved] What Is svchost.exe (Netsvcs) and Fix Its High Network Usage Issue</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-shoppers-ultimate-list-of-top-rated-webcams/"><u>[Updated] 2024 Approved Shopper’s Ultimate List of Top-Rated Webcams</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-current-compendium-of-questions-for-captivating-audio-clips-for-2024/"><u>[Updated] Current Compendium of Questions for Captivating Audio Clips for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-historical-gems-art-unshackled-by-laws/"><u>[Updated] Historical Gems Art Unshackled by Laws</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-your-personalized-music-compilation/"><u>[Updated] In 2024, Your Personalized Music Compilation</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-essentials-of-sharing-music-compilations-online/"><u>2024 Approved The Essentials of Sharing Music Compilations Online</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unveiling-windows-11s-hidden-secrets-for-media-upload/"><u>2024 Approved Unveiling Windows 11'S Hidden Secrets for Media Upload</u></a></li>
<li><a href="https://discover-exclusive.techidaily.com/mp4-dvd-flick/"><u>読み込まれないMP4問題: DVD Flickで解決策を見つける方法</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-fixes-for-malfunctioning-system-components-in-windows-11-pcs/"><u>Efficient Fixes for Malfunctioning System Components in Windows 11 PCs</u></a></li>
<li><a href="https://solve-news.techidaily.com/gratuit-conversion-de-mov-en-m4v-sur-moovavni-en-ligne-et-facile-a-utiliser/"><u>Gratuit Conversion De MOV en M4V Sur Moovavni - En Ligne Et Facile À Utiliser</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-open-apps-using-your-systems-default-admin-profile/"><u>How To Successfully Open Apps Using Your System's Default Admin Profile</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Infinix Note 30 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-pubg-effective-strategies-to-combat-and-prevent-game-lags/"><u>Mastering PUBG: Effective Strategies to Combat and Prevent Game Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-for-activating-bluetooth-connectivity-in-windows-11-and-10/"><u>Step-by-Step Tutorial for Activating Bluetooth Connectivity in Windows 11 & 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-fixes-and-tips-for-overcoming-error-1603-fatal-installation-issue/"><u>Successful Fixes & Tips for Overcoming Error 1603 - Fatal Installation Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-your-bootstrapper-keeps-crashing-on-startup/"><u>Troubleshooting Steps When Your Bootstrapper Keeps Crashing on Startup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210807114-usb-tethering-on-windows-10-easily/"><u>USB Tethering on Windows 10 Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-stuck-heres-how-you-can-get-your-computer-to-properly-power-off/"><u>Windows 11 Stuck? Here's How You Can Get Your Computer to Properly Power Off</u></a></li>
</ul></div>

