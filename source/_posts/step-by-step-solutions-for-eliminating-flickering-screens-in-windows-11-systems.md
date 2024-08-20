---
title: Step-by-Step Solutions for Eliminating Flickering Screens in Windows 11 Systems
date: 2024-08-19T07:56:33.803Z
updated: 2024-08-20T07:56:33.803Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for Eliminating Flickering Screens in Windows 11 Systems
excerpt: This Article Describes Step-by-Step Solutions for Eliminating Flickering Screens in Windows 11 Systems
thumbnail: https://thmb.techidaily.com/c4aba1f1071f6153eef4e836db7e5ca4bdc93515fc62fa8fcf2e43a66dd6f0fc.jpg
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
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-maximizing-impact-with-youtube-micro-videos/"><u>[New] 2024 Approved  Maximizing Impact with YouTube Micro Videos</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-direct-dissemination-from-tiktok-to-social-networks/"><u>[New] In 2024, Direct Dissemination From TikTok to Social Networks</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-tips-how-to-perfectly-flip-videos-on-devices/"><u>[Updated] Instagram Tips  How to Perfectly Flip Videos on Devices</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-reinventing-your-avatar-a-detailed-guide-to-changing-tiktok-handle-for-2024/"><u>[Updated] Reinventing Your Avatar  A Detailed Guide to Changing TikTok Handle for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-simplified-guide-to-iphone-screen-adjustment/"><u>[Updated] Simplified Guide to iPhone Screen Adjustment</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/2-ways-to-monitor-apple-iphone-15-pro-activity-drfone-by-drfone-virtual-ios/"><u>2 Ways to Monitor Apple iPhone 15 Pro Activity | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-steadicam-models-compatible-with-dslr-cameras/"><u>2024 Approved  Top Steadicam Models Compatible with DSLR Cameras</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-turn-your-mobile-into-a-professional-webcam-for-video/"><u>2024 Approved  Turn Your Mobile Into a Professional Webcam for Video</u></a></li>
<li><a href="https://win-howtos.techidaily.com/advanced-handling-of-insufficient-resources-service-errors/"><u>Advanced Handling of 'Insufficient Resources' Service Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/arrow-key-malfunctions-heres-how-to-restore-functionality-on-your-keyboard/"><u>Arrow Key Malfunctions? Here's How to Restore Functionality on Your Keyboard!</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/broadcast-tools-battle-wirecast-versus-obs-in-detail-for-2024/"><u>Broadcast Tools Battle  Wirecast versus OBS in Detail for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/compact-travel-tp-link-wr902ac-portable-wireless-router/"><u>Compact Travel TP-Link WR902AC Portable Wireless Router</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-when-the-backspace-keys-stopped-responding-a-step-by-estep-guide/"><u>Easy Fixes for When the Backspace Keys Stopped Responding: A Step-by-eStep Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-sims-4-not-loading-up-a-step-by-step-guide/"><u>Effective Fixes for Sims 4 Not Loading Up: A Step-by-Step Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-gmail-password-on-realme-12plus-5g-devices-by-drfone-android/"><u>How to Reset Gmail Password on Realme 12+ 5G Devices</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Xiaomi 14 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-solve-mouse-right-click-not-working-in-windows-10/"><u>How To Solve Mouse Right Click Not Working in Windows 10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-lava-agni-2-5g-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Lava Agni 2 5G Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-xiaomi-civi-3-disney-100th-anniversary-editionmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Xiaomi Civi 3 Disney 100th Anniversary EditionMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unlocking-asmrs-secrets-for-optimal-wellness/"><u>In 2024, Unlocking ASMR's Secrets for Optimal Wellness</u></a></li>
<li><a href="https://extra-support.techidaily.com/leading-soundstage-viewing-for-2024/"><u>Leading Soundstage Viewing for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/managing-high-gpu-use-by-the-desktop-window-manager-in-windows-effective-techniques/"><u>Managing High GPU Use by the Desktop Window Manager in Windows: Effective Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigate-past-windows-11-update-blockages-solutions-that-work/"><u>Navigate Past Windows 11 Update Blockages – Solutions That Work</u></a></li>
<li><a href="https://win-solutions.techidaily.com/optimizing-dying-light-overcoming-fps-decreases-for-a-seamless-survival-horror-adventure/"><u>Optimizing Dying Light: Overcoming FPS Decreases for a Seamless Survival Horror Adventure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-netcertweaksignature-problem-to-ensure-website-safety-and-integrity/"><u>Overcoming the NET::CERT_WEAK_SIGNATURE Problem to Ensure Website Safety and Integrity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-repairing-your-devices-inactive-at-sign-typing-feature/"><u>Quick Fix: Repairing Your Device's Inactive At Sign Typing Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-0xc00000e9-blue-screen-error-in-windows-a-step-by-step-guide/"><u>Resolving the 0xC00000E9 Blue Screen Error in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-quick-guide-windows-cannot-complete-installing-software/"><u>Resolving the Quick Guide: Windows Cannot Complete Installing Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-brightness-adjustment-problems-for-optimal-display-control/"><u>Resolving Windows 11 Brightness Adjustment Problems for Optimal Display Control</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-the-classic-start-menu-in-modern-windows-10-systems/"><u>Reviving the Classic Start Menu in Modern Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-for-keyboards-where-the-number-pad-doesnt-respond/"><u>Solution Guide for Keyboards Where the Number Pad Doesn’t Respond</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-media-disconnected-issues-on-your-windows-computer-troubleshooting-steps/"><u>Solving 'Media Disconnected' Issues on Your Windows Computer - Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-critical-installation-failure-decoding-error-1603/"><u>Step-by-Step Fixes for Critical Installation Failure - Decoding Error 1603</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-resolution-for-execution-restrictions-fixing-access-is-denied-during-setup/"><u>Step-by-Step Resolution for Execution Restrictions: Fixing ‘Access Is Denied’ During Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-correcting-ps4-network-address-translation-errors/"><u>Step-by-Step Solutions for Correcting PS4 Network Address Translation Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-overcoming-steam-store-access-problems/"><u>Step-by-Step Solutions: Overcoming Steam Store Access Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-your-non-responsive-xbox-one-controller/"><u>Troubleshooting Guide: Fixing Your Non-Responsive Xbox One Controller</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-halo-4s-critical-ue4-bugs-for-smooth-gaming/"><u>Troubleshooting Halo 4'S Critical UE4 Bugs for Smooth Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-persistent-freezing-problems-on-windows-11-boot-up/"><u>Troubleshooting Persistent Freezing Problems on Windows 11 Boot-Up</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-inactive-diagnostics-policy-service-fixed/"><u>Troubleshooting Steps for Inactive Diagnostics Policy Service [Fixed]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-defender-smartscreen-service-not-available/"><u>Troubleshooting: Windows Defender SmartScreen Service Not Available</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-how-to-create-funny-talking-avatars-using-oddcast-text-to-speech-tech/"><u>Updated How to Create Funny Talking Avatars Using Oddcast Text to Speech Tech</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-tecno-phantom-v-fold-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Tecno Phantom V Fold Device</u></a></li>
</ul></div>
