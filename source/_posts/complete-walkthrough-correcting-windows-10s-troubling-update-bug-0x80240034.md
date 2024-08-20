---
title: "Complete Walkthrough: Correcting Windows 10'S Troubling Update Bug 0X80240034"
date: 2024-08-19T06:28:42.938Z
updated: 2024-08-20T06:28:42.938Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Complete Walkthrough: Correcting Windows 10'S Troubling Update Bug 0X80240034"
excerpt: "This Article Describes Complete Walkthrough: Correcting Windows 10'S Troubling Update Bug 0X80240034"
thumbnail: https://thmb.techidaily.com/6195218912eaa800d5cbedefde726b6171a7555efb599d49cbd4be5617c35eea.jpg
---

## Bypassing the Stubborn Windows Update Glitch: Eliminate Error 0X80240017 Now

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04d8761fcdb.jpg)

 The**0x80240017** error is a common Windows Update error which happens when you’re downloading or installing your Windows updates and indicates the Windows update failed. It’s generally caused by system files corruption or driver issues. But don’t worry. You can try the solutions below to fix this problem easily.

## Try these fixes

 Here are the solutions that have helped other Windows users resolve error 0x80240017\. You don’t need to try them all; just work your way down the list until everything’s working again.

1. **[Run Windows Update Troubleshooter](#F1)**
2. **[Reset Windows Update Components](#F2)**
3. **[Repair corrupted system files](#F3)**
4. **[Update available drivers](#F4)**

 Note: the screenshots below com from Windows 10, and fixes apply to Windows 11, 8 and 7.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
### Fix 1: Run Windows Update Troubleshooter

 Windows Update Troubleshooter is a helpful tool built in Windows system, and you can use it to scan and fix the Windows Update error 0x80240017.

Here’s what you can do:

1. Type**Troubleshoot** in the search box on your desktop, and click**Troubleshoot** .  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04da616dafa.jpg)
2. Click**Troubleshoot** on the left. Click**Windows Update** \>**Run the troubleshooter** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 2: Reset Windows Update Components

 Windows Update components ensure Windows Update runs properly and the updates can be installed successfully in your computer. If there’s anything wrong during the process, you can try resetting Windows Update components and see how it works.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Copy and paste the following commands one by one in Command Prompt, and press**Enter** on your keyboard.  
**net stop wuauserv**  
**net stop cryptSvc**  
**net stop bits**  
**net stop msiserver**  
 **ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old**  
**ren C:\\Windows\\System32\\catroot2 catroot2.old**  
**net start wuauserv**  
**net start cryptSvc**  
**net start bits**  
**net start msiserver**  
**pause**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dd3338a3f.jpg)
3. Wait for the commands to complete, and exit Command Prompt.
4. Open Windows Update and see if it works properly.

 If your issue still persists, don’t worry, There is something else to try.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.

 Try to update Windows again and see if it fixes your error 0x80240017\. Still no luck? There’s one more thing to try.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
### Fix 4: Update available drivers

 To ensure your computer operates without problems, you should keep your devices drivers up to date. And here are two ways for you to update drivers:**manually** and**automatically** .

**Manually update your driver** – You can go to the manufacturer’s website of your devices, find the latest driver that’s compatible with your Windows operating system, and download it. Once done, open the downloaded file and follow the instruction to install it to your computer.

**Automatically update your driver** **(recommended)** – If you don’t have time or patience, you can do it automatically with[**Driver** **Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  it takes just 2 clicks (and you get full support and a**30-day money back guarantee** ):

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Then Driver Easy will scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/driver-easy-scan.jpg)
3. Click the**Update** button next to the flagged device(s) to automatically download the driver (you can do that with the FREE version), then install it in your computer.  
 Or click**Update All** to automatically download and install all the correct drivers for problem drivers (you can do this with the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) , and you’ll be prompted to upgrade when your click**Update All** ).  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/07/driver-easy-update.jpg)
