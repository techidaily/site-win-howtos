---
title: "Winning Against Windows Update Glitches: A Comprehensive Fix Guide"
date: 2025-01-10T17:05:36.924Z
updated: 2025-01-13T16:15:35.393Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Winning Against Windows Update Glitches: A Comprehensive Fix Guide"
excerpt: "This Article Describes Winning Against Windows Update Glitches: A Comprehensive Fix Guide"
thumbnail: https://thmb.techidaily.com/154ba651f58f7b61c6d13ed51a3e08aab825faff32ad0111bfbaa0c8293dac8c.jpg
---

## Winning the Battle Against MsMpEng.exe: Reducing CPU Usage in Windows 11 – Effective Strategies Inside

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Want us to fix the problem for you?

 If the fix above didn’t work, and you don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

 That’s it – top 3 fixes for your **MsMpEng.exe-eating-up-too-much-CPU-in-Windows 10** problem. Hope this helps and feel free to comment below if you have any further questions. 🙂

* [high CPU](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://fox-hovers.techidaily.com/new-from-capture-to-creation-discover-the-best-montage-apps-for-smartphones-for-2024/"><u>[New] From Capture to Creation Discover the Best Montage Apps for Smartphones for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-safe-methods-to-fast-forward-in-spotify-files-for-2024/"><u>[Updated] Safe Methods to Fast-Forward in Spotify Files for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-the-complete-igtv-user-manual/"><u>2024 Approved The Complete IGTV User Manual</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dell-usb-keyboard-and-wireless-mouse-issues-solutions-for-common-problems/"><u>Dell USB Keyboard & Wireless Mouse Issues - Solutions for Common Problems</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/eagle-eyes-for-blocks-no-more-chat-from-someone/"><u>Eagle Eyes for Blocks No More Chat From Someone</u></a></li>
<li><a href="https://win-bytes.techidaily.com/easy-ways-to-resize-text-on-your-screen-in-windows-11-with-yl-software-solutions/"><u>Easy Ways to Resize Text on Your Screen in Windows 11 with YL Software Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-a-broken-dell-webcam-connection-in-windows-environment/"><u>Expert Tips for Repairing a Broken Dell Webcam Connection in Windows Environment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gadget-fixation-fixed-keys/"><u>Gadget Fixation: Fixed Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/google-chrome-black-screen-fixes-a-step-by-step-guide/"><u>Google Chrome Black Screen Fixes - A Step-by-Step Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-asus-rog-phone-8-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Asus ROG Phone 8 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ideal-frequency-of-smartphone-upgrades-when-should-you-consider-a-new-model/"><u>Ideal Frequency of Smartphone Upgrades: When Should You Consider a New Model?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-infinix-zero-30-5g-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Infinix Zero 30 5G? Try These Fixes</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ingenious-tips-on-keeping-your-cell-phone-powered-without-a-standard-adapter/"><u>Ingenious Tips on Keeping Your Cell Phone Powered Without a Standard Adapter</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209546383-quick-fixes-overcome-the-silence-on-netflix-restore-sound-now/"><u>Quick Fixes: Overcome the Silence on Netflix – Restore Sound Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rectified-problem-with-non-functional-keyboard-input/"><u>Rectified Problem with Non-Functional Keyboard Input</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-speedy-path-to-a-clean-windows-10-setup-made-effortless/"><u>The Speedy Path to a Clean Windows 10 Setup Made Effortless</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-when-your-pc-doesnt-recognize-the-hard-disk/"><u>Troubleshooting Guide: When Your PC Doesn't Recognize the Hard Disk</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-non-charging-microsoft-surface-a-complete-guide/"><u>Troubleshooting Your Non-Charging Microsoft Surface: A Complete Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-samsung-galaxy-a14-4g-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Samsung Galaxy A14 4G? | Dr.fone</u></a></li>
</ul></div>

