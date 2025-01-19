---
title: Step-by-Step Tutorial to Correctly Install Windows 11 Despite Encountering Error Code 80240020
date: 2025-01-16T20:19:33.390Z
updated: 2025-01-19T19:22:18.698Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Tutorial to Correctly Install Windows 11 Despite Encountering Error Code 80240020
excerpt: This Article Describes Step-by-Step Tutorial to Correctly Install Windows 11 Despite Encountering Error Code 80240020
thumbnail: https://thmb.techidaily.com/e68430bcb106e10e6ed671e16682f01d022f0799c626556c343ddc595fa9cde5.jpg
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

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
<li><a href="https://facebook-video-recording.techidaily.com/new-quiet-browsing-of-fb-narratives/"><u>[New] Quiet Browsing of FB Narratives</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-excellent-quality-hd-video-preservers/"><u>[Updated] 2024 Approved Excellent Quality HD Video Preservers</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-become-a-shorts-connoisseur-must-know-facts/"><u>[Updated] In 2024, Become a Shorts Connoisseur Must-Know Facts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719342757489-commanding-your-digital-files-linking-dropbox-googledrive-to-c/"><u>Commanding Your Digital Files: Linking Dropbox, GoogleDrive to C:</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/connectivity-wonders-switchs-usb-and-bluetooth-unveiled-100-chars/"><u>Connectivity Wonders: Switch's USB and Bluetooth Unveiled (100 Chars)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-correcting-the-port-reset-failed-warning-for-your-usb-gadget-in-windows-10/"><u>Expert Advice: Correcting the 'Port Reset Failed' Warning for Your USB Gadget in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-infinite-load-ultimate-guide-to-overcoming-stuck-screens-in-valorant/"><u>Fixing the Infinite Load: Ultimate Guide to Overcoming Stuck Screens in Valorant</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-no-audio-device-installed-error-in-windows-operating-systems/"><u>How to Resolve No Audio Device Installed Error in Windows Operating Systems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-vivo-y100i-power-5g-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Vivo Y100i Power 5G to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-mouse-pad-not-responding-heres-how-you-can-fix-it-on-any-window-os/"><u>Lenovo Mouse Pad Not Responding? Here's How You Can Fix It on Any Window OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-device-recognition-issues-bluetooth-setup-fixed-in-windows-11/"><u>Overcoming Device Recognition Issues: Bluetooth Setup Fixed in Windows 11</u></a></li>
<li><a href="https://win-net.techidaily.com/recovering-lost-audio-files-a-comprehensive-guide-for-windows-and-ios-users/"><u>Recovering Lost Audio Files: A Comprehensive Guide for Windows and iOS Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-steelseries-arctis-5-mic-expert-solutions-to-get-it-working-again/"><u>Revive Your SteelSeries Arctis 5 Mic: Expert Solutions to Get It Working Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-how-to-resolve-problems-when-trying-to-cast-devices/"><u>Windows 11: How to Resolve Problems When Trying to Cast Devices</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

