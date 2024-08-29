---
title: Solving VCRUNTIME140.dll Missing Problem for Successful Program Execution in Windows 10
date: 2024-08-28T00:22:01.990Z
updated: 2024-08-29T00:22:01.990Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving VCRUNTIME140.dll Missing Problem for Successful Program Execution in Windows 10
excerpt: This Article Describes Solving VCRUNTIME140.dll Missing Problem for Successful Program Execution in Windows 10
thumbnail: https://thmb.techidaily.com/a4cc32918e39c53ac0181d3e14c0cb7c5573f6c68460130a6a8de8214128380d.jpg
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

**2)** In Command Prompt, type the following lines of command and press**Enter**on your keyboard after typing each:

* _**net stop bits**_
* _**net stop wuauserv**_
* _**net stop appidsvc**_
* _**net stop cryptsvc**_
(These commands will stop the services that Windows Update requires to download and install updates.)**3)** Type these lines of command and press**Enter** after typing each in Command Prompt:
* _**Ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old**_
* _**Ren %systemroot%\\system32\\catroot2 catroot2.old**_
(This will rename the_SoftwareDistribution_and_catroot2_folder, which are used by Windows Update to store data and temporary files. Your system will detect that these folders are missing, and then it’ll create new ones. The purpose of this is to make the system use the new_SoftwareDistribution_and _catroot2_folders so that Windows Update can avoid issues from the old ones.)**4)**Still in Command Prompt, type these commands and press Enter after each to restart the services you closed just now:
* _**net start bits**_
* _**net start wuauserv**_
* _**net start appidsvc**_
* _**net start cryptsvc**_
**5)**Run Windows Update and check to see if your computer can install the 1607 update.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## Method 4: Temporarily disable your antivirus software

