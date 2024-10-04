---
title: "Resolved Issue: Fixing Error 1053 – Service Unresponsive on Start or Command"
date: 2024-10-01T22:17:26.941Z
updated: 2024-10-03T19:58:24.462Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved Issue: Fixing Error 1053 – Service Unresponsive on Start or Command"
excerpt: "This Article Describes Resolved Issue: Fixing Error 1053 – Service Unresponsive on Start or Command"
thumbnail: https://thmb.techidaily.com/f75585e4daf78953dd0ce1cfd0b26209fab1e9c588003fe7de564148a8e3e23c.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-capturing-top-notch-audio-without-microphone-dependency/"><u>[New] 2024 Approved Capturing Top-Notch Audio Without Microphone Dependency</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-cutting-edge-techniques-in-image-fusion/"><u>[New] 2024 Approved Cutting-Edge Techniques in Image Fusion</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-expert-guide-to-optimal-tripod-setup-for-high-quality-vlogs-for-2024/"><u>[New] Expert Guide to Optimal Tripod Setup for High-Quality Vlogs for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-apple-iphone-se-without-anyone-knowing-drfone-by-drfone-virtual-ios/"><u>4 Methods to Turn off Life 360 On Apple iPhone SE without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-motorola-edge-2023-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-dealing-with-windows-camera-malfunction-error-0xa00f4292-resolved/"><u>Expert Tips for Dealing with Windows Camera Malfunction - Error 0xA00F4292 Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-for-not-charging-issue-when-device-connected-to-a-windows-7-or-10-computer/"><u>Fixes for 'Not Charging' Issue When Device Connected to a Windows 7 or 10 Computer</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-data-from-iphone-11-pro-to-other-iphone-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 11 Pro To Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamlined-techniques-for-transforming-vids-on-pinterest-to-mp3s/"><u>In 2024, Streamlined Techniques for Transforming Vids on Pinterest to MP3s</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-casting-on-windows-10-tips-and-tricks-for-seamless-device-connectivity/"><u>Master the Art of Casting on Windows 10: Tips and Tricks for Seamless Device Connectivity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/missing-device-drivers-how-to-fix-when-your-pc-lacks-essential-media-software/"><u>Missing Device Drivers: How to Fix When Your PC Lacks Essential Media Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-what-to-do-when-your-xbox-one-controller-wont-sync/"><u>Step-by-Step Solution: What to Do When Your Xbox One Controller Won't Sync</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-non-responsive-function-key-issues/"><u>Troubleshooting and Fixing Non-Responsive Function Key Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-overcome-windows-11s-update-error-0xc19n0208/"><u>Troubleshooting Guide: How to Overcome Windows 11'S Update Error 0Xc19n0208</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

