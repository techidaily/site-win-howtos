---
title: Bypass Installation Hurdles – Fixing Failed Hardware Monitor Driver Loading Problems
date: 2024-09-27T22:18:52.111Z
updated: 2024-09-28T22:17:44.027Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Bypass Installation Hurdles – Fixing Failed Hardware Monitor Driver Loading Problems
excerpt: This Article Describes Bypass Installation Hurdles – Fixing Failed Hardware Monitor Driver Loading Problems
thumbnail: https://thmb.techidaily.com/61f98fc4d9e1af032d9fc6896b875fde870b9cc610ca573f8ea2783fc3752f47.jpg
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
<li><a href="https://facebook-video-files.techidaily.com/new-unlocking-the-potential-of-your-online-persona-on-facebook-for-2024/"><u>[New] Unlocking the Potential of Your Online Persona on Facebook for 2024</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/5-ways-to-transfer-music-from-apple-iphone-14-to-android-drfone-by-drfone-transfer-from-ios/"><u>5 Ways to Transfer Music from Apple iPhone 14 to Android | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-messages-from-vivo-s17-pro-by-fonelab-android-recover-messages/"><u>Best Android Data Recovery - Undelete Lost Messages from Vivo S17 Pro</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-practices-for-an-immersive-streaming-experience/"><u>Best Practices for an Immersive Streaming Experience</u></a></li>
<li><a href="https://extra-information.techidaily.com/bringing-facial-movement-to-life-with-picsarts-effects/"><u>Bringing Facial Movement to Life with Picsart's Effects</u></a></li>
<li><a href="https://win-howtos.techidaily.com/destiny-the-second-server-problems-heres-how-to-resolve-them-efficiently/"><u>Destiny the Second Server Problems? Here's How to Resolve Them Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-tricks-to-unfreeze-and-optimize-your-windows-11-taskbar-experience/"><u>Effective Tricks to Unfreeze and Optimize Your Windows 11 Taskbar Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-10-update-mishap-overcome-error-code-0xc1900208/"><u>Fixing the Windows 10 Update Mishap: Overcome Error Code 0xC1900208</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210060400-get-your-keyboards-arrow-keys-working-again-with-these-proven-tips/"><u>Get Your Keyboard's Arrow Keys Working Again with These Proven Tips!</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-on-your-iphone-8-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card on Your iPhone 8 Apple ID and Apple Pay</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-gmail-password-on-oppo-a56s-5g-devices-by-drfone-android/"><u>How to Reset Gmail Password on Oppo A56s 5G Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-strategies-to-fix-frame-rate-drops-and-lags-in-world-of-warcraft/"><u>In-Depth Strategies to Fix Frame Rate Drops and Lags in World of Warcraft</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-dns-failure-discover-4-effortless-solutions-for-restoring-connectivity/"><u>Overcome DNS Failure: Discover 4 Effortless Solutions for Restoring Connectivity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-hp-laptop-camera-glitches-in-windows-11-expert-advice-and-effective-methods/"><u>Overcoming HP Laptop Camera Glitches in Windows 11: Expert Advice and Effective Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-steam-service-problems-for-a-smooth-windows-11-experience/"><u>Solving Steam Service Problems for a Smooth Windows 11 Experience</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-tecno-pop-7-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Tecno Pop 7 Pro Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-is-runtime-broker-and-fix-its-high-cpu-error-on-windows-10-solved/"><u>What Is Runtime Broker and Fix Its High CPU Error on Windows 10 [Solved]</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145082/17095" target="_top" id="2145082">
  <img src="//a.impactradius-go.com/display-ad/17095-2145082" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145082/17095" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

