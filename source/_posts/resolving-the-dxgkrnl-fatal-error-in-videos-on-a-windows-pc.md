---
title: Resolving the Dxgkrnl Fatal Error in Videos on a Windows PC
date: 2024-08-19T06:43:13.949Z
updated: 2024-08-20T06:43:13.949Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving the Dxgkrnl Fatal Error in Videos on a Windows PC
excerpt: This Article Describes Resolving the Dxgkrnl Fatal Error in Videos on a Windows PC
thumbnail: https://thmb.techidaily.com/73182ed54b3d34ca981abeae24ed800ccc098d1b157cf1a2528e89d05cbc2979.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
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
<li><a href="https://win-howtos.techidaily.com/issue-resolved-how-to-overcome-windows-camera-error-code-0xa0-groovyf4292-and-get-back-to-snapshots/"><u>[Issue Resolved]: How to Overcome Windows Camera Error Code 0xA0 Groovyf4292 and Get Back to Snapshots</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-dodging-doubts-a-guide-to-vloggings-most-common-anxieties-for-2024/"><u>[Updated] Dodging Doubts  A Guide to Vlogging's Most Common Anxieties for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-navigating-tiktok-web-efficiently-as-a-mac-user/"><u>[Updated] In 2024, Navigating TikTok Web Efficiently as a Mac User</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-spin-the-web-advanced-tips-for-video-orientation-in-youtube-for-2024/"><u>[Updated] Spin the Web  Advanced Tips for Video Orientation in YouTube for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-utilizing-luts-for-professional-color-grading/"><u>[Updated] Utilizing LUTs for Professional Color Grading</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-charismatic-charm-of-moving-text-on-screen/"><u>2024 Approved  Charismatic Charm of Moving Text on Screen</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-nokia-c12-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-typing-troubles-learn-how-to-reconnect-your-wireless-keyboard-with-computer/"><u>Bluetooth Typing Troubles? Learn How to Reconnect Your Wireless Keyboard with Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/charge-rescue-for-pcs-fixing-the-plugged-in-not-charging-error-in-wndows-710/"><u>Charge Rescue for PCs: Fixing the 'Plugged In, Not Charging' Error in Wndows 7/10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209362481-conquer-minecraft-setbacks-with-ease-fix-your-encounter-with-error-code-5-today/"><u>Conquer Minecraft Setbacks with Ease – Fix Your Encounter with Error Code 5 Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cracking-the-code-solving-nvidias-geforce-setting-retrieval-problem/"><u>Cracking the Code: Solving Nvidia's GeForce Setting Retrieval Problem</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Honor X50i | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-broken-usb-connectivity-in-windows-11/"><u>Diagnosing and Repairing Broken USB Connectivity in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-hard-drive-access-problems-in-windows-10/"><u>Expert Tips for Fixing Hard Drive Access Problems in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/find-the-start-button-on-windows-10/"><u>Find The Start Button on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/finding-companion-cameras-for-windows-hello-effortlessly/"><u>Finding Companion Cameras for Windows Hello Effortlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-incompatibility-issues-update-your-device-driver-on-windows-operating-system/"><u>Fixing Incompatibility Issues: Update Your Device Driver on Windows Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-microsofts-latest-patches-reviving-your-stalled-windows-update-service/"><u>Getting Microsoft's Latest Patches? Reviving Your Stalled Windows Update Service</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-correcting-the-problem-of-non-existent-binkw32dll-on-your-system/"><u>Guide to Correcting The Problem of Non-Existent BinkW32.DLL on Your System</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>How to Change Location on TikTok to See More Content On your Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-effortlessly-repair-a-non-detected-usb-device/"><u>How to Effortlessly Repair a Non-Detected USB Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-broken-spacebar-issue-on-microsofts-latest-operating-system/"><u>How to Fix a Broken Spacebar Issue on Microsoft's Latest Operating System</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-excel-2013-formulas-not-working-properly-step-by-step-guide-stellar-by-stellar-guide/"><u>How to Fix Excel 2013 Formulas Not Working Properly | Step-by-Step Guide | Stellar</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-honor-90-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Honor 90 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-techniques-for-rectifying-vexing-screen-rippling-in-valorant-games/"><u>In-Depth Techniques for Rectifying Vexing Screen Rippling in VALORANT Games</u></a></li>
<li><a href="https://tech-revival.techidaily.com/innovative-ways-to-use-chatgpt-for-tailoring-your-auto-modifications/"><u>Innovative Ways to Use ChatGPT for Tailoring Your Auto Modifications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/is-my-netflix-service-disrupted-find-out-why-and-how-to-fix-it-now/"><u>Is My Netflix Service Disrupted? Find Out Why & How To Fix It Now!</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-the-article-below-will-show-you-some-of-the-best-apps-to-convert-a-video-to-a-live-photo-and-how-to-set-up-live-photos-as-wallpaper-on-iph/"><u>New 2024 Approved The Article Below Will Show You some of the Best Apps to Convert a Video to a Live Photo, and How to Set up Live Photos as Wallpaper on iPhone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-your-windows-10-access-denied-hurdle-comprehensive-troubleshooting-guide-solved/"><u>Overcome Your Windows 10 'Access Denied' Hurdle - Comprehensive Troubleshooting Guide [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-for-hidden-bluetooth-devices-in-windows-device-management/"><u>Quick Fix for Hidden Bluetooth Devices in Windows Device Management</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-to-address-and-resolve-steam-disk-write-problems/"><u>Quick Fixes to Address and Resolve Steam Disk Write Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-insufficient-system-resources-errors-for-smoother-operations/"><u>Resolved: Fixing 'Insufficient System Resources' Errors for Smoother Operations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restarting-your-windows-update-service-for-optimal-performance-a-step-by-step-solution/"><u>Restarting Your Windows Update Service for Optimal Performance: A Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/silent-streets-no-more-eliminating-sound-problems-in-forza-horizon-4-with-ease/"><u>Silent Streets No More: Eliminating Sound Problems in Forza Horizon 4 with Ease</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/simplify-slide-sharing-at-work-webcam-assisted-tips-for-2024/"><u>Simplify Slide Sharing at Work  Webcam-Assisted Tips for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-steam-missing-files-issue-regain-your-full-game-access/"><u>Solving the Steam Missing Files Issue: Regain Your Full Game Access</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-ce-34878-0-playstation-4-error-message-updated-solution/"><u>Step-by-Step Fix for CE-34878-0 Playstation 4 Error Message [UPDATED SOLUTION]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-windows-11-sign-in-failures-caused-by-user-profile-services/"><u>Step-by-Step Fixes for Windows 11 Sign-In Failures Caused by User Profile Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-fixing-the-inoperative-touchpad-scroll-in-windows-10-devices/"><u>Step-by-Step Guide: Fixing the Inoperative Touchpad Scroll in Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-getting-your-windows-optical-drives-back-to-working-order/"><u>Step-by-Step Tutorial: Getting Your Windows Optical Drives Back to Working Order</u></a></li>
<li><a href="https://win-howtos.techidaily.com/success-story-overcoming-the-challenge-of-a-non-starting-computer-system/"><u>Success Story: Overcoming The Challenge of a Non-Starting Computer System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-tackled-persistent-doubling-of-mouse-clicks/"><u>Successfully Tackled: Persistent Doubling of Mouse Clicks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-end-of-the-green-glitch-in-nba-2k21-a-complete-solution/"><u>The End of the Green Glitch in NBA 2K21: A Complete Solution</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-8-iphone-selfie-stick-choices-revealed/"><u>Top 8 iPhone Selfie Stick Choices Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-device-not-found-errors-in-windows-111087-resolving-code-24/"><u>Troubleshooting 'Device Not Found' Errors in Windows 11/10/8/7: Resolving Code 24</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-malfunctioning-shift-key-proven-fixes-you-can-apply-today/"><u>Troubleshooting a Malfunctioning Shift Key - Proven Fixes You Can Apply Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-the-initial-blackout-in-monster-hunter-world/"><u>Troubleshooting Guide: Fixing the Initial Blackout in Monster Hunter: World</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missed-extra-monitor/"><u>Troubleshooting Missed Extra Monitor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-a-hanging-or-stuck-windows-10-computer/"><u>Troubleshooting Tips for a Hanging or Stuck Windows 10 Computer</u></a></li>
<li><a href="https://some-skills.techidaily.com/utilizing-in-presentation-speech-to-text-functionality-in-powerpoint-for-2024/"><u>Utilizing In-Presentation Speech-to-Text Functionality in PowerPoint for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win10-computer-restarts-without-cause/"><u>Win10: Computer Restarts Without Cause</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-wi-fi-not-showing-here-are-the-fixes-for-missing-connections/"><u>Windows 11 Wi-Fi Not Showing? Here Are the Fixes for Missing Connections</u></a></li>
</ul></div>
