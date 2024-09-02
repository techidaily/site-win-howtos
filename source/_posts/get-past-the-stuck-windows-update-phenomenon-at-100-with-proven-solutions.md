---
title: Get Past the Stuck Windows Update Phenomenon at 100%% with Proven Solutions
date: 2024-09-01T04:55:12.352Z
updated: 2024-09-02T04:55:12.352Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Get Past the Stuck Windows Update Phenomenon at 100%% with Proven Solutions
excerpt: This Article Describes Get Past the Stuck Windows Update Phenomenon at 100%% with Proven Solutions
thumbnail: https://thmb.techidaily.com/4e9a1c940b50724444178a8ca1ea00629e8b0a1b576a49f43654cbb3ff64d23c.jpg
---

## Resolving the Troublesome 0X80240017 Windows Update Issue: Proven Solutions

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04d8761fcdb.jpg)

 The**0x80240017** error is a common Windows Update error which happens when you’re downloading or installing your Windows updates and indicates the Windows update failed. It’s generally caused by system files corruption or driver issues. But don’t worry. You can try the solutions below to fix this problem easily.

## Try these fixes

 Here are the solutions that have helped other Windows users resolve error 0x80240017\. You don’t need to try them all; just work your way down the list until everything’s working again.

1. **[Run Windows Update Troubleshooter](#F1)**
2. **[Reset Windows Update Components](#F2)**
3. **[Repair corrupted system files](#F3)**
4. **[Update available drivers](#F4)**

 Note: the screenshots below com from Windows 10, and fixes apply to Windows 11, 8 and 7.

### Fix 1: Run Windows Update Troubleshooter

 Windows Update Troubleshooter is a helpful tool built in Windows system, and you can use it to scan and fix the Windows Update error 0x80240017.

Here’s what you can do:

1. Type**Troubleshoot** in the search box on your desktop, and click**Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04da616dafa.jpg)
2. Click**Troubleshoot** on the left. Click**Windows Update** \>**Run the troubleshooter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

### Fix 2: Reset Windows Update Components

 Windows Update components ensure Windows Update runs properly and the updates can be installed successfully in your computer. If there’s anything wrong during the process, you can try resetting Windows Update components and see how it works.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Copy and paste the following commands one by one in Command Prompt, and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Try to update Windows again and see if it fixes your error 0x80240017\. Still no luck? There’s one more thing to try.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
 Or click**Update All** to automatically download and install all the correct drivers for problem drivers (you can do this with the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) , and you’ll be prompted to upgrade when your click**Update All** ).  
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
<li><a href="https://fox-direct.techidaily.com/new-captivating-books-in-video-form-for-2024/"><u>[New] Captivating Books in Video Form for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-experience-the-thrill-of-kinemaster-and-rank-10-online-alternatives-alike/"><u>[New] Experience the Thrill of KineMaster and Rank 10 Online Alternatives Alike</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-shooting-stars-and-sedans-selecting-the-best-gear-for-sj4000/"><u>[New] In 2024, Shooting Stars & Sedans  Selecting the Best Gear for SJ4000</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-ultimate-guide-to-budget-friendly-phone-video-conferencing-iphone-and-android/"><u>[New] In 2024, Ultimate Guide to Budget-Friendly Phone Video Conferencing (iPhone & Android)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-windows-update-error-8007000e-quickly-and-easily/"><u>[Solved] Windows Update Error 8007000E | Quickly & Easily</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-sharex-review-and-alternatives/"><u>[Updated] 2024 Approved  ShareX Review and Alternatives</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-most-effective-9-microphone-capture-tools-online-2e-for-2024/"><u>[Updated] The Most Effective 9 Microphone Capture Tools Online (2E) for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-making-magic-with-mac-techniques-for-exceptional-tiktok-videos/"><u>2024 Approved  Making Magic with Mac  Techniques for Exceptional TikTok Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/childs-play-top-5-fun-flying-toys-reviewed/"><u>Child's Play  Top 5 Fun Flying Toys Reviewed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/computer-wont-proceed-past-boot-tips-for-successful-resolution/"><u>Computer Won’t Proceed Past Boot - Tips for Successful Resolution</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/dark-moments-decoded-for-iphone-users/"><u>Dark Moments Decoded for iPhone Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decoding-macos-a-detailed-compendium-of-version-histories/"><u>Decoding macOS: A Detailed Compendium of Version Histories</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-to-reconnect-auxiliary-devices-with-windows-10-or-later/"><u>Easy Fixes to Reconnect Auxiliary Devices with Windows 10 or Later</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-solutions-resolving-opengl-error-code-1281/"><u>Easy Solutions: Resolving OpenGL Error Code 1281</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-fixing-the-errinternetdisconnected-error-on-any-browser/"><u>Effective Solutions for Fixing the ERR_INTERNET_DISCONNECTED Error on Any Browser</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202094236-fixing-missing-desktop-icons-on-windows-11-complete-solution/"><u>Fixing Missing Desktop Icons on Windows 11 - Complete Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-sticky-keyboard-buttons-in-windows-a-step-by-step-guide/"><u>Fixing Sticky Keyboard Buttons in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210851945-fixing-the-windows-11-welcome-hang-up-fast-solutions/"><u>Fixing the Windows 11 Welcome Hang-Up: Fast Solutions!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-play-fortnite-solutions-for-incompatible-graphics-cards-under-windows/"><u>How to Play Fortnite: Solutions for Incompatible Graphics Cards Under Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-sounds-on-a-windows-11-computer-without-an-installed-audio-device/"><u>How To Restore Sounds On A Windows 11 Computer Without An Installed Audio Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-touch-functionality-on-your-microsoft-surface-pro-4/"><u>How to Restore Touch Functionality on Your Microsoft Surface Pro 4</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-iphone-14-pro-max-and-ipad-securely-drfone-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on iPhone 14 Pro Max and iPad Securely | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-full-guide-to-apple-iphone-xs-icloud-bypass-by-drfone-ios/"><u>In 2024, Full guide to Apple iPhone XS iCloud Bypass</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/innovating-sound-design-the-impact-and-prowess-of-magix-samplitude-for-2024/"><u>Innovating Sound Design The Impact and Prowess of MAGIX Samplitude for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/insider-look-the-fix-for-nba-2k21s-sustainable-gameplay-feature-bug/"><u>Insider Look: The Fix for NBA 2K21's Sustainable Gameplay Feature Bug</u></a></li>
<li><a href="https://buynow-help.techidaily.com/iphone-15-showdown-determining-the-better-choice-between-pro-and-pro-max-models/"><u>IPhone 15 Showdown: Determining the Better Choice Between Pro and Pro Max Models</u></a></li>
<li><a href="https://win-howtos.techidaily.com/kodi-continuous-playback-solution-say-goodbye-to-buffering/"><u>Kodi Continuous Playback Solution - Say Goodbye to Buffering</u></a></li>
<li><a href="https://win-howtos.techidaily.com/livekernel-event-error-144-strategies-to-solve-the-problem-quickly/"><u>LiveKernel Event Error 144: Strategies to Solve the Problem Quickly</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/navigating-through-interrupted-streams-on-social-media-for-2024/"><u>Navigating Through Interrupted Streams on Social Media for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-and-effective-fixes-for-steam-game-installation-errors/"><u>Quick and Effective Fixes for Steam Game Installation Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-your-pc-when-its-trapped-in-the-boot-sequence/"><u>Resolved: Troubleshooting Your PC When It's Trapped in the Boot Sequence</u></a></li>
<li><a href="https://win-blog.techidaily.com/reviving-game-sounds-addressing-lost-arks-noise-problem/"><u>Reviving Game Sounds: Addressing Lost Ark's Noise Problem</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-fix-for-minecrafts-troublesome-black-screen-fault-in-the-year-2024/"><u>The Ultimate Fix for Minecraft's Troublesome Black Screen Fault in the Year 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-what-to-do-when-your-computer-fails-to-boot/"><u>Troubleshoot and Fix: What To Do When Your Computer Fails to Boot</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixes-for-corrupted-pictures-in-windows-10-and-11/"><u>Troubleshooting Fixes for Corrupted Pictures in Windows 10 and 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-non-functional-night-light-on-windows-11/"><u>Troubleshooting Guide for Non-Functional Night Light on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-enabling-supported-graphic-cards-for-fortnite-in-windows-os/"><u>Troubleshooting Guide: Enabling Supported Graphic Cards for Fortnite in Windows OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-fix-microsoft-wireless-display-adapter-issues-with-windows-10/"><u>Troubleshooting Guide: How to Fix Microsoft Wireless Display Adapter Issues with Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-why-wont-minecraft-open-in-windows-and-how-to-fix-it/"><u>Troubleshooting Guide: Why Won't Minecraft Open in Windows and How to Fix It</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-steps-for-rainbow-six-siege-overcoming-error-3-0x0001000b/"><u>Troubleshooting Steps for Rainbow Six Siege - Overcoming Error 3-0X0001000B</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723200709282-troubleshooting-windows-keys-that-wont-budge-solutions-inside/"><u>Troubleshooting Windows Keys That Won't Budge – Solutions Inside!</u></a></li>
<li><a href="https://games-able.techidaily.com/valves-move-to-curtail-misused-return-options/"><u>Valve's Move to Curtail Misused Return Options</u></a></li>
<li><a href="https://techtrends.techidaily.com/voice-message-basics-learn-how-to-use-the-built-in-ios-microphone-feature-easily/"><u>Voice Message Basics: Learn How to Use the Built-In iOS Microphone Feature Easily</u></a></li>
</ul></div>
