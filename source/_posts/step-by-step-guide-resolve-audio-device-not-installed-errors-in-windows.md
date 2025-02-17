---
title: "Step-by-Step Guide: Resolve Audio Device Not Installed Errors in Windows"
date: 2025-02-14T18:47:42.390Z
updated: 2025-02-17T00:32:08.398Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Guide: Resolve Audio Device Not Installed Errors in Windows"
excerpt: "This Article Describes Step-by-Step Guide: Resolve Audio Device Not Installed Errors in Windows"
thumbnail: https://thmb.techidaily.com/b419546ab6fdd218d829eb22a844376fcf0d2afcf21c79595fda949de5f6b103.jpg
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
<li><a href="https://fox-http.techidaily.com/new-critical-look-at-ustream-plus-alternatives-for-2024/"><u>[New] Critical Look at Ustream, Plus Alternatives for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-revolutionizing-lessons-with-top-screen-recorder-apps/"><u>[New] In 2024, Revolutionizing Lessons with Top Screen Recorder Apps</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-face-unlock-tech-iphone-xs-face-id-versus-samsung/"><u>[Updated] 2024 Approved Face Unlock Tech IPhone X's Face ID Versus Samsung'</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-simplified-path-getting-snapchat-on-macos/"><u>[Updated] 2024 Approved Simplified Path Getting Snapchat on macOS</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-common-issues-how-to-troubleshoot-voice-communication-in-destiny-2/"><u>Fixing Common Issues: How to Troubleshoot Voice Communication in Destiny 2</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-masterfully-convert-and-compress-mp4-with-the-best-encoders-available/"><u>How to Masterfully Convert and Compress MP4 with the Best Encoders Available.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-solve-mouse-right-click-not-working-in-windows-10/"><u>How To Solve Mouse Right Click Not Working in Windows 10</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-c-span-video-hack-a-controocentric-viewpoint/"><u>In 2024, C-Span Video Hack A Controocentric Viewpoint</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-procleanse-top-tier-background-removal-tool/"><u>In 2024, ProCleanse Top-Tier Background Removal Tool</u></a></li>
<li><a href="https://win-howtos.techidaily.com/managing-high-gpu-use-by-the-desktop-window-manager-in-windows-effective-techniques/"><u>Managing High GPU Use by the Desktop Window Manager in Windows: Effective Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-the-classic-start-menu-in-modern-windows-10-systems/"><u>Reviving the Classic Start Menu in Modern Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-media-disconnected-issues-on-your-windows-computer-troubleshooting-steps/"><u>Solving 'Media Disconnected' Issues on Your Windows Computer - Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-resolution-for-execution-restrictions-fixing-access-is-denied-during-setup/"><u>Step-by-Step Resolution for Execution Restrictions: Fixing ‘Access Is Denied’ During Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-overcoming-steam-store-access-problems/"><u>Step-by-Step Solutions: Overcoming Steam Store Access Problems</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-power-of-persuasion-hire-success-stories-1-10/"><u>The Power of Persuasion Hire Success Stories #1-10</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