Sometimes your system can’t install new updates due to the interference from your**antivirus software**. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.**IMPORTANT:**Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-prime-pick-simple-effective-gaming-edit-suites/"><u>[Updated] 2024 Approved  Prime Pick  Simple, Effective Gaming Edit Suites</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-streamlining-media-consumption-accessing-facebook-content-via-appletv/"><u>[Updated] 2024 Approved  Streamlining Media Consumption  Accessing Facebook Content via AppleTV</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-darkroom-to-digital-mastering-modern-grading-techniques/"><u>[Updated] From Darkroom to Digital  Mastering Modern Grading Techniques</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-ultimate-guide-to-gameplay-in-simulated-liquids/"><u>[Updated] In 2024, Ultimate Guide to Gameplay in Simulated Liquids</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-mastering-chroma-key-techniques-for-professional-videos/"><u>[Updated] Mastering Chroma Key Techniques for Professional Videos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-growth-and-profitability-in-the-digital-marketplace-explore-these-top-15-facebook-insights/"><u>2024 Approved  Growth & Profitability in the Digital Marketplace  Explore These Top 15 Facebook Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquer-constant-buffering-essential-fixes-for-stalled-valorant-launch/"><u>Conquer Constant Buffering: Essential Fixes for Stalled Valorant Launch</u></a></li>
<li><a href="https://fox-access.techidaily.com/constructing-visually-captivating-photo-collections/"><u>Constructing Visually Captivating Photo Collections</u></a></li>
<li><a href="https://win-howtos.techidaily.com/core-library-loader-dll-deficiency-noted/"><u>Core Library Loader Dll Deficiency Noted</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeating-the-device-doesnt-receive-miracast-advanced-techniques-and-updates/"><u>Defeating the 'Device Doesn't Receive Miracast': Advanced Techniques and Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-loudness-issues-in-playstation-4-systems-tips-and-fixes/"><u>Diagnosing Loudness Issues in PlayStation 4 Systems – Tips & Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-no-device-drivers-detected-error-when-installing-windows-7/"><u>Easy Fixes for 'No Device Drivers Detected' Error When Installing Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-ways-to-resolve-lack-of-sound-device-in-windows-10-or-11/"><u>Effective Ways to Resolve Lack of Sound Device in Windows 10 or 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-ways-to-switch-off-the-touchpad-in-windows-10-while-your-external-mouse-is-connected/"><u>Effective Ways to Switch Off the Touchpad in Windows 10 While Your External Mouse Is Connected</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-fix-it-methods-using-system-file-checker-and-deployment-image-servicing-on-win11/"><u>Essential Fix-It Methods: Using System File Checker and Deployment Image Servicing on Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-techniques-for-repairing-a-broken-camera-on-your-lenovo-device/"><u>Expert Techniques for Repairing a Broken Camera on Your Lenovo Device</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/facebook-vids-fast-track-to-mp4-conversion/"><u>Facebook Vids  Fast Track to MP4 Conversion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-dim-or-overly-bright-screen-correcting-brightness-issues-on-windows-10/"><u>Fix Your Dim or Overly-Bright Screen: Correcting Brightness Issues on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-dota-2-change-rendering-api-error-code-2024-in-minutes/"><u>Fix Your Dota 2 'Change Rendering API' Error Code 2024 in Minutes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-recurring-problems-with-unrecognized-external-devices-on-pc-expert-advice/"><u>Fixing Recurring Problems with Unrecognized External Devices on PC – Expert Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-unable-to-activate-hosted-wifi-on-windows-10/"><u>Fixing the Issue: Unable to Activate Hosted WiFi on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-total-war-rome-remastered-game-crashes-complete-solution/"><u>Fixing Total War: Rome Remastered Game Crashes – Complete Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-detect-dual-monitors/"><u>How to Correctly Detect Dual Monitors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-persistent-red-screen-problem-on-your-windows-11-pc/"><u>How to Fix a Persistent Red Screen Problem on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-printer-offline-with-error-code-30-a-comprehensive-guide/"><u>How to Fix Printer Offline with Error Code -30: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204109263-how-to-get-your-laptops-usb-mouse-working-again-step-by-step-fixes/"><u>How to Get Your Laptop's USB Mouse Working Again – Step by Step Fixes!</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-key-steps-for-an-optimal-chromebook-zooming-experience/"><u>In 2024, Key Steps for an Optimal Chromebook Zooming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-not-working-heres-how-you-can-fix-it-on-windows-11-7-or-8/"><u>Keyboard Not Working? Here's How You Can Fix It on Windows 11, 7, or 8</u></a></li>
<li><a href="https://win-howtos.techidaily.com/logitechs-leap-forward-wireless-woes-end/"><u>Logitech's Leap Forward: Wireless Woes End</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-retrieving-and-repositioning-hidden-system-windows/"><u>Master the Art of Retrieving and Repositioning Hidden System Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-bluetooth-pairing-expert-advice-for-windows-7-users/"><u>Mastering Bluetooth Pairing: Expert Advice for Windows 7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-exe-file-failure-fixing-applications-that-have-crashed/"><u>Resolved: Exe File Failure - Fixing Applications That Have Crashed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211802354-resolving-audio-problems-get-back-control-of-windows-10-speaker-volume-now/"><u>Resolving Audio Problems: Get Back Control of Windows 10 Speaker Volume Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-with-non-functional-volume-buttons-on-windows-10-detailed-tutorial-with-screenshots/"><u>Resolving Issues With Non-Functional Volume Buttons on Windows 10 [Detailed Tutorial with Screenshots]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-unresponsive-mousepad-problems-on-windows-systems-windows-7810/"><u>Resolving Unresponsive Mousepad Problems on Windows Systems (Windows 7/8/10)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205783555-revive-your-touchpad-a-device-mastering-quest/"><u>Revive Your Touchpad: A Device Mastering Quest!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/seeking-a-perfect-match-cameras-and-windows-hello/"><u>Seeking a Perfect Match: Cameras & Windows Hello</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-unregistered-program-components-in-windows-11-a-step-by-step-tutorial/"><u>Solve Unregistered Program Components in Windows 11: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-common-issues-with-non-responsive-at-sign-functionality/"><u>Solving Common Issues with Non-Responsive 'At Sign' Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-client-launcher-trouble-discover-how-to-fix-and-get-back-in-action-today/"><u>Steam Client Launcher Trouble? Discover How to Fix and Get Back in Action Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-better-game-speeds-on-a-windows-11-system/"><u>Step-by-Step Guide to Better Game Speeds on a Windows 11 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-restoring-healthy-file-integrity-for-windows-11-systems/"><u>Step-by-Step Tutorial: Restoring Healthy File Integrity for Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205382179-stop-your-device-from-falling-asleep-simple-solutions/"><u>Stop Your Device From Falling Asleep: Simple Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205981019-success-story-how-i-fixed-a-continuous-steam-update-glitch-easily/"><u>Success Story: How I Fixed a Continuous Steam Update Glitch Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-restore-windows-11-touchscreen-functionality-with-these-5-techniques/"><u>Troubleshooting Guide: Restore Windows 11 Touchscreen Functionality with These 5 Techniques</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unlocking-secure-and-economical-document-disposal-the-amazonbasics-section-1-understanding-bacterial-classification-based-on-sporulation/"><u>Unlocking Secure and Economical Document Disposal: The AmazonBasics # Section 1: Understanding Bacterial Classification Based on Sporulation</u></a></li>
</ul></div>
