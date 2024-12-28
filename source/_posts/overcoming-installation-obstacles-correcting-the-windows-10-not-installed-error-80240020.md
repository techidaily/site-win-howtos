---
title: "Overcoming Installation Obstacles: Correcting the 'Windows 10 Not Installed' Error 80240020"
date: 2024-12-22T20:10:13.805Z
updated: 2024-12-28T14:01:47.055Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming Installation Obstacles: Correcting the 'Windows 10 Not Installed' Error 80240020"
excerpt: "This Article Describes Overcoming Installation Obstacles: Correcting the 'Windows 10 Not Installed' Error 80240020"
thumbnail: https://thmb.techidaily.com/f96105d1405f7c845f75622429456df69e9791ebea6985dfc0c6d939ebdaa395.jpg
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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-localizing-your-content-adding-subtitles-to-igtv/"><u>[New] In 2024, Localizing Your Content Adding Subtitles to IGTV</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-instant-techniques-chaotic-ordering-of-youtube-tracks/"><u>[New] Instant Techniques Chaotic Ordering of YouTube Tracks</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-animators-artistry-archives-for-2024/"><u>[Updated] Animator's Artistry Archives for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-comprehensive-directory-extracting-yt-template-videos-online-for-2024/"><u>[Updated] Comprehensive Directory Extracting YT Template Videos Online for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-satirists-web-workshop/"><u>2024 Approved Satirist's Web Workshop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixation-of-windows-failure-to-connect-with-system-event-management-protocols-successfully/"><u>Fixation of Windows Failure to Connect with System Event Management Protocols Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-your-bluetooth-keyboard-when-it-wont-connect-to-a-computer/"><u>How to Fix Your Bluetooth Keyboard When It Won't Connect to a Computer</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-essential-tips-for-youtube-edits-with-sony-vegas/"><u>In 2024, Essential Tips for YouTube Edits with Sony Vegas</u></a></li>
<li><a href="https://win-howtos.techidaily.com/next-generation-tkis-have-been-developed-to-overcome-some-forms-of-resistance/"><u>Next-Generation TKIs Have Been Developed to Overcome some Forms of Resistance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-troubleshooting-steps-to-overcome-the-windows-update-error-0x80070002/"><u>Quick Troubleshooting Steps to Overcome the Windows Update Error 0X80070002</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-vivo-y100i-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Vivo Y100i</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-youtube-sound-issues-in-windows-10-a-step-by-step-guide/"><u>Resolving YouTube Sound Issues in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-troubleshooting-unknown-usb-device-detected-and-port-reset-failures-on-windows-11/"><u>Solving the Mystery: Troubleshooting 'Unknown USB Device Detected' And Port Reset Failures on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/1723262416500-unbeatable-offer-get-legion-desktop-powered-by-rtx-4080-gpu-at-a-steep-discount-for-just-2091/"><u>Unbeatable Offer: Get Legion Desktop Powered by RTX 4080 GPU at a Steep Discount for Just $2,091</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

