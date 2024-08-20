---
title: Step-by-Step Solutions for Non-Working Blue Light Filter on Windows 11
date: 2024-08-19T06:47:12.020Z
updated: 2024-08-20T06:47:12.020Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for Non-Working Blue Light Filter on Windows 11
excerpt: This Article Describes Step-by-Step Solutions for Non-Working Blue Light Filter on Windows 11
thumbnail: https://thmb.techidaily.com/805e7ed862b37908d5fd3eef7b67791c5d0d0472cc7eebb84910c74e668a853a.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
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
<li><a href="https://win-howtos.techidaily.com/issue-resolved-how-to-overcome-windows-camera-error-code-0xa0-groovyf4292-and-get-back-to-snapshots/"><u>[Issue Resolved]: How to Overcome Windows Camera Error Code 0xA0 Groovyf4292 and Get Back to Snapshots</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-precision-craftsmanship-building-exquisite-circle-sphere-objects/"><u>[New] 2024 Approved  Precision Craftsmanship  Building Exquisite Circle, Sphere Objects</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-bridging-the-gap-between-classic-and-contemporary-videos-for-2024/"><u>[New] Bridging the Gap Between Classic and Contemporary Videos for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-profiles-profits-and-partnerships-joining-a-youtube-mcn/"><u>[Updated] In 2024, Profiles, Profits & Partnerships  Joining a YouTube MCN</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-navigating-like-a-pro-with-telegram-web/"><u>[Updated] Navigating Like a Pro with Telegram Web</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-quick-mac-screenshot-methods-a-comprehensive-list-for-2024/"><u>[Updated] Quick Mac Screenshot Methods  A Comprehensive List for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-pudding-patrol-tutorial-how-to-guide-to-screen-capture-software/"><u>2024 Approved  Pudding Patrol Tutorial  How-To Guide to Screen Capture Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-typing-troubles-learn-how-to-reconnect-your-wireless-keyboard-with-computer/"><u>Bluetooth Typing Troubles? Learn How to Reconnect Your Wireless Keyboard with Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/charge-rescue-for-pcs-fixing-the-plugged-in-not-charging-error-in-wndows-710/"><u>Charge Rescue for PCs: Fixing the 'Plugged In, Not Charging' Error in Wndows 7/10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cracking-the-code-solving-nvidias-geforce-setting-retrieval-problem/"><u>Cracking the Code: Solving Nvidia's GeForce Setting Retrieval Problem</u></a></li>
<li><a href="https://facebook.techidaily.com/deciphering-usernames-from-profile-names-on-social-networks/"><u>Deciphering Usernames From Profile Names on Social Networks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-broken-usb-connectivity-in-windows-11/"><u>Diagnosing and Repairing Broken USB Connectivity in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-when-your-dell-camera-fails-to-operate-on-a-windows-machine/"><u>Effective Fixes When Your Dell Camera Fails to Operate on a Windows Machine</u></a></li>
<li><a href="https://win-amazing.techidaily.com/find-and-install-logitech-mx-master-mouse-software-the-ultimate-guide/"><u>Find & Install Logitech MX Master Mouse Software: The Ultimate Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/find-the-start-button-on-windows-10/"><u>Find The Start Button on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/finding-companion-cameras-for-windows-hello-effortlessly/"><u>Finding Companion Cameras for Windows Hello Effortlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-microsofts-latest-patches-reviving-your-stalled-windows-update-service/"><u>Getting Microsoft's Latest Patches? Reviving Your Stalled Windows Update Service</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-correcting-the-problem-of-non-existent-binkw32dll-on-your-system/"><u>Guide to Correcting The Problem of Non-Existent BinkW32.DLL on Your System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-effortlessly-repair-a-non-detected-usb-device/"><u>How to Effortlessly Repair a Non-Detected USB Device</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-stop-unexpected-shutdowns-from-watchdogsys-errors-a-step-by-step-guide/"><u>How to Stop Unexpected Shutdowns From watchdog.sys Errors - A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-access-a-wide-range-of-content-via-12-streaming-apps/"><u>In 2024, Access a Wide Range of Content via 12 Streaming Apps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-xiaomi-redmi-note-12-pro-5g-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Xiaomi Redmi Note 12 Pro 5G Fingerprint Lock</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Share/Fake Location on WhatsApp for Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-making-money-on-youtube-a-guide/"><u>In 2024, Making Money on YouTube  A Guide</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-apple-iphone-8-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 5 Tracking Apps to Track Apple iPhone 8 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-copypaste-anomalies/"><u>Overcoming Windows 11 Copy/Paste Anomalies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-for-hidden-bluetooth-devices-in-windows-device-management/"><u>Quick Fix for Hidden Bluetooth Devices in Windows Device Management</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-to-address-and-resolve-steam-disk-write-problems/"><u>Quick Fixes to Address and Resolve Steam Disk Write Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-insufficient-system-resources-errors-for-smoother-operations/"><u>Resolved: Fixing 'Insufficient System Resources' Errors for Smoother Operations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restarting-your-windows-update-service-for-optimal-performance-a-step-by-step-solution/"><u>Restarting Your Windows Update Service for Optimal Performance: A Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/silent-streets-no-more-eliminating-sound-problems-in-forza-horizon-4-with-ease/"><u>Silent Streets No More: Eliminating Sound Problems in Forza Horizon 4 with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-steam-missing-files-issue-regain-your-full-game-access/"><u>Solving the Steam Missing Files Issue: Regain Your Full Game Access</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-ce-34878-0-playstation-4-error-message-updated-solution/"><u>Step-by-Step Fix for CE-34878-0 Playstation 4 Error Message [UPDATED SOLUTION]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-windows-11-sign-in-failures-caused-by-user-profile-services/"><u>Step-by-Step Fixes for Windows 11 Sign-In Failures Caused by User Profile Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-getting-your-windows-optical-drives-back-to-working-order/"><u>Step-by-Step Tutorial: Getting Your Windows Optical Drives Back to Working Order</u></a></li>
<li><a href="https://win-howtos.techidaily.com/success-story-overcoming-the-challenge-of-a-non-starting-computer-system/"><u>Success Story: Overcoming The Challenge of a Non-Starting Computer System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-end-of-the-green-glitch-in-nba-2k21-a-complete-solution/"><u>The End of the Green Glitch in NBA 2K21: A Complete Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-device-not-found-errors-in-windows-111087-resolving-code-24/"><u>Troubleshooting 'Device Not Found' Errors in Windows 11/10/8/7: Resolving Code 24</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-malfunctioning-shift-key-proven-fixes-you-can-apply-today/"><u>Troubleshooting a Malfunctioning Shift Key - Proven Fixes You Can Apply Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-a-hanging-or-stuck-windows-10-computer/"><u>Troubleshooting Tips for a Hanging or Stuck Windows 10 Computer</u></a></li>
<li><a href="https://tech-hub.techidaily.com/what-is-grok-ai-from-elon-musk-inside-look-at-its-potential-and-price-points/"><u>What Is Grok AI From Elon Musk? Inside Look at Its Potential and Price Points</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win10-computer-restarts-without-cause/"><u>Win10: Computer Restarts Without Cause</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-wi-fi-not-showing-here-are-the-fixes-for-missing-connections/"><u>Windows 11 Wi-Fi Not Showing? Here Are the Fixes for Missing Connections</u></a></li>
</ul></div>
