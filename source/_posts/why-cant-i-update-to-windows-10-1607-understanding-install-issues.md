---
title: Why Can't I Update to Windows 10 1607? Understanding Install Issues
date: 2024-08-19T06:52:46.452Z
updated: 2024-08-20T06:52:46.452Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Why Can't I Update to Windows 10 1607? Understanding Install Issues
excerpt: This Article Describes Why Can't I Update to Windows 10 1607? Understanding Install Issues
thumbnail: https://thmb.techidaily.com/f244a4b607ff1304250df827a08b69767edd00f8e4433a759d16a32700c891a6.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-transform-your-editing-master-the-fade-effect/"><u>[New] 2024 Approved  Transform Your Editing  Master the Fade Effect</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-latest-tech-blog-movavi-screencapture-update/"><u>[New] Latest Tech Blog  Movavi ScreenCapture Update</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-optimal-techniques-for-verbal-note-taking-expertise/"><u>[New] Optimal Techniques for Verbal Note-Taking Expertise</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-exclusive-tips-to-elevate-your-canva-projects-by-10x/"><u>[Updated] Exclusive Tips to Elevate Your Canva Projects by 10X</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-boost-your-tiktok-presence-advanced-mac-video-techniques/"><u>[Updated] In 2024, Boost Your TikTok Presence  Advanced Mac Video Techniques</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-insiders-choice-the-best-fb-video-tools/"><u>[Updated] Insider's Choice  The Best FB Video Tools</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-unleash-focus-the-pros-guide-to-distraction-free-google-meet-sessions/"><u>[Updated] Unleash Focus  The Pro's Guide to Distraction-Free Google Meet Sessions</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-how-to-share-a-private-youtube-video/"><u>2024 Approved  How to Share a Private YouTube Video?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-leading-cloud-storage-vendors-a-comparative-pricing-analysis/"><u>2024 Approved  Leading Cloud Storage Vendors  A Comparative Pricing Analysis</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-the-error-a-detailed-walkthrough-of-fixing-the-ce-34878-0-problem-in-playstation-4-devices/"><u>Beat The Error: A Detailed Walkthrough of Fixing the CE-34878-0 Problem in PlayStation 4 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-dell-laptops-pitch-dark-monitor-heres-how-you-can-help-it-full-guide/"><u>Dealing with Dell Laptop's Pitch Dark Monitor? Here’s How You Can Help It (Full Guide)</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-oppo-a78-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Oppo A78 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/discover-14-intriguing-text-animations-to-play-with/"><u>Discover 14 Intriguing Text Animations to Play With</u></a></li>
<li><a href="https://techtrends.techidaily.com/discovering-document-viewer-unveiling-the-secrets-of-google-docs-tracking/"><u>Discovering Document Viewer: Unveiling the Secrets of Google Docs Tracking</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-techniques-to-correct-the-unidentified-external-hardware-issue-and-port-reset-failure-in-windows-10/"><u>Effective Techniques to Correct the Unidentified External Hardware Issue & Port Reset Failure in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-getting-an-unresponsive-xbox-one-controller-back-online/"><u>Expert Advice on Getting an Unresponsive Xbox One Controller Back Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-correcting-windows-driver-power-state-malfunctions/"><u>Expert Tips for Correcting Window's Driver Power State Malfunctions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-an-endless-loop-resolving-the-stuck-infinite-load-of-valorant/"><u>Fixing an Endless Loop: Resolving the Stuck Infinite Load of Valorant</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-non-responsive-sound-issues-in-windows-7/"><u>Fixing the Non-Responsive Sound Issues in Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-printer-driver-not-found-error-on-windows-systems/"><u>How to Fix 'Printer Driver Not Found' Error on Windows Systems</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-innovate-your-podcast-previews-and-trailers-for-2024/"><u>How to Innovate Your Podcast Previews and Trailers for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-roccat-mouse-driver-step-by-step-tutorial/"><u>How to Install Roccat Mouse Driver - Step-by-Step Tutorial</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-enhancing-video-conferencing-with-zoom-and-chromebook/"><u>In 2024, Enhancing Video Conferencing with Zoom and Chromebook</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-nubia-red-magic-8s-pro-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Nubia Red Magic 8S Pro Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-file-explorer-in-windows-10-quick-and-effective-tips/"><u>Mastering File Explorer in Windows 10: Quick and Effective Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fixes-how-to-overcome-error-code-0x8024200d-and-restore-windows-updates-seamlessly/"><u>Mastering the Fixes: How to Overcome Error Code 0X8024200d and Restore Windows Updates Seamlessly</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/mp4-2-mp3-best-mp4-to-mp3-converters/"><u>MP4 2 MP3 Best MP4 to MP3 Converters</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-limitations-for-personalizing-your-computer-navigating-it-rules-on-windows/"><u>Overcoming Limitations for Personalizing Your Computer: Navigating IT Rules on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-error-how-to-successfully-restore-or-fix-your-pc-in-windows-10/"><u>Overcoming the Error: How to Successfully Restore or Fix Your PC in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-non-functional-screen-savers-on-windows-11-devices-quickly/"><u>Resolve Non-Functional Screen Savers on Windows 11 Devices Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-typing-issues-on-your-keyboard-are-now-fixed/"><u>Resolved: Typing Issues on Your Keyboard Are Now Fixed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-high-cpu-usage-by-msmpengexe-on-windows-10-solved/"><u>Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-ineterr-missing-resource-issue-a-step-by-step-guide/"><u>Resolving the [InetErr] Missing Resource Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-dealing-with-a-computer-that-cant-shut-down-windows-10/"><u>Solved! Dealing with a Computer That Can't Shut Down Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-of-a-disconnected-bluetooth-keypad-on-laptopdesktop/"><u>Solving the Problem of a Disconnected Bluetooth Keypad on Laptop/Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-overcoming-windows-11s-bluetooth-connectivity-challenges/"><u>Step-by-Step Fixes: Overcoming Windows 11'S Bluetooth Connectivity Challenges</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fixing-a-pc-that-wont-proceed-past-the-windows-preparation-stage/"><u>Step-by-Step Guide to Fixing a PC That Won't Proceed Past the Windows Preparation Stage</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-by-step-guide-to-full-periscope-capabilities-for-2024/"><u>Step-by-Step Guide to Full Periscope Capabilities for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-guide-to-restoring-binkw32dll-and-ending-error-messages/"><u>The Ultimate Guide to Restoring binkw32.dll and Ending Error Messages</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-correcting-the-notorious-xerox-update-error-in-windows-0x800f020b/"><u>Troubleshooting and Correcting the Notorious Xerox Update Error in Windows (0X800F020B)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-non-responsive-razer-mechanical-keyboard/"><u>Troubleshooting Guide: Fixing a Non-Responsive Razer Mechanical Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-unsupported-commands-on-computer-screens/"><u>Troubleshooting Unsupported Commands on Computer Screens</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-logon-issues-with-keyboard-responsiveness/"><u>Troubleshooting: Logon Issues with Keyboard Responsiveness</u></a></li>
</ul></div>
