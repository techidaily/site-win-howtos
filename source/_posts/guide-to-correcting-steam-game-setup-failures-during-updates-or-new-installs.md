---
title: Guide to Correcting Steam Game Setup Failures During Updates or New Installs
date: 2024-08-19T07:50:14.724Z
updated: 2024-08-20T07:50:14.724Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Guide to Correcting Steam Game Setup Failures During Updates or New Installs
excerpt: This Article Describes Guide to Correcting Steam Game Setup Failures During Updates or New Installs
thumbnail: https://thmb.techidaily.com/043a6e9400628e90ba868e49367a439edaed6ed2655e7384611850ca4beac263.jpg
---

## Fixing Windows 10 Update Failures - Get Your Updates Rolling

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb080685ea1.png)

 Many Windows users are having an issue with their Windows Update. If they check for updates on their Windows system, they get an error that says “ **Windows Update cannot currently check for updates, because the service is not running** “. And they can’t install updates for their system.

 This is an annoying issue. And trying to fix it is just as annoying, because you’ll spend a lot of time reading suggestions on the Internet, and most won’t work.

 But don’t worry. The following are some methods that have helped many Windows users fix their error.

### Try these fixes

 You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Run Windows Update troubleshooter**](#a)
2. [**Check for malicious software**](#b)
3. [**Restart your Windows Update associated services**](#c)
4. [**Clear the SoftwareDistribution folder**](#d)
5. [**Update your device drivers**](#e)

## Method 1: Run Windows Update troubleshooter

 Windows has a built-in troubleshooter that can check and fix issues with Windows Update. You should run it when an error occurs on your Windows Update. To do so:

### on Windows 10

**1)** On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.

**2)** Select**Update & Security** .

![](https://www.drivereasy.com/wp-content/uploads/2023/10/Windows-10-Update-and-Security.jpg)

**2)** Click**Troubleshoot > Additional troubleshooters** .

**3)** Find**Windows Update** and click**Run the troubleshooter** .

**4)** Follow the on-screen instructions to complete the troubleshooting process.

**5)** Run your Windows Update again and see if your error is fixed.

### on Windows 11

**1)** On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.

**2)** From the left navigation panel, select**System** . Click**Troubleshoot** .

![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-System-Troubleshoot-1200x699.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
**3)** Click**Other troubleshooters** .

![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-Other-troubleshooters-1200x699.jpg)

**4)** Click on the**Run** button next to**Windows Update** .

![](https://www.drivereasy.com/wp-content/uploads/2023/12/win11-Troubleshooter-Windows-Update-1200x616.jpg)

**5)** Follow the on-screen instructions to complete the troubleshooting process.

**6)** Run your Windows Update again and see if your error is fixed.

## Method 2: Check for malicious software

 Your error may occur because of interference from malicious software. You should run a scan on your computer for any malicious program.

 You can use the **[Malicious Software Removal Tool](https://www.microsoft.com/en-us/download/malicious-software-removal-tool-details.aspx)**  released by Microsoft. Download the tool and run it on your computer. Then follow its instructions to complete the scanning process. If this method works for you, you won’t see the error on your Windows Update again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Method 3: Restart your Windows Update associated services

 You may get the service not running error because the services associated with your Windows Update are disabled. You should restart those services and see if this fixes your error. To do so:

**1)** Press the**Windows logo key** and**R** on your keyboard to invoke the Run box.

**2)** Type “_services.msc_ ” and click**OK** to open the_Services_ snap-in.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2aa01cd2e.png)

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**3)** Double click **Background Intelligent Transfer Service** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb31524505e.jpg)

**4)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3214c6b1e.jpg)

**5)** Double click**Cryptographic Services** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2d8b6d4e7.jpg)

**6)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2f73c5553.jpg)

