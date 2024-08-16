---
title: "Winning Against 'Unknown USB Device (Port Reset Failed)' In Windows 11: A Comprehensive Fix Guide"
date: 2024-08-15T11:34:53.732Z
updated: 2024-08-16T11:34:53.732Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Winning Against 'Unknown USB Device (Port Reset Failed)' In Windows 11: A Comprehensive Fix Guide"
excerpt: "This Article Describes Winning Against 'Unknown USB Device (Port Reset Failed)' In Windows 11: A Comprehensive Fix Guide"
thumbnail: https://thmb.techidaily.com/4509b58b3a9a19b95f97977ea395ec0191792aea55bdaf18f72a70f3772092da.jpg
---

## Fixing Error 1068 in Windows: A Comprehensive Guide - SOLUTION FOUND

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-freewayframe-the-road-to-effortless-game-snapshots-in-24/"><u>[New] 2024 Approved  FreewayFrame  The Road to Effortless Game Snapshots in '24</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-in-depth-look-at-voice-memo-features-on-your-ios-device/"><u>[New] 2024 Approved  In-Depth Look at Voice Memo Features on Your iOS Device</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-privacy-first-the-leading-storywatchers/"><u>[New] In 2024, Privacy-First  The Leading Storywatchers</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-online-viewers-count-counter/"><u>[Updated] In 2024, Online Viewers Count Counter</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-make-a-statement-crafting-memes-on-kapwing/"><u>[Updated] Make a Statement  Crafting Memes on Kapwing</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-skin-care-secrets-unveiled/"><u>[Updated] Skin Care Secrets Unveiled</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-football-film-study-premier-insights-infographic/"><u>2024 Approved  Football Film Study  Premier Insights Infographic</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-illustrate-laughter-memes-in-adobe/"><u>2024 Approved  Illustrate Laughter  Memes in Adobe</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-inspiring-14-animated-text-concepts/"><u>2024 Approved  Inspiring 14 Animated Text Concepts</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/4-ways-to-unlock-iphone-13-to-use-usb-accessories-without-passcode-drfone-by-drfone-ios/"><u>4 Ways to Unlock iPhone 13 to Use USB Accessories Without Passcode | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-to-hdr-on-windows-11/"><u>A Complete Guide to HDR on Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/choosing-a-more-useful-foreign-language-german-or-french/"><u>Choosing a More Useful Foreign Language: German or French</u></a></li>
<li><a href="https://technical-tips.techidaily.com/complete-guide-viewing-sequence-of-superman-cinematic-universe/"><u>Complete Guide: Viewing Sequence of Superman Cinematic Universe</u></a></li>
<li><a href="https://win-howtos.techidaily.com/confirmation-of-setting-resource-reluctant-to-respond/"><u>Confirmation of Setting: Resource Reluctant to Respond</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-audio-failures-on-netflix-quickly/"><u>Diagnosing and Repairing Audio Failures on Netflix Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-repair-guide-getting-your-lenovo-laptop-camera-back-online/"><u>DIY Repair Guide: Getting Your Lenovo Laptop Camera Back Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dragon-ball-fighterz-network-configuration-fixed-now-running-smoothly/"><u>Dragon Ball FighterZ Network Configuration Fixed - Now Running Smoothly</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/efficiently-using-skypes-screen-share-feature-in-telecommuting/"><u>Efficiently Using Skype's Screen-Share Feature in Telecommuting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-scroll-functionality-of-your-touchpad-in-windows-11-solved/"><u>Enhance Scroll Functionality of Your Touchpad in Windows 11 (Solved)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/experience-uninterrupted-updates-on-windows-11-solve-error-code-0x800f0922-using-our-top-fixes/"><u>Experience Uninterrupted Updates on Windows 11: Solve ERROR CODE 0X800F0922 Using Our Top Fixes!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-solutions-to-fix-the-persistent-kb40240034-glitch-in-windows-10/"><u>Expert Solutions to Fix the Persistent KB40240034 Glitch in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-solutions-how-to-troubleshoot-and-fix-parameter-issues/"><u>Expert Solutions: How to Troubleshoot and Fix Parameter Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/full-tutorial-on-repairing-non-functional-xbox-one-controllers/"><u>Full Tutorial on Repairing Non-Functional Xbox One Controllers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gaming-frustrations-unexpected-computer-lockups/"><u>Gaming Frustrations: Unexpected Computer Lockups</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-fix-resetting-your-computer-failed-error-messages-on-windows-11/"><u>Guide: Fix 'Resetting Your Computer Failed' Error Messages on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-tecno-camon-30-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-driver-power-state-failure-error/"><u>How to Fix DRIVER POWER STATE FAILURE Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-vcruntime140dll-error-and-resolve-windows-10-application-launch-issues/"><u>How to Fix VCRUNTIME140.dll Error and Resolve Windows 10 Application Launch Issues</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-beyond-reality-jaunt-vr-breakdown/"><u>In 2024, Beyond Reality  Jaunt VR Breakdown</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-htc-u23-pro-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from HTC U23 Pro Phones with/without a PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-mic-disconnect-on-discord/"><u>Resolved Mic Disconnect on Discord</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-tablet-charging-problems-what-if-the-device-says-fully-charged-but-wont-turn-on/"><u>Solving Tablet Charging Problems: What If the Device Says Fully Charged But Won't Turn On?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-of-unknown-usb-device-errors-a-guide-to-port-reset-success-in-windows-10/"><u>Solving the Mystery of 'Unknown USB Device' Errors: A Guide to Port Reset Success in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-excessive-cpu-consumption-due-to-faulty-audio-drivers-on-your-computer/"><u>Tackling Excessive CPU Consumption Due to Faulty Audio Drivers on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-troubleshooting-tips-for-resolving-binkw32dll-errors/"><u>The Ultimate Troubleshooting Tips for Resolving binkw32.dll Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-minecraft-crashes-due-to-faulty-video-card-drivers-in-windows-a-comprehhemed-solution/"><u>Troubleshooting Minecraft Crashes Due to Faulty Video Card Drivers in Windows: A Comprehhemed Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-solution-fixing-the-persistent-error-0x800f020b-after-xerox-software-update-on-windows-computers/"><u>Ultimate Solution: Fixing the Persistent Error 0X800f020b After Xerox Software Update on Windows Computers</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-features-and-performance-of-the-samsung-galaxy-tab-s7plus/"><u>Unveiling the Features and Performance of the Samsung Galaxy Tab S7+</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-update-stuck-at-100-solved/"><u>Windows Update Stuck at 100%% [SOLVED]</u></a></li>
</ul></div>
