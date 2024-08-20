---
title: Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix!
date: 2024-08-19T06:32:19.517Z
updated: 2024-08-20T06:32:19.517Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix!
excerpt: This Article Describes Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix!
thumbnail: https://thmb.techidaily.com/069b298bfedee9c280f30a09eb725e41e8884f90fc111239be7bdf14c7e0c06b.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-build-stellar-youtube-beginnings-on-a-shoestring-budget/"><u>[New] 2024 Approved  Build Stellar YouTube Beginnings on a Shoestring Budget</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-boost-engagement-top-8-youtube-video-trackers-unveiled/"><u>[New] In 2024, Boost Engagement - Top 8 YouTube Video Trackers Unveiled</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-your-daily-diary-staying-fresh-and-avoiding-common-mistakes/"><u>[New] Your Daily Diary  Staying Fresh & Avoiding Common Mistakes</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-pcs-picks-the-finest-ps1-game-emulators/"><u>[Updated] 2024 Approved  PC's Picks  The Finest PS1 Game Emulators</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-best-ways-to-record-and-save-itunes-videos-for-2024/"><u>[Updated] Best Ways to Record and Save iTunes Videos for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-add-a-streamline-of-youtube-playlists-on-your-website-for-2024/"><u>[Updated] How to Add a Streamline of YouTube Playlists on Your Website for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-switchs-prime-capture-technology-picks/"><u>[Updated] In 2024, Switch's Prime Capture Technology Picks</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-premier-windows-video-chat-apps-7-1/"><u>[Updated] Premier Windows Video Chat Apps #7-#1</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-unveiling-the-process-of-making-a-twitter-account-for-2024/"><u>[Updated] Unveiling the Process of Making a Twitter Account for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-broadcast-battleground-pick-your-preferred-livestreaming-champion-vmixwirecast/"><u>2024 Approved  Broadcast Battleground  Pick Your Preferred Livestreaming Champion (VMix/Wirecast)</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-mastering-sales-select-from-these-top-15-facebook-analytics-pros/"><u>2024 Approved  Mastering Sales  Select From These Top 15 Facebook Analytics Pros</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-secrets-to-joining-friends-tiktok-live-events/"><u>2024 Approved  Secrets to Joining Friends' TikTok Live Events</u></a></li>
<li><a href="https://win-howtos.techidaily.com/aoc-monitor-not-responding-heres-your-ultimate-guide-for-windows-10-users/"><u>AOC Monitor Not Responding? Here's Your Ultimate Guide for Windows 10 Users</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-step-by-step-solution-resolving-issues-with-your-xbox-one-controller-guide/"><u>Complete Step-by-Step Solution: Resolving Issues with Your Xbox One Controller (Guide)</u></a></li>
<li><a href="https://games-able.techidaily.com/dandd-dynamics-boosted-six-chatgpt-methods-to-become-your-mentor/"><u>D&D Dynamics Boosted: Six ChatGPT Methods to Become Your Mentor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-a-broken-spacebar-on-your-windows-10-pc-expert-tips-and-tricks/"><u>Dealing with a Broken Spacebar on Your Windows 10 PC – Expert Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeating-the-frozen-screen-strategies-to-revive-your-computer/"><u>Defeating the Frozen Screen: Strategies to Revive Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fixes-for-dxgi-device-hung-errors-quick-solutions-and-tips/"><u>Effortless Fixes for DXGI Device Hung Errors: Quick Solutions & Tips</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/embracing-global-communication-4-essential-reasons-for-post-40-polyglots/"><u>Embracing Global Communication: 4 Essential Reasons for Post-40 Polyglots</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-for-repairing-a-malfunctioning-corsair-hs50-mic-step-by-step-solutions/"><u>Expert Advice for Repairing a Malfunctioning Corsair HS50 Mic - Step-by-Step Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-it-persistent-issues-with-functional-buttons-on-windows-1110-computer-keyboards/"><u>Fix It! Persistent Issues with Functional Buttons on Windows 11/10 Computer Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-the-not-supported-error-in-miracast-with-a-simple-graphics-driver-update/"><u>Fix the Not Supported Error in Miracast with a Simple Graphics Driver Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-fixing-windows-unable-to-access-sen-issue-resolved/"><u>Guide to Fixing 'Windows Unable to Access SEN' - Issue Resolved</u></a></li>
<li><a href="https://win-blog.techidaily.com/haley-ba-et-al-2n-glyphosate-in-surface-water-a-review-of-occurrence-and-potential-impacts-on-aquatic-ecosystems-environ-monit-assess-1896-401/"><u>Haley BA., Et Al (2N). Glyphosate in Surface Water: A Review of Occurrence and Potential Impacts on Aquatic Ecosystems. Environ Monit Assess, 189(6), 401</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-infinix-smart-8-plus-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Infinix Smart 8 Plus Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-eliminate-the-persistent-bright-scarlet-error-on-your-pc-windows-10-solution/"><u>How to Eliminate the Persistent Bright Scarlet Error on Your PC (Windows 10 Solution)</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-honor-100-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Honor 100? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-an-unresponsive-aoc-monitor-with-windows-10-troubleshooting-tips/"><u>How to Repair an Unresponsive AOC Monitor with Windows 10: Troubleshooting Tips</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Samsung Galaxy M34 5G? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-network-locked-tecno-spark-go-2024-phone-by-drfone-android/"><u>How to Unlock a Network Locked Tecno Spark Go (2024) Phone?</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-poco-x6-pro-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-perfecting-live-social-media-facebook-livestream-tutorials-for-tech/"><u>In 2024, Perfecting Live Social Media  Facebook Livestream Tutorials for Tech</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-on-poco-x6-pro-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Poco X6 Pro FRP Bypass</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-unlock-and-save-your-favorite-fb-videos/"><u>In 2024, Unlock and Save Your Favorite FB Videos</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/iphone-hacks-the-definitive-guide-to-sending-sound-based-messages-efficiently/"><u>IPhone Hacks: The Definitive Guide to Sending Sound-Based Messages Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-minecraft-expert-tips-for-resolving-local-network-glitches/"><u>Mastering Minecraft: Expert Tips for Resolving Local Network Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-performance-strategies-for-reducing-system-idle-process-cpu-strain/"><u>Optimizing Performance: Strategies for Reducing System Idle Process CPU Strain</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcome-flashy-windows-11-monitor/"><u>Overcome Flashy Windows 11 Monitor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-syncing-hurdles-for-your-xbox-one-controller-a-comprehensive-guide/"><u>Overcoming Syncing Hurdles for Your Xbox One Controller - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-update-service-failures-steps-and-fixes-unveiled/"><u>Overcoming Windows Update Service Failures: Steps and Fixes Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-why-does-wudfhostexe-consume-high-cpu-on-windows-10/"><u>Resolved: Why Does wudfhost.exe Consume High CPU on Windows 10?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-hardware-malfunctions-fixing-a-frozen-hddssd-on-windows-11/"><u>Resolving Hardware Malfunctions: Fixing a Frozen HDD/SSD on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-unable-to-start-application-issue-error-0xc000007b-explained-and-fixed/"><u>Resolving the 'Unable to Start Application' Issue: Error 0xC000007B Explained and Fixed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-solutions-for-resolving-hearthstone-game-lags/"><u>Simple Solutions for Resolving Hearthstone Game Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-stalled-windows-updates-at-100-mark/"><u>Step-by-Step Guide: Resolving Stalled Windows Updates at 100%% Mark</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-troubleshooting-tips-for-d3derr-not-available-issue/"><u>Step-by-Step Troubleshooting Tips for 'D3DERR Not Available' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/streamline-your-windows-experience-fixing-dwms-impact-on-gpu-resources-in-win11-and-win10-a-5-step-guide/"><u>Streamline Your Windows Experience: Fixing DWM's Impact on GPU Resources in Win11 and Win10 – A 5-Step Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-apple-iphone-15-pro-by-drfone-ios/"><u>The Easy Way to Remove an Apple ID from Your MacBook For your Apple iPhone 15 Pro</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-solution-for-stuck-buttons-on-your-windows-keyboard/"><u>The Ultimate Solution for Stuck Buttons on Your Windows Keyboard</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/transferring-your-favorite-spotify-playlist-into-a-written-format/"><u>Transferring Your Favorite Spotify Playlist Into a Written Format</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/transform-your-virtual-engagements-with-these-top-10-cost-free-tools-for-2024/"><u>Transform Your Virtual Engagements with These Top 10 Cost-Free Tools for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-continuous-system-reboots-ultimate-solutions-for-windows-1110-users/"><u>Troubleshooting Continuous System Reboots - Ultimate Solutions for Windows 11/10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-when-the-microsoft-store-wont-open/"><u>Troubleshooting Guide for When the Microsoft Store Won't Open</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-non-functional-hdmi-connector-via-usb/"><u>Troubleshooting Guide: Fixing a Non-Functional HDMI Connector via USB</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-successfully-resolving-loadlibrary-error-code-87/"><u>Troubleshooting Guide: Successfully Resolving LoadLibrary Error Code 87</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-sudden-shutdown-of-windows-processes-understanding-error-1067/"><u>Troubleshooting the Sudden Shutdown of Windows Processes - Understanding Error 10^67</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-fix-unresponsive-function-key-issues/"><u>Troubleshooting: How to Fix Unresponsive Function Key Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-mse-insights-into-microsoft-security-essentials-and-its-impact-on-disk-utilization/"><u>Understanding MSE: Insights Into Microsoft Security Essentials & Its Impact on Disk Utilization</u></a></li>
<li><a href="https://driver-download.techidaily.com/up-to-date-drivers-for-scansnap-s1300i-quick-download-and-installation-tutorial/"><u>Up-to-Date Drivers for ScanSnap S1300i: Quick Download and Installation Tutorial!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/updating-windows-10-to-version-1803-a-step-by-step-success-guide/"><u>Updating Windows 10 to Version 1803: A Step-by-Step Success Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Poco M6 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-strategies-for-enhanced-gaming-speed-in-windows-11/"><u>Winning Strategies for Enhanced Gaming Speed in Windows 11</u></a></li>
</ul></div>
