---
title: Troubleshooting and Repairing Xbox Elite Wireless Controller Problems - Full Tutorial
date: 2024-08-15T11:19:59.644Z
updated: 2024-08-16T11:19:59.644Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Repairing Xbox Elite Wireless Controller Problems - Full Tutorial
excerpt: This Article Describes Troubleshooting and Repairing Xbox Elite Wireless Controller Problems - Full Tutorial
thumbnail: https://thmb.techidaily.com/9abfa493c09f599241cf74fbf150ee16ae0981c6610495144fe17eca852c8fbd.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-enhancing-your-tiktok-intro-with-mac-techniques/"><u>[New] 2024 Approved  Enhancing Your TikTok Intro with Mac Techniques</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-capturing-crisp-sound-a-guide-to-superior-audio-recording/"><u>[New] In 2024, Capturing Crisp Sound  A Guide to Superior Audio Recording</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-photoshops-powerful-tool-image-curving-techniques/"><u>[New] Photoshop's Powerful Tool  Image Curving Techniques</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-stepwise-strategies-for-enhancing-yt-game-coverage-through-effective-hashing/"><u>[New] Stepwise Strategies for Enhancing YT Game Coverage Through Effective Hashing</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-trailblazers-in-auditory-and-visual-creation-list/"><u>[New] Trailblazers in Auditory & Visual Creation List</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-unmasking-the-hidden-culprit-of-high-cpu-consumption-the-role-of-shell-infrastructures/"><u>[Resolved] Unmasking the Hidden Culprit of High CPU Consumption: The Role Of Shell Infrastructures.</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-balancing-bandwidth-for-obs-streams/"><u>[Updated] 2024 Approved  Balancing Bandwidth for OBS Streams</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-meerkat-experts-live-at-snapchat-spotlight-for-2024/"><u>[Updated] Meerkat Experts Live at Snapchat Spotlight for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-step-by-step-techniques-for-earning-profits-on-vimeo/"><u>[Updated] Step-by-Step Techniques for Earning Profits on Vimeo</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-audio-booster-apps-to-quicken-playback/"><u>[Updated] Top Audio Booster Apps to Quicken Playback</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-free-picture-perfection-the-finest-10-sites-reviewed/"><u>2024 Approved  Free Picture Perfection  The Finest 10 Sites Reviewed</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-gameplay-streaming-tools-revealed-obs-or-fraps/"><u>2024 Approved  Gameplay Streaming Tools Revealed  OBS or Fraps?</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-innovative-and-simple-18-vlogging-projects/"><u>2024 Approved  Innovative & Simple  18 Vlogging Projects</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-superior-hd-video-capturing-choosing-premium-recorder-models/"><u>2024 Approved  Superior HD Video Capturing  Choosing Premium Recorder Models</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-versamix-suite-mac-and-pc/"><u>2024 Approved  VersaMix Suite - Mac & PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-device-attached-to-the-system-is-not-functioning-fixed/"><u>A Device Attached to The System Is Not Functioning [Fixed]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/audio-woes-in-win-10-over-now-smooth-operations/"><u>Audio Woes in WIN 10 Over, Now Smooth Operations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-step-by-step-tutorial-resolving-the-dark-display-issue-on-your-dell-notebook/"><u>Complete Step-by-Step Tutorial: Resolving the Dark Display Issue on Your Dell Notebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-resolving-the-unresponsive-start-menu-in-windows-11-systems/"><u>Diagnosing & Resolving the Unresponsive Start Menu in Windows 11 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-installation-tips-for-intel-pro1000-mt-server-ethernet-controller/"><u>Download & Installation Tips for Intel Pro/1000 MT Server Ethernet Controller</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-connecting-a-microsoft-wireless-adapter-in-windows-10-systems/"><u>Easy Fixes for Connecting a Microsoft Wireless Adapter in Windows 10 Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/enhance-your-projectes-dimensionality-with-3d-text-psx/"><u>Enhance Your Project'es Dimensionality with 3D Text PSX</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-device-path-not-found-issues-on-windows-a-comprehensive-guide/"><u>Fixing 'Device Path Not Found' Issues on Windows: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-back-to-gaming-fix-overwatch-voice-chat-glitches-instantly/"><u>Get Back to Gaming: Fix Overwatch Voice Chat Glitches Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correct-a-failing-windows-10-update-process-expert-tips-for-users-resolved/"><u>How to Correct a Failing Windows 10 Update Process - Expert Tips for Users [RESOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-game-freezes-in-popular-battle-royale-titles/"><u>How to Fix Game Freezes in Popular Battle Royale Titles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-destructive-fatal-glitch-causing-halo-4-ue4-game-crashes-edition/"><u>How to Fix the Destructive Fatal Glitch Causing Halo 4 UE4 Game Crashes Edition</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-x-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone X Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-honor-x50i-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Honor X50i | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-from-iphone-13-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID From iPhone 13 without Password?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-xiaomi-redmi-12-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Xiaomi Redmi 12 Through Google Earth?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-definitive-guide-to-avoiding-youtube-copyright-issues/"><u>In 2024, The Definitive Guide to Avoiding YouTube Copyright Issues</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-photography-gurus-guide-to-date-stamping/"><u>In 2024, The Photography Guru's Guide to Date Stamping</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-asmrists-aiding-the-nighttime-ritual/"><u>In 2024, Top ASMRists Aiding the Nighttime Ritual</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-depth-tutorial-for-immaculate-3d-shapes-perfect-circles-spheres-for-2024/"><u>In-Depth Tutorial for Immaculate 3D Shapes  Perfect Circles, Spheres for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-conundrum-solved-reasons-behind-your-dysfunctional-razer-board/"><u>Keyboard Conundrum Solved: Reasons Behind Your Dysfunctional Razer Board</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mandatory-specification-run-the-engine-only-with-a-directx-11-supported-graphics-processor/"><u>Mandatory Specification: Run the Engine Only with a DirectX 11 Supported Graphics Processor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-the-puzzle-of-a-frozen-windows-update-at-100-mark/"><u>Overcome the Puzzle of a Frozen Windows Update at 100%% Mark</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-dota-navigating-through-error-2024-in-change-rendering-api-tips-and-tricks/"><u>Overcoming Dota Navigating Through Error 2024 in 'Change Rendering API' – Tips and Tricks</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-vivo-v30-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Vivo V30 Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/persistent-file-placement-on-windows-10-understanding-how-your-files-stay-put-between-boots/"><u>Persistent File Placement on Windows 10: Understanding How Your Files Stay Put Between Boots</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-hdcp-compatibility-issues-for-optimal-display-functionality/"><u>Resolving HDCP Compatibility Issues for Optimal Display Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-volume-control-glitches-tips-and-tricks-for-windows-users/"><u>Resolving Volume Control Glitches: Tips and Tricks for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/secure-edge-with-microsofts-advanced-protection-technology-aguard-on-windows-11/"><u>Secure Edge with Microsoft's Advanced Protection Technology (Aguard) on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-resolving-windows-sound-not-functional-errors/"><u>Solution Guide: Resolving 'Windows Sound Not Functional' Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-overcoming-black-screen-issues-on-your-dell-computer/"><u>Step-by-Step Guide: Overcoming Black Screen Issues on Your Dell Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-steelseries-x70-pen-failure-full-repair-instructions-and-tips/"><u>Step-by-Step Solution for SteelSeries X70 Pen Failure - Full Repair Instructions and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-restoring-msvcr110dll-on-your-pc/"><u>Step-by-Step Solutions for Restoring MSVCR110.dll on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-fix-is-in-how-to-reactivate-sound-in-acer-computers-silently-struggling/"><u>The Fix Is In: How to Reactivate Sound in Acer Computers Silently Struggling</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-fix-ensuring-wd-my-passport-ultra-is-compatible-and-visible-to-windows-systems/"><u>The Fix: Ensuring WD My Passport Ultra Is Compatible and Visible to Windows Systems</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-music-from-oneplus-by-fonelab-android-recover-music/"><u>The way to get back lost music from OnePlus</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208048641-trouble-free-fixes-for-a-laptop-that-wont-hold-a-charge-expert-advice-inside/"><u>Trouble-Free Fixes for a Laptop That Won't Hold A Charge: Expert Advice Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubled-rollout-issues-with-the-latest-windows-10-version-1607-upgrade/"><u>Troubled Rollout: Issues with the Latest Windows 10 Version 1607 Upgrade</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-way-out-of-windows-10-update-failure-code-0x800f0922-solved/"><u>Troubleshoot Your Way Out of Windows 10 Update Failure: Code 0X800F0922 Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-bootmgr-is-missing-errors-with-easy-diagrams/"><u>Troubleshooting and Repairing 'BOOTMGR Is Missing' Errors with Easy Diagrams</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-non-functional-keyboard-illumination-on-macbook-and-desktop-computers/"><u>Troubleshooting Guide: Non-Functional Keyboard Illumination on MacBook and Desktop Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-no-audio-output-device-message-on-windows-11/"><u>Troubleshooting Guide: Resolving 'No Audio Output Device' Message on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-solutions-fixing-steam-server-connectivity-issues/"><u>Troubleshooting Solutions: Fixing Steam Server Connectivity Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-windows-10-system-restore-fails/"><u>Troubleshooting Steps When Windows 10 System Restore Fails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooting-steps-resolving-the-dark-display-issue-on-your-dell-notebook/"><u>Ultimate Troubleshooting Steps: Resolving the Dark Display Issue on Your Dell Notebook</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-xiaomi-13t-pro-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Xiaomi 13T Pro? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211229315-windows-10-couldnt-be-installed-error-code-80240020-solved/"><u>Windows 10 Couldn't Be Installed Error Code 80240020 [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-screen-brightness-problem-steps-to-fix-it-now/"><u>Windows 11 Screen Brightness Problem: Steps to Fix It Now</u></a></li>
</ul></div>
