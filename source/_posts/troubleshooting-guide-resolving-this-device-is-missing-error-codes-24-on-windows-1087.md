---
title: "Troubleshooting Guide: Resolving 'This Device Is Missing' Error Codes (24) on Windows 10/8/7"
date: 2024-09-21T23:33:05.856Z
updated: 2024-09-28T16:36:27.540Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: Resolving 'This Device Is Missing' Error Codes (24) on Windows 10/8/7"
excerpt: "This Article Describes Troubleshooting Guide: Resolving 'This Device Is Missing' Error Codes (24) on Windows 10/8/7"
thumbnail: https://thmb.techidaily.com/cce90de001854095939cd22c7e555d9393bc0bdf8a9fe07be68597eb9b7713ab.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-access.techidaily.com/2024-approved-boost-engagement-crafting-the-perfect-instagram-unboxing/"><u>2024 Approved Boost Engagement Crafting the Perfect Instagram Unboxing</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-professional-grade-grid-tools-for-striking-instagram-posts/"><u>2024 Approved Professional-Grade Grid Tools for Striking Instagram Posts</u></a></li>
<li><a href="https://win11.techidaily.com/8-microsoft-apps-you-must-install-on-android-if-you-have-a-windows-pc/"><u>8 Microsoft Apps You Must Install on Android if You Have a Windows PC</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-xiaomi-redmi-note-12-pro-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Xiaomi Redmi Note 12 Pro 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-interactive-learning-landscapes-with-vr/"><u>In 2024, Interactive Learning Landscapes with VR</u></a></li>
<li><a href="https://extra-information.techidaily.com/nostalgic-portraits-retold-transforming-old-prints-to-digital/"><u>Nostalgic Portraits Retold Transforming Old Prints to Digital</u></a></li>
<li><a href="https://extra-support.techidaily.com/premium-webcam-options-tailored-for-efficient-zoom-meetings-for-2024/"><u>Premium Webcam Options Tailored for Efficient Zoom Meetings for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/recover-power-icon-in-windows-10-a-step-by-step-solution/"><u>Recover Power Icon in Windows 10: A Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-windows-unable-to-finish-setup-in-just-a-few-easy-steps/"><u>Resolve 'Windows Unable to Finish Setup' In Just a Few Easy Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-pc-exploring-sfc-and-dism-tools-for-fixing-windows-10-issues/"><u>Reviving Your PC: Exploring SFC and DISM Tools for Fixing Windows 10 Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-overcome-the-challenge-of-forcing-a-shutdown-in-windows-11-systems/"><u>Solution Found! Overcome the Challenge of Forcing a Shutdown in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-approach-correcting-msxml3-protocol-error-code-0x88-without-hassle/"><u>Step-by-Step Approach: Correcting Msxml3 Protocol Error (Code 0X88지) Without Hassle</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-dealing-with-windows-combination-key-malfunction-in-win-11-or-win-10/"><u>Step-by-Step Solution: Dealing With Windows Combination Key Malfunction in Win 11 or Win 지정 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-installing-oddworld-soulstorm-on-your-windows-computer/"><u>Successfully Installing Oddworld: Soulstorm on Your Windows Computer</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-things-you-should-evaluate-prior-to-investing-in-video-capturing-gear/"><u>Top Things You Should Evaluate Prior to Investing in Video Capturing Gear</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-resolving-issues-with-the-at-symbol-on-your-device/"><u>Troubleshooting Steps: Resolving Issues with the 'At' Symbol on Your Device</u></a></li>
<li><a href="https://some-guidance.techidaily.com/understanding-the-enhanced-5gplus-feature-on-your-smartphone-ios-vs-android/"><u>Understanding the Enhanced 5G+ Feature on Your Smartphone: IOS Vs. Android</u></a></li>
</ul></div>

