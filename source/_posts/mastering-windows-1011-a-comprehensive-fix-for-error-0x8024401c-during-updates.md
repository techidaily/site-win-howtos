---
title: "Mastering Windows 10/11: A Comprehensive Fix for Error 0X8024401c During Updates"
date: 2024-09-24T16:17:57.371Z
updated: 2024-09-28T19:01:14.499Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Mastering Windows 10/11: A Comprehensive Fix for Error 0X8024401c During Updates"
excerpt: "This Article Describes Mastering Windows 10/11: A Comprehensive Fix for Error 0X8024401c During Updates"
thumbnail: https://thmb.techidaily.com/ecfcd073ace7d18c0661d93194869f4c69c9a93b7f7e0b0c3bf6cf212d7d6071.jpg
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
<li><a href="https://some-techniques.techidaily.com/updated-high-def-phones-with-vlogging-extras/"><u>[Updated] High-Def Phones with Vlogging Extras</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-error-2024-on-dota-2-by-modifying-the-rendering-api-a-step-by-step-guide/"><u>Bypass Error 2024 on Dota 2 by Modifying the Rendering API - A Step-by-Step Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-honor-magic-5-lite-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Honor Magic 5 Lite to iPod | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/improve-your-iphone-photography-a-guide-to-overcome-blurriness-with-7-simple-tricks/"><u>Improve Your iPhone Photography: A Guide to Overcome Blurriness with 7 Simple Tricks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ps4-controller-not-charging-heres-how-to-get-it-working-again/"><u>PS4 Controller Not Charging? Here's How to Get It Working Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-code-24-fixing-device-not-found-error-on-windows-1187/"><u>Troubleshooting Code 24: Fixing 'Device Not Found' Error on Windows 11/8/7</u></a></li>
<li><a href="https://android-transfer.techidaily.com/two-ways-to-sync-contacts-from-vivo-v27e-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Two Ways to Sync Contacts from Vivo V27e to Gmail | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-amozekioe11-not-working-heres-how-you-can-repair-it/"><u>Windows Amozekioe11 Not Working? Here's How You Can Repair It</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1899850">
					<video width="486" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1899850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14483-1899850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1899850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:304px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Felectronicx.pxf.io%2Fc%2F5597632%2F1899850%2F14483'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1899850/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

