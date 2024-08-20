---
title: "Resolving Windows 11 Login Issues: Fixing User Profile Service Failures"
date: 2024-08-19T07:46:53.035Z
updated: 2024-08-20T07:46:53.035Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Windows 11 Login Issues: Fixing User Profile Service Failures"
excerpt: "This Article Describes Resolving Windows 11 Login Issues: Fixing User Profile Service Failures"
thumbnail: https://thmb.techidaily.com/4ea85f8fd0d9ab2c6c04d80e6aa73ebac967f8aac30c01b0db47479107c6b7f9.jpg
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
<li><a href="https://fox-boxes.techidaily.com/new-defining-techniques-for-e-narrative-construction/"><u>[New] Defining Techniques for E-Narrative Construction</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-prime-collection-of-effortless-phone-apps/"><u>[New] Prime Collection of Effortless Phone Apps</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-leading-movie-teasers-highlighted/"><u>[Updated] Leading Movie Teasers Highlighted</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-the-rise-of-facebooks-quick-vids-for-2024/"><u>[Updated] The Rise of Facebook's Quick Vids for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-samsung-galaxy-a24-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solution-for-the-windows-11-updating-problem-error-code-0xc1900208/"><u>Comprehensive Solution for the Windows 11 Updating Problem - Error Code 0xC1900208</u></a></li>
<li><a href="https://article-posts.techidaily.com/crafting-a-personalized-ringtone-from-tiktok-sounds-for-2024/"><u>Crafting a Personalized Ringtone From TikTok Sounds for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficiently-navigate-the-new-file-explorer-features-of-windows-11/"><u>Efficiently Navigate the New File Explorer Features of Windows 11</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/enhanced-connectivity-sending-social-media-content-between-facebook-and-whatsapp-for-2024/"><u>Enhanced Connectivity  Sending Social Media Content Between Facebook & WhatsApp for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0xc1900208-on-windows-11-updates-heres-how-you-can-fix-it/"><u>Error 0xC1900208 on Windows 11 Updates? Here’s How You Can Fix It</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ience-the-new-unleash-a-set-of-50-designs-for-free-in-2024/"><u>Experience the New  Unleash a Set of 50 Designs for Free, In 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-microsofts-wireless-display-adapter-connectivity-woes-on-windows-10-systems/"><u>Fixing Microsoft's Wireless Display Adapter Connectivity Woes on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-dota-2-error-2024-a-step-by-step-guide-on-changing-rendering-api/"><u>Fixing the Dota 2 Error 2024: A Step-by-Step Guide on Changing Rendering API</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-11-slideshow-and-customized-screen-saver-problems-expert-solutions/"><u>Fixing Windows 11 Slideshow & Customized Screen Saver Problems - Expert Solutions!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/halo-4-ue4-debugging-eradicating-the-catastrophic-bug-that-triggered-crashes/"><u>Halo 4 UE4 Debugging: Eradicating the Catastrophic Bug That Triggered Crashes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-oppo-a78-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Oppo A78? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-svchostexe-using-excessive-cpu-resources-in-windows-10/"><u>How to Fix svchost.exe Using Excessive CPU Resources in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-put-an-end-to-distracting-cursor-vibrations-solution-tips/"><u>How to Put an End to Distracting Cursor Vibrations - Solution Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-stop-your-nier-automata-game-from-crashing-on-windows/"><u>How to Stop Your Nier Automata Game From Crashing on Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-full-guide-to-iphone-11-pro-max-icloud-bypass-by-drfone-ios/"><u>In 2024, Full guide to iPhone 11 Pro Max iCloud Bypass</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-steps-to-avoid-automatic-podcast-suggestions-on-spotify/"><u>In 2024, Steps to Avoid Automatic Podcast Suggestions on Spotify</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723201208684-laptop-microphone-woes-find-out-how-to-get-it-working-again/"><u>Laptop Microphone Woes? Find Out How to Get It Working Again!</u></a></li>
<li><a href="https://buynow-info.techidaily.com/mac-loyalists-guide-to-freestyle2-blue-the-ultimate-customization-tool/"><u>Mac Loyalists' Guide to Freestyle2 Blue: The Ultimate Customization Tool</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-technique-of-resolving-critical-fatal-error-during-install-issues-code-1603/"><u>Master the Technique of Resolving Critical 'Fatal Error During Install' Issues (Code 1603)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/masterclass-troubleshooting-and-solving-graphic-card-problems-for-fortnite-windows-players/"><u>Masterclass: Troubleshooting and Solving Graphic Card Problems for Fortnite Windows Players</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207304266-no-more-stuttering-screens-just-gameplay/"><u>No More Stuttering Screens, Just Gameplay!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-the-stuck-at-windows-setup-problem-for-smooth-operating-system-install/"><u>Overcome the 'Stuck at Windows Setup' Problem for Smooth Operating System Install</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-tlsssl-verification-issues-with-your-secure-browsers-a-guide-for-quick-fixes/"><u>Overcoming TLS/SSL Verification Issues with Your Secure Browsers: A Guide for Quick Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-11-error-code-0x80072efd-effective-strategies-and-fixes/"><u>Overcoming Windows 11 Error Code 0X80072EFD: Effective Strategies and Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212279696-quick-fixes-for-your-non-functioning-mac-webcam-simple-solutions/"><u>Quick Fixes for Your Non-Functioning Mac Webcam – Simple Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207172659-resolve-the-bluetooth-not-found-error-on-windows-10-with-simple-fixes/"><u>Resolve the 'Bluetooth Not Found' Error on Windows 10 with Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-the-audio-malfunction-in-forza-horizon-4-a-step-by-step-guide/"><u>Resolved: Fixing the Audio Malfunction in Forza Horizon 4 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-update-issue-code-0x800f0922-solutions/"><u>Resolving Windows 11 Update Issue - Code 0X800F0922 Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11s-0x80072efd-issue-a-step-by-step-guide/"><u>Resolving Windows 11'S 0X80072EFD Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-how-to-fix-microsoft-store-not-responding-problem/"><u>Solution: How to Fix Microsoft Store Not Responding Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-microsoft-surface-pro-4-touch-lag-a-step-by-step-guide/"><u>Solving Microsoft Surface Pro 4 Touch Lag: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-errcachemiss-issue-a-step-by-step-guide-for-chrome-users/"><u>Solving the ERR_CACHE_MISS Issue: A Step-by-Step Guide for Chrome Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-nonresponsive-key-a-comprehensive-tutorial/"><u>Step-by-Step Fix for Nonresponsive @ Key – A Comprehensive Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fix-application-could-not-launch-correctly-with-error-0xc000007b-updated-solution/"><u>Step-by-Step Guide to Fix 'Application Could Not Launch Correctly' With Error (0XC000007B) - Updated Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-instructions-for-repairing-ethernet-connection-errors-on-pc-windows-10-and-7/"><u>Step-by-Step Instructions for Repairing Ethernet Connection Errors on PC (Windows 10 and 7)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-restoring-integrity-of-system-files-on-windows-11/"><u>Step-by-Step Tutorial: Restoring Integrity of System Files on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-restoring-light-on-your-corsair-keyboard/"><u>Troubleshooting Guide: Restoring Light on Your Corsair Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-stop-windows-10-from-automatic-reboot-on-close/"><u>Troubleshooting: Stop Windows 10 From Automatic Reboot on Close</u></a></li>
<li><a href="https://win-howtos.techidaily.com/uncover-solutions-to-the-icue-not-detecting-devices-problem/"><u>Uncover Solutions to the ICUE Not Detecting Devices Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-obtaining-trustedinstaller-permission-for-file-editing-on-your-pc/"><u>Understanding and Obtaining TrustedInstaller Permission for File Editing on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unraveling-the-mystery-behind-google-chrome-critical-error-solutions-at-hand/"><u>Unraveling The Mystery Behind Google Chrome Critical Error - Solutions at Hand!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/valorant-perpetual-boot-loop-heres-how-to-resolve-it/"><u>Valorant Perpetual Boot Loop? Here's How to Resolve It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205712471-windows-10-struggling-with-constant-airplane-mode-heres-your-solution/"><u>Windows 10 Struggling with Constant Airplane Mode? Here's Your Solution!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-invisible-bluetooth-connections-in-windows/"><u>Winning Against Invisible Bluetooth Connections in Windows #</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->