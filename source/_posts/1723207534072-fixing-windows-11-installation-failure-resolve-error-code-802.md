---
title: "Fixing Windows 11 Installation Failure: Resolve Error Code 802#"
date: 2024-08-19T07:51:23.018Z
updated: 2024-08-20T07:51:23.018Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing Windows 11 Installation Failure: Resolve Error Code 802#"
excerpt: "This Article Describes Fixing Windows 11 Installation Failure: Resolve Error Code 802#"
thumbnail: https://thmb.techidaily.com/66380fee6148181c7fbef919ab70be5b7f03dcd6ba9d00048b2c822f6ae741fb.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

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
<li><a href="https://extra-tips.techidaily.com/new-choosing-prime-top-8-budget-friendly-srt-translator-tools/"><u>[New] Choosing Prime  Top 8 Budget-Friendly SRT Translator Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-crafting-youtube-video-trailers-with-filmoras-guide/"><u>[New] In 2024, Crafting YouTube Video Trailers with Filmora's Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-raw-footage-to-highlight-hits/"><u>[New] In 2024, From Raw Footage to Highlight Hits</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-restoring-clear-vision-fixing-iphone-lens-out-of-focus/"><u>[New] In 2024, Restoring Clear Vision  Fixing iPhone Lens Out-of-Focus</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-ultimate-guide-to-professional-grade-mobile-screencasting-with-mobizen-for-2024/"><u>[New] Ultimate Guide to Professional-Grade Mobile Screencasting with Mobizen for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-bridging-platforms-loop-ready-setups-for-youtube-and-tv-for-2024/"><u>[Updated] Bridging Platforms  Loop-Ready Setups for YouTube and TV for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-live-streaming-made-simple-mastering-ps4-captures-using-obs/"><u>[Updated] In 2024, Live Streaming Made Simple  Mastering PS4 Captures Using OBS</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-ultimate-visual-preservation-tool-chromebook/"><u>[Updated] In 2024, Ultimate Visual Preservation Tool  Chromebook</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-inside-secrets-to-stunning-photography-with-canva/"><u>[Updated] Inside Secrets to Stunning Photography with Canva</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-perfectpicturefree-ultimate-erase-for-clean-bgs/"><u>[Updated] PerfectPictureFree  Ultimate Erase for Clean BGs</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-striding-forward-a-comprehensive-review-of-vr-walkers/"><u>[Updated] Striding Forward  A Comprehensive Review of VR Walkers</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-ultimate-list-of-16-key-youtube-videos-for-higher-engagement/"><u>[Updated] Ultimate List of 16 Key YouTube Videos for Higher Engagement</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-enhance-privacy-and-speed-the-best-7-android-adblocks/"><u>2024 Approved  Enhance Privacy & Speed  The Best 7 Android AdBlocks</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-premium-top-ten-nintendo-switch-fighter-games-max-156/"><u>2024 Approved  Premium Top Ten Nintendo Switch Fighter Games (Max 156)</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-skyward-file-fortresses-identifying-top-cloud-titans/"><u>2024 Approved  Skyward File Fortresses  Identifying Top Cloud Titans</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-troubleshooting-why-are-your-shorts-thumbnails-hiding/"><u>2024 Approved  Troubleshooting  Why Are Your Shorts' Thumbnails Hiding?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/8-safe-and-effective-methods-to-unlock-your-iphone-6-without-a-passcode-drfone-by-drfone-ios/"><u>8 Safe and Effective Methods to Unlock Your iPhone 6 Without a Passcode | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/advanced-tips-for-3d-color-grading/"><u>Advanced Tips for 3D Color Grading</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avoiding-game-crashes-solving-severe-bugs-in-call-of-duty-black-ops-iv/"><u>Avoiding Game Crashes: Solving Severe Bugs in Call of Duty: Black Ops IV</u></a></li>
<li><a href="https://extra-tips.techidaily.com/beyond-samsung-gear-360-top-alternative-cameras-of-2023-for-2024/"><u>Beyond Samsung Gear 360  Top Alternative Cameras of 2023 for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-motorola-edge-40-pro-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Motorola Edge 40 Pro?</u></a></li>
<li><a href="https://fox-http.techidaily.com/capture-the-essence-in-cloud-mix-free-space-plus-charged-backup-sanctuaries/"><u>Capture the Essence in Cloud  Mix Free Space + Charged Backup Sanctuaries</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-repair-instructions-the-stop-working-issue-with-32-bit-print-management-hosts-resolved/"><u>Comprehensive Repair Instructions: The Stop Working Issue with 32-Bit Print Management Hosts Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-tutorial-diagnosing-and-repairing-windows-driver-power-failures/"><u>Comprehensive Tutorial: Diagnosing and Repairing Windows Driver Power Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-dealing-with-freezing-issues-on-your-laptop-mouse/"><u>Effective Solutions for Dealing with Freezing Issues on Your Laptop Mouse</u></a></li>
<li><a href="https://win-solutions.techidaily.com/effective-techniques-to-correct-directx-issues-in-battlefield-2042/"><u>Effective Techniques to Correct DirectX Issues in Battlefield 2042</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/te-reach-optimal-strategies-for-crafting-youtube-titles-and-tags-for-2024/"><u>Elevate Reach  Optimal Strategies for Crafting YouTube Titles & Tags for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhanced-efficiency-in-wdf-addressing-previous-cpu-overload-concerns/"><u>Enhanced Efficiency in WDF: Addressing Previous CPU Overload Concerns</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhancement-alert-new-gpu-prerequisite-d3d11-compatibility-required-by-game-software/"><u>Enhancement Alert: New GPU Prerequisite - D3D11 Compatibility Required by Game Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-overcoming-the-update-failed-error-code-0x800f0922-on-windows-10/"><u>Expert Tips for Overcoming the 'Update Failed' Error (Code 0X800f0922) on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208637048-fixing-the-issue-how-to-resolve-windows-update-error-code-0x8007001f/"><u>Fixing the Issue: How to Resolve Windows Update Error Code 0X8007001f</u></a></li>
<li><a href="https://screen-recording.techidaily.com/from-casual-gamer-to-pro-elevating-your-minecraft-recordings-with-a-mac-for-2024/"><u>From Casual Gamer to Pro  Elevating Your Minecraft Recordings with a Mac for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/geforce-experience-wont-open-comprehensive-solutions-and-fixes/"><u>GeForce Experience Won't Open - Comprehensive Solutions and Fixes</u></a></li>
<li><a href="https://program-issues.techidaily.com/haley-ba-et-al-nd-glyphosate-occurrence-and-potential-impacts-on-surface-water-ecosystems-a-review-retrieved-from-httpswwwusgsgovspecial-topicwater-science-570/"><u>Haley BA., Et Al (N.d.). Glyphosate Occurrence and Potential Impacts on Surface Water Ecosystems: A Review. Retrieved From https://www.usgs.gov/special-topic/water-science-school/science/glyphosate-occurrence-and-potential-impacts-surface</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-loadlibrary-error-code-1114-in-your-system-efficiently/"><u>How to Fix 'LoadLibrary' Error Code 1114 in Your System Efficiently</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-oppo-find-n3-flip-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Oppo Find N3 Flip Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-lenovos-malfunctioning-special-function-keys-a-step-by-step-guide/"><u>How to Repair Lenovo's Malfunctioning Special Function Keys: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-copy-and-paste-features-in-your-windows-11-operating-system/"><u>How to Restore Copy and Paste Features in Your Windows 11 Operating System</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-vivo-s18-pro-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Vivo S18 Pro to iPod | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-music-management-for-social-media-iphone-and-android-basics/"><u>In 2024, Music Management for Social Media  IPhone & Android Basics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/is-netflix-not-working-properly-uncover-the-causes-and-quick-fixes/"><u>Is Netflix Not Working Properly? Uncover the Causes and Quick Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211140305-master-the-trick-to-keep-your-cs-go-game-running-smoothly/"><u>Master the Trick to Keep Your CS GO Game Running Smoothly!</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719579198473-mondly-and-apple-championed-as-ed-tech-elite-10-list-feat/"><u>Mondly & Apple Championed as Ed-Tech Elite: #10 List Feat</u></a></li>
<li><a href="https://win-howtos.techidaily.com/monster-hunter-world-troubleshooting-guide-tackling-the-ominous-black-screen-on-boot/"><u>Monster Hunter: World Troubleshooting Guide – Tackling the Ominous Black Screen on Boot</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-amd-video-driver-found-in-windows-systems/"><u>No AMD Video Driver Found in Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-frustrations-seamlessly-connect-with-your-microsoft-projector-on-windows-10/"><u>No More Frustrations: Seamlessly Connect with Your Microsoft Projector on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-typing-troubles-overcoming-windows-11s-input-lag-issues/"><u>No More Typing Troubles: Overcoming Windows 11'S Input Lag Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-performance-addressing-ntoskrnlexe-load/"><u>Optimizing Performance: Addressing ntoskrnl.exe Load</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/oming-obscured-views-during-youtube-playback/"><u>Overcoming Obscured Views During YouTube Playback</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-writers-block-in-computer-memory-dealing-with-a-referenced-location-at-0x-0x/"><u>Overcoming Writer's Block in Computer Memory: Dealing with a Referenced Location at 0X (0X)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207863980-pdf-printing-problems-quick-fixes-to-get-your-document-out/"><u>PDF Printing Problems? Quick Fixes to Get Your Document Out</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repairing-damaged-system-files-in-windows-10-and-11-step-by-step-guide/"><u>Repairing Damaged System Files in Windows 10 & 11 – Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolution-steps-enable-detection-of-unrecognized-wd-my-passport-ultra-external-hard-drive/"><u>Resolution Steps: Enable Detection of Unrecognized 'WD My Passport Ultra' External Hard Drive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-update-error-code-0x802eb3f6-a-step-by-step-guide/"><u>Resolving Windows 11 Update Error Code 0X802eb3f6: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-the-usb-port-how-to-restore-functionality-in-your-hp-notebook/"><u>Reviving the USB Port: How to Restore Functionality in Your HP Notebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-astro-a40-mic-step-by-step-troubleshooting-guide/"><u>Reviving Your Astro A40 Mic: Step-by-Step Troubleshooting Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/simplify-your-digital-life-5-essential-recording-strategies-web/"><u>Simplify Your Digital Life  5 Essential Recording Strategies Web</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-tips-for-fixing-media-connection-errors-on-your-windows-computer/"><u>Solution Tips for Fixing Media Connection Errors on Your Windows Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-typing-issues-fix-broken-letter-functions-on-win-1011-computers/"><u>Solving Typing Issues: Fix Broken Letter Functions on Win 10/11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-common-dll-has-stopped-working-in-windows-bid-error-goodbye/"><u>Step-by-Step Fix for 'Common DLL Has Stopped Working' In Windows: Bid Error Goodbye</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-obtain-trustee-access-from-trustedinstaller-for-file-modification/"><u>Steps to Obtain Trustee Access From TrustedInstaller for File Modification</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-fix-tips-for-overcoming-the-absence-of-hardware-drivers-in-windows-7-setup/"><u>Successful Fix Tips for Overcoming the Absence of Hardware Drivers in Windows 7 Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-overcoming-the-kb4056892-hurdle-windows-10-update-installation-tips/"><u>Successfully Overcoming the KB4056892 Hurdle - Windows 10 Update Installation Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-the-infamous-red-screen-problem-a-complete-fix-guide/"><u>Tackling the Infamous 'Red Screen' Problem: A Complete Fix Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-samsung-galaxy-z-flip-7-unveiled-anticipated-launch-date-and-pricing-details-revealed/"><u>The Samsung Galaxy Z Flip 7 Unveiled: Anticipated Launch Date & Pricing Details Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-microsoft-wireless-display-drivers-in-windows-n11-solutions-and-tips/"><u>Troubleshooting Microsoft Wireless Display Drivers in Windows N11 – Solutions and Tips</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-redmi-a2plus-by-fonelab-android-recover-music/"><u>Undelete lost music from Redmi A2+</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-epson-scan-communication-issues/"><u>Unlocking Epson Scan Communication Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/vcruntime140dll-not-found-heres-how-you-can-resolve-it/"><u>VCRUNTIME140.dll Not Found? Here's How You Can Resolve It!</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Xiaomi Mix Fold 3? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203298632-windows-11-installer-halted-by-code-80240020-heres-the-comprehensive-fix/"><u>Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-windows-10s-persistent-0x800705b4-update-issue-a-step-by-step-fix/"><u>Winning the Battle Against Windows 10'S Persistent 0X800705b4 Update Issue – A Step-by-Step Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211838378-your-sds-silence-uncover-solutions/"><u>Your SD's Silence? Uncover Solutions!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->