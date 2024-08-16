---
title: "Solving Tablet Charging Problems: What If the Device Says Fully Charged But Won't Turn On?"
date: 2024-08-15T11:19:49.767Z
updated: 2024-08-16T11:19:49.767Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solving Tablet Charging Problems: What If the Device Says Fully Charged But Won't Turn On?"
excerpt: "This Article Describes Solving Tablet Charging Problems: What If the Device Says Fully Charged But Won't Turn On?"
thumbnail: https://thmb.techidaily.com/35d94d879f36ec99317b8846f11d26f9aaf2a40f83fc7f425abd54c5d13338ca.jpg
---

## Error Code 0X800F081F on Your Mind? Solving the DotNet 3.5 Install Problems

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8a7b95c3a7.png)

 If you are seeing an error code**0x800F081F** when you try to install .NET Framework 3.5 on your Windows computer, you are not alone. Many Windows users are reporting it. But the good news is you can fix this error. Here are two fixes you can try:

 Method 1:[**Configure Group Policy**](https://tools.techidaily.com/drivereasy/download/)
 Method 2:[**Install .NET Framework 3.5 using DISM**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## Method 1: Configure Group Policy

 The 0x800F081F error may occur because the component setting in Group Policy is disabled. You should enable it to see if this fixes the error. To do so:

**1)** On your keyboard, press the   **Windows logo key![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png)**  and**R** **key** at the same time to invoke the Run box.

**2)**  Type “**gpedit.msc** ” and press**Enter** on your keyboard.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8b46182da0.png)

**3)**  Go to **Computer Configuration -> Administrative Templates -> System** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8b4b628c80.jpg)

**4)** Double click **Specify settings for optional component installation and component repair** .

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8cb90d9ace.jpg)

**5)** Select**Enabled** . Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8cd1538e66.jpg)

**6)** Try installing .NET Framework 3.5\. If this method works for you, you won’t see the error again. Otherwise, you should try the method below.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## Method 2: Enable the .NET Framework 3.5 feature using DISM

 It is also possible that the error occurs because the .NET Framework 3.5 feature has not been enabled in your system. You can use a DISM command to enable it.

**NOTE** : You need to have installation media or an ISO image for your Windows version to perform this method.

To enable the .NET Framework 3.5 feature using DISM:

**1)** Put the Windows installation media into your computer, or mount the Windows ISO image in your system.

**2)** Press the**Windows logo key** on your keyboard. Then type “**_cmd_** “.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b7455a57b7b.png)

**3)** Right-click “**Command Prompt** ” and select “**Run as administrator** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b75954000f6.png)

**4)** Type “ _**Dism /online /enable-feature /featurename:NetFx3 /All /Source:**_ **<DRIVE>** _**:\\sources\\sxs /LimitAccess**_ ” and press**Enter** on your keyboard. (Note that you need to replace the**<DRIVE>** here with the drive letter for the installation media drive or the ISO drive.)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8d9fc19402.png)

