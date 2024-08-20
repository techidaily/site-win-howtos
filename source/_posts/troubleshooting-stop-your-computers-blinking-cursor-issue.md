---
title: "Troubleshooting: Stop Your Computer's Blinking Cursor Issue"
date: 2024-08-19T07:21:54.474Z
updated: 2024-08-20T07:21:54.474Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: Stop Your Computer's Blinking Cursor Issue"
excerpt: "This Article Describes Troubleshooting: Stop Your Computer's Blinking Cursor Issue"
thumbnail: https://thmb.techidaily.com/0f399835ae801930fc09d856b55526ca68007b6aa28f7cfc8442056063114a14.jpg
---

## Troubleshooting Missing Desktop Icons on Windows 11 – Solved

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf526e8ebcab-1024x552.jpg)

If your desktop icons somehow disappear on your Windows 10 computer, don’t worry, you can try the tips below to fix the issue. Quickly and easily.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## Try these tips

You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Enable Show desktop icons**](#t1)
2. [**Check your desktop icon settings**](#t2)
3. [**Rebuild icon cache**](#t4)
4. [**Perform a system restore**](#t5)
5. [**Reset your computer**](#t6)
6. [**Bonus tip**](#t7)

### Tip 1: Enable Show desktop icons

Make sure you have enabled the “Show desktop icon” feature on Windows 10:

1. Right-click your desktop, click **View**, and check **Show desktop icons**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf52ca259fe4.jpg)
2. Check to see if your desktop icons are back. If not, try Tip 2, below.

---

### Tip 2: Check your desktop icon settings

1. Right-click your desktop and click **Personalize**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf531bcea206.jpg)
2. Click **Themes** \> **Desktop icon settings**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53220a4552.jpg)
3. Select the icons you want to show on desktop, then click **OK**.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53279e9206.jpg)
4. Check if your “desktop icons missing” problem is resolved. If not, try Tip 3, below.

---

### Tip 3: Rebuild icon cache

You can also try these steps to rebuild the icon cache:

1. Run **Command Prompt** as administrator.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
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

### Tip 4: Perform a system restore

If your desktop icons still don’t show up, you can perform a system restore to return your system to a date when the icons appeared normally on the desktop. Here’s how to perform a system restore to help fix your “desktop icons disappeared in Windows 10” issue:

1. Type **recovery** in the Windows search box, then press **Enter**.
2. At Recovery, click **Open System Restore**.  
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a2728a7e.jpg)
3. Select **Choose a different restore point**, and click **Next**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a34c35bc.jpg)
4. Check the box beside **Show more restore points**. You should see a list of ‘restore points’. These are like backups of your computer, as it was at that particular date and time. Think back to a date when your desktop icons showed up, and **select a restore point** from that date or slightly earlier (but no later).  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a4d84f3c.jpg)
5. Click **Next** \> **Finish**.
6. Check to see if your desktop icons are now restored on Windows 10\. If not, try Tip 5, below.

---

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Tip 5: Reset your computer

If the steps above didn’t work for you. Resetting your computer is worth a try. It fixed the desktop icon issue for some users.

1. Click the **Start** button > the **Settings** icon.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b790f639.jpg)
2. Click **Update & security** \> **Recovery**.
3. In the **Reset this PC** area, click the **Get started** button. Then follow the on-screen instructions to reset your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b9dab56d.jpg)

---

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
### Bonus tip

A missing or outdated graphics driver may also stop items from appearing properly on PC. You should make sure your graphics card driver is up to date. There are two ways to update your graphics driver: **manually** and **automatically**.

**Update your graphics driver manually** — You can update your driver manually by going to the hardware manufacturer’s website, and searching for the latest driver for your graphics card. But if you take this approach, be sure to choose the driver that’s compatible with the exact model number of your hardware, and your version of Windows.

OR

