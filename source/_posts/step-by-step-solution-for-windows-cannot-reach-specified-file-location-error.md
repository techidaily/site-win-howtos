---
title: Step-by-Step Solution for 'Windows Cannot Reach Specified File Location Error'
date: 2024-08-28T00:23:41.705Z
updated: 2024-08-29T00:23:41.705Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for 'Windows Cannot Reach Specified File Location Error'
excerpt: This Article Describes Step-by-Step Solution for 'Windows Cannot Reach Specified File Location Error'
thumbnail: https://thmb.techidaily.com/2e98346ae0ee2e0559c5260d992a7113232d0df75bda10dff9dc91899db94103.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-brand-visualization-inserting-watermarks-and-logos-into-youtube-media/"><u>[New] 2024 Approved  Brand Visualization  Inserting Watermarks and Logos Into YouTube Media</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-make-big-bucks-fast-with-a-focus-on-youtube-short-video-creation/"><u>[New] 2024 Approved  Make Big Bucks Fast with a Focus on YouTube Short Video Creation</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-offline-viewing-of-full-hd-fb-content/"><u>[New] Offline Viewing of Full-HD FB Content</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-advanced-techniques-for-convincing-ppt-presentations-on-gmeet/"><u>[Updated] Advanced Techniques for Convincing PPT Presentations on GMeet</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-secrets-of-hosting-no-cost-seminars-on-the-worlds-largest-video-platform/"><u>[Updated] Secrets of Hosting No-Cost Seminars on the World’s Largest Video Platform</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-gifs-that-speak-volumes-unveiling-6-critical-strategies-for-memetic-design/"><u>2024 Approved  GIFs That Speak Volumes  Unveiling 6 Critical Strategies for Memetic Design</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unveiling-mixed-reality-a-comprehensive-insight/"><u>2024 Approved  Unveiling Mixed Reality  A Comprehensive Insight</u></a></li>
<li><a href="https://win-howtos.techidaily.com/check-for-windows-compatibility-issues/"><u>Check for Windows Compatibility Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-to-diagnose-and-fix-windows-error-code-0xc00000e9/"><u>Comprehensive Guide to Diagnose and Fix Windows Error Code 0Xc00000e9</u></a></li>
<li><a href="https://win-howtos.techidaily.com/crackle-free-audio-effective-solutions-for-clearing-up-sound-on-windows-11-and-7-computers/"><u>Crackle-Free Audio: Effective Solutions for Clearing Up Sound on Windows 11 and 7 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cured-discord-microphone-halt/"><u>Cured Discord Microphone Halt</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202666896-dells-guide-to-restoring-usb-port-functionality-solved/"><u>Dell's Guide to Restoring USB Port Functionality - Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-hp-laptop-usb-port-troubleshooting-step-by-step-repair-tips/"><u>DIY HP Laptop USB Port Troubleshooting: Step-by-Step Repair Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-a-non-functional-usb-on-an-hp-laptop-now-working/"><u>Easy Fixes for a Non-Functional USB on an HP Laptop - Now Working</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-tips-and-tricks-for-keeping-windows-10-current-with-new-updates/"><u>Easy Tips and Tricks for Keeping Windows 10 Current With New Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-resolving-the-livekernelevent-117-mistake/"><u>Effective Solutions for Resolving the LiveKernelEvent 117 Mistake</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-ways-to-resolve-incomplete-windows-setup-issues/"><u>Effortless Ways to Resolve Incomplete Windows Setup Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-and-tips-resolving-mic-issues-in-windows-10/"><u>Fixes & Tips: Resolving Mic Issues in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-keyboard-shortcuts-why-winplusshiftpluss-is-unresponsive-in-windows-11-and-10/"><u>Fixing Keyboard Shortcuts: Why Win+Shift+S Is Unresponsive in Windows 11 & 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-activating-touchscreen-capabilities-on-computers-with-disabled-stylus-access/"><u>Guide to Activating Touchscreen Capabilities on Computers with Disabled Stylus Access</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-livekernelevent-141-hardware-error-2024/"><u>How to Fix LiveKernelEvent 141 Hardware Error - 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-when-the-component-object-model-surrogate-stopped/"><u>How to Resolve When the 'Component Object Model Surrogate Stopped'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-brightness-functionality-in-windows-10-pcs/"><u>How To Restore Brightness Functionality in Windows 10 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206205090-how-to-restore-functionality-in-malfunctioning-arrow-keys-on-your-keyboard/"><u>How To Restore Functionality in Malfunctioning Arrow Keys on Your Keyboard!</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-vivo-y28-5g-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Vivo Y28 5G to New Phone | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-we-overcame-the-problem-of-contacting-a-non-responsive-dhcp-server/"><u>How We Overcame the Problem of Contacting a Non-Responsive DHCP Server</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-audiovisual-ascension-masterful-lighting-techniques-unveiled/"><u>In 2024, Audiovisual Ascension  Masterful Lighting Techniques Unveiled</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-screen-sharing-on-windows-11-via-zoom/"><u>In 2024, Mastering Screen Sharing on Windows 11 via Zoom</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/journey-to-unlicensed-beauty-open-source-portfolits/"><u>Journey to Unlicensed Beauty  Open-Source Portfolits</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lwjgl-exception-handling-correcting-non-accelerated-pixel-formats-efficiently/"><u>LWJGL Exception Handling: Correcting Non-Accelerated Pixel Formats Efficiently</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-indicators-of-a-premium-audio-tool-suitable-for-macos-environments/"><u>New Indicators of a Premium Audio Tool Suitable for macOS Environments</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-the-ultimate-choice-final-cut-pro-or-lumafusion-for-your-video-needs-for-2024/"><u>New The Ultimate Choice Final Cut Pro or LumaFusion for Your Video Needs for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-system-storage-a-guide-to-overcoming-insufficient-resources-for-command-execution/"><u>Optimizing System Storage: A Guide to Overcoming 'Insufficient Resources for Command Execution'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-bluetooth-glitches-how-to-get-your-airpods-working-again-on-windows-1n/"><u>Overcoming Bluetooth Glitches: How to Get Your AirPods Working Again on Windows 1N</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-deceptive-google-chrome-critical-error-phenomenon/"><u>Overcoming the Deceptive Google Chrome Critical Error Phenomenon</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-common-airdrop-problems-now-resolved/"><u>Quick Fixes for Common AirDrop Problems – Now Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-key-stickiness-on-new-windows-operating-systems-a-comprehensive-fix-guide/"><u>Resolving Key Stickiness on New Windows Operating Systems: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-access-denied-by-microsoft-exchange-for-your-email-client/"><u>Resolving the Issue: Access Denied by Microsoft Exchange for Your Email Client</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-problem-of-windows-7-update-download-failures/"><u>Resolving the Problem of Windows 7 Update Download Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-vanishing-mouse-pointer-in-windows-10-a-comprehensive-guide/"><u>Resolving the Vanishing Mouse Pointer in Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/smartphone-skills-producing-engaging-youtube-thumbnails-for-2024/"><u>Smartphone Skills  Producing Engaging YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-tips-for-non-working-dvds-in-windows-media-player/"><u>Solution Tips for Non-Working DVDs in Windows Media Player</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-no-sound-output-problems-in-windows-os/"><u>Step-by-Step Guide: Correcting 'No Sound Output' Problems in Windows OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-repair-tips-for-non-responsive-dell-wireless-keyboards/"><u>Step-by-Step Repair Tips for Non-Responsive Dell Wireless Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-implementation-of-the-latest-windows-11-update-kb4056892-guide/"><u>Successful Implementation of the Latest Windows 11 Update (KB4056892) [GUIDE]</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-ultimate-walkthrough-for-epson-wf-7620-driver-update-on-windows-operating-systems/"><u>The Ultimate Walkthrough for Epson WF-7620 Driver Update on Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-strategies-for-successfully-pairing-devices-via-bluetooth-on-windows-n-11/"><u>Top Strategies for Successfully Pairing Devices via Bluetooth on Windows N 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-step-by-step-fixing-the-registry-damage-causing-dvdcd-rom-not-working-on-windows-10/"><u>Troubleshooting Step-by-Step: Fixing the Registry Damage Causing DVD/CD-ROM Not Working on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-overcoming-windows-update-issue-error-0x8007001f-solution/"><u>Troubleshooting Steps for Overcoming Windows Update Issue - Error 0X8007001F Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-livekernelevent-117-mistake/"><u>Ultimate Guide: Resolving the LiveKernelEvent 117 Mistake</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-is-google-chrome-freezing-expert-tips-for-resolving-non-responsive-issues/"><u>Why Is Google Chrome Freezing? Expert Tips for Resolving Non-Responsive Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205764869-windows-11-typing-troubles-heres-how-you-can-eliminate-sticky-keys-and-improve-response-time/"><u>Windows 11 Typing Troubles? Here's How You Can Eliminate Sticky Keys and Improve Response Time</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->