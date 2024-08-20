---
title: Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now
date: 2024-08-19T07:17:56.550Z
updated: 2024-08-20T07:17:56.550Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now
excerpt: This Article Describes Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now
thumbnail: https://thmb.techidaily.com/f33adb8a41f790bc858c47b5fb66f5998fe40f1007e9c52f968a63abc439ec92.jpg
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-mastering-your-camera-essential-tactics-for-hit-youtube-videos/"><u>[New] 2024 Approved  Mastering Your Camera  Essential Tactics for Hit YouTube Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-unleashing-potential-best-macos-recording-apps-analysis/"><u>[New] 2024 Approved  Unleashing Potential  Best macOS Recording Apps Analysis</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-asian-themed-mini-mansions-for-creative-builders-for-2024/"><u>[New] Asian Themed Mini Mansions for Creative Builders for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-insightful-reviews-from-vllo-users/"><u>[New] Insightful Reviews From VLLO Users</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-ultra-clear-gaming-best-21-hdmi-compatible-monitors-ps5-for-2024/"><u>[New] Ultra Clear Gaming  Best 2.1 HDMI Compatible Monitors [PS5] for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-watch-in-style-top-8-best-mobile-movies-for-iphones/"><u>[Updated] 2024 Approved  Watch in Style  Top 8 Best Mobile Movies for iPhones</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-exploring-entertainment-youtubes-integration-with-fb/"><u>[Updated] In 2024, Exploring Entertainment  YouTube's Integration with FB</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-how-to-record-video-with-logitech-webcam/"><u>[Updated] In 2024, How to Record Video with Logitech Webcam</u></a></li>
<li><a href="https://win-howtos.techidaily.com/2023s-definitive-tricks-to-optimize-performance-and-reduce-lags-in-fallout-4-adventures/"><u>2023'S Definitive Tricks to Optimize Performance & Reduce Lags in Fallout 4 Adventures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/audio-woes-in-win-10-over-now-smooth-operations/"><u>Audio Woes in WIN 10 Over, Now Smooth Operations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209865722-battleye-service-install-errors-now-corrected/"><u>BattlEye Service Install Errors - Now Corrected</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-advanced-chatbots-like-chatgpt-replace-human-jobs-a-detailed-analysis/"><u>Can Advanced Chatbots Like ChatGPT Replace Human Jobs? A Detailed Analysis</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-step-by-step-tutorial-resolving-the-dark-display-issue-on-your-dell-notebook/"><u>Complete Step-by-Step Tutorial: Resolving the Dark Display Issue on Your Dell Notebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-to-overcome-error-code-0x802n-2400d-on-your-pcs-updates/"><u>Comprehensive Solutions to Overcome Error Code 0X802n-2400D on Your PC's Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-resolving-the-unresponsive-start-menu-in-windows-11-systems/"><u>Diagnosing & Resolving the Unresponsive Start Menu in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-guide-troubleshooting-and-repairing-error-ebd-c0fe3897-b4f0-4aa5-a8e1-2dd5d3cbcefa-in-windows/"><u>Effortless Guide: Troubleshooting and Repairing Error Ebd-C0fe3897-B4f0-4aa5-A8e1-2dd5d3cbcefa in Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/enhancing-visuals-in-remote-collaborations-with-google-meet/"><u>Enhancing Visuals in Remote Collaborations with Google Meet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-fixes-for-windows-10-not-shutting-down-now-resolved/"><u>Expert Fixes for Windows 10 Not Shutting Down - Now Resolved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-for-geforce-experience-cant-load-settings-issues/"><u>Fixes for 'GeForce Experience Can't Load Settings' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-fix-the-bluetooth-disappeared-error-on-windows-11-a-simple-guide/"><u>How to Correctly Fix the 'Bluetooth Disappeared' Error on Windows 11 – A Simple Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-realme-note-50-screen-sharing-drfone-by-drfone-android/"><u>How To Do Realme Note 50 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-migrate-android-data-from-realme-narzo-60x-5g-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Migrate Android Data From Realme Narzo 60x 5G to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-the-d3derr-notavailable-mistake-in-windows-systems/"><u>How To Overcome the 'D3DERR NOTAVAILABLE' Mistake in Windows Systems</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-realme-narzo-n53-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Realme Narzo N53 for Free? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-unlock-on-iphone-12-pro-how-to-fix-it-by-drfone-ios/"><u>In 2024, Apple ID Unlock On iPhone 12 Pro? How to Fix it?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlink-apple-id-from-apple-iphone-6s-plus-by-drfone-ios/"><u>In 2024, How To Unlink Apple ID From Apple iPhone 6s Plus</u></a></li>
<li><a href="https://extra-resources.techidaily.com/innovative-approaches-to-nba-game-broadcasting/"><u>Innovative Approaches to NBA Game Broadcasting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overclocking-odds-on-your-side-again-fast-fixes/"><u>Overclocking Odds on Your Side Again - Fast Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-dota-navigating-through-error-2024-in-change-rendering-api-tips-and-tricks/"><u>Overcoming Dota Navigating Through Error 2024 in 'Change Rendering API' – Tips and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-dormant-windows-keys-for-functionality/"><u>Overhauling Dormant Windows Keys for Functionality</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/precision-in-visuals-learning-to-soften-specific-areas-for-2024/"><u>Precision in Visuals  Learning to Soften Specific Areas for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-audio-glitches-with-speaker-pop-crackles-in-windows-operating-systems-solved/"><u>Resolve Audio Glitches with Speaker Pop-Crackles in Windows Operating Systems (Solved)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-hdcp-compatibility-issues-for-optimal-display-functionality/"><u>Resolving HDCP Compatibility Issues for Optimal Display Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-unreachable-website-error-in-google-chrome-step-by-step-solution/"><u>Resolving the Unreachable Website Error in Google Chrome - Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-volume-control-glitches-tips-and-tricks-for-windows-users/"><u>Resolving Volume Control Glitches: Tips and Tricks for Windows Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/simplified-avatar-design-in-the-metaverse-explained-for-2024/"><u>Simplified Avatar Design in the Metaverse Explained for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-connection-issues-how-to-get-airpods-working-with-windows-11/"><u>Solving Your Connection Issues: How To Get AirPods Working with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-trickery-head-on-proven-tips-for-removing-misleading-google-chrome-error-notifications/"><u>Tackling Trickery Head-On: Proven Tips for Removing Misleading Google Chrome Error Notifications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-fix-is-in-how-to-reactivate-sound-in-acer-computers-silently-struggling/"><u>The Fix Is In: How to Reactivate Sound in Acer Computers Silently Struggling</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-fix-ensuring-wd-my-passport-ultra-is-compatible-and-visible-to-windows-systems/"><u>The Fix: Ensuring WD My Passport Ultra Is Compatible and Visible to Windows Systems</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-vivo-s18e-by-drfone-android/"><u>Three Ways to Sim Unlock Vivo S18e</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-application-launch-failures-with-error-0xc000007b-steps-for-success/"><u>Troubleshoot and Fix Application Launch Failures with Error 0xC000007B – Steps for Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-miracast-connectivity-problems-tips-to-fix-device-support-issues/"><u>Troubleshoot Miracast Connectivity Problems: Tips to Fix Device Support Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-bootmgr-is-missing-errors-with-easy-diagrams/"><u>Troubleshooting and Repairing 'BOOTMGR Is Missing' Errors with Easy Diagrams</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-making-your-usb-drive-detectable-again/"><u>Troubleshooting Guide: Making Your USB Drive Detectable Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-non-functional-keyboard-illumination-on-macbook-and-desktop-computers/"><u>Troubleshooting Guide: Non-Functional Keyboard Illumination on MacBook and Desktop Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-minecraft-solutions-for-opengl-errors/"><u>Troubleshooting Minecraft: Solutions for OpenGL Errors</u></a></li>
<li><a href="https://screen-capture.techidaily.com/troubleshooting-pc-issues-for-sons-of-the-forest-expert-tips-and-tricks/"><u>Troubleshooting PC Issues for 'Sons of the Forest': Expert Tips and Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-windows-10-system-restore-fails/"><u>Troubleshooting Steps When Windows 10 System Restore Fails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-ftdi-bus-system-errors-driver-incompatibility-causes-loss-of-memory-protection/"><u>Understanding FTDI Bus System Errors: Driver Incompatibility Causes Loss of Memory Protection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/xbox-one-and-pc-integration-button-maneuvers/"><u>Xbox One & PC Integration: Button Maneuvers</u></a></li>
</ul></div>
