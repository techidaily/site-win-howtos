---
title: "Expert Advice for Windows Users Facing 'Not Charging Although Plugged In': Solutions for Windows 7 and 10 Devices"
date: 2024-12-25T21:04:44.086Z
updated: 2024-12-27T17:34:44.660Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Expert Advice for Windows Users Facing 'Not Charging Although Plugged In': Solutions for Windows 7 and 10 Devices"
excerpt: "This Article Describes Expert Advice for Windows Users Facing 'Not Charging Although Plugged In': Solutions for Windows 7 and 10 Devices"
thumbnail: https://thmb.techidaily.com/289536a26b86dc5c26586097f9ebf58e81d35aa537c61d20d15b54d1edc660b4.jpg
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
<li><a href="https://facebook-video-content.techidaily.com/new-social-simulacrum-sculpting-constructing-playful-profiles-for-2024/"><u>[New] Social Simulacrum Sculpting Constructing Playful Profiles for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-capturing-photographs-from-movies-in-windows-photos-app-for-savvy-users/"><u>[Updated] Capturing Photographs From Movies in Windows Photos App for Savvy Users</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-recording-your-display-essential-tips-for-effective-screen-capture-for-2024/"><u>[Updated] Recording Your Display Essential Tips for Effective Screen Capture for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-11-update-0x80240034-bug-comprehensive-solutions/"><u>Fixing the Windows 11 Update 0X80240034 Bug – Comprehensive Solutions</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-oppo-a18-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Oppo A18 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-screenshot-on-an-asus-laptop-easily/"><u>How to Screenshot on an ASUS Laptop [Easily]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-resource-protection-start-up-errors-in-system-file-checker-scans/"><u>Overcoming 'Windows Resource Protection' Start-Up Errors in System File Checker Scans</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-error-with-amd-195-software/"><u>Resolving Windows Error with AMD 195 Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revitalize-your-laptops-charging-issues-with-these-straightforward-tips/"><u>Revitalize Your Laptop's Charging Issues with These Straightforward Tips</u></a></li>
<li><a href="https://fox-links.techidaily.com/room-and-pc-readiness-for-immersive-vr-with-oculus/"><u>Room & PC Readiness for Immersive VR with Oculus</u></a></li>
<li><a href="https://win-howtos.techidaily.com/spontaneous-shutdown-of-windows-machine/"><u>Spontaneous Shutdown of Windows Machine</u></a></li>
<li><a href="https://some-guidance.techidaily.com/strategies-for-effective-content-promotion-on-youtube-for-2024/"><u>Strategies for Effective Content Promotion on YouTube for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/struggling-with-torrent-downloads-heres-what-you-should-do-next/"><u>Struggling with Torrent Downloads? Here's What You Should Do Next</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-secret-to-deep-sleep-on-win11/"><u>The Secret to Deep Sleep on Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unpacking-whatsapps-telephony-and-messaging-system/"><u>Unpacking WhatsApp's Telephony and Messaging System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-over-windows-update-glitches-solutions-for-error-code-0xc1900208-in-w10/"><u>Winning Over Windows Update Glitches: Solutions for Error Code 0Xc1900208 in W10</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

