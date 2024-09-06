---
title: How to Break Free From the Restart Cycle in Windows 10/11 - A Comprehensive Guide
date: 2024-09-05T10:14:47.314Z
updated: 2024-09-06T10:14:47.314Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Break Free From the Restart Cycle in Windows 10/11 - A Comprehensive Guide
excerpt: This Article Describes How to Break Free From the Restart Cycle in Windows 10/11 - A Comprehensive Guide
thumbnail: https://thmb.techidaily.com/545f7379c0befa5a44cab74ccb395e1f4653a53c66c0461613d4a49d7a7f9a57.jpg
---

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120861/26400?prodsku=Saturn" target="_top" id="2120861">
  <img src="//a.impactradius-go.com/display-ad/26400-2120861" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120861/26400?prodsku=Saturn" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115942/19272" target="_top" id="2115942">
  <img src="//a.impactradius-go.com/display-ad/19272-2115942" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115942/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115945/19272" target="_top" id="2115945">
  <img src="//a.impactradius-go.com/display-ad/19272-2115945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115945/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-expert-picks-our-1-10-list-of-camera-lenses-for-the-best-shots/"><u>[New] 2024 Approved  Expert Picks  Our #1-10 List of Camera Lenses for the Best Shots</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-fixing-problematic-youtube-shorts-thumbnails-display-for-2024/"><u>[New] Fixing Problematic YouTube Shorts Thumbnails Display for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-optimal-storage-expansion-for-sony-a7c-for-2024/"><u>[New] Optimal Storage Expansion for Sony A7C for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-elevate-video-editing-expert-use-of-obs-on-mobile-devices/"><u>[Updated] In 2024, Elevate Video Editing  Expert Use of OBS on Mobile Devices</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-embellish-videos-and-stories-with-charts-notes-and-more/"><u>[Updated] In 2024, Embellish Videos & Stories with Charts, Notes & More</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-techniques-for-capturing-and-storing-android-and-mac-snaps/"><u>[Updated] Techniques for Capturing and Storing Android & Mac Snaps</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-techniques-for-transforming-twitter-vids-to-mp3-audios/"><u>2024 Approved  Techniques for Transforming Twitter Vids to MP3 Audios</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bid-farewell-to-shockwave-flash-errors-on-google-chrome-with-this-comprehensive-fix/"><u>Bid Farewell to Shockwave Flash Errors on Google Chrome with This Comprehensive Fix</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-correct-non-responsive-casting-devices-in-windows-11-environments/"><u>Diagnose & Correct Non-Responsive Casting Devices in Windows 11 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-the-0xc00000e9-blue-screen-of-death-on-your-pc-an-easy-guide/"><u>Diagnosing and Repairing the 0Xc00000e9 Blue Screen of Death on Your PC: An Easy Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-restoring-ethernet-connections-for-windows-10-and-7-computers/"><u>Diagnosing and Restoring Ethernet Connections for Windows 10 and 7 Computers</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-toms-tech-insights-and-reviews-your-guide-to-the-latest-gadgets/"><u>Exploring Tom's Tech Insights & Reviews - Your Guide to the Latest Gadgets</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721471285610-fix-your-iphones-missing-voicemail-in-just-9-simple-ways/"><u>Fix Your iPhone's Missing Voicemail in Just 9 Simple Ways!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixation-of-windows-failure-to-connect-with-system-event-management-protocols-successfully/"><u>Fixation of Windows Failure to Connect with System Event Management Protocols Successfully</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-google-pixel-7a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Google Pixel 7a | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210507695-guide-to-restoring-bluetooth-functionality-in-windows-11-instantly-and-easily/"><u>Guide to Restoring Bluetooth Functionality in Windows 11 Instantly & Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-disabling-the-touchpad-when-using-an-external-mouse-in-win11/"><u>Guide: Disabling the Touchpad when Using an External Mouse in Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-steam-file-access-denied-problem/"><u>How to Fix Steam File Access Denied Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-your-bluetooth-keyboard-when-it-wont-connect-to-a-computer/"><u>How to Fix Your Bluetooth Keyboard When It Won't Connect to a Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-systemprofile-desktop-missing-from-cwindows-in-windows-1087/"><u>How to Fix: SystemProfile Desktop Missing From C:\\Windows in Windows 10/8/7</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-stolen-apple-iphone-xr-in-different-conditionsin-by-drfone-ios/"><u>In 2024, How To Unlock Stolen Apple iPhone XR In Different Conditionsin</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-stutter-on-windows-10-heres-how-you-can-fix-it/"><u>Keyboard Stutter on Windows 10? Here’s How You Can Fix It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/league-of-legends-update-woes-heres-how-you-can-fix-those-dragging-downloads/"><u>League of Legends Update Woes? Here's How You Can Fix Those Dragging Downloads!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/next-generation-tkis-have-been-developed-to-overcome-some-forms-of-resistance/"><u>Next-Generation TKIs Have Been Developed to Overcome some Forms of Resistance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-black-screen-error-expert-strategies-for-your-dell-notebook-revival/"><u>Overcoming Black Screen Error: Expert Strategies for Your Dell Notebook Revival</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-troubleshooting-steps-to-overcome-the-windows-update-error-0x80070002/"><u>Quick Troubleshooting Steps to Overcome the Windows Update Error 0X80070002</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-youtube-sound-issues-in-windows-10-a-step-by-step-guide/"><u>Resolving YouTube Sound Issues in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/run-windows-update/"><u>Run Windows Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-for-non-functional-fn-keys-a-step-by-step-approach-for-asus-laptop-users/"><u>Solution Guide for Non-Functional Fn Keys: A Step-by-Step Approach for ASUS Laptop Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-connectivity-issues-with-a-broken-corsair-hs50-headset-mic/"><u>Solving Connectivity Issues with a Broken Corsair HS50 Headset Mic</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-troubleshooting-unknown-usb-device-detected-and-port-reset-failures-on-windows-11/"><u>Solving the Mystery: Troubleshooting 'Unknown USB Device Detected' And Port Reset Failures on Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-to-accessing-facetime-on-your-windows-pc/"><u>Step-by-Step Guide to Accessing FaceTime on Your Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-correct-the-error-in-com-surrogate-service-and-prevent-crashes/"><u>Steps to Correct the 'Error in COM Surrogate Service' And Prevent Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-frustration-with-these-fast-and-effective-ways-to-fix-csgo-crashes/"><u>Stop Frustration with These Fast and Effective Ways to Fix CS:GO Crashes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-why-your-windows-11-pc-cant-find-bluetooth-gadgets-resolved/"><u>Troubleshooting: Why Your Windows 11 PC Can't Find Bluetooth Gadgets (Resolved)</u></a></li>
<li><a href="https://techidaily.com/unlock-a-disable-iphone-8-plus-using-icloud-website-by-drfone-ios-unlock-ios-unlock/"><u>Unlock a disable iPhone 8 Plus using icloud website</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-windows-update-glitches-a-comprehensive-fix-guide/"><u>Winning Against Windows Update Glitches: A Comprehensive Fix Guide</u></a></li>
</ul></div>
