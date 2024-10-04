---
title: Solutions for Fixing a Non-Responsive Windows 11 Start Button and Menu
date: 2024-10-02T16:00:51.305Z
updated: 2024-10-04T16:00:51.451Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solutions for Fixing a Non-Responsive Windows 11 Start Button and Menu
excerpt: This Article Describes Solutions for Fixing a Non-Responsive Windows 11 Start Button and Menu
thumbnail: https://thmb.techidaily.com/4f82ef6a5653e12bb243abaaf90bd8a672c270d2a21f27f2fda0ba3002b69992.jpg
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-insta-explosion-supercharge-with-content-likes-and-videos/"><u>[New] 2024 Approved Insta Explosion Supercharge with Content, Likes & Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-stepwise-strategy-for-perfectly-curating-videos-in-your-youtube-playlists/"><u>[New] Stepwise Strategy for Perfectly Curating Videos in Your YouTube Playlists</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-sony-x1000d-vivid-full-action-cam-test/"><u>[Updated] 2024 Approved Sony X1000D Vivid - Full Action Cam Test</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-quick-guide-to-screen-capture-on-laptops-and-chromeos/"><u>2024 Approved Quick Guide to Screen Capture on Laptops and ChromeOS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/aipc/"><u>無料AIアプリで一枚絵が生きる！PCとスマホ向けに最適な動画化方法</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-resolve-google-chrome-hanging-issues-and-restart-promptly/"><u>Expert Tips to Resolve Google Chrome Hanging Issues and Restart Promptly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-non-responsive-spacebar-issue-in-windows-10-a-step-by-step-guide/"><u>Fixing the Non-Responsive Spacebar Issue in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205979411-function-lock-key-not-working-heres-how-you-can-solve-it/"><u>Function Lock Key Not Working? Here's How You Can Solve It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-resolving-dell-webcam-issues-on-the-windows-operating-system/"><u>Guide to Resolving Dell Webcam Issues on the Windows Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-hp-notebook-webcam-errors-in-the-latest-windows-11-operating-system/"><u>How to Repair HP Notebook Webcam Errors in the Latest Windows 11 Operating System</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-low-memory-issues-solutions-for-an-uninterrupted-god-of-war-adventure/"><u>Overcoming Low Memory Issues - Solutions for an Uninterrupted God of War Adventure</u></a></li>
<li><a href="https://os-tips.techidaily.com/secure-your-privacy-the-ultimate-3-step-guide-to-total-iphone-data-deletion/"><u>Secure Your Privacy: The Ultimate 3-Step Guide to Total iPhone Data Deletion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-to-fix-the-d3derrnotavailable-graphics-card-problem/"><u>Solutions to Fix the D3DERR_NotAvailable Graphics Card Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-laptop-trackpad-issues-on-windows-11-a-comprehensive-fix/"><u>Troubleshooting Laptop Trackpad Issues on Windows 11 - A Comprehensive Fix</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-guide-solving-phantom-issues-in-your-3d-printed-creations/"><u>Ultimate Guide: Solving Phantom Issues in Your 3D Printed Creations</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

