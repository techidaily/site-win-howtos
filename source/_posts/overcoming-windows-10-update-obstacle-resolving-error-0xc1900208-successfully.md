---
title: "Overcoming Window's 10 Update Obstacle: Resolving Error 0xC1900208 Successfully"
date: 2024-09-16T02:59:41.549Z
updated: 2024-09-17T18:56:02.780Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming Window's 10 Update Obstacle: Resolving Error 0xC1900208 Successfully"
excerpt: "This Article Describes Overcoming Window's 10 Update Obstacle: Resolving Error 0xC1900208 Successfully"
thumbnail: https://thmb.techidaily.com/f93eb5bd46514b847ac07d099dc18d72eab724476fd27a01a5370f94ffa41df8.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

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
<li><a href="https://fox-http.techidaily.com/new-a-compreran-analysis-asus-proart-pa-329qs-innovations-in-4k-monitoring/"><u>[New] A Compreran Analysis Asus ProArt PA 329Q’s Innovations in 4K Monitoring</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-how-to-add-filters-effects-and-masks-in-google-meet-in-2024/"><u>[New] How to Add Filters, Effects, and Masks in Google Meet, In 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/androidiphone-the-best-selection-of-free-overlays-for-image-enhancement-for-2024/"><u>Android/iPhone The Best Selection of Free Overlays for Image Enhancement for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/deciphering-the-mechanics-of-claude-pro-compared-to-gptplusplus/"><u>Deciphering the Mechanics of Claude Pro Compared to GPT+Plus</u></a></li>
<li><a href="https://win-howtos.techidaily.com/directx-device-setup-complete-after-troubleshooting-guide/"><u>DirectX Device Setup Complete After Troubleshooting Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-supercharge-your-scholarly-studies-the-impact-of-artificial-intelligence-in-academia/"><u>How to Supercharge Your Scholarly Studies: The Impact of Artificial Intelligence in Academia</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-pc-game-crashes-in-nier-automata-solved/"><u>How to Troubleshoot PC Game Crashes in Nier: Automata - Solved!</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-learn-to-access-final-cut-pro-for-free/"><u>In 2024, Learn To Access Final Cut Pro for Free</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-quiet-movies-effective-ways-to-get-your-netflix-audio-working-again/"><u>No More Quiet Movies: Effective Ways to Get Your Netflix Audio Working Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-resolving-plugged-in-but-not-charging-glitches-in-windows-operating-systems/"><u>Solved! Resolving Plugged In but Not Charging Glitches in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-the-notorious-laptop-blackwhite-display-glitch/"><u>Troubleshooting and Repairing the Notorious Laptop Black/White Display Glitch</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151894/7443" target="_top" id="2151894">
  <img src="//a.impactradius-go.com/display-ad/7443-2151894" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151894/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

