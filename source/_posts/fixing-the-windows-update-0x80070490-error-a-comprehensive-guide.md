---
title: "Fixing the Windows Update 0X80070490 Error: A Comprehensive Guide"
date: 2024-10-11T22:57:04.155Z
updated: 2024-10-15T18:15:50.083Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the Windows Update 0X80070490 Error: A Comprehensive Guide"
excerpt: "This Article Describes Fixing the Windows Update 0X80070490 Error: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/4e54d2ee69e2d3cc5b62664f281e174d4bc506ec5c304888c5062a8c04d6107f.jpg
---

## Fixing Error 1068 in Windows: A Comprehensive Guide - SOLUTION FOUND

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528689/16446" target="_top" id="1528689">
  <img src="//a.impactradius-go.com/display-ad/16446-1528689" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528689/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
5. Right-click**Dhcp** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111968/7443" target="_top" id="2111968">
  <img src="//a.impactradius-go.com/display-ad/7443-2111968" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111968/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105863/7443" target="_top" id="2105863">
  <img src="//a.impactradius-go.com/display-ad/7443-2105863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105863/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

### Solution 3: Update your network adapter driver

 This problem could be also due to**a corrupted, old or missing network driver** on your system. So you can solve it through updating your network driver.

 Updating drivers require Internet connection on your computer. If your computer can’t access the wireless network, try to connect your computer to a wired network connection or, you can try the[Offline Scan](https://tools.techidaily.com/drivereasy/download/) feature of Driver Easy.

You can update your network driver either manually or automatically.

#### Manual driver update

 You can update your network driver manually by going to the manufacturer’s website for your network adapter, say,**Realtek** , and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

#### Automatic driver update

 If you don’t have the time, patience or computer skills to update your network driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly.

 You can click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the Pro version which comes with**full support** and a**30-day money back guarantee** . You’ll be prompted to upgrade when you click Update All.)  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b891580f3aca.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997690/19272" target="_top" id="1997690">
  <img src="//a.impactradius-go.com/display-ad/19272-1997690" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997690/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

You’re done. Feel free to comment below if you have any question.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-seize-your-social-media-videos-top-extensions-and-downloaders-for-firefox/"><u>[New] 2024 Approved Seize Your Social Media Videos! Top Extensions and Downloaders for Firefox</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-avoiding-strikes-youtube-edition-for-2024/"><u>[New] Avoiding Strikes YouTube Edition for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-peer-into-the-future-with-apeaksofts-screen-capture-trends-2023/"><u>[Updated] In 2024, Peer Into the Future with Apeaksoft’s Screen Capture Trends 2023</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-comprehensive-guide-to-changing-console-voice/"><u>[Updated] The Comprehensive Guide to Changing Console Voice</u></a></li>
<li><a href="https://article-helps.techidaily.com/bringing-images-to-life-expert-level-photo-text-editing/"><u>Bringing Images to Life Expert-Level Photo Text Editing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/detect-and-install-missing-audiovideo-hardware-drivers-on-your-pc/"><u>Detect & Install Missing Audio/Video Hardware Drivers on Your PC</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/discover-the-power-of-asus-ac68u-tri-band-router-speedy-secure-and-revolutionary-5g-wireless-review/"><u>Discover the Power of Asus AC68U Tri-Band Router - Speedy, Secure, and Revolutionary 5G Wireless Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x80070490-demystified-effective-solutions-for-fixing-windows-update-glitches/"><u>Error Code 0X80070490 Demystified: Effective Solutions for Fixing Windows Update Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-this-device-is-not-plugged-in-error-codes-on-windows-1087/"><u>Fixing 'This Device Is Not Plugged In' Error Codes on Windows 10/8/7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/from-pitch-black-to-full-throttle-solving-startup-display-issues-in-monster-hunter-world/"><u>From Pitch Black to Full Throttle: Solving Startup Display Issues in Monster Hunter: World</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-internet-explorer-has-stopped-working/"><u>How to Fix Internet Explorer Has Stopped Working</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-breaking-into-the-livestream-scene-on-youtube-with-under-a-thousand-views/"><u>In 2024, Breaking Into the Livestream Scene on YouTube with Under a Thousand Views</u></a></li>
<li><a href="https://review-topics.techidaily.com/iphone-6-data-recovery-software-to-recover-lost-ios-data-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>iPhone 6® Data Recovery Software to Recover Lost iOS® Data | Stellar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-your-windows-update-isnt-active/"><u>Troubleshooting Steps When Your Windows Update Isn't Active</u></a></li>
<li><a href="https://win-howtos.techidaily.com/type-error-resolved-repairing-the-common-faulty-keyboard-problems/"><u>Type Error Resolved: Repairing the Common Faulty Keyboard Problems</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-lava-blaze-2-5g-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Lava Blaze 2 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-over-wifi-woes-effective-techniques-to-get-airpods-working-on-windows-11/"><u>Win Over WiFi Woes: Effective Techniques to Get AirPods Working on Windows 11</u></a></li>
</ul></div>

