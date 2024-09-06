---
title: Diagnosing and Fixing Windows System Faults - Addressing the Device Unavailable Issue (Code 24)
date: 2024-09-05T10:00:16.790Z
updated: 2024-09-06T10:00:16.790Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Fixing Windows System Faults - Addressing the Device Unavailable Issue (Code 24)
excerpt: This Article Describes Diagnosing and Fixing Windows System Faults - Addressing the Device Unavailable Issue (Code 24)
thumbnail: https://thmb.techidaily.com/90c2e01727fc918de7950373ab7790d2b6bd79b92f560dcc1472e9356e8fe972.png
---

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123475/16836" target="_top" id="2123475">
  <img src="//a.impactradius-go.com/display-ad/16836-2123475" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123475/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

<!-- affiliate ads begin -->
<span id="1983551">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983551.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983551">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983551.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983551%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983551/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

<!-- affiliate ads begin -->
<span id="1982508">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982508.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982508">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982508.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982508%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982508/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://fox-http.techidaily.com/new-in-2024-tips-to-rectify-broken-airdrop-connectivity-across-apple-gadgets/"><u>[New] In 2024, Tips to Rectify Broken AirDrop Connectivity Across Apple Gadgets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-screen-flickering-in-windows-11/"><u>[Solved] Screen Flickering in Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-elevate-video-clarity-with-expert-tips-for-youtube-editors/"><u>[Updated] In 2024, Elevate Video Clarity with Expert Tips for YouTube Editors</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-narrowing-focus-mac-techniques-for-snapchat-videos/"><u>2024 Approved  Narrowing Focus  Mac Techniques for Snapchat Videos</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-perfect-pacing-with-macos-a-specialists-guide-to-srt-editing/"><u>2024 Approved  Perfect Pacing with macOS  A Specialist's Guide to SRT Editing</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-premium-fullscreen-screen-recording-tools/"><u>2024 Approved  Premium Fullscreen Screen Recording Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-itel-a70-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Itel A70 Phone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/banishing-shadows-from-your-game-onload-a-guide-to-fix-monster-hunter-world-black-screen-problem/"><u>Banishing Shadows From Your Game Onload: A Guide to Fix Monster Hunter: World Black Screen Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-strategies-restoring-your-display-from-a-black-screen-in-windows-11/"><u>Comprehensive Strategies: Restoring Your Display From a Black Screen in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/computer-wont-exit-boot-screen-try-these-solutions/"><u>Computer Won't Exit Boot Screen? Try These Solutions!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-warframe-patch-failures-step-by-step-solution-guide/"><u>Dealing with Warframe Patch Failures: Step-by-Step Solution Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/deciding-on-nvidia-fe-or-asus-branded-gpus/"><u>Deciding on Nvidia FE or Asus-Branded GPUs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-repair-what-to-do-when-your-surface-pen-stops-responding/"><u>DIY Repair: What To Do When Your Surface Pen Stops Responding</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-the-persistent-windows-update-error-0x8023c401c-in-latest-versions-of-microsoft-os/"><u>Effective Fixes for the Persistent 'Windows Update Error 0X802^3C401C' In Latest Versions of Microsoft OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x8072f8f-fixes-step-by-step-solutions-for-windows-operating-systems-windows-1110/"><u>Error Code 0X80#72F8F Fixes: Step-by-Step Solutions for Windows Operating Systems (Windows 11/10)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-fix-system-restore-failed-with-error-code-0x80070091-in-windows-10/"><u>Expert Tips to Fix System Restore Failed with Error Code 0X80070091 in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-world-of-warcraft-wow-lags-effective-strategies-and-techniques/"><u>Fixing World of Warcraft (WoW) Lags: Effective Strategies and Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-fix-screen-stuttering-problems-in-your-windows-prise/"><u>Guide to Fix Screen Stuttering Problems in Your Windows Prise</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-overcoming-dvd-compatibility-and-playability-hurdles-on-windows-systems/"><u>Guide: Overcoming DVD Compatibility and Playability Hurdles on Windows Systems</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-honor-play-8t-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Honor Play 8T?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212186222-how-to-fix-unrecognized-usb-hardware-errors-on-your-pc-solutions-inside/"><u>How to Fix Unrecognized USB Hardware Errors on Your PC – Solutions Inside!</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-tecno-phantom-v-flip-by-fonelab-android-recover-video/"><u>How to recover old videos from your Tecno Phantom V Flip</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-turn-off-touchpad-auto-enablement-with-a-mouse-in-windows-11/"><u>How to Turn Off Touchpad Auto-Enablement with a Mouse in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-go-joystick-on-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Samsung Galaxy A25 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205383936-ignored-sd-card-find-the-cure/"><u>Ignored SD Card? Find the Cure</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-bringing-your-ideas-to-life-vo-plus-ppt-perfection/"><u>In 2024, Bringing Your Ideas to Life  VO + PPT Perfection</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-cutting-edge-videography-top-cameras/"><u>In 2024, Cutting-Edge Videography  Top Cameras</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209638916-laptop-microphone-problems-heres-how-to-get-it-working-again/"><u>Laptop Microphone Problems? Here's How to Get It Working Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-update-recovery-and-optimization/"><u>Mastering Windows Update Recovery and Optimization</u></a></li>
<li><a href="https://win-howtos.techidaily.com/maximizing-your-machines-potential-how-to-end-overbearing-system-load-from-shell-infrastructures/"><u>Maximizing Your Machine’s Potential – How to End Overbearing System Load From Shell Infrastructures</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-the-ipodiverse-compreenasol-for-ios-podcast-downloads/"><u>Navigating the iPodiverse  Compreenasol for iOS Podcast Downloads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-luck-with-your-pdf-printer-let-us-guide-you-to-quick-fixes/"><u>No Luck with Your PDF Printer? Let Us Guide You to Quick Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205377777-quick-fixes-for-stuck-or-unresponsive-buttons-on-an-hp-laptop-solutions-at-hand/"><u>Quick Fixes for Stuck or Unresponsive Buttons on an HP Laptop – Solutions at Hand!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-when-your-netflix-has-no-audio/"><u>Quick Fixes for When Your Netflix Has No Audio</u></a></li>
<li><a href="https://howto.techidaily.com/quick-fixes-for-why-is-my-samsung-galaxy-f54-5g-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Samsung Galaxy F54 5G Black and White | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solution-for-fixing-error-0x887a0006-a-comprehensive-walkthrough/"><u>Quick Solution for Fixing Error 0X887A0006: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-continuous-reboot-issues-in-windows-10-a-step-by-step-guide/"><u>Resolving Continuous Reboot Issues in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-ce-34878-0-glitch-on-playstation-4-a-comprehensive-guide/"><u>Resolving the CE-34878-0 Glitch on PlayStation 4: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-1011-problems-night-light-functionality-gone-awry/"><u>Resolving Windows 10/11 Problems - Night Light Functionality Gone Awry?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restored-essential-touch-sensitivity-for-hit-device/"><u>Restored Essential Touch Sensitivity for HIT Device</u></a></li>
<li><a href="https://tech-revival.techidaily.com/simple-solutions-eliminating-screen-phantom-images-effortlessly/"><u>Simple Solutions: Eliminating Screen Phantom Images Effortlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-off-screen-window-problems-with-simple-shortcuts-and-adjustments/"><u>Solving Off-Screen Window Problems with Simple Shortcuts and Adjustments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-undetected-window-two-screen-issue/"><u>Solving Undetected Window Two-Screen Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-when-number-keys-on-your-keyboard-wont-respond/"><u>Step-by-Step Solution for When Number Keys on Your Keyboard Won't Respond</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/straightforward-stories-essence/"><u>Straightforward Stories' Essence</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-updating-stuck-systems-mastering-windows-11-upgrades-and-installations/"><u>Successfully Updating Stuck Systems: Mastering Windows 11 Upgrades and Installations</u></a></li>
<li><a href="https://some-guidance.techidaily.com/techniques-to-weave-narrative-into-visual-content-for-2024/"><u>Techniques to Weave Narrative Into Visual Content for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/the-ultimate-guide-to-playing-yakuza-like-a-dragon-on-pc-problems-solved/"><u>The Ultimate Guide to Playing 'Yakuza: Like a Dragon' On PC - Problems Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-solutions-for-excessive-svchost-process-load-on-windows-11-computers/"><u>Top Solutions for Excessive Svchost Process Load on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trace-your-lost-touchpad-to-device-master/"><u>Trace Your Lost Touchpad to Device Master!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-a-persistent-code-28-device-manager-glitch-on-windows-systems/"><u>Troubleshooting and Resolving a Persistent 'Code 28' Device Manager Glitch on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-common-issues-with-windows-11-1607-update-failures/"><u>Troubleshooting Common Issues with Windows 11 1607 Update Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-overcoming-sfc-error-in-windows-operating-systems/"><u>Troubleshooting Tips for Overcoming SFC Error in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-windows-error-code-31-swiftly/"><u>Ultimate Guide: Resolving Windows Error Code 31 Swiftly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unreachable-fixed-troubleshooting-windows-smartscreen-connectivity-issues/"><u>Unreachable [FIXED]: Troubleshooting Windows SmartScreen Connectivity Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-stalled-windows-update-at-100-with-these-proven-tips-and-tricks/"><u>Unstick Your Stalled Windows Update at 100%% with These Proven Tips and Tricks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/watch-disneys-magic-on-the-big-screen-connecting-disneyplus-with-chromecast-made-easy/"><u>Watch Disney's Magic on the Big Screen: Connecting Disney+ with Chromecast Made Easy</u></a></li>
<li><a href="https://tech-revival.techidaily.com/why-choose-claude-3-explore-these-4-compelling-reasons-to-upgrade-from-chatgpt/"><u>Why Choose Claude 3? Explore These 4 Compelling Reasons to Upgrade From ChatGPT</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Samsung Galaxy S23 FE | Dr.fone</u></a></li>
</ul></div>
