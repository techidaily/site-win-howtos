---
title: Troubleshooting DVD Not Working Errors on Windows Machines
date: 2024-08-28T00:31:58.462Z
updated: 2024-08-29T00:31:58.462Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting DVD Not Working Errors on Windows Machines
excerpt: This Article Describes Troubleshooting DVD Not Working Errors on Windows Machines
thumbnail: https://thmb.techidaily.com/5f9bdb089a72cbfbce20351e13d8c69867a47335c73b8710c5509727c5e15028.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

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
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Right-click**Dhcp** under the Services section to select**Export** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-imagelogger-screen-logger-xtreme/"><u>[New] In 2024, ImageLogger Screen Logger Xtreme</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-unlocking-video-revenue-potential-the-facebook-marketing-playbook/"><u>[New] In 2024, Unlocking Video Revenue Potential  The Facebook Marketing Playbook</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-learn-to-flip-film-sequences-on-iphone/"><u>[New] Learn to Flip Film Sequences on iPhone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-tomorrows-scrutiny-innovative-perspectives/"><u>[New] Tomorrow’s Scrutiny  Innovative Perspectives</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-waveforms-and-windows-mac-sound-recording-for-2024/"><u>[New] Waveforms and Windows  Mac Sound Recording for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-expert-recommendations-prime-apps-for-mac-video-recording-for-2024/"><u>[Updated] Expert Recommendations  Prime Apps for Mac Video Recording for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-elevate-your-video-projects-with-top-tier-srt-edits-on-macos/"><u>2024 Approved  Elevate Your Video Projects with Top-Tier SRT Edits on macOS</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-hurdle-free-humor-your-guide-to-the-ifunny-app-world/"><u>2024 Approved  Hurdle-Free Humor  Your Guide to the iFunny App World</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-sony-xperia-5-v-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-infinix-hot-40i-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Infinix Hot 40i | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-displays-that-dont-support-high-definition-content-protection-hdcp/"><u>Dealing With Displays That Don't Support High-Definition Content Protection (HDCP)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-missing-opencl-dll-files/"><u>Dealing with Missing OpenCL DLL Files</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/detailed-analysis-performance-metrics-of-toms-computer-components/"><u>Detailed Analysis: Performance Metrics of Tom's Computer Components</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/tless-transformation-of-your-youtube-content-into-webm-for-2024/"><u>Effortless Transformation of Your YouTube Content Into WebM for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/elevate-your-experience-expert-tips-for-eliminating-stutter-and-improving-frame-rates-in-gaming/"><u>Elevate Your Experience: Expert Tips for Eliminating Stutter and Improving Frame Rates in Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-windows-11-touch-display-issues-with-these-5-proven-strategies/"><u>Fix Your Windows 11 Touch Display Issues with These 5 Proven Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-disappearing-touchpad-pointer-problems-in-windows-11-systems/"><u>Fixing Disappearing Touchpad Pointer Problems in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-startup-failures-your-comprehensive-solution-to-error-code-0xc000007b-on-application-launch/"><u>Fixing Startup Failures: Your Comprehensive Solution to Error Code 0xC000007B on Application Launch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-your-lenovo-mouse-pad-functioning-again-for-windows-users-versions-11-8-and-7/"><u>Get Your Lenovo Mouse Pad Functioning Again for Windows Users (Versions 11, 8, & 7)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unable-to-switch-to-desired-screen-size-error-easily/"><u>How to Fix 'Unable to Switch to Desired Screen Size' Error Easily</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-z-flip-5-bootloader-easily-by-drfone-android/"><u>How to Unlock Samsung Galaxy Z Flip 5 Bootloader Easily</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-realme-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Realme Phone Hassle-Free</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/is-your-apple-iphone-13-pro-max-in-security-lockout-proper-ways-to-unlock-by-drfone-ios/"><u>Is Your Apple iPhone 13 Pro Max in Security Lockout? Proper Ways To Unlock</u></a></li>
<li><a href="https://tech-revival.techidaily.com/lost-in-conversation-a-guide-to-recovering-deleted-chatgpt-sessions/"><u>Lost in Conversation: A Guide to Recovering Deleted ChatGPT Sessions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-efficient-system-resource-use-curbing-msmpengines-cpu-overuse-on-windows-10-resolved/"><u>Mastering Efficient System Resource Use: Curbing MsMpEngine's CPU Overuse on Windows 10 [RESOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-7-installation-solving-unrecognized-hardware-problems/"><u>Mastering Windows 7 Installation – Solving Unrecognized Hardware Problems</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-in-2024-guide-to-discovering-the-voice-generatorschangers-with-the-most-anime/"><u>New In 2024, Guide to Discovering the Voice Generators/Changers with the Most Anime</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-steps-to-recover-an-unresponsive-off-screen-window/"><u>Resolved: Steps to Recover an Unresponsive Off-Screen Window</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-boot-issues-in-windows-11-overcoming-freezing-at-startup/"><u>Resolving Boot Issues in Windows 11 - Overcoming Freezing at Startup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-installation-and-update-complications-for-steam-gaming-software/"><u>Resolving Installation and Update Complications for Steam Gaming Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211255697-revive-your-silent-companion-the-touchpad/"><u>Revive Your Silent Companion - The Touchpad!</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-resolving-mouse-right-click-malfunctions-in-windows-10/"><u>Step-by-Step Guide: Resolving Mouse Right Click Malfunctions in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-fix-windows-hello-not-supported-error-message-on-your-device-running-windows-10/"><u>Steps to Fix Windows Hello Not Supported Error Message on Your Device Running Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/teredo-addressing-the-difficulty-in-achieving-eligibility/"><u>Teredo: Addressing the Difficulty in Achieving Eligibility</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-resolve-sluggish-startup-problems-in-windows-7/"><u>Troubleshoot & Resolve Sluggish Startup Problems in Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-microsoft-outlook-error-0x80004005-the-unspecified-error-dilemma/"><u>Troubleshooting Guide for Microsoft Outlook Error 0X80004005 - The Unspecified Error Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-dealing-with-a-non-functional-backspace-button/"><u>Troubleshooting Tips: Dealing with a Non-Functional Backspace Button</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-d3derrnotavailable-error/"><u>Ultimate Guide: Resolving 'D3DERR_NOTAVAILABLE' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-system-mastering-the-art-of-seamless-windows-11-updates/"><u>Unstick Your System: Mastering the Art of Seamless Windows 11 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/update-guide-enabling-unsupported-graphics-cards-in-fortnite-on-windows-systems/"><u>Update Guide: Enabling Unsupported Graphics Cards in Fortnite on Windows Systems</u></a></li>
</ul></div>
