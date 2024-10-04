---
title: "Mastering Windows 10/11: A Comprehensive Fix for Error 0X8024401c During Updates"
date: 2024-10-02T09:13:59.608Z
updated: 2024-10-04T11:31:32.574Z
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-unlocking-twitters-potential-with-live-videos/"><u>[New] 2024 Approved Unlocking Twitter's Potential with Live Videos</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-deep-dive-magix-video-pro-x-features-and-performance-for-2024/"><u>[New] Deep Dive Magix Video Pro X Features and Performance for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-avoiding-youtube-copyright-claims-understanding-the-rules/"><u>[Updated] 2024 Approved Avoiding YouTube Copyright Claims Understanding the Rules</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-instagram-story-highlight-a-user-friendly-guide/"><u>[Updated] 2024 Approved Instagram Story Highlight A User-Friendly Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-the-art-of-video-marketing-11-tips-to-skyrocket-fb-traffic/"><u>[Updated] In 2024, The Art of Video Marketing 11 Tips to Skyrocket FB Traffic</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-key-to-spreading-online-jokes-fast/"><u>[Updated] The Key to Spreading Online Jokes Fast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212440566-bring-out-the-hidden-touchpad-showcase-it/"><u>Bring Out the Hidden Touchpad, Showcase It!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-for-dealing-with-loadlibrary-failures-insights-into-error-1114/"><u>Effective Strategies for Dealing with LoadLibrary Failures – Insights Into Error 1114</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0x80004005-deciphered-ultimate-troubleshooting-steps-and-solutions/"><u>Error 0X80004005 Deciphered: Ultimate Troubleshooting Steps and Solutions</u></a></li>
<li><a href="https://some-techniques.techidaily.com/excellent-free-thumbnails-collection-pubg-edition-for-2024/"><u>Excellent Free Thumbnails Collection PUBG Edition for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-poco-x6-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-windows-update-0x8007049e-troubleshooting-guide/"><u>How to Fix the Windows Update '0X8007049e' Troubleshooting Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-triple-tactic-tracker-how-to-scrutinize-your-subscriber-earnings-on-googles-platform-youtube/"><u>In 2024, Triple Tactic Tracker How to Scrutinize Your Subscriber Earnings on Google's Platform, YouTube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-entrypointnotfound-issue-fix-guide-for-windows-systems/"><u>Resolving 'EntryPointNotFound' Issue: Fix Guide for Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-device-detection-issues-with-bluetooth-on-windows-10/"><u>Troubleshooting Guide: Fixing Device Detection Issues with Bluetooth on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-camera-issues-on-hp-laptops-with-windows-11/"><u>Troubleshooting Guide: Resolving Camera Issues on HP Laptops with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-fixing-d3derr-not-available-errors-on-your-pc/"><u>Troubleshooting Tips for Fixing D3DERR Not Available Errors on Your PC</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958378/18409" target="_top" id="1958378">
  <img src="//a.impactradius-go.com/display-ad/18409-1958378" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1958378/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