**5)**  Try installing .NET Framework 3.5 and see if the error disappears.

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
<li><a href="https://win-howtos.techidaily.com/1723209908371-resolution-tackle-the-stealthy-culprit-of-elevated-system-load-the-invisible-impacts-of-shell-infra-on-your-windows/"><u>(Resolution) Tackle the Stealthy Culprit of Elevated System Load: The Invisible Impacts Of Shell Infra on Your Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-fight-like-a-warrior-5-intense-martial-arts-rpgs/"><u>[New] 2024 Approved  Fight Like a Warrior  5 Intense Martial Arts RPGs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-scanning-and-repairing-drive-stuck-issue-in-windows-10/"><u>[Solved] Scanning and Repairing Drive Stuck Issue in Windows 10</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-cutting-edge-third-place-ipad-audio-capture-apps-for-2024/"><u>[Updated] Cutting-Edge Third-Place iPad Audio Capture Apps for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-directly-upload-videos-from-twitter-to-tumblr/"><u>2024 Approved  Directly Upload Videos From Twitter to Tumblr</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-freedom-in-meditation-tracks/"><u>2024 Approved  Freedom in Meditation Tracks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/audio-puzzle-solved-pc-and-headphones-reconcile/"><u>Audio Puzzle Solved: PC & Headphones Reconcile</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-stuck-scroll-wheel-on-laptop-touchpad-fixed/"><u>Dealing with Stuck Scroll Wheel on Laptop Touchpad [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-repair-igfxem-problems-for-improved-system-performance/"><u>Diagnose & Repair igfxEM Problems for Improved System Performance</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-solutions-for-dealing-with-total-disk-use-saturation-on-windows-11-systems/"><u>Effective Solutions for Dealing with Total Disk Use Saturation on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-solutions-to-correct-the-change-rendering-api-error-2024-in-dota-2/"><u>Effortless Solutions to Correct the 'Change Rendering API' Error 2024 in Dota 2</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortlessly-fix-your-bcm2045a0-driver-problems-a-step-by-step-guide/"><u>Effortlessly Fix Your BCM2045A0 Driver Problems: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-windows-11-bluetooth-missing-issue-quickly-and-easily/"><u>Fix Windows 11 Bluetooth Missing Issue. Quickly & Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-cant-open-geforce-experience-a-comprehensive-solution/"><u>Fixing 'Can't Open GeForce Experience': A Comprehensive Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-library-loading-failures-dealing-with-error-87-incorrect-parameter-issue/"><u>Fixing Library Loading Failures: Dealing with Error 87 - Incorrect Parameter Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-unresponsive-touchpad-scrolling-issues-a-comprehensive-guide/"><u>Fixing Unresponsive Touchpad Scrolling Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-identifying-and-resolving-non-detecting-bluetooth-issues-on-windows-10-computers/"><u>Guide: Identifying & Resolving Non-Detecting Bluetooth Issues on Windows 10 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-and-solve-dhcp-server-offline-connectivity-problems/"><u>How to Address and Solve 'DHCP Server Offline' Connectivity Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-and-restart-the-igfxem-module-in-your-computer-system/"><u>How to Repair and Restart the IgfxEM Module in Your Computer System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-hdcp-errors-on-incompatible-monitors/"><u>How To Resolve HDCP Errors on Incompatible Monitors</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-20-essential-methods-for-face-blurring-in-images/"><u>In 2024, 20 Essential Methods for Face Blurring in Images</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-phone-number-from-your-apple-id-on-your-iphone-15-pro-by-drfone-ios/"><u>In 2024, How To Remove Phone Number From Your Apple ID on Your iPhone 15 Pro?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-mastering-content-restrictions-on-youtube-videos/"><u>In 2024, Mastering Content Restrictions on YouTube Videos</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-version-of-focusrite-scarlett-2i2-windows-driver-download-available-here/"><u>Latest Version of Focusrite Scarlett 2I2 Windows Driver Download Available Here</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-audio-control-in-windows-11-a-comprehensive-guide-to-address-and-correct-volume-issues/"><u>Mastering Audio Control in Windows 11: A Comprehensive Guide to Address and Correct Volume Issues</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/mastering-the-art-of-locating-fb-lately-seen-videos-for-2024/"><u>Mastering the Art of Locating Fb Lately Seen Videos for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-windows-11-reducing-disk-impact-of-compatibility-telemetry-services/"><u>Optimizing Windows 11: Reducing Disk Impact of Compatibility Telemetry Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-challenges-when-setting-up-the-directx-11-device-expert-solutions/"><u>Overcoming Challenges When Setting Up the DirectX 11 Device - Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pdm-pulse-density-modulation/"><u>PDM (Pulse Density Modulation)</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-motorola-edge-40-neo-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Motorola Edge 40 Neo.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-reaction-to-valorant-freezes-reboot-call/"><u>Quick Reaction to Valorant Freezes: Reboot Call</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-overcoming-challenges-in-reaching-dhcp-services/"><u>Resolved! Overcoming Challenges in Reaching DHCP Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-0x800705b4-glitch-a-complete-guide-to-fixing-windows-10-updates/"><u>Resolving the 0X800705b4 Glitch: A Complete Guide to Fixing Windows 10 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-windows-11-update-conundrum-navigating-through-error-code-0x80240034/"><u>Resolving the Windows 11 Update Conundrum: Navigating Through Error Code 0X80240034</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-key-illumination-step-by-step-solutions-for-malfunctioning-backlit-keys-on-macos-and-windows/"><u>Restore Key Illumination: Step-by-Step Solutions For Malfunctioning Backlit Keys on macOS and Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/samsung-tips-easy-time-lapse-photography-for-2024/"><u>Samsung Tips  Easy Time-Lapse Photography for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-puzzle-a-detailed-guide-to-turning-on-bluetooth-in-windows-7/"><u>Solving the Puzzle: A Detailed Guide to Turning On Bluetooth in Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-update-issue-error-code-0x802c002e-now-resolved/"><u>Solving Windows Update Issue: Error Code 0X802C002E Now Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-stuck-keyboard-arrows-essential-troubleshooting-tips/"><u>Solving Your Stuck Keyboard Arrows: Essential Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-techniques-to-correct-videodxgkrnlfatalerror-issues-in-windows/"><u>Step-by-Step Techniques to Correct Video_Dxgkrnl_Fatal_Error Issues in Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-next-level-in-autonomous-rides-explore-rumored-details-about-teslas-upcoming-robotaxi/"><u>The Next Level in Autonomous Rides: Explore Rumored Details About Tesla's Upcoming Robotaxi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-win11-shutdown-spike/"><u>Troubleshooting Win11 Shutdown Spike</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-to-overcoming-windows-file-permission-errors/"><u>Ultimate Guide to Overcoming Windows File Permission Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolve-the-troublesome-windows-update-error-code-0x8024402c/"><u>Ultimate Guide: Resolve the Troublesome Windows Update Error Code 0X802#4402C</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-wrap-errors-in-windows-causes-solutions-and-prevention-tips/"><u>Understanding WRAP Errors in Windows: Causes, Solutions & Prevention Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-icon-troubleshooting-solutions-for-missing-desktop-icons/"><u>Windows 10 Icon Troubleshooting: Solutions for Missing Desktop Icons</u></a></li>
</ul></div>
