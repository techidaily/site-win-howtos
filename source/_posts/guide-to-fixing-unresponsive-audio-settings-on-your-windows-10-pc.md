---
title: Guide to Fixing Unresponsive Audio Settings on Your Windows 10 PC
date: 2024-10-06T18:52:04.982Z
updated: 2024-10-09T19:11:22.179Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Guide to Fixing Unresponsive Audio Settings on Your Windows 10 PC
excerpt: This Article Describes Guide to Fixing Unresponsive Audio Settings on Your Windows 10 PC
thumbnail: https://thmb.techidaily.com/91e7f02bd957e18d2516616e2ae6cdb5e18d026273686f4e3b0840225091d98b.jpg
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
<li><a href="https://screen-activity-recording.techidaily.com/new-essential-tech-top-10-webcam-recorders-in-win-11-for-2024/"><u>[New] Essential Tech Top 10 Webcam Recorders in Win 11 for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-understanding-your-macs-capabilities-in-big-sur/"><u>[New] Understanding Your Mac's Capabilities in Big Sur</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-much-could-you-make-on-youtube-snippets/"><u>[Updated] How Much Could You Make on YouTube Snippets?</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-mastering-3d-luts-complete-guide/"><u>[Updated] In 2024, Mastering 3D LUTs Complete Guide</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-navigating-youtubes-systems-after-video-upload/"><u>[Updated] In 2024, Navigating YouTube's Systems After Video Upload</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-malfunctioning-at-signs-in-text-input-devices-how-to/"><u>Addressing Malfunctioning At Signs in Text Input Devices: How-To</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-ms-teams-error-80080300-fixes-for-w11-users/"><u>Breaking Down MS Teams Error 80080300: Fixes for W11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210421278-expert-advice-on-handling-unavailable-dhcp-servers-get-connected-again/"><u>Expert Advice on Handling Unavailable DHCP Servers - Get Connected Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-internet-explorer-launch-issues-a-comprehensive-guide/"><u>Fixing Internet Explorer Launch Issues - A Comprehensive Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-and-fix-the-high-resource-demand-of-wudfhostexe-on-windows-11-devices/"><u>How to Address and Fix the High Resource Demand of Wudfhost.exe on Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-a-non-functional-scroll-wheel-on-your-logitech-mouse/"><u>How to Repair a Non-Functional Scroll Wheel on Your Logitech Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-touchpad-scrolling-functionality-in-windows-10/"><u>How to Restore Touchpad Scrolling Functionality in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-we-solved-the-igfxem-module-malfunction-problem/"><u>How We Solved the Igfxem Module Malfunction Problem</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-the-benefits-of-using-video-for-social-media-marketing/"><u>New In 2024, The Benefits Of Using Video For Social Media Marketing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-instructions-getting-your-laptop-mic-back-online/"><u>Step-by-Step Instructions: Getting Your Laptop Mic Back Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-backup-with-windows-11/"><u>Streamlining File Backup with Windows 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880976/19272" target="_top" id="1880976">
  <img src="//a.impactradius-go.com/display-ad/19272-1880976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880976/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
