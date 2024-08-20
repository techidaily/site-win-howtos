---
title: Diagnosing & Solving Windows System Driver Power Malfunctions
date: 2024-08-19T07:56:38.187Z
updated: 2024-08-20T07:56:38.187Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing & Solving Windows System Driver Power Malfunctions
excerpt: This Article Describes Diagnosing & Solving Windows System Driver Power Malfunctions
thumbnail: https://thmb.techidaily.com/76cb87841297f436650576e356aab992c1ddd1148ccda3c73b6601c2eaf3c2ce.jpg
---

## Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7be8093704.jpg)

 Your computer startup very slow? or you cannot log in Windows on your computer with the standard user account? After you log in with an administrative account, you’re seeing an error saying:

**Failed to connect to a windows services**
  
 **Windows could not connect to the System Event Notification Service service.**

 I know you’re likely frustrating. But don’t worry. Usually it’s easy to solve out. Read on to see how…

## Try these fixes

 The methods below have helped other users solve the problem. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. **[Check the setting of System Event Notification Service on your computer](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset your Winsock Catalog](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your video card driver](https://tools.techidaily.com/drivereasy/download/)**
4. **[Uninstall the KB2952664 update](https://tools.techidaily.com/drivereasy/download/)**
5. [**Remove klhkum.dll**](https://tools.techidaily.com/drivereasy/download/)

 The following screenshots are from Windows 10\. But you can also follow the steps if you’re having the problem on Windows 7.

### Fix 1: Check the setting of System Event Notification Service on your computer

 You may have the problem due to the incorrect setting of System Event Notification Service.  
 Follow these steps to modify the setting:

1. On your keyboard, hold down the**Windows logo key** and**R** to invoke the Run box.
2. Type**services.msc** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf596c06c.jpg)
3. Right-click**System Event Notification Service** , then select**Restart** . If Restart grayed out, click**Start** instead.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf9e2c9b8.jpg)
4. Right-click System Event Notification Service again, this time select**Properties** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bfcea31f4.jpg)
5. Set the**Startup type** to**Automatic** . Then click **Apply**  \> **OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c08c50e91.jpg)

 Restart your computer to see if the error has gone. If you still see the error, you have something else to try…

---

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 2: Reset your Winsock Catalog

 You very likely have the problem on your computer that joins in a domain network. You could have problem due to some interference of your Winsock Catalog setting.

Follow these steps to reset your Winsock Catalog:

1. On your keyboard, hold down the**Windows logo key** and press**R** to invoke the Run box.
2. Type**cmd** , then press**Shift + Ctrl + Enter** keys together.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c0804d3b9.jpg)
3. An elevated Command Prompt would be open. Type the following command and press Enter.  
**netsh winsock reset**

 Restart your computer to see if the error has gone. If you still see the error, don’t worry, move onto the next methods.  
 If resetting Winsock worked temporarily, you can move to Fix 5.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
### Fix 3: Update your video card driver

 You could probably encounter this error if the video card driver on your computer is outdated, incompatible or corrupt. So you should**update your video card driver** to see if it fixes your problem. If you don’t have the time, patience or skills to update the driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to be troubled by the wrong driver you would be downloading, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the**FREE** or the**Pro version** of Driver Easy. But with the Pro version it takes just 2 steps (and you get**full support and a 30-day money back guarantee** ):

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c1c42f3f2.jpg)
3. C  lick **Update All** to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All).  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Note** : You can do it for free if you like, but it’s partly manual.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2297ff06.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Restart your computer to see if the error has gone. If the error persists, don’t give up hope, see if the last method could help you…

---

### Fix 4: Uninstall the KB2952664 update

 According to many users’ report, this error could be due to the**KB2952664** Windows Update. If none of the methods above helps you, go with the following steps to**uninstall the KB2952664 update** on your computer:

