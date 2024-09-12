---
title: Step-by-Step Solutions to Correctly Resolve Code 0X8024402c in Windows Update
date: 2024-09-11T15:28:25.845Z
updated: 2024-09-12T15:28:25.845Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions to Correctly Resolve Code 0X8024402c in Windows Update
excerpt: This Article Describes Step-by-Step Solutions to Correctly Resolve Code 0X8024402c in Windows Update
thumbnail: https://thmb.techidaily.com/1950983d0af24cf7ccce7d0d9b553dd604417e3bd4a6dbac12c3df842a2a8fe2.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-videography-secrets-leveraging-strikethrough-for-impactful-edits/"><u>[New] In 2024, Videography Secrets Leveraging Strikethrough for Impactful Edits</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-huawei-p10-review/"><u>[Updated] 2024 Approved Huawei P10 Review</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-iphone-photography-breakthroughs-with-lifelike-motion/"><u>2024 Approved IPhone Photography Breakthroughs with Lifelike Motion</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-motorola-razr-40-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Motorola Razr 40 without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0x800705b4-the-ultimate-solutions-for-windows-1n-update-issues/"><u>Error 0X800705B4: The Ultimate Solutions for Windows 1N Update Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-resolving-failed-updates-in-your-favorite-game-warframe/"><u>Expert Advice on Resolving Failed Updates in Your Favorite Game, Warframe</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-on-win-xpvista7-backup-reset-procedure/"><u>Guide on Win XP/Vista/7 Backup Reset Procedure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-tips-navigating-and-using-file-explorer-on-windows-11-seamlessly/"><u>Quick Tips: Navigating and Using File Explorer on Windows 11 Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revival-tactics-restoring-microsoft-store-on-win-11-and-11/"><u>Revival Tactics: Restoring Microsoft Store on Win 11 & 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/taming-soundscapes-mastering-gradual-volume-increase-with-audition/"><u>Taming Soundscapes Mastering Gradual Volume Increase with Audition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-cache-miss-error-errcachemiss-in-google-chrome-easily/"><u>Troubleshooting the Cache Miss Error (ERR_CACHE_MISS) in Google Chrome Easily</u></a></li>
<li><a href="https://extra-information.techidaily.com/unveiling-vr-the-creation-gap/"><u>Unveiling VR The Creation Gap</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-does-my-computer-freeze-with-windows-11-learn-the-fixes/"><u>Why Does My Computer Freeze with Windows 11? Learn the Fixes!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-performance-boost-tackling-high-cpu-drain-by-svchostexe-guide/"><u>Windows 10 Performance Boost: Tackling High CPU Drain by svchost.exe [Guide]</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1982462">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982462%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982462/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

