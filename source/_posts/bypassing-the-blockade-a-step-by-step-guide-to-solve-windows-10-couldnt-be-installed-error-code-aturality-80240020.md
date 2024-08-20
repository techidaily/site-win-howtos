---
title: "Bypassing the Blockade: A Step-by-Step Guide to Solve Windows 10 Couldn't Be Installed - Error Code Aturality | 80240020"
date: 2024-08-19T06:38:36.899Z
updated: 2024-08-20T06:38:36.899Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Bypassing the Blockade: A Step-by-Step Guide to Solve Windows 10 Couldn't Be Installed - Error Code Aturality | 80240020"
excerpt: "This Article Describes Bypassing the Blockade: A Step-by-Step Guide to Solve Windows 10 Couldn't Be Installed - Error Code Aturality | 80240020"
thumbnail: https://thmb.techidaily.com/84164da8d50de5c78ef7a37eabfb52e8bc2ce824a8108b09359dc8a81eead685.jpeg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-device-friendly-tutorial-inserting-your-shorts-into-youtube/"><u>[New] In 2024, Device-Friendly Tutorial  Inserting Your Shorts Into YouTube</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-instantaneous-installation-laugh-with-ifunny-memes-easily-for-2024/"><u>[New] Instantaneous Installation  Laugh with iFunny Memes Easily for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-resolving-social-media-puzzle-zippy-fb-videos-not-in-view-for-2024/"><u>[New] Resolving Social Media Puzzle  Zippy FB Videos Not in View for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-stream-video-freely-on-any-os-no-cost-video-player/"><u>[New] Stream Video Freely on Any OS  No-Cost VIDEO Player</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-xiaomi-11-series-a-visual-journey-through-precision-recording-for-2024/"><u>[New] Xiaomi 11 Series  A Visual Journey Through Precision Recording for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restarts-computer-responds-to-games/"><u>[RESTARTS] Computer Responds to Games</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-elevate-video-popularity-with-strategic-hashtags/"><u>[Updated] Elevate Video Popularity with Strategic #Hashtags</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-sky-high-storages-expert-recommendations/"><u>[Updated] In 2024, Sky-High Storages  Expert Recommendations</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-speedy-retrieval-of-snap-archive/"><u>[Updated] In 2024, Speedy Retrieval of Snap Archive</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-jpeg-to-gif-with-a-click-ranked-list-of-top-free-converters/"><u>[Updated] JPEG to GIF with a Click  Ranked List of Top Free Converters</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-understanding-luts-to-amplify-your-photo-quality/"><u>[Updated] Understanding LUTs to Amplify Your Photo Quality</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-leading-phones-gopro-editing-solutions-revealed/"><u>2024 Approved  Leading Phones' GoPro Editing Solutions Revealed</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-leveraging-health-data-in-online-healthcare-ads/"><u>2024 Approved  Leveraging Health Data in Online Healthcare Ads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-sign-in-error-messages-caused-by-user-profile-service-in-windows-operating-systems/"><u>Addressing Sign-In Error Messages Caused by User Profile Service in Windows Operating Systems</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-honor-100-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Honor 100 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-error-code-24-device-missing-in-windows-1187-environments/"><u>Comprehensive Fixes for Error Code 24 - Device Missing in Windows 11/8/7 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corsair-keyboard-failure-heres-how-to-restore-its-functionality/"><u>Corsair Keyboard Failure? Here's How to Restore Its Functionality!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/critical-system-file-not-installed/"><u>Critical System File Not Installed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-restore-airpods-pairing-on-your-windows-pc-a-step-by-step-tutorial/"><u>Easy Steps to Restore AirPods Pairing on Your Windows PC : A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-sims-4-game-not-starting-correctly/"><u>Effective Solutions for Sims 4 Game Not Starting Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortlessly-resolve-your-windows-10-continuous-rebooting-dilemma-today/"><u>Effortlessly Resolve Your Windows 10 Continuous Rebooting Dilemma Today</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-speed-differences-chatgpt-4-vs-chatgpt-35/"><u>Exploring the Speed Differences: ChatGPT-4 Vs. ChatGPT-3.5</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-the-your-pc-cant-be-reset-issue-in-windows-10-solution-guide/"><u>How to Overcome the 'Your PC Can’t Be Reset' Issue in Windows 10 - Solution Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-your-computers-night-light-on-windows-10-and-11-systems/"><u>How to Restore Your Computer’s Night Light on Windows 10 and 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-turn-on-bluetooth-on-windows-7-solved/"><u>How to Turn on Bluetooth on Windows 7 [Solved]</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hp-laptop-usb-dysfunction-heres-how-to-restore-its-functionality/"><u>HP Laptop USB Dysfunction? Here’s How to Restore Its Functionality</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-apps-and-online-tools-to-track-oneplus-ace-3-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track OnePlus Ace 3 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-valorant-lags-post-reboot-solution/"><u>Navigating Valorant Lags: Post-Reboot Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-disruptions-the-guide-to-stop-shockwave-flash-from-crashing-on-google-chrome/"><u>No More Disruptions: The Guide to Stop Shockwave Flash From Crashing on Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208645794-overcome-stuck-keyboard-arrows-effective-troubleshooting-tips-inside/"><u>Overcome Stuck Keyboard Arrows - Effective Troubleshooting Tips Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-windows-10s-0x80072efd-mistake-a-step-by-step-guide/"><u>Resolve Windows 10'S 0X80072EFD Mistake: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-correct-non-compatible-device-drivers-on-windows-os-for-optimal-performance/"><u>Resolved: How To Correct Non-Compatible Device Drivers On Windows OS For Optimal Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-silent-issues-effective-solutions-for-your-acer-laptops-audio-problem/"><u>Resolving Silent Issues: Effective Solutions for Your Acer Laptop's Audio Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-update-issues-fixing-windows-10-freezing-during-installation/"><u>Resolving Update Issues: Fixing Windows 10 Freezing During Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-for-when-windows-cant-locate-the-right-printer-driver-fixed/"><u>Solution for When Windows Can’t Locate the Right Printer Driver [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-bluetooth-connectivity-issues-repair-windows-mouse-connection/"><u>Solve Your Bluetooth Connectivity Issues - Repair Windows Mouse Connection</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/take-your-online-presence-to-new-heights-with-youtube-edits-in-sony-vegas-for-2024/"><u>Take Your Online Presence to New Heights with YouTube Edits in Sony Vegas for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-vivo-y17s-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Vivo Y17s Phone Hassle-Free</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-role-of-msda80dll-in-your-system-and-its-necessity/"><u>The Role of MSDA80DLL in Your System and Its Necessity</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-guide-to-top-5-expertly-curated-ai-course-rankings/"><u>The Ultimate Guide to Top 5 Expertly Curated AI Course Rankings</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/transforming-youtube-videos-into-cash-flows-for-2024/"><u>Transforming YouTube Videos Into Cash Flows for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/trouble-with-msidll-heres-how-to-fix-the-file-not-detected-error/"><u>Trouble with msi.dll? Here’s How to Fix the File Not Detected Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-copy-and-paste-glitches-on-your-latest-windows-operating-system/"><u>Troubleshooting Copy & Paste Glitches on Your Latest Windows Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-crc-eliminating-persistent-data-integrity-problems/"><u>Troubleshooting CRC: Eliminating Persistent Data Integrity Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-windows-10s-unwanted-keep-restarting-dilemma/"><u>Winning Against Windows 10'S Unwanted Keep Restarting Dilemma</u></a></li>
</ul></div>
