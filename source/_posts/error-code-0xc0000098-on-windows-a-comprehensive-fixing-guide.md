---
title: "Error Code 0XC0000098 on Windows: A Comprehensive Fixing Guide"
date: 2025-01-16T19:29:10.104Z
updated: 2025-01-19T17:11:30.603Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 0XC0000098 on Windows: A Comprehensive Fixing Guide"
excerpt: "This Article Describes Error Code 0XC0000098 on Windows: A Comprehensive Fixing Guide"
thumbnail: https://thmb.techidaily.com/4d7dde3a99efac5f6bdb879d88148e0d5b48fb1025ad045c8786c79687920a30.jpg
---

## Fixing Error 1068 in Windows: A Comprehensive Guide - SOLUTION FOUND

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-decoding-instagrams-max-video-content/"><u>[New] 2024 Approved Decoding Instagram's Max Video Content</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-solve-facebook-messenger-not-sending-videos-on-iphone-and-android/"><u>[New] 2024 Approved Solve “Facebook Messenger Not Sending Videos” On iPhone and Android</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-elite-6-software-for-audiovisual-translation/"><u>[New] Elite 6 Software for Audio/Visual Translation</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-mac-users-launch-your-own-sports-videography-hub/"><u>[Updated] 2024 Approved Mac Users Launch Your Own Sports Videography Hub</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-obstacles-in-windows-11-installation-error-code-802-explained-and-solved/"><u>Bypassing Obstacles in Windows 11 Installation - Error Code 802# Explained and Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/copy-errors-on-the-latest-win-11-version/"><u>Copy Errors on the Latest Win 11 Version</u></a></li>
<li><a href="https://driver-install.techidaily.com/download-lenovos-high-quality-hd-sound-card-software-at-no-cost/"><u>Download Lenovo's High-Quality HD Sound Card Software at No Cost</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-solutions-to-repair-non-functioning-lenovo-biometric-sensor/"><u>Easy Solutions to Repair Non-Functioning Lenovo Biometric Sensor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-guide-why-some-screens-lack-pen-or-touch-input-options-solutions-included/"><u>Fix Guide: Why Some Screens Lack Pen or Touch Input Options – Solutions Included</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-realme-c67-4g-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/guida-completa-come-risolvere-i-problemi-di-riproduzione-dei-file-mkv-su-pc-e-mac/"><u>Guida Completa: Come Risolvere I Problemi Di Riproduzione Dei File MKV Su PC E Mac</u></a></li>
<li><a href="https://some-techniques.techidaily.com/high-definition-videography-unveiled-by-yi-for-2024/"><u>High Definition Videography Unveiled by Yi for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-ultimate-visual-verdict-sj6-meets-xiaomis-yi-visionaries/"><u>In 2024, The Ultimate Visual Verdict SJ6 Meets Xiaomi’s Yi Visionaries</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/master-a-new-tongue-best-9-free-language-resources/"><u>Master a New Tongue: Best 9 Free Language Resources</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-remedies-to-reactivate-your-lenovos-shortcut-keys/"><u>Quick Remedies to Reactivate Your Lenovo's Shortcut Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-mic-not-working-errors-on-windows-10-pcs/"><u>Resolving 'Mic Not Working' Errors on Windows 10 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-for-preventing-self-activating-boot-sequences-on-windows-10-devices/"><u>Solutions for Preventing Self-Activating Boot Sequences on Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-step-by-step-for-error-1000-on-windows-os-versions-7-8-and-10/"><u>Troubleshooting Step-by-Step for Error 1000 on Windows OS Versions 7, 8 & 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-win32-app-crashes-error-code-0xc0000098/"><u>Ultimate Guide: Resolving Win32 App Crashes (Error Code 0xC0000098)</u></a></li>
</ul></div>

