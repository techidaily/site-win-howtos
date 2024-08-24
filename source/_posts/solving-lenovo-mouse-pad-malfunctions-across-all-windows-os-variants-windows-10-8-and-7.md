---
title: Solving Lenovo Mouse Pad Malfunctions Across All Windows OS Variants (Windows 10, 8 & 7)
date: 2024-08-23T14:09:45.345Z
updated: 2024-08-24T14:09:45.345Z
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-supercharge-collaboration-essential-facebook-planners-decoded/"><u>[New] 2024 Approved  Supercharge Collaboration  Essential Facebook Planners Decoded</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-kick-starting-a-captivating-instagram-live/"><u>[New] Kick-Starting a Captivating Instagram Live</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-revamping-memories-editing-in-look-back-videos/"><u>[Updated] 2024 Approved  Revamping Memories  Editing in Look Back Videos</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-best-practices-for-leveraging-b-roll-content/"><u>[Updated] Best Practices for Leveraging B-Roll Content</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-rapid-views-hourlys-youtube-hit-list-for-2024/"><u>[Updated] Rapid Views  Hourly's YouTube Hit List for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-uav-connoisseurs-guide-to-essential-equipment/"><u>2024 Approved  The UAV Connoisseur's Guide to Essential Equipment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-resolution-of-system-resource-shortages-to-ensure-seamless-service-delivery/"><u>Complete Resolution of System Resource Shortages to Ensure Seamless Service Delivery</u></a></li>
<li><a href="https://buynow-help.techidaily.com/comprehensive-evaluation-of-maxoak-185wh-50000mah-power-bank-the-ultimate-all-rounder/"><u>Comprehensive Evaluation of MaxOak 185Wh / 50,000mAh Power Bank - The Ultimate All-Rounder</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-displays-that-dont-support-high-definition-content-protection-hdcp/"><u>Dealing With Displays That Don't Support High-Definition Content Protection (HDCP)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-missing-opencl-dll-files/"><u>Dealing with Missing OpenCL DLL Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-problems-during-the-installation-of-windows-11-update-version-1607/"><u>Diagnosing Problems During the Installation of Windows 11 Update (Version 1607)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211158318-eradicate-unwanted-on-screen-flashing-ultimate-fixes-for-a-steady-point/"><u>Eradicate Unwanted On-Screen Flashing: Ultimate Fixes for a Steady Point</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205707776-explain-how-problem-solving-skills-contribute-to-career-advancement-and-effective-teamwork-in-the-workplace/"><u>Explain How Problem-Solving Skills Contribute to Career Advancement and Effective Teamwork in the Workplace</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-windows-11-touch-display-issues-with-these-5-proven-strategies/"><u>Fix Your Windows 11 Touch Display Issues with These 5 Proven Strategies</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fixing-caught-on-video-code-0xc10100be/"><u>Fixing Caught on Video Code 0XC10100be</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-disappearing-touchpad-pointer-problems-in-windows-11-systems/"><u>Fixing Disappearing Touchpad Pointer Problems in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-startup-failures-your-comprehensive-solution-to-error-code-0xc000007b-on-application-launch/"><u>Fixing Startup Failures: Your Comprehensive Solution to Error Code 0xC000007B on Application Launch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-your-lenovo-mouse-pad-functioning-again-for-windows-users-versions-11-8-and-7/"><u>Get Your Lenovo Mouse Pad Functioning Again for Windows Users (Versions 11, 8, & 7)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unable-to-switch-to-desired-screen-size-error-easily/"><u>How to Fix 'Unable to Switch to Desired Screen Size' Error Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-installation-issues-error-code-0x80070643-on-windows-systems/"><u>How to Overcome Installation Issues (Error Code 0X80070643) on Windows Systems</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-oneplus-nord-n30-5g-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked OnePlus Nord N30 5G in Minutes | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-a-non-responsive-chromecast-device/"><u>How to Troubleshoot a Non-Responsive Chromecast Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/huion-pen-not-responding-5-rapid-repair-techniques-for-artists/"><u>Huion Pen Not Responding? 5 Rapid Repair Techniques for Artists</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-motorola-moto-e13-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Motorola Moto E13 Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-fix-guide-for-directx-encountering-unresolvable-faults/"><u>In-Depth Fix Guide for DirectX Encountering Unresolvable Faults</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/lightstudiokit-econ-budget-umbrella-style-lights/"><u>LightStudioKit Econ: Budget Umbrella Style Lights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-efficient-system-resource-use-curbing-msmpengines-cpu-overuse-on-windows-10-resolved/"><u>Mastering Efficient System Resource Use: Curbing MsMpEngine's CPU Overuse on Windows 10 [RESOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-7-installation-solving-unrecognized-hardware-problems/"><u>Mastering Windows 7 Installation – Solving Unrecognized Hardware Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209460952-playstation-4-trouble-solve-the-mystery-of-error-code-ce-34878-0-today/"><u>PlayStation 4 Trouble? Solve the Mystery of Error Code CE-34878-0 Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-windows-11-bluetooth-not-detected-problem-fast-and-easy-step-by-step-guide/"><u>Resolve Your Windows 11 Bluetooth Not Detected Problem Fast and Easy - Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-steps-to-recover-an-unresponsive-off-screen-window/"><u>Resolved: Steps to Recover an Unresponsive Off-Screen Window</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-boot-issues-in-windows-11-overcoming-freezing-at-startup/"><u>Resolving Boot Issues in Windows 11 - Overcoming Freezing at Startup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-class-registration-issues-in-windows-10-a-comprehensive-guide/"><u>Resolving Class Registration Issues in Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-installation-and-update-complications-for-steam-gaming-software/"><u>Resolving Installation and Update Complications for Steam Gaming Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-mousepad-malfunctions-for-laptops-running-windows-systems/"><u>Resolving Mousepad Malfunctions for Laptops Running Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211255697-revive-your-silent-companion-the-touchpad/"><u>Revive Your Silent Companion - The Touchpad!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-repairing-corsair-keyboards-that-wont-work/"><u>Solution Guide: Repairing Corsair Keyboards That Won't Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-troubleshooting-minecrafts-opengl-issues/"><u>Step-by-Step Guide: Troubleshooting Minecraft's OpenGL Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-fix-windows-hello-not-supported-error-message-on-your-device-running-windows-10/"><u>Steps to Fix Windows Hello Not Supported Error Message on Your Device Running Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/teredo-addressing-the-difficulty-in-achieving-eligibility/"><u>Teredo: Addressing the Difficulty in Achieving Eligibility</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-risks-of-using-ai-like-chatgpt-for-medical-consultation/"><u>The Risks of Using AI Like ChatGPT for Medical Consultation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trim-wmis-firm-grip-on-cores/"><u>Trim WMI's Firm Grip on Cores</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-resolve-sluggish-startup-problems-in-windows-7/"><u>Troubleshoot & Resolve Sluggish Startup Problems in Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-dns-server-issues-discover-4-simple-fixes/"><u>Troubleshooting DNS Server Issues: Discover 4 Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-microsoft-outlook-error-0x80004005-the-unspecified-error-dilemma/"><u>Troubleshooting Guide for Microsoft Outlook Error 0X80004005 - The Unspecified Error Dilemma</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-failed-to-initialize-network-in-dragon-ball-fighterz/"><u>Troubleshooting Steps for 'Failed to Initialize Network' In Dragon Ball FighterZ</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-change-rendering-api-dota-2-error-error-202-fast-solutions-inside/"><u>Troubleshooting the 'Change Rendering API' Dota 2 Error (Error 202^): Fast Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-dealing-with-a-non-functional-backspace-button/"><u>Troubleshooting Tips: Dealing with a Non-Functional Backspace Button</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-d3derrnotavailable-error/"><u>Ultimate Guide: Resolving 'D3DERR_NOTAVAILABLE' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-system-mastering-the-art-of-seamless-windows-11-updates/"><u>Unstick Your System: Mastering the Art of Seamless Windows 11 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/update-guide-enabling-unsupported-graphics-cards-in-fortnite-on-windows-systems/"><u>Update Guide: Enabling Unsupported Graphics Cards in Fortnite on Windows Systems</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-the-complete-guide-to-audio-manipulation-in-avidemux/"><u>Updated 2024 Approved The Complete Guide to Audio Manipulation in Avidemux</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/weaving-in-youtubes-video-selection-a-step-by-step-guide-for-2024/"><u>Weaving in YouTube's Video Selection  A Step-by-Step Guide for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->