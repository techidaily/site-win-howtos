---
title: "DIY Solutions: Resolving Failed Installs of Windows 11 Version 1607 Update"
date: 2024-12-20T23:23:29.889Z
updated: 2024-12-22T19:43:05.459Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 2) Go to **Component Services**  \> **Computers**  \> **My Computer**  on the Component Services window. Then double-click on **DCOM Config** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-17.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Open the app again to see if it goes fine.

``

## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-navigating-through-the-best-tools-to-monitor-instagram-metrics-effectively/"><u>[New] Navigating Through the Best Tools to Monitor Instagram Metrics Effectively</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unveiling-hidden-potential-a-deep-dive-into-background-eraser-in-ps/"><u>[New] Unveiling Hidden Potential A Deep Dive Into Background Eraser in PS</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-top-ios-and-android-photo-blur-tools-for-2024/"><u>[Updated] Top iOS & Android Photo Blur Tools for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-xiaomi-civi-3-disney-100th-anniversary-edition-support-avchd-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Does Xiaomi Civi 3 Disney 100th Anniversary Edition support AVCHD video?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/gain-extensive-engagement-master-the-view-multiplier/"><u>Gain Extensive Engagement Master the View Multiplier</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208360473-get-your-youtube-sound-back-addressing-and-repairing-audio-renderer-errors-in-windows-1nvite-the-audio-troubleshooting-community-with-expert-tips/"><u>Get Your YouTube Sound Back: Addressing and Repairing Audio Renderer Errors in Windows 1Nvite the Audio Troubleshooting Community with Expert Tips.</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/getting-started-with-vn-video-editor-on-pc-a-review/"><u>Getting Started with VN Video Editor on PC A Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-connectivity-with-destiny-2-servers-when-theyre-down/"><u>How to Restore Connectivity with Destiny 2 Servers When They're Down</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-perfecting-the-green-screen-essential-techniques/"><u>In 2024, Perfecting the Green Screen Essential Techniques</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pinnacle-of-brainy-content-general-knowledge-top-11/"><u>In 2024, Pinnacle of Brainy Content General Knowledge Top 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/mastering-4k-movie-viewing-a-comprehensive-guide-to-watching-films-in-ultra-hd-on-your-apple-tv/"><u>Mastering 4K Movie Viewing: A Comprehensive Guide to Watching Films in Ultra HD on Your Apple TV</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-building-errors-resolved-load-up-without-interruption/"><u>PUBG Building Errors Resolved: Load Up Without Interruption</u></a></li>
<li><a href="https://win-howtos.techidaily.com/red-screen-resolved-step-by-step-fix-for-common-software-glitches/"><u>Red Screen Resolved: Step-by-Step Fix for Common Software Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-windows-11-update-error-0xc1900208-step-by-step-tutorial/"><u>Resolve Your Windows 11 Update Error (0xC1900208) - Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-fix-a-persistent-laptop-displaying-only-a-white-screen/"><u>Resolved: How to Fix a Persistent Laptop Displaying Only a White Screen</u></a></li>
</ul></div>

