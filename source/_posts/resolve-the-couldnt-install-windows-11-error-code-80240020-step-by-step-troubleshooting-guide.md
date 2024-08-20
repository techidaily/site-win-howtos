---
title: "Resolve the 'Couldn't Install Windows 11 - Error Code 80240020': Step-by-Step Troubleshooting Guide"
date: 2024-08-19T07:00:23.596Z
updated: 2024-08-20T07:00:23.596Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolve the 'Couldn't Install Windows 11 - Error Code 80240020': Step-by-Step Troubleshooting Guide"
excerpt: "This Article Describes Resolve the 'Couldn't Install Windows 11 - Error Code 80240020': Step-by-Step Troubleshooting Guide"
thumbnail: https://thmb.techidaily.com/a018e8a9f0d428a05e6f8e5f431115fbc243ce5256805ecd4c390c919b578ebe.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-elevating-clarity-optimal-speech-to-text-with-google/"><u>[New] 2024 Approved  Elevating Clarity  Optimal Speech-to-Text with Google</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-from-live-demos-to-recordings-harness-ezvide-power/"><u>[New] 2024 Approved  From Live Demos to Recordings  Harness EZvide Power</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-beginners-pathway-to-effective-video-tag-usage-for-2024/"><u>[New] A Beginner's Pathway to Effective Video Tag Usage for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-beauty-and-inspiration-a-top-20-ig-showcase/"><u>[New] Beauty and Inspiration  A Top 20 IG Showcase</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-how-to-change-facebook-cover-photo/"><u>[New] How to Change Facebook Cover Photo</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-hunters-top-5-video-tools-of-today/"><u>[New] In 2024, Hunters' Top 5 Video Tools of Today</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-inside-the-arsenal-the-complete-review-of-sj-cam-s6-for-2024/"><u>[New] Inside the Arsenal  The Complete Review of SJ-CAM S6 for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-exclusive-list-of-8-best-apps-to-enhance-facebook-likes-for-2024/"><u>[Updated] Exclusive List of 8 Best Apps To Enhance Facebook Likes for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-complete-rankings-of-mobile-apps-altering-your-speech-for-2024/"><u>[Updated] The Complete Rankings of Mobile Apps Altering Your Speech for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-unique-visuals-merge-create-joy-with-photo-collage-for-2024/"><u>[Updated] Unique Visuals Merge  Create Joy with Photo Collage for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unlocking-potential-with-top-pixlr-editing-techniques/"><u>[Updated] Unlocking Potential with Top Pixlr Editing Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/0x80073712-error-code-in-windows-11-solved/"><u>0X80073712 Error Code in Windows 11 [SOLVED]</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-essential-tips-for-monitoring-facebook-live-streams/"><u>2024 Approved  Essential Tips for Monitoring Facebook Live Streams</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exceptional-book-video-examples/"><u>2024 Approved  Exceptional Book Video Examples</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-flawless-footage-with-best-stabilizer-brands/"><u>2024 Approved  Flawless Footage with Best Stabilizer Brands</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ais-premium-convo-boost-chatgpt-plus-unveiled-at-20mo-us-only/"><u>AI's Premium Convo Boost: ChatGPT Plus Unveiled at $20/Mo (US-Only)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/deciphering-the-hurdles-in-teredos-network-connection-process/"><u>Deciphering the Hurdles in Teredo's Network Connection Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dhcp-communication-errors-addressed-what-to-do-when-your-server-wont-respond/"><u>DHCP Communication Errors Addressed: What To Do When Your Server Won't Respond</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolution-strategies-for-a-smooth-origin-gaming-launchpad/"><u>Error Resolution Strategies for a Smooth Origin Gaming Launchpad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-overcoming-the-kb4056892-update-hurdle-on-windows-11-systems-effortlessly/"><u>Expert Advice: Overcoming the KB4056892 Update Hurdle on Windows 11 Systems Effortlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-restoring-functionality-to-a-broken-lenovo-f-key-with-ease/"><u>Expert Advice: Restoring Functionality to a Broken Lenovo F-Key with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-the-driverpowerstatefailure-challenge/"><u>Expert Tips to Overcome the DRIVER_POWER_STATE_FAILURE Challenge</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-and-guide-pubg-building-loading-problems-solved/"><u>Fix & Guide: PUBG Building Loading Problems Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-back-your-racetrack-roar-expert-solutions-for-restoring-sounds-in-forza-horizon-4/"><u>Get Back Your Racetrack Roar: Expert Solutions for Restoring Sounds in Forza Horizon 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208360473-get-your-youtube-sound-back-addressing-and-repairing-audio-renderer-errors-in-windows-1nvite-the-audio-troubleshooting-community-with-expert-tips/"><u>Get Your YouTube Sound Back: Addressing and Repairing Audio Renderer Errors in Windows 1Nvite the Audio Troubleshooting Community with Expert Tips.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-unresponsive-windows-11-after-turning-it-on-a-comprehensive-guide/"><u>How to Address Unresponsive Windows 11 After Turning It On - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unresponsive-number-keys-on-your-keyboard/"><u>How to Fix Unresponsive Number Keys on Your Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-connectivity-with-destiny-2-servers-when-theyre-down/"><u>How to Restore Connectivity with Destiny 2 Servers When They're Down</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-becoming-an-smm-virtuoso-the-ultimate-pathway-of-10-strategic-steps/"><u>In 2024, Becoming an SMM Virtuoso  The Ultimate Pathway of 10 Strategic Steps</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Tecno Spark 20 Pro+? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-activation-lock-on-apple-watch-or-apple-iphone-xr-by-drfone-ios/"><u>In 2024, How To Bypass Activation Lock On Apple Watch Or Apple iPhone XR?</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-honor-x50i-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Honor X50i | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-optimizing-video-flow-for-social-networks/"><u>In 2024, Optimizing Video Flow for Social Networks</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-metaverse-memes-and-diy-humor-mastery/"><u>In 2024, The Ultimate Guide to Metaverse Memes and DIY Humor Mastery</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/netflix-group-watches-unlocked-a-guide-to-syncing-your-views-across-distances/"><u>Netflix Group Watches Unlocked: A Guide to Syncing Your Views Across Distances</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-more-screen-shimmy-win11-improved/"><u>No More Screen Shimmy: Win11 Improved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/out-of-sight-not-out-of-reach-bringing-offscreen-windows-back-into-view/"><u>Out of Sight, Not Out of Reach: Bringing Offscreen Windows Back Into View</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-google-chromes-not-responding-glitches-expert-fix-guide/"><u>Overcoming Google Chrome's 'Not Responding' Glitches – Expert Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-hurdle-of-the-troublesome-windows-error-understanding-and-fixing-0x8000ffff/"><u>Overcoming the Hurdle of the Troublesome Windows Error: Understanding and Fixing 0X8000FFFF</u></a></li>
<li><a href="https://win-howtos.techidaily.com/playing-fortnite-without-support-workaround-for-older-graphic-cards-on-windows/"><u>Playing Fortnite Without Support: Workaround for Older Graphic Cards on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-building-errors-resolved-load-up-without-interruption/"><u>PUBG Building Errors Resolved: Load Up Without Interruption</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-handbook-for-persistent-csgo-game-crashes-step-by-step/"><u>Quick-Fix Handbook for Persistent CSGO Game Crashes – Step by Step</u></a></li>
<li><a href="https://win-howtos.techidaily.com/red-screen-resolved-step-by-step-fix-for-common-software-glitches/"><u>Red Screen Resolved: Step-by-Step Fix for Common Software Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/renderer-startup-problems-heres-how-the-2021-revisions-can-help/"><u>Renderer Startup Problems? Here's How the 2021 Revisions Can Help</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-windows-11-update-error-0xc1900208-step-by-step-tutorial/"><u>Resolve Your Windows 11 Update Error (0xC1900208) - Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-fix-a-persistent-laptop-displaying-only-a-white-screen/"><u>Resolved: How to Fix a Persistent Laptop Displaying Only a White Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-cannot-reset-pc-issue-in-windows-11-a-complete-guide/"><u>Resolving the 'Cannot Reset PC' Issue in Windows 11 – A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/securing-your-software-properly-handling-missing-dlls/"><u>Securing Your Software: Properly Handling Missing DLLs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-restoring-volume-control-on-windows-11-systems/"><u>Solution Guide: Restoring Volume Control on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-game-playability-resolving-windows-driver-issues-for-a-smooth-minecraft-experience/"><u>Solving Game Playability: Resolving Windows Driver Issues for a Smooth Minecraft Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-for-restoring-broken-dell-usb-port-functionality/"><u>Step-by-Step Tutorial for Restoring Broken Dell USB Port Functionality</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/thumbnails-as-a-key-player-in-video-marketing-strategies-for-2024/"><u>Thumbnails as a Key Player in Video Marketing Strategies for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-solve-unwanted-screen-shaking-in-windows-11-expert-tips-and-tricks/"><u>Troubleshoot and Solve Unwanted Screen Shaking in Windows 11 – Expert Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-support-issues-with-fortnite-on-non-compatible-graphics-units-for-windows-gamers/"><u>Troubleshooting and Fixing Support Issues with Fortnite on Non-Compatible Graphics Units for Windows Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-windows-11-brightness-control-issues/"><u>Troubleshooting Guide: Fixing Windows 11 Brightness Control Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-lost-sound-devices-in-windows-1011-expert-fixes/"><u>Troubleshooting Lost Sound Devices in Windows 10/11 - Expert Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-restoring-a-laptop-screen-that-turned-upside-down/"><u>Troubleshooting Tips for Restoring a Laptop Screen That Turned Upside Down</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-10-updates-solutions-for-when-installation-freezes/"><u>Troubleshooting Windows 10 Updates: Solutions for When Installation Freezes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixing-the-right-click-function-on-a-mouse-in-windows-11/"><u>Troubleshooting: Fixing the Right-Click Function on a Mouse in Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unveiling-the-finest-iphone-x876-gif-apps/"><u>Unveiling the Finest iPhone X/8/7/6 GIF Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/voice-modification-gear-top-picks-for-creators-for-2024/"><u>Voice Modification Gear  Top Picks for Creators for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-to-do-if-your-display-device-does-not-recognize-hdcp/"><u>What to Do If Your Display Device Does Not Recognize HDCP?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-perturber-a-la-migration-de-lappareil-solutions-pour-le-probleme-survenu-apres-une-mise-a-jour/"><u>Windows Perturber À La Migration De L'appareil: Solutions Pour Le Problème Survenu Après Une Mise À Jour</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-sleepy-secret-pc-does-not-awake/"><u>Windows' Sleepy Secret - PC Does Not Awake</u></a></li>
<li><a href="https://win-howtos.techidaily.com/yac518-yamahaaturbosound-ii-sound-module-based-on-the-ymf746ymu740-dsp-plus-midi-synthesizer-plus-codec-and-64-mb-of-sram-for-sample-storage-instead-of-rom-96/"><u>YAC518 - Yamaha'aturboSound II Sound Module Based on the YMF746/YMU740 (DSP + MIDI Synthesizer + Codec) and 64 MB of SRAM for Sample Storage Instead of ROM. It Also Includes a Second Audio Input Connector</u></a></li>
</ul></div>
