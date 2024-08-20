---
title: Solving Non-Functional Scroll Wheel Issues on Synaptics Trackpads Post-Windows 11 Update
date: 2024-08-19T07:57:37.880Z
updated: 2024-08-20T07:57:37.880Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving Non-Functional Scroll Wheel Issues on Synaptics Trackpads Post-Windows 11 Update
excerpt: This Article Describes Solving Non-Functional Scroll Wheel Issues on Synaptics Trackpads Post-Windows 11 Update
thumbnail: https://thmb.techidaily.com/46220d4e5de752c9f9121bc5fe5314f52ef333630dc70248125ef90566a42a71.jpg
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

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
4) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

``

 2) Click **System** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8-12.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-which-should-you-use-obs-studio-or-bandicam/"><u>[New] Which Should You Use, OBS Studio or Bandicam?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-what-is-svchostexe-netsvcs-and-fix-its-high-network-usage-issue/"><u>[Solved] What Is svchost.exe (Netsvcs) and Fix Its High Network Usage Issue</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-your-path-to-perfect-videos-with-any-of-these-7-free-tools/"><u>[Updated] 2024 Approved  Your Path to Perfect Videos with Any of These 7 Free Tools</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-google-pixel-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/autonomous-exposure-control-the-magic-behind-auto-and-smart-hdr-for-2024/"><u>Autonomous Exposure Control  The Magic Behind Auto and Smart HDR for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/banish-troublesome-glitches-proven-methods-to-correct-0x80072efd-mishaps-on-your-windows-11-machine/"><u>Banish Troublesome Glitches: Proven Methods to Correct 0X80072EFD Mishaps on Your Windows 11 Machine</u></a></li>
<li><a href="https://fox-links.techidaily.com/behind-the-scenes-how-to-master-voice-manipulation-with-free-tools-for-2024/"><u>Behind the Scenes  How to Master Voice Manipulation with Free Tools for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-call-logs-from-oppo-reno-10-5g-by-fonelab-android-recover-call-logs/"><u>Best Android Data Recovery - undelete lost call logs from Oppo Reno 10 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-address-fatal-installation-error-understanding-error-1603/"><u>Effective Solutions to Address Fatal Installation Error: Understanding Error 1603</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-fixes-for-malfunctioning-system-components-in-windows-11-pcs/"><u>Efficient Fixes for Malfunctioning System Components in Windows 11 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-handling-and-correcting-critical-directx-error-situations/"><u>Expert Tips on Handling and Correcting Critical DirectX Error Situations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-unresponsive-file-explorer-problem-in-windows-10-step-by-step-solution/"><u>Fixing the Unresponsive File Explorer Problem in Windows 10 - Step by Step Solution</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-videos-on-samsung-galaxy-s24-ultra-by-fonelab-android-recover-video/"><u>How to restore wiped videos on Samsung Galaxy S24 Ultra</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-open-apps-using-your-systems-default-admin-profile/"><u>How To Successfully Open Apps Using Your System's Default Admin Profile</u></a></li>
<li><a href="https://extra-information.techidaily.com/how-to-transcribe-speech-to-text-in-microsoft-word-learn-it-here/"><u>How to Transcribe Speech to Text in Microsoft Word  Learn It Here</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pixel-power-play-best-speedy-game-applications/"><u>In 2024, Pixel Power Play  Best Speedy Game Applications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-display-repair-how-to-solve-the-persistent-white-screen-problem/"><u>Laptop Display Repair: How to Solve the Persistent White Screen Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-pubg-effective-strategies-to-combat-and-prevent-game-lags/"><u>Mastering PUBG: Effective Strategies to Combat and Prevent Game Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-touchpad-navigation-resolve-stuckunresponsive-scroll-wheel-issues/"><u>Mastering Touchpad Navigation: Resolve Stuck/Unresponsive Scroll Wheel Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-your-system-addressing-the-audio-device-graphs-impact-on-cpu-load-in-windows/"><u>Optimizing Your System: Addressing the Audio Device Graph's Impact on CPU Load in Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/originality-awaits-create-unique-business-logos-with-template-editing-for-2024/"><u>Originality Awaits  Create Unique Business Logos with Template Editing for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-cpu-consumption-caused-by-wudfhostexe-on-windows-10-systems/"><u>Resolve Excessive CPU Consumption Caused by wudfhost.exe on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-for-activating-bluetooth-connectivity-in-windows-11-and-10/"><u>Step-by-Step Tutorial for Activating Bluetooth Connectivity in Windows 11 & 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-fixes-and-tips-for-overcoming-error-1603-fatal-installation-issue/"><u>Successful Fixes & Tips for Overcoming Error 1603 - Fatal Installation Issue</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-foundations-of-vsco-photo-manipulation-for-2024/"><u>The Foundations of VSCO Photo Manipulation for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/the-ultimate-list-top-websites-for-downloading-pc-games-for-2024/"><u>The Ultimate List Top Websites for Downloading PC Games for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-computers-fail-to-detect-audio-devices/"><u>Troubleshooting Steps When Computers Fail to Detect Audio Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-your-bootstrapper-keeps-crashing-on-startup/"><u>Troubleshooting Steps When Your Bootstrapper Keeps Crashing on Startup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-strategies-resolve-unknown-usb-device-and-port-reset-errors-on-windows-10/"><u>Troubleshooting Strategies: Resolve 'Unknown USB Device' And Port Reset Errors on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210807114-usb-tethering-on-windows-10-easily/"><u>USB Tethering on Windows 10 Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-1011-missing-visual-settings/"><u>Windows 10/11: Missing Visual Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-stuck-heres-how-you-can-get-your-computer-to-properly-power-off/"><u>Windows 11 Stuck? Here's How You Can Get Your Computer to Properly Power Off</u></a></li>
<li><a href="https://win-howtos.techidaily.com/yac539-yamahaaturbosound-ii-sound-module-based-on-the-ymf768ymu768-dsp-plus-midi-synthesizer-plus-codec-and-128-mb-of-spiram-for-sample-storage-instead-of-r145/"><u>YAC539 - Yamaha'aturboSound II Sound Module Based on the YMF768/YMU768 (DSP + MIDI Synthesizer + Codec) and 128 MB of SPIRAM for Sample Storage Instead of ROM. It Also Includes a Second Audio Input Connector</u></a></li>
</ul></div>
