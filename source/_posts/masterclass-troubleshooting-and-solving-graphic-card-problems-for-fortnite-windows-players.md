---
title: "Masterclass: Troubleshooting and Solving Graphic Card Problems for Fortnite Windows Players"
date: 2024-08-19T06:46:10.875Z
updated: 2024-08-20T06:46:10.875Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Masterclass: Troubleshooting and Solving Graphic Card Problems for Fortnite Windows Players"
excerpt: "This Article Describes Masterclass: Troubleshooting and Solving Graphic Card Problems for Fortnite Windows Players"
thumbnail: https://thmb.techidaily.com/9333e7c75e292a0b83b1e16b6df5d6742dede6cee3e1ad9fc6da9c95dfc95571.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-beginners-blueprint-for-initiating-instagram-discussions/"><u>[New] In 2024, Beginner's Blueprint for Initiating Instagram Discussions</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-convenient-tutorial-snapchat-installation-macos-style/"><u>[New] In 2024, Convenient Tutorial  Snapchat Installation macOS-Style</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-elevate-your-channel-studio-upgrade-vs-beta-shift/"><u>[New] In 2024, Elevate Your Channel  Studio Upgrade Vs. Beta Shift</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-optimal-solutions-for-webp-to-jpg-image-transformation/"><u>[New] Optimal Solutions for WebP-to-JPG Image Transformation</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-retro-to-modern-radeon-transition/"><u>[New] Retro to Modern  Radeon Transition</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-chromebook-masterclass-excellent-recording-suite/"><u>[Updated] 2024 Approved  Chromebook Masterclass  Excellent Recording Suite</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-youtube-streams-optimal-webm-converters-ranked/"><u>[Updated] 2024 Approved  YouTube Streams  Optimal WebM Converters Ranked!</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-beginners-guide-to-crafting-trendy-mac-video-content/"><u>[Updated] Beginner's Guide to Crafting Trendy Mac Video Content</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-dslr-or-mirrorless-the-ultimate-question-for-videographers/"><u>[Updated] In 2024, DSLR or Mirrorless? The Ultimate Question for Videographers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-win-11s-10-finest-webcams-for-high-quality-capture/"><u>[Updated] In 2024, Win 11'S 10 Finest Webcams For High-Quality Capture</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-photo-retouch-erase-backgrounds-effectively/"><u>[Updated] Mastering Photo Retouch  Erase Backgrounds Effectively</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-saturating-the-market-precision-in-sharing-through-shorts/"><u>[Updated] Saturating the Market  Precision in Sharing Through Shorts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-best-for-broadcasting-obs-vs-twitch-studio/"><u>[Updated] The Best for Broadcasting? OBS vs Twitch Studio</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-peeling-layers-to-originality-a-guide-for-instagram-photo-search/"><u>2024 Approved  Peeling Layers to Originality  A Guide for Instagram Photo Search</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-the-ultimate-route-to-record-your-favorite-streaming-content-hulu/"><u>2024 Approved  The Ultimate Route to Record Your Favorite Streaming Content (Hulu)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-nubia-red-magic-9-pro-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/address-counterarguments-eg-some-may-argue-that-other-qualities-are-more-important-for-professional-success-and-rebut-them-with-convincing-evidence/"><u>Address Counterarguments (E.g., some May Argue that Other Qualities Are More Important for Professional Success) and Rebut Them with Convincing Evidence.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-trouble-shooting-tips-to-restore-your-pcs-ethernet-functionality-in-windows-10-and-7/"><u>Comprehensive Trouble Shooting Tips to Restore Your PC's Ethernet Functionality in Windows 10 & 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-touchless-screens-learn-quick-fixes-for-activating-interactive-controls/"><u>Dealing with Touchless Screens? Learn Quick Fixes for Activating Interactive Controls!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-resolving-lenovo-keyboard-malfunctions-effectively/"><u>Diagnosing and Resolving Lenovo Keyboard Malfunctions Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/discord-mic-now-operational/"><u>Discord Mic Now Operational</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/enhance-discord-conversations-a-recorders-insight-for-2024/"><u>Enhance Discord Conversations  A Recorder's Insight for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-correctly-address-the-windows-error-code-0x80072f8f-on-1110-systems/"><u>Expert Tips to Correctly Address the Windows Error Code 0X80072F8F on 11/10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-restoring-and-refreshing-your-computers-keyboard-functionality/"><u>Expert Tips: Restoring and Refreshing Your Computer's Keyboard Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-critical-system-error-5-across-multiple-windows-platforms-a-step-by-step-guide/"><u>Fixing Critical System Error 5 Across Multiple Windows Platforms: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-0x800705b4-fault-during-windows-update-on-windows-11-a-comprehensive-guide/"><u>Fixing the 0X800705b4 Fault During Windows Update on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://buynow-help.techidaily.com/go-anywhere-stay-in-control-the-sabrent-portable-miniature-mouse-merging-accuracy-and-detachable-wires/"><u>Go Anywhere, Stay in Control: The Sabrent Portable Miniature Mouse Merging Accuracy and Detachable Wires</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-connection-could-not-be-established-errors-in-firefox/"><u>How to Fix 'Connection Could Not Be Established' Errors in Firefox</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-1ve-when-it-becomes-unresponsive/"><u>How to Fix Windows 1Ve When It Becomes Unresponsive?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-mousepad-working-again-on-windows-operating-systems-win1087/"><u>How to Get Your Mousepad Working Again on Windows Operating Systems (Win10/8/7)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-sound-back-addressing-windows-11-mutevolume-problems/"><u>How to Get Your Sound Back: Addressing Windows 11 Mute/Volume Problems</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-realme-v30t-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Realme V30T Pattern Lock Screen</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-professional-steps-for-high-quality-powerpoint-replays/"><u>In 2024, Professional Steps for High-Quality PowerPoint Replays</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-streamline-your-video-capture-on-youtube/"><u>In 2024, Streamline Your Video Capture on YouTube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209281547-master-the-art-of-keeping-your-machine-awake-all-night-hassle-free/"><u>Master the Art of Keeping Your Machine Awake All Night, Hassle-Free!</u></a></li>
<li><a href="https://review-topics.techidaily.com/nokia-bypass-tools-to-bypass-lock-screennokia-by-drfone-android-unlock-android-unlock/"><u>Nokia Bypass Tools to Bypass Lock Screen(Nokia)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-wrp-errors-in-windows-a-comprehensive-troubleshooting-manual/"><u>Overcoming WRP Errors in Windows: A Comprehensive Troubleshooting Manual</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-system-palette-placing-this-pc-on-screen/"><u>Personalized System Palette: Placing 'This PC' On Screen</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-connection-issues-fixing-network-restrictions-on-party-apps/"><u>Resolve Your Connection Issues: Fixing 'Network Restrictions on Party Apps'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-critical-error-during-program-launch-fixing-the-application-failed-to-initialize-message-0xc000007b/"><u>Resolved: Critical Error During Program Launch - Fixing The 'Application Failed To Initialize' Message (0xC000007B)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208194874-run-the-latest-engine-successfully-upgrade-to-a-gpu-that-works-with-direct3d-11/"><u>Run the Latest Engine Successfully? Upgrade to a GPU that Works with Direct3D 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-for-resolving-windows-error-code-0xc0000098/"><u>Solutions for Resolving Windows Error Code 0xC0000098</u></a></li>
<li><a href="https://win-howtos.techidaily.com/svchostexe-overload-understanding-netservices-solutions-and-prevention/"><u>Svchost.exe Overload: Understanding Netservices, Solutions & Prevention</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-nba-2k21-emerald-gaffe-solved-techniques-for-gamers/"><u>The NBA 2K21 Emerald Gaffe: Solved Techniques for Gamers</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-vivo-x90s-frp-by-drfone-android/"><u>The Updated Method to Bypass Vivo X90S FRP</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-device-casting-resolve-it-quickly-on-windows-11/"><u>Trouble with Device Casting? Resolve It Quickly on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-resolve-your-computers-stuck-at-loading-windows/"><u>Troubleshoot and Resolve Your Computer's 'Stuck at Loading Windows'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixes-for-unresponsive-personal-setting-adjustments/"><u>Troubleshooting Fixes for Unresponsive Personal Setting Adjustments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-how-to-overcome-remote-server-connection-problems/"><u>Troubleshooting Steps: How to Overcome Remote Server Connection Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-fixing-the-logitech-g930-headset-microphone-cut-out-issue/"><u>Troubleshooting Tips: Fixing the Logitech G930 Headset Microphone Cut-Out Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unavailable-feature-fixed-monitor-displays-do-not-recognize-current-input-timing/"><u>Unavailable Feature: [FIXED] Monitor Displays Do Not Recognize Current Input Timing</u></a></li>
</ul></div>
