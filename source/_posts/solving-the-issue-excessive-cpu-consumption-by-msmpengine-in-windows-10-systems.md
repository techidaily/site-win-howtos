---
title: "Solving the Issue: Excessive CPU Consumption by MsMpEngine in Windows 10 Systems"
date: 2024-08-19T07:55:38.359Z
updated: 2024-08-20T07:55:38.359Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solving the Issue: Excessive CPU Consumption by MsMpEngine in Windows 10 Systems"
excerpt: "This Article Describes Solving the Issue: Excessive CPU Consumption by MsMpEngine in Windows 10 Systems"
thumbnail: https://thmb.techidaily.com/be42a9800526c31b5bfdef3ed18cce59bd7b3192524b647f6f87b51df7e044d8.png
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
<li><a href="https://youtube-sure.techidaily.com/-step-financial-forecasting-assessing-revenue-from-googles-platform-youtube/"><u>[New] 3-Step Financial Forecasting  Assessing Revenue From Google's Platform, YouTube</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-mastering-voice-over-recording-for-videos-for-2024/"><u>[New] Mastering Voice-Over Recording for Videos for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-perfecting-cinematography-for-reddit-amas-for-2024/"><u>[New] Perfecting Cinematography for Reddit AMAs for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-sims-4-recording-techniques-for-gamers-for-2024/"><u>[New] Sims 4  Recording Techniques for Gamers for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-sourcing-free-frame-videos-without-a-dollar-drop/"><u>[New] Sourcing Free Frame Videos Without a Dollar Drop</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-editors-arsenal-advanced-techniques-in-chromatic-tuning/"><u>[New] The Editor's Arsenal  Advanced Techniques in Chromatic Tuning</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-behind-the-scenes-of-effective-instagram-caption-use/"><u>[Updated] 2024 Approved  Behind the Scenes of Effective Instagram Caption Use</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-significant-aspects-in-techno-narrative-design/"><u>[Updated] 2024 Approved  Significant Aspects in Techno Narrative Design</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-unlock-the-full-potential-of-game-recordings-in-w11/"><u>[Updated] 2024 Approved  Unlock the Full Potential of Game Recordings in W11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-get-more-from-instagram-reels-top-8-downloaders-at-no-cost/"><u>2024 Approved  Get More From Instagram Reels - Top 8 Downloaders at No Cost</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-obs-or-wirecast-deciding-on-the-best-streamer-tool/"><u>2024 Approved  OBS or Wirecast? Deciding on the Best Streamer Tool</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-skin-the-subject-eradicate-bg-in-affinity/"><u>2024 Approved  Skin the Subject, Eradicate Bg in Affinity</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-step-by-step-inserting-chapters-in-vimeo-videos/"><u>2024 Approved  Step-by-Step  Inserting Chapters in Vimeo Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-understanding-limits-to-instagram-videography/"><u>2024 Approved  Understanding Limits to Instagram Videography</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-honor-magic-v2-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Honor Magic V2 Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/banish-error-code-5-from-your-minecraft-adventure-today/"><u>Banish Error Code 5 From Your Minecraft Adventure Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-the-persistent-0x80070490-error-during-windows-update-process/"><u>Comprehensive Fixes for the Persistent 0X80070490 Error During Windows Update Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-unresponsive-space-bar-keys-in-your-new-windows-11-pc/"><u>Dealing with Unresponsive Space Bar Keys in Your New Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-when-your-windows-10-device-crashes/"><u>Effective Solutions When Your Windows 10 Device Crashes</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ensuring-compatibility-free-download-and-update-for-corsair-keyboards-k55-model/"><u>Ensuring Compatibility: Free Download & Update for Corsair Keyboard's K55 Model</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-1067-decoded-overcoming-unexpected-shutdowns-in-your-windows-system/"><u>Error 1067 Decoded: Overcoming Unexpected Shutdowns in Your Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-free-connection-overcoming-device-descriptor-request-failed-for-your-usb-gadgets/"><u>Error-Free Connection: Overcoming 'Device Descriptor Request Failed' For Your USB Gadgets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-solutions-how-to-unfreeze-your-windows-11-taskbar-efficiently/"><u>Expert Solutions: How To Unfreeze Your Windows 11 Taskbar Efficiently</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-variants-how-does-gpt-4-turbo-stack-up-against-standard-gpt-4/"><u>Exploring Variants: How Does GPT- 4 Turbo Stack Up Against Standard GPT-4?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-vanished-taskbar-icons-in-windows-n-top-4-tips-for-quick-recovery/"><u>Fix Your Vanished Taskbar Icons in Windows N - Top 4 Tips for Quick Recovery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-boot-up-issues-why-does-my-pc-with-windows-11-keep-crashing/"><u>Fixing Boot-Up Issues: Why Does My PC With Windows 11 Keep Crashing?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Samsung Galaxy Z Flip 5? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oppo-reno-11-5g-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Oppo Reno 11 5G If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-factory-unlock-your-telstra-iphone-6s-by-drfone-ios/"><u>How To Factory Unlock Your Telstra iPhone 6s</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-apple-id-from-iphone-x-without-password-by-drfone-ios/"><u>How to Remove Apple ID from iPhone X without Password?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-your-astro-a40s-nonfunctional-mic-effective-solutions-unveiled/"><u>How to Repair Your Astro A40's Nonfunctional Mic: Effective Solutions Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-non-responsive-google-chrome-errors-effectively/"><u>How to Resolve Non-Responsive Google Chrome Errors Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-address-and-resolve-incorrect-pc-booting-issues/"><u>How to Successfully Address and Resolve Incorrect PC Booting Issues</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-pro-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 Pro to other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-a-comprehensive-guide-to-iphone-6s-plus-blacklist-removal-tips-and-tools-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iPhone 6s Plus Blacklist Removal Tips and Tools</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Poco Phone without Google Account?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-woes-successful-strategies-for-restoring-your-input-device/"><u>Keyboard Woes? Successful Strategies for Restoring Your Input Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/livekernelevent-117-trouble-heres-how-you-can-fix-it/"><u>LiveKernelEvent 117 Trouble? Here's How You Can Fix It!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-a-guide-to-resolving-crc-verification-failures-efficiently/"><u>Mastering the Fix: A Guide to Resolving CRC Verification Failures Efficiently</u></a></li>
<li><a href="https://program-issues.techidaily.com/optimize-call-of-duty-warzone-for-a-lag-free-experience-on-your-pc-latest-tricks/"><u>Optimize Call of Duty Warzone for a Lag-Free Experience on Your PC - Latest Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-casting-errors-on-windows-10-a-complete-guide-to-device-connection-issues/"><u>Overcoming Casting Errors on Windows 10 - A Complete Guide to Device Connection Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-troubleshooting-solutions-for-thawing-out-a-stuck-computer-system/"><u>Quick Troubleshooting: Solutions for Thawing Out a Stuck Computer System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-guide-resurrect-lost-gaming-dlls-like-x3d/"><u>Quick-Fix Guide: Resurrect Lost Gaming Dlls Like X3D</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-poco-x6-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Poco X6 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-usb-device-not-recognized-descriptive-error-corrected/"><u>Resolving 'USB Device Not Recognized: Descriptive Error Corrected</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-how-to-correctly-fix-setup-errors-in-your-origin-game/"><u>Resolving Issues: How to Correctly Fix Setup Errors in Your Origin Game</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-non-responsive-fn-keys-expert-tips-for-dell-laptop-users/"><u>Resolving Non-Responsive Fn Keys: Expert Tips for Dell Laptop Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-dxgkrnl-fatal-error-in-videos-on-your-pc/"><u>Resolving the Dxgkrnl Fatal Error in Videos on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-missing-binkw32dll-file-a-step-by-step-guide/"><u>Resolving the Missing binkw32.dll File: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-youtube-sound-issues-how-to-fix-the-audio-renderer-glitch-in-windows-11/"><u>Resolving YouTube Sound Issues: How to Fix the Audio Renderer Glitch in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209794416-restore-your-privileges-on-steam-for-absent-files-easy-fixes-inside/"><u>Restore Your Privileges on Steam for Absent Files – Easy Fixes Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-addressing-damaged-windows-store-data-reserves/"><u>Solution Guide: Addressing Damaged Windows Store Data Reserves</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-plcncachewiper-blue-screen-of-death-understanding-and-resolving-error-0xc00000e9/"><u>Solving the PLCN_CACHE_WIPER Blue Screen of Death: Understanding and Resolving Error 0xC00000E9</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-resolving-the-persistent-windows-update-issue-error-0x8024002e/"><u>Step-by-Step Solutions for Resolving the Persistent Windows Update Issue - Error 0X8024002e</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-significance-of-msdia80dll-and-when-you-should-consider-keeping-or-deleting-this-file/"><u>The Significance of msdia80.dll and When You Should Consider Keeping or Deleting This File</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Apple iPhone 12 mini | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-addressing-stop-errors-with-printer-drivers-on-32-bit-os/"><u>Troubleshooting Tips: Addressing Stop Errors with Printer Drivers on 32-Bit OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unhide-the-taskbar-on-windows-10-for-an-optimized-desktop-experience/"><u>Unhide the Taskbar on Windows 10 for an Optimized Desktop Experience</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/unlocking-efficiency-incorporating-bings-ai-into-your-android-typing-experience/"><u>Unlocking Efficiency: Incorporating Bing's AI Into Your Android Typing Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-solutions-to-the-ce-34878-0-fault-in-ps4-consoles-a-proven-strategy-guide/"><u>Unlocking Solutions to the CE-34878-0 Fault in PS4 Consoles: A Proven Strategy Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unveiling-the-mystery-behind-dxgidll-in-pubg/"><u>Unveiling the Mystery Behind Dxgi.dll in PUBG</u></a></li>
<li><a href="https://techtrends.techidaily.com/what-to-expect-from-apples-new-foldable-phone-insider-rumors-on-release-timeline-and-pricing/"><u>What to Expect From Apple's New Foldable Phone – Insider Rumors on Release Timeline & Pricing</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->