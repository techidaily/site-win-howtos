---
title: Solving Lenovo Mouse Pad Malfunctions Across All Windows OS Variants (Windows 10, 8 & 7)
date: 2025-02-05T14:41:35.470Z
updated: 2025-02-07T11:31:42.350Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving Lenovo Mouse Pad Malfunctions Across All Windows OS Variants (Windows 10, 8 & 7)
excerpt: This Article Describes Solving Lenovo Mouse Pad Malfunctions Across All Windows OS Variants (Windows 10, 8 & 7)
thumbnail: https://thmb.techidaily.com/0c231e30e1cde65144bf91e6e96a309bb581e79a51b0603eaf2331d2401d5ca6.jpg
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
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-craft-top-quality-youtube-thumbnails-fast/"><u>[Updated] 2024 Approved How To Craft Top Quality YouTube Thumbnails Fast</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-premium-roundup-best-3ds-on-pc-simulator-tools/"><u>[Updated] In 2024, Premium Roundup Best 3Ds on PC Simulator Tools</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-pros-playbook-for-top-10-music-videos-that-define-genres-for-2024/"><u>[Updated] The Pros' Playbook for Top 10 Music Videos That Define Genres for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/calm-tales-on-screen-analyzing-parent-child-bedtime-videos-for-2024/"><u>Calm Tales on Screen Analyzing Parent-Child Bedtime Videos for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722214295682-dipole-transitions-such-as-electronic-excitations-within-atoms-or-molecules/"><u>Dipole Transitions (Such as Electronic Excitations Within Atoms or Molecules)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-80240020-in-windows-11-a-step-by-step-solution-for-successful-installation/"><u>Error Code 80240020 in Windows 11: A Step-by-Step Solution for Successful Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-microsoft-wireless-display-adapter-connection-issues-in-windows-11-solutions-unveiled/"><u>Fixing Microsoft Wireless Display Adapter Connection Issues in Windows 11 - Solutions Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-fix-windows-11-when-updates-wont-proceed/"><u>How To Troubleshoot and Fix Windows 11 When Updates Won't Proceed</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-nubia-z50-ultra-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Nubia Z50 Ultra to New Android? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/laptop-beautification-leading-website-walls/"><u>Laptop Beautification Leading Website Walls</u></a></li>
<li><a href="https://extra-skills.techidaily.com/nine-remedies-for-firefox-video-glitches-on-social-media-for-2024/"><u>Nine Remedies for Firefox Video Glitches on Social Media for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-error-code-0xc00cuh8-a-comprehensive-fix-guide-for-windows-users/"><u>Overcoming Error Code 0Xc00cuh8: A Comprehensive Fix Guide for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-for-correcting-the-error-code-ce-34878-0-on-sonys-console/"><u>Solution Steps for Correcting the Error Code CE-34878-0 on Sony's Console</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-resolving-loading-issues-in-madden-nfl-22/"><u>Troubleshooting Tips: Resolving 'Loading' Issues in Madden NFL 22</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

