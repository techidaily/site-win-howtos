---
title: Solutions for Resolving 'RPC Server Unreachable' On Your Windows PC
date: 2024-08-19T07:35:46.158Z
updated: 2024-08-20T07:35:46.158Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solutions for Resolving 'RPC Server Unreachable' On Your Windows PC
excerpt: This Article Describes Solutions for Resolving 'RPC Server Unreachable' On Your Windows PC
thumbnail: https://thmb.techidaily.com/12f126cae006dddf10c1360de286a92e906c5d739c81b28f20530205245977db.jpg
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## Method 3: Run the DISM utility

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
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
<li><a href="https://win-howtos.techidaily.com/fixed-windows-11-red-screen-issue/"><u>[Fixed] Windows 11 Red Screen Issue</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-free-music-unlocked-the-ultimate-library-for-videographers/"><u>[New] 2024 Approved  Free Music Unlocked  The Ultimate Library for Videographers</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-uncover-beats-shortcut-musical-roles/"><u>[New] 2024 Approved  Uncover Beats  Shortcut Musical Roles</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-boosting-visuals-high-definition-on-twitter-vids/"><u>[New] Boosting Visuals  High-Definition on Twitter Vids</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/aster-the-art-of-youtube-outros-with-pros-and-resources/"><u>[New] Master the Art of YouTube Outros with Pros and Resources</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-key-steps-to-accurate-and-effective-market-research-analysis/"><u>[Updated] Key Steps to Accurate and Effective Market Research Analysis</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-navigate-your-newly-enjoyed-facebook-movies-with-this-2023-guide-for-2024/"><u>[Updated] Navigate Your Newly Enjoyed Facebook Movies with This 2023 Guide for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-most-innovative-and-easy-to-use-mobile-photo-layers-top-10/"><u>[Updated] The Most Innovative & Easy-to-Use Mobile Photo Layers (Top 10)</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-wired-versus-broadcasted-analyzing-wirecast-and-obs/"><u>2024 Approved  Wired versus Broadcasted  Analyzing Wirecast and OBS</u></a></li>
<li><a href="https://extra-information.techidaily.com/avoiding-edgenuitys-grasp-tips-for-quickly-skipping-video-lessons-for-2024/"><u>Avoiding Edgenuity's Grasp  Tips for Quickly Skipping Video Lessons for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-troubleshooting-for-svchostexe-memory-hog-on-windows-10-machines/"><u>Comprehensive Troubleshooting for svchost.exe Memory Hog on Windows 10 Machines</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-damaged-windows-store-caches-heres-your-guide-to-success/"><u>Dealing with Damaged Windows Store Caches? Here's Your Guide to Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-not-enough-memory-or-cpu-errors-in-service-requests/"><u>Effective Solutions for 'Not Enough Memory or CPU' Errors in Service Requests</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-implemented-for-print-driver-host-stopped-working-on-32-bit-systems-seamless-printing-restored/"><u>Fix Implemented for 'Print Driver Host Stopped Working' On 32-Bit Systems – Seamless Printing Restored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-mysterious-error-1067-when-your-windows-app-crashes-without-warning/"><u>Fixing the Mysterious 'Error 1067' – When Your Windows App Crashes Without Warning</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-odd-top-scroll-reflex-in-windows-10s-file-explorer-for-improved-user-experience/"><u>Fixing the Odd Top-Scroll Reflex in Windows 10'S File Explorer for Improved User Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-10-sound-settings-solving-the-non-responsive-volume-issue/"><u>Fixing Windows 10 Sound Settings: Solving the Non-Responsive Volume Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-back-to-gaming-expert-tips-on-repairing-overwatch-voice-communication-issues/"><u>Get Back to Gaming: Expert Tips on Repairing Overwatch Voice Communication Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-11-couldnt-be-installed-error-80240020-expert-solutions-revealed/"><u>How To Fix 'Windows 11 Couldn't Be Installed Error 80240020 - Expert Solutions Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unplayable-dvd-issues-on-your-windows-device/"><u>How to Fix Unplayable DVD Issues on Your Windows Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-microsoft-wireless-display-device-working-again-on-windows-11/"><u>How to Get Your Microsoft Wireless Display Device Working Again on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-connection-difficulties-with-destiny-amoor-game-servers/"><u>How To Overcome Connection Difficulties with Destiny Amoor Game Servers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-how-to-do-screen-recording-on-ipad/"><u>In 2024, How to Do Screen Recording on iPad?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-and-reset-face-id-on-apple-iphone-14-pro-max-drfone-by-drfone-ios/"><u>In 2024, How to Remove and Reset Face ID on Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-huawei-p60-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Huawei P60 Phone? Unlock It Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-laptop-webcam-woes-master-the-art-of-fixing-it-with-our-proven-methods/"><u>Lenovo Laptop Webcam Woes? Master the Art of Fixing It with Our Proven Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-accurate-typing-remedying-the-issue-of-miskeyed-letters/"><u>Mastering Accurate Typing: Remedying the Issue of Miskeyed Letters</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/meta-quest-2-light-anticipated-costs-release-date-and-latest-specs-whats-next-for-oculus/"><u>Meta Quest 2 Light: Anticipated Costs, Release Date & Latest Specs - What's Next for Oculus?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-device-not-supported-miracast-setup-tips/"><u>Overcoming 'Device Not Supported' - Miracast Setup Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-error-0x8024002e-your-ultimate-guide-to-updating-windows-successfully-fixed/"><u>Overcoming Error 0X8024002e: Your Ultimate Guide to Updating Windows Successfully [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repair-tips-making-your-windows-11-touchscreen-work-like-new-5-ways/"><u>Repair Tips: Making Your Windows 11 Touchscreen Work Like New (5 Ways)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resetting-valorant-for-smooth-play-system-approach/"><u>Resetting Valorant for Smooth Play: System Approach</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-identifying-and-fixing-the-windows-10-update-database-issue/"><u>Resolved: Identifying and Fixing the Windows 10 Update Database Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-windows-10-trapped-in-flight-setting/"><u>Resolving the Issue: Windows 10 Trapped in Flight Setting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/securing-your-network-instructions-for-enabling-lsa-guardrails/"><u>Securing Your Network: Instructions for Enabling LSA Guardrails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-failed-to-initialize-network-hurdle-in-dragon-ball-fighterz/"><u>Solving the 'Failed to Initialize Network' Hurdle in Dragon Ball FighterZ</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-xerox-printer-update-mishap-error-code-0x80f020b-on-windows-systems/"><u>Solving the Xerox Printer Update Mishap: Error Code 0X80^F020B on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-reviving-a-broken-lenovo-keyboard/"><u>Step-by-Step Guide: Reviving a Broken Lenovo Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-the-download-timed-out-problem/"><u>Step-by-Step Solution for the 'Download Timed Out' Problem</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-power-of-openais-shapley-values-how-they-transform-model-clarity-and-decision-making/"><u>The Power of OpenAI's Shapley Values: How They Transform Model Clarity and Decision Making</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-tutorial-to-switch-on-bluetooth-for-windows-7-users/"><u>The Ultimate Tutorial to Switch On Bluetooth for Windows 7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-input-unsupported-errors-on-your-display-device/"><u>Troubleshooting 'Input Unsupported' Errors on Your Display Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-astro-a40-microphone-issues-fixes-and-solutions/"><u>Troubleshooting Astro A40 Microphone Issues: Fixes and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-solving-windows-10-and-7-ethernet-connectivity-problems/"><u>Troubleshooting Guide: Solving Windows 10 & 7 Ethernet Connectivity Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-opening-the-microsoft-store-after-unexpected-crashes/"><u>Troubleshooting Tips - Opening the Microsoft Store After Unexpected Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-how-to-restart-your-diagnostic-tool-successfully/"><u>Troubleshooting Tips: How to Restart Your Diagnostic Tool Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-to-fixing-a-stuck-windows-10-taskbar/"><u>Ultimate Guide to Fixing a Stuck Windows 10 Taskbar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-cannot-connect-error-0x80072fed-on-windows-10/"><u>Ultimate Guide: Resolving the 'Cannot Connect' Error (0X80072FED) on Windows 10</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/views-for-livelihood-mastering-youtubes-true-numbers-for-2024/"><u>Views for Livelihood  Mastering YouTube's True Numbers for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wacom-tablet-not-working-heres-how-to-restore-functionality-and-get-back-to-creating/"><u>Wacom Tablet Not Working? Here's How to Restore Functionality and Get Back to Creating</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-hidden-icons-on-windows-11-effective-restoration-techniques/"><u>Winning Against Hidden Icons on Windows 11 - Effective Restoration Techniques</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-motorola-edge-40-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Motorola Edge 40 | Dr.fone</u></a></li>
</ul></div>
