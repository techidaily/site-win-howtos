---
title: "Fixing Missing DLLs: The Definitive Guide for Windows 10 Class Registration Issues"
date: 2024-10-19T20:35:34.272Z
updated: 2024-10-21T20:39:01.693Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing Missing DLLs: The Definitive Guide for Windows 10 Class Registration Issues"
excerpt: "This Article Describes Fixing Missing DLLs: The Definitive Guide for Windows 10 Class Registration Issues"
thumbnail: https://thmb.techidaily.com/ebac8749de86200184a77a3fa2bb901785d67bf12335ea2d0dc0b871ccf2113a.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-earnings-escalation-via-youtube-channel-initiatives/"><u>[New] 2024 Approved Earnings Escalation via YouTube Channel Initiatives</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-emancipate-your-engagement-facebook-restored-for-2024/"><u>[New] Emancipate Your Engagement Facebook Restored for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-swift-screen-capture-with-your-idevice/"><u>[Updated] In 2024, Swift Screen Capture with Your iDevice</u></a></li>
<li><a href="https://games-able.techidaily.com/aligning-your-entertainment-budget-with-ps5-plans/"><u>Aligning Your Entertainment Budget with PS5 Plans</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/blurring-the-focus-bokeh-wonders-in-stories-for-2024/"><u>Blurring the Focus Bokeh Wonders in Stories for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/desktop-icon-disappearance-issue-in-windows-11-solution-steps/"><u>Desktop Icon Disappearance Issue in Windows 11 - Solution Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fix-for-non-functional-volume-keys-in-windows-11-operating-system/"><u>Easy Fix for Non-Functional Volume Keys in Windows 11 Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhancing-visual-performance-adaptive-refresh-rates-for-todays-displays/"><u>Enhancing Visual Performance: Adaptive Refresh Rates for Today’s Displays</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1726029838563-gif/"><u>GIFアニメの強化と改良手順：簡単ガイド</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-pubg-launch-a-step-by-step-guide-for-seamless-play-in-the-2024-version/"><u>Mastering PUBG Launch: A Step-by-Step Guide for Seamless Play in the 2024 Version</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restoring-the-bluetooth-symbol-on-your-windows-10-system-a-step-by-step-guide/"><u>Restoring the Bluetooth Symbol on Your Windows 10 System: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-surface-pro-4-stylus-issues/"><u>Troubleshooting Guide: Fixing Surface Pro 4 Stylus Issues</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleash-creative-freedom-crafting-your-own-insta-tones/"><u>Unleash Creative Freedom Crafting Your Own Insta Tones</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484951/16446" target="_top" id="1484951">
  <img src="//a.impactradius-go.com/display-ad/16446-1484951" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484951/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

