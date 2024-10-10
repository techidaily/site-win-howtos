---
title: Resolving Windows 10 Explorer's Unwanted Scroll-to-Top Behavior for Seamless Navigation
date: 2024-10-06T23:15:36.234Z
updated: 2024-10-09T22:13:45.195Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Windows 10 Explorer's Unwanted Scroll-to-Top Behavior for Seamless Navigation
excerpt: This Article Describes Resolving Windows 10 Explorer's Unwanted Scroll-to-Top Behavior for Seamless Navigation
thumbnail: https://thmb.techidaily.com/a208b6b47f62fc53f6719bf37fb44710d3bca87f00271cab6e02272f4110e26d.jpg
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-elevating-videogame-recording-the-steam-methodology/"><u>[New] 2024 Approved Elevating Videogame Recording The Steam Methodology</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-battle-of-accessible-viewerships-google-vs-samsung-headsets/"><u>[New] The Battle of Accessible Viewerships Google Vs. Samsung Headsets</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-rapid-accessibility-of-instagram-videos-and-stories/"><u>[Updated] In 2024, Rapid Accessibility of Instagram Videos and Stories</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-virtual-horizons-10-cinematic-escapes-into-sci-fi-metaverses/"><u>[Updated] In 2024, Virtual Horizons 10 Cinematic Escapes Into Sci-Fi Metaverses</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-exploring-hottest-ae-template-trends-on-ig/"><u>2024 Approved Exploring Hottest AE Template Trends on IG</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-navigating-the-new-youtube-earnings-landscape/"><u>2024 Approved Navigating the New YouTube Earnings Landscape</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209925826-astro-a40-microphone-not-working-heres-what-you-need-to-know/"><u>Astro A40 Microphone Not Working? Here's What You Need to Know!</u></a></li>
<li><a href="https://extra-resources.techidaily.com/creating-a-unified-multimedia-experience-on-iphone/"><u>Creating a Unified Multimedia Experience on iPhone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-fix-your-oculus-gear-problems-2024-update/"><u>Effective Solutions to Fix Your Oculus Gear Problems – 2024 Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-damaged-windows-store-caches-solved/"><u>Expert Tips for Fixing Damaged Windows Store Caches - SOLVED!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-nonfunctional-lenovo-mouse-pad-in-various-windows-systems-windows-10-8-and-7/"><u>Fixing a Nonfunctional Lenovo Mouse Pad in Various Windows Systems [Windows 10, 8 & 7]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hid-requirement-corrected-missing-touch-functionality-on-device/"><u>HID Requirement - Corrected Missing Touch Functionality on Device</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-use-special-features-virtual-location-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On OnePlus Ace 2V? | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-sprout-ultimate-guide-to-capturing-your-desktop/"><u>In 2024, Sprout Ultimate Guide to Capturing Your Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-driver-problems-making-your-wd-my-passport-ultra-visible-in-windows/"><u>Overcoming Driver Problems: Making Your WD My Passport Ultra Visible in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-audio-on-steam-effective-and-swift-methods-for-gamers/"><u>Revive Audio on Steam: Effective & Swift Methods for Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-fix-a-non-responsive-corsair-keyboard/"><u>Troubleshooting Guide: How To Fix a Non-Responsive Corsair Keyboard</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144277/7443" target="_top" id="2144277">
  <img src="//a.impactradius-go.com/display-ad/7443-2144277" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144277/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

