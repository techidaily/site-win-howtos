---
title: Effective Fixes for Unsuccessful Windows 11 Installation and Patching
date: 2024-09-05T10:04:39.394Z
updated: 2024-09-06T10:04:39.394Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Effective Fixes for Unsuccessful Windows 11 Installation and Patching
excerpt: This Article Describes Effective Fixes for Unsuccessful Windows 11 Installation and Patching
thumbnail: https://thmb.techidaily.com/3e64ab7fbedf01adf094c0f7a07b62ec8466f937073c7188969d1624a01e5f53.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136614/26400" target="_top" id="2136614">
  <img src="//a.impactradius-go.com/display-ad/26400-2136614" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136614/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115949/19272" target="_top" id="2115949">
  <img src="//a.impactradius-go.com/display-ad/19272-2115949" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115949/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115919/19272" target="_top" id="2115919">
  <img src="//a.impactradius-go.com/display-ad/19272-2115919" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115919/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121334/18498" target="_top" id="2121334">
  <img src="//a.impactradius-go.com/display-ad/18498-2121334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121334/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://win-howtos.techidaily.com/fixed-usb-ports-not-working-in-windows-1111/"><u>[Fixed] USB Ports Not Working in Windows 11/11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-leveraging-the-power-of-images-in-your-instagram-video-plans-for-2024/"><u>[New] Leveraging the Power of Images in Your Instagram Video Plans for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-reviewing-the-best-screen-recorders-on-the-market-for-2024/"><u>[New] Reviewing the Best Screen Recorders on the Market for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-the-powerhouse-analyzing-the-performance-of-lg-ud88-w-hdtv/"><u>[New] The Powerhouse  Analyzing the Performance of LG UD88-W HDTV</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transform-your-drive-must-have-accessories-for-sj4000-owners/"><u>[New] Transform Your Drive  Must-Have Accessories for SJ4000 Owners</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fading-sounds-gently-a-guide-to-softening-audibility-in-lumafusion/"><u>[Updated] Fading Sounds Gently  A Guide to Softening Audibility in Lumafusion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-not-working-a-step-by-step-solution-guide-for-windows-10-users-in-2e24/"><u>Bluetooth Not Working? A Step-by-Step Solution Guide for Windows 10 Users in 2E24</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-resolving-failed-installation-of-windows-10-updates-efficiently/"><u>Diagnosing and Resolving Failed Installation of Windows 10 Updates Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-the-non-accelerated-pixel-format-error-in-orglwjgl-codebase/"><u>Effective Fixes for the Non-Accelerated Pixel Format Error in Org.LWJGL Codebase</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-and-fixes-overcoming-corsair-hs50-microphone-problems-for-crystal-clear-sound/"><u>Expert Tips and Fixes: Overcoming Corsair HS50 Microphone Problems for Crystal Clear Sound</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-failures-during-battleye-service-start-up-overcoming-generic-errors-effectively/"><u>Fixing Failures During BattlEye Service Start-Up: Overcoming Generic Errors Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-launch-errors-in-epic-games-new-world-implementing-effective-solutions-for-easy-anti-cheat/"><u>Fixing Launch Errors in Epic Games' New World: Implementing Effective Solutions for Easy Anti-Cheat</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/from-recordings-to-live-streaming-on-youtube-and-twitch-with-obs-for-2024/"><u>From Recordings to Live  Streaming on YouTube & Twitch with OBS for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-stop-total-war-rome-remastered-from-crashing-expert-fixes-revealed/"><u>How to Stop Total War: Rome Remastered From Crashing – Expert Fixes Revealed</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-navigating-facebooks-medical-and-wellness-campaigning/"><u>In 2024, Navigating Facebook's Medical and Wellness Campaigning</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-vivo-s17e-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Vivo S17e Users</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Lava Blaze 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/insta-photography-enhancement-hacks-for-professionals/"><u>Insta-Photography Enhancement Hacks for Professionals</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-solution-correct-unidentified-usb-problems-with-this-simple-fix/"><u>Master the Solution: Correct Unidentified USB Problems with This Simple Fix</u></a></li>
<li><a href="https://fox-direct.techidaily.com/mastering-movies-with-yi-4k-hero-for-2024/"><u>Mastering Movies with YI 4K HERO for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-art-of-fixing-windows-system-crashes-dealing-with-blue-screen-error-0xc00eby/"><u>Mastering the Art of Fixing Windows System Crashes: Dealing with Blue Screen Error 0XC00eby</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-initializing-hurdle-in-destiny-2-a-step-by-step-guide/"><u>Mastering the Initializing Hurdle in Destiny 2: A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-view-counts-by-upholding-youtubes-cc-license-for-2024/"><u>Mastering View Counts by Upholding YouTube's CC License for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/modern-warfare-2-wont-start-troubleshooting-and-fixes/"><u>Modern Warfare 2 Won't Start: Troubleshooting and Fixes</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-world-of-ai-powered-bots-the-role-of-censorship/"><u>Navigating the World of AI-Powered Bots - The Role of Censorship</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-excessive-disk-space-utilization-by-microsoft-telemetry-in-windows-11/"><u>Resolved: Excessive Disk Space Utilization by Microsoft Telemetry in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-usb-connection-issues-on-your-hp-laptop-easy-solutions/"><u>Resolving USB Connection Issues on Your HP Laptop: Easy Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/second-monitor-not-detected-windows-7-solved/"><u>Second Monitor Not Detected Windows 7 [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-for-non-responsive-numeric-keys-on-keyboards/"><u>Solution Steps for Non-Responsive Numeric Keys on Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-resolution-to-solve-the-notorious-ps4-ce-34878-0-problem-expert-advice-included/"><u>Step-by-Step Resolution to Solve the Notorious PS4 CE-34878-0 Problem: Expert Advice Included</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tech-troubleshoot-repaired-wireless-logitech-mouse/"><u>Tech Troubleshoot: Repaired Wireless Logitech Mouse</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-iphone-se-2020-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of iPhone SE (2020)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/time-lapse-wizardry-an-introduction-for-2024/"><u>Time-Lapse Wizardry  An Introduction for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-failed-hardware-monitor-driver-load-problems/"><u>Troubleshooting Guide: Resolving Failed Hardware Monitor Driver Load Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooting-guide-resolving-steam-file-access-issues-and-securing-privileges/"><u>Ultimate Troubleshooting Guide: Resolving Steam File Access Issues & Securing Privileges</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wacom-tablet-woes-heres-how-to-get-it-working-again/"><u>Wacom Tablet Woes? Here's How to Get It Working Again</u></a></li>
</ul></div>
