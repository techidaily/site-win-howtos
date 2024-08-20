---
title: "Solution Guide: Addressing Damaged Windows Store Data Reserves"
date: 2024-08-19T06:24:14.674Z
updated: 2024-08-20T06:24:14.674Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solution Guide: Addressing Damaged Windows Store Data Reserves"
excerpt: "This Article Describes Solution Guide: Addressing Damaged Windows Store Data Reserves"
thumbnail: https://thmb.techidaily.com/d909c336a94ed9bab4a7576f74cacae95859492ef6caf81801a20c12eae1a573.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-navigating-the-ins-and-outs-of-aiseesofts-screencast-functionality/"><u>[New] Navigating the Ins and Outs of Aiseesoft's Screencast Functionality</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-blur-faces-in-piscart-in-simple-ways/"><u>[Updated] How to Blur Faces in Piscart in Simple Ways</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-estimating-gb-for-an-entire-film-daily-viewing/"><u>2024 Approved  Estimating GB for an Entire Film, Daily Viewing</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-innovative-approaches-5-techniques-for-recording-sounds-on-windows-11/"><u>2024 Approved  Innovative Approaches  5 Techniques for Recording Sounds on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/banish-error-code-5-from-your-minecraft-adventure-today/"><u>Banish Error Code 5 From Your Minecraft Adventure Today</u></a></li>
<li><a href="https://article-files.techidaily.com/comprehensive-setup-steps-for-wm6-for-2024/"><u>Comprehensive Setup Steps for WM6 for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-unresponsive-space-bar-keys-in-your-new-windows-11-pc/"><u>Dealing with Unresponsive Space Bar Keys in Your New Windows 11 PC</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-official-logitech-g29-steering-wheel-drivers-for-windows-users/"><u>Download the Official Logitech G29 Steering Wheel Drivers for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-free-connection-overcoming-device-descriptor-request-failed-for-your-usb-gadgets/"><u>Error-Free Connection: Overcoming 'Device Descriptor Request Failed' For Your USB Gadgets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-vanished-taskbar-icons-in-windows-n-top-4-tips-for-quick-recovery/"><u>Fix Your Vanished Taskbar Icons in Windows N - Top 4 Tips for Quick Recovery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-your-astro-a40s-nonfunctional-mic-effective-solutions-unveiled/"><u>How to Repair Your Astro A40's Nonfunctional Mic: Effective Solutions Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-address-and-resolve-incorrect-pc-booting-issues/"><u>How to Successfully Address and Resolve Incorrect PC Booting Issues</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-13-pro-max-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 13 Pro Max to other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-8-without-swiping-up-6-ways-drfone-by-drfone-ios/"><u>In 2024, How To Unlock iPhone 8 Without Swiping Up? 6 Ways | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-latest-realtek-audio-drivers-on-windows-11107-download-now/"><u>Install Latest Realtek Audio Drivers on Windows 11/10/7 - Download Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-woes-successful-strategies-for-restoring-your-input-device/"><u>Keyboard Woes? Successful Strategies for Restoring Your Input Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/livekernelevent-117-trouble-heres-how-you-can-fix-it/"><u>LiveKernelEvent 117 Trouble? Here's How You Can Fix It!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-a-guide-to-resolving-crc-verification-failures-efficiently/"><u>Mastering the Fix: A Guide to Resolving CRC Verification Failures Efficiently</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-bring-your-videos-to-life-top-rated-1080p-video-editors/"><u>New In 2024, Bring Your Videos to Life Top-Rated 1080P Video Editors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-casting-errors-on-windows-10-a-complete-guide-to-device-connection-issues/"><u>Overcoming Casting Errors on Windows 10 - A Complete Guide to Device Connection Issues</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/palette-power-skillful-color-adjustment-for-2024/"><u>Palette Power  Skillful Color Adjustment for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-guide-resurrect-lost-gaming-dlls-like-x3d/"><u>Quick-Fix Guide: Resurrect Lost Gaming Dlls Like X3D</u></a></li>
<li><a href="https://apple-account.techidaily.com/removing-device-from-apple-id-for-your-apple-iphone-11-pro-max-by-drfone-ios/"><u>Removing Device From Apple ID For your Apple iPhone 11 Pro Max</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-how-to-correctly-fix-setup-errors-in-your-origin-game/"><u>Resolving Issues: How to Correctly Fix Setup Errors in Your Origin Game</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-non-responsive-fn-keys-expert-tips-for-dell-laptop-users/"><u>Resolving Non-Responsive Fn Keys: Expert Tips for Dell Laptop Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-missing-binkw32dll-file-a-step-by-step-guide/"><u>Resolving the Missing binkw32.dll File: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209794416-restore-your-privileges-on-steam-for-absent-files-easy-fixes-inside/"><u>Restore Your Privileges on Steam for Absent Files – Easy Fixes Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-plcncachewiper-blue-screen-of-death-understanding-and-resolving-error-0xc00000e9/"><u>Solving the PLCN_CACHE_WIPER Blue Screen of Death: Understanding and Resolving Error 0xC00000E9</u></a></li>
<li><a href="https://some-skills.techidaily.com/tailor-made-tunes-for-chrome-companions-for-2024/"><u>Tailor-Made Tunes for Chrome Companions for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-addressing-stop-errors-with-printer-drivers-on-32-bit-os/"><u>Troubleshooting Tips: Addressing Stop Errors with Printer Drivers on 32-Bit OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-solutions-to-the-ce-34878-0-fault-in-ps4-consoles-a-proven-strategy-guide/"><u>Unlocking Solutions to the CE-34878-0 Fault in PS4 Consoles: A Proven Strategy Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unveiling-the-mystery-behind-dxgidll-in-pubg/"><u>Unveiling the Mystery Behind Dxgi.dll in PUBG</u></a></li>
</ul></div>
