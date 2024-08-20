---
title: "Resolved: Fixing the Perplexing 'Code 28' Issue on Your Windows Device Manager"
date: 2024-08-19T07:29:57.159Z
updated: 2024-08-20T07:29:57.159Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Fixing the Perplexing 'Code 28' Issue on Your Windows Device Manager"
excerpt: "This Article Describes Resolved: Fixing the Perplexing 'Code 28' Issue on Your Windows Device Manager"
thumbnail: https://thmb.techidaily.com/459b794516e41ca817af82c1c22066d193c455f4891dd7a8e040210befb5bf6c.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-twin-screens-archive-capture/"><u>[New] 2024 Approved  Twin Screens Archive Capture</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-storage-solutions-ps5s-top-10-external-units-for-2024/"><u>[New] Storage Solutions  PS5's Top 10 External Units for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-a-step-by-step-approach-to-snapchat-commerce-for-2024/"><u>[Updated] A Step-by-Step Approach to Snapchat Commerce for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-converting-in-meeting-google-meet-to-youtube-broadcasts-your-guide/"><u>[Updated] Converting In-Meeting Google Meet to YouTube Broadcasts  Your Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-strategic-electrical-power-choices-for-drones-success/"><u>[Updated] Strategic Electrical Power Choices for Drones' Success</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-vdx-quickcapture-evaluation-guide-comprehensive-review/"><u>[Updated] VDX QuickCapture Evaluation Guide  Comprehensive Review</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-toolwiz-visualize-a-comprehensive-2023-evaluation/"><u>2024 Approved  Toolwiz Visualize - A Comprehensive 2023 Evaluation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/audio-woes-in-win-10-over-now-smooth-operations/"><u>Audio Woes in WIN 10 Over, Now Smooth Operations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-step-by-step-tutorial-resolving-the-dark-display-issue-on-your-dell-notebook/"><u>Complete Step-by-Step Tutorial: Resolving the Dark Display Issue on Your Dell Notebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-to-overcome-error-code-0x802n-2400d-on-your-pcs-updates/"><u>Comprehensive Solutions to Overcome Error Code 0X802n-2400D on Your PC's Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-resolving-the-unresponsive-start-menu-in-windows-11-systems/"><u>Diagnosing & Resolving the Unresponsive Start Menu in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-connecting-a-microsoft-wireless-adapter-in-windows-10-systems/"><u>Easy Fixes for Connecting a Microsoft Wireless Adapter in Windows 10 Systems</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/efficient-tiktok-twitter-crossposting-guide/"><u>Efficient TikTok-Twitter Crossposting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-guide-troubleshooting-and-repairing-error-ebd-c0fe3897-b4f0-4aa5-a8e1-2dd5d3cbcefa-in-windows/"><u>Effortless Guide: Troubleshooting and Repairing Error Ebd-C0fe3897-B4f0-4aa5-A8e1-2dd5d3cbcefa in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-for-geforce-experience-cant-load-settings-issues/"><u>Fixes for 'GeForce Experience Can't Load Settings' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-fix-the-bluetooth-disappeared-error-on-windows-11-a-simple-guide/"><u>How to Correctly Fix the 'Bluetooth Disappeared' Error on Windows 11 – A Simple Guide</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-fix-continuous-freezing-issues-in-genshin-impact-on-your-pc/"><u>How to Fix Continuous Freezing Issues in Genshin Impact on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-game-freezes-in-popular-battle-royale-titles/"><u>How to Fix Game Freezes in Popular Battle Royale Titles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-conundrum-solved-reasons-behind-your-dysfunctional-razer-board/"><u>Keyboard Conundrum Solved: Reasons Behind Your Dysfunctional Razer Board</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overclocking-odds-on-your-side-again-fast-fixes/"><u>Overclocking Odds on Your Side Again - Fast Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-dota-navigating-through-error-2024-in-change-rendering-api-tips-and-tricks/"><u>Overcoming Dota Navigating Through Error 2024 in 'Change Rendering API' – Tips and Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-audio-glitches-with-speaker-pop-crackles-in-windows-operating-systems-solved/"><u>Resolve Audio Glitches with Speaker Pop-Crackles in Windows Operating Systems (Solved)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-hdcp-compatibility-issues-for-optimal-display-functionality/"><u>Resolving HDCP Compatibility Issues for Optimal Display Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-unreachable-website-error-in-google-chrome-step-by-step-solution/"><u>Resolving the Unreachable Website Error in Google Chrome - Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-volume-control-glitches-tips-and-tricks-for-windows-users/"><u>Resolving Volume Control Glitches: Tips and Tricks for Windows Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/step-by-step-guide-to-installing-streamlabs-in-obs-mac/"><u>Step-by-Step Guide to Installing Streamlabs in OBS (Mac)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-overcoming-black-screen-issues-on-your-dell-computer/"><u>Step-by-Step Guide: Overcoming Black Screen Issues on Your Dell Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-steelseries-x70-pen-failure-full-repair-instructions-and-tips/"><u>Step-by-Step Solution for SteelSeries X70 Pen Failure - Full Repair Instructions and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-restoring-msvcr110dll-on-your-pc/"><u>Step-by-Step Solutions for Restoring MSVCR110.dll on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-fix-is-in-how-to-reactivate-sound-in-acer-computers-silently-struggling/"><u>The Fix Is In: How to Reactivate Sound in Acer Computers Silently Struggling</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-fix-ensuring-wd-my-passport-ultra-is-compatible-and-visible-to-windows-systems/"><u>The Fix: Ensuring WD My Passport Ultra Is Compatible and Visible to Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubled-rollout-issues-with-the-latest-windows-10-version-1607-upgrade/"><u>Troubled Rollout: Issues with the Latest Windows 10 Version 1607 Upgrade</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-miracast-connectivity-problems-tips-to-fix-device-support-issues/"><u>Troubleshoot Miracast Connectivity Problems: Tips to Fix Device Support Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-bootmgr-is-missing-errors-with-easy-diagrams/"><u>Troubleshooting and Repairing 'BOOTMGR Is Missing' Errors with Easy Diagrams</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-non-functional-keyboard-illumination-on-macbook-and-desktop-computers/"><u>Troubleshooting Guide: Non-Functional Keyboard Illumination on MacBook and Desktop Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-windows-10-system-restore-fails/"><u>Troubleshooting Steps When Windows 10 System Restore Fails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooting-steps-resolving-the-dark-display-issue-on-your-dell-notebook/"><u>Ultimate Troubleshooting Steps: Resolving the Dark Display Issue on Your Dell Notebook</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/uncover-the-secret-to-sending-and-receiving-free-faxes-with-these-7-websites/"><u>Uncover the Secret to Sending and Receiving Free Faxes with These 7 Websites</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211229315-windows-10-couldnt-be-installed-error-code-80240020-solved/"><u>Windows 10 Couldn't Be Installed Error Code 80240020 [Solved]</u></a></li>
</ul></div>
