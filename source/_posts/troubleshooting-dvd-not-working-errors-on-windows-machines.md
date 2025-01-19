---
title: Troubleshooting DVD Not Working Errors on Windows Machines
date: 2025-01-13T17:29:57.643Z
updated: 2025-01-19T18:21:15.459Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting DVD Not Working Errors on Windows Machines
excerpt: This Article Describes Troubleshooting DVD Not Working Errors on Windows Machines
thumbnail: https://thmb.techidaily.com/5f9bdb089a72cbfbce20351e13d8c69867a47335c73b8710c5509727c5e15028.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-twitcast-audible-and-mp4-edition/"><u>[New] 2024 Approved TwitCast Audible & MP4 Edition</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-conquer-screen-capture-in-depth-windows-pc-guide-for-live-tv-recording/"><u>[New] In 2024, Conquer Screen Capture In-Depth Windows PC Guide for Live TV Recording</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-exclusive-soundstage-shows/"><u>[New] In 2024, Exclusive Soundstage Shows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-the-evolutionary-path-of-roguelike-games/"><u>[Updated] 2024 Approved The Evolutionary Path of Roguelike Games</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-trouble-connecting-your-keyboard-to-your-pc-made-simple/"><u>Bluetooth Trouble? Connecting Your Keyboard to Your PC Made Simple</u></a></li>
<li><a href="https://win-howtos.techidaily.com/boost-your-wow-experience-eliminate-latency-problems-today/"><u>Boost Your WoW Experience: Eliminate Latency Problems Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/copy-and-paste-error-solutions-for-windows-11-users-a-complete-fixer/"><u>Copy & Paste Error Solutions for Windows 11 Users: A Complete Fixer</u></a></li>
<li><a href="https://extra-resources.techidaily.com/endless-buffering-solving-photo-booth-freezes/"><u>Endless Buffering Solving Photo Booth Freezes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-address-and-repair-fatal-errors-in-black-ops-4/"><u>Expert Tips to Address and Repair Fatal Errors in Black Ops 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-windows-11-audio-issues-a-step-by-step-guide-to-restoring-volume-functionality/"><u>Fix Windows 11 Audio Issues: A Step-by-Step Guide to Restoring Volume Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/identified-absence-of-api-dll-l1-1/"><u>Identified Absence of API DLL L1-1</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-11-stalling-during-installation-how-to/"><u>Overcoming Windows 11 Stalling During Installation – How To</u></a></li>
<li><a href="https://article-helps.techidaily.com/pivoting-careers-from-novice-to-industry-veteran-for-2024/"><u>Pivoting Careers From Novice to Industry Veteran for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-gpu-usage-with-windows-desktop-window-manager-learn-5-fixes/"><u>Resolve Excessive GPU Usage with Windows' Desktop Window Manager - Learn 5 Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-user-profile-services-failure-and-sign-in-issues-in-windows-10-and-11/"><u>Resolving User Profile Services Failure and Sign-In Issues in Windows 10 & 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unleash-energy-selecting-the-ultimate-workout-melodies/"><u>Unleash Energy Selecting the Ultimate Workout Melodies</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-top-tiktok-watermark-removal-tools-to-remove-logos-for-free/"><u>Updated Top TikTok Watermark Removal Tools to Remove Logos for Free</u></a></li>
</ul></div>

