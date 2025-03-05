---
title: "Resolving Windows 11 Login Issues: Fixing User Profile Service Failures"
date: 2025-03-04T18:55:47.651Z
updated: 2025-03-05T16:38:32.094Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Windows 11 Login Issues: Fixing User Profile Service Failures"
excerpt: "This Article Describes Resolving Windows 11 Login Issues: Fixing User Profile Service Failures"
thumbnail: https://thmb.techidaily.com/4ea85f8fd0d9ab2c6c04d80e6aa73ebac967f8aac30c01b0db47479107c6b7f9.jpg
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
<li><a href="https://some-techniques.techidaily.com/new-humor-haven-the-ultimate-list-of-event-specific-jokes/"><u>[New] Humor Haven The Ultimate List of Event-Specific Jokes</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-methods-for-reducing-jello-like-video-stabilization-effects/"><u>[Updated] In 2024, Methods for Reducing Jello-Like Video Stabilization Effects</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-becoming-a-savvy-vr-tour-connoisseur/"><u>2024 Approved Becoming a Savvy VR Tour Connoisseur</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/sing-the-riches-of-mr-beast/"><u>Assessing the Riches of Mr. Beast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-repair-tips-for-fixing-malfunctioning-function-keys/"><u>DIY Repair Tips for Fixing Malfunctioning Function Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-a-frozen-windows-10-update-dilemma/"><u>Expert Tips for Fixing a Frozen Windows 10 Update Dilemma</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-tecno-phantom-v-flip-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Tecno Phantom V Flip Phone | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-recover-from-an-unresponsive-google-chrome-session-effectively/"><u>How to Recover From an Unresponsive Google Chrome Session Effectively</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-11-pro-withwithout-sim-card-by-drfone-ios/"><u>How to Unlock iPhone 11 Pro with/without SIM Card</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/innovative-techniques-for-engaging-igtv-thumbnails/"><u>Innovative Techniques for Engaging IGTV Thumbnails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-fixes-for-the-fatal-exception-error-understanding-windows-code-0xc00000e9/"><u>Mastering Fixes for the Fatal Exception Error: Understanding Windows Code 0Xc00000e9</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-for-failed-remote-procedure-calls-expert-tips-inside/"><u>Mastering the Fix for Failed Remote Procedure Calls - Expert Tips Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/netflix-service-outage-is-it-down-heres-how-you-can-check-and-resolve-issues/"><u>Netflix Service Outage - Is It Down? Here's How You Can Check & Resolve Issues</u></a></li>
<li><a href="https://extra-tips.techidaily.com/seamless-sync-solutions-top-cloud-apps-for-android/"><u>Seamless Sync Solutions Top Cloud Apps for Android</u></a></li>
<li><a href="https://win11.techidaily.com/shielding-game-progress-a-comprehensive-backup-approach/"><u>Shielding Game Progress: A Comprehensive Backup Approach</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-windows-update-error-code-0x80402c-your-ultimate-solution/"><u>Troubleshooting and Fixing Windows Update Error Code 0X80^402C: Your Ultimate Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-present-opencl-links/"><u>Troubleshooting Non-Present OpenCL Links</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-addressing-miskeyed-characters-on-keyboard-devices/"><u>Troubleshooting: Addressing Miskeyed Characters on Keyboard Devices</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-top-11-deepfake-voice-apps-and-software-you-need-to-know-about/"><u>Updated 2024 Approved Top 11 Deepfake Voice Apps and Software You Need to Know About</u></a></li>
</ul></div>

