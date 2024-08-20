---
title: "Detailed Instructions: How to Tackle and Resolve Black Screen Errors on Your Dell System"
date: 2024-08-19T06:51:58.731Z
updated: 2024-08-20T06:51:58.731Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Detailed Instructions: How to Tackle and Resolve Black Screen Errors on Your Dell System"
excerpt: "This Article Describes Detailed Instructions: How to Tackle and Resolve Black Screen Errors on Your Dell System"
thumbnail: https://thmb.techidaily.com/e5cf76fbd383eaf326a40e9f47ba567bbfc7a691177fb2bbb8430f5442ba8e06.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-your-step-by-step-approach-to-youtube-copyright-mastery/"><u>[New] 2024 Approved  Your Step-by-Step Approach to YouTube Copyright Mastery</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-halt-youtube-suggested-content-now-for-2024/"><u>[New] Halt YouTube Suggested Content Now for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-the-professionals-guide-to-innovative-360-cams-2023/"><u>[New] The Professionals’ Guide to Innovative 360° Cams, 2023</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-efficient-practices-archiving-google-voice-transcripts/"><u>[Updated] 2024 Approved  Efficient Practices  Archiving Google Voice Transcripts</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-avoid-buffering-switch-av1-codec-on-youtube/"><u>[Updated] Avoid Buffering  Switch AV1 Codec on YouTube</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>5 Best Route Generator Apps You Should Try On Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corrected-non-hid-interactive-capability-in-touch-screen/"><u>Corrected Non-HID Interactive Capability in Touch Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corrective-steps-for-desktop-is-unreachable-under-cwindowssystem32configsystemprofile/"><u>Corrective Steps for 'Desktop Is Unreachable' Under C:\\Windows\\System32\\Config\\SystemProfile</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-the-malfunctioning-spacebar-in-your-windows-11-pc/"><u>Diagnosing and Repairing the Malfunctioning Spacebar in Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-repair-handling-a-missing-bootmgr-error-smoothly-comprehensive-guide-with-images/"><u>DIY Repair: Handling a 'Missing Bootmgr' Error Smoothly - Comprehensive Guide With Images</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dns-server-not-responding-4-easy-solutions/"><u>DNS Server Not Responding (4 Easy Solutions)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-repairing-unresponsive-functional-keys-on-lenovo-computers/"><u>Effective Solutions for Repairing Unresponsive Functional Keys on Lenovo Computers</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-choice-top-10-video-subtitles-editors-online-for-2024/"><u>Expert Choice  Top 10 Video Subtitles Editors Online for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-correcting-the-persistent-144-livekernelevent-glitch/"><u>Expert Tips for Correcting the Persistent 144 LiveKernelEvent Glitch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-unresponsive-usb-devices-and-descriptor-request-issues-resolved/"><u>Expert Tips for Repairing Unresponsive USB Devices and Descriptor Request Issues [Resolved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-it-overcoming-the-challenge-of-an-unresponsive-backspace-button/"><u>Fix It! Overcoming the Challenge of an Unresponsive Backspace Button</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722901225017-get-the-scoop-anticipated-details-about-apples-upcoming-annulus-product-price-and-release-date-revealed/"><u>Get the Scoop: Anticipated Details About Apple's Upcoming Annulus Product – Price & Release Date Revealed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-fixing-windows-error-1067-the-process-ended-suddenly-and-how-we-resolved-it/"><u>Guide: Fixing Windows Error 1#067 – The Process Ended Suddenly & How We Resolved It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/halo-e-4-unreal-engine-glitches-how-to-fix-the-critical-errors-edition/"><u>Halo E 4 Unreal Engine Glitches: How to Fix the Critical Errors Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/handling-temporary-failures-in-reaching-windows-smartscreen-for-safety-checks/"><u>Handling Temporary Failures in Reaching Windows SmartScreen for Safety Checks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unresponsive-scroll-wheel-issue-on-windows-10-laptop/"><u>How to Fix Unresponsive Scroll Wheel Issue on Windows 10 Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-your-computer-when-it-gets-stuck-during-windows-setup/"><u>How to Fix Your Computer When It Gets Stuck During Windows Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-back-online-dealing-with-inaccessible-valve-network-servers/"><u>How To Get Back Online: Dealing With Inaccessible Valve Network Servers</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-oppo-k11-5g-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Oppo K11 5G Without PUK Codes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-choosing-the-best-screen-capture-app-obs-vs-fraps/"><u>In 2024, Choosing the Best Screen Capture App – OBS vs Fraps</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-parallel-audio-stream-mapping/"><u>In 2024, Parallel Audio Stream Mapping</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-unlocking-viral-potential-creating-captivating-instagram-puzzles/"><u>In 2024, Unlocking Viral Potential  Creating Captivating Instagram Puzzles</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-watching-the-future-on-screen-androids-2023-update-on-vr/"><u>In 2024, Watching the Future on Screen - Android's 2023 Update on VR</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211287030-innovative-solutions-stop-the-halt-on-your-hamachi-connection-now/"><u>Innovative Solutions: Stop the Halt on Your Hamachi Connection Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/logildadll-recovery-made-easy/"><u>LogiLDA.dll Recovery Made Easy</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-the-ultimate-list-best-free-online-video-editing-software/"><u>New 2024 Approved The Ultimate List Best Free Online Video Editing Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-1class-not-registered-hurdle-tips-and-tricks-successfully-implemented/"><u>Overcoming Windows 1#Class Not Registered Hurdle: Tips and Tricks Successfully Implemented</u></a></li>
<li><a href="https://win-howtos.techidaily.com/remedy-for-erroneous-character-input-on-keyboards/"><u>Remedy for Erroneous Character Input on Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-cpu-load-caused-by-wudfhostexe-on-windows-10/"><u>Resolve Excessive CPU Load Caused by wudfhost.exe on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-ps4-nat-problems-a-comprehensive-step-by-step-fixing-guide/"><u>Resolve Your PS4 NAT Problems: A Comprehensive Step-by-Step Fixing Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/revamp-your-pcs-performance-a-comprehensive-tutorial-for-windows-n-update-drivers-using-revouninstaller/"><u>Revamp Your PC's Performance: A Comprehensive Tutorial for Windows N Update Drivers Using RevoUninstaller</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-for-lenovos-stuck-fn-key-fast-and-simple-fixes/"><u>Solution Steps for Lenovo's Stuck FN Key - Fast and Simple Fixes!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-minecraft-crashes-stemming-from-outdated-or-corrupted-windows-vga-drivers/"><u>Step-by-Step Solutions for Minecraft Crashes Stemming From Outdated or Corrupted Windows VGA Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-overcoming-windows-11-update-installation-hurdles-a-comprehensive-guide/"><u>Successfully Overcoming Windows 11 Update Installation Hurdles – A Comprehensive Guide</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-oppo-reno-9a-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Oppo Reno 9A Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-8-solutions-to-overcome-the-windows-11-update-error-code-0x800f0922/"><u>Top 8 Solutions to Overcome the Windows 11 Update Error CODE 0X800F0922</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-fix-steam-server-not-reachable-issue/"><u>Troubleshooting Guide: How To Fix 'Steam Server Not Reachable' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-uac-requirements-handling-elevated-permissions-on-windows-versions/"><u>Understanding UAC Requirements: Handling Elevated Permissions on Windows Versions</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-premier-digital-audio-editor-for-2024/"><u>Updated Premier Digital Audio Editor for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-update-glitch-beat-error-8007000e-now-with-simple-fixes/"><u>Windows Update Glitch? Beat Error 8007000E Now with Simple Fixes!</u></a></li>
</ul></div>
