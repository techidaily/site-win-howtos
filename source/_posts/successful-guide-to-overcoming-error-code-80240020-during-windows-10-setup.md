---
title: Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
date: 2024-12-21T18:36:08.253Z
updated: 2024-12-22T19:24:47.491Z
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
<li><a href="https://video-screen-grab.techidaily.com/new-essential-tips-for-organizing-zoom-sessions/"><u>[New] Essential Tips for Organizing Zoom Sessions</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/batterypower-icon-missing-windows-10-solved/"><u>Battery/Power Icon Missing Windows 10 [Solved]</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/cheap-yet-superior-gaming-keyboard-guide-under-100-for-2024/"><u>Cheap, Yet Superior Gaming Keyboard Guide Under $100 for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-it-the-ultimate-solution-for-warframe-update-failed-issues/"><u>Fix It! The Ultimate Solution for 'Warframe Update Failed' Issues</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-when-apple-account-locked-from-apple-iphone-14-pro-max-by-drfone-ios/"><u>How to Fix when Apple Account Locked From Apple iPhone 14 Pro Max?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-from-the-iphone-x-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock From the iPhone X Without Previous Owner?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-infinix-hot-30-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Infinix Hot 30 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/refining-your-facebook-presence-for-success/"><u>Refining Your Facebook Presence for Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-persistent-windows-error-a-comprehensive-fix-for-error-0x8000ffff/"><u>Resolving the Persistent Windows Error: A Comprehensive Fix for Error 0X8000ffff</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-correct-xerox-error-code-0x800f020b-for-windows-users/"><u>Step-by-Step Guide to Correct Xerox Error Code 0X800F020B for Windows Users</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/step-by-step-guide-how-to-recover-lost-iphone-phone-logs/"><u>Step-by-Step Guide: How to Recover Lost iPhone Phone Logs</u></a></li>
<li><a href="https://discover-data.techidaily.com/troubleshooting-flip-editors-grey-screen-issue-for-smooth-page-customization/"><u>Troubleshooting Flip Editor's Grey Screen Issue for Smooth Page Customization</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

