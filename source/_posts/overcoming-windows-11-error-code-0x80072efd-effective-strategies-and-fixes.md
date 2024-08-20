---
title: "Overcoming Windows 11 Error Code 0X80072EFD: Effective Strategies and Fixes"
date: 2024-08-19T06:46:15.275Z
updated: 2024-08-20T06:46:15.275Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming Windows 11 Error Code 0X80072EFD: Effective Strategies and Fixes"
excerpt: "This Article Describes Overcoming Windows 11 Error Code 0X80072EFD: Effective Strategies and Fixes"
thumbnail: https://thmb.techidaily.com/9a7e28e8568427a787263a138246015aa54bad8070697287a395ca8f0d59bbb1.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
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
<li><a href="https://extra-tips.techidaily.com/new-amplify-your-videos-the-best-text-effects-guide/"><u>[New] Amplify Your Videos  The Best Text Effects Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-beyond-apowersoft-top-10-screen-capture-apps-analyzed-for-2024/"><u>[New] Beyond Apowersoft  Top 10 Screen Capture Apps Analyzed for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-expert-tips-crafting-compelling-facebook-ad-videos/"><u>[New] Expert Tips  Crafting Compelling Facebook Ad Videos</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-hitching-a-ride-in-high-flying-tiktok-live-shows/"><u>[New] In 2024, Hitching a Ride in High-Flying TikTok Live Shows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-a-glimpse-into-future-facebook-ad-tactics-for-24/"><u>[Updated] 2024 Approved  A Glimpse Into Future-Facebook Ad Tactics for '24</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-innovative-text-treatments-elevating-ae-titles/"><u>[Updated] 2024 Approved  Innovative Text Treatments  Elevating AE Titles</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-nba-game-broadcasting-select-the-best-platforms/"><u>[Updated] 2024 Approved  NBA Game Broadcasting  Select the Best Platforms</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-dynamic-strategies-for-complementary-podcast-consumption/"><u>[Updated] In 2024, Dynamic Strategies for Complementary Podcast Consumption</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-scale-up-snaps-no-loss-in-detail/"><u>[Updated] Scale Up Snaps - No Loss in Detail</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/avoiding-frustrations-with-tiktok-glitches/"><u>Avoiding Frustrations with TikTok Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-error-0x800f081f-expert-strategies-for-a-smooth-net-framework-35-installation-process/"><u>Bypass Error 0X800F081F – Expert Strategies for a Smooth .NET Framework 3.5 Installation Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-tutorial-resolving-display-connections-and-no-video-errors/"><u>Comprehensive Tutorial: Resolving Display Connections and No Video Errors</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/decode-your-insta-performance-a-complete-look-at-user-behavior-for-2024/"><u>Decode Your Insta Performance  A Complete Look at User Behavior for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fix-for-red-dead-redemption-2-memory-problems-upgrade-page-file-without-hesitation/"><u>Easy Fix for Red Dead Redemption 2 Memory Problems: Upgrade Page File Without Hesitation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-handling-video-related-dxgkrnl-crashes-on-windows-systems/"><u>Effective Fixes for Handling Video-Related Dxgkrnl Crashes on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212530010-endless-blinking-cursor-learn-how-to-make-it-disappear-now/"><u>Endless Blinking Cursor? Learn How to Make It Disappear Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/experience-smooth-controls-xbox-one-on-pc/"><u>Experience Smooth Controls: Xbox One on PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-issues-with-windows-boot-process-delays/"><u>Expert Tips to Overcome Issues with Windows Boot Process Delays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-update-0x80070490-issue-a-step-by-step-guide/"><u>Fixing the Windows Update 0X80070490 Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/foobar2000-wave-router/"><u>Foobar2000 Wave Router</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fortnite-troubleshooting-launch-success/"><u>Fortnite Troubleshooting: Launch Success</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-honor-magic-vs-2-is-unlocked-by-drfone-android/"><u>How To Check if Your Honor Magic Vs 2 Is Unlocked</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-rid-of-the-unsettling-red-screen-problems-in-windows-11/"><u>How to Get Rid of the Unsettling Red Screen Problems in Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-install-the-latest-dell-v305-all-in-one-printer-driver-on-windows-7/"><u>How to Install the Latest Dell V305 All-in-One Printer Driver on Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-smooth-out-your-gaming-experience-in-pubg-best-tips-and-tricks/"><u>How to Smooth Out Your Gaming Experience in PUBG - Best Tips & Tricks</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-reno-10-pro-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Oppo Reno 10 Pro 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-best-ways-to-bypass-icloud-activation-lock-on-iphone-14-plusipadipod-by-drfone-ios/"><u>In 2024, Best Ways to Bypass iCloud Activation Lock on iPhone 14 Plus/iPad/iPod</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-evaluating-the-financial-returns-for-makers-on-youtube-shorts/"><u>In 2024, Evaluating the Financial Returns for Maker's on YouTube Shorts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Lava Blaze 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-rapid-rise-to-affiliate-hit-the-pivotal-10000-view-mark/"><u>In 2024, Rapid Rise to Affiliate  Hit the Pivotal 10,000 View Mark</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-pc-efficiency-fixing-the-problem-of-overworked-wudfhostexe-in-windows-11/"><u>Mastering PC Efficiency: Fixing the Problem of Overworked WUDFHost.exe in Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-mastering-the-art-of-flawless-podcast-production-your-comprehensive-tutorial/"><u>New Mastering the Art of Flawless Podcast Production Your Comprehensive Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/oddworld-soulstorm-pc-game-crash-no-more-discover-effective-fix-strategies-here/"><u>Oddworld: Soulstorm PC Game Crash No More? Discover Effective Fix Strategies Here</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-game-crashes-in-nier-automata-tips-and-solutions-for-a-smoother-pc-gaming-experience/"><u>Overcome Game Crashes in Nier Automata: Tips & Solutions for a Smoother PC Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-0x8024401c-update-glitches-in-microsofts-latest-operating-systems-a-comprehensive-guide-for-windows-10-and-11-users/"><u>Overcoming 0X8024401c Update Glitches in Microsoft's Latest Operating Systems: A Comprehensive Guide for Windows 10 and 11 Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pinnacle-screenplays-reviewed-for-2024/"><u>Pinnacle Screenplays Reviewed for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-to-restore-battery-charging-functionality-on-your-laptop/"><u>Quick Fixes to Restore Battery Charging Functionality on Your Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/recovering-an-off-screen-window-a-step-by-step-guide/"><u>Recovering an Off-Screen Window: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-a-non-responsive-laptop-mouse-step-by-step-troubleshooting-guide/"><u>Resolving a Non-Responsive Laptop Mouse: Step-by-Step Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-errcachemiss-issue-on-google-chrome-a-step-by-step-guide/"><u>Resolving the ERR_CACHE_MISS Issue on Google Chrome: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-overcoming-hurdles-in-your-latest-windows-11-system-update/"><u>Solved! Overcoming Hurdles in Your Latest Windows 11 System Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-resolution-overcoming-bluetooth-mouse-connection-problems-in-windows/"><u>Step-by-Step Resolution: Overcoming Bluetooth Mouse Connection Problems in Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-hdr-experience-with-asuss-4k-monitor-for-2024/"><u>The Ultimate HDR Experience with Asus's 4K Monitor for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210018626-troubleshooting-apex-legends-simple-fixes-for-the-anti-cheat-error-solved/"><u>Troubleshooting Apex Legends: Simple Fixes for the Anti-Cheat Error - Solved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-nier-automata-pc-issues-for-smooth-gaming-experience/"><u>Troubleshooting Nier: Automata PC Issues for Smooth Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-overcoming-windows-10s-stalled-updates-and-installation-problems/"><u>Troubleshooting Tips: Overcoming Windows 10'S Stalled Updates and Installation Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-0x8024a105-issue-with-windows-updates/"><u>Ultimate Guide: Resolving the 0X8024A105 Issue with Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209521615-unexpected-silence-revive-your-touchpads-display/"><u>Unexpected Silence? Revive Your Touchpad's Display</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlock-the-solution-step-by-step-tips-for-addressing-twitch-error-4000/"><u>Unlock the Solution: Step-by-Step Tips for Addressing Twitch Error #4000</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-windows-11-on-startup-efficient-troubleshooting-tips/"><u>Unstick Your Windows 11 on Startup: Efficient Troubleshooting Tips</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-secrets-of-dts-virtual-x-technology/"><u>Unveiling the Secrets of DTS Virtual X Technology</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
</ul></div>
