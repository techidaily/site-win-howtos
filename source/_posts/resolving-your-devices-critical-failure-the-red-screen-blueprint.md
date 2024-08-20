---
title: "Resolving Your Device's Critical Failure: The Red Screen Blueprint"
date: 2024-08-19T06:25:19.133Z
updated: 2024-08-20T06:25:19.133Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Your Device's Critical Failure: The Red Screen Blueprint"
excerpt: "This Article Describes Resolving Your Device's Critical Failure: The Red Screen Blueprint"
thumbnail: https://thmb.techidaily.com/c3e0373857c4f6ff49001a6f640f1a15c7eebbb819c0655734f3bd74245cc5d7.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
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
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-anime-inspired-dance-routines-top-20-tiktok-trends/"><u>[New] In 2024, Anime-Inspired Dance Routines  Top 20 TikTok Trends</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-guide-to-structuring-youtube-content-with-separate-chapters/"><u>[New] In 2024, Guide to Structuring YouTube Content with Separate Chapters</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-re-enable-sound-on-twitter-video-tweets/"><u>[New] In 2024, Re-Enable Sound on Twitter Video Tweets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-skyrim-infinite-loading-screen-issue/"><u>[Solved] Skyrim Infinite Loading Screen Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-windows-update-error-0x80070002-easily/"><u>[Solved] Windows Update Error 0X80070002 | Easily!</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-elite-ears-microphones-for-lectures/"><u>[Updated] In 2024, Elite Ears  Microphones for Lectures</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-secure-your-video-conferences-recording-made-easy/"><u>[Updated] In 2024, Secure Your Video Conferences  Recording Made Easy</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-iphone-hacks-seamless-video-repetition/"><u>[Updated] IPhone Hacks  Seamless Video Repetition</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-signs-that-youve-been-muted-by-someone/"><u>2024 Approved  Signs That You've Been Muted by Someone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-the-ultimate-framework-perfecting-live-broadcasts-via-obs-and-zoom/"><u>2024 Approved  The Ultimate Framework  Perfecting Live Broadcasts via OBS & Zoom</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/a-comprehensive-review-of-the-more-reasonable-apple-iphone-se-202-1/"><u>A Comprehensive Review of the More Reasonable Apple iPhone SE (202 1)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211932697-acer-quiet-crisis-proven-steps-to-reactivate-your-laptop-speakers/"><u>Acer Quiet Crisis? Proven Steps to Reactivate Your Laptop Speakers!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-fixing-the-0x80072efd-issue-on-windows-10-systems/"><u>Effective Solutions for Fixing the 0X80072EFD Issue on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0x80072efd-on-windows-11-understanding-causes-and-implementing-fixes-for-a-smooth-operating-experience/"><u>Error 0X80072EFD on Windows 11: Understanding Causes and Implementing Fixes for a Smooth Operating Experience</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-issue-when-your-windows-10-lacks-a-coprocessor-driver/"><u>Fixing the Issue When Your Windows 10 Lacks a Coprocessor Driver</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-why-steam-content-servers-are-not-responding/"><u>Fixing the Issue: Why Steam Content Servers Are Not Responding</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-non-operative-diagnostics-policy-service-step-by-step-guide/"><u>Fixing the Non-Operative Diagnostics Policy Service - Step by Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-your-non-responsive-dell-bluetooth-mouse-or-wireless-keyboard/"><u>Fixing Your Non-Responsive Dell Bluetooth Mouse or Wireless Keyboard</u></a></li>
<li><a href="https://extra-resources.techidaily.com/hidden-horizons-in-hand-drawn-harmony/"><u>Hidden Horizons in Hand-Drawn Harmony</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-mouse-keeps-disconnecting/"><u>How To Fix Mouse Keeps Disconnecting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-10-error-code-80240020-and-ensure-a-smooth-installation-experience/"><u>How to Fix Windows 10 Error Code 80240020 and Ensure a Smooth Installation Experience</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-12plus-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Realme 12+ 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-achieving-zero-expense-in-picture-filled-content/"><u>In 2024, Achieving Zero Expense in Picture-Filled Content</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-amplifying-your-playlists-on-instagram/"><u>In 2024, Amplifying Your Playlists on Instagram</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-10-updates-essential-guide-to-solving-error-code-0x800f0922-with-8-fixes/"><u>Mastering Windows 10 Updates: Essential Guide to Solving Error Code 0X800f0922 with 8 Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-fixing-insufficient-system-resources-error-to-fulfill-your-request/"><u>Solved: Fixing 'Insufficient System Resources' Error to Fulfill Your Request</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-how-to-fix-windows-update-hanging-on-100/"><u>Solved: How to Fix Windows Update Hanging on 100%%</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-enabling-bluetooth-connectivity-in-windows-7/"><u>Step-by-Step Guide: Enabling Bluetooth Connectivity in Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/streamlining-scannerprinter-connection-for-optimal-performance/"><u>Streamlining Scanner/Printer Connection for Optimal Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-windows-system-failure-with-error-0xc0000005/"><u>Troubleshooting and Repairing Windows System Failure with Error 0XC0000005</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212293023-windows-7-startup-woes-heres-how-to-get-faster-boot-speeds/"><u>Windows 7 Startup Woes? Here's How to Get Faster Boot Speeds</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-update-cannot-currently-check-for-updates-solved/"><u>Windows Update Cannot Currently Check For Updates [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-strategies-against-windows-11-taskbar-freezing-a-comprehensive-fix-list/"><u>Winning Strategies Against Windows 11 Taskbar Freezing: A Comprehensive Fix List</u></a></li>
</ul></div>
