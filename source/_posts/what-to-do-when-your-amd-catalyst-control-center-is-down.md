---
title: What to Do When Your AMD Catalyst Control Center Is Down
date: 2024-08-19T07:38:00.093Z
updated: 2024-08-20T07:38:00.093Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes What to Do When Your AMD Catalyst Control Center Is Down
excerpt: This Article Describes What to Do When Your AMD Catalyst Control Center Is Down
thumbnail: https://thmb.techidaily.com/dc54f112c78b3afb0110331eb25c5f493a4d3b2149d6ee352dfe8394d4845198.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-behind-the-scenes-recording-your-facebook-live-stream/"><u>[New] 2024 Approved  Behind the Scenes  Recording Your Facebook Live Stream</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-streamline-your-watching-enabling-youtube-autoplay-in-facebook-feeds-for-2024/"><u>[New] Streamline Your Watching  Enabling YouTube Autoplay in Facebook Feeds for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-how-to-boost-your-windowslinux-performance-and-reduce-shell-induced-high-cpu-use/"><u>[Solved] How to Boost Your Windows/Linux Performance and Reduce Shell-Induced High CPU Use.</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-xbox-game-recording-techniques-for-gamers/"><u>[Updated] 2024 Approved  Xbox Game Recording Techniques for Gamers</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-complete-voice-memo-primer-tips-and-tricks/"><u>2024 Approved  The Complete Voice Memo Primer  Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-unregistered-software-class-errors-on-windows-10-solutions/"><u>Addressing Unregistered Software Class Errors on Windows 10 [Solutions]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/banishing-blackness-solutions-for-a-netflix-visual-glitch/"><u>Banishing Blackness: Solutions for a Netflix Visual Glitch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/computer-freeze-no-more-strategies-for-smooth-operations-and-prevention/"><u>Computer Freeze No More: Strategies for Smooth Operations and Prevention</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ddpair-mini3s-delightful-adventure-in-dashcam-fun-a-must-read-review/"><u>DDPair Mini3's Delightful Adventure in Dashcam Fun - A Must-Read Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-when-facing-microsoft-exchange-unreachable-in-outlook/"><u>Effective Solutions When Facing 'Microsoft Exchange Unreachable' In Outlook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fix-for-msxml3-error-eliminating-issue-0x887a0006-with-precision/"><u>Effortless Fix for MsXML3 Error - Eliminating Issue 0X887A0006 with Precision</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-0x80004005-explained-your-ultimate-solution-for-the-unexplained-glitch/"><u>Error 0X80004005 Explained: Your Ultimate Solution for the Unexplained Glitch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-solving-tips-for-when-windows-cant-find-the-specified-file-or-disk/"><u>Error Solving Tips for When Windows Can’t Find the Specified File or Disk</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-glitched-start-menu-in-windows-11-a-comprehensive-guide/"><u>Fixing the Glitched Start Menu in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/how-does-fbcta-affect-your-social-media-feed/"><u>How Does FBCTA Affect Your Social Media Feed?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-type-without-typing-wrong-characters-solutions-explored/"><u>How to Correctly Type Without Typing Wrong Characters: Solutions Explored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-connected-but-not-connected-issue-with-bluetooth-devices-on-windows-11/"><u>How to Fix 'Connected but Not Connected' Issue with Bluetooth Devices on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-ps4-ce-34878-0-e-codes-and-get-back-in-gaming-mode/"><u>How to Fix PS4 CE-34878-0 E-Codes and Get Back in Gaming Mode</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-windows-10-0x800705b4-issue-with-microsoft-update-a-complete-guide/"><u>How to Fix the Windows 10 0X800705b4 Issue with Microsoft Update: A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-call-of-duty-wwii-error-code-4220-troubleshooting-guide/"><u>How to Resolve Call of Duty: WWII Error Code 4220 - Troubleshooting Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-oppo-reno-10-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Oppo Reno 10 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Motorola Moto G13 | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-obstacles-to-seamless-play-tackling-outriders-pc-malfunctions/"><u>Overcoming Obstacles to Seamless Play: Tackling Outriders' PC Malfunctions</u></a></li>
<li><a href="https://fox-direct.techidaily.com/peak-craft-studio-25-overview-for-2024/"><u>Peak Craft Studio 25 Overview for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reactivating-wi-fi-capability-on-electronics-a-step-by-step-guide/"><u>Reactivating Wi-Fi Capability on Electronics - A Step by Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-the-sudden-shutdown-understanding-error-code-1067-in-windows/"><u>Resolved: Fixing the Sudden Shutdown - Understanding Error Code 1067 in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-outage-at-networking-interface/"><u>Resolved: Outage at Networking Interface</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-for-rectifying-your-windows-10-mouses-unresponsive-right-click-feature/"><u>Solutions for Rectifying Your Windows 10 Mouse's Unresponsive Right-Click Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-inside-how-to-repair-your-unresponsive-dell-wireless-keyboard/"><u>Solutions Inside: How to Repair Your Unresponsive Dell Wireless Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-unresponsive-ps4-mic-a-gamers-guide/"><u>Step-by-Step Fix for Unresponsive PS4 Mic: A Gamer's Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-resolve-windows-device-manager-error-code-28-explained/"><u>Step-by-Step Guide to Resolve Windows Device Manager Error: Code 28 Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-correctly-address-invalid-entry-names-in-directories/"><u>Steps to Correctly Address Invalid Entry Names in Directories</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/tips-to-triple-your-instagram-video-viewers-for-2024/"><u>Tips to Triple Your Instagram Video Viewers for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-eliminating-flicker-problems-in-windows-11-system/"><u>Troubleshooting and Eliminating Flicker Problems in Windows 11 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-common-opengl-errors-in-minecraft-effective-techniques-explored/"><u>Troubleshooting Common OpenGL Errors in Minecraft – Effective Techniques Explored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-minecraft-solutions-for-opengl-errors/"><u>Troubleshooting Minecraft: Solutions for OpenGL Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixing-non-responsive-microphone-issues-in-windows-11/"><u>Troubleshooting: Fixing Non-Responsive Microphone Issues in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-solving-the-continuous-reboot-issue-in-windows-10/"><u>Ultimate Guide: Solving the Continuous Reboot Issue in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-your-pc-stops-working-unexpectedly-and-how-to-fix-it/"><u>Why Your PC Stops Working Unexpectedly & How To Fix It</u></a></li>
</ul></div>
