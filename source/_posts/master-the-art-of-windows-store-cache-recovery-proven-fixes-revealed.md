---
title: Master the Art of Windows Store Cache Recovery - Proven Fixes Revealed
date: 2024-08-19T07:07:50.086Z
updated: 2024-08-20T07:07:50.086Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Master the Art of Windows Store Cache Recovery - Proven Fixes Revealed
excerpt: This Article Describes Master the Art of Windows Store Cache Recovery - Proven Fixes Revealed
thumbnail: https://thmb.techidaily.com/59c3843adcf6e65abddadc6ccd38abd83d01c075541dbef1c38bbe62a795e13b.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://article-posts.techidaily.com/new-in-2024-how-to-activate-auto-hdr-setting-in-windows-11/"><u>[New] In 2024, How to Activate Auto HDR Setting in Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-powerpoint-presentation-soundtracking-secrets/"><u>[New] PowerPoint Presentation Soundtracking Secrets</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-enhance-video-rankings-on-youtube-through-seo/"><u>[Updated] In 2024, How to Enhance Video Rankings on YouTube Through SEO</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-streamline-your-binge-sessions-leveraging-the-power-of-pip-on-netflix/"><u>[Updated] Streamline Your Binge Sessions  Leveraging the Power of PIP on Netflix</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-look-into-magix-graphic-designer/"><u>2024 Approved  A Look Into MAGIX Graphic Designer</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-elite-upgrades-for-enhanced-gopro-images/"><u>2024 Approved  Elite Upgrades for Enhanced GoPro Images</u></a></li>
<li><a href="https://fox-http.techidaily.com/best-free-live-streaming-software-and-app-for-all-platforms-for-2024/"><u>Best Free Live Streaming Software and App for All Platforms for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corrected-non-hid-interactive-capability-in-touch-screen/"><u>Corrected Non-HID Interactive Capability in Touch Screen</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/cut-to-the-chase-guide-for-gopro-4k-mastery/"><u>Cut-to-the-Chase Guide for GoPro 4K Mastery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-the-malfunctioning-spacebar-in-your-windows-11-pc/"><u>Diagnosing and Repairing the Malfunctioning Spacebar in Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dns-server-not-responding-4-easy-solutions/"><u>DNS Server Not Responding (4 Easy Solutions)</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/empower-everyday-narratives-free-extensions-and-mobile-magic-for-2024/"><u>Empower Everyday Narratives – Free Extensions & Mobile Magic for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolution-overcoming-the-0x887a0006-issue-with-simple-steps/"><u>Error Resolution - Overcoming the 0X887A0006 Issue with Simple Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-unresponsive-usb-devices-and-descriptor-request-issues-resolved/"><u>Expert Tips for Repairing Unresponsive USB Devices and Descriptor Request Issues [Resolved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-it-overcoming-the-challenge-of-an-unresponsive-backspace-button/"><u>Fix It! Overcoming the Challenge of an Unresponsive Backspace Button</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-laptop-trackball-issues-on-windows-10-8-and-7-solutions-revealed/"><u>Fix Laptop Trackball Issues on Windows 10, 8 & 7 – Solutions Revealed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-failed-feature-installation-on-windows-10-version-1607/"><u>Fixing Failed Feature Installation on Windows 10 Version 1607</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/concept-to-screen-channel-yt-for-pioneering-filmmaking-techniques-for-2024/"><u>From Concept to Screen  Channel YT for Pioneering Filmmaking Techniques for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-oneplus-ace-2v-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your OnePlus Ace 2V to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-fixing-windows-error-1067-the-process-ended-suddenly-and-how-we-resolved-it/"><u>Guide: Fixing Windows Error 1#067 – The Process Ended Suddenly & How We Resolved It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/halo-e-4-unreal-engine-glitches-how-to-fix-the-critical-errors-edition/"><u>Halo E 4 Unreal Engine Glitches: How to Fix the Critical Errors Edition</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-on-iphone-13-pro-with-or-without-password-by-drfone-ios/"><u>How To Change Your Apple ID on iPhone 13 Pro With or Without Password</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unresponsive-scroll-wheel-issue-on-windows-10-laptop/"><u>How to Fix Unresponsive Scroll Wheel Issue on Windows 10 Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-your-computer-when-it-gets-stuck-during-windows-setup/"><u>How to Fix Your Computer When It Gets Stuck During Windows Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-back-online-dealing-with-inaccessible-valve-network-servers/"><u>How To Get Back Online: Dealing With Inaccessible Valve Network Servers</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-on-iphone-6s-plus-without-password-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account On iPhone 6s Plus without Password?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-reset-itunes-backup-password-of-apple-iphone-12-mini-prevention-and-solution-by-drfone-ios/"><u>In 2024, Reset iTunes Backup Password Of Apple iPhone 12 mini Prevention & Solution</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-top-6-best-8k-cameras/"><u>In 2024, Top 6 Best 8K Cameras</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unleashing-creativity-a-guide-to-innovative-gopro-video-editing/"><u>In 2024, Unleashing Creativity  A Guide to Innovative GoPro Video Editing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211287030-innovative-solutions-stop-the-halt-on-your-hamachi-connection-now/"><u>Innovative Solutions: Stop the Halt on Your Hamachi Connection Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/logildadll-recovery-made-easy/"><u>LogiLDA.dll Recovery Made Easy</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-problem-of-windows-10-prolonged-shutdown-periods/"><u>Overcoming the Problem of Windows 10 Prolonged Shutdown Periods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-1class-not-registered-hurdle-tips-and-tricks-successfully-implemented/"><u>Overcoming Windows 1#Class Not Registered Hurdle: Tips and Tricks Successfully Implemented</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-cpu-load-caused-by-wudfhostexe-on-windows-10/"><u>Resolve Excessive CPU Load Caused by wudfhost.exe on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-ps4-nat-problems-a-comprehensive-step-by-step-fixing-guide/"><u>Resolve Your PS4 NAT Problems: A Comprehensive Step-by-Step Fixing Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-for-lenovos-stuck-fn-key-fast-and-simple-fixes/"><u>Solution Steps for Lenovo's Stuck FN Key - Fast and Simple Fixes!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-minecraft-crashes-stemming-from-outdated-or-corrupted-windows-vga-drivers/"><u>Step-by-Step Solutions for Minecraft Crashes Stemming From Outdated or Corrupted Windows VGA Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-chrome-freeze-issue-for-windows-users/"><u>Tackling Chrome Freeze Issue for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-troubled-windows-registry-with-effective-solutions/"><u>Tackling Troubled Windows Registry with Effective Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-windows-1011s-damaged-system-files/"><u>Ultimate Guide: Resolving Windows 10/11'S Damaged System Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-update-glitch-beat-error-8007000e-now-with-simple-fixes/"><u>Windows Update Glitch? Beat Error 8007000E Now with Simple Fixes!</u></a></li>
</ul></div>
