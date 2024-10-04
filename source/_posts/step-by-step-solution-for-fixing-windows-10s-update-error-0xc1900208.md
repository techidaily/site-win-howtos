---
title: "Step-by-Step Solution for Fixing Windows 10'S Update Error: 0Xc1900208"
date: 2024-09-30T23:58:24.728Z
updated: 2024-10-03T22:43:51.529Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Solution for Fixing Windows 10'S Update Error: 0Xc1900208"
excerpt: "This Article Describes Step-by-Step Solution for Fixing Windows 10'S Update Error: 0Xc1900208"
thumbnail: https://thmb.techidaily.com/5164fa265fad5df086cc8d529b2f3b17fbfd4164208e747d807661e727a6e5b2.jpg
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
<li><a href="https://eaxpv-info.techidaily.com/updated-charting-the-course-of-monetization-for-creator-economy-on-youtubeshorts-for-2024/"><u>[Updated] Charting the Course of Monetization for Creator Economy on YouTubeshorts for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-secure-your-fb-story-views-with-these-5-techniques/"><u>[Updated] In 2024, Secure Your FB Story Views with These 5 Techniques</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-angle-alchemists-guide-to-transforming-your-videos-youtube-edition/"><u>[Updated] The Angle Alchemist's Guide to Transforming Your Videos (YouTube Edition)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-step-by-step-for-secure-complimentary-vlc-installation-on-mac/"><u>2024 Approved Step-by-Step for Secure, Complimentary VLC Installation on Mac</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/7-best-free-online-youtube-tag-extractors-for-2024/"><u>7 Best Free Online YouTube Tag Extractors for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/covid-deception-12-influencer-misinformation-role/"><u>Covid Deception: 12 Influencer Misinformation Role</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0xc00solved-troubleshooting-and-fixes-for-windows-users/"><u>Error Code 0XC00#Solved: Troubleshooting and Fixes for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-your-steelseries-arctis-5-headsets-broken-microphone-no-more-sorry/"><u>Expert Tips for Repairing Your SteelSeries Arctis 5 Headset's Broken Microphone (NO MORE SORRY)</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-best-10-mock-location-apps-worth-trying-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Best 10 Mock Location Apps Worth Trying On Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-xiaomi-redmi-13c-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Xiaomi Redmi 13C? Try These Fixes</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-the-ultimate-room-and-pc-checklist-for-vr/"><u>In 2024, The Ultimate Room and PC Checklist for VR</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-issues-with-starting-your-hosted-network-feature-on-windows-10-devices/"><u>Overcoming Issues with Starting Your Hosted Network Feature on Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210538704-resolving-problem-during-restore-mistake-in-windows-10-fixed/"><u>Resolving 'Problem During Restore' Mistake in Windows 10 – Fixed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723201180829-resolving-windows-update-error-code-0x80cuh0002-quickly-and-easily/"><u>Resolving Windows Update Error Code 0X80cuh0002 Quickly and Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/sharpen-your-windows-11-viewing-experience-fixes-for-unclear-characters/"><u>Sharpen Your Windows 11 Viewing Experience - Fixes for Unclear Characters</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-fixes-for-windows-11-users-struggling-with-the-disappearing-bluetooth-feature/"><u>Simple Fixes for Windows 11 Users Struggling with the Disappearing Bluetooth Feature!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-non-functional-usb-ports-on-a-dell-device/"><u>Troubleshooting and Repairing Non-Functional USB Ports on a Dell Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-successfully-update-your-pc-with-fixes-for-error-0x800f0922-on-windows-11/"><u>Troubleshooting Tips: Successfully Update Your PC with Fixes for Error 0X800f0922 on Windows 11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-power-of-fujitsu-scansnap-ix1600-an-essential-for-any-office-space/"><u>Unveiling the Power of Fujitsu ScanSnap iX1600: An Essential for Any Office Space</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

