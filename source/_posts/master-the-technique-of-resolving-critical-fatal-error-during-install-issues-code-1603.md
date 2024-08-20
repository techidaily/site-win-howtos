---
title: Master the Technique of Resolving Critical 'Fatal Error During Install' Issues (Code 1603)
date: 2024-08-19T06:46:29.400Z
updated: 2024-08-20T06:46:29.400Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Master the Technique of Resolving Critical 'Fatal Error During Install' Issues (Code 1603)
excerpt: This Article Describes Master the Technique of Resolving Critical 'Fatal Error During Install' Issues (Code 1603)
thumbnail: https://thmb.techidaily.com/5c8db21fb7e97eed2eddd025f3f66d3a9e58c7bc74fde8e765814f3eec97fd83.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-eyes-on-the-digital-winners-top-channels/"><u>[New] 2024 Approved  Eyes on the Digital Winners  Top Channels</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-how-to-record-the-screen-with-adobe-captive/"><u>[New] In 2024, How To Record The Screen With Adobe Captive</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-quickcapture-studio-chrome-os-snapper/"><u>[New] In 2024, QuickCapture Studio  Chrome OS Snapper</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-setting-up-an-online-presence-for-reviews-of-commercial-goods/"><u>[New] Setting Up an Online Presence for Reviews of Commercial Goods</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-yoga-enthusiasts-go-to-guide-on-youtube/"><u>[New] Yoga Enthusiasts' Go-To Guide on YouTube</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-how-to-use-zoom-webinars-beginners-guide/"><u>[Updated] In 2024, How to Use Zoom Webinars [Beginner’s Guide]</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-spotify-promotion-strategies-for-effective-ads/"><u>[Updated] Mastering Spotify Promotion  Strategies for Effective Ads</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-overlay-solutions-for-your-videos/"><u>Best Overlay Solutions for Your Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/confirmed-lack-of-opengl-from-drivers/"><u>Confirmed: Lack of OpenGL From Drivers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/effortless-enhancements-how-to-amplify-your-image-edits-on-pc-for-2024/"><u>Effortless Enhancements  How to Amplify Your Image Edits on PC for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-cutting-edge-computing-at-toms-hardware-store/"><u>Exploring Cutting-Edge Computing at Tom's Hardware Store</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-tracking-pc-boot-speed-expert-advice-and-strategies/"><u>Fast-Tracking PC Boot Speed: Expert Advice and Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-previously-restricted-now-fully-accessible-content-unveiled/"><u>Fixed! Previously Restricted, Now Fully Accessible Content Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-stuck-or-unresponsive-fn-keys-on-an-asus-computer-system/"><u>Fixing Stuck or Unresponsive Fn Keys on an ASUS Computer System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-wacom-device-driver-not-installed-problem-in-windows-11-environments/"><u>Fixing the 'Wacom Device Driver Not Installed' Problem in Windows 11 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-why-wont-my-pc-boot-up/"><u>Fixing the Issue: Why Won't My PC Boot Up?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-speakers-back-reactivating-disabled-audio-functionality-on-windows-7/"><u>Getting Your Speakers Back: Reactivating Disabled Audio Functionality on Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-xbox-one-audio-back-on-track-a-complete-guide/"><u>Getting Your Xbox One Audio Back on Track – A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-address-high-resource-usage-from-microsoft-telemetry-on-windows-11-devices/"><u>Guide to Address High Resource Usage From Microsoft Telemetry on Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-ensure-seamless-integration-of-airpods-with-windows-1011-essential-hacks/"><u>How to Ensure Seamless Integration of AirPods with Windows 10/11 - Essential Hacks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-dragon-ball-fighterz-when-it-cant-connect-to-the-network/"><u>How to Fix Dragon Ball FighterZ When It Can't Connect to the Network</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-show-wi-fi-password-on-infinix-hot-40i-by-drfone-android/"><u>How to Show Wi-Fi Password on Infinix Hot 40i</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-14-plus-passcode-screen-drfone-by-drfone-ios/"><u>How to Unlock iPhone 14 Plus Passcode Screen? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-quickened-keys-powerpoint-presentation-capture/"><u>In 2024, Quickened Keys  PowerPoint Presentation Capture</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-technology-choices-the-comprehensive-guide-from-toms-hardware/"><u>Mastering Technology Choices - The Comprehensive Guide From Tom's Hardware</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203444449-minecraft-multiplayer-lag-solve-your-lan-woes-here/"><u>Minecraft Multiplayer Lag? Solve Your LAN Woes Here</u></a></li>
<li><a href="https://win-howtos.techidaily.com/netflix-outage-guide-identifying-and-resolving-streaming-errors/"><u>Netflix Outage Guide – Identifying and Resolving Streaming Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-unavailable-desktop-error-on-windows-system-profile-directory/"><u>Overcoming the Unavailable Desktop Error on Windows System Profile Directory</u></a></li>
<li><a href="https://win-howtos.techidaily.com/playtime-puzzles-pc-crashes-in-gameplay/"><u>Playtime Puzzles: PC Crashes in Gameplay</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-start-troubleshooting-what-to-do-when-your-computer-stops-responding/"><u>Quick-Start Troubleshooting: What To Do When Your Computer Stops Responding</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211242910-resolve-your-windows-10-bluetooth-disappearance-problem-with-simple-steps/"><u>Resolve Your Windows 10 Bluetooth Disappearance Problem with Simple Steps!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-resource-protection-failed-errors-a-step-by-step-guide/"><u>Resolving 'Windows Resource Protection Failed' Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-graphic-glitches-a-solution-for-windows-11-and-10-images-issues/"><u>Resolving Graphic Glitches: A Solution for Windows 11 and 10 Images Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-pcs-built-in-webcam-problems-with-these-tips-for-windows-users/"><u>Solve Your PC's Built-In Webcam Problems with These Tips for Windows Users</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-complete-guide-to-twitters-paid-reach-and-impressions/"><u>The Complete Guide to Twitter's Paid Reach and Impressions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tips-and-tricks-for-fixing-the-unable-to-initialize-directx-component-issue/"><u>Tips and Tricks for Fixing the Unable to Initialize DirectX Component Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-update-fails-fixed/"><u>Windows Update Fails [FIXED]</u></a></li>
</ul></div>
