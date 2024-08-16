---
title: "Solution Guide: Restoring Volume Control on Windows 11 Systems"
date: 2024-08-15T11:24:22.493Z
updated: 2024-08-16T11:24:22.493Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solution Guide: Restoring Volume Control on Windows 11 Systems"
excerpt: "This Article Describes Solution Guide: Restoring Volume Control on Windows 11 Systems"
thumbnail: https://thmb.techidaily.com/33f7a6674447c8f7173ff1c687707de6ab2b192d47bf8afae9f7fe02b3355e59.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
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
<li><a href="https://extra-skills.techidaily.com/new-navigating-the-maze-of-stock-visual-acquisition/"><u>[New] Navigating the Maze of Stock Visual Acquisition</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-optimize-zoom-performance-top-three-tactical-approaches/"><u>[New] Optimize Zoom Performance  Top Three Tactical Approaches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206025152-solved-crash-the-high-cpu-usage-of-your-system-with-these-tricks-no-matter-if-you-are-using-windows-10linux/"><u>[Solved] Crash the High CPU Usage of Your System with These Tricks, No Matter if You Are Using Windows 10/Linux.</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-how-to-record-itunes-videos/"><u>[Updated] 2024 Approved  How to Record iTunes Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-how-to-use-filters-on-instagram/"><u>[Updated] 2024 Approved  How to Use Filters on Instagram?</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-creative-curvature-enhancing-imagery-with-text-shaping-for-2024/"><u>[Updated] Creative Curvature  Enhancing Imagery with Text Shaping for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-democracy-dive-deep-top-5-political-simulation-titles/"><u>[Updated] In 2024, Democracy Dive Deep  Top 5 Political Simulation Titles</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-integrating-social-video-platforms-with-hdtv/"><u>[Updated] In 2024, Integrating Social Video Platforms with HDTV</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-the-art-of-high-quality-sound-recording-via-audacity/"><u>2024 Approved  The Art of High-Quality Sound Recording via Audacity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-windows-11s-constant-cycling-easy-repair-tips-for-persistent-shutdown-problems/"><u>Beat Windows 11'S Constant Cycling - Easy Repair Tips for Persistent Shutdown Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bugs-and-glitches-the-challenges-of-installing-the-newest-windows-10-v1607-patch/"><u>Bugs and Glitches: The Challenges of Installing the Newest Windows 10 v1607 Patch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-methods-to-repair-integrated-cameras-on-windows-devices/"><u>Efficient Methods to Repair Integrated Cameras on Windows Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-windows-7-launch-speed-top-solutions-to-combat-delays/"><u>Enhance Windows 7 Launch Speed: Top Solutions to Combat Delays!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ensure-flawless-play-with-fixing-xbox-one-controller/"><u>Ensure Flawless Play with Fixing Xbox One Controller</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-resolving-power-plugs-detected-yet-no-charge-on-windows-os/"><u>Expert Tips for Resolving Power Plugs Detected, Yet No Charge on Windows OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-why-wont-my-windows-10-screen-adjust-its-brightness/"><u>Fix: Why Won't My Windows 10 Screen Adjust Its Brightness?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-print-screen-functionality-in-windows-11-and-windows-10-systems/"><u>How to Restore Print Screen Functionality in Windows 11 and Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/igfxem-malfunction-effective-solutions-for-reestablishing-functionality/"><u>IgfxEM Malfunction: Effective Solutions for Reestablishing Functionality</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-realme-11x-5g-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Realme 11X 5G PC | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-turning-off-two-factor-authentication-from-apple-iphone-11-5-tips-you-must-know-by-drfone-ios/"><u>In 2024, Turning Off Two Factor Authentication From Apple iPhone 11? 5 Tips You Must Know</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-device-compatibility-fix-your-pcs-casting-problem-in-the-latest-windows-10-update/"><u>Mastering Device Compatibility: Fix Your PC's Casting Problem in the Latest Windows 10 Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-errors-in-establishing-a-link-to-remote-servers-effective-fixes/"><u>Overcoming Errors in Establishing a Link to Remote Servers: Effective Fixes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-infinix-smart-8-plus-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Infinix Smart 8 Plus to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-of-unresponsive-right-clicks-in-windows-11/"><u>Resolving the Issue of Unresponsive Right Clicks in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-the-power-of-a-lazy-logitech-mouse/"><u>Reviving the Power of a Lazy Logitech Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-youtube-sound-issue-fixing-audioplayer-glitches-in-windows-11/"><u>Solving the YouTube Sound Issue: Fixing Audioplayer Glitches in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-microsoft-widi-adapter-connection-failures-on-windows-11-systems/"><u>Step-by-Step Fix: Microsoft WiDi Adapter Connection Failures on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-d3derr-not-available-errors-on-your-pc/"><u>Step-by-Step Guide: Correcting 'D3DERR Not Available' Errors on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-ensuring-smooth-device-integration-post-windows-11-update/"><u>Step-by-Step Guide: Ensuring Smooth Device Integration Post Windows 11 Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/teredo-struggles-with-eligibility-understanding-the-challenges/"><u>Teredo Struggles with Eligibility: Understanding the Challenges</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-tecno-spark-go-2023-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Tecno Spark Go (2023) Phone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-initializer-not-starting-updated-fixes-2021-problem/"><u>Troubleshooting the 'Initializer Not Starting [Updated Fixes, 2021]' Problem</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlocking-solutions-what-to-do-when-your-iphone-freezes-up/"><u>Unlocking Solutions: What to Do When Your iPhone Freezes Up</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-pdf-printer-effortless-fixes-for-a-smooth-printout/"><u>Unstick Your PDF Printer: Effortless Fixes for a Smooth Printout</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-valorant-startup-a-guide-to-fixing-infinite-loading-screens/"><u>Unstick Your Valorant Startup: A Guide to Fixing Infinite Loading Screens</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-oppo-find-x7-ultra-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Oppo Find X7 Ultra? Fixed | Dr.fone</u></a></li>
</ul></div>
