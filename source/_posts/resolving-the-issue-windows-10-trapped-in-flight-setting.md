---
title: "Resolving the Issue: Windows 10 Trapped in Flight Setting"
date: 2024-08-19T06:22:21.808Z
updated: 2024-08-20T06:22:21.808Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the Issue: Windows 10 Trapped in Flight Setting"
excerpt: "This Article Describes Resolving the Issue: Windows 10 Trapped in Flight Setting"
thumbnail: https://thmb.techidaily.com/b59734d21ac4befa6d882d663a57d13f768195f331fa0eea08a7ad594a08d5e2.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-becoming-part-of-the-global-community-your-guide-to-facebook/"><u>[New] 2024 Approved  Becoming Part of the Global Community  Your Guide to Facebook</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-troubleshooting-tips-for-win-11s-stubborn-photos-app/"><u>[New] 2024 Approved  Troubleshooting Tips for Win 11'S Stubborn Photos App</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-expert-guide-screen-capture-on-windows-8-devices/"><u>[New] Expert Guide  Screen Capture on Windows 8 Devices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-access-high-quality-youtube-images-without-paying-a-dime/"><u>[New] In 2024, Access High-Quality YouTube Images Without Paying a Dime</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-pinpointing-your-unique-tiktok-tagline/"><u>[New] In 2024, Pinpointing Your Unique TikTok Tagline</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-reassert-true-look-corrected-video-error-for-2024/"><u>[New] Reassert True Look  Corrected Video Error for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-step-by-step-manual-kickstart-your-bite-sized-gadget-reviews-channel-for-2024/"><u>[New] Step-by-Step Manual  Kickstart Your Bite-Sized Gadget Reviews Channel for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-scanning-and-repairing-drive-stuck-issue-in-windows-10/"><u>[Solved] Scanning and Repairing Drive Stuck Issue in Windows 10</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-innovative-approaches-to-console-playback-on-pc-hardware/"><u>[Updated] Innovative Approaches to Console Playback on PC Hardware</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-seamlessly-connect-with-friends-and-family-via-skype-call/"><u>[Updated] Seamlessly Connect with Friends & Family via Skype Call</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-snap-inspiration-selecting-stunning-ig-visuals/"><u>[Updated] Snap Inspiration! Selecting Stunning IG Visuals</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-streamlining-videographs-for-instagram-via-mac/"><u>[Updated] Streamlining Videographs for Instagram via Mac</u></a></li>
<li><a href="https://program-issues.techidaily.com/2024-solutions-what-to-do-if-you-cant-get-hogwarts-legacy-running/"><u>2024 Solutions: What to Do If You Can't Get Hogwarts Legacy Running</u></a></li>
<li><a href="https://extra-tips.techidaily.com/all-around-vs-3d-visual-perspectives/"><u>All Around Vs 3D Visual Perspectives</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-stuck-scroll-wheel-on-laptop-touchpad-fixed/"><u>Dealing with Stuck Scroll Wheel on Laptop Touchpad [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-repair-igfxem-problems-for-improved-system-performance/"><u>Diagnose & Repair igfxEM Problems for Improved System Performance</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-realme-c33-2023-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Realme C33 2023 Location Settings | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-solutions-to-correct-the-change-rendering-api-error-2024-in-dota-2/"><u>Effortless Solutions to Correct the 'Change Rendering API' Error 2024 in Dota 2</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-to-overcome-issues-with-downloads-in-steam-update-processes/"><u>Expert Guide to Overcome Issues with Downloads in Steam Update Processes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-windows-11-bluetooth-missing-issue-quickly-and-easily/"><u>Fix Windows 11 Bluetooth Missing Issue. Quickly & Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-cant-open-geforce-experience-a-comprehensive-solution/"><u>Fixing 'Can't Open GeForce Experience': A Comprehensive Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-library-loading-failures-dealing-with-error-87-incorrect-parameter-issue/"><u>Fixing Library Loading Failures: Dealing with Error 87 - Incorrect Parameter Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-unresponsive-touchpad-scrolling-issues-a-comprehensive-guide/"><u>Fixing Unresponsive Touchpad Scrolling Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/from-standard-to-stylish-personalize-each-window-11-screen/"><u>From Standard to Stylish: Personalize Each Window 11 Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-identifying-and-resolving-non-detecting-bluetooth-issues-on-windows-10-computers/"><u>Guide: Identifying & Resolving Non-Detecting Bluetooth Issues on Windows 10 Computers</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-nokia-g42-5gwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Nokia G42 5Gwith/without a PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-and-solve-dhcp-server-offline-connectivity-problems/"><u>How to Address and Solve 'DHCP Server Offline' Connectivity Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-and-restart-the-igfxem-module-in-your-computer-system/"><u>How to Repair and Restart the IgfxEM Module in Your Computer System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-hdcp-errors-on-incompatible-monitors/"><u>How To Resolve HDCP Errors on Incompatible Monitors</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-xiaomi-redmi-12-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Xiaomi Redmi 12</u></a></li>
<li><a href="https://win-howtos.techidaily.com/identifying-suitable-cameras-for-windows-hello/"><u>Identifying Suitable Cameras for Windows Hello</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-oppo-a1x-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Oppo A1x 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-best-ways-to-bypass-icloud-activation-lock-from-apple-iphone-11ipadipod-by-drfone-ios/"><u>In 2024, Best Ways to Bypass iCloud Activation Lock from Apple iPhone 11/iPad/iPod</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-closer-look-strategies-in-virtual-world-of-roblox/"><u>In 2024, Closer Look Strategies in Virtual World of Roblox</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Realme 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-audio-control-in-windows-11-a-comprehensive-guide-to-address-and-correct-volume-issues/"><u>Mastering Audio Control in Windows 11: A Comprehensive Guide to Address and Correct Volume Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-windows-11-reducing-disk-impact-of-compatibility-telemetry-services/"><u>Optimizing Windows 11: Reducing Disk Impact of Compatibility Telemetry Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-quick-windows-setup-failures-successfully/"><u>Overcome Quick Windows Setup Failures Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-challenges-when-setting-up-the-directx-11-device-expert-solutions/"><u>Overcoming Challenges When Setting Up the DirectX 11 Device - Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pdm-pulse-density-modulation/"><u>PDM (Pulse Density Modulation)</u></a></li>
<li><a href="https://fox-that.techidaily.com/quick-fix-how-to-perform-a-hard-reset-and-boot-into-iphone-recovery-mode/"><u>Quick Fix: How to Perform a Hard Reset & Boot Into iPhone Recovery Mode</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/quick-fixes-for-missing-fm20dll-error-in-windows-steps-and-tips/"><u>Quick Fixes for Missing fm20.dll Error in Windows: Steps and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-reaction-to-valorant-freezes-reboot-call/"><u>Quick Reaction to Valorant Freezes: Reboot Call</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-0x800705b4-glitch-a-complete-guide-to-fixing-windows-10-updates/"><u>Resolving the 0X800705b4 Glitch: A Complete Guide to Fixing Windows 10 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-windows-11-update-conundrum-navigating-through-error-code-0x80240034/"><u>Resolving the Windows 11 Update Conundrum: Navigating Through Error Code 0X80240034</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-key-illumination-step-by-step-solutions-for-malfunctioning-backlit-keys-on-macos-and-windows/"><u>Restore Key Illumination: Step-by-Step Solutions For Malfunctioning Backlit Keys on macOS and Windows</u></a></li>
<li><a href="https://driver-download.techidaily.com/simple-steps-get-your-corsair-drivers-installed-on-windows-systems/"><u>Simple Steps: Get Your Corsair Drivers Installed on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-puzzle-a-detailed-guide-to-turning-on-bluetooth-in-windows-7/"><u>Solving the Puzzle: A Detailed Guide to Turning On Bluetooth in Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-update-issue-error-code-0x802c002e-now-resolved/"><u>Solving Windows Update Issue: Error Code 0X802C002E Now Resolved</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-xiaomi-redmi-note-12-pro-5g-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Xiaomi Redmi Note 12 Pro 5G Phone Hassle-Free</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-win11-shutdown-spike/"><u>Troubleshooting Win11 Shutdown Spike</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/ultimate-guide-to-environmentally-safe-tech-for-2024/"><u>Ultimate Guide to Environmentally Safe Tech for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolve-the-troublesome-windows-update-error-code-0x8024402c/"><u>Ultimate Guide: Resolve the Troublesome Windows Update Error Code 0X802#4402C</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-wrap-errors-in-windows-causes-solutions-and-prevention-tips/"><u>Understanding WRAP Errors in Windows: Causes, Solutions & Prevention Tips</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unlock-the-power-of-bethesdas-epic-adventure-skyrim-reviewed-for-the-portable-console/"><u>Unlock the Power of Bethesda's Epic Adventure - Skyrim Reviewed for the Portable Console</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-the-c-drive-issue-on-windows-11/"><u>Unlocking the C: Drive Issue on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-icon-troubleshooting-solutions-for-missing-desktop-icons/"><u>Windows 10 Icon Troubleshooting: Solutions for Missing Desktop Icons</u></a></li>
</ul></div>
