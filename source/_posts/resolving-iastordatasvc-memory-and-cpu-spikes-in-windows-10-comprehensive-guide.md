---
title: Resolving IAStorDataSvc Memory and CPU Spikes in Windows 10 - Comprehensive Guide
date: 2024-08-19T07:04:54.246Z
updated: 2024-08-20T07:04:54.246Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving IAStorDataSvc Memory and CPU Spikes in Windows 10 - Comprehensive Guide
excerpt: This Article Describes Resolving IAStorDataSvc Memory and CPU Spikes in Windows 10 - Comprehensive Guide
thumbnail: https://thmb.techidaily.com/128652f3635b5c02571aebd32ea42bdf5de3d8228fe08a4a4993ce8bcc5b8b84.png
---

## How to Restore Vanished Desktop Icons in Your Windows 10 System - SOLUTION Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf526e8ebcab-1024x552.jpg)

If your desktop icons somehow disappear on your Windows 10 computer, don’t worry, you can try the tips below to fix the issue. Quickly and easily.

## Try these tips

You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Enable Show desktop icons**](#t1)
2. [**Check your desktop icon settings**](#t2)
3. [**Rebuild icon cache**](#t4)
4. [**Perform a system restore**](#t5)
5. [**Reset your computer**](#t6)
6. [**Bonus tip**](#t7)

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Tip 1: Enable Show desktop icons

Make sure you have enabled the “Show desktop icon” feature on Windows 10:

1. Right-click your desktop, click **View**, and check **Show desktop icons**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf52ca259fe4.jpg)
2. Check to see if your desktop icons are back. If not, try Tip 2, below.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
### Tip 2: Check your desktop icon settings

1. Right-click your desktop and click **Personalize**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf531bcea206.jpg)
2. Click **Themes** \> **Desktop icon settings**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53220a4552.jpg)
3. Select the icons you want to show on desktop, then click **OK**.  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53279e9206.jpg)
4. Check if your “desktop icons missing” problem is resolved. If not, try Tip 3, below.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Tip 3: Rebuild icon cache

You can also try these steps to rebuild the icon cache:

1. Run **Command Prompt** as administrator.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53d32cc341.jpg)
2. Copy-paste the following commands one at a time and press **Enter** after each command.  
taskkill /F /IM explorer.exe  
cd /d %userprofile%\AppData\Local  
attrib –h IconCache.db  
del IconCache.db  
start explorer.exe
3. Check if it helps restore your desktop icons. If not, try Tip 4, below.

---

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
### Tip 4: Perform a system restore

If your desktop icons still don’t show up, you can perform a system restore to return your system to a date when the icons appeared normally on the desktop. Here’s how to perform a system restore to help fix your “desktop icons disappeared in Windows 10” issue:

1. Type **recovery** in the Windows search box, then press **Enter**.
2. At Recovery, click **Open System Restore**.  
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a2728a7e.jpg)
3. Select **Choose a different restore point**, and click **Next**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a34c35bc.jpg)
4. Check the box beside **Show more restore points**. You should see a list of ‘restore points’. These are like backups of your computer, as it was at that particular date and time. Think back to a date when your desktop icons showed up, and **select a restore point** from that date or slightly earlier (but no later).  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a4d84f3c.jpg)
5. Click **Next** \> **Finish**.
6. Check to see if your desktop icons are now restored on Windows 10\. If not, try Tip 5, below.

---

### Tip 5: Reset your computer

If the steps above didn’t work for you. Resetting your computer is worth a try. It fixed the desktop icon issue for some users.

1. Click the **Start** button > the **Settings** icon.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b790f639.jpg)
2. Click **Update & security** \> **Recovery**.
3. In the **Reset this PC** area, click the **Get started** button. Then follow the on-screen instructions to reset your PC.  
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b9dab56d.jpg)

---

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Bonus tip

A missing or outdated graphics driver may also stop items from appearing properly on PC. You should make sure your graphics card driver is up to date. There are two ways to update your graphics driver: **manually** and **automatically**.

**Update your graphics driver manually** — You can update your driver manually by going to the hardware manufacturer’s website, and searching for the latest driver for your graphics card. But if you take this approach, be sure to choose the driver that’s compatible with the exact model number of your hardware, and your version of Windows.

OR

