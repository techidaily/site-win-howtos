---
title: Step-by-Step Solution for 'Contact Failure with DHCP Server' Problems
date: 2025-01-17T20:22:54.520Z
updated: 2025-01-19T20:39:08.377Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for 'Contact Failure with DHCP Server' Problems
excerpt: This Article Describes Step-by-Step Solution for 'Contact Failure with DHCP Server' Problems
thumbnail: https://thmb.techidaily.com/e576fa6a569d314a929d202ace0124c24bb9f5c7c863ef858ebb7371b469a682.jpg
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

## Fix 1: Fix DCOM(**Distributed Component Object Model)** errors

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

`` 2) Type **dcomcnfg**  and press Enter to open **Component Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-19.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 2) Go to **Component Services**  \> **Computers**  \> **My Computer**  on the Component Services window. Then double-click on **DCOM Config** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-17.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Then a few DCOM Configuration warning messages will pop up. Click **Yes**  for each one.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-18.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-behind-the-scenes-insights-for-instagram-story-audience/"><u>[New] 2024 Approved Behind the Scenes Insights for Instagram Story Audience</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-bringing-heartwarmth-to-the-winter-5-snug-cinematographic-tips/"><u>[New] In 2024, Bringing Heartwarmth to the Winter 5 Snug Cinematographic Tips</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-clever-circumventions-for-edgenuity-video-course-skipping/"><u>[New] In 2024, Clever Circumventions for Edgenuity Video Course Skipping</u></a></li>
<li><a href="https://article-files.techidaily.com/new-samsungs-latest-bd-edition-k850-update/"><u>[New] Samsung's Latest BD Edition - K850 Update</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-all-inclusive-rundown-whats-behind-the-google-podcast-app/"><u>2024 Approved All-Inclusive Rundown What's Behind the Google Podcast App?</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/148712-9780687083329-addiction/"><u>Addiction | Free Book</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-troubleshooting-error-code-0x800f0922-in-windows-10-updates/"><u>Easy Fixes for Troubleshooting Error Code 0X800f0922 in Windows 10 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211913941-error-resolution-overcoming-the-0x887a0006-issue-with-simple-steps/"><u>Error Resolution - Overcoming the 0X887A0006 Issue with Simple Steps!</u></a></li>
<li><a href="https://buynow-help.techidaily.com/how-the-hisense-50h8f-delivers-quality-4k-viewing-without-breaking-the-bank-tv-review/"><u>How the Hisense 50H8F Delivers Quality 4K Viewing Without Breaking the Bank: TV Review</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-c12-plus-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on C12 Plus</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-system-diagnostics-service-not-active-a-comprehensive-fix/"><u>Overcoming 'System Diagnostics Service Not Active' - A Comprehensive Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-updating-missing-widevine-cdm-on-your-windows-system/"><u>Step-by-Step Guide: Updating Missing Widevine CDM on Your Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-overcoming-common-minecraft-opengl-errors/"><u>Step-by-Step Solutions: Overcoming Common Minecraft OpenGL Errors</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-basics-of-net-neutrality-simplified-for-everyone/"><u>The Basics of Net Neutrality Simplified for Everyone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solving-class-not-found-problems-in-windows-11/"><u>Troubleshooting and Solving 'Class Not Found' Problems in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-your-orgs-influence-managing-windows-setup-parameters/"><u>Understanding Your Org's Influence: Managing Windows Setup Parameters</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-10-shutdown-woes-here-are-effective-solutions/"><u>Win 10 Shutdown Woes? Here Are Effective Solutions</u></a></li>
</ul></div>

