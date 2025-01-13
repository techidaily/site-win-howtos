---
title: Effective Solutions to Resolve the Windows 10 Intermittent Rebooting Dilemma
date: 2025-01-08T16:59:19.198Z
updated: 2025-01-13T16:12:34.797Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Effective Solutions to Resolve the Windows 10 Intermittent Rebooting Dilemma
excerpt: This Article Describes Effective Solutions to Resolve the Windows 10 Intermittent Rebooting Dilemma
thumbnail: https://thmb.techidaily.com/5c2d24edaaf4b6dd8b5262f3555ac32c929e36e44030c42b24af4ca2cf08c3a5.jpg
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

## Fix 1: Fix DCOM(**Distributed Component Object Model)** errors

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

`` 2) Type **dcomcnfg**  and press Enter to open **Component Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-19.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

4) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://digital-screen-recording.techidaily.com/new-reviewing-vlc-as-a-multimedia-recorder/"><u>[New] Reviewing VLC as a Multimedia Recorder</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-top-editing-apps-revolutionize-your-photo-backgrounds-for-2024/"><u>[New] Top Editing Apps Revolutionize Your Photo Backgrounds for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-top-10-most-accessible-costless-lut-tools-unveiled/"><u>[Updated] The Top 10 Most Accessible, Costless LUT Tools Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208965391-bluetooth-connection-woes-on-windows-10-how-to-get-your-paired-devices-really-connected-and-working/"><u>Bluetooth Connection Woes on Windows 10 - How to Get Your Paired Devices Really Connected and Working!</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-11-pro-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>Complete Fixes To Solve Apple iPhone 11 Pro Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decode-error-28-in-windows-device-manager-diagnosis-and-solutions-revealed/"><u>Decode Error 28 in Windows Device Manager: Diagnosis and Solutions Revealed</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-the-leading-voice-assistants-and-smart-speakers/"><u>Exploring the Leading Voice Assistants & Smart Speakers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixation-guide-eliminating-unwanted-cursor-blink-on-screen/"><u>Fixation Guide: Eliminating Unwanted Cursor Blink on Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-systemprofile-desktop-inaccessible-issue-in-windows/"><u>Fixing the ‘SystemProfile Desktop Inaccessible’ Issue in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-i-fixed-my-disconnected-equipment-attached-to-the-computer-network/"><u>How I Fixed My Disconnected Equipment Attached to the Computer Network</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-recover-and-repair-corrupted-registry-entries-on-windows-1011/"><u>How To Recover and Repair Corrupted Registry Entries on Windows 10/11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-your-motorola-g24-power-lock-screen-password-by-drfone-android/"><u>How to Reset your Motorola G24 Power Lock Screen Password</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-malfunctioning-your-drivers-with-windows-device-manager-in-windows-11-by-drivereasy-guide/"><u>Identify malfunctioning your drivers with Windows Device Manager in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-remedies-to-restore-functionality-of-hp-laptops-stickyunresponsive-buttons/"><u>Quick Remedies to Restore Functionality of HP Laptop's Sticky/Unresponsive Buttons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-deactivated-keys-in-win11-os/"><u>Rectifying Deactivated Keys in Win11 OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-semaphore-timeout-error-code-0x80070079-now-fixed/"><u>Resolved: 'Semaphore Timeout Error Code 0X80070079' Now Fixed</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-vivo-y100a-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Vivo Y100A ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-recurrent-win11-freezes/"><u>Tackling Recurrent Win11 Freezes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/transforming-vids-10-leading-apps-for-instagram-video-editing-for-2024/"><u>Transforming Vids 10 Leading Apps for Instagram Video Editing for 2024</u></a></li>
</ul></div>

