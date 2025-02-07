---
title: "Troubleshooting Guide: Restoring Your Lost Desktop Icons on Windows 10 [FIXED]"
date: 2025-02-03T20:01:43.793Z
updated: 2025-02-07T08:50:54.395Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: Restoring Your Lost Desktop Icons on Windows 10 [FIXED]"
excerpt: "This Article Describes Troubleshooting Guide: Restoring Your Lost Desktop Icons on Windows 10 [FIXED]"
thumbnail: https://thmb.techidaily.com/691a0d9f6910ad496390c7d88febf7f6a054b2a526595909cdbd9daef2d1d484.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-leverage-social-blades-platform-for-in-depth-video-analytics/"><u>[New] 2024 Approved Leverage Social Blade's Platform for In-Depth Video Analytics</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ditprime-vision-for-2024/"><u>[New] EditPrime Vision for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-igtv-video-placement-to-facebook-networks-5-ways/"><u>[Updated] In 2024, IGTV Video Placement to Facebook Networks (5 Ways)</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-infinix-gt-10-pro-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Infinix GT 10 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-quietude-on-the-silver-screen-a-study/"><u>2024 Approved Quietude on the Silver Screen A Study</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-temporary-directory-restrictions-resolving-file-execution-errors-and-setup-interruptions/"><u>Bypass Temporary Directory Restrictions - Resolving File Execution Errors and Setup Interruptions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207952817-easy-solutions-to-common-file-explorer-problems-in-windows-10/"><u>Easy Solutions to Common File Explorer Problems in Windows 10!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-apocalypse-device-fatality-scenario/"><u>Error Apocalypse: Device Fatality Scenario</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-fixing-bluetooth-connectivity-issues-in-windows-11-quickly-and-effortlessly/"><u>Guide to Fixing Bluetooth Connectivity Issues in Windows 11 Quickly and Effortlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-no-audio-output-device-is-installed-error-in-windows-1111/"><u>How to Fix No Audio Output Device Is Installed Error in Windows 11/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-a-malfunctioning-laptop-keyboard-on-pc-tips-for-win7win8win10-users/"><u>How to Repair a Malfunctioning Laptop Keyboard on PC: Tips for Win7/Win8/Win10 Users</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-realme-12-pro-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Realme 12 Pro 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/ideal-hosts-elevating-youtube-video-audiences/"><u>Ideal Hosts Elevating YouTube Video Audiences</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Lava Blaze 2? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/index-of-varied-photographic-and-videography-instruments/"><u>Index of Varied Photographic and Videography Instruments</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-silent-issues-restoring-audio-on-anthem-with-windows-11/"><u>Resolving Silent Issues: Restoring Audio on Anthem with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-getting-the-clipboard-working-again-in-windows-11/"><u>Step-by-Step Solutions: Getting the Clipboard Working Again in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixes-resolving-installation-issues-with-steam-game-updates/"><u>Troubleshooting Fixes: Resolving Installation Issues with Steam Game Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-screen-mirroring-windows-11-solutions/"><u>Troubleshooting Screen Mirroring: Windows 11 Solutions</u></a></li>
</ul></div>

