---
title: "Error 80240020: Why Windows 10 Won't Install & How You Can Successfully Resolve It"
date: 2024-08-19T07:17:09.306Z
updated: 2024-08-20T07:17:09.306Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error 80240020: Why Windows 10 Won't Install & How You Can Successfully Resolve It"
excerpt: "This Article Describes Error 80240020: Why Windows 10 Won't Install & How You Can Successfully Resolve It"
thumbnail: https://thmb.techidaily.com/ac052320a70f53cd4defac365f581dfb457a1cc20abd20579ee272bb28f0f35e.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-twitter-live-sound-solving-partially-muted-audio-issues/"><u>[New] 2024 Approved  Twitter Live Sound  Solving Partially Muted Audio Issues</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-best-practices-for-converting-webp-to-jpg-format/"><u>[New] Best Practices for Converting WebP to JPG Format</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-bridging-the-gap-between-classic-and-contemporary-videos/"><u>[Updated] 2024 Approved  Bridging the Gap Between Classic and Contemporary Videos</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-your-top-10-favorites-on-spotify/"><u>[Updated] 2024 Approved  Your Top 10 Favorites on Spotify</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-essential-steps-for-logging-virtual-exchanges-for-2024/"><u>[Updated] Essential Steps for Logging Virtual Exchanges for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-maximize-video-visibility-on-facebook-via-youtube/"><u>[Updated] In 2024, Maximize Video Visibility on Facebook via YouTube</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-innovative-strategies-for-maximizing-your-facebook-videos/"><u>2024 Approved  Innovative Strategies for Maximizing Your Facebook Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/5-effective-ways-to-correct-the-black-display-issue-with-google-chrome/"><u>5 Effective Ways to Correct the Black Display Issue with Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/busting-the-silence-restoring-mic-functionality-on-windows-10-computers/"><u>Busting the Silence: Restoring Mic Functionality on Windows 10 Computers</u></a></li>
<li><a href="https://facebook.techidaily.com/cracking-open-the-mystery-of-vague-online-posts/"><u>Cracking Open the Mystery of Vague Online Posts</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/direct-links-to-download-corsair-icue-optimized-for-windows-11-and-10-systems/"><u>Direct Links to Download Corsair iCUE - Optimized for Windows 11 & 10 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/epson-scannerprinter-blank-page-mystery-solved/"><u>Epson Scanner/Printer Blank Page Mystery Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0x80072ee7-in-the-windows-store-easy-fixes-unveiled/"><u>Error 0X80072EE7 in the Windows Store: Easy Fixes Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-80240020-on-your-mind-heres-how-to-successfully-install-windows-11/"><u>Error 80240020 on Your Mind? Here's How to Successfully Install Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-fixes-for-the-persistent-werfaultexe-problem-in-windows-os/"><u>Expert Fixes for the Persistent WERFault.exe Problem in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-overcoming-call-failed-error-on-win1011/"><u>Guidelines for Overcoming 'Call Failed' Error on Win10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-device-not-found-when-casting-from-windows-10-computer/"><u>How to Resolve 'Device Not Found' When Casting From Windows 10 Computer</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-x-to-others-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone X To Others Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hp-spectre-x360-overheating-problem-solved/"><u>HP Spectre X360 Overheating Problem [Solved]</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-effective-ways-to-fix-checkra1n-error-31-on-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, Effective Ways To Fix Checkra1n Error 31 On iPhone 15 Pro Max</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-essential-mc-stronghold-constructions/"><u>In 2024, Essential MC Stronghold Constructions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210673109-lenovo-mouse-pad-troubles-in-windows-87-discover-the-quick-fix/"><u>Lenovo Mouse Pad Troubles in Windows 8/7? Discover the Quick Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-white-screen-of-death-a-guide-for-laptop-users/"><u>Overcoming the White Screen of Death: A Guide for Laptop Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/persistent-usb-problem-solved-stop-seeing-device-not-recognized-alerts-forever/"><u>Persistent USB Problem Solved: Stop Seeing 'Device Not Recognized' Alerts Forever!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/professional-gopro-filming-made-simple-a-comprehensive-guide/"><u>Professional GoPro Filming Made Simple  A Comprehensive Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-unresponsive-hp-laptop-keyboards-learn-how/"><u>Quick Fixes for Unresponsive HP Laptop Keyboards – Learn How!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-no-audio-output-device-found-issues-on-windows-11-a-step-by-step-guide/"><u>Resolving 'No Audio Output Device Found' Issues on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-errors-quickly-using-system-file-check-sfc-and-deployment-imaging-service-dism/"><u>Resolving Windows Errors Quickly Using System File Check (SFC) and Deployment Imaging Service (DISM)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-port-reset-error-a-guide-to-troubleshooting-your-usb-on-windows-10/"><u>Solving the Port Reset Error: A Guide to Troubleshooting Your USB on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-disappearing-bluetooth-icon-in-windows-10-environment/"><u>Step-by-Step Fix for Disappearing Bluetooth Icon in Windows 10 Environment</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/top-5-best-rtf-helis-why-blade-e-flite-mcx2-reigns-supreme/"><u>Top 5 Best RTF Helis - Why Blade E-Flite mCX2 Reigns Supreme</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723200871325-troubleshooting-tips-stop-windows-10-unwanted-automatic-re-starts-now/"><u>Troubleshooting Tips: Stop Windows 10 Unwanted Automatic Re-Starts Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-fortnite-gaming-for-your-discontinued-windows-graphics-card-a-fix-guide/"><u>Unlocking Fortnite Gaming for Your Discontinued Windows Graphics Card: A Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208329490-windows-10-users-say-goodbye-to-keyboard-latency-issues/"><u>Windows 10 Users, Say Goodbye to Keyboard Latency Issues!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206834834-winupdate-trouble-heres-how-to-fix-error-0x80240017-for-good/"><u>WinUpdate Trouble? Here's How to Fix Error 0X80240017 for Good!</u></a></li>
</ul></div>
