---
title: "Comprehensive Guide: Resolving the 'Cannot Find Source File' - 0X80070^[SOLVED] Windows Update Error"
date: 2024-08-19T07:39:21.229Z
updated: 2024-08-20T07:39:21.229Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Comprehensive Guide: Resolving the 'Cannot Find Source File' - 0X80070^[SOLVED] Windows Update Error"
excerpt: "This Article Describes Comprehensive Guide: Resolving the 'Cannot Find Source File' - 0X80070^[SOLVED] Windows Update Error"
thumbnail: https://thmb.techidaily.com/50ec9f96a3862eafb44f6037d6d07d4292a04cc1b5866ca0d81d1cb562971c20.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
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
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-easy-access-guide-skype-audio-to-mp3-free/"><u>[Updated] In 2024, Easy-Access Guide  Skype Audio to Mp3, Free</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-freenoweb-cam-app-assessment-and-comparison-guide/"><u>[Updated] In 2024, FreenoWeb Cam App Assessment & Comparison Guide</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-comprehensive-guide-to-premium-data-reservoirs/"><u>2024 Approved  Comprehensive Guide to Premium Data Reservoirs</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-transforming-dull-interviews-into-engaging-assessments/"><u>2024 Approved  Transforming Dull Interviews Into Engaging Assessments</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/adapt-images-to-any-size-on-your-iphone-instantly/"><u>Adapt Images to Any Size on Your iPhone Instantly</u></a></li>
<li><a href="https://facebook.techidaily.com/designing-visuals-that-stand-out-in-the-fb-crowd/"><u>Designing Visuals That Stand Out in the Fb Crowd</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210904347-error-0x802a1ee9-errconnectionrefused-easy-image-based-solutions-to-get-you-connected-again/"><u>Error 0X802A1EE9 (ERR_CONNECTION_REFUSED): Easy Image-Based Solutions to Get You Connected Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-fixing-screen-failure-on-dell-laptops-a-comprehensive-walkthrough/"><u>Expert Advice: Fixing Screen Failure on Dell Laptops - A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-restoring-functionality-to-a-dell-laptop-keyboard/"><u>Expert Advice: Restoring Functionality to a Dell Laptop Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-applicationexe-error-how-to-resolve-the-program-crash/"><u>Fixing 'Application.exe' Error: How to Resolve the Program Crash</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-unexpected-freezing-problems-when-booting-into-windows-10/"><u>Fixing Unexpected Freezing Problems When Booting Into Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-your-lenovo-mouse-pad-malfunction-across-different-versions-of-windows-a-step-by-step-guide/"><u>Fixing Your Lenovo Mouse Pad Malfunction Across Different Versions of Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722975860705-get-your-logitech-g29-steering-wheel-drivers-for-pcs-running-windows-10117-now/"><u>Get Your Logitech G29 Steering Wheel Drivers for PCs Running Windows 10/11/7 Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206213816-guide-to-fixing-windows-unable-to-access-sen-issue-resolved/"><u>Guide to Fixing 'Windows Unable to Access SEN' - Issue Resolved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-enabling-and-displaying-bluetooth-drivers-via-device-manager/"><u>Guide: Enabling and Displaying Bluetooth Drivers via Device Manager</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-reorient-an-inverted-laptop-display-back-to-normal/"><u>How To Correctly Reorient An Inverted Laptop Display Back To Normal</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-easily-correct-the-troublesome-0x80072efd-error-encountered-in-windows-10/"><u>How to Easily Correct the Troublesome 0X80072EFD Error Encountered in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-unresponsive-fn-keys-a-guide-for-asus-notebook-users/"><u>How to Repair Unresponsive Fn Keys: A Guide for ASUS Notebook Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-error-0x80070426-on-your-windows-11-system-efficiently/"><u>How to Resolve the 'Error 0X80070426' On Your Windows 11 System Efficiently</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-audio-alchemy-transforming-instagram-videos-with-sound/"><u>In 2024, Audio Alchemy  Transforming Instagram Videos with Sound</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-infinix-gt-10-pro-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Infinix GT 10 Pro Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-a-lost-apple-iphone-13-for-free-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track a Lost Apple iPhone 13 for Free? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-zte-blade-a73-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on ZTE Blade A73 5G Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/miracast-and-graphics-driver-support-overcoming-the-compatibility-challenge/"><u>Miracast and Graphics Driver Support: Overcoming the Compatibility Challenge</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-write-protection-solutions-for-usb-sd-card-and-cd-disc-problems-in-windows-environments/"><u>Overcoming Write Protection: Solutions for USB, SD Card & CD Disc Problems in Windows Environments</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/pawsome-vision-unpacking-the-features-that-make-furbos-dog-camera-a-top-choice/"><u>Pawsome Vision: Unpacking the Features That Make Furbo’s Dog Camera a Top Choice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-resolution-why-is-my-computer-taking-longer-to-shut-down-in-windows-11/"><u>Quick Resolution: Why Is My Computer Taking Longer to Shut Down in Windows 11?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-successfully-restore-downloaded-steam-patches-and-fixes/"><u>Steps to Successfully Restore Downloaded Steam Patches and Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-resolving-the-unable-to-initialize-directx-graphics-error/"><u>Successfully Resolving the 'Unable to Initialize DirectX Graphics' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-invisible-mouse-cursor-problems-on-windows-11-solutions-inside/"><u>Troubleshooting the Invisible Mouse Cursor Problems on Windows 11 – Solutions Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-resolving-hp-laptop-webcam-issues-on-windows-10/"><u>Troubleshooting Tips: Resolving HP Laptop Webcam Issues on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-solving-laptop-mouse-freezing-issues/"><u>Ultimate Guide: Solving Laptop Mouse Freezing Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win10-tackling-excessive-cpu-waste/"><u>Win10: Tackling Excessive CPU Waste</u></a></li>
</ul></div>
