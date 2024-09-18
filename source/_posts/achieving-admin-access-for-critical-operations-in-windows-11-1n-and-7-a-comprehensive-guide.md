---
title: "Achieving Admin Access for Critical Operations in Windows 11, 1N & 7: A Comprehensive Guide"
date: 2024-09-15T17:19:42.274Z
updated: 2024-09-17T19:46:53.390Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Achieving Admin Access for Critical Operations in Windows 11, 1N & 7: A Comprehensive Guide"
excerpt: "This Article Describes Achieving Admin Access for Critical Operations in Windows 11, 1N & 7: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/8a309f6aebab825a6cd0baff1d0b8550d45fadce34f31fb21e5a5f2109ae3299.jpg
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

``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

4) Open the app again to see if it goes fine.

``

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://discord-videos.techidaily.com/new-in-2024-deleting-a-discord-server-desktop-and-mobile-guide/"><u>[New] In 2024, Deleting a Discord Server Desktop & Mobile Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instagram-stories-secrets-for-success/"><u>[Updated] In 2024, Instagram Stories Secrets for Success</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-blur-a-part-of-a-picture-on-pcmobile/"><u>2024 Approved How to Blur a Part of a Picture on PC/Mobile</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-ipados-update-manual-a-complete-version-history/"><u>Comprehensive iPadOS Update Manual: A Complete Version History</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-ensure-uninterrupted-gaming-experience-with-house-flipper-2-pc-version/"><u>How To Ensure Uninterrupted Gaming Experience with House Flipper 2 (PC Version)</u></a></li>
<li><a href="https://win-blog.techidaily.com/improving-sifu-gameplay-overcoming-stuttering-issues-and-frame-drops-on-pc/"><u>Improving Sifu Gameplay: Overcoming Stuttering Issues and Frame Drops on PC</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/prime-selector-20-twitters-animated-treasure-chest/"><u>Prime Selector 2.0 Twitter's Animated Treasure Chest</u></a></li>
<li><a href="https://android-unlock.techidaily.com/remove-the-lock-screen-fingerprint-of-your-asus-rog-phone-7-ultimate-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Asus ROG Phone 7 Ultimate</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-steps-for-setting-up-titanium-kodi-fridge-on-latest-kodi-versions-including-leia-18/"><u>Successful Steps for Setting Up Titanium Kodi Fridge on Latest Kodi Versions Including Leia 18.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-step-by-step-tutorial-on-integrating-subtitles-in-handbrake/"><u>The Ultimate Step-by-Step Tutorial on Integrating Subtitles in HandBrake</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-12-free-software-convert-wmv-files-into-mp4-format-with-ease/"><u>Top 12 Free Software: Convert WMV Files Into MP4 Format with Ease</u></a></li>
<li><a href="https://blog-min.techidaily.com/ultimate-digital-storage-tips-for-dvd-collections-in-202-the-future-of-dvd-preservation-transitioning-to-digital-formats/"><u>Ultimate Digital Storage Tips for DVD Collections in 202 The Future of DVD Preservation: Transitioning to Digital Formats</u></a></li>
<li><a href="https://win-howtos.techidaily.com/surfacehddssddvd/"><u>スパッと解決! Surface上で外付けHDD/SSDを用いたDVD視聴不能問題に対するツール</u></a></li>
</ul></div>

