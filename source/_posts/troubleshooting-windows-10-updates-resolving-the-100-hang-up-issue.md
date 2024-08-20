---
title: "Troubleshooting Windows 10 Updates: Resolving the 100%% Hang-Up Issue"
date: 2024-08-19T07:38:11.124Z
updated: 2024-08-20T07:38:11.124Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Windows 10 Updates: Resolving the 100%% Hang-Up Issue"
excerpt: "This Article Describes Troubleshooting Windows 10 Updates: Resolving the 100%% Hang-Up Issue"
thumbnail: https://thmb.techidaily.com/2921f580a005bca983d6da9a3afb73cd46b3297303a92739f51d69c3aa21056e.jpg
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
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
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
sfc /scannow  
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.

 Try to update Windows again and see if it fixes your error 0x80240017\. Still no luck? There’s one more thing to try.

### Fix 4: Update available drivers

 To ensure your computer operates without problems, you should keep your devices drivers up to date. And here are two ways for you to update drivers:**manually** and**automatically** .

**Manually update your driver** – You can go to the manufacturer’s website of your devices, find the latest driver that’s compatible with your Windows operating system, and download it. Once done, open the downloaded file and follow the instruction to install it to your computer.

**Automatically update your driver** **(recommended)** – If you don’t have time or patience, you can do it automatically with[**Driver** **Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  it takes just 2 clicks (and you get full support and a**30-day money back guarantee** ):

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Then Driver Easy will scan your computer and detect any problem drivers.  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/06/driver-easy-scan.jpg)
3. Click the**Update** button next to the flagged device(s) to automatically download the driver (you can do that with the FREE version), then install it in your computer.  
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
<li><a href="https://win-howtos.techidaily.com/fixed-usb-mouse-and-keyboard-stop-working-issue-in-windows-7/"><u>[Fixed] USB Mouse and Keyboard Stop Working Issue in Windows 7</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-vintage-racing-spectacles-top-five/"><u>[New] 2024 Approved  Vintage Racing Spectacles  Top Five</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-how-to-convert-live-photo-to-video/"><u>[New] In 2024, How to Convert Live Photo to Video</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-streamlining-your-ad-engagement-configuring-and-measuring-instream-ads-on-facebook/"><u>[New] In 2024, Streamlining Your Ad Engagement  Configuring & Measuring Instream Ads on Facebook</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-reversing-the-flow-a-guide-to-tracing-instagram-pics-backwards/"><u>[New] Reversing the Flow  A Guide to Tracing Instagram Pics Backwards</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-master-curves-transforming-photos-in-ps/"><u>[Updated] In 2024, Master Curves  Transforming Photos in PS</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-reviewing-the-impression-of-high-dynamic-range-on-aurora-tv/"><u>2024 Approved  Reviewing the Impression of High Dynamic Range on Aurora TV</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-potential-glitches-a-guide-to-when-netflix-is-down-or-malfunctioning/"><u>Addressing Potential Glitches: A Guide to When Netflix Is Down or Malfunctioning</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-system-gap-msvcr71-acquired/"><u>Addressing System Gap: MSVCR71 Acquired</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bring-back-the-buzz-troubleshooting-and-solving-no-sound-issues-on-acer-devices/"><u>Bring Back the Buzz - Troubleshooting and Solving No-Sound Issues on Acer Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-class-not-registered-hurdle-on-windows-10-expert-tips-and-tricks/"><u>Bypassing the 'Class Not Registered' Hurdle on Windows 10: Expert Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clear-audio-ahead-step-by-step-fixes-for-common-netflix-sound-issues/"><u>Clear Audio Ahead: Step-by-Step Fixes for Common Netflix Sound Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/computer-wont-shut-down-windows-11-solved/"><u>Computer Won't Shut Down Windows 11 [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212535440-defeat-pc-game-lag-in-oddworld-soulstorm-with-these-proven-troubleshooting-steps/"><u>Defeat PC Game Lag in Oddworld: Soulstorm with These Proven Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-stop-that-annoying-blinking-cursor-on-your-pcmac/"><u>Easy Steps to Stop That Annoying Blinking Cursor on Your PC/MAC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-remedies-for-when-your-windows-update-gets-stuck-at-zero/"><u>Effective Remedies for When Your Windows Update Gets Stuck at Zero</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-remedies-to-tackle-the-0-hurdle-in-updating-windows-successfully/"><u>Effortless Remedies to Tackle the 0%% Hurdle in Updating Windows Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ending-the-woes-of-windows-update-error-8007000e-easy-solutions-for-speedy-success/"><u>Ending the Woes of Windows Update Error 8007000E: Easy Solutions for Speedy Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x800f0831-fast-fix-with-automated-windows-update-solutions/"><u>Error Code 0X800F0831? Fast Fix with Automated Windows Update Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-synaptics-touchpad-not-scrolling-issue-in-windows-11/"><u>Fix Synaptics Touchpad Not Scrolling Issue in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/geforce-experience-configuration-recovery-solved-techniques-and-tips/"><u>GeForce Experience Configuration Recovery - Solved Techniques and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-epson-scan-cannot-communicate-with-the-scanner-easily/"><u>How To Fix EPSON Scan Cannot Communicate with the Scanner Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-identify-corporate-controlled-settings-within-windows-os/"><u>How To Identify Corporate-Controlled Settings Within Windows OS</u></a></li>
<li><a href="https://youtube-data.techidaily.com/o-select-a-youtube-gaming-introduction-maker-free-or-paid-edition/"><u>How to Select a YouTube Gaming Introduction Maker  Free or Paid Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-overcome-windows-11s-0x800f0922-update-error-with-8-strategies/"><u>How To Successfully Overcome Windows 11'S 0X800f0922 Update Error with 8 Strategies</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-samsung-galaxy-a14-5g-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Samsung Galaxy A14 5G Lock Screen Password?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-pc-maintenance-effective-use-of-sfc-and-dism-in-windows-10-fixes/"><u>Mastering PC Maintenance: Effective Use of SFC and DISM in Windows 10 Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mic-functioning-issue-resolved/"><u>Mic Functioning: Issue Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-hurdle-of-microsoft-error-code-0x800f0831-a-simple-solution/"><u>Overcoming the Hurdle of Microsoft Error Code 0X800f0831: A Simple Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-valorant-endless-load-troubleshooting-steps/"><u>Overcoming the Valorant Endless Load: Troubleshooting Steps</u></a></li>
<li><a href="https://discord-videos.techidaily.com/power-up-your-discord-experience-with-the-art-of-adding-gifs-for-2024/"><u>Power up Your Discord Experience with the Art of Adding GIFs for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206694721-revive-your-steelseries-arctis-5-mic-expert-solutions-to-get-it-working-again/"><u>Revive Your SteelSeries Arctis 5 Mic: Expert Solutions to Get It Working Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-for-loudspeakers-buzzing-in-your-pc-running-windows-10-or-7/"><u>Solution for Loudspeakers Buzzing in Your PC Running Windows 10 or 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-effective-measures-for-unsuccessful-torrent-downloads/"><u>Solving the Problem: Effective Measures for Unsuccessful Torrent Downloads</u></a></li>
<li><a href="https://extra-tips.techidaily.com/starters-guide-to-optimal-gopro-accessories-list/"><u>Starter’s Guide to Optimal GoPro Accessories List</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-the-notorious-minecraft-error-n405/"><u>Step-by-Step Guide: Correcting the Notorious Minecraft Error N405</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fixes-for-windows-11s-bluetooth-pairing-dilemma-pro-tips-and-tricks/"><u>The Ultimate Fixes for Windows 11'S Bluetooth Pairing Dilemma - Pro Tips and Tricks</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-samsung-galaxy-a25-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-methods-to-resolve-frozen-taskbar-in-windows-10/"><u>Top Methods to Resolve Frozen Taskbar in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-strategies-for-eliminating-latency-issues-in-fallout-4/"><u>Top Strategies for Eliminating Latency Issues in Fallout 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-non-functional-huion-stylus-top-5-quick-solutions/"><u>Troubleshoot Your Non-Functional Huion Stylus: Top 5 Quick Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-instantly-solving-windows-installation-errors/"><u>Troubleshooting Guide: Instantly Solving Windows Installation Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-resolving-media-device-unresponsive-on-your-windows-pc/"><u>Troubleshooting Steps: Resolving 'Media Device Unresponsive' On Your Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooting-guide-resolving-the-dell-laptops-black-screen-issue/"><u>Ultimate Troubleshooting Guide: Resolving the Dell Laptop's Black Screen Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/usb-flash-drive-not-showing-up-easy-troubleshooting-steps-inside/"><u>USB Flash Drive Not Showing Up? Easy Troubleshooting Steps Inside!</u></a></li>
</ul></div>
