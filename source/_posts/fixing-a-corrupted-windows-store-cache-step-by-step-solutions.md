---
title: "Fixing a Corrupted Windows Store Cache: Step-by-Step Solutions"
date: 2024-08-15T11:29:49.907Z
updated: 2024-08-16T11:29:49.907Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing a Corrupted Windows Store Cache: Step-by-Step Solutions"
excerpt: "This Article Describes Fixing a Corrupted Windows Store Cache: Step-by-Step Solutions"
thumbnail: https://thmb.techidaily.com/969f33b117977e3c9183a386d2bdc9ab1274e9f63db8d891784a69dcdfd3c683.jpg
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
<li><a href="https://vimeo-videos.techidaily.com/new-best-vimeo-video-downloaders-for-2024/"><u>[New] Best Vimeo Video Downloaders for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-premium-podcast-partners-in-academia/"><u>[New] Premium Podcast Partners in Academia</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-power-of-words-in-marketing-top-20-essentials/"><u>[New] The Power of Words in Marketing - Top 20 Essentials</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-top-rated-apps-for-capturing-and-saving-videos-online/"><u>[New] Top-Rated Apps for Capturing & Saving Videos Online</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elegant-aesthetics-mastering-youtubes-beauty-landscape-for-2024/"><u>[Updated] Elegant Aesthetics  Mastering YouTube's Beauty Landscape for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-gearing-up-for-a-leisurely-view-three-methods-to-tame-video-speed-on-youtube-60-chars-minor-exception-due-to-title-length-but-offers-comprehensive-i/"><u>[Updated] Gearing Up for a Leisurely View  Three Methods to Tame Video Speed on YouTube (60 Chars, Minor Exception Due to Title Length but Offers Comprehensive Insight) for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-clear-screening-for-focused-online-participation/"><u>[Updated] In 2024, Clear Screening for Focused Online Participation</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-increase-views-with-smart-igtv-title-and-summary-edits/"><u>[Updated] In 2024, Increase Views with Smart IGTV Title and Summary Edits</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/banish-blurry-lines-from-your-laptop-screens/"><u>Banish Blurry Lines From Your Laptop Screens</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-this-troubleshooting-steps-for-windows-10s-persistent-update-error-0x800f0922/"><u>Beat This: Troubleshooting Steps for Windows 10'S Persistent Update Error 0X800F0922</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>Best 10 Mock Location Apps Worth Trying On Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-0x80072efd-error-in-windows-11-with-proven-solutions/"><u>Bypassing the 0X80072EFD Error in Windows 11 with Proven Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206298676-complete-guide-to-overcome-the-error-5-notification-in-windows-1178-systems-now-solved/"><u>Complete Guide to Overcome the Error 5 Notification in Windows 11/7/8 Systems – Now Solved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corsair-hs50-headset-mic-repair-guide-troubleshooting-tips-for-improved-audio-output/"><u>Corsair HS50 Headset Mic Repair Guide - Troubleshooting Tips for Improved Audio Output</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-issues-with-your-steelseries-x70-mouse-pen-not-responding-detailed-tutorial-inside/"><u>Diagnosing and Repairing Issues with Your SteelSeries X70 Mouse Pen Not Responding – Detailed Tutorial Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-solutions-for-oculus-tech-hiccups-how-to-tackle-hardware-errors/"><u>DIY Solutions for Oculus Tech Hiccups: How to Tackle Hardware Errors</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/effortlessly-engaging-in-linguistics-expert-advice/"><u>Effortlessly Engaging in Linguistics: Expert Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-restoring-pen-and-touch-sensitivity-after-screen-malfunction/"><u>Expert Advice: Restoring Pen and Touch Sensitivity After Screen Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-unresponsive-apple-magic-mouse-on-macos/"><u>Expert Tips for Repairing Unresponsive Apple Magic Mouse on macOS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/from-dead-screen-to-battlefield-fortnite-launches/"><u>From Dead Screen to Battlefield: Fortnite Launches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-back-in-control-resolving-power-issues-with-your-ps4-controllers-battery/"><u>Get Back in Control - Resolving Power Issues with Your PS4 Controller's Battery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-the-night-light-feature-up-and-running-again-on-your-windows-1011-device/"><u>Getting the Night Light Feature Up and Running Again on Your Windows 10/11 Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-minimize-dwm-gpu-usage-a-5-step-approach-for-windows-users/"><u>How to Minimize DWM GPU Usage: A 5-Step Approach for Windows Users</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-locked-honor-x9b-phone-by-drfone-android/"><u>How to Reset a Locked Honor X9b Phone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-6-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>How to Unlock iPhone 6 without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-is-your-apple-iphone-6-plus-in-security-lockout-proper-ways-to-unlock-by-drfone-ios/"><u>In 2024, Is Your Apple iPhone 6 Plus in Security Lockout? Proper Ways To Unlock</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212531767-keypad-issues-on-your-notebook-running-windows-solutions-for-all-versions/"><u>Keypad Issues on Your Notebook Running Windows? Solutions for All Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/locate-and-install-required-media-driver-quickly-fixed-solution/"><u>Locate & Install Required Media Driver Quickly | Fixed Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203247138-lost-the-icons-on-your-taskbar-revive-them-with-these-4-secrets-for-windows-11-users/"><u>Lost The ICONS on Your Taskbar? Revive Them with These 4 Secrets for Windows 11 Users!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-windows-store-cache-recovery-proven-fixes-revealed/"><u>Master the Art of Windows Store Cache Recovery - Proven Fixes Revealed</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-art-of-display-sharing-with-your-lg-smart-television/"><u>Mastering the Art of Display Sharing with Your LG Smart Television</u></a></li>
<li><a href="https://win-howtos.techidaily.com/maximize-your-gaming-experience-in-windows-11-with-these-key-optimization-techniques/"><u>Maximize Your Gaming Experience in Windows 11 with These Key Optimization Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-scroll-wheel-troubleshooting-tips-for-restoring-functionality-on-a-logitech-mouse/"><u>Overcoming Scroll Wheel Troubleshooting: Tips for Restoring Functionality on a Logitech Mouse.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ps4-network-type-trouble-follow-this-comprehensive-fix-tutorial/"><u>PS4 Network Type Trouble? Follow This Comprehensive Fix Tutorial!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-when-your-steam-store-wont-open-correctly/"><u>Quick Fixes when Your Steam Store Won't Open Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fortnites-unsuccessful-launch/"><u>Resolved Fortnite's Unsuccessful Launch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fix-your-kodi-streams-say-goodbye-to-buffering/"><u>Resolved: Fix Your Kodi Streams - Say Goodbye to Buffering</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-overcoming-setbacks-in-installing-the-windows-10-may-2019-update-v1903/"><u>Resolved! Overcoming Setbacks in Installing the Windows 10 May 2019 Update (V1903)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-excessive-cpu-consumption-by-wudfhostexe-on-windows-11/"><u>Resolving Excessive CPU Consumption by wudfhost.exe on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-lost-touchpad-device-masters-mission/"><u>Restore Lost Touchpad: Device Master's Mission</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-dell-input-devices-troubleshooting-tips-for-keyboards-and-mice-that-wont-work/"><u>Revive Your Dell Input Devices: Troubleshooting Tips for Keyboards and Mice That Won't Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-connection-errors-a-guide-to-reconnecting-with-a-distant-server/"><u>Solving Connection Errors: A Guide to Reconnecting with a Distant Server</u></a></li>
<li><a href="https://extra-support.techidaily.com/soundscapes-for-static-music-in-whatsapp-for-2024/"><u>Soundscapes for Static  Music in WhatsApp for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-overcoming-the-80072ee2-error-in-windows-updates/"><u>Step-by-Step Fixes for Overcoming the 80072EE2 Error in Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tips-for-correcting-the-rpc-server-unavailable-error-on-windows-machines/"><u>Step-by-Step Tips for Correcting the 'RPC Server Unavailable Error' On Windows Machines</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-the-overuse-of-processor-resources-in-windows-sound-card-graphs/"><u>Tackling the Overuse of Processor Resources in Windows Sound Card Graphs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/tech-savvy-strategies-to-maximize-whiteboard-functionality-across-devices/"><u>Tech-Savvy Strategies to Maximize Whiteboard Functionality Across Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-resolving-the-windows-update-failed-with-error-80244019/"><u>Troubleshooting Guide for Resolving the 'Windows Update Failed with Error 80244019'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-when-google-chrome-wont-respond/"><u>Troubleshooting Guide for When Google Chrome Won't Respond</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-digital-boutiques-unique-personalized-present-boxes/"><u>Ultimate Digital Boutiques  Unique, Personalized Present Boxes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-file-explorer-guide-enhance-your-organization-and-efficiency-skills/"><u>Windows 11 File Explorer Guide: Enhance Your Organization & Efficiency Skills!</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/windows-11-gamers-ultimate-playbook-top-5-record-techniques-for-2024/"><u>Windows 11 Gamers' Ultimate Playbook  Top 5 Record Techniques for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winupdate-trouble-learn-how-to-restart-and-resolve-issues-quickly/"><u>WinUpdate Trouble? Learn How to Restart and Resolve Issues Quickly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/your-sd-card-not-detected-heres-the-fix/"><u>Your SD Card Not Detected? Here’s the Fix</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->