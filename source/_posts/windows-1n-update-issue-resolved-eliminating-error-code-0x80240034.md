---
title: "Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
date: 2024-10-14T19:04:23.480Z
updated: 2024-10-15T19:38:05.240Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
excerpt: "This Article Describes Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
thumbnail: https://thmb.techidaily.com/d44c84cbf0699642eded061365e62aa884811112a5aa8ff88c8335f623b0d0e8.jpg
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
<li><a href="https://digital-screen-recording.techidaily.com/new-unlocking-google-meets-whiteboard-capabilities-on-diverse-tech-ecosystems-for-2024/"><u>[New] Unlocking Google Meet's Whiteboard Capabilities on Diverse Tech Ecosystems for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-crafting-success-the-premier-list-of-ai-namesmiths/"><u>2024 Approved Crafting Success The Premier List of AI Namesmiths</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-slomo-app-assessment-insights/"><u>2024 Approved Ultimate SloMo App Assessment - Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-windows-11-freezing-problems-effective-fixes-for-a-smoother-experience/"><u>Dealing with Windows 11 Freezing Problems: Effective Fixes for a Smoother Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/exploring-top-techniques-for-fixing-windows-10-issues-with-sfc-and-dism/"><u>Exploring Top Techniques for Fixing Windows 10 Issues with SFC & DISM</u></a></li>
<li><a href="https://vp-tips.techidaily.com/listeners-lexicon-selecting-solid-offline-recording-tools/"><u>Listeners' Lexicon Selecting Solid Offline Recording Tools</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcome-the-launch-hurdle-essential-troubleshooting-steps-for-cyberpunk-2077/"><u>Overcome the Launch Hurdle: Essential Troubleshooting Steps for Cyberpunk 2077</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210992498-resolved-issues-with-total-war-rome-remastered-no-more-crashing/"><u>Resolved Issues with Total War: Rome Remastered - No More Crashing</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-vivo-y100i-by-fonelab-android-recover-data/"><u>The way to get back lost data from Vivo Y100i</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-6-ways-to-transfer-text-messages-from-motorola-moto-g73-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 6 Ways to Transfer Text Messages from Motorola Moto G73 5G to Other Android Devices | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-locked-up-windows-keyboard-buttons/"><u>Troubleshooting and Repairing Locked-Up Windows Keyboard Buttons</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-error-0x80300024-problems/"><u>Unraveling Windows' Error 0X80300024 Problems</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925468/19272" target="_top" id="1925468">
  <img src="//a.impactradius-go.com/display-ad/19272-1925468" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925468/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

