---
title: "Resolving the Persistent 'Windows Update Error 0X800705B4' In Windows 11: Effective Solutions"
date: 2024-08-19T07:08:48.516Z
updated: 2024-08-20T07:08:48.516Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the Persistent 'Windows Update Error 0X800705B4' In Windows 11: Effective Solutions"
excerpt: "This Article Describes Resolving the Persistent 'Windows Update Error 0X800705B4' In Windows 11: Effective Solutions"
thumbnail: https://thmb.techidaily.com/2675fb371c905563da08e97bc8df2b8ac8d7bb0fb61d06cdf9fff2c91961fd4b.png
---

## Resolving the Troublesome 0X80240017 Windows Update Issue: Proven Solutions

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04da616dafa.jpg)
2. Click**Troubleshoot** on the left. Click**Windows Update** \>**Run the troubleshooter** .  
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

### Fix 2: Reset Windows Update Components

 Windows Update components ensure Windows Update runs properly and the updates can be installed successfully in your computer. If there’s anything wrong during the process, you can try resetting Windows Update components and see how it works.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dd3338a3f.jpg)
3. Wait for the commands to complete, and exit Command Prompt.
4. Open Windows Update and see if it works properly.

 If your issue still persists, don’t worry, There is something else to try.

### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
sfc /scannow  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
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
![](https://images.drivereasy.com/wp-content/uploads/2018/06/driver-easy-scan.jpg)
3. Click the**Update** button next to the flagged device(s) to automatically download the driver (you can do that with the FREE version), then install it in your computer.  
 Or click**Update All** to automatically download and install all the correct drivers for problem drivers (you can do this with the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) , and you’ll be prompted to upgrade when your click**Update All** ).  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
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
<li><a href="https://extra-hints.techidaily.com/new-boost-creativity-tiktok-video-treatments/"><u>[New] Boost Creativity  TikTok Video Treatments</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-captivating-storytelling-with-these-6-snapchat-video-editors/"><u>[New] Captivating Storytelling with These 6 Snapchat Video Editors</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-connecting-twitters-and-facebooks-easily/"><u>[New] Connecting Twitters & Facebooks Easily</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-maximizing-team-productivity-with-snap-camera-integration/"><u>[New] Maximizing Team Productivity with Snap Camera Integration</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-optimal-vision-with-the-best-4k-monitors-1-10/"><u>[New] Optimal Vision with the Best 4K Monitors, #1-10</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-quick-tunes-explore-video-music-characters/"><u>[New] Quick Tunes  Explore Video Music Characters</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-creme-de-la-cream-of-online-tv-services/"><u>[New] The Crème De La Cream of Online TV Services</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-tranquil-tracks-easy-volume-diminution-via-garageband/"><u>[New] Tranquil Tracks  Easy Volume Diminution via Garageband</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-night-light-not-working-on-windows-1011/"><u>[SOLVED] Night Light Not Working on Windows 10/11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-excellence-exchange-global-creators/"><u>[Updated] Excellence Exchange  Global Creators</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-in-depth-analysis-and-exploration-adobe-storage-vs-competitors-options/"><u>[Updated] In-Depth Analysis & Exploration  Adobe Storage Vs. Competitors' Options</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-full-circumference-video-rigging/"><u>2024 Approved  Full-Circumference Video Rigging</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ace-your-green-screen-videos-must-know-secrets/"><u>Ace Your Green Screen Videos  Must-Know Secrets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-and-repairing-the-persistent-0x802n40017-issue-in-windows-updates/"><u>Bypassing and Repairing the Persistent 0X802n40017 Issue in Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-when-your-windows-10-mouse-ignores-the-right-click/"><u>Comprehensive Fixes for When Your Windows 10 Mouse Ignores the Right Click</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquering-the-blue-screen-of-death-fix-your-windows-0xc0000098-error-today/"><u>Conquering the Blue Screen of Death: Fix Your Windows 0xC0000098 Error Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/curbing-wudfhostexe-cpu-hogs-on-your-pc-a-fix-for-windows-10-users/"><u>Curbing wudfhost.exe CPU Hogs on Your PC - A Fix for Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-microsofts-wireless-display-not-connecting-issue-on-pcs-with-windows-10/"><u>Effective Solutions to Microsoft's Wireless Display Not Connecting Issue on PCs with Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-repair-serious-bugs-in-call-of-duty-black-ops-4/"><u>Expert Tips to Repair Serious Bugs in Call of Duty: Black Ops 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-no-battery-found-problem-fast-and-simple-solutions/"><u>Fix 'No Battery Found' Problem: Fast and Simple Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-print-screen-function-issues-on-windows-11-and-windows-10/"><u>Fixing 'Print Screen' Function Issues on Windows 11 & Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-d3dx930dll-file-absent-error-a-comprehensive-guide/"><u>Fixing d3dx9_30.dll File Absent Error - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-correct-scrollbar-glitch-in-windows-10-file-explorer-that-hits-top-when-moving-up/"><u>Guide to Correct Scrollbar Glitch in Windows 10 File Explorer That Hits Top When Moving Up</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Motorola Moto G14? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-lenovo-mouse-pad-up-and-running-again-on-windows-systems-windows-10-8-7/"><u>How to Get Your Lenovo Mouse Pad Up & Running Again on Windows Systems (Windows 10, 8, 7)</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-advanced-techniques-for-audio-detachment-in-newly-updated-mkv-files-mkv-2023/"><u>In 2024, Advanced Techniques for Audio Detachment in Newly Updated MKV Files (MKV-2023)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-bring-back-the-sparkle-applying-instagram-effects-retro-style/"><u>In 2024, Bring Back the Sparkle  Applying Instagram Effects Retro Style</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-infinix-smart-7-hd-easily-by-drfone-android/"><u>In 2024, How To Unlock a Infinix Smart 7 HD Easily?</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ipad-pro-vs-surface-pro-showdown-key-features-and-benefits-unveiled/"><u>IPad Pro Vs. Surface Pro Showdown: Key Features & Benefits Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203188320-laptop-battery-woes-discover-easy-methods-to-restore-charging-power-today/"><u>Laptop Battery Woes? Discover Easy Methods to Restore Charging Power Today</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/maintaining-meetings-in-google-recorder-for-2024/"><u>Maintaining Meetings in Google Recorder for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-for-unable-to-start-application-correctly-0xc000007b-expert-tips-and-tricks/"><u>Mastering the Fix for 'Unable to Start Application Correctly (0xC000007B)': Expert Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-solution-eradicating-livekernel-event-mishap-no-144/"><u>Mastering the Solution: Eradicating LiveKernel Event Mishap No. 144</u></a></li>
<li><a href="https://win-howtos.techidaily.com/nba-2k21-green-hiccup-patch-details-and-how-its-gone/"><u>NBA 2K21 Green Hiccup: Patch Details & How It's Gone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-the-best-free-online-video-editors-a-comprehensive-guide/"><u>New The Best Free Online Video Editors A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209290778-no-more-pdf-printing-woes-swift-solutions-that-work/"><u>No More PDF Printing Woes - Swift Solutions That Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-network-hurdles-corrective-measures-for-error-0x800704cf-in-windows/"><u>Overcoming Network Hurdles: Corrective Measures for Error 0X800704CF in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-when-file-explorer-freezes-on-windows-10/"><u>Quick Fixes for When File Explorer Freezes on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repair-how-to-fix-a-malfunctioning-windows-11-start-menu/"><u>Repair: How to Fix a Malfunctioning Windows 11 Start Menu</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-silent-dell-speakers-a-comprehensive-guide/"><u>Reviving Silent Dell Speakers: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-overcoming-the-stuck-configuring-windows-phase-with-easy-fixes/"><u>Solution Found: Overcoming the Stuck 'Configuring Windows' Phase with Easy Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steelseries-arctis-5-wireless-headset-how-to-restore-microphone-functionality-successfully/"><u>SteelSeries Arctis 5 Wireless Headset: How to Restore Microphone Functionality Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-unsticking-a-pc-stuck-in-the-getting-ready-window-phase/"><u>Step-by-Step Guide: Unsticking a PC Stuck in the 'Getting Ready' Window Phase</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-troubleshooting-windows-0xc0000005-faults/"><u>Step-by-Step Solutions for Troubleshooting Windows 0xC0000005 Faults</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-troubleshooting-connecting-your-airpods-to-windows-11-latest-techniques/"><u>Step-by-Step Troubleshooting: Connecting Your AirPods to Windows 11 - Latest Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/success-story-how-i-fixed-a-continuous-steam-update-glitch-easily/"><u>Success Story: How I Fixed a Continuous Steam Update Glitch Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-troubleshooting-steps-when-microsoft-store-doesnt-launch/"><u>Successful Troubleshooting Steps When Microsoft Store Doesn't Launch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/surface-laptop-stuck-at-0-is-it-truly-plugged-in-and-why/"><u>Surface Laptop Stuck at 0%% - Is It Truly Plugged in and Why?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackle-stubborn-valorant-errors-with-system-reset/"><u>Tackle Stubborn Valorant Errors with System Reset</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-excessive-gpu-drain-by-the-desktop-window-manager-in-windows-1011/"><u>Troubleshooting Guide for Excessive GPU Drain by the Desktop Window Manager in Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-functioning-function-keys-in-dell-laptops/"><u>Troubleshooting Non-Functioning Function Keys in Dell Laptops</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-not-responding-errors-for-file-explorer-in-windows-11/"><u>Ultimate Guide: Resolving 'Not Responding' Errors for File Explorer in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-repairing-windows-media-player-server-problem-on-your-pc-solved/"><u>Understanding and Repairing Windows Media Player Server Problem on Your PC [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unraveled-addressing-the-write-failure-in-referenced-memory-location-x/"><u>Unraveled: Addressing the Write Failure in Referenced Memory Location X</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-help-fixing-the-secured-c-drive-accessibility/"><u>Windows 11 Help: Fixing the Secured C:\\ Drive Accessibility</u></a></li>
</ul></div>
