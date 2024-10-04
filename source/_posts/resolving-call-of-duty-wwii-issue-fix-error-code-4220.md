---
title: "Resolving Call of Duty WWII Issue: Fix Error Code 4220"
date: 2024-09-26T18:33:25.438Z
updated: 2024-10-04T15:47:27.149Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Call of Duty WWII Issue: Fix Error Code 4220"
excerpt: "This Article Describes Resolving Call of Duty WWII Issue: Fix Error Code 4220"
thumbnail: https://thmb.techidaily.com/781e8428af43f7240e5d953add419c8aa194f2d4e4f1f7a9a67dc80aa935e243.jpg
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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-turbocharging-fb-media-speed-techniques-revealed/"><u>[New] 2024 Approved Turbocharging FB Media Speed Techniques Revealed</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-cost-efficient-sky-companions-drone-guide-(500/"><u>[New] Cost-Efficient Sky Companions Drone Guide <$500</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-linux-windows-and-mac-10-budget-video-player-options/"><u>2024 Approved Linux, Windows & Mac 10 Budget Video Player Options</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-oppo-find-n3-flip-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Oppo Find N3 Flip in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/enhancing-facebook-viewership-with-obs-broadcasts-for-2024/"><u>Enhancing Facebook Viewership with OBS Broadcasts for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-gionee-f3-pro-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Gionee F3 Pro If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-vanished-desktop-icons-in-windows-11-a-complete-guide/"><u>How to Restore Vanished Desktop Icons in Windows 11: A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-solutions-for-fixing-overwatchs-voice-chat-issues/"><u>Immediate Solutions for Fixing Overwatch's Voice Chat Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-update-recovery-techniques-for-smooth-operations/"><u>Mastering Windows Update Recovery Techniques for Smooth Operations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-for-resolving-the-livekernelevent-117-mistake/"><u>Solutions for Resolving the LiveKernelEvent 117 Mistake</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-nubia-z50-ultra-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Nubia Z50 Ultra Device</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-guide-on-how-to-completely-remove-yourself-from-twitch/"><u>The Ultimate Guide on How to Completely Remove Yourself From Twitch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-no-more-how-to-solve-oddworld-soulstorm-pc-crash-issues/"><u>Trouble No More: How to Solve Oddworld: Soulstorm PC Crash Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-resolve-non-responsive-keyboard-during-login/"><u>Troubleshooting Guide: How to Resolve Non-Responsive Keyboard During Login</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-in-2024-searching-for-free-sports-streaming-sites-look-no-further/"><u>Updated In 2024, Searching for Free Sports Streaming Sites? Look No Further</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