**Update your graphics driver automatically** — If you don’t have the time, patience, or computer skills to update your driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.
2. Run Driver Easy and click **Scan Now**. Driver Easy will then scan your computer and detect any problem drivers.  
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-Scan-Needed.jpg)
3. Click **Update** next to any flagged devices to automatically download the correct version of their drivers, then you can install them manually. Or click **Update All** to automatically download and install them all automatically. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All. You get full support and a 30-day money-back guarantee.)  
![](https://www.drivereasy.com/wp-content/uploads/2022/02/de-update-all-rtx-3080.jpg)  
If you need assistance, please contact Driver Easy’s support team at **<support@drivereasy.com>**.

---

Hopefully, this can help you out.

If you have any other suggestions, please feel free to leave a comment below.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-streamlabs-vs-top-embedding-platforms/"><u>[New] 2024 Approved  Streamlabs Vs. Top Embedding Platforms</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-creative-openings-just-a-click-away/"><u>[New] In 2024, Creative Openings, Just a Click Away</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-maximizing-virtual-reality-potential/"><u>[New] Maximizing Virtual Reality Potential</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-screen-sync-free-cross-platform-high-quality-recording-tools/"><u>[New] Screen Sync  Free Cross-Platform, High-Quality Recording Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-ultimate-compilation-budget-friendly-editing-tools/"><u>[New] The Ultimate Compilation  Budget-Friendly Editing Tools</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-the-most-affordable-gaming-tunes-top-10-lists/"><u>[Updated] The Most Affordable Gaming Tunes  Top 10 Lists</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-password-recall-issue-on-w10w11/"><u>Addressing the “Password Recall Issue on W10/W11”</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-solution-resolving-the-persistent-windows-update-error-0x80240017/"><u>Complete Solution: Resolving the Persistent Windows Update Error 0X80240017</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquering-the-google-chrome-alarm-a-step-by-step-guide-to-scam-recovery/"><u>Conquering The Google Chrome Alarm: A Step-by-Step Guide to Scam Recovery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-reducing-microsoft-compatibility-telemetrys-impact-on-hard-drive-space-in-windows-10/"><u>Diagnosing and Reducing Microsoft Compatibility Telemetry's Impact on Hard Drive Space in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosis-and-fixes-restoring-function-key-capabilities/"><u>Diagnosis and Fixes: Restoring Function Key Capabilities</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-access-to-remote-brother-print-device/"><u>Enabling Access to Remote Brother Print Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-224003-solved-ensuring-successful-video-streaming/"><u>Error 224003 Solved: Ensuring Successful Video Streaming</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722978042469-find-and-install-the-right-asus-mousepad-driver-software-on-your-windows-machine-now/"><u>Find & Install the Right ASUS Mousepad Driver Software on Your Windows Machine Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-the-set-user-settings-to-driver-failed-issue-with-easy-steps/"><u>Fix the 'Set User Settings to Driver Failed' Issue with Easy Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-camera-not-found-overcome-windows-error-0xa0nf4292/"><u>How to Resolve 'Camera Not Found' - Overcome Windows Error 0xA0nf4292</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-a-broken-connection-between-your-usb-and-hdmi-device/"><u>How to Resolve a Broken Connection Between Your USB and HDMI Device</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-14-pro-3-ways-to-unlock-by-drfone-ios/"><u>How To Unlock iPhone 14 Pro 3 Ways To Unlock</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My ZTE Axon 40 Lite? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-huawei-nova-y71-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Huawei Nova Y71 To Phone | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-latest-guide-on-ipad-23-and-iphone-15-plus-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Latest Guide on iPad 2/3 and iPhone 15 Plus iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-snappy-solutions-maintaining-a-vigorous-snapstreak/"><u>In 2024, Snappy Solutions  Maintaining a Vigorous Snapstreak</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-unleash-your-creativity-top-video-collage-apps-for-iphone-and-ipad/"><u>New 2024 Approved Unleash Your Creativity Top Video Collage Apps for iPhone and iPad</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-graphics-driver22-hurdle/"><u>Overcoming Graphics DRIVER#22 Hurdle</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-red-screen-of-error-a-step-by-step-guide/"><u>Resolving the Red Screen of Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/rhythm-of-motivation-discover-the-most-inspiring-exercinasaurus-rex-songs/"><u>Rhythm of Motivation  Discover the Most Inspiring Exercinasaurus Rex Songs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-troubleshooting-guide-for-initializing-issues-with-smartaudio/"><u>Solved: Troubleshooting Guide for Initializing Issues with SmartAudio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-invalid-value-in-registry-issues-when-launching-photos-app-on-windows-10/"><u>Solving 'Invalid Value in Registry' Issues when Launching Photos App on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-repair-of-non-functional-usb-port-on-hp-laptop-models-step-by-step/"><u>Successful Repair of Non-Functional USB Port on HP Laptop Models - Step by Step</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-vivo-y77t-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Vivo Y77t Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-definitive-answer-to-solving-glexttexturencompression-level-format-problem-in-opengl-error-1281/"><u>The Definitive Answer to Solving GL_EXT_texture_ncompression Level Format Problem in OpenGL (Error 1281)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209681282-the-resolution-to-your-olive-obstacle-in-nba-2k21-solving-steps-unpacked/"><u>The Resolution to Your Olive Obstacle in NBA 2K21 - Solving Steps Unpacked</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-repair-windows-10s-missing-bluetooth-functionality-with-ease/"><u>Troubleshoot and Repair Windows 10'S Missing Bluetooth Functionality with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solutions-for-automatic-mouse-double-clicks/"><u>Troubleshooting and Solutions for Automatic Mouse Double-Clicks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-timely-response-error-in-system-services-code-1053/"><u>Troubleshooting Guide for Timely Response Error in System Services (Code 1053)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-logitech-mouse-scroll-wheel-issues/"><u>Troubleshooting Guide: Resolving Logitech Mouse Scroll Wheel Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-non-functioning-webcam-in-windows/"><u>Troubleshooting Steps for Non-Functioning Webcam in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-unsuccessful-windows-patches-solutions-proven-effective/"><u>Winning the Battle Against Unsuccessful Windows Patches: Solutions Proven Effective</u></a></li>
</ul></div>
