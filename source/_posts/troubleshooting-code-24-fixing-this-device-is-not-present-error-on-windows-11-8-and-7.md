---
title: "Troubleshooting Code 24: Fixing 'This Device Is Not Present' Error on Windows 11, 8 & 7"
date: 2024-08-19T07:43:30.297Z
updated: 2024-08-20T07:43:30.297Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Code 24: Fixing 'This Device Is Not Present' Error on Windows 11, 8 & 7"
excerpt: "This Article Describes Troubleshooting Code 24: Fixing 'This Device Is Not Present' Error on Windows 11, 8 & 7"
thumbnail: https://thmb.techidaily.com/0bb0f990e78102071e50c31f7028b725d7f6b1084837b38e9693d564989750d9.jpg
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
5. Right-click**Dhcp** under the Services section to select**Export** .  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-equality-and-innovation-an-easeus-analysis/"><u>[New] 2024 Approved  Equality and Innovation - An EaseUS Analysis</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-blending-youtube-audio-features-into-video-projects/"><u>[Updated] Blending YouTube Audio Features Into Video Projects</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-designing-dynamic-videos-with-adobe-captivate-for-2024/"><u>[Updated] Designing Dynamic Videos with Adobe Captivate for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-shooter-showdown-the-ultimate-battle-for-game-supremacy/"><u>[Updated] In 2024, Shooter Showdown  The Ultimate Battle for Game Supremacy</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximize-your-youtube-yields-small-channel-sponsorship-strategies/"><u>[Updated] Maximize Your YouTube Yields  Small Channel Sponsorship Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-wows-performance-hiccups-learn-how-to-fix-lag-problems-once-and-for-all/"><u>Beat Wow's Performance Hiccups - Learn How To Fix Lag Problems Once And For All</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204758975-bring-back-your-windows-10-bluetooth-effective-solutions-that-work-instantly/"><u>Bring Back Your Windows 10 Bluetooth: Effective Solutions That Work Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208004395-chrome-troubles-eradicate-errnamenotresolved-with-this-easy-method/"><u>Chrome Troubles? Eradicate 'ERR_NAME_NOT_RESOLVED' With This Easy Method</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/compreranse-google-meets-board-features-for-compelling-remote-collaboration-on-all-platforms-for-2024/"><u>Compreranse Google Meet's Board Features for Compelling Remote Collaboration on All Platforms for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-restore-bluetooth-functionality-on-your-windows-11-system-today/"><u>Easy Steps to Restore Bluetooth Functionality on Your Windows 11 System Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eliminate-game-hacks-in-apex-legends-with-this-straightforward-anti-cheat-solution/"><u>Eliminate Game Hacks in Apex Legends with This Straightforward Anti-Cheat Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x80072f8f-easy-fix-steps-for-windows-1110-users/"><u>Error Code 0X80072F8F - Easy Fix Steps for Windows 11/10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-correcting-this-file-cannot-be-played-overcoming-error-224003/"><u>Expert Tips on Correcting 'This File Cannot Be Played' - Overcoming Error 224003</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-d3dxt939dll-error-not-found-heres-how-to-solve-it-effectively/"><u>Fix d3dxt9_39.dll Error Not Found? Here's How to Solve It Effectively!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210007407-fix-invalid-value-for-registry-error-when-opening-photos-on-windows-10/"><u>Fix: “Invalid Value for Registry” Error When Opening Photos on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-malfunctioning-camera-on-lenovo-laptops-practical-solutions/"><u>Fixing a Malfunctioning Camera on Lenovo Laptops - Practical Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-corrupted-windows-store-cache-comprehensive-solutions/"><u>Fixing Corrupted Windows Store Cache - Comprehensive Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-malfunctioned-function-keys-a-step-by-step-guide/"><u>Fixing Malfunctioned Function Keys: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-unregistered-class-errors-in-windows-11-a-step-by-step-guide/"><u>Fixing Unregistered Class Errors in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/get-to-know-amds-newest-graphics-innovation-rdna-35/"><u>Get to Know AMD's Newest Graphics Innovation, RDNA 3.5</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-successfully-overcoming-the-notorious-0x80244022-error-during-windows-updates/"><u>Guide: Successfully Overcoming the Notorious 0X80244022 Error During Windows Updates</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-issue-when-your-print-driver-host-ceases-on-32-bit-software/"><u>How to Fix the Issue When Your Print Driver Host Ceases on 32 Bit Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-prevent-automatic-jump-to-top-on-windows-11-explorer-scrollbar/"><u>How to Prevent Automatic Jump to Top on Windows 11 Explorer Scrollbar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-cast-feature-between-devices-on-windows-11-issue-solved/"><u>How to Restore Cast Feature Between Devices on Windows 11 (Issue Solved)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-volume-functionality-on-your-windows-10-pc-solved/"><u>How To Restore Volume Functionality On Your Windows 10 PC (Solved)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-ispoofer-on-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Sony Xperia 5 V? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-xiaomi-redmi-k70-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Xiaomi Redmi K70 Screen | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transformative-srt-editing-techniques-for-apple-devices/"><u>In 2024, Transformative SRT Editing Techniques for Apple Devices</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/mastering-panoramic-videos-on-iphone-perfect-for-facebook-for-2024/"><u>Mastering Panoramic Videos on iPhone, Perfect for Facebook for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-challenge-of-an-unresponsive-dns-top-five-strategies/"><u>Overcoming the Challenge of an Unresponsive DNS: Top Five Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-2024-unplayable-master-the-ultimate-troubleshooters-guide-to-resolve-launch-errors/"><u>PUBG 2024 Unplayable? Master the Ultimate Troubleshooter's Guide to Resolve Launch Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-stuck-or-unresponsive-buttons-on-an-hp-laptop-solutions-at-hand/"><u>Quick Fixes for Stuck or Unresponsive Buttons on an HP Laptop – Solutions at Hand</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-windows-failed-to-link-with-the-system-event-notification-services/"><u>Resolved: Windows Failed to Link with the System Event Notification Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-persistent-reboot-issues-on-your-windows-11-machine-efficiently/"><u>Resolving Persistent Reboot Issues on Your Windows #11 Machine Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-when-your-diagnostic-tool-is-unresponsive/"><u>Resolving the Issue When Your Diagnostic Tool Is Unresponsive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-ps4-controllers-ultimate-fixes-for-non-charging-problems/"><u>Revive Your PS4 Controllers! Ultimate Fixes for Non-Charging Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-an-inactive-google-chrome-browser-with-swift-reload-strategies/"><u>Reviving an Inactive Google Chrome Browser with Swift Reload Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-solutions-for-when-you-cant-connect-to-wi-fi-a-step-by-step-guide/"><u>Simple Solutions for When You Can't Connect to Wi-Fi - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-nvidia-web-helper-no-disk-error/"><u>Solved Nvidia Web Helper No Disk Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-lenovo-wireless-connectivity-issues-missing-or-incorrect-drivers/"><u>Solving Lenovo Wireless Connectivity Issues: Missing or Incorrect Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-vcruntime140dll-cannot-find-error-a-step-by-step-guide/"><u>Solving VCruntime140.dll Cannot Find Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-fixing-a-stuck-warframe-game-update/"><u>Troubleshooting Steps: Fixing a Stuck Warframe Game Update</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-a-complete-guide-of-top-7-video-language-translators-for-2024/"><u>Updated A Complete Guide of Top 7 Video Language Translators for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Tecno Spark 10 4G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203042340-win-over-sleep-mode-glitch-user-friendly-methods-to-keep-your-pc-awake-all-night-long/"><u>Win Over Sleep Mode Glitch: User-Friendly Methods to Keep Your PC Awake All Night Long</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-youtube-sound-glitches-learn-how-to-tackle-audio-renderer-troubles-effectively/"><u>Windows 11 YouTube Sound Glitches? Learn How to Tackle Audio Renderer Troubles Effectively</u></a></li>
</ul></div>
