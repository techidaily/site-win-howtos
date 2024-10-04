---
title: Step-by-Step Approach to Correct the 'Failed to Set Up Service' Error (0X80072EFD) on Your PC
date: 2024-09-30T08:21:28.501Z
updated: 2024-10-04T01:57:32.428Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Approach to Correct the 'Failed to Set Up Service' Error (0X80072EFD) on Your PC
excerpt: This Article Describes Step-by-Step Approach to Correct the 'Failed to Set Up Service' Error (0X80072EFD) on Your PC
thumbnail: https://thmb.techidaily.com/104450fe8ea4a9516969410598e82c71d2951cffe9ee598f36dc42477a8a3193.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-ultimate-free-top-ranked-image-overlays-for-androidandios/"><u>[New] 2024 Approved Ultimate FREE Top-Ranked Image Overlays for Android&iOS</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-gratuitous-goal-games-capturing-kicks-without-costs/"><u>[New] Gratuitous Goal Games Capturing Kicks Without Costs</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-simplicity-in-capturing-your-lenovo-pics/"><u>[Updated] Simplicity in Capturing Your Lenovo Pics</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/access-spankwire-video-downloads-for-both-mac-os-and-windows-users/"><u>Access Spankwire Video Downloads for Both Mac OS & Windows Users</u></a></li>
<li><a href="https://network-issues.techidaily.com/dell-desktop-hologram-glitch-resolved/"><u>Dell Desktop Hologram Glitch Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-how-to-resolve-a-frozen-pc-while-setting-up-the-windows-operating-system/"><u>Expert Advice: How to Resolve a Frozen PC While Setting Up the Windows Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-for-when-google-chrome-freezes/"><u>Fixes for When Google Chrome Freezes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-how-to-restore-your-laptops-or-pcs-backlit-keyboard/"><u>Fixing the Issue: How to Restore Your Laptop's or PC's Backlit Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-failed-user-profile-service-error-when-trying-to-log-into-windows-11/"><u>How to Resolve the Failed 'User Profile Service' Error When Trying to Log Into Windows 11</u></a></li>
<li><a href="https://media-tips.techidaily.com/include-provisions-that-require-the-destruction-of-data-after-5-years-unless-renewed-consent-is-given-by-the-patient-or-required-for-ongoing-research-purpos1/"><u>Include Provisions that Require the Destruction of Data After 5 Years Unless Renewed Consent Is Given by the Patient or Required for Ongoing Research Purposes, Citing Section XX, Paragraph YY.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/metaplasia-dysplasia-carcinogenesis-sequence/"><u>Metaplasia-Dysplasia-Carcinogenesis Sequence</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/transformate-gratuita-de-imagenes-jpg-a-jpeg-online-con-movavi/"><u>Transfórmate Gratuita De Imágenes JPG a JPEG Online Con Movavi</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

