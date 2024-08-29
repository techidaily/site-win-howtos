---
title: "How to Correct 'Bad Image' Errors for Windows 11 Users: A Comprehensive Fix"
date: 2024-08-28T00:28:50.479Z
updated: 2024-08-29T00:28:50.479Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Correct 'Bad Image' Errors for Windows 11 Users: A Comprehensive Fix"
excerpt: "This Article Describes How to Correct 'Bad Image' Errors for Windows 11 Users: A Comprehensive Fix"
thumbnail: https://thmb.techidaily.com/38a10dded96ded9495ccb2173f240c20a69acb6b4b947c6dc175d30ce0f723b9.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-accelerating-windows-document-analysis/"><u>[New] 2024 Approved  Accelerating Windows Document Analysis</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-ultimate-picks-for-top-rated-free-srt-translation-tools/"><u>[New] Ultimate Picks for Top-Rated Free SRT Translation Tools</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-empowering-your-business-communication-google-meet-to-youtube-steps/"><u>[Updated] Empowering Your Business Communication  Google Meet to YouTube Steps</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-high-definition-dominance-leading-monitors-for-ps5-hdmi-21/"><u>[Updated] High-Definition Dominance  Leading Monitors for PS5 (HDMI 2.1)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-bring-back-the-buzz-transforming-previous-media-with-ig-filters/"><u>[Updated] In 2024, Bring Back the Buzz  Transforming Previous Media with IG Filters</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-master-live-broadcast-a-step-by-step-guide-to-recording-webcam-via-vlc-for-2024/"><u>[Updated] Master Live Broadcast  A Step-by-Step Guide to Recording Webcam via VLC for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unveiling-yourself-instagram-live-basics-for-2024/"><u>[Updated] Unveiling Yourself  Instagram Live Basics for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-unleashing-revenue-with-review-videos-of-household-items/"><u>2024 Approved  Unleashing Revenue with Review Videos of Household Items</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-honor-x8b-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Honor X8b | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/applecareplus-value-check-is-the-extra-protection-justified/"><u>AppleCare+ Value Check: Is the Extra Protection Justified?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/but-investors-are-still-buying-stocks-because-they-expect-strong-corporate-profits-and-rising-economic-growth-over-the-next-six-months-to-drive-further-gain149/"><u>But Investors Are Still Buying Stocks because They Expect Strong Corporate Profits and Rising Economic Growth over the Next Six Months to Drive Further Gains</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-deceptive-alerts-solve-google-chromes-fraudulent-critical-error-problem/"><u>Bypassing Deceptive Alerts: Solve Google Chrome's Fraudulent Critical Error Problem</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-sequential-visual-narratives-with-photos/"><u>Crafting Sequential Visual Narratives with Photos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-unexpected-outages-how-to-fix-your-erratic-internet-connection/"><u>Dealing With Unexpected Outages: How to Fix Your Erratic Internet Connection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-resolve-continuous-system-freezing-on-your-laptop-or-desktop/"><u>Easy Steps to Resolve Continuous System Freezing on Your Laptop or Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-solution-reviving-non-functioning-keys-on-your-hp-device/"><u>Effortless Solution: Reviving Non-Functioning Keys on Your HP Device</u></a></li>
<li><a href="https://win-amazing.techidaily.com/epson-l3150-printer-software-download-and-update-for-windows-11-8-and-7/"><u>Epson L3150 Printer Software Download & Update for Windows 11, 8 & 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-restoring-access-to-a-non-responsive-dhcp-server/"><u>Expert Advice: Restoring Access to a Non-Responsive DHCP Server</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-cache-miss-errors-quickly-in-google-chrome-for-a-smooth-web-experience/"><u>Fixing 'Cache Miss' Errors Quickly in Google Chrome for a Smooth Web Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-a-step-by-step-guide-to-resolving-google-chromes-critical-error-scam/"><u>Fixing the Issue: A Step-by-Step Guide to Resolving Google Chrome's 'Critical Error Scam'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-audio-hardware-detection-failures-on-windows-11-computers/"><u>How to Fix Audio Hardware Detection Failures on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-failed-to-create-d3d-device-error-on-windows-solution-guide/"><u>How to Fix the Failed to Create D3D Device Error on Windows – Solution Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-when-apple-account-locked-from-apple-iphone-8-plus-by-drfone-ios/"><u>How to Fix when Apple Account Locked From Apple iPhone 8 Plus?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-when-your-macs-trackpad-wont-respond/"><u>How to Repair When Your Mac's Trackpad Won't Respond</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-tackle-overuse-of-hard-drive-storage-by-microsofts-telemetry-feature-in-windows-11/"><u>How to Tackle Overuse of Hard Drive Storage by Microsoft's Telemetry Feature in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-update-your-drivers-in-windows-10-by-drivereasy-guide/"><u>How to use Device Manager to update your drivers in Windows 10</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-best-music-live-streaming-services/"><u>In 2024, Best Music Live Streaming Services</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-ispoofer-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/minecraft-error-code-5-explained-quick-fixes-for-a-smooth-gaming-experience/"><u>Minecraft Error Code 5 Explained – Quick Fixes for a Smooth Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/obs-game-capturing-woes-fix-that-perplexing-black-screen-issue-today/"><u>OBS Game Capturing Woes? Fix That Perplexing Black Screen Issue Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-surface-keyboard-quirk/"><u>Resolved Surface Keyboard Quirk</u></a></li>
<li><a href="https://fox-blue.techidaily.com/showcasing-design-brilliance-best-10-text-setups-in-ae/"><u>Showcasing Design Brilliance  Best 10 Text Setups in AE</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-resolving-windows-11s-unresponsive-volume-adjustment/"><u>Step-by-Step Guide to Resolving Windows 11'S Unresponsive Volume Adjustment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-strategies-to-revive-and-restart-an-unresponsive-pc/"><u>Step-by-Step Strategies to Revive and Restart an Unresponsive PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-usb-tethering-mastery-for-windows-10-users/"><u>Step-by-Step USB Tethering Mastery for Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-roadblock-ahead-teredo-fails-to-secure-spot-on-competitive-list/"><u>The Roadblock Ahead: Teredo Fails to Secure Spot on Competitive List</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-overcoming-deadly-glitches-in-black-ops-4/"><u>Troubleshooting Tips: Overcoming Deadly Glitches in Black Ops 4</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-windows-live-movie-maker-tutorial-splitting-videos-made-easy-for-2024/"><u>Updated Windows Live Movie Maker Tutorial Splitting Videos Made Easy for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->