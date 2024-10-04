---
title: Error 80240020 on Your PC? Here's How to Successfully Install Windows 10
date: 2024-09-29T08:47:07.398Z
updated: 2024-10-04T04:40:54.987Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Error 80240020 on Your PC? Here's How to Successfully Install Windows 10
excerpt: This Article Describes Error 80240020 on Your PC? Here's How to Successfully Install Windows 10
thumbnail: https://thmb.techidaily.com/1501cba3c5f4c4b803b623584f546bd1f9723b8ea081222f679c45ec271effc3.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

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
<li><a href="https://desktop-recording.techidaily.com/new-game-changing-strategies-for-effective-video-capture-for-2024/"><u>[New] Game-Changing Strategies for Effective Video Capture for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-top-12-wildlife-wonders-for-your-android-device/"><u>2024 Approved Top 12 Wildlife Wonders for Your Android Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207222250-accelerate-your-league-of-legends-installations-no-more-sluggish-downloads/"><u>Accelerate Your League of Legends Installations: No More Sluggish Downloads!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-setting-up-your-microsoft-wireless-display-adapter-for-optimal-performance-on-windows-10-devices/"><u>Expert Advice on Setting Up Your Microsoft Wireless Display Adapter for Optimal Performance on Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hit-compliant-resolution-enhanced-missing-touch-sensitivity/"><u>HIT Compliant Resolution - Enhanced Missing Touch Sensitivity</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-are-apples-new-processors-revolutionizing-editing-tech/"><u>In 2024, Are Apple's New Processors Revolutionizing Editing Tech?</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-provide-information-to-the-audience-with-the-perfect-graphic-elements-it-is-high-time-to-add-value-to-your-video-step-into-this-article-to-get-insig/"><u>In 2024, Provide Information to the Audience with the Perfect Graphic Elements. It Is High Time to Add Value to Your Video. Step Into This Article to Get Insights on the Lower Third Modules</u></a></li>
<li><a href="https://article-files.techidaily.com/initiate-integrate-and-interact-the-basics-of-zoom-for-android/"><u>Initiate, Integrate, and Interact The Basics of Zoom for Android</u></a></li>
<li><a href="https://win-howtos.techidaily.com/startup-issues-resolved-for-your-troubled-computing-device/"><u>Startup Issues Resolved for Your Troubled Computing Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-errors-resolving-failed-to-load-in-hardware-monitor-drivers/"><u>Troubleshooting Errors: Resolving 'Failed to Load' In Hardware Monitor Drivers</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-honor-x50-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Honor X50 | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

