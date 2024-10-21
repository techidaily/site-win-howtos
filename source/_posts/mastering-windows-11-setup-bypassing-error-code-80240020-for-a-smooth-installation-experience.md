---
title: "Mastering Windows 11 Setup: Bypassing Error Code 80240020 for a Smooth Installation Experience"
date: 2024-10-20T17:42:09.233Z
updated: 2024-10-21T17:29:19.098Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Mastering Windows 11 Setup: Bypassing Error Code 80240020 for a Smooth Installation Experience"
excerpt: "This Article Describes Mastering Windows 11 Setup: Bypassing Error Code 80240020 for a Smooth Installation Experience"
thumbnail: https://thmb.techidaily.com/2efc75770914ae3db1b269aa438526aea2b37f029f972da8e465d2fb4ae63f10.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://fox-access.techidaily.com/new-in-2024-laughing-moments-crafting-with-adobe/"><u>[New] In 2024, Laughing Moments Crafting with Adobe</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-80s-filters-and-effects-for-professional-videos/"><u>2024 Approved Top 80S Filters & Effects for Professional Videos</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/compose-cover-videos-for-friends-facebooks/"><u>Compose Cover Videos for Friends' Facebooks</u></a></li>
<li><a href="https://android-unlock.techidaily.com/downloading-samfw-frp-tool-30-for-samsung-galaxy-s23-tactical-edition-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Samsung Galaxy S23 Tactical Edition</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-guide-updating-your-asus-maximus-x-hero-motherboard-drivers/"><u>Effortless Guide: Updating Your ASUS Maximus X Hero Motherboard Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-troubleshooting-and-solving-power-state-driver-mistakes-on-pc/"><u>Expert Advice: Troubleshooting and Solving Power State Driver Mistakes on PC</u></a></li>
<li><a href="https://os-tips.techidaily.com/exploring-the-comprehensive-development-timeline-of-the-iconic-iphone/"><u>Exploring the Comprehensive Development Timeline of the Iconic iPhone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-airpod-connectivity-with-windows-11-advanced-solutions-for-a-seamless-experience/"><u>Mastering AirPod Connectivity with Windows 11: Advanced Solutions for a Seamless Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-usb-mouse-issues-solutions-when-it-wont-connect-to-your-laptop/"><u>Troubleshooting USB Mouse Issues: Solutions When It Won't Connect to Your Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-the-reason-behind-teredos-inability-to-connect-successfully/"><u>Understanding the Reason Behind Teredo's Inability to Connect Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wired-back-to-life-logitech-mouse-restsore/"><u>Wired Back to Life: Logitech Mouse Restsore</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

