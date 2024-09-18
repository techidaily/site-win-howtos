---
title: "Resolving the 'Video File Unplayable' Mistake: Fixing Error Code 224003"
date: 2024-09-10T17:21:07.435Z
updated: 2024-09-17T19:19:05.721Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the 'Video File Unplayable' Mistake: Fixing Error Code 224003"
excerpt: "This Article Describes Resolving the 'Video File Unplayable' Mistake: Fixing Error Code 224003"
thumbnail: https://thmb.techidaily.com/75e496d7d03af882c809a7273c9e1eb1d9baeae9a3a5a4a6ed566b778061c9ff.png
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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-pro-video-tips-add-borders-and-raise-quality-on-ig/"><u>[New] In 2024, Pro Video Tips Add Borders and Raise Quality on IG</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-ways-to-overcome-the-windows-update-failure-error-0x80070652/"><u>Effortless Ways to Overcome the Window's Update Failure (Error 0X80070652)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/elevate-your-teams-presence-blur-backdrops-with-expertise/"><u>Elevate Your Teams Presence Blur Backdrops with Expertise</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-successfully-solving-error-code-0x800f0922-during-windows-11-updates-top-8-fixes/"><u>Guide to Successfully Solving Error Code 0X800f0922 During Windows 11 Updates (Top 8 Fixes)</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-a-beginners-approach-to-adding-dates-to-photographs/"><u>In 2024, A Beginner's Approach to Adding Dates to Photographs</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-honor-v-purse-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Honor V Purse Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-the-weak-signature-algorithm-warning-in-browsers-a-comprehensive-guide-to-resolve-neterrcertweaksignaturealgorithm-error/"><u>Overcome the Weak Signature Algorithm Warning in Browsers: A Comprehensive Guide to Resolve NET::ERR_CERT_WEAK_SIGNATURE_ALGORITHM Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-enable-device-pairing-for-bluetooth-on-windows-11-computers/"><u>Resolved! How to Enable Device Pairing for Bluetooth on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-solutions-for-rapidly-improving-your-sluggish-keyboard-reaction-time/"><u>Simple Solutions for Rapidly Improving Your Sluggish Keyboard Reaction Time</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-streamlining-your-workflow-import-and-export-videos-in-adobe-premiere-pro-2023/"><u>Updated Streamlining Your Workflow Import and Export Videos in Adobe Premiere Pro 2023</u></a></li>
<li><a href="https://extra-tips.techidaily.com/youtubes-role-in-shaping-brands-and-collaborations/"><u>YouTube's Role in Shaping Brands & Collaborations</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

