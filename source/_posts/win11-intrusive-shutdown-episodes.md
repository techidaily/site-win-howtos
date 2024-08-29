---
title: Win11 Intrusive Shutdown Episodes
date: 2024-08-28T00:36:23.799Z
updated: 2024-08-29T00:36:23.799Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Win11 Intrusive Shutdown Episodes
excerpt: This Article Describes Win11 Intrusive Shutdown Episodes
thumbnail: https://thmb.techidaily.com/286866a306a63ee3881a3e82bbbdfd6a5621a0735c9f349a630ef1e39c65837d.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://youtube-tips.techidaily.com/024-approved-convenient-viewing-setting-up-youtube-on-large-tv-panels/"><u>[New] 2024 Approved  Convenient Viewing  Setting Up YouTube on Large TV Panels</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-mastering-the-art-of-farewell-in-the-instagram-world/"><u>[New] 2024 Approved  Mastering the Art of Farewell in the Instagram World</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-expert-insights-into-iptv-stream-logging/"><u>[New] In 2024, Expert Insights Into IPTV Stream Logging</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-picture-posters-best-frame-enhancing-software-recommendations/"><u>[New] Picture Posters  Best Frame-Enhancing Software Recommendations</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-capturing-clarity-ranking-5-excellent-live-stream-devices/"><u>[Updated] 2024 Approved  Capturing Clarity  Ranking 5 Excellent Live Stream Devices</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-breaking-down-the-secrets-of-impactful-asmr-video-creation/"><u>[Updated] Breaking Down the Secrets of Impactful ASMR Video Creation</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-digital-mastery-top-10-instagram-enhancers/"><u>[Updated] In 2024, Digital Mastery  Top 10 Instagram Enhancers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-newfrontiersincameratech-for-2024/"><u>[Updated] NewFrontiersInCameraTech for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-essential-new-features-in-facebooks-repertoire/"><u>[Updated] The Essential New Features in Facebook's Repertoire</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-vivo-x-fold-2-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-ideal-tools-for-group-online-communication/"><u>2024 Approved  Ideal Tools for Group Online Communication</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-prime-film-unveiling-series/"><u>2024 Approved  Prime Film Unveiling Series</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ideal-beginning-enhancer-for-your-devices/"><u>2024 Approved  The Ideal Beginning Enhancer for Your Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/call-of-duty-world-war-ii-troubleshooting-guide-overcome-error-4220/"><u>Call of Duty World War II Troubleshooting Guide - Overcome Error 4220</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpts-role-in-developing-professional-presentations-techniques-unveiled/"><u>ChatGPT's Role in Developing Professional Presentations: Techniques Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-overcoming-the-0x80072efd-error-in-windows-10-environments/"><u>Comprehensive Fixes for Overcoming the 0X80072EFD Error in Windows 10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cracking-the-code-on-windows-update-failure-error-0x8024200d-a-comprehensive-solution-guide/"><u>Cracking the Code on Windows Update Failure (Error 0X8024200D): A Comprehensive Solution Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-combat-and-correct-valorants-persistent-screen-distortion-problem/"><u>Easy Steps to Combat and Correct Valorant's Persistent Screen Distortion Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-dx-feature-level-10-issue-on-your-wwe-gamehttpswwwexample-game-linkcom-2k-battl/"><u>Effective Fixes for DX Feature Level 10 Issue on Your WWE ([^Game](https://www.example-game-link.com)) 2K Battl</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-to-resolve-freezing-issues-with-windows-11-taskbar/"><u>Effective Strategies to Resolve Freezing Issues with Windows 11 Taskbar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-ways-to-resolve-lack-of-sound-device-in-windows-10-or-11/"><u>Effective Ways to Resolve Lack of Sound Device in Windows 10 or 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211881676-end-the-frustration-of-spontaneous-hibernation-on-your-computer-smart-fixes-inside/"><u>End the Frustration of Spontaneous Hibernation on Your Computer - Smart Fixes Inside</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhancing-employment-skills-with-these-6-chatgpt-uses/"><u>Enhancing Employment Skills with These 6 ChatGPT Uses</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-repairing-and-reviving-a-damaged-igfxem-unit/"><u>Expert Advice: Repairing and Reviving a Damaged IgfxEM Unit</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-techniques-for-repairing-a-broken-camera-on-your-lenovo-device/"><u>Expert Techniques for Repairing a Broken Camera on Your Lenovo Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-restoring-functionality-to-your-quick-capture-tool-with-the-windows-key-combo-on-new-versions-of-windows-os/"><u>Expert Tips: Restoring Functionality to Your Quick Capture Tool with the Windows Key Combo on New Versions of Windows OS</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/facebook-update-essential-strategies-for-social-media-savvy-for-2024/"><u>Facebook Update  Essential Strategies for Social Media Savvy for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fail-to-initialize-directx-easy-fix/"><u>Fail to Initialize DirectX - Easy Fix</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-dota-2-change-rendering-api-error-code-2024-in-minutes/"><u>Fix Your Dota 2 'Change Rendering API' Error Code 2024 in Minutes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-recurring-problems-with-unrecognized-external-devices-on-pc-expert-advice/"><u>Fixing Recurring Problems with Unrecognized External Devices on PC – Expert Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-invisible-mouse-pointer-problem-on-windows-11-systems/"><u>Fixing the Invisible Mouse Pointer Problem on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-total-war-rome-remastered-game-crashes-complete-solution/"><u>Fixing Total War: Rome Remastered Game Crashes – Complete Solution</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/from-airwaves-to-archives-online-recording-strategies-for-tv-shows/"><u>From Airwaves to Archives  Online Recording Strategies for TV Shows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-xiaomi-13t-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Xiaomi 13T Phones with/without a PC</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/horizontal-orientation-issue-on-portable-pc/"><u>Horizontal Orientation Issue on Portable PC</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-poco-x5-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Poco X5 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-elevated-cpu-load-caused-by-microsofts-sound-isolation-tech/"><u>How to Fix Elevated CPU Load Caused by Microsoft's Sound Isolation Tech</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-reactivate-windows-smartscreen-when-it-fails-to-load/"><u>How to Reactivate Windows SmartScreen When It Fails to Load</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-realme-11-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Realme 11 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-realme-v30-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Realme V30? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-capturing-online-seminars/"><u>In 2024, Capturing Online Seminars</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-from-iphone-13-mini-without-password-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account From iPhone 13 mini without Password?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Realme GT Neo 5? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-your-oppo-a1x-5gs-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Oppo A1x 5Gs Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-vivo-y17s-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Vivo Y17s? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-stability-how-to-fix-continuous-crashes-of-nier-automata-on-your-computer-system/"><u>Mastering Stability: How to Fix Continuous Crashes of Nier Automata on Your Computer System</u></a></li>
<li><a href="https://extra-support.techidaily.com/orbital-design-kit-for-2024/"><u>Orbital Design Kit for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/pixel-fold-2-sneak-peek-expected-price-tag-launch-date-and-features-what-to-know-now/"><u>Pixel Fold 2 Sneak Peek: Expected Price Tag, Launch Date & Features - What to Know Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-a-broken-screen-boosting-touch-responsiveness-on-windows-10-systems/"><u>Quick Fixes for a Broken Screen: Boosting Touch Responsiveness on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-start-solution-how-to-resolve-slow-lol-download-speed-bottlenecks/"><u>Quick-Start Solution: How to Resolve Slow LoL Download Speed Bottlenecks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-boot-issues-in-windows-10-common-causes-and-solutions/"><u>Resolving Boot Issues in Windows 10: Common Causes and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-lack-of-touchpen-responsiveness-on-displays/"><u>Resolving Lack of Touch/Pen Responsiveness on Displays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-dilemma-when-skype-microphone-fails-to-work/"><u>Resolving the Dilemma: When Skype Microphone Fails to Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-why-your-wd-my-passport-ultra-may-not-appear-on-windows/"><u>Resolving the Issue: Why Your WD My Passport Ultra May Not Appear on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-touchscreen-on-windows-11-top-5-methods/"><u>Reviving Your Touchscreen on Windows 11: Top 5 Methods</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/utionize-video-closings-exclusive-end-screen-templates/"><u>Revolutionize Video Closings - Exclusive End Screen Templates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-connectivity-issues-with-usb-ports-in-recent-windows-versions/"><u>Solving Connectivity Issues with USB Ports in Recent Windows Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-non-functional-scroll-wheel-issues-on-synaptics-trackpads-post-windows-11-update/"><u>Solving Non-Functional Scroll Wheel Issues on Synaptics Trackpads Post-Windows 11 Update</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Nokia 130 Music? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/spotify-masterclass-seamlessly-blending-multiple-playlists-together/"><u>Spotify Masterclass: Seamlessly Blending Multiple Playlists Together</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-nonfunctional-night-light-setting-in-modern-windows-pcs/"><u>Step-by-Step Fixes for Nonfunctional Night Light Setting in Modern Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-restoring-healthy-file-integrity-for-windows-11-systems/"><u>Step-by-Step Tutorial: Restoring Healthy File Integrity for Windows 11 Systems</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-samsung-galaxy-f04-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Samsung Galaxy F04 Phone Hassle-Free</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-solve-file-explorer-not-working-errors-for-windows-11-users/"><u>Troubleshoot and Solve File Explorer Not Working Errors for Windows 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-the-livekernelevent-144-issue/"><u>Troubleshooting and Resolving the 'LiveKernelEvent 144' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-vanishing-desktop-symbols-on-windows-11-devices/"><u>Troubleshooting Tips for Vanishing Desktop Symbols on Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unsticking-the-spacebar-in-windows-11-effective-solutions-for-a-smooth-typing-experience/"><u>Unsticking the Spacebar in Windows 11: Effective Solutions for a Smooth Typing Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-is-my-dell-wireless-keyboard-unresponsive-lets-resolve-it-together/"><u>Why Is My Dell Wireless Keyboard Unresponsive? Let's Resolve It Together</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-10-not-closing-complete-guide-for-successful-system-shutdown/"><u>Win 10 Not Closing? Complete Guide for Successful System Shutdown</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->