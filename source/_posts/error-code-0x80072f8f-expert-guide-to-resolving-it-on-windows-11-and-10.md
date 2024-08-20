---
title: "Error Code 0X80072f8f: Expert Guide to Resolving It on Windows 11 & 10"
date: 2024-08-19T06:59:35.972Z
updated: 2024-08-20T06:59:35.972Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 0X80072f8f: Expert Guide to Resolving It on Windows 11 & 10"
excerpt: "This Article Describes Error Code 0X80072f8f: Expert Guide to Resolving It on Windows 11 & 10"
thumbnail: https://thmb.techidaily.com/41ff678b4dcc101622fd3ddb2b8cccf21c75e6fdbac012d53d8a0b29b1503958.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/new-capture-the-internets-attention-craft-with-kapwing-for-2024/"><u>[New] Capture the Internet’s Attention – Craft with Kapwing for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-optimizing-television-access-to-facebook-events/"><u>[New] Optimizing Television Access to Facebook Events</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-crafting-visual-harmony-with-bokeh-techniques-in-storytelling/"><u>[Updated] 2024 Approved  Crafting Visual Harmony with Bokeh Techniques in Storytelling</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-discover-top-5-ios-ps2-games-simulators/"><u>[Updated] Discover Top 5 IOS PS2 Games Simulators</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-samsung-galaxy-m34-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Samsung Galaxy M34 Fingerprint Lock</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-repair-instructions-the-stop-working-issue-with-32-bit-print-management-hosts-resolved/"><u>Comprehensive Repair Instructions: The Stop Working Issue with 32-Bit Print Management Hosts Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solution-for-microsoft-antimalware-engine-overusing-resources-on-your-windows-11-pc/"><u>Comprehensive Solution for Microsoft Antimalware Engine Overusing Resources on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-tutorial-diagnosing-and-repairing-windows-driver-power-failures/"><u>Comprehensive Tutorial: Diagnosing and Repairing Windows Driver Power Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/computer-boot-issues-solved-a-guide-to-overcoming-initialization-hiccups/"><u>Computer Boot Issues Solved: A Guide to Overcoming Initialization Hiccups</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-failed-save-of-display-preferences/"><u>Correcting Failed Save of Display Preferences</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-dealing-with-freezing-issues-on-your-laptop-mouse/"><u>Effective Solutions for Dealing with Freezing Issues on Your Laptop Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhanced-efficiency-in-wdf-addressing-previous-cpu-overload-concerns/"><u>Enhanced Efficiency in WDF: Addressing Previous CPU Overload Concerns</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhancement-alert-new-gpu-prerequisite-d3d11-compatibility-required-by-game-software/"><u>Enhancement Alert: New GPU Prerequisite - D3D11 Compatibility Required by Game Software</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/enhancing-winter-vlogs-with-five-heartwarming-backdrops/"><u>Enhancing Winter Vlogs with Five Heartwarming Backdrops</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-overcoming-the-update-failed-error-code-0x800f0922-on-windows-10/"><u>Expert Tips for Overcoming the 'Update Failed' Error (Code 0X800f0922) on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208637048-fixing-the-issue-how-to-resolve-windows-update-error-code-0x8007001f/"><u>Fixing the Issue: How to Resolve Windows Update Error Code 0X8007001f</u></a></li>
<li><a href="https://win-howtos.techidaily.com/geforce-experience-wont-open-comprehensive-solutions-and-fixes/"><u>GeForce Experience Won't Open - Comprehensive Solutions and Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-lenovos-malfunctioning-special-function-keys-a-step-by-step-guide/"><u>How to Repair Lenovo's Malfunctioning Special Function Keys: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-to-your-astro-a40s-malfunctioning-mic/"><u>How to Restore Functionality to Your Astro A40's Malfunctioning Mic</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-8-safe-and-effective-methods-to-unlock-your-apple-iphone-12-without-a-passcode-drfone-by-drfone-ios/"><u>In 2024, 8 Safe and Effective Methods to Unlock Your Apple iPhone 12 Without a Passcode | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-vivo-y27s-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Vivo Y27s to Apple TV | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-telegram-online-comprehensive-user-guide/"><u>In 2024, Mastering Telegram Online  Comprehensive User Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-connectivity-how-to-ensure-flawless-bluetooth-pairing-on-your-windows-11-pc/"><u>Master Connectivity: How to Ensure Flawless Bluetooth Pairing on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211140305-master-the-trick-to-keep-your-cs-go-game-running-smoothly/"><u>Master the Trick to Keep Your CS GO Game Running Smoothly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/monster-hunter-world-troubleshooting-guide-tackling-the-ominous-black-screen-on-boot/"><u>Monster Hunter: World Troubleshooting Guide – Tackling the Ominous Black Screen on Boot</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-typing-troubles-overcoming-windows-11s-input-lag-issues/"><u>No More Typing Troubles: Overcoming Windows 11'S Input Lag Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-the-window-plus-shift-plus-s-hurdle-on-your-computer-running-windows-11-or-10/"><u>Overcome the 'Window + Shift + S' Hurdle on Your Computer Running Windows 11 or 10</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/packaging-growth-tactics-for-2024/"><u>Packaging Growth Tactics for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-asus-rog-phone-8-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Asus ROG Phone 8 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repairing-damaged-system-files-in-windows-10-and-11-step-by-step-guide/"><u>Repairing Damaged System Files in Windows 10 & 11 – Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolution-steps-enable-detection-of-unrecognized-wd-my-passport-ultra-external-hard-drive/"><u>Resolution Steps: Enable Detection of Unrecognized 'WD My Passport Ultra' External Hard Drive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-with-your-laptops-keyboard-tips-and-solutions/"><u>Resolving Issues with Your Laptop's Keyboard - Tips & Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-the-usb-port-how-to-restore-functionality-in-your-hp-notebook/"><u>Reviving the USB Port: How to Restore Functionality in Your HP Notebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206824332-reviving-your-keyboards-arrow-buttons-effective-solutions-inside/"><u>Reviving Your Keyboard's Arrow Buttons – Effective Solutions Inside</u></a></li>
<li><a href="https://tech-revival.techidaily.com/safeguarding-against-chatbot-breaches-with-insights-into-neural-network-attacks/"><u>Safeguarding Against Chatbot Breaches with Insights Into Neural Network Attacks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-tips-for-fixing-media-connection-errors-on-your-windows-computer/"><u>Solution Tips for Fixing Media Connection Errors on Your Windows Computer</u></a></li>
<li><a href="https://program-issues.techidaily.com/speeding-up-chrome-in-seconds-a-step-by-step-guide-for-a-smooth-experience/"><u>Speeding Up Chrome in Seconds – A Step-by-Step Guide for a Smooth Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-common-dll-has-stopped-working-in-windows-bid-error-goodbye/"><u>Step-by-Step Fix for 'Common DLL Has Stopped Working' In Windows: Bid Error Goodbye</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-tutorial-quickly-set-up-hp-printerlaptop-drivers/"><u>Step-by-Step Tutorial: Quickly Set Up HP Printer/Laptop Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-fix-tips-for-overcoming-the-absence-of-hardware-drivers-in-windows-7-setup/"><u>Successful Fix Tips for Overcoming the Absence of Hardware Drivers in Windows 7 Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-overcoming-the-kb4056892-hurdle-windows-10-update-installation-tips/"><u>Successfully Overcoming the KB4056892 Hurdle - Windows 10 Update Installation Tips</u></a></li>
<li><a href="https://extra-hints.techidaily.com/tactical-approach-for-finalizing-a-dormant-linkedin-profile/"><u>Tactical Approach for Finalizing a Dormant LinkedIn Profile</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/the-best-of-the-best-top-ipad-video-editing-software-for-2024/"><u>The Best of the Best Top iPad Video Editing Software for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-tips-and-solutions-for-fixing-a-non-responsive-ps4-microphone/"><u>Top Tips & Solutions for Fixing a Non-Responsive PS4 Microphone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-microsoft-wireless-display-drivers-in-windows-n11-solutions-and-tips/"><u>Troubleshooting Microsoft Wireless Display Drivers in Windows N11 – Solutions and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-quick-solutions-for-unrecognized-usb-flash-drives/"><u>Troubleshooting: Quick Solutions for Unrecognized USB Flash Drives</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-fixing-and-preventing-critical-errors-in-google-chrome-stay-protected/"><u>Ultimate Guide: Fixing and Preventing Critical Errors in Google Chrome - Stay Protected!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-epson-scan-communication-issues/"><u>Unlocking Epson Scan Communication Issues</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-or-fresh-install-of-brother-mfc-7860dw-printer-software-for-windows-users/"><u>Update or Fresh Install of Brother MFC-7860DW Printer Software for Windows Users</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-honor-x8b-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Honor X8b</u></a></li>
</ul></div>
