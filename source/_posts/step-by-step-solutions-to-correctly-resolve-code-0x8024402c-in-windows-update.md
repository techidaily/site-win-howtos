---
title: Step-by-Step Solutions to Correctly Resolve Code 0X8024402c in Windows Update
date: 2024-11-22T05:57:57.954Z
updated: 2024-11-27T17:13:48.169Z
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
<li><a href="https://program-issues.techidaily.com/detective-in-la-uncovering-clues-now-playable-on-your-computer/"><u>'Detective in LA: Uncovering Clues' Now Playable on Your Computer</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-streaming-platforms-face-off-choosing-between-vimeo-youtube-dailymotion/"><u>[New] In 2024, Streaming Platforms Face-Off Choosing Between Vimeo, YouTube, DailyMotion</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-utilizing-smartphones-for-effective-home-based-filming/"><u>[New] In 2024, Utilizing Smartphones for Effective Home-Based Filming</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-from-the-field-expertly-chosen-5-gamer-friendly-webcams/"><u>[Updated] 2024 Approved From the Field Expertly Chosen 5 Gamer-Friendly Webcams</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-and-repairing-error-code-28-on-your-windows-computers-device-manager/"><u>Addressing and Repairing Error Code 28 on Your Windows Computer’s Device Manager</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/best-approach-for-managing-cc-rights-and-usage/"><u>Best Approach for Managing CC Rights & Usage</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/enhancing-user-experience-recovering-lost-youtubefb-videos-for-2024/"><u>Enhancing User Experience Recovering Lost YouTube/FB Videos for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-how-to-restore-night-light-feature-in-windows-11/"><u>Fixing the Issue: How to Restore Night Light Feature in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-missing-device-driver-issue-step-by-step-guide-for-windows-answer/"><u>Fixing the Missing Device Driver Issue: Step-by-Step Guide for Windows [Answer]</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-a-small-act-of-kindness-by-amazon-surprised-and-delighted-customers-on-zdnet/"><u>How a Small Act of Kindness by Amazon Surprised and Delighted Customers on ZDNet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-sound-from-my-acer-try-these-pro-tricks-for-audio-recovery/"><u>No Sound From My Acer? Try These Pro Tricks for Audio Recovery</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-erroneous-0x80246007-in-win11-uptime/"><u>Quick Fix for Erroneous 0X80246007 in Win11 Uptime</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-cpu-use-by-windows-sound-card-driver/"><u>Resolve Excessive CPU Use by Windows Sound Card Driver</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-dxgkrnl-fatal-error-in-videos-on-windows-systems/"><u>Resolving the DXGKRNL Fatal Error in Videos on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-net-framework-35-installation-tackling-and-fixing-error-code-0x800f081f-issues/"><u>Successful .NET Framework 3.5 Installation: Tackling and Fixing Error Code 0X800F081F Issues</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-a-non-functional-laptop-microphone/"><u>Troubleshooting & Repairing a Non-Functional Laptop Microphone</u></a></li>
<li><a href="https://driver-download.techidaily.com/upgrade-your-microsoft-sculpt-ergonomic-keyboard-drivers-in-a-flash-a-user-friendly-tutorial/"><u>Upgrade Your Microsoft Sculpt Ergonomic Keyboard Drivers in a Flash: A User-Friendly Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wacom-pen-wont-connect-to-windows-1110-heres-how-you-can-solve-it/"><u>Wacom Pen Won't Connect to Windows 11/10? Here's How You Can Solve It!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

