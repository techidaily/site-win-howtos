---
title: Fixing 'Windows 10 Couldn't Be Installed' Error 80240020 - A Complete Guide to Resolution
date: 2024-08-19T06:52:29.034Z
updated: 2024-08-20T06:52:29.034Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing 'Windows 10 Couldn't Be Installed' Error 80240020 - A Complete Guide to Resolution
excerpt: This Article Describes Fixing 'Windows 10 Couldn't Be Installed' Error 80240020 - A Complete Guide to Resolution
thumbnail: https://thmb.techidaily.com/988b0aa2e48e125d13283fa19f222d53a696ba967b4ae3ee4ad76e4ed04670c1.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-maximize-views-with-these-top-20-thumbnail-fonts/"><u>[New] 2024 Approved  Maximize Views with These Top 20 Thumbnail Fonts</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-top-secure-cloud-stores-for-your-android-compiled/"><u>[New] 2024 Approved  Top Secure Cloud Stores for Your Android - Compiled</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-comprehensive-list-top-screenshot-videography-tools-for-2024/"><u>[New] Comprehensive List  Top Screenshot Videography Tools for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-chrome-os-screen-capture-mastering-the-art-in-four-steps-for-2024/"><u>[Updated] Chrome OS Screen Capture  Mastering the Art in Four Steps for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-essential-blueprint-a-simple-guide-to-facebook-ad-success/"><u>[Updated] Essential Blueprint  A Simple Guide to Facebook Ad Success</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-footage-to-feature-making-youtube-thumbnails-mobile-for-2024/"><u>[Updated] From Footage to Feature  Making YouTube Thumbnails (Mobile) for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-women-in-warfare-youtubes-elite-ten/"><u>[Updated] Women in Warfare  YouTube’s Elite Ten</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-ultimate-mp4-extractor-for-social-media-vids/"><u>2024 Approved  Ultimate MP4 Extractor for Social Media Vids</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-vivo-s18-pro-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Vivo S18 Pro Phone</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-and-repairing-secure-socket-layer-problems-in-firefox-web-explorer/"><u>Addressing and Repairing Secure Socket Layer Problems in Firefox Web Explorer</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/becoming-a-video-wizard-with-screencast-insider-tips/"><u>Becoming a Video Wizard with Screencast Insider Tips</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-samsung-galaxy-z-fold-5-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Samsung Galaxy Z Fold 5</u></a></li>
<li><a href="https://win-howtos.techidaily.com/desktop-icon-disappearance-issues-resolved-in-windows-11-solved/"><u>Desktop Icon Disappearance Issues Resolved in Windows 11 [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-correcting-ethernet-connectivity-troubles-in-windows-107/"><u>Diagnosing and Correcting Ethernet Connectivity Troubles in Windows 10/7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-making-your-lenovos-fingerprint-authentication-work-again/"><u>Easy Fixes: Making Your Lenovo's Fingerprint Authentication Work Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-overcome-the-error-code-0x80240034-during-windows-10-update-process/"><u>Effective Solutions to Overcome the Error Code 0X80240034 During Windows 10 Update Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-ways-to-overcome-minecraft-lan-play-connectivity-errors/"><u>Effective Ways to Overcome Minecraft LAN Play Connectivity Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x800f0831-easily-correct-with-these-steps-on-windows-update/"><u>Error Code 0X800f0831? Easily Correct with These Steps on Windows Update</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/essential-thumbnail-strategies-for-amplifying-viewership-on-youtube/"><u>Essential Thumbnail Strategies for Amplifying Viewership on YouTube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-a-broken-right-click-on-windows-10-systems/"><u>Expert Tips for Fixing a Broken Right Click on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-needed-for-copy-failure-win-11/"><u>Fix Needed for Copy Failure, WIN 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-continuously-use-hamachi-handling-and-fixing-service-disruption-errors/"><u>How To Continuously Use Hamachi: Handling and Fixing Service Disruption Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-set-user-settings-and-avoid-error-driver-failed/"><u>How to Correctly Set User Settings and Avoid 'Error: Driver Failed'</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-poco-x6-screen-sharing-drfone-by-drfone-android/"><u>How To Do Poco X6 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-audio-rendering-errors-in-youtube-with-windows-10/"><u>How to Overcome Audio Rendering Errors in YouTube with Windows 10</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-galaxy-s23-ultra-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from Galaxy S23 Ultra.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-missing-device-issue-code-24-in-windows-operating-systems-11-8-and-7-solutions/"><u>How to Resolve the Missing Device Issue (Code 24) in Windows Operating Systems: 11, 8 & 7 Solutions</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-analyzing-screen-capture-tech-for-professionals/"><u>In 2024, Analyzing Screen Capture Tech for Professionals</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-samsung-galaxy-s23plus-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Samsung Galaxy S23+ to Apple TV | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-list-of-affordable-licensed-game-music-websites/"><u>In 2024, List of Affordable, Licensed Game Music Websites</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-prime-converter-kit-go-from-fb-to-high-fidelity-mp4/"><u>In 2024, Prime Converter Kit  Go From FB to High-Fidelity MP4</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/nba-2k19-ultimate-pro-hoops-experience/"><u>NBA 2K19: Ultimate Pro Hoops Experience</u></a></li>
<li><a href="https://buynow-info.techidaily.com/nixplay-nix-advance-x15d-digital-frame-review-beautiful-hd-photos/"><u>Nixplay NIX Advance X15D Digital Frame Review: Beautiful HD Photos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-compatibility-problems-with-shockwave-flash-on-google-chrome/"><u>Overcoming Compatibility Problems with Shockwave Flash on Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-shockwave-flash-crashes-tips-for-google-chrome-users/"><u>Overcoming Shockwave Flash Crashes: Tips for Google Chrome Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-gpu-load-from-desktop-window-manager-on-win11-a-guide-with-5-fixes/"><u>Resolve Excessive GPU Load From Desktop Window Manager on Win11: A Guide with 5 Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-steps-when-printscreen-fails-in-windows-11-and-windows-10/"><u>Resolved! Troubleshooting Steps When PrintScreen Fails in Windows 11 and Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-freezing-taskbars-in-windows-11-most-efficient-methods/"><u>Resolving Freezing Taskbars in Windows 11 – Most Efficient Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-non-playable-content-on-windows-a-step-by-step-guide/"><u>Solving the Issue of Non-Playable Content on Windows - A Step by Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-troublesome-reset-failed-an-error-occurred-in-windows-11/"><u>Solving the Troublesome 'Reset Failed: An Error Occurred' In Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-addressing-high-graphics-power-usage-stemming-from-the-desktop-window-manager-in-windows-11/"><u>Step-by-Step Guide: Addressing High Graphics Power Usage Stemming From the Desktop Window Manager in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-correcting-invalid-parameter-errors-efficiently/"><u>Step-by-Step Tutorial: Correcting Invalid Parameter Errors Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/surface-pro-4-pen-problem-heres-how-you-can-get-it-working-again/"><u>Surface Pro 4 Pen Problem? Here’s How You Can Get It Working Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/system-specification-alert-the-engine-runs-only-on-systems-with-directx-11-gpu-support/"><u>System Specification Alert: The Engine Runs Only on Systems with DirectX 11 GPU Support</u></a></li>
<li><a href="https://extra-resources.techidaily.com/tablet-artistry-top-8-drawing-software-for-ipados/"><u>Tablet Artistry  Top 8 Drawing Software for iPadOS</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-battle-of-flagships-iphone-15-pro-max-vs-samsung-s24-ultra-analysis/"><u>The Battle of Flagships: IPhone 15 Pro Max Vs. Samsung S24 Ultra Analysis</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-video-sounds-overcoming-audio-renderer-problems-on-windows-11/"><u>Troubleshoot Your Video Sounds - Overcoming Audio Renderer Problems on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-dealing-with-the-persistent-d3derr-not-available-error/"><u>Troubleshooting Guide: Dealing With the Persistent D3DERR NOT AVAILABLE Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-reactivating-mac-and-windows-keyboard-illumination/"><u>Troubleshooting Guide: Reactivating Mac and Windows Keyboard Illumination</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-the-windows-11-kb5003602-update-malfunction/"><u>Troubleshooting Tips for the Windows 11 KB5003602 Update Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-lowering-telemetry-impact-on-storage-in-windows-10-and-11/"><u>Understanding and Lowering Telemetry Impact on Storage in Windows 10 & 11</u></a></li>
</ul></div>
