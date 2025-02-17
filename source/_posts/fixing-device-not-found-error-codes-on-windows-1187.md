---
title: Fixing 'Device Not Found' Error Codes on Windows 11/8/7
date: 2025-02-11T18:43:18.190Z
updated: 2025-02-16T19:10:51.614Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing 'Device Not Found' Error Codes on Windows 11/8/7
excerpt: This Article Describes Fixing 'Device Not Found' Error Codes on Windows 11/8/7
thumbnail: https://thmb.techidaily.com/f35affd0446f81f879a70f50fd131f599003c290d87b21cce9966af54d527118.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Right-click**Eaphost** under the Services section to select**Export** .  

 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-clips.techidaily.com/updated-crucial-collections-8-innovative-products-to-boost-your-professional-edge-for-2024/"><u>[Updated] Crucial Collections 8 Innovative Products to Boost Your Professional Edge for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-mirrored-worldviews-on-insta-discover-100-reflective-captions/"><u>[Updated] In 2024, Mirrored Worldviews on Insta - Discover 100 Reflective Captions</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-steps-to-manage-video-watcher-restrictions-on-youtube-for-2024/"><u>[Updated] Steps to Manage Video Watcher Restrictions on Youtube for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-free-tailor-made-templates-for-concluding-audio/"><u>2024 Approved Free, Tailor-Made Templates for Concluding Audio</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-optimize-capture-smooth-screenshots-with-dell-models/"><u>2024 Approved Optimize Capture Smooth Screenshots with Dell Models</u></a></li>
<li><a href="https://games-able.techidaily.com/avoiding-costly-hdr-top-6-reasons-for-gamers/"><u>Avoiding Costly HDR: Top 6 Reasons for Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/critical-solutions-for-windows-10-access-denied-problems-within-containers-expertly-explained/"><u>Critical Solutions for Windows 10 Access Denied Problems Within Containers - Expertly Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/from-dark-to-bright-repairing-google-chromes-unexpected-blackout-issues/"><u>From Dark to Bright: Repairing Google Chrome's Unexpected Blackout Issues</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-guide-to-unlock-your-poco-f5-5g-by-drfone-android/"><u>Full Guide to Unlock Your Poco F5 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-your-windows-10-bluetooth-back-on-track-with-our-step-by-step-guide/"><u>Get Your Windows 10 Bluetooth Back on Track with Our Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-disabling-half-decked-keyboard-and-touchpad-while-connected-to-a-mouse-on-windows-11/"><u>Guide to Disabling HALF-DECKED Keyboard and Touchpad While Connected to a Mouse on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-corsair-keyboard-back-in-action-after-malfunction/"><u>How to Get Your Corsair Keyboard Back in Action After Malfunction</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-sony-xperia-10-v-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Sony Xperia 10 V?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transform-viewing-experience-adding-subtitles-on-windows-media-player/"><u>In 2024, Transform Viewing Experience Adding Subtitles on Windows Media Player</u></a></li>
<li><a href="https://win-howtos.techidaily.com/interactive-entertainment-pauses-pc-life/"><u>Interactive Entertainment Pauses PC Life</u></a></li>
<li><a href="https://facebook.techidaily.com/mastering-facebook-pages-admins-onboard-guide/"><u>Mastering Facebook Pages: Admins Onboard Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-pubg-startup-failures-a-detailed-tutorial-for-gamers-and-techies/"><u>Solving PUBG Startup Failures : A Detailed Tutorial for Gamers and Techies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-solving-astro-a40-microphone-issues-step-by-step-guide/"><u>Successfully Solving Astro A40 Microphone Issues - Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-10-touchpad-scrolling-problems-a-step-by-step-guide/"><u>Troubleshooting Windows 10 Touchpad Scrolling Problems: A Step-by-Step Guide</u></a></li>
</ul></div>

