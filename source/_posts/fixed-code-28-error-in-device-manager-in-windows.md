---
title: "[Fixed] Code 28 Error in Device Manager in Windows"
date: 2024-08-19T07:42:41.201Z
updated: 2024-08-20T07:42:41.201Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes [Fixed] Code 28 Error in Device Manager in Windows
excerpt: This Article Describes [Fixed] Code 28 Error in Device Manager in Windows
thumbnail: https://thmb.techidaily.com/85e59c055b67b955137888fcf7f73876f5aa865452b0b880700bbba9d50ba851.jpg
---

## The Ultimate Fix Guide for Overcoming Error 1068 in Windows – Expert Advice Included

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

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Right-click**Eaphost** under the Services section to select**Export** .  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://win-howtos.techidaily.com/fixed-computer-crashes-when-playing-games-in-windows-1011/"><u>[FIXED] Computer Crashes When Playing Games in Windows 10/11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-elevate-your-fb-ad-campaigns-top-20-strategies-for-successful-videos/"><u>[New] In 2024, Elevate Your FB Ad Campaigns  Top 20 Strategies for Successful Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-navigating-free-text-animation-for-artists/"><u>[New] Navigating Free Text Animation for Artists</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-boost-engagement-with-these-5-caption-tricks-on-tiktok-videos/"><u>[Updated] 2024 Approved  Boost Engagement with These 5 Caption Tricks on TikTok Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-a-spectrum-of-style-the-finest-photo-frame-software/"><u>[Updated] A Spectrum of Style  The Finest Photo Frame Software</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-troubleshooting-stalled-video-sending-on-iphone-and-androids-messenger/"><u>[Updated] Troubleshooting Stalled Video Sending on iPhone and Android's Messenger</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-simplifying-cinematics-in-filmora-answering-the-core-questions/"><u>2024 Approved  Simplifying Cinematics in Filmora  Answering the Core Questions</u></a></li>
<li><a href="https://review-topics.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-infinix-note-30-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-itel-s23plus-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Itel S23+ | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209925826-astro-a40-microphone-not-working-heres-what-you-need-to-know/"><u>Astro A40 Microphone Not Working? Here's What You Need to Know!</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/capturing-the-cloud-techniques-for-digital-show-archives-for-2024/"><u>Capturing the Cloud  Techniques for Digital Show Archives for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/compatible-cameras-list-for-windows-hello/"><u>Compatible Cameras List for Windows Hello</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-the-0xc00amage-expert-fixes-to-your-windows-error-code-problems/"><u>Decoding the 0xC00amage: Expert Fixes to Your Windows Error Code Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-fix-your-oculus-gear-problems-2024-update/"><u>Effective Solutions to Fix Your Oculus Gear Problems – 2024 Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-damaged-windows-store-caches-solved/"><u>Expert Tips for Fixing Damaged Windows Store Caches - SOLVED!</u></a></li>
<li><a href="https://buynow-info.techidaily.com/experts-weigh-in-on-samsung-galaxy-fit-a-wearable-device-tailored-to-active-living/"><u>Experts Weigh in on Samsung Galaxy Fit: A Wearable Device Tailored to Active Living</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-nonfunctional-lenovo-mouse-pad-in-various-windows-systems-windows-10-8-and-7/"><u>Fixing a Nonfunctional Lenovo Mouse Pad in Various Windows Systems [Windows 10, 8 & 7]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-missing-audio-files-dlls-in-a-flash/"><u>Fixing Missing Audio Files' DLLs in a Flash</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-your-laptop-mousepad-issues-on-windows-10-8-and-7-a-comprehensive-guide/"><u>Fixing Your Laptop Mousepad Issues on Windows 10, 8 & 7: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-repairing-ethernet-network-errors-for-windows-10-and-7-users/"><u>Guide to Repairing Ethernet Network Errors for Windows 10 and 7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hid-requirement-corrected-missing-touch-functionality-on-device/"><u>HID Requirement - Corrected Missing Touch Functionality on Device</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-oppo-find-x6-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from Oppo Find X6.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-non-responsive-laptop-mousepad-on-windows-8-and-7-step-by-step-guide/"><u>How to Fix a Non-Responsive Laptop Mousepad on Windows 8 & 7: Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-runtime-brokers-excessive-cpu-consumption-in-windows-10-a-step-by-step-guide/"><u>How to Fix Runtime Broker's Excessive CPU Consumption in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-asus-rog-phone-7-ultimate-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-realme-with-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of Realme with Video Repair Utility on Windows?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-print-to-pdf-not-working-in-windows-11/"><u>How To Resolve 'Print to PDF Not Working' In Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-8-to-other-iphone-11-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 8 To Other iPhone 11 devices? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-fix-a-fatal-exception-handler-error-on-windows/"><u>How to Troubleshoot and Fix a Fatal Exception Handler Error on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-repair-non-functional-dell-usb-ports/"><u>How to Troubleshoot and Repair Non-Functional Dell USB Ports</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-gps-on-samsung-galaxy-s23-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>In 2024, How To Fake GPS On Samsung Galaxy S23 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-live-broadcast-over-the-internet-via-vlc-media-player/"><u>In 2024, Mastering Live Broadcast Over the Internet via VLC Media Player</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-the-art-of-recording-your-online-fb-conversations/"><u>In 2024, The Art of Recording Your Online FB Conversations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-resource-allocation-in-complex-system-environments/"><u>Optimizing Resource Allocation in Complex System Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-driver-problems-making-your-wd-my-passport-ultra-visible-in-windows/"><u>Overcoming Driver Problems: Making Your WD My Passport Ultra Visible in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-challenge-unsupported-monitor-input-error-now-solved/"><u>Overcoming the Challenge: Unsupported Monitor Input Error Now Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-with-unsupported-platforms-during-intel-serial-io-driver-setup/"><u>Resolving Issues with Unsupported Platforms During Intel Serial IO Driver Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-audio-on-steam-effective-and-swift-methods-for-gamers/"><u>Revive Audio on Steam: Effective & Swift Methods for Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-update-issues-in-windows-10-resolve-error-code-0x800f0922/"><u>Solving Update Issues in Windows 10: Resolve Error Code 0X800f0922</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-10-photo-libraries-for-free-visuals-worldwide/"><u>Top 10 Photo Libraries for Free Visuals Worldwide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-resolve-silent-mic-issues-with-steelseries-arctis-5-guide/"><u>Troubleshoot and Resolve Silent Mic Issues with SteelSeries Arctis 5 [GUIDE]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-side-by-side-assembly-errors-in-windows-10-systems-diy/"><u>Troubleshooting & Resolving Side-by-Side Assembly Errors in Windows 10 Systems [DIY]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-fix-a-non-responsive-corsair-keyboard/"><u>Troubleshooting Guide: How To Fix a Non-Responsive Corsair Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205370097-troubleshooting-persistent-booting-problems-solutions-inside/"><u>Troubleshooting Persistent Booting Problems: Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fix-for-dell-laptop-black-screen-problems-a-comprehensive-guide/"><u>Ultimate Fix for Dell Laptop Black Screen Problems – A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-solving-your-usb-connection-woes/"><u>Ultimate Guide: Solving Your USB Connection Woes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unraveling-the-mystery-effective-ways-to-address-continuous-reboots-in-windows-10/"><u>Unraveling the Mystery: Effective Ways to Address Continuous Reboots in Windows 10</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-mobile-animation-magic-top-stop-motion-apps-revealed/"><u>Updated 2024 Approved Mobile Animation Magic Top Stop Motion Apps Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/usb-malfunctioning-problem-solved-guides-for-windows-10-and-11/"><u>USB Malfunctioning Problem Solved: Guides for Windows 10 and 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/yac551-yamahaaturbosound-ii-sound-module-based-on-the-ymf794bymu794b-dsp-plus-midi-synthesader-plus-codec-and-256-mb-of-spiram-for-sample-storage-instead-of55/"><u>YAC551 - Yamaha'aturboSound II Sound Module Based on the YMF794B/YMU794B (DSP + MIDI Synthesader + Codec) and 256 MB of SPIRAM for Sample Storage Instead of ROM. It Also Includes a Second Audio Input Connector</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/your-ultimate-guide-to-downloading-youtube-on-ios/"><u>Your Ultimate Guide to Downloading YouTube on iOS</u></a></li>
</ul></div>