1. On your keyboard, press the**Windows logo key** and**R** to invoke the Run box.
2. Type**control** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c29a46965.jpg)
3. Select**Uninstall a program** under**Programs** when**View by Category** selected.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2c7bbb7b.jpg)
4. Click View installed updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2f3ae739.jpg)
5. Find and right-click the update with KB2952664, then Uninstall.

Restart your computer to see if the error has gone.

---

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 5: Remove klhkum.dll

 If you have to reset Winsock tens of times a day, you need to try this method. What you should do is checking whether you have “klhkum.dll” or not.

 klhkum.dll’s description is “**System Interceptors PDK usermode service interceptor** ” and it’s intercepting the system when it shouldn’t.  
 So how to remove it? Follow the guide:

1. Press**Ctrl+Shift+Esc** to open the Task Manager.
2. Click the**Startup** tab and find**klhkum.dll** process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-52-10.jpg)
3. Right-click on it and choose**Disable** . You can also open its file location and delete it permanently.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-55-36.jpg)
4. Restart your computer to see if the error has gone.

 One more tip: If you’re using Kaspersky security software and possibly on Windows 7, you need to turn off Kaspersky manually to fix the issue.

---

 Tada! Hopefully this helps. Feel free to comment below with your own experiences.

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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-the-ultimate-guide-to-making-money-with-vimeo-monetization/"><u>[New] 2024 Approved  The Ultimate Guide to Making Money with Vimeo Monetization</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-expert-endorsed-techniques-for-iphone-audio-retrieval/"><u>[New] Expert-Endorsed Techniques for iPhone Audio Retrieval</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-volume-curves-in-ableton-live/"><u>[New] Mastering Volume Curves in Ableton Live</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-mastering-the-art-of-recording-macs-roblox-sessions/"><u>[Updated] 2024 Approved  Mastering the Art of Recording Mac's Roblox Sessions</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-top-five-revolutionary-facebook-enhancements/"><u>[Updated] 2024 Approved  Top Five Revolutionary Facebook Enhancements</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-novice-to-connoisseur-transform-your-sub4sub-experience-now/"><u>[Updated] In 2024, From Novice to Connoisseur  Transform Your Sub4sub Experience Now</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-tailored-instagram-filters-a-step-by-step-process/"><u>[Updated] Tailored Instagram Filters  A Step-by-Step Process</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-smoothing-playback-the-truth-behind-frozen-photo-booth-videos/"><u>2024 Approved  Smoothing Playback  The Truth Behind Frozen Photo Booth Videos</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/addressing-the-c1900101-error-in-windows-11-installation/"><u>Addressing the C1900101 Error in Windows 11 Installation</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/androids-premier-choice-top-10-free-fb-video-extractor-for-2024/"><u>Android's Premier Choice  Top 10 Free FB Video Extractor for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/browse-these-top-10-online-markets-for-one-of-a-kind-gift-boxes-for-2024/"><u>Browse These Top 10 Online Markets for One-of-a-Kind Gift Boxes for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-error-2024-on-dota-2-by-modifying-the-rendering-api-a-step-by-step-guide/"><u>Bypass Error 2024 on Dota 2 by Modifying the Rendering API - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-a-damaged-volume-error-code-0x80071ac3-a-troubleshooting-guide/"><u>Dealing with a Damaged Volume (Error Code 0X80071AC3) - A Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/device-silence-amidst-configuration-success/"><u>Device Silence Amidst Configuration Success</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/easy-ways-to-translate-tiktok-videos/"><u>Easy Ways to Translate TikTok Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-fixing-common-minecraft-lan-connectivity-challenges/"><u>Expert Advice: Fixing Common Minecraft LAN Connectivity Challenges</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-microsoft-wi-fi-dock-connection-issues-in-windows-10-a-comprehensive-guide/"><u>Fixing Microsoft Wi-Fi Dock Connection Issues in Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-failed-renderer-start-up-in-your-browser-new-patch-released/"><u>Fixing the Failed Renderer Start-Up in Your Browser (New Patch Released)</u></a></li>
<li><a href="https://driver-download.techidaily.com/freshly-updated-retrieve-geforce-rtx-3070-ti-graphics-card-drivers-for-win-11-8-and-7-from-nvidia/"><u>Freshly Updated: Retrieve GeForce RTX 3070 Ti Graphics Card Drivers for Win 11, 8 & 7 From NVIDIA</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-successfully-reactivating-your-diagnostic-service/"><u>Guide: Successfully Reactivating Your Diagnostic Service</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-12-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 12 without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-effortlessly-correct-the-0x800f0831-glitch-using-windows-updates/"><u>How to Effortlessly Correct the 0X800F0831 Glitch Using Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-0x80070490-faulty-update-issue-on-your-pc-solved/"><u>How to Resolve 0X80070490 Faulty Update Issue on Your PC (Solved!)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ig-tik-combined-expertise-for-smooth-integration/"><u>IG-Tik Combined Expertise for Smooth Integration</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-realme-12-pro-5g-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Realme 12 Pro 5G</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-poco-c55-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Poco C55</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-leading-camera-innovations-revealed-future-edition/"><u>In 2024, Leading Camera Innovations Revealed - Future Edition</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-oneplus-nord-n30-5g-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 OnePlus Nord N30 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-touchscreen-troubleshooting-in-windows-10-a-comprehensive-5-way-approach/"><u>Mastering Touchscreen Troubleshooting in Windows 10: A Comprehensive 5-Way Approach</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-x3daudio17dll-non-existence-issues/"><u>Overcome X3DAudio1_7.dll Non-Existence Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-service-failed-problem-with-your-windows-1011-account-expert-solutions/"><u>Overcoming 'Service Failed' Problem with Your Windows 10/11 Account - Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reactivate-keyboard-glow-essential-fixes-for-non-functioning-backlight-on-your-macpc/"><u>Reactivate Keyboard Glow: Essential Fixes for Non-Functioning Backlight on Your Mac/PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-steam-game-files-not-found-error-fix-guide/"><u>Resolved: Steam Game Files Not Found Error Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-apex-legends-simple-cheat-detection-mishap/"><u>Resolving Apex Legends' Simple Cheat Detection Mishap</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-11-night-light-problems-a-comprehensive-tutorial/"><u>Solving Windows 11 Night Light Problems - A Comprehensive Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-file-retrieval-tips-restoring-missing-privileges-successfully/"><u>Steam File Retrieval Tips: Restoring Missing Privileges Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-windows-driver-power-management-errors/"><u>Step-by-Step Guide: Correcting Windows Driver Power Management Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-code-24-fixing-device-not-found-error-on-windows-1187/"><u>Troubleshooting Code 24: Fixing 'Device Not Found' Error on Windows 11/8/7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-your-non-responsive-laptop-trackpad-issues/"><u>Troubleshooting Guide: Fixing Your Non-Responsive Laptop Trackpad Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-login-issues-in-windows-1011-with-user-profile-service-errors/"><u>Troubleshooting Login Issues in Windows 10/11 with User Profile Service Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-how-to-fix-computer-not-closing-windows-10/"><u>Troubleshooting Steps: How To Fix Computer Not Closing Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-resolving-the-dreaded-0x800f0922-update-glitch-in-windows-10/"><u>Troubleshooting Tips for Resolving the Dreaded 0X800f0922 Update Glitch in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-10-how-to-fix-a-stuck-update-process/"><u>Troubleshooting Windows 10: How to Fix a Stuck Update Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-x3daudio17dll-play-games-effortlessly/"><u>Troubleshooting X3DAudio1_7.dll, Play Games Effortlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-amozekioe11-not-working-heres-how-you-can-repair-it/"><u>Windows Amozekioe11 Not Working? Here's How You Can Repair It</u></a></li>
</ul></div>