**7)** Double click**Windows Update** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb327c20a47.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
**6)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb361957d5c.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**7)** Close the Services snap-in and restart your computer. Then check to see if this resolves your problem.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 4: Clear the SoftwareDistribution folder

 The SoftwareDistribution folder stores temporary files for Windows Update. You may get the error due to corruption issues with these files. To see if these files are the cause, you should remove all the content of this folder.

**1)** Press the**Windows logo key** and**R** on your keyboard to invoke the Run box.

**2)** Type “_services.msc_ ” and click**OK**  to open the_Services_ snap-in.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2aa01cd2e.png)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
**3)** Click**Windows Update** and then click**Stop** (the service).

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3bc020986.jpg)

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
**4)** Open_File Explorer_ (press the**Windows logo** key and**E** on your keyboard at the same time), then go to **C:\\Windows\\SoftwareDistribution** and**delete** all the files and folders there.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3da65b40b.jpg)

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**5)**  Restore the_Services_ snap-in. Then click**Windows Update** and click**Start** (the service).

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3f4e427ba.jpg)

**6)** Restart your computer. Then run Windows Update see if this helps you get rid of the Windows Update service not running error.

## Method 5: Update your device drivers

 Your error may occur because you’re using a wrong device driver or it’s out of date. To see if that’s the case for you, you should check your computer and update all those outdated or wrong drivers.

 Updating drivers can consume a lot of time. But if you want to do it easily and quickly, you can use [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

**Driver Easy**  will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can download and install your drivers by using either Free or **Pro**  version of Driver Easy. But with the Pro version it takes only **2**  clicks (and you get **full support** and a **30-day money back guarantee** ):

**1)** [**Download**](https://tools.techidaily.com/drivereasy/download/) and install **Driver Easy** .

**2)** Run **Driver Easy** and click the **Scan Now** button. **Driver Easy**  will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ac9e7d372aa0.png)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**3)**  Click the **Update**  button next to your each of your devices to download the latest and correct driver for it. You can also click the **Update All**  button at the bottom right to automatically update all outdated or missing drivers on your computer (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  — you will be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ac9f8a62a090.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
**4)** Restart your computer. Then run you Windows Update to see if this resolves your problem.

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
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-tutorial-for-apple-music-and-video-mix/"><u>[New] The Ultimate Tutorial for Apple Music & Video Mix</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-enhance-engagement-learn-to-dim-youtube-video-backgrounds/"><u>[Updated] In 2024, Enhance Engagement  Learn to Dim YouTube Video Backgrounds</u></a></li>
<li><a href="https://android-frp.techidaily.com/best-huawei-frp-bypass-guide-by-drfone-android/"><u>Best Huawei FRP Bypass Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/definitive-fixes-overcoming-windows-media-player-server-error-woes-on-windows-os/"><u>Definitive Fixes: Overcoming Windows Media Player Server Error Woes on Windows OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-intermittent-sounds-in-your-logitech-g930-headset/"><u>Effective Fixes for Intermittent Sounds in Your Logitech G930 Headset</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-overcome-the-0x80070490-hurdle-during-system-updates-on-windows/"><u>Effective Solutions to Overcome the 0X80070490 Hurdle During System Updates on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-your-gpu-experience-by-fixing-inadequate-alpha-blending-support/"><u>Enhance Your GPU Experience by Fixing Inadequate Alpha Blending Support</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0x887a0006-no-more-fast-fixes-at-your-fingertips/"><u>Error 0X887A0006 No More: Fast Fixes at Your Fingertips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-responsive-shift-key-a-comprehensive-guide/"><u>Fixing a Non-Responsive Shift Key: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-your-keyboards-arrow-keys-working-again-with-these-proven-tips/"><u>Get Your Keyboard's Arrow Keys Working Again with These Proven Tips</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oppo-a78-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Oppo A78 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204731127-how-to-fix-call-of-duty-ww2-error-code-4220-and-get-back-in-battle-asap/"><u>How to Fix Call of Duty WW2 Error Code 4220 & Get Back in Battle ASAP!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-csgo-high-ping-issues/"><u>How to Fix CS:GO High Ping Issues</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-vivo-y100-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Vivo Y100 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-the-one-or-more-components-cant-be-configured-by-windows-error/"><u>How to Overcome the 'One or More Components Can't Be Configured by Windows' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-sound-quality-problems-fixing-windows-speaker-glitches/"><u>How to Resolve Sound Quality Problems: Fixing Window's Speaker Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-repair-a-malfunctioning-lenovo-keyboard/"><u>How To Troubleshoot and Repair A Malfunctioning Lenovo Keyboard</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-conquering-gameplay-logic-from-console-to-computer-playback/"><u>In 2024, Conquering Gameplay Logic  From Console to Computer Playback</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722129499885-ios-enthusiasts-meet-your-new-chatbuddy/"><u>IOS Enthusiasts, Meet Your New ChatBuddy!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/kodi-troubleshooting-mastery-overcoming-errors-and-enjoying-media-again/"><u>Kodi Troubleshooting Mastery: Overcoming Errors and Enjoying Media Again</u></a></li>
<li><a href="https://extra-support.techidaily.com/master-voice-to-text-conversion-a-step-by-step-guide-to-efficient-documentation-using-ms-word-for-2024/"><u>Master Voice-to-Text Conversion  A Step by Step Guide to Efficient Documentation Using MS Word for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-fixes-for-windows-error-code-absolutely-31-a-users-handbook/"><u>Mastering Fixes for Windows Error Code Absolutely 31 – A User's Handbook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/opaque-oscillation-device-mystery/"><u>Opaque Oscillation: Device Mystery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-destiny-2-boot-issues-effective-solutions-unveiled/"><u>Overcome Destiny 2 Boot Issues: Effective Solutions Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-kernel-power-hurdle-addressing-windows-error-code-0xc00pressure-to-ensure-a-healthy-environment/"><u>Overcoming the 'Kernel Power' Hurdle: Addressing Windows Error Code 0xC00pressure to Ensure a Healthy Environment.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-a-speedy-shutdown-on-your-windows-10-pc/"><u>Quick Solutions for a Speedy Shutdown on Your Windows 10 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-unresponsive-external-mouse-problems-for-windows-and-mac/"><u>Resolve Unresponsive External Mouse Problems for Windows and Mac</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-typing-issues-on-keyboard-no-longer-a-problem/"><u>Resolved: Typing Issues on Keyboard No Longer a Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-windows-update-issue-code-0x8024402c-explained-and-solved/"><u>Resolving the Windows Update Issue: Code 0X8024402C Explained and Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-steam-store-wont-load-effective-troubleshooting-tips/"><u>Solving the Issue of 'Steam Store Won't Load': Effective Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-undetected-bluetooth-hardware-in-windows-11/"><u>Solving the Issue of Undetected Bluetooth Hardware in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-how-to-repair-a-broken-dell-laptop-keys/"><u>Step-by-Step Guide: How to Repair a Broken Dell Laptop Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-restoring-function-key-response-on-asus-laptops/"><u>Step-by-Step Guide: Restoring Function Key Response on ASUS Laptops</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-12-prominent-itel-p55-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Itel P55 Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-non-functional-wacom-pen-in-windows-11-and-windows-10/"><u>Troubleshooting Guide: Fixing a Non-Functional Wacom Pen in Windows 11 and Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-solving-windows-camera-not-working-error-0xa00febec6-issue/"><u>Troubleshooting Guide: Solving Windows Camera Not Working (Error 0xA00Febec6) Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-win32-exception-not-handled-error-0xc0000005-in-windows/"><u>Ultimate Guide: Resolving Win32 Exception Not Handled (Error 0xC0000005) in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-machine-stops-unannounced/"><u>Windows 11: Machine Stops Unannounced</u></a></li>
</ul></div>
