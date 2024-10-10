---
title: Resolving Slow Typing Response Time for Windows 10 Users
date: 2024-10-05T21:38:11.261Z
updated: 2024-10-09T19:52:50.268Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Slow Typing Response Time for Windows 10 Users
excerpt: This Article Describes Resolving Slow Typing Response Time for Windows 10 Users
thumbnail: https://thmb.techidaily.com/77bfb2c7f1c1fe0360a8a12d5582bbafa6a377d533d7c690d2e56cf6d1507405.jpg
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
<li><a href="https://extra-support.techidaily.com/new-speedy-scripts-top-1-written-game-experiences-on-devices/"><u>[New] Speedy Scripts Top 1 Written Game Experiences on Devices</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-from-virtual-speaker-to-reel-showman-fb-live-recording-tactics/"><u>[Updated] 2024 Approved From Virtual Speaker to Reel Showman FB Live Recording Tactics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204204020-astro-a40-microphone-not-working-heres-how-to-fix-it/"><u>Astro A40 Microphone Not Working? Here's How to Fix It!</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discover-the-best-virtual-programming-tutors-and-platforms-for-mastery/"><u>Discover the Best Virtual Programming Tutors and Platforms for Mastery</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discovering-what-makes-telegram-a-unique-chat-service/"><u>Discovering What Makes Telegram a Unique Chat Service</u></a></li>
<li><a href="https://apple-account.techidaily.com/guide-on-how-to-remove-apple-id-from-apple-iphone-12-pro-max-by-drfone-ios/"><u>Guide on How To Remove Apple ID From Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-restoring-sound-output-dealing-with-no-installed-audio-device-warning-in-windows/"><u>Guide to Restoring Sound Output: Dealing with No Installed Audio Device Warning in Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-samsung-galaxy-m14-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Samsung Galaxy M14 5G? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-make-the-most-of-your-apple-iphone-12-pro-max-lock-screen-with-notifications-drfone-by-drfone-ios/"><u>How to Make the Most of Your Apple iPhone 12 Pro Max Lock Screen with Notifications? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/identifying-absence-of-critical-library-in-system/"><u>Identifying Absence of Critical Library in System</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/los-mejores-clientes-de-torrents-y-su-audiencia-una-guia-completa/"><u>Los Mejores Clientes De Torrents Y Su Audiencia: Una Guía Completa</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206950085-master-the-trick-to-eliminate-constant-usb-not-detected-pop-ups-for-good/"><u>Master the Trick to Eliminate Constant 'USB Not Detected' Pop-Ups for Good</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-detected-network-adjustment-problem/"><u>Step-by-Step Solution for 'Detected Network Adjustment Problem'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/teredo-struggles-with-eligibility-uncover-the-causes/"><u>Teredo Struggles with Eligibility: Uncover the Causes</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144283/7443" target="_top" id="2144283">
  <img src="//a.impactradius-go.com/display-ad/7443-2144283" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144283/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

