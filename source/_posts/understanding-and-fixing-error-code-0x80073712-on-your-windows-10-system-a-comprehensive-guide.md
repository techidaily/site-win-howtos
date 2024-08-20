---
title: Understanding and Fixing 'Error Code 0X80073712' On Your Windows 10 System – A Comprehensive Guide
date: 2024-08-19T06:52:00.997Z
updated: 2024-08-20T06:52:00.997Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Understanding and Fixing 'Error Code 0X80073712' On Your Windows 10 System – A Comprehensive Guide
excerpt: This Article Describes Understanding and Fixing 'Error Code 0X80073712' On Your Windows 10 System – A Comprehensive Guide
thumbnail: https://thmb.techidaily.com/32523e559641d9ec27c8a10ab7be14cb0b35f831c8a7be2e764f2665633793d5.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://win-howtos.techidaily.com/fixed-windows-11-red-screen-issue/"><u>[Fixed] Windows 11 Red Screen Issue</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-melodypulse-recorder-downloads-guide/"><u>[New] In 2024, Melodypulse Recorder Downloads Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-learn-from-the-greats-strategies-for-confident-online-sharing/"><u>[New] Learn From the Greats  Strategies for Confident Online Sharing</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-sourav-joshis-guide-to-earning/"><u>[New] Sourav Joshi's Guide to Earning</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-elevating-your-vlogs-with-high-quality-editing-premiere-pro-style/"><u>[Updated] 2024 Approved  Elevating Your Vlogs with High-Quality Editing - Premiere Pro Style</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-chasing-profit-on-platforms-youtube-partner-application-steps-for-2024/"><u>[Updated] Chasing Profit on Platforms  YouTube Partner Application Steps for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-unveiling-new-perspectives-streaming-aerial-content-on-facebook/"><u>[Updated] In 2024, Unveiling New Perspectives  Streaming Aerial Content on Facebook</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-navigating-the-landscape-of-digital-grading-tools/"><u>[Updated] Navigating the Landscape of Digital Grading Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-troubleshooting-for-svchostexe-memory-hog-on-windows-10-machines/"><u>Comprehensive Troubleshooting for svchost.exe Memory Hog on Windows 10 Machines</u></a></li>
<li><a href="https://article-files.techidaily.com/designing-an-emotional-film-flashback-frenzy-for-2024/"><u>Designing an Emotional Film Flashback Frenzy for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-not-enough-memory-or-cpu-errors-in-service-requests/"><u>Effective Solutions for 'Not Enough Memory or CPU' Errors in Service Requests</u></a></li>
<li><a href="https://extra-information.techidaily.com/enjoy-dual-views-expert-tips-for-utilizing-picture-in-picture-on-netflix/"><u>Enjoy Dual Views  Expert Tips for Utilizing Picture-in-Picture on Netflix</u></a></li>
<li><a href="https://youtube-data.techidaily.com/t-strategies-for-tackling-copyright-claims-on-youtube-for-2024/"><u>Expert Strategies for Tackling Copyright Claims on YouTube for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-motorola-razr-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-odd-top-scroll-reflex-in-windows-10s-file-explorer-for-improved-user-experience/"><u>Fixing the Odd Top-Scroll Reflex in Windows 10'S File Explorer for Improved User Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-10-sound-settings-solving-the-non-responsive-volume-issue/"><u>Fixing Windows 10 Sound Settings: Solving the Non-Responsive Volume Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-back-to-gaming-expert-tips-on-repairing-overwatch-voice-communication-issues/"><u>Get Back to Gaming: Expert Tips on Repairing Overwatch Voice Communication Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-microsoft-wireless-display-device-working-again-on-windows-11/"><u>How to Get Your Microsoft Wireless Display Device Working Again on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-connection-difficulties-with-destiny-amoor-game-servers/"><u>How To Overcome Connection Difficulties with Destiny Amoor Game Servers</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-record-internet-radio-a-simple-guide/"><u>In 2024, How To Record Internet Radio - A Simple Guide</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-vivo-v29-pro-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Vivo V29 Pro FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-the-graphic-problem-in-overwatch/"><u>Overcoming the Graphic Problem in Overwatch</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723002707338-pc-players-struggle-with-everspace-ii-but-solutions-exist-learn-them-now/"><u>PC Players Struggle With Everspace II, But Solutions Exist – Learn Them Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resetting-valorant-for-smooth-play-system-approach/"><u>Resetting Valorant for Smooth Play: System Approach</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-identifying-and-fixing-the-windows-10-update-database-issue/"><u>Resolved: Identifying and Fixing the Windows 10 Update Database Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-windows-10-trapped-in-flight-setting/"><u>Resolving the Issue: Windows 10 Trapped in Flight Setting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-failed-to-initialize-network-hurdle-in-dragon-ball-fighterz/"><u>Solving the 'Failed to Initialize Network' Hurdle in Dragon Ball FighterZ</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-xerox-printer-update-mishap-error-code-0x80f020b-on-windows-systems/"><u>Solving the Xerox Printer Update Mishap: Error Code 0X80^F020B on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-opening-the-microsoft-store-after-unexpected-crashes/"><u>Troubleshooting Tips - Opening the Microsoft Store After Unexpected Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-how-to-restart-your-diagnostic-tool-successfully/"><u>Troubleshooting Tips: How to Restart Your Diagnostic Tool Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-to-fixing-a-stuck-windows-10-taskbar/"><u>Ultimate Guide to Fixing a Stuck Windows 10 Taskbar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-cannot-connect-error-0x80072fed-on-windows-10/"><u>Ultimate Guide: Resolving the 'Cannot Connect' Error (0X80072FED) on Windows 10</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-don-t-have-google-pixel-fold-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you don't have Google Pixel Fold fingerprint</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wacom-tablet-not-working-heres-how-to-restore-functionality-and-get-back-to-creating/"><u>Wacom Tablet Not Working? Here's How to Restore Functionality and Get Back to Creating</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-hidden-icons-on-windows-11-effective-restoration-techniques/"><u>Winning Against Hidden Icons on Windows 11 - Effective Restoration Techniques</u></a></li>
</ul></div>
