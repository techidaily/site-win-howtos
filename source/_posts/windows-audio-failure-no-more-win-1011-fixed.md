---
title: Windows Audio Failure No More - Win 10/11 Fixed
date: 2024-08-23T14:07:11.230Z
updated: 2024-08-24T14:07:11.230Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows Audio Failure No More - Win 10/11 Fixed
excerpt: This Article Describes Windows Audio Failure No More - Win 10/11 Fixed
thumbnail: https://thmb.techidaily.com/c64fedaf756cbcf9ac92722c1b2668052e1efc526bd85097cc0c097ddacbbc3a.jpg
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
<li><a href="https://win-howtos.techidaily.com/1723204135970-fix-immediately-reduce-high-cpu-usage-of-your-device-targeted-solutions-for-tackling-excessive-shell-induced-heat/"><u>[Fix] Immediately Reduce High CPU Usage of Your Device – Targeted Solutions for Tackling Excessive Shell-Induced Heat</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-capture-and-store-videos-effortlessly-with-our-top-list-for-2024/"><u>[New] Capture & Store Videos Effortlessly with Our Top List for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-from-game-day-to-hollywood-sports-video-success-story/"><u>[New] In 2024, From Game Day to Hollywood  Sports Video Success Story</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-gaming-to-goals-celebrating-the-top-10-ladies-on-youtube/"><u>[New] In 2024, From Gaming to Goals  Celebrating the Top 10 Ladies on YouTube</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/everaging-videos-with-text-a-cost-free-approach-for-2024/"><u>[New] Leveraging Videos with Text  A Cost-Free Approach for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-laptop-keyboard-not-working/"><u>[Solved] Laptop Keyboard Not Working</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-unlock-superior-mac-gif-capture-with-these-apps/"><u>[Updated] Unlock Superior Mac GIF Capture with These Apps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-masterclass-in-making-panzoids/"><u>2024 Approved  Masterclass in Making Panzoids</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-the-complete-hulu-recording-manual-for-pc-mac-and-mobile-users/"><u>2024 Approved  The Complete Hulu Recording Manual for PC, Mac & Mobile Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/breaking-through-the-blockage-a-guide-to-resolving-destiny-2s-start-up-stuck-point/"><u>Breaking Through the Blockage: A Guide to Resolving Destiny 2'S Start-Up Stuck Point</u></a></li>
<li><a href="https://win-howtos.techidaily.com/breeze-through-fixing-windows-update-problems-solution-for-error-code-0x80073cfb/"><u>Breeze Through Fixing Windows Update Problems - Solution for Error Code 0X80073CFB</u></a></li>
<li><a href="https://techtrends.techidaily.com/connecting-fubotv-to-your-firestick-a-complete-tutorial/"><u>Connecting FuboTV to Your Firestick: A Complete Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-the-unresponsive-spacekey-problem-on-windows-11/"><u>Diagnosing and Fixing the Unresponsive Spacekey Problem on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/disrupting-high-cpu-usage-in-windows-11/"><u>Disrupting High CPU Usage in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-solutions-for-fixing-your-software-after-an-unexpected-shutdown/"><u>Easy Solutions for Fixing Your Software After an Unexpected Shutdown</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enabling-local-security-reactivate-lsa-protection-now/"><u>Enabling Local Security: Reactivate LSA Protection Now</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-ps5-with-best-in-class-addons/"><u>Enhancing PS5 with Best-in-Class Addons</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-for-endless-load-time-in-valorant-get-back-into-battle/"><u>Fixes for Endless Load Time in Valorant - Get Back Into Battle</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-android-phone-not-powering-up-despite-being-connected-to-charger/"><u>Fixing Android Phone Not Powering Up Despite Being Connected to Charger</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-common-issues-wacom-pen-malfunction-on-windows-11-and-10/"><u>Fixing Common Issues: Wacom Pen Malfunction on Windows 11 & 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-unresponsive-sound-feature-in-windows-7-a-step-by-step-guide/"><u>Fixing the Unresponsive Sound Feature in Windows 7: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-repair-a-troublesome-device-manager-code-28-glitch-in-windows-systems/"><u>How to Correctly Repair a Troublesome 'Device Manager Code #28' Glitch in Windows Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-idt-hd-audio-codec-driver-issues-under-windows-11/"><u>How To Fix IDT HD Audio Codec Driver Issues Under Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-geforce-settings-retrieval-error-on-your-pc/"><u>How to Overcome GeForce Settings Retrieval Error on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-unresponsive-buttons-in-windows-11-laptop-and-desktop-keyboards/"><u>How to Repair Unresponsive Buttons in Windows 11 Laptop and Desktop Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-the-energy-icon-for-efficient-power-management-in-windows-11/"><u>How to Restore the Energy Icon for Efficient Power Management in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-vanished-desktop-shortcuts-in-windows-10-a-step-by-step-guide/"><u>How to Restore Vanished Desktop Shortcuts in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-solve-charging-issues-on-your-pc-with-windows-os-version-7-and-10/"><u>How to Solve Charging Issues on Your PC with Windows OS (Version 7 and 10)</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-iphone-12-pro-max-device-from-icloud-by-drfone-ios/"><u>In 2024, How to Remove iPhone 12 Pro Max Device from iCloud</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-from-iphone-15-pro-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password From iPhone 15 Pro</u></a></li>
<li><a href="https://extra-information.techidaily.com/innovation-in-display-tech-top-10-of-4k-displays/"><u>Innovation in Display Tech  #Top 10 of 4K Displays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/kidneys/"><u>Kidneys</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-edit-m4a-files-for-free-top-5-software-recommendations-for-2024/"><u>New Edit M4A Files for Free Top 5 Software Recommendations for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-omegle-explained-navigating-free-chat-engagements-with-a-lens-on-security-concerns-for-2024/"><u>New Omegle Explained Navigating Free Chat Engagements with a Lens on Security Concerns for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-initial-dark-screen-error-in-monster-hunter-world-gameplay/"><u>Overcoming the Initial Dark Screen Error in Monster Hunter: World Gameplay</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-with-your-microsoft-stores-local-cache-on-windows/"><u>Resolving Issues with Your Microsoft Store's Local Cache on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-opencldll-file-disparities/"><u>Resolving OpenCL.dll File Disparities</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-overcoming-common-software-stoppages-effectively/"><u>Solution Found: Overcoming Common Software Stoppages Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-common-opengl-issues-in-minecraft-a-step-by-step-guide/"><u>Solving Common OpenGL Issues in Minecraft: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-excessive-cpu-consumption-by-msmpengine-in-windows-10-systems/"><u>Solving the Issue: Excessive CPU Consumption by MsMpEngine in Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-widevine-cdm-is-absent-from-your-windows-system/"><u>Troubleshooting Steps When Widevine CDM Is Absent From Your Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-correcting-the-windows-cannot-install-service-packs-problem-in-windows-10-error-0x800705b4/"><u>Troubleshooting Tips: Correcting the 'Windows Cannot Install Service Packs' Problem in Windows 10 (Error 0X800705b4)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-overcoming-the-0xc0000005-kernel-termination-blue-screen-of-death-on-windows-computers/"><u>Troubleshooting Tips: Overcoming the '0xC0000005' Kernel Termination Blue Screen of Death on Windows Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-win32-app-crash-error-code-0xc0000005-on-your-pc/"><u>Ultimate Guide: Resolving the Win32 App Crash (Error Code 0xC0000005) on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-solution-eliminating-obs-game-capture-black-screen-glitch/"><u>Ultimate Solution: Eliminating OBS Game Capture Black Screen Glitch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-solutions-for-the-persistent-0x80072efd-error-in-your-windows-10-system/"><u>Ultimate Solutions for the Persistent 0X80072EFD Error in Your Windows 10 System</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/upgrade-to-an-rtx-4090-gaming-beast-exclusive-offer-on-alienwares-m18-r2-laptop-slash-700-from-the-price/"><u>Upgrade to an RTX 4090 Gaming Beast – Exclusive Offer on Alienware's M18 R2 Laptop, Slash $700 From the Price</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-startup-issues-how-to-get-your-start-menu-working-again/"><u>Windows 11 Startup Issues: How to Get Your Start Menu Working Again</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->