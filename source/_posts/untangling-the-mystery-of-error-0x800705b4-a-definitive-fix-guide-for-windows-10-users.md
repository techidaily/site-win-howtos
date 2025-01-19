---
title: "Untangling The Mystery of Error 0X800705B4: A Definitive Fix Guide for Windows 10 Users"
date: 2025-01-17T20:16:18.162Z
updated: 2025-01-19T19:11:14.654Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Untangling The Mystery of Error 0X800705B4: A Definitive Fix Guide for Windows 10 Users"
excerpt: "This Article Describes Untangling The Mystery of Error 0X800705B4: A Definitive Fix Guide for Windows 10 Users"
thumbnail: https://thmb.techidaily.com/3ce7ce4cef66cdb03e7ac7e019dea8d112e1795f84ca632563f78a12990cc533.jpg
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
<li><a href="https://screen-capture.techidaily.com/new-the-ultimate-guide-for-professional-use-of-screen-recorder-by-zd-soft/"><u>[New] The Ultimate Guide for Professional Use of Screen Recorder by ZD Soft</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-techniques-for-optimizing-gopro-camera-battery-life/"><u>[Updated] Techniques for Optimizing GoPro Camera Battery Life</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-advanced-editing-workflows-windows-photos-and-story-remix-combo/"><u>2024 Approved Advanced Editing Workflows Windows Photos & Story Remix Combo</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-xiaomi-redmi-k70-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Xiaomi Redmi K70 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-guide-step-by-step-process-for-rebooting-your-keyboard/"><u>Easy Guide: Step-by-Step Process for Rebooting Your Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-when-your-dells-usb-port-stops-responding/"><u>Effective Solutions: When Your Dell's USB Port Stops Responding</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/essential-know-how-record-ipad-display/"><u>Essential Know-How Record iPad Display</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-y78plus-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo Y78+</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-chrome-os-talk-modifiers-selecting-the-top-5-cloud-speech-services/"><u>In 2024, Chrome OS Talk Modifiers Selecting the Top 5 Cloud Speech Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-incoherency/"><u>Keyboard Incoherency</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigate-through-the-stop-error-0xc0000005-expert-strategies-for-fixing-critical-process-died-on-your-windows-machine/"><u>Navigate Through the STOP Error 0XC0000005: Expert Strategies for Fixing Critical Process Died on Your Windows Machine</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/navigating-technology-the-toms-hardware-compendium/"><u>Navigating Technology: The Tom's Hardware Compendium</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-trick-for-restoring-responsiveness-in-laptop-touchpad-scrolls/"><u>The Ultimate Trick for Restoring Responsiveness in Laptop Touchpad Scrolls</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-fixing-failed-windows-10-version-1903-updates/"><u>Troubleshooting Tips: Fixing Failed Windows 10 Version 1903 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-cannot-reach-remote-server-issues/"><u>Ultimate Guide: Resolving 'Cannot Reach Remote Server' Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-full-game-potential-the-critical-role-of-a-d3d11-compatible-gpu-for-running-our-engine-effectively/"><u>Unlocking Full Game Potential: The Critical Role of a D3D11-Compatible GPU for Running Our Engine Effectively</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-make-this-valentines-day-unforgettable-tips-for-creating-a-personalized-video-gift/"><u>Updated 2024 Approved Make This Valentines Day Unforgettable Tips for Creating a Personalized Video Gift</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

