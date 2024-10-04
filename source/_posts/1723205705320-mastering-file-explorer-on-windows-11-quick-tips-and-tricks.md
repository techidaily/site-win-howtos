---
title: "Mastering File Explorer on Windows 11: Quick Tips and Tricks"
date: 2024-09-30T16:02:54.889Z
updated: 2024-10-04T16:01:23.986Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Mastering File Explorer on Windows 11: Quick Tips and Tricks"
excerpt: "This Article Describes Mastering File Explorer on Windows 11: Quick Tips and Tricks"
thumbnail: https://thmb.techidaily.com/05547d7adb90fbf06f532d01e335fbdece6e08beadfb934a2bc64b999d114da7.jpg
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049388/7443" target="_top" id="2049388">
  <img src="//a.impactradius-go.com/display-ad/7443-2049388" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049388/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1983446">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983446.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983446">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983446.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983446%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983446/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411">
  <img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134239/18498" target="_top" id="2134239">
  <img src="//a.impactradius-go.com/display-ad/18498-2134239" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134239/18498" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-premier-selection-of-best-indoor-android-games-no-wi-fi-required/"><u>[Updated] 2024 Approved Premier Selection of Best Indoor Android Games (No Wi-Fi Required)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-best-editing-app-for-iphones-choose-between-cameo-and-filmorago/"><u>[Updated] In 2024, Best Editing App for iPhones Choose Between Cameo & FilmoraGo</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-capturing-motion-with-precision-how-to-choose-between-30-and-60fps/"><u>[Updated] In 2024, Capturing Motion with Precision How to Choose Between 30 and 60Fps</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-unleashing-the-power-of-edit-in-tiktok-video-creation/"><u>[Updated] In 2024, Unleashing the Power of Edit in TikTok Video Creation</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-sj4000-stylish-essentials-a-comprehensive-list/"><u>[Updated] SJ4000 Stylish Essentials A Comprehensive List</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/directing-viewers-across-platforms-igtv-and-facebook/"><u>Directing Viewers Across Platforms IGTV & Facebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eliminate-win11-restart-cycles/"><u>Eliminate Win11 Restart Cycles</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/facebook-short-videos-and-everything-about-them/"><u>Facebook Short Videos and Everything About Them</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-media-sharing-on-windows-11-solving-common-cast-to-device-errors/"><u>Mastering Media Sharing on Windows 11: Solving Common 'Cast to Device' Errors</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/seamless-driver-update-process-for-brother-mfc-7360n-on-windows-tips-and-tricks/"><u>Seamless Driver Update Process for Brother MFC-7360N on Windows - Tips & Tricks!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-high-cpu-error-linked-to-runtime-broker-in-windows-11-systems/"><u>Step-by-Step Fix for High CPU Error Linked to Runtime Broker in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-update-errors-resolved-a-comprehensive-fix-guide/"><u>Windows Update Errors Resolved: A Comprehensive Fix Guide</u></a></li>
</ul></div>