4. Restart your computer to take effect.

 Open Windows Update to download and install updates and it should working now.

 So there you have it – Hope this post helps in resolving your**Windows Update error** **0x80240017** . If you have any questions or suggestions, feel free to leave a comment below.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](/tag-search/?tagId=62)

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-finding-storylines-with-google-trends-analysis-techniques/"><u>[New] 2024 Approved  Finding Storylines with Google Trends Analysis Techniques</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-premium-app-list-androids-best-video-and-image-capture/"><u>[New] In 2024, Premium App List  Android's Best Video & Image Capture</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-design-humor-in-frames-picgenius/"><u>[Updated] 2024 Approved  Design Humor in Frames  PicGenius</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-funimate-android-adventure-the-apk-breakdown/"><u>[Updated] In 2024, Funimate Android Adventure  The APK Breakdown</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-xiaomi-mix-fold-3-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Xiaomi Mix Fold 3</u></a></li>
<li><a href="https://fox-links.techidaily.com/clear-views-combating-fog-in-gopro-photos/"><u>Clear Views  Combating Fog in GoPro Photos</u></a></li>
<li><a href="https://win-amazing.techidaily.com/complete-solution-updating-huion-graphics-tablet-software-for-pcs/"><u>Complete Solution: Updating Huion Graphics Tablet Software for PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-the-troublesome-usb-recognition-issue-and-unsuccessful-port-resets-on-windows-11-systems/"><u>Comprehensive Fixes for the Troublesome USB Recognition Issue and Unsuccessful Port Resets on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-windows-11-pc-reset-errors-learn-how-to-resolve-them-today/"><u>Easy Fixes for Windows 11 PC Reset Errors - Learn How to Resolve Them Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-ways-to-overcome-minecraft-lan-play-connectivity-errors/"><u>Effective Ways to Overcome Minecraft LAN Play Connectivity Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-correctly-resolving-the-system-exception-handler-problem-error-0xc0n00000e9/"><u>Expert Tips: Correctly Resolving the System Exception Handler Problem (Error 0xC0n00000E9)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-eliminate-windows-10-typing-lags-step-by-step-solution/"><u>How to Eliminate Window's 10 Typing Lags - Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-error-0xc000007b-when-apps-fail-to-start-properly-solutions-inside/"><u>How to Fix Error 0xC000007B When Apps Fail to Start Properly - Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-infinite-loading-in-the-elder-scrolls-v-skyrim/"><u>How to Overcome Infinite Loading in The Elder Scrolls V: Skyrim</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-solve-the-unknown-usb-device-failure-problem-effectively/"><u>How To Solve the 'Unknown USB Device Failure' Problem Effectively</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-lava-yuva-2-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Lava Yuva 2 Phone? Unlock It Now</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-unlocking-the-potential-of-recording-google-voice-calls/"><u>In 2024, Unlocking the Potential of Recording Google Voice Calls</u></a></li>
<li><a href="https://screen-recording.techidaily.com/innovative-vfx-equipment-for-eco-warriors/"><u>Innovative VFX Equipment for Eco Warriors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lsa-safety-measures-fully-operational-again-secure-your-system-now/"><u>LSA Safety Measures Fully Operational Again - Secure Your System Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-past-update-obstacles-a-solution-for-error-code-0x80070002-in-windows/"><u>Navigating Past Update Obstacles: A Solution for Error Code 0X80070002 in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-challenges-a-look-at-how-nba-2k21s-green-glitch-was-conquered/"><u>Overcoming Challenges: A Look at How NBA 2K21’s Green Glitch Was Conquered</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-wwe-2k-battlegrounds-directx-11-feature-level-10-compatibility-issues/"><u>Overcoming WWE 2K Battlegrounds DirectX 11 Feature Level 10 Compatibility Issues</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/precision-in-reducing-image-size-the-essential-guide-to-thumbnails/"><u>Precision in Reducing Image Size  The Essential Guide to Thumbnails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-resolving-http-503-service-temporarily-unavailable/"><u>Quick Solutions for Resolving HTTP 503 - Service Temporarily Unavailable</u></a></li>
<li><a href="https://win-howtos.techidaily.com/recovering-data-from-broken-unreadable-file-systems-a-step-by-nstep-guide/"><u>Recovering Data From Broken, Unreadable File Systems: A Step-by-nStep Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-cannot-reach-remote-server-a-step-by-step-fix-guide/"><u>Resolving 'Cannot Reach Remote Server': A Step-by-Step Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-freezing-taskbars-in-windows-11-most-efficient-methods/"><u>Resolving Freezing Taskbars in Windows 11 – Most Efficient Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-svchostexes-excessive-cpu-drain-in-windows-11-a-comprehensive-fix-guide/"><u>Resolving svchost.exe's Excessive CPU Drain in Windows 11 - A Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restoring-disappeared-desktop-icons-on-your-pc-running-windows-10-solution/"><u>Restoring Disappeared Desktop Icons on Your PC Running Windows 10 [SOLUTION]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-the-dilemma-computer-unable-to-shut-down-under-windows-11-fixed/"><u>Solve the Dilemma: Computer Unable to Shut Down Under Windows 11 (FIXED)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-sims-4-not-launching-problem-effective-solutions/"><u>Solving the 'Sims 4 Not Launching' Problem: Effective Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-of-a-non-functional-ps4-mic-top-strategies-for-fans/"><u>Solving the Mystery of a Non-Functional PS4 Mic: Top Strategies for Fans</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-cs-go-game-crashes-fast-and-simple-troubleshooting-tips/"><u>Solving Your CS: GO Game Crashes - Fast and Simple Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-correct-windows-11-bluetooth-connection-issues-easily/"><u>Troubleshoot and Correct Windows 11 Bluetooth Connection Issues Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-steps-to-take-when-windows-10-system-crashes/"><u>Troubleshooting Guide: Steps to Take When Windows 10 System Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-fixing-camera-issues-on-surface-pro-4-with-windows-11/"><u>Troubleshooting Steps: Fixing Camera Issues on Surface Pro 4 with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-the-windows-11-kb5003602-update-malfunction/"><u>Troubleshooting Tips for the Windows 11 KB5003602 Update Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-when-copy-and-paste-stops-working-in-windows-11/"><u>Troubleshooting Tips for When 'Copy & Paste' Stops Working in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-resolving-logitech-mouse-scrolling-issues/"><u>Troubleshooting Tips: Resolving Logitech Mouse Scrolling Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-microsoft-wireless-display-on-windows-11-solutions-revealed/"><u>Troubleshooting Your Microsoft Wireless Display on Windows 11 - Solutions Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/updates-fixing-shockwave-flash-crashes-within-the-latest-google-chrome-version/"><u>Updates: Fixing Shockwave Flash Crashes Within the Latest Google Chrome Version</u></a></li>
</ul></div>
