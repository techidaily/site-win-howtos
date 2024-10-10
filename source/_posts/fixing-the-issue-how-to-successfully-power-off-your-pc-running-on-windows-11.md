---
title: "Fixing the Issue: How to Successfully Power Off Your PC Running on Windows 11"
date: 2024-10-04T18:39:22.609Z
updated: 2024-10-09T20:20:23.023Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the Issue: How to Successfully Power Off Your PC Running on Windows 11"
excerpt: "This Article Describes Fixing the Issue: How to Successfully Power Off Your PC Running on Windows 11"
thumbnail: https://thmb.techidaily.com/c9af2386c6798b3575f6d66e9544981a45984b6b6be55d294d273187d6f5f1e2.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

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
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-streamlining-your-discord-chat-experience-on-devices/"><u>[New] 2024 Approved Streamlining Your Discord Chat Experience on Devices</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-extract-and-play-fb-soundtracks/"><u>[New] Extract and Play FB Soundtracks</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-the-art-of-auditory-branding-logo-insights-for-podcasters/"><u>[New] In 2024, The Art of Auditory Branding Logo Insights for Podcasters</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-virtual-adrenaline-rushes-top-10-without-gta/"><u>[Updated] 2024 Approved Virtual Adrenaline Rushes - Top 10 Without GTA</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-advanced-techniques-in-xbox-gaming-recording-setup/"><u>[Updated] Advanced Techniques in Xbox Gaming Recording Setup</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-mastering-instagram-your-complete-guide-to-making-a-mark-with-reels/"><u>[Updated] Mastering Instagram Your Complete Guide to Making a Mark With Reels</u></a></li>
<li><a href="https://win-howtos.techidaily.com/advanced-handling-of-insufficient-resources-service-errors/"><u>Advanced Handling of 'Insufficient Resources' Service Errors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/banish-silent-tweets-add-volume-to-videos/"><u>Banish Silent Tweets Add Volume to Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-when-the-backspace-keys-stopped-responding-a-step-by-estep-guide/"><u>Easy Fixes for When the Backspace Keys Stopped Responding: A Step-by-eStep Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-when-your-lenovo-laptop-camera-stops-functioning/"><u>Effective Solutions for When Your Lenovo Laptop Camera Stops Functioning</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correct-a-bad-image-error-on-your-windows-11windows-10-device/"><u>How to Correct a Bad Image Error on Your Windows 11/Windows 10 Device</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-mastering-the-art-of-photo-retouching/"><u>In 2024, Mastering the Art of Photo Retouching</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-fcp-like-a-pro-top-5-editing-techniques-to-take-your-videos-to-the-next-level/"><u>New FCP Like a Pro Top 5 Editing Techniques to Take Your Videos to the Next Level</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-svchostexes-excessive-cpu-consumption-in-windows-10-a-complete-guide/"><u>Resolving svchost.exe's Excessive CPU Consumption in Windows 10 - A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-0xc00000e9-blue-screen-error-in-windows-a-step-by-step-guide/"><u>Resolving the 0xC00000E9 Blue Screen Error in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/seamless-repair-tips-for-resolving-stubborn-usb-port-issues-effectively/"><u>Seamless Repair Tips for Resolving Stubborn USB Port Issues Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/svchostexe-using-too-much-power-optimize-your-pc-with-these-windows-10-tips/"><u>Svchost.exe Using Too Much Power? Optimize Your PC with These Windows 10 Tips!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-crackling-sounds-from-speakers-on-microsoft-operating-systems/"><u>Troubleshooting Crackling Sounds From Speakers on Microsoft Operating Systems</u></a></li>
<li><a href="https://win-able.techidaily.com/update-the-google-app-ensure-that-you-have-the-latest-version-of-the-google-app-installed-on-your-device-go-to-the-play-store-search-for-google-and-update-i435/"><u>Update the Google App: Ensure that You Have the Latest Version of the Google App Installed on Your Device. Go to the Play Store, Search for Google, and Update if Necessary</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052062/7443" target="_top" id="2052062">
  <img src="//a.impactradius-go.com/display-ad/7443-2052062" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052062/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

