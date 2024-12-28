---
title: "The Best Fixes for Frozen Taskbar in Windows 10: Step-by-Step Solutions"
date: 2024-12-23T15:01:00.064Z
updated: 2024-12-27T20:39:42.982Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes The Best Fixes for Frozen Taskbar in Windows 10: Step-by-Step Solutions"
excerpt: "This Article Describes The Best Fixes for Frozen Taskbar in Windows 10: Step-by-Step Solutions"
thumbnail: https://thmb.techidaily.com/f55f35329f28573e49eb2c54e3ad586424ba4a61048c3f39de5943b637615a77.jpg
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
<li><a href="https://youtube-data.techidaily.com/024-approved-step-by-step-to-creating-an-unbeatable-biz-youtube-channel/"><u>[New] 2024 Approved Step-by-Step to Creating an Unbeatable Biz YouTube Channel</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-swiveling-screens-mastering-video-rotation-on-instagram/"><u>[New] 2024 Approved Swiveling Screens Mastering Video Rotation on Instagram</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-innovative-approaches-to-ppt-video-captures/"><u>[Updated] In 2024, Innovative Approaches to PPT Video Captures</u></a></li>
<li><a href="https://data-recovery.techidaily.com/arrayally-master-raid-reconstruction-tool/"><u>ArrayAlly: Master RAID Reconstruction Tool</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Tecno Spark 10 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-curbing-high-disk-space-usage-from-windows-10-compatibility-telemetry/"><u>Guide: Curbing High Disk Space Usage From Windows 10 Compatibility Telemetry</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-code-24-issue-in-windows-operating-systems-win11-win8-and-win7/"><u>Resolving Code 24 Issue in Windows Operating Systems (Win11, Win8 & Win7)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-repairing-broken-windows-11-operating-system-components/"><u>Step-by-Step Solutions for Repairing Broken Windows 11 Operating System Components</u></a></li>
<li><a href="https://network-issues.techidaily.com/steps-to-eliminate-black-screen-complications/"><u>Steps to Eliminate Black Screen Complications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-windows-10-0x80240034-error-during-updates/"><u>Ultimate Guide: Resolving Windows 10 0X80240034 Error During Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlock-the-potential-of-system-file-checker-sfc-and-deployment-image-servicing-dism-for-seamless-windows-10-recovery/"><u>Unlock the Potential of System File Checker (SFC) and Deployment Image Servicing (DISM) for Seamless Windows 10 Recovery</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

