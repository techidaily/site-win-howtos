---
title: "Resolved: Identifying and Fixing Windows Update Database Issues on Windows 11"
date: 2024-08-23T14:03:18.772Z
updated: 2024-08-24T14:03:18.772Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Identifying and Fixing Windows Update Database Issues on Windows 11"
excerpt: "This Article Describes Resolved: Identifying and Fixing Windows Update Database Issues on Windows 11"
thumbnail: https://thmb.techidaily.com/255a2b0d86b70a9b8b182a32b7f077670444b2206bc46e01ddb9543cc9317ad5.png
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
<li><a href="https://video-capture.techidaily.com/new-goovision-pro-high-quality-chromecasting/"><u>[New] GooVision Pro  High-Quality Chromecasting</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-science-of-quadcopters-understanding-their-flight-patterns/"><u>[New] The Science of Quadcopters  Understanding Their Flight Patterns</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-from-followers-to-fans-5-essential-instagram-tactics-for-influencers/"><u>[Updated] From Followers to Fans  5 Essential Instagram Tactics for Influencers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-professional-ppt-recording-tactics-and-tricks-for-2024/"><u>[Updated] Professional PPT Recording Tactics and Tricks for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premium-action-recording-in-faceview-option/"><u>2024 Approved  Premium Action Recording  In-Faceview Option</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/beginners-guide-to-solving-helldivers-ii-launching-glitch-addressing-the-black-screen-problem/"><u>Beginner's Guide to Solving Helldivers II Launching Glitch: Addressing the Black Screen Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-displays-that-dont-support-high-definition-content-protection-hdcp/"><u>Dealing With Displays That Don't Support High-Definition Content Protection (HDCP)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-missing-opencl-dll-files/"><u>Dealing with Missing OpenCL DLL Files</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/determining-which-language-will-benefit-me-most/"><u>Determining Which Language Will Benefit Me Most</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205707776-explain-how-problem-solving-skills-contribute-to-career-advancement-and-effective-teamwork-in-the-workplace/"><u>Explain How Problem-Solving Skills Contribute to Career Advancement and Effective Teamwork in the Workplace</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-windows-11-touch-display-issues-with-these-5-proven-strategies/"><u>Fix Your Windows 11 Touch Display Issues with These 5 Proven Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-disappearing-touchpad-pointer-problems-in-windows-11-systems/"><u>Fixing Disappearing Touchpad Pointer Problems in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-startup-failures-your-comprehensive-solution-to-error-code-0xc000007b-on-application-launch/"><u>Fixing Startup Failures: Your Comprehensive Solution to Error Code 0xC000007B on Application Launch</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-activate-group-policy-editor-gpeditmsc-on-non-professional-windows-versions/"><u>How to Activate Group Policy Editor (gpedit.msc) on Non-Professional Windows Versions</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unable-to-switch-to-desired-screen-size-error-easily/"><u>How to Fix 'Unable to Switch to Desired Screen Size' Error Easily</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-vivo-y02t-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlocking-the-power-of-iphones-high-dynamic-range/"><u>In 2024, Unlocking the Power of iPhone's High Dynamic Range</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-the-most-recent-drivers-for-your-corsair-k55-controller-step-by-step-instructions/"><u>Install the Most Recent Drivers for Your Corsair K55 Controller - Step-by-Step Instructions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-efficient-system-resource-use-curbing-msmpengines-cpu-overuse-on-windows-10-resolved/"><u>Mastering Efficient System Resource Use: Curbing MsMpEngine's CPU Overuse on Windows 10 [RESOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-7-installation-solving-unrecognized-hardware-problems/"><u>Mastering Windows 7 Installation – Solving Unrecognized Hardware Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-steps-to-recover-an-unresponsive-off-screen-window/"><u>Resolved: Steps to Recover an Unresponsive Off-Screen Window</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-boot-issues-in-windows-11-overcoming-freezing-at-startup/"><u>Resolving Boot Issues in Windows 11 - Overcoming Freezing at Startup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-installation-and-update-complications-for-steam-gaming-software/"><u>Resolving Installation and Update Complications for Steam Gaming Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211255697-revive-your-silent-companion-the-touchpad/"><u>Revive Your Silent Companion - The Touchpad!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-repairing-corsair-keyboards-that-wont-work/"><u>Solution Guide: Repairing Corsair Keyboards That Won't Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-fix-windows-hello-not-supported-error-message-on-your-device-running-windows-10/"><u>Steps to Fix Windows Hello Not Supported Error Message on Your Device Running Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/teredo-addressing-the-difficulty-in-achieving-eligibility/"><u>Teredo: Addressing the Difficulty in Achieving Eligibility</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trim-wmis-firm-grip-on-cores/"><u>Trim WMI's Firm Grip on Cores</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-resolve-sluggish-startup-problems-in-windows-7/"><u>Troubleshoot & Resolve Sluggish Startup Problems in Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-microsoft-outlook-error-0x80004005-the-unspecified-error-dilemma/"><u>Troubleshooting Guide for Microsoft Outlook Error 0X80004005 - The Unspecified Error Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-change-rendering-api-dota-2-error-error-202-fast-solutions-inside/"><u>Troubleshooting the 'Change Rendering API' Dota 2 Error (Error 202^): Fast Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-dealing-with-a-non-functional-backspace-button/"><u>Troubleshooting Tips: Dealing with a Non-Functional Backspace Button</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-d3derrnotavailable-error/"><u>Ultimate Guide: Resolving 'D3DERR_NOTAVAILABLE' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-system-mastering-the-art-of-seamless-windows-11-updates/"><u>Unstick Your System: Mastering the Art of Seamless Windows 11 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/update-guide-enabling-unsupported-graphics-cards-in-fortnite-on-windows-systems/"><u>Update Guide: Enabling Unsupported Graphics Cards in Fortnite on Windows Systems</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->