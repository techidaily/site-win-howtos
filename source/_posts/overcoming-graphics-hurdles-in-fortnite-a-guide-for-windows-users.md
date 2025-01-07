---
title: "Overcoming Graphics Hurdles in Fortnite: A Guide for Windows Users"
date: 2024-12-31T17:33:19.738Z
updated: 2025-01-07T04:03:16.786Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming Graphics Hurdles in Fortnite: A Guide for Windows Users"
excerpt: "This Article Describes Overcoming Graphics Hurdles in Fortnite: A Guide for Windows Users"
thumbnail: https://thmb.techidaily.com/94949839e44613400bd5d58f4fe6242909222f90165f20a133ed7c6cab443aea.png
---

## The Ultimate Fix Guide for Overcoming Error 1068 in Windows – Expert Advice Included

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-instagrams-trust-tales-decoding-the-power-of-selfies/"><u>[New] 2024 Approved Instagram's Trust Tales Decoding the Power of Selfies</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-best-mp4-player-you-should-know/"><u>2024 Approved Best MP4 Player You Should Know</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-unlock-iphone-15-plus-without-passcode-or-face-id-by-drfone-ios/"><u>3 Ways to Unlock iPhone 15 Plus without Passcode or Face ID</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-apples-m2-powered-mac-mini-at-a-record-low-only-479-detailed-analysis-on-zdnet/"><u>Discover Apple's M2-Powered Mac Mini at a Record Low: Only $479 - Detailed Analysis on ZDNet</u></a></li>
<li><a href="https://some-guidance.techidaily.com/free-winx-video-editor-edit-videos-on-windows-11-10-and-7-download-now/"><u>Free WinX Video Editor: Edit Videos on Windows 11, 10 & 7 - Download Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-control-back-how-to-restore-functionality-of-usb-peripherals-on-windows-7-pcs/"><u>Getting Control Back: How to Restore Functionality of USB Peripherals on Windows 7 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/handling-and-resolving-google-chromes-not-responding-situation-effectively/"><u>Handling and Resolving Google Chrome's Not Responding Situation Effectively</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-enable-usb-debugging-on-a-locked-oppo-find-x6-pro-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Oppo Find X6 Pro Phone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-common-issues-troubleshooting-a-non-booting-laptop-or-desktop/"><u>Overcoming Common Issues - Troubleshooting a Non-Booting Laptop or Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-steam-disk-writing-issues-smoothly/"><u>Step-by-Step Guide: Correcting Steam Disk Writing Issues Smoothly</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Lava Blaze Curve 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-compatibility-resolving-connection-failures-for-microsoft-wireless-display-adapters/"><u>Windows 11 Compatibility: Resolving Connection Failures for Microsoft Wireless Display Adapters</u></a></li>
<li><a href="https://tech-haven.techidaily.com/workforce-upheaval-will-chatgpt-replace-humans/"><u>Workforce Upheaval: Will ChatGPT Replace Humans?</u></a></li>
</ul></div>

