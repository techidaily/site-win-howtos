---
title: "Win11 Speeds Up: Resolving High WMI CPU Consumption"
date: 2024-10-13T01:34:51.648Z
updated: 2024-10-15T23:56:42.633Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Win11 Speeds Up: Resolving High WMI CPU Consumption"
excerpt: "This Article Describes Win11 Speeds Up: Resolving High WMI CPU Consumption"
thumbnail: https://thmb.techidaily.com/c18d888464621b9b20ff1e9897c3e6fc08590ad7205eab6f350d2eff8745d04c.jpg
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
<li><a href="https://youtube-tips.techidaily.com/ed-mastering-keywords-the-best-7-no-cost-youtube-taggers/"><u>[Updated] Mastering Keywords The Best 7 No-Cost Youtube Taggers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-uniting-slack-and-filmora-for-ultimate-collaborative-gatherings/"><u>[Updated] Uniting Slack and Filmora for Ultimate Collaborative Gatherings</u></a></li>
<li><a href="https://buynow-info.techidaily.com/bluetooth-battle-royale-apple-airpods-pro-versus-samsung-buds-pro/"><u>Bluetooth Battle Royale: Apple AirPods Pro versus Samsung Buds Pro</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-a-hit-solo-podcast-trendsetting-tips-for-2024/"><u>Crafting a Hit Solo Podcast Trendsetting Tips for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decode-and-defuse-msmpengineexes-greedy-cpu-behavior-in-windows-10-detailed-steps-to-resolve/"><u>Decode and Defuse MsMpEngine.exe's Greedy CPU Behavior in Windows 10 - Detailed Steps to Resolve</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-fix-unresponsive-letters-in-microsofts-new-os-windows-11-keyboard-issues/"><u>Guide to Fix Unresponsive Letters in Microsoft's New OS, Windows 11 Keyboard Issues</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-13-pro-max-to-the-previous-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 13 Pro Max to the Previous iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-remedies-for-chromes-unresolved-domain-error-errnamenotfound/"><u>Immediate Remedies for Chrome's Unresolved Domain Error (ERR_NAME_NOT_FOUND)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/journey-into-the-enigma-discovering-hidden-emoji-messages/"><u>Journey Into the Enigma Discovering Hidden Emoji Messages</u></a></li>
<li><a href="https://vp-tips.techidaily.com/proiphone-photo-techniques-for-beginners/"><u>Proiphone Photo Techniques for Beginners</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-problem-of-failed-steam-updates-a-step-by-step-guide/"><u>Resolving the Problem of Failed Steam Updates – A Step-by-Step Guide</u></a></li>
<li><a href="https://buynow-help.techidaily.com/revving-up-entertainment-with-the-holy-stone-cartoon-race-car-a-thorough-review/"><u>Revving up Entertainment with the Holy Stone Cartoon Race Car - A Thorough Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-display-dilemmas-getting-your-aoc-monitor-up-and-running-in-windows-10-environment/"><u>Solving Display Dilemmas: Getting Your AOC Monitor Up and Running in Windows 10 Environment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-windows-network-error-0x800704cf-explained-and-fixed/"><u>Solving the Mystery: Windows Network Error 0X800704CF Explained and Fixed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-faulty-windows-7-updates-a-comprehensive-guide-guide-and-helpful-tips/"><u>Step-by-Step Fix for Faulty Windows 7 Updates – A Comprehensive Guide (Guide & Helpful Tips)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-the-user-profile-service-error-during-your-sign-in-to-windows-1011/"><u>Step-by-Step Fixes for 'The User Profile Service' Error During Your Sign-In to Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-laptop-trackpad-problems-in-windows-operating-systems-1087-expert-tips/"><u>Troubleshooting Laptop TrackPad Problems in Windows Operating Systems (10/8/7): Expert Tips</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-final-cut-pro-x-tutorial-l-cuts-and-j-cuts/"><u>Updated In 2024, Final Cut Pro X Tutorial L-Cuts and J-Cuts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/winxvideo-artificial-intelligence-solutions-comprehensive-faq-and-response-guide/"><u>Winxvideo Artificial Intelligence Solutions: Comprehensive FAQ & Response Guide</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

