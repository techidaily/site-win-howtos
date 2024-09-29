---
title: "Error Code 80240020 in Windows 11: A Step-by-Step Solution for Successful Installation"
date: 2024-09-21T20:18:44.944Z
updated: 2024-09-28T17:46:32.972Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 80240020 in Windows 11: A Step-by-Step Solution for Successful Installation"
excerpt: "This Article Describes Error Code 80240020 in Windows 11: A Step-by-Step Solution for Successful Installation"
thumbnail: https://thmb.techidaily.com/0afc969a260468b6e52b6a33d1ca7e6eed63bd07ec976231956f9d4e1713d1ee.jpg
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-the-ultimate-guide-to-recording-gaming-with-fraps/"><u>[New] In 2024, The Ultimate Guide to Recording Gaming with Fraps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-mastering-instagram-the-ultimate-video-cropping-techniques/"><u>[Updated] In 2024, Mastering Instagram The Ultimate Video Cropping Techniques</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-syncing-tunes-with-video-cut-and-paste-youtube-editor-basics/"><u>[Updated] Syncing Tunes with Video Cut & Paste YouTube Editor Basics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-to-repair-solutions-for-windows-11-the-power-of-sfc-and-dism/"><u>Comprehensive Guide to Repair Solutions for Windows 11: The Power of SFC & DISM</u></a></li>
<li><a href="https://win-howtos.techidaily.com/destiny-2-launch-issue-how-to-fix-the-initializing-hang-up/"><u>Destiny 2 Launch Issue: How to Fix the 'Initializing' Hang-Up</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-implemented-previously-unsuccessful-attempts-to-reach-dhcp-server-now-successful/"><u>Fix Implemented: Previously Unsuccessful Attempts to Reach DHCP Server Now Successful</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-logitech-keyboard-recognized-on-a-newly-installed-windows-11-system/"><u>Getting Your Logitech Keyboard Recognized on a Newly Installed Windows 11 System</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-honor-magic5-ultimate-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Honor Magic5 Ultimate?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-oneplus-12-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-scrutinizing-the-economics-behind-short-video-earnings/"><u>In 2024, Scrutinizing the Economics Behind Short Video Earnings</u></a></li>
<li><a href="https://games-able.techidaily.com/interpretation-and-correction-of-error-code-30005/"><u>Interpretation and Correction of Error Code 30005</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/top-rated-laptop-docking-station-comparison-in-depth-analysis-by-tech-experts-zdnet/"><u>Top-Rated Laptop Docking Station Comparison: In-Depth Analysis by Tech Experts - ZDNet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-windows-10-solve-the-mystery-of-missing-icons-on-your-taskbar-here/"><u>Troubleshoot Your Windows 10: Solve the Mystery of Missing Icons On Your Taskbar Here</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-tecno-spark-10c-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Tecno Spark 10C Device</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947750/11832" target="_top" id="947750">
  <img src="//a.impactradius-go.com/display-ad/11832-947750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947750/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

