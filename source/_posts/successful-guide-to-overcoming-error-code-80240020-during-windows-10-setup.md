---
title: Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
date: 2024-10-19T21:25:14.270Z
updated: 2024-10-21T20:55:39.416Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
excerpt: This Article Describes Successful Guide to Overcoming Error Code #80240020 During Windows 10 Setup
thumbnail: https://thmb.techidaily.com/2e5cadcabaa5bc146e9286cd6ccf5e30c43742afdff538e1080a5add013b39bf.jpg
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-access-top-shorter-video-downloads-for-free-online/"><u>[New] 2024 Approved Access Top Shorter Video Downloads for FREE Online</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-elite-android-and-pc-mkv-software/"><u>[New] 2024 Approved Elite Android & PC MKV Software</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-polarr-mastery-manual-transforming-digital-imagery-with-ease/"><u>[New] Polarr Mastery Manual Transforming Digital Imagery with Ease</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-old-tweet-discovery-mining-twitters-history/"><u>2024 Approved Old Tweet Discovery Mining Twitter's History</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-unlocking-the-secrets-to-altering-your-networks-showcase-picture/"><u>2024 Approved Unlocking the Secrets to Altering Your Network's Showcase Picture</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-your-gpu-experience-by-fixing-inadequate-alpha-blending-support/"><u>Enhance Your GPU Experience by Fixing Inadequate Alpha Blending Support</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-responsive-shift-key-a-comprehensive-guide/"><u>Fixing a Non-Responsive Shift Key: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-your-keyboards-arrow-keys-working-again-with-these-proven-tips/"><u>Get Your Keyboard's Arrow Keys Working Again with These Proven Tips</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mac-and-windows-compatible-srt-boosters-the-elite-list-of-10/"><u>In 2024, Mac & Windows Compatible SRT Boosters The Elite List of 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-fixes-for-windows-error-code-absolutely-31-a-users-handbook/"><u>Mastering Fixes for Windows Error Code Absolutely 31 – A User's Handbook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-kernel-power-hurdle-addressing-windows-error-code-0xc00pressure-to-ensure-a-healthy-environment/"><u>Overcoming the 'Kernel Power' Hurdle: Addressing Windows Error Code 0xC00pressure to Ensure a Healthy Environment.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-a-speedy-shutdown-on-your-windows-10-pc/"><u>Quick Solutions for a Speedy Shutdown on Your Windows 10 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-undetected-bluetooth-hardware-in-windows-11/"><u>Solving the Issue of Undetected Bluetooth Hardware in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-how-to-repair-a-broken-dell-laptop-keys/"><u>Step-by-Step Guide: How to Repair a Broken Dell Laptop Keys</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/the-ultimate-guide-saving-movs-on-windows-10-pro-for-2024/"><u>The Ultimate Guide Saving MOVs on Windows 10 Pro for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-mastering-frequency-adjustment-in-audacity-without-compromising-sound-fidelity/"><u>Updated Mastering Frequency Adjustment in Audacity Without Compromising Sound Fidelity</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100533/7443" target="_top" id="2100533">
  <img src="//a.impactradius-go.com/display-ad/7443-2100533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

