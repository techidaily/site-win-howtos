---
title: "Resolving Start-Up Failures: The Application Couldn't Launch Correctly (0xC000007B Explained)"
date: 2024-10-01T20:28:17.717Z
updated: 2024-10-04T12:49:54.971Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Start-Up Failures: The Application Couldn't Launch Correctly (0xC000007B Explained)"
excerpt: "This Article Describes Resolving Start-Up Failures: The Application Couldn't Launch Correctly (0xC000007B Explained)"
thumbnail: https://thmb.techidaily.com/f17f33138f47cc809c1c7740ec4a954bd7d355028092c16b39a2af30bc8bac07.jpg
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-pixel-perfection-masterful-methods-for-stunning-imagery/"><u>[New] 2024 Approved Pixel Perfection Masterful Methods for Stunning Imagery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-journey-to-stability-dxgidll-restored/"><u>[PUBG] Journey to Stability - Dxgi.dll Restored</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-strategies-to-optimize-time-and-quality-in-thumbnail-design/"><u>[Updated] In 2024, Strategies to Optimize Time and Quality in Thumbnail Design</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cursor-continuous-display-troubles-learn-how-to-fix-it-now/"><u>Cursor Continuous Display Troubles? Learn How to Fix It Now</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-fixes-for-when-your-bluetooth-mouse-wont-pair-on-your-pc-running-windows/"><u>DIY Fixes for When Your Bluetooth Mouse Won't Pair on Your PC Running Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-malfunctioning-function-keys-for-optimal-usage/"><u>How to Fix Malfunctioning Function Keys for Optimal Usage</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-lost-files-from-motorola-g54-5g-by-fonelab-android-recover-data/"><u>How to retrieve lost files from Motorola G54 5G?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-remedies-to-restore-sound-in-your-favorite-steam-games-hassle-free/"><u>Immediate Remedies to Restore Sound in Your Favorite Steam Games | HASSLE-FREE</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Google Pixel 7a | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-easy-photo-progression-on-instagram/"><u>In 2024, Easy Photo Progression on Instagram</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-repairing-windows-11-and-10-os-errors-by-correcting-system-files/"><u>Master the Art of Repairing Windows 11 & 10 OS Errors by Correcting System Files</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/step-by-step-perfectly-sharing-your-photography-on-youtube-for-2024/"><u>Step-by-Step Perfectly Sharing Your Photography on YouTube for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-strategies-conquering-twitchs-notorious-error-4ntry/"><u>Step-by-Step Strategies: Conquering Twitch's Notorious Error 4Ntry</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missing-desktop-symbols-on-windows-10-solved/"><u>Troubleshooting Missing Desktop Symbols on Windows 10 [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-access-to-your-start-menu-on-windows-10-made-easy/"><u>Unlocking Access to Your Start Menu on Windows 10 Made Easy</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/unlocking-instagrams-power-essential-5-tips-and-examples-from-pros-for-2024/"><u>Unlocking Instagram's Power Essential 5 Tips & Examples From Pros for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134227/18498" target="_top" id="2134227">
  <img src="//a.impactradius-go.com/display-ad/18498-2134227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134227/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

