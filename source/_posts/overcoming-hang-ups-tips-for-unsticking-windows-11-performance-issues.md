---
title: "Overcoming Hang-Ups: Tips for Unsticking Windows 11 Performance Issues"
date: 2024-08-15T11:36:17.910Z
updated: 2024-08-16T11:36:17.910Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming Hang-Ups: Tips for Unsticking Windows 11 Performance Issues"
excerpt: "This Article Describes Overcoming Hang-Ups: Tips for Unsticking Windows 11 Performance Issues"
thumbnail: https://thmb.techidaily.com/11e98257d7e7257e5883dcc5757d573b33d04f0ecfefae2f5882a90863822c25.png
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
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-discovering-clarity-in-your-craft-our-choice-of-top-12-vlogging-cameras/"><u>[Updated] 2024 Approved  Discovering Clarity in Your Craft  Our Choice of Top 12 Vlogging Cameras</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-video-aspects-online/"><u>[Updated] Mastering Video Aspects Online</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-sizing-up-how-to-make-videos-work-in-instagram-bests/"><u>[Updated] Sizing Up  How to Make Videos Work in Instagram Bests</u></a></li>
<li><a href="https://win-howtos.techidaily.com/key-not-responding-here-are-proven-ways-to-restore-its-functionality/"><u>@ Key Not Responding? Here Are Proven Ways to Restore Its Functionality!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-capturing-creativity-mobile-gadgets-ranking-leaders/"><u>2024 Approved  Capturing Creativity  Mobile Gadgets Ranking Leaders</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-stardews-ultimate-customization-guide-the-top-7-mods-listed/"><u>2024 Approved  Stardew's Ultimate Customization Guide  The Top 7 Mods Listed</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-samsung-galaxy-f14-5g-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Samsung Galaxy F14 5G to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/after-effects-templates-crafting-stories-one-text-at-a-time-for-2024/"><u>After Effects Templates  Crafting Stories One Text at a Time for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/compatibility-issue-display-does-not-recognize-hdcp-protocols/"><u>Compatibility Issue: Display Does Not Recognize HDCP Protocols</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/control-de-tempo-con-botones-inicio-eficaz/"><u>Control De Tempo Con Botones: Inicio Eficaz</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-unwanted-automatic-restart-cycles-when-powering-off-windows-11-devices/"><u>Dealing With Unwanted Automatic Restart Cycles When Powering Off Windows 11 Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/dive-into-chatgpt-written-world-top-6-game-journeys/"><u>Dive Into ChatGPT' Written World: Top 6 Game Journeys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-persistent-reboot-problems-in-windows-10/"><u>Easy Fixes for Persistent Reboot Problems in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-fixing-cast-to-device-failures-in-windows-10-systems/"><u>Effective Solutions for Fixing 'Cast to Device' Failures in Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/errtoomanyredirects-clear-it-up-in-minutes-with-these-tips/"><u>ERR_TOO_MANY_REDIRECTS? Clear It Up in Minutes with These Tips</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/essential-skills-importing-snapchat-images-into-device-gallery/"><u>Essential Skills  Importing Snapchat Images Into Device Gallery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-webcam-back-on-track-a-guide-for-hp-laptops-on-windows-10/"><u>Getting Your Webcam Back on Track: A Guide for HP Laptops on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-fixing-windows-could-not-be-installed-error-with-code-80240020-on-your-pc/"><u>Guide to Fixing 'Windows Could Not Be Installed' Error with Code 80240020 on Your PC</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-lenovo-mouse-pad-problems-in-various-windows-systems/"><u>How to Resolve Lenovo Mouse Pad Problems in Various Windows Systems</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-10-best-zoom-alternatives-deskop-and-mobile/"><u>In 2024, 10 Best Zoom Alternatives [Deskop & Mobile]</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-zte-blade-a73-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on ZTE Blade A73 5G Phones with/without a PC</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-narrative-noble-order-honors-hexagon/"><u>In 2024, Narrative Noble Order - Honor's Hexagon</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ps4-power-dilemma-no-more-solve-your-controllers-charging-woes-here/"><u>PS4 Power Dilemma No More - Solve Your Controller's Charging Woes Here</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-compatibility-woes-of-wd-my-passport-ultra-with-the-windows-operating-system/"><u>Resolved: Compatibility Woes of WD My Passport Ultra with the Windows Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-user-profile-service-failure-during-sign-in-on-windows-1011-a-step-by-step-guide/"><u>Resolving 'User Profile Service' Failure During Sign-In on Windows 10/11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-sound-setbacks-astro-a40-microphone-not-working-guide/"><u>Resolving Sound Setbacks: Astro A40 Microphone Not Working Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-windows-11-touch-screen-effective-fixes-you-must-know-5/"><u>Revive Your Windows 11 Touch Screen: Effective Fixes You Must Know (5)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-persistent-usb-mouse-connection-issues-a-comprehensive-guide/"><u>Solving Persistent USB Mouse Connection Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-repairing-the-troublesome-red-screen-in-windows-10/"><u>Step-by-Step Guide: Repairing the Troublesome Red Screen in Windows 10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-fix-for-offline-hp-desktop/"><u>Successful Fix for Offline HP Desktop</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-ultimate-guide-to-free-high-quality-subtitle-tools-for-2024/"><u>The Ultimate Guide to FREE, High-Quality Subtitle Tools for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205491215-troubleshooting-nonfunctional-usb-ports-on-windows-1011-fixed/"><u>Troubleshooting Nonfunctional USB Ports on Windows 10/11 - Fixed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723201556389-troubleshooting-overwatch-voice-chat-malfunctions-simple-solutions/"><u>Troubleshooting Overwatch Voice Chat Malfunctions: Simple Solutions!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211779531-twitch-troubles-heres-how-you-can-resolve-error-4000-effectively/"><u>Twitch Troubles? Here's How You Can Resolve Error 4000 Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fixes-for-the-persistent-error-code-0x800705b4-on-your-windows-10-system/"><u>Ultimate Fixes for the Persistent Error Code 0X800705b4 on Your Windows 10 System</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/uncovering-invisible-challenges-in-vr/"><u>Uncovering Invisible Challenges in VR</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-the-potential-of-gpt-4-collectively/"><u>Unlocking the Potential of GPT-4 Collectively</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-top-rated-weather-stations-for-homes/"><u>Unveiling the Top-Rated Weather Stations for Homes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/wheres-the-magic-explore-real-world-hidden-gems-through-location-services/"><u>Where's the Magic? Explore Real-World Hidden Gems Through Location Services</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->