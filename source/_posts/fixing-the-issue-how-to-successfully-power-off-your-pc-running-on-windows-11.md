---
title: "Fixing the Issue: How to Successfully Power Off Your PC Running on Windows 11"
date: 2024-10-12T20:22:16.898Z
updated: 2024-10-15T21:04:05.297Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the Issue: How to Successfully Power Off Your PC Running on Windows 11"
excerpt: "This Article Describes Fixing the Issue: How to Successfully Power Off Your PC Running on Windows 11"
thumbnail: https://thmb.techidaily.com/c9af2386c6798b3575f6d66e9544981a45984b6b6be55d294d273187d6f5f1e2.jpg
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
<li><a href="https://article-helps.techidaily.com/new-stream-selection-simplified-top-10-actionable-tips/"><u>[New] Stream Selection Simplified Top 10 Actionable Tips</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-your-makeup-maestro-journey-establishing-a-channel-for-beauty-buffs/"><u>[Updated] Your Makeup Maestro Journey Establishing a Channel for Beauty Buffs</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-unparalleled-quality-discover-the-best-8-streamer-cameras/"><u>2024 Approved Unparalleled Quality Discover the Best 8 Streamer Cameras</u></a></li>
<li><a href="https://vp-tips.techidaily.com/beginners-guide-the-ultimate-list-of-7-vital-websites-every-aspiring-developer-should-explore/"><u>Beginners' Guide: The Ultimate List of 7 Vital Websites Every Aspiring Developer Should Explore</u></a></li>
<li><a href="https://win-hacks.techidaily.com/build-more-than-22-web-applications-mastering-vue-laravel-and-json-api-techniques-with-insights-from-creative-tim/"><u>Build More than 22 Web Applications: Mastering Vue, Laravel, and JSON API Techniques with Insights From Creative Tim</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-solving-usb-functionality-problems-in-modern-windows-environments/"><u>Diagnosing and Solving USB Functionality Problems in Modern Windows Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easily-resolve-the-notorious-error-code-0x800f081f-in-your-net-framework-35-installation/"><u>Easily Resolve the Notorious Error Code 0X800F081F in Your .NET Framework 3.5 Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-failed-graphics-driver-d3derrnotavailable-quickly/"><u>How to Fix a Failed Graphics Driver (D3DERR_NOTAVAILABLE) Quickly</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-look-at-the-lenovo-ideapad-functional-and-well-built-laptops-unveiled/"><u>In Depth Look at the Lenovo IdeaPad: Functional and Well-Built Laptops Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-airpod-windows-sync-advanced-tips-to-resolve-connections/"><u>Master AirPod-Windows Sync: Advanced Tips to Resolve Connections</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-top-8-animated-audio-tracks-for-creatives-free-downloads/"><u>New In 2024, Top 8 Animated Audio Tracks for Creatives Free Downloads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-guide-resolving-delayed-shutdown-problems-in-windows-10/"><u>Quick Fix Guide: Resolving Delayed Shutdown Problems in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-email-characters-glitch-fixing-a-broken-key/"><u>Resolve Email Characters Glitch: Fixing a Broken '@' Key</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

