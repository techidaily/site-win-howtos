---
title: Solutions for Fixing a Non-Responsive Windows 11 Start Button and Menu
date: 2024-10-03T21:39:23.694Z
updated: 2024-10-09T23:24:45.977Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solutions for Fixing a Non-Responsive Windows 11 Start Button and Menu
excerpt: This Article Describes Solutions for Fixing a Non-Responsive Windows 11 Start Button and Menu
thumbnail: https://thmb.techidaily.com/4f82ef6a5653e12bb243abaaf90bd8a672c270d2a21f27f2fda0ba3002b69992.jpg
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
<li><a href="https://win-community.techidaily.com/1-how-to-overcome-region-code-restrictions-on-sony-dvd-players-fixed-guide/"><u>1. How to Overcome Region Code Restrictions on Sony DVD Players: Fixed Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bring-back-the-buzz-troubleshooting-and-solving-no-sound-issues-on-acer-devices/"><u>Bring Back the Buzz - Troubleshooting and Solving No-Sound Issues on Acer Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypassreset-motorola-phone-screen-passcodepatternpin-by-drfone-android-unlock-android-unlock/"><u>Bypass/Reset Motorola Phone Screen Passcode/Pattern/Pin</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-stop-that-annoying-blinking-cursor-on-your-pcmac/"><u>Easy Steps to Stop That Annoying Blinking Cursor on Your PC/MAC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/entdeckung-der-leistungsfahigkeit-von-abbyy-ocr-server-erfahren-sie-mehr-aus-zufriedenheitstranskripten/"><u>Entdeckung Der Leistungsfähigkeit Von ABBYY OCR-Server: Erfahren Sie Mehr Aus Zufriedenheitstranskripten</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-synaptics-touchpad-not-scrolling-issue-in-windows-11/"><u>Fix Synaptics Touchpad Not Scrolling Issue in Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-the-activation-lock-on-your-ipad-and-iphone-8-without-apple-account-by-drfone-ios/"><u>How to Remove the Activation Lock On your iPad and iPhone 8 without Apple Account</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-5-from-vivo-y28-5g-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 5 from Vivo Y28 5G to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/mastering-the-art-of-managing-and-editing-iphone-snapshots-tips-and-solutions/"><u>Mastering the Art of Managing & Editing iPhone Snapshots: Tips & Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-hurdle-of-microsoft-error-code-0x800f0831-a-simple-solution/"><u>Overcoming the Hurdle of Microsoft Error Code 0X800f0831: A Simple Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206694721-revive-your-steelseries-arctis-5-mic-expert-solutions-to-get-it-working-again/"><u>Revive Your SteelSeries Arctis 5 Mic: Expert Solutions to Get It Working Again</u></a></li>
<li><a href="https://win-able.techidaily.com/roblox-hangup-overcoming-the-perpetual-loading-dilemma/"><u>Roblox Hangup: Overcoming the Perpetual 'Loading' Dilemma</u></a></li>
<li><a href="https://article-posts.techidaily.com/seamless-edits-navigating-photoshops-eraser-function-for-2024/"><u>Seamless Edits Navigating Photoshop’s Eraser Function for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-the-notorious-minecraft-error-n405/"><u>Step-by-Step Guide: Correcting the Notorious Minecraft Error N405</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997717/19272" target="_top" id="1997717">
  <img src="//a.impactradius-go.com/display-ad/19272-1997717" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997717/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

