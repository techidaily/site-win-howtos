---
title: Step-by-Step Solutions for Overcoming the Windows Update Issue (Error 0X8024002E)
date: 2025-01-12T16:53:45.996Z
updated: 2025-01-13T16:47:16.849Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for Overcoming the Windows Update Issue (Error 0X8024002E)
excerpt: This Article Describes Step-by-Step Solutions for Overcoming the Windows Update Issue (Error 0X8024002E)
thumbnail: https://thmb.techidaily.com/bbd88c517a72e9ebb4f977c94404d584a269beabb937398b9573ea9432863248.jpg
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-defending-your-youtube-profile/"><u>[New] 2024 Approved Defending Your YouTube Profile</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-unbearable-high-cpu-consumption-by-shell-infrastructures-in-modern-oses-like-windows-10-and-linux/"><u>[Resolved] Unbearable High CPU Consumption by Shell Infrastructures in Modern OSes Like Windows 10 & Linux.</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-visual-communication-title-and-caption-overlays-on-video-clips-via-photos/"><u>[Updated] Mastering Visual Communication Title & Caption Overlays on Video Clips via Photos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-reposting-photosvideos-a-users-manual/"><u>2024 Approved Reposting Photos/Videos A User's Manual</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-youtube-music-replay-tracks-2023/"><u>2024 Approved The Ultimate YouTube Music Replay Tracks, 2023</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-strategies-to-fix-audio-services-not-responding-error-in-widows-10/"><u>Comprehensive Strategies to Fix 'Audio Services Not Responding' Error in Widows 10</u></a></li>
<li><a href="https://extra-resources.techidaily.com/enlightening-your-iphone-images-through-effective-hdr-methods/"><u>Enlightening Your iPhone Images Through Effective HDR Methods</u></a></li>
<li><a href="https://howto.techidaily.com/fix-nokia-c300-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Nokia C300 Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-specified-module-could-not-be-found/"><u>How To Fix The Specified Module Could Not Be Found</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-phone-without-pin-by-drfone-android/"><u>How to Unlock Samsung Phone without PIN</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-infinix-hot-30i-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Infinix Hot 30i Phone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-resolve-error-code-0x800f081f-during-net-framework-35-setup/"><u>Solving the Problem: Resolve Error Code 0X800F081F During .NET Framework 3.5 Setup</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/the-ultimate-guide-to-animated-text-in-video-best-mobile-apps-for-2024/"><u>The Ultimate Guide to Animated Text in Video Best Mobile Apps for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

