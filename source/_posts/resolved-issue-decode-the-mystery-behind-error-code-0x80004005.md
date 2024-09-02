---
title: "Resolved Issue: Decode the Mystery Behind Error Code 0X80004005"
date: 2024-09-01T04:54:00.969Z
updated: 2024-09-02T04:54:00.969Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved Issue: Decode the Mystery Behind Error Code 0X80004005"
excerpt: "This Article Describes Resolved Issue: Decode the Mystery Behind Error Code 0X80004005"
thumbnail: https://thmb.techidaily.com/be7eb26b929d376d352a2b6560c781f129b853a9868bdf923c96ee4b76c8aaef.jpg
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
<li><a href="https://digital-screen-recording.techidaily.com/new-diy-lol-gameplay-tapes-mastering-three-methods/"><u>[New] DIY LOL Gameplay Tapes  Mastering Three Methods</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-unveiling-the-wonders-of-phantoms-chrono-inversion-for-2024/"><u>[New] Unveiling the Wonders of Phantom’s Chrono Inversion for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-screen-flickering-in-windows-11/"><u>[Solved] Screen Flickering in Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-optimal-tools-for-educators-lesson-archiving/"><u>[Updated] 2024 Approved  Optimal Tools for Educator's Lesson Archiving</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-cut-to-the-chase-efficient-screen-recording-methods-for-hp-users/"><u>[Updated] Cut to the Chase  Efficient Screen Recording Methods for HP Users</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-essential-recording-gear-for-environmentalists/"><u>[Updated] In 2024, Essential Recording Gear for Environmentalists</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-ranked-alternatives-to-sporting-events-in-firstrow-views/"><u>2024 Approved  Ranked Alternatives to Sporting Events in Firstrow Views</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-infinix-hot-30i-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Infinix Hot 30i Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/apcs-desktop-titan-msi-raider-reviewed/"><u>APC's Desktop Titan: MSI Raider Reviewed</u></a></li>
<li><a href="https://facebook.techidaily.com/avoid-the-pitfalls-of-indiscriminate-online-networking/"><u>Avoid the Pitfalls of Indiscriminate Online Networking</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-ps4-connection-bottlenecks-your-ultimate-step-by-step-nat-type-solution-guide/"><u>Beat PS4 Connection Bottlenecks: Your Ultimate Step-by-Step NAT Type Solution Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/best-flash-video-player-apps-for-macos-top-picks-and-features-compared/"><u>Best Flash Video Player Apps for macOS: Top Picks & Features Compared</u></a></li>
<li><a href="https://win-howtos.techidaily.com/blizzard-outage-system-unavailable/"><u>Blizzard Outage: System Unavailable</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-blocked-pages-expert-tips-for-overcoming-http-403-barriers/"><u>Bypassing Blocked Pages: Expert Tips for Overcoming HTTP 403 Barriers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-delays-quick-fix-guide-for-slow-keyboards/"><u>Bypassing Delays: Quick Fix Guide for Slow Keyboards</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-honor-magic-5-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/computer-wont-exit-boot-screen-try-these-solutions/"><u>Computer Won't Exit Boot Screen? Try These Solutions!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/critical-insights-how-to-rectify-the-persistent-red-screen-problems-on-windows-pcs/"><u>Critical Insights: How To Rectify The Persistent Red Screen Problems On Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-stuck-windows-11-issues-expert-advice-on-keeping-your-system-responsive/"><u>Dealing with Stuck Windows 11 Issues: Expert Advice on Keeping Your System Responsive</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-the-troubling-error-0x8024401c-in-updating-your-windows-operating-system/"><u>Effective Fixes for the Troubling Error 0X8024401c in Updating Your Windows Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-when-the-shiftpluss-shortcut-doesnt-work-with-your-windows-keys-on-windows-11-and-10-systems/"><u>Effective Fixes for When the Shift+S Shortcut Doesn't Work with Your Windows Keys on Windows 11 and 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-laptops-that-dont-charge-when-plugged-in-on-windows-11-systems/"><u>Effective Solutions for Laptops That Don't Charge When Plugged in on Windows 11 Systems</u></a></li>
<li><a href="https://buynow-help.techidaily.com/elite-choices-for-home-and-business-cctv-solutions-expert-reviews-and-comparisons/"><u>Elite Choices for Home & Business CCTV Solutions - Expert Reviews and Comparisons</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-your-battle-royale-solutions-for-dealing-with-unsupported-gpus-in-fortnite-windows-edition/"><u>Enhance Your Battle Royale: Solutions for Dealing with Unsupported GPUs in Fortnite Windows Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/five-steps-to-diagnose-and-repair-recurring-mouse-disconnection-glitches/"><u>Five Steps to Diagnose and Repair Recurring Mouse Disconnection Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-bad-image-issue-in-windows-11-and-windows-10-systems/"><u>Fixing the 'Bad Image' Issue in Windows 11 and Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-simple-methods-to-correct-steam-cannot-write-to-disk/"><u>Guide: Simple Methods to Correct 'Steam Cannot Write to Disk'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-class-registration-problems-in-windows-10-with-proven-methods/"><u>How to Address Class Registration Problems in Windows 10 with Proven Methods</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-cities-skylines-crashing-issue-2024-tips/"><u>How to Fix Cities: Skylines Crashing Issue [2024 Tips]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-lenovo-mouse-pad-malfunctioning-across-windows-11-8-and-7-platforms-guide/"><u>How to Fix Lenovo Mouse Pad Malfunctioning Across Windows 11, 8, and 7 Platforms [GUIDE]</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Oppo Find X7? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-svchostexe-consuming-too-much-cpu-in-windows-10/"><u>How to Fix svchost.exe Consuming Too Much CPU in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-your-bluetooth-keyboard-when-it-wont-pair-with-your-computer/"><u>How to Fix Your Bluetooth Keyboard When It Won't Pair With Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-surface-tablet-wont-charge-solved/"><u>How to Fix: Surface Tablet Won't Charge – Solved!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-unresolved-fatal-error-bug-in-halo-4-ue4/"><u>How to Resolve the Unresolved 'Fatal Error' Bug in Halo 4 UE4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-a-safe-and-stable-connection-on-firefox-platform/"><u>How to Restore a Safe and Stable Connection on Firefox Platform</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-stop-your-football-manager-2022-from-crashing-on-windows/"><u>How to Stop Your Football Manager 2022 From Crashing on Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/innovative-mac-tool-for-screen-and-audio-capture-for-2024/"><u>Innovative Mac Tool for Screen & Audio Capture for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208340234-instant-fix-for-electronic-gadgets-when-they-cant-find-a-charge/"><u>Instant Fix for Electronic Gadgets - When They Can't Find a Charge</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/learn-the-solution-to-instagram-video-issues/"><u>Learn the Solution to Instagram Video Issues</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-discretion-in-digital-artistry/"><u>Mastering Discretion in Digital Artistry</u></a></li>
<li><a href="https://extra-hints.techidaily.com/moving-photos-and-videos-from-pc-to-iphone-effortlessly/"><u>Moving Photos & Videos From PC to iPhone Effortlessly</u></a></li>
<li><a href="https://hardware-help.techidaily.com/one-click-canon-pro-100-driver-download-and-install-for-windows-users/"><u>One-Click Canon PRO 100 Driver Download & Install for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-system-crashes-a-complete-guide-to-fixing-the-your-pc-did-not-shut-down-properly-problem/"><u>Overcoming System Crashes: A Complete Guide to Fixing the 'Your PC Did Not Shut Down Properly' Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-update-error-code-0x802e-expert-solutions-revealed/"><u>Overcoming Windows Update Error Code 0X802e: Expert Solutions Revealed</u></a></li>
<li><a href="https://review-topics.techidaily.com/poco-data-retrieval-tool-restore-lost-data-from-poco-by-fonelab-android-recover-data/"><u>Poco Data Retrieval tool – restore lost data from Poco</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205377777-quick-fixes-for-stuck-or-unresponsive-buttons-on-an-hp-laptop-solutions-at-hand/"><u>Quick Fixes for Stuck or Unresponsive Buttons on an HP Laptop – Solutions at Hand!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-microsoft-print-to-pdf-problems-for-windows-11-users/"><u>Resolving Microsoft Print to PDF Problems for Windows 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-sound-interruptions-in-your-logitech-g930-a-comprehensive-guide/"><u>Resolving Sound Interruptions in Your Logitech G930 - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-why-your-windows-11-wont-connect-with-cast-devices-and-what-to-do/"><u>Solved! Why Your Windows 11 Won't Connect with Cast Devices & What to Do</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-user-configuration-to-solve-driver-failed-errors/"><u>Step-by-Step Guide: Correcting User Configuration to Solve 'Driver Failed' Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tech-fix-windows-1011-malfunctioning-acer-inputs/"><u>Tech Fix: Windows 10/11, Malfunctioning Acer Inputs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-art-of-amassing-attention-on-ig-a-guide-for-a-thousand-likesmonth-for-2024/"><u>The Art of Amassing Attention on IG  A Guide for a Thousand Likes/Month for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-power-of-ai-in-personal-connections-enhancing-your-dating-experience-with-chatgpt/"><u>The Power of AI in Personal Connections: Enhancing Your Dating Experience with ChatGPT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-solution-to-enable-digital-ink-and-gesture-recognition-again/"><u>The Solution to Enable Digital Ink & Gesture Recognition Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-nvidia-shadowplay-setup-problems-effectively/"><u>Troubleshoot Your Nvidia ShadowPlay Setup Problems Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-an-issue-prevented-the-installation-of-features-or-an-update-on-your-windows-11-machine-solved/"><u>Troubleshooting 'An Issue Prevented the Installation of Features or an Update' On Your Windows 11 Machine [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-elevated-cpu-consumption-caused-by-msmpengexe-in-win-11-fixed/"><u>Troubleshooting Elevated CPU Consumption Caused by MsMpEng.exe in Win 11 [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-persistent-problems-with-windows-11-updates/"><u>Troubleshooting Persistent Problems with Windows 11 Updates</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-tips-for-iphones-hdr-images/"><u>Ultimate Tips for iPhone's HDR Images</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-3gp-video-editing-cutting-and-trimming-made-easy/"><u>Updated 2024 Approved 3GP Video Editing Cutting and Trimming Made Easy</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win11-intrusive-shutdown-episodes/"><u>Win11 Intrusive Shutdown Episodes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-users-heres-how-to-overcome-the-port-reset-failed-error-with-your-usb-device/"><u>Windows 10 Users, Here's How to Overcome the 'Port Reset Failed' Error with Your USB Device</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->