---
title: Solutions for Resolving Windows Setup Hanging Issues on Your Laptop or Desktop
date: 2024-10-15T18:19:47.873Z
updated: 2024-10-21T22:11:24.479Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solutions for Resolving Windows Setup Hanging Issues on Your Laptop or Desktop
excerpt: This Article Describes Solutions for Resolving Windows Setup Hanging Issues on Your Laptop or Desktop
thumbnail: https://thmb.techidaily.com/749c8b13fba53b16e3cca7c517e32ea283379a232e31a28dc3a9b19edc9409b3.jpg
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
<li><a href="https://article-files.techidaily.com/updated-2024-approved-best-20-free-public-license-pubg-gallery-mixes/"><u>[Updated] 2024 Approved Best 20 Free Public License PUBG Gallery Mixes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-catching-life-in-motion-iphones-burst-capability/"><u>[Updated] Catching Life in Motion IPhone's Burst Capability</u></a></li>
<li><a href="https://win-howtos.techidaily.com/conquering-the-challenge-of-error-code-0x8024200d-winning-strategies-for-flawless-windows-updates-tutorial/"><u>Conquering the Challenge of Error Code 0X8024200d - Winning Strategies for Flawless Windows Updates [TUTORIAL]</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-vivo-s17-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Vivo S17 to iPhone | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-perfecting-elite-canon-time-lapse-cinematic/"><u>In 2024, Perfecting Elite Canon Time-Lapse Cinematic</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-monitor-resolution-setup-errors-solutions-that-worked-for-me/"><u>Overcoming Monitor Resolution Setup Errors: Solutions That Worked for Me</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-issue-steps-to-overcome-a-black-screen-on-google-chrome/"><u>Resolving the Issue: Steps to Overcome a Black Screen on Google Chrome</u></a></li>
<li><a href="https://video-capture.techidaily.com/screenflow-for-mac-a-full-featured-deep-dive-for-2024/"><u>ScreenFlow for Mac - A Full Featured Deep Dive for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-printer-accessibility-within-edges-secure-zone/"><u>Setting Up Printer Accessibility Within Edge's Secure Zone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/straightforward-methods-to-save-insta-story-videos-for-2024/"><u>Straightforward Methods to Save Insta Story Videos for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-how-to-fix-sound-issues-in-windows-7/"><u>Troubleshooting Steps: How to Fix Sound Issues in Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-vcruntime140dll-not-detected-error-on-your-pc-solution/"><u>Troubleshooting the VCRUNTIME140.dll Not Detected Error on Your PC [SOLUTION]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/update-needed-monitor-cannot-sync-with-present-input-delay-settings/"><u>Update Needed: Monitor Cannot Sync with Present Input Delay Settings</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

