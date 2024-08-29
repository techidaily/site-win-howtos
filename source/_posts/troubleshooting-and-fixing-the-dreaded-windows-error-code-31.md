---
title: Troubleshooting and Fixing the Dreaded Windows Error Code 31
date: 2024-08-28T00:20:54.081Z
updated: 2024-08-29T00:20:54.081Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Fixing the Dreaded Windows Error Code 31
excerpt: This Article Describes Troubleshooting and Fixing the Dreaded Windows Error Code 31
thumbnail: https://thmb.techidaily.com/c773b247e1e0895c35ac3965c0957524900af663f812d6e184693495dab0728b.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-capturing-with-snap-zoom-guide/"><u>[New] Capturing with Snap  Zoom Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-hottest-trends-these-tiktok-tests-you-need-for-2024/"><u>[New] Hottest Trends  These TikTok Tests You Need for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-stream-to-record-essential-know-how-for-tv-capture/"><u>[New] Stream to Record  Essential Know-How for TV Capture</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-comprehensively-understanding-youtubes-aspect-ratio-ecosystem/"><u>[Updated] 2024 Approved  Comprehensively Understanding YouTube's Aspect Ratio Ecosystem</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-joyful-jokes-youtubes-funniest-creators-to-relax-with/"><u>[Updated] 2024 Approved  Joyful Jokes  YouTube's Funniest Creators to Relax With</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-navigating-showmores-features-for-best-screen-recording/"><u>[Updated] 2024 Approved  Navigating ShowMore's Features for Best Screen Recording</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-immortalize-memories-prime-online-tools-for-photo-framing/"><u>[Updated] Immortalize Memories  Prime Online Tools for Photo Framing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-self-portraits-that-talk-100-words-to-define-you-on-insta/"><u>[Updated] In 2024, Self-Portraits That Talk  100 Words to Define You on Insta</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-streamlined-techniques-download-vimeo-videos-efficiently/"><u>[Updated] In 2024, Streamlined Techniques  Download Vimeo Videos Efficiently</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-premium-voice-capture-apps-on-mac-the-best-five-ranked/"><u>[Updated] Premium Voice Capture Apps on Mac  The Best Five Ranked</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-mastering-srt-to-txt-translation-the-fastest-guide/"><u>2024 Approved  Mastering SRT to TXT Translation - The Fastest Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/blades-and-boards-olympians-on-ice/"><u>Blades & Boards  Olympians on Ice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bringing-harmony-to-your-screen-fixing-microsofts-display-connections-in-windows-10/"><u>Bringing Harmony to Your Screen: Fixing Microsoft's Display Connections in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-overcoming-the-0x80072efd-error-in-windows-10-environments/"><u>Comprehensive Fixes for Overcoming the 0X80072EFD Error in Windows 10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-a-non-responsive-steam-store-page-error/"><u>Easy Fixes for a Non-Responsive Steam Store Page Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-combat-and-correct-valorants-persistent-screen-distortion-problem/"><u>Easy Steps to Combat and Correct Valorant's Persistent Screen Distortion Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211881676-end-the-frustration-of-spontaneous-hibernation-on-your-computer-smart-fixes-inside/"><u>End the Frustration of Spontaneous Hibernation on Your Computer - Smart Fixes Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolved-fix-for-semaphore-error-code-0x80070079-now-available/"><u>Error Resolved: Fix for Semaphore Error Code 0X80070079 Now Available</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-reactivate-windows-smartscreen-when-it-fails-to-load/"><u>How to Reactivate Windows SmartScreen When It Fails to Load</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-d3d-device-failure-issues-on-windows-platforms-efficiently/"><u>How To Resolve D3D Device Failure Issues on Windows Platforms Efficiently</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/infinitesound-concert-headphones-insights/"><u>InfiniteSound Concert Headphones Insights</u></a></li>
<li><a href="https://fox-glue.techidaily.com/into-virtual-realms-assessing-current-progress-future-hurdles-for-2024/"><u>Into Virtual Realms  Assessing Current Progress, Future Hurdles for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-stability-how-to-fix-continuous-crashes-of-nier-automata-on-your-computer-system/"><u>Mastering Stability: How to Fix Continuous Crashes of Nier Automata on Your Computer System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-dark-display-challenges-expert-strategies-for-your-dell-computer/"><u>Overcoming Dark Display Challenges: Expert Strategies for Your Dell Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-system-restore-challenges-in-windows-10-a-step-by-step-guide/"><u>Overcoming System Restore Challenges in Windows 10 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-pink-hue-dilemma-in-your-windows-11-interface/"><u>Overcoming the Pink Hue Dilemma in Your Windows 11 Interface</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-hevc-h265-on-samsung-is-it-possible-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Play HEVC H.265 on Samsung , is it possible?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-a-broken-screen-boosting-touch-responsiveness-on-windows-10-systems/"><u>Quick Fixes for a Broken Screen: Boosting Touch Responsiveness on Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reinstating-the-vanished-speaker-icon-on-windows-11-a-picture-perfect-guide/"><u>Reinstating the Vanished Speaker Icon on Windows 11 - A Picture Perfect Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-youtube-sound-issues-a-guide-to-fixing-audio-renderer-errors-in-windows-11/"><u>Resolving YouTube Sound Issues: A Guide to Fixing Audio Renderer Errors in Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/solving-launch-issues-top-8-troubleshooting-tips-for-hogwarts-legacy-pc-game/"><u>Solving Launch Issues: Top 8 Troubleshooting Tips for Hogwarts Legacy PC Game</u></a></li>
<li><a href="https://extra-tips.techidaily.com/sonic-startups-where-to-find-music-that-kicks-off-your-podcast/"><u>Sonic Startups  Where to Find Music that Kicks Off Your Podcast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-repairing-failed-logins-to-user-profile-service-an-in-depth-tutorial/"><u>Successfully Repairing Failed Logins to User Profile Service: An In-Depth Tutorial</u></a></li>
<li><a href="https://some-guidance.techidaily.com/superior-routes-converting-pinners-videos-into-music-files-for-2024/"><u>Superior Routes  Converting Pinners' Videos Into Music Files for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/technical-collapse-terminal-hardware-problem/"><u>Technical Collapse: Terminal Hardware Problem</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-honor-play-40c-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Honor Play 40C Reset Code | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-solve-file-explorer-not-working-errors-for-windows-11-users/"><u>Troubleshoot and Solve File Explorer Not Working Errors for Windows 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-faulty-hp-laptop-cameras-under-windows-11-operating-system/"><u>Troubleshooting Guide for Faulty HP Laptop Cameras Under Windows 11 Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-noise-issues-in-acer-laptops-quick-guide/"><u>Troubleshooting Noise Issues in Acer Laptops - Quick Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-why-does-my-mouse-keep-losing-signal/"><u>Troubleshooting Steps: Why Does My Mouse Keep Losing Signal?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/twitch-time-travel-retrieve-lost-broadcast-moments/"><u>Twitch Time-Travel  Retrieve Lost Broadcast Moments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unsticking-the-spacebar-in-windows-11-effective-solutions-for-a-smooth-typing-experience/"><u>Unsticking the Spacebar in Windows 11: Effective Solutions for a Smooth Typing Experience</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-unleash-your-creativity-free-32-bit-windows-video-editing-tools-for-2024/"><u>Updated Unleash Your Creativity Free 32-Bit Windows Video Editing Tools for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->