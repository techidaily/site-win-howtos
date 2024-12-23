---
title: How to Break Free From the Restart Cycle in Windows 10/11 - A Comprehensive Guide
date: 2024-12-19T16:09:29.541Z
updated: 2024-12-22T21:47:18.300Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Break Free From the Restart Cycle in Windows 10/11 - A Comprehensive Guide
excerpt: This Article Describes How to Break Free From the Restart Cycle in Windows 10/11 - A Comprehensive Guide
thumbnail: https://thmb.techidaily.com/545f7379c0befa5a44cab74ccb395e1f4653a53c66c0461613d4a49d7a7f9a57.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

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
<li><a href="https://instagram-clips.techidaily.com/updated-perfectly-prepared-videos-a-guide-to-instagram-fitness-for-2024/"><u>[Updated] Perfectly Prepared Videos A Guide to Instagram Fitness for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-superior-streaming-made-simple-enabling-av1-in-youtube/"><u>[Updated] Superior Streaming Made Simple Enabling AV1 in YouTube</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-understanding-your-profit-revenue-per-thousand-from-youtubes-adsense-income/"><u>[Updated] Understanding Your Profit Revenue Per Thousand From YouTube's AdSense Income</u></a></li>
<li><a href="https://win-trending.techidaily.com/6zplusz6zplus44oo44kk44k66zmk5y675pya5paw44k944ov44oi44km44kn44kiioodioodgplusodlplusplus8leaoqoiwpiatios9vplusobhowniplusocgeociplusobruobqplusajiplusavsoa21/"><u>音響ノイズ除去最新ソフトウェア トップ５推薦 - 使い始めるのに手数料不要</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/expert-insights-into-synchronizing-desktops-in-google-meet/"><u>Expert Insights Into Synchronizing Desktops in Google Meet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-fixing-windows-system-entrypointnotfoundexception/"><u>Guide: Fixing Windows System 'EntryPointNotFoundException'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-solve-no-battery-found-in-a-moment-a-simple-guide/"><u>How to Solve 'No Battery Found' In a Moment - A Simple Guide</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/immerse-yourself-in-gaming-excellence-with-philipss-49-inch-oled-curve-screen/"><u>Immerse Yourself in Gaming Excellence with Philips's 49-Inch OLED Curve Screen</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-xiaomi-redmi-note-12-pro-4g-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Xiaomi Redmi Note 12 Pro 4G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revise-your-setup-troubleshooting-techniques-for-non-blinking-cursors/"><u>Revise Your Setup! Troubleshooting Techniques for Non-Blinking Cursors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-overcoming-difficulties-with-launching-nvidia-geforce-experience/"><u>Solved: Overcoming Difficulties with Launching NVIDIA GeForce Experience</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-vivo-v30-lite-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Vivo V30 Lite 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-windows-update-error-0x8024401c-for-windows-10-and-11-users/"><u>Troubleshooting and Fixing Windows Update Error 0X8024401c for Windows 10 & 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-made-easy-fix-windows-error-code-0xc0000098-in-minutes/"><u>Troubleshooting Made Easy: Fix Windows Error Code 0xC0000098 in Minutes!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-opengl-glitches-in-minecraft-expert-tips-and-tricks/"><u>Troubleshooting OpenGL Glitches in Minecraft: Expert Tips and Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-resolving-the-system-event-service-unreachable-problem-on-windows-pcs/"><u>Understanding and Resolving the 'System Event Service Unreachable' Problem on Windows PCs</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/video-editing-software-like-gopro-quik-for-windows-and-mac/"><u>Video Editing Software Like GoPro Quik for Windows and Mac</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

