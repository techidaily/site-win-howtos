---
title: Resolve 'There Was an Issue Resetting Your Computer' Error in Windows 10 [Guide]
date: 2025-02-13T01:26:33.813Z
updated: 2025-02-17T00:20:22.567Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolve 'There Was an Issue Resetting Your Computer' Error in Windows 10 [Guide]
excerpt: This Article Describes Resolve 'There Was an Issue Resetting Your Computer' Error in Windows 10 [Guide]
thumbnail: https://thmb.techidaily.com/40dacce0cb547ba8c0e5ef7c77101f1f8b7f316b2e066f32c3a4f5370faddce4.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`` 2) Type **dcomcnfg**  and press Enter to open **Component Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-19.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## Fix 2: Re-register the ExplorerFrame.dll file

``

`
` ``

 1) Press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  +**X** key together, then click**Command Prompt(Admin)** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`` Click **Yes**  when prompted by User Account Control.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-17.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

``

``

`` 3) Click **Default apps**  on the left pane. Then on the right pane, scroll down to click **Reset**  under the **Reset to the Microsoft recommended defaults**  section.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7-11.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-inclusive-panel-of-easeus-reviewers/"><u>[New] In 2024, Inclusive Panel of EaseUS Reviewers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-seamless-techniques-for-effective-iphone-screen-captures/"><u>[Updated] Seamless Techniques for Effective Iphone Screen Captures</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-best-pc-vr-headsets-ranked/"><u>2024 Approved Best PC VR Headsets Ranked</u></a></li>
<li><a href="https://tech-hub.techidaily.com/elevating-your-presentations-top-7-ai-solutions/"><u>Elevating Your Presentations: Top 7 AI Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-successfully-launching-oddworld-soulstorm-on-your-windows-computer/"><u>Guide to Successfully Launching Oddworld: Soulstorm on Your Windows Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-i-resolved-the-bug-that-made-my-software-misbehave-guide/"><u>How I Resolved The Bug That Made My Software Misbehave [GUIDE]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-renderer-start-failure-corrected-fixes-of-2021/"><u>How to Resolve 'Renderer Start Failure [Corrected Fixes of 2021]'</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-honor-magic-5-lite-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Honor Magic 5 Lite Phone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-nubia-red-magic-9-pro-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Nubia Red Magic 9 Pro</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://solve-manuals.techidaily.com/insurtech-evolution-insights-expert-interview-with-forrester/"><u>InsurTech Evolution Insights: Expert Interview with Forrester</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-stuck-on-the-loading-screen-master-this-2024-troubleshooting-and-start-guide/"><u>PUBG Stuck on the Loading Screen? Master This 2024 Troubleshooting and Start Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-custom-user-settings-failure-no-longer-an-issue/"><u>Resolved: Custom User Settings Failure No Longer an Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-resource-protection-failed-on-this-computer-error/"><u>Resolving: 'Windows Resource Protection Failed on This Computer' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-steps-to-resolve-usb-flash-drive-unrecognized-issues/"><u>Simple Steps to Resolve 'USB Flash Drive Unrecognized' Issues</u></a></li>
<li><a href="https://extra-resources.techidaily.com/step-by-step-iphone-guide-creating-and-editing-languid-video-sequences/"><u>Step by Step iPhone Guide Creating & Editing Languid Video Sequences</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-swiftly-overcome-0x80070652-windows-update-glitches/"><u>Troubleshooting Guide: Swiftly Overcome 0X80070652 Windows Update Glitches</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-flip-rotate-and-enhance-top-10-video-editing-software/"><u>Updated In 2024, Flip, Rotate, and Enhance Top 10 Video Editing Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-is-my-mouse-right-click-not-working-in-windows-10-solutions-inside/"><u>Why Is My Mouse Right Click Not Working in Windows 10? Solutions Inside!</u></a></li>
</ul></div>

