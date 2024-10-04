---
title: How to Fix the Missing Media Device Driver Errors on Your Computer
date: 2024-09-29T19:53:15.848Z
updated: 2024-10-03T23:22:49.899Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix the Missing Media Device Driver Errors on Your Computer
excerpt: This Article Describes How to Fix the Missing Media Device Driver Errors on Your Computer
thumbnail: https://thmb.techidaily.com/33f7a6674447c8f7173ff1c687707de6ab2b192d47bf8afae9f7fe02b3355e59.jpg
---

## The Ultimate Fix Guide for Overcoming Error 1068 in Windows – Expert Advice Included

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
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1521325/16446" target="_top" id="1521325">
  <img src="//a.impactradius-go.com/display-ad/16446-1521325" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1521325/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Right-click**Eaphost** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-script-to-screen-crafting-your-unique-youtube-tale/"><u>[New] 2024 Approved From Script to Screen Crafting Your Unique YouTube Tale</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-entertaining-videoland-audit-for-2024/"><u>[New] Entertaining Videoland Audit for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-enhancing-televised-experiences-with-fb-live-techniques/"><u>[New] In 2024, Enhancing Televised Experiences with FB Live Techniques</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-securing-virtual-triumphs-mastering-screen-captures-in-pc-games-for-2024/"><u>[New] Securing Virtual Triumphs - Mastering Screen Captures in PC Games for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-solutions-for-resolving-crackling-audio-issues-on-pcs-with-windows-107/"><u>Easy Solutions for Resolving Crackling Audio Issues on PCs with Windows 10/7</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/evaluating-the-jaco-smartpro-digital-tire-inflator-an-experts-guide-to-a-portable-and-high-performance-device/"><u>Evaluating the Jaco SmartPro Digital Tire Inflator: An Expert's Guide to a Portable and High-Performance Device</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-advice-on-optimal-live-cricket-broadcast-watching/"><u>Expert Advice on Optimal Live Cricket Broadcast Watching</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-your-lenovos-fingerprint-sensor-issues-in-no-time/"><u>Fixing Your Lenovo's Fingerprint Sensor Issues in No Time</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-forcibly-update-login-credentials-for-windows-accounts-admin-only/"><u>How To Forcibly Update Login Credentials for Windows Accounts (Admin Only)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-responsiveness-improved-solutions-for-windows-11-lags/"><u>Keyboard Responsiveness Improved – Solutions for Windows 11 Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/kodi-not-working-issues-solved/"><u>Kodi Not Working Issues [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/shift-key-malfunction-heres-how-you-can-resolve-it/"><u>Shift Key Malfunction? Here’s How You Can Resolve It</u></a></li>
<li><a href="https://games-able.techidaily.com/the-list-that-could-change-everything-7-games-for-a-new-era-with-ms/"><u>The List That Could Change Everything: 7 Games for a New Era with MS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-vanished-bluetooth-icon-on-your-pc-running-windows-10/"><u>Troubleshooting a Vanished Bluetooth Icon on Your PC Running Windows 지급자 10</u></a></li>
<li><a href="https://app-tips.techidaily.com/urgent-security-alert-critical-vulnerability-found-and-patched-in-popular-curl-tool-for-linux-systems-read-the-full-story-on-zdnet/"><u>Urgent Security Alert: Critical Vulnerability Found & Patched in Popular Curl Tool for Linux Systems - Read the Full Story on ZDNet</u></a></li>
</ul></div>

