---
title: Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
date: 2025-02-15T21:50:59.036Z
updated: 2025-02-16T16:38:24.976Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
excerpt: This Article Describes Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
thumbnail: https://thmb.techidaily.com/2e5cadcabaa5bc146e9286cd6ccf5e30c43742afdff538e1080a5add013b39bf.jpg
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

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
<li><a href="https://article-helps.techidaily.com/new-in-2024-distilling-virtual-realitys-kin-ar-mr-and-beyond/"><u>[New] In 2024, Distilling Virtual Reality's Kin AR, MR & Beyond</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-visual-giggle-factory-memebake-zone/"><u>[New] In 2024, Visual Giggle Factory Memebake Zone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-all-about-youtube-micro-videos/"><u>[Updated] All About YouTube Micro Videos</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/battle-desktop-window-managers-excessive-gpu-load-five-key-fixes-for-windows-users/"><u>Battle Desktop Window Manager's Excessive GPU Load: Five Key Fixes for Windows Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/enhance-user-experience-with-cookiebot-technology-integration/"><u>Enhance User Experience with Cookiebot Technology Integration</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-realme-gt-neo-5-se-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-update-issue-how-to-resolve-the-0x80070490-error/"><u>Fixing the Windows Update Issue: How to Resolve the 0X80070490 Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/flawless-typing-ahead-diagnosing-and-fixing-bluetooth-keyboard-pairing-failures-with-laptops-or-desktops/"><u>Flawless Typing Ahead: Diagnosing and Fixing Bluetooth Keyboard Pairing Failures with Laptops or Desktops</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-guide-to-unlock-your-vivo-y100t-by-drfone-android/"><u>Full Guide to Unlock Your Vivo Y100t</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-iphone-11-stuck-at-attempting-data-recovery-loop-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Fix iPhone 11 Stuck at attempting data recovery Loop | Stellar</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-vivo-x90s-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-printer-driver-not-found-on-your-windows-pc-fixed/"><u>How to Overcome 'Printer Driver Not Found' On Your Windows PC [FIXED]</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-frame-your-filmmaking-the-3-secrets-to-instagram-borders/"><u>In 2024, Frame Your Filmmaking The 3 Secrets to Instagram Borders</u></a></li>
<li><a href="https://win-howtos.techidaily.com/process-halted-no-execution/"><u>Process Halted: No Execution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-clipboard-problems-on-windows-11-computers/"><u>Resolved! Troubleshooting Clipboard Problems on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-this-device-is-not-present-error-code-24-in-windows-versions-11-8-and-7/"><u>Step-by-Step Fixes for 'This Device Is Not Present' - Error Code 24 in Windows Versions: 11, 8 and 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-resolving-twitch-error-4000/"><u>Troubleshooting Guide for Resolving Twitch Error 4000</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win10-renders-computer-inactive-suddenly/"><u>Win10 Renders Computer Inactive Suddenly</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