**Update your graphics driver automatically** — If you don’t have the time, patience, or computer skills to update your driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.
2. Run Driver Easy and click **Scan Now**. Driver Easy will then scan your computer and detect any problem drivers.  
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-unrestricted-story-preservation-free/"><u>[New] 2024 Approved  Unrestricted Story Preservation, FREE</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-best-budget-gaming-accessories-keyboards-and-mice-under-99/"><u>[New] Best Budget Gaming Accessories  Keyboards & Mice Under $99</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-effective-use-of-adsense-on-youtube-to-boost-channel-income/"><u>[New] Effective Use of AdSense on YouTube to Boost Channel Income</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-piecing-a-puzzle-of-cinematic-highlights/"><u>[New] Piecing a Puzzle of Cinematic Highlights</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-top-alert-tones-superior-download-sites-list-for-2024/"><u>[New] Top Alert Tones  Superior Download Sites List for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/riting-for-impact-a-compreenas-guide-to-youtube-video-storytelling-for-2024/"><u>[New] Writing for Impact  A Compreenas Guide to YouTube Video Storytelling for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-how-to-step-into-a-tiktok-event-like-a-pro/"><u>[Updated] 2024 Approved  How to Step Into a TikTok Event Like a Pro</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-elevate-your-art-with-professional-color-alteration-for-2024/"><u>[Updated] Elevate Your Art with Professional Color Alteration for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/1716069067071-updated-in-2024-apocalypse-arena-top-8-zombie-games-showdown-ranked/"><u>[Updated] In 2024, Apocalypse Arena  Top 8 Zombie Games Showdown Ranked!</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-partition-performance-topping-recorder-showdown-for-2024/"><u>[Updated] Partition Performance  Topping Recorder Showdown for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-simple-steps-for-android-voice-recording-no-root-for-2024/"><u>[Updated] Simple Steps for Android Voice Recording (No Root) for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-unveiling-the-secrets-of-live-broadcasting-on-instagram-through-obs-for-2024/"><u>[Updated] Unveiling the Secrets of Live Broadcasting on Instagram Through OBS for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-why-are-social-media-suggested-videos-evanescent-for-2024/"><u>[Updated] Why Are Social Media Suggested Videos Evanescent for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-inside-look-at-instagrams-subtle-yet-powerful-features/"><u>2024 Approved  Inside Look at Instagram's Subtle Yet Powerful Features</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-leveraging-keywords-for-peak-marketing-results/"><u>2024 Approved  Leveraging Keywords for Peak Marketing Results</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-the-change-rendering-api-glitch-dota-2-error-2024-with-this-quick-guide/"><u>Beat the Change Rendering API Glitch (Dota 2 Error 2024) with This Quick Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202077745-dragon-ball-fighterz-successfully-overcoming-network-setup-errors/"><u>Dragon Ball FighterZ - Successfully Overcoming Network Setup Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205997164-easy-fixes-for-windows-11s-disappearing-bluetooth-feature-get-started-now/"><u>Easy Fixes for Windows 11'S Disappearing Bluetooth Feature – Get Started Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-guide-to-repairing-inactive-at-sign-functionality/"><u>Easy Guide to Repairing Inactive 'At Sign' Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/exe-error-troubleshoot-and-resolve/"><u>Exe Error: Troubleshoot & Resolve</u></a></li>
<li><a href="https://win-howtos.techidaily.com/execution-inhibited-awaiting-signal/"><u>Execution Inhibited: Awaiting Signal</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-bad-image-issues-in-windows-11-and-10/"><u>Fixing 'Bad Image' Issues in Windows 11 and 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-class-registration-issues-in-windows-10-a-comprehensive-guide/"><u>Fixing Class Registration Issues in Windows 10 - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/games-glitches-unstoppable-system-crashes/"><u>Games Glitches: Unstoppable System Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203393456-how-to-get-your-windows-pertinent-audio-services-up-and-running-again/"><u>How to Get Your Windows Pertinent Audio Services up and Running Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-browser-render-engine-setup-failures-recent-solutions/"><u>How to Overcome Browser Render Engine Setup Failures - Recent Solutions</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-track-imei-number-of-oppo-a18-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Oppo A18 Through Google Earth?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-vivo-x100-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Vivo X100 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-a-guide-to-the-finest-apps-for-instagram-reel-creation/"><u>In 2024, A Guide to the Finest Apps for Instagram Reel Creation</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-capturing-the-action-ps4-to-video-using-obs/"><u>In 2024, Capturing the Action  PS4 to Video Using OBS</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-oppo-a1x-5g-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Oppo A1x 5G Device SIM</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-infinix-note-30i-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Infinix Note 30i To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-nokia-c110-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Nokia C110 Devices</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/integration-guide-how-to-enjoy-imessage-features-while-using-an-android-phone-or-tablet/"><u>Integration Guide: How to Enjoy iMessage Features While Using an Android Phone or Tablet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-mouse-pad-malfunctions-in-windows-top-troubleshooting-steps-for-windows-1087-users/"><u>Lenovo Mouse Pad Malfunctions in Windows: Top Troubleshooting Steps for Windows 10/8/7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-controller-repair-fixing-dead-left-analogue-sticks-for-console-gamers/"><u>Mastering Controller Repair: Fixing Dead Left Analogue Sticks for Console Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/msda80dll-explained-why-this-file-matters-for-your-pc/"><u>MSDA80.DLL Explained: Why This File Matters for Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-buildings-not-loading-fixed/"><u>PUBG Buildings Not Loading [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-resolving-windows-update-error-0x80070652/"><u>Quick Solutions for Resolving Window's Update Error 0X80070652</u></a></li>
<li><a href="https://win-howtos.techidaily.com/recovering-lost-resource-msvcr71dll/"><u>Recovering Lost Resource: MSVCR71.dll</u></a></li>
<li><a href="https://win-howtos.techidaily.com/requirements-your-pc-needs-a-d3d11-compatible-graphics-card-for-optimal-performance/"><u>Requirements: Your PC Needs a D3d11-Compatible Graphics Card for Optimal Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-access-issues-for-the-primary-partition-on-windows-11-computers/"><u>Resolving Access Issues for the Primary Partition on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-audio-problems-repairing-mic-issues-in-windows-10/"><u>Resolving Audio Problems: Repairing Mic Issues in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-extended-waiting-time-error-in-semaphore-communication/"><u>Resolving the Issue: Extended Waiting Time Error in Semaphore Communication</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-fixes-for-when-your-pc-gets-stuck-during-windows-update-at-0/"><u>Simple Fixes for When Your PC Gets Stuck During Windows Update at 0%%</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-addressing-user-settings-cause-driver-failure-problem/"><u>Solution Found! Addressing 'User Settings Cause Driver Failure' Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-screen-mirroring-problems-on-windows-10-expert-tips-and-solutions/"><u>Solve Screen Mirroring Problems on Windows 10 – Expert Tips & Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-10-mouse-malfunctions-restoring-right-click-capabilities/"><u>Solving Windows 10 Mouse Malfunctions: Restoring Right-Click Capabilities</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-enabling-bluetooth-connectivity-in-windows-11-and-windows-10/"><u>Step-by-Step Guide: Enabling Bluetooth Connectivity in Windows 11 and Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-restore-your-computers-sound-after-no-audio-device-found-on-windows/"><u>Steps to Restore Your Computer's Sound After 'No Audio Device Found' On Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-vivo-t2-5g-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Vivo T2 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-boot-issues-in-windows-11/"><u>Troubleshooting Guide: Resolving Boot Issues in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-unsuccessful-windows-11-1607-feature-update/"><u>Troubleshooting Steps for Unsuccessful Windows 11 1607 Feature Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-resolving-the-sims-4-wont-open-problem/"><u>Troubleshooting Steps: Resolving the 'Sims 4 Won't Open' Problem</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlock-the-secret-to-easier-mobile-troubleshooting-with-just-a-restart/"><u>Unlock the Secret to Easier Mobile Troubleshooting with Just a Restart</u></a></li>
<li><a href="https://win-howtos.techidaily.com/update-error-unsuccessful-upgrade-to-windows-10-version-1607/"><u>Update Error: Unsuccessful Upgrade to Windows 10 (Version 1607)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/xbox-one-woes-learn-to-sync-an-inactive-controller-with-ease/"><u>Xbox One Woes? Learn to Sync an Inactive Controller with Ease</u></a></li>
</ul></div>
