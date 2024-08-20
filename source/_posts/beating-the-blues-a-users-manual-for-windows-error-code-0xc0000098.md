---
title: "Beating the Blues: A User's Manual for Windows Error Code 0xC0000098"
date: 2024-08-19T07:28:31.537Z
updated: 2024-08-20T07:28:31.537Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Beating the Blues: A User's Manual for Windows Error Code 0xC0000098"
excerpt: "This Article Describes Beating the Blues: A User's Manual for Windows Error Code 0xC0000098"
thumbnail: https://thmb.techidaily.com/84523bff91adaad5f05da4dc5462c4e758d2c84a6b7c5d09810fe5f525ef9fc4.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://win-howtos.techidaily.com/fixed-usb-ports-not-working-in-windows-1011/"><u>[Fixed] USB Ports Not Working in Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-excessive-windows-cpu-usage-subdued-by-interruptions/"><u>[RESOLVED] Excessive Windows CPU Usage Subdued by Interruptions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-odins-progeny-clash-of-titans/"><u>[Updated] 2024 Approved  Odin’s Progeny  Clash of Titans</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-the-comprehensible-guide-to-enhancing-your-facebook-live-experience/"><u>[Updated] 2024 Approved  The Comprehensible Guide to Enhancing Your Facebook Live Experience</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-transforming-gameplay-discovering-the-seven-stars-of-stardew-updates/"><u>[Updated] 2024 Approved  Transforming Gameplay  Discovering the Seven Stars of Stardew Updates</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-a-comprehensive-look-at-securing-background-visuals/"><u>[Updated] A Comprehensive Look at Securing Background Visuals</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-the-route-to-a-great-twitch-recording-journey/"><u>[Updated] In 2024, The Route to a Great Twitch Recording Journey</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-oppo-find-x6-pro-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Oppo Find X6 Pro to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/amplify-your-windows-10-audio-through-new-drivers/"><u>Amplify Your Windows 10 Audio Through New Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/arctis-5-headset-microphone-troubleshooting-fixes-for-non-functional-mic-issues/"><u>Arctis 5 Headset Microphone Troubleshooting: Fixes for Non-Functional Mic Issues</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/breaking-language-barriers-with-i-love-you-today/"><u>Breaking Language Barriers with 'I Love You' Today</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/conversational-openers-starting-conversations-in-china/"><u>Conversational Openers: Starting Conversations in China</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corrective-actions-for-the-infamous-error-0x80071ac3-volume-issue/"><u>Corrective Actions for the Infamous Error 0X80071AC3: Volume Issue</u></a></li>
<li><a href="https://fox-info.techidaily.com/decoding-the-capabilities-in-samsungs-newest-photo-software/"><u>Decoding the Capabilities in Samsung's Newest Photo Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-resolve-non-functional-ethernet-networking-in-windows-107/"><u>Easy Steps to Resolve Non-Functional Ethernet Networking in Windows 10/7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/event-1000-issues-in-windows-operating-systems-solutions-for-versions-7-8-and-10/"><u>Event 1000 Issues in Windows Operating Systems - Solutions for Versions 7, 8 and 10</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/experience-exceptional-sound-quality-klipschs-flexus-200/"><u>Experience Exceptional Sound Quality: Klipsch's Flexus 200</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-solutions-for-when-your-usb-hdmi-connection-wont-connect/"><u>Expert Solutions for When Your USB-HDMI Connection Won't Connect</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-correct-unidentified-usb-hardware-issues-and-port-reset-failures-on-windows-10-machines/"><u>Expert Tips to Correct Unidentified USB Hardware Issues and Port Reset Failures on Windows 10 Machines</u></a></li>
<li><a href="https://win-howtos.techidaily.com/five-effective-methods-to-repair-a-malfunctioning-screen-on-your-windows-11-pc/"><u>Five Effective Methods to Repair a Malfunctioning Screen on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-windows-driver-energy-management-problems-quickly-and-easily/"><u>Fix Windows Driver Energy Management Problems Quickly and Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-corrupted-windows-store-cache-step-by-step-solutions/"><u>Fixing a Corrupted Windows Store Cache: Step-by-Step Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-silent-issues-restoring-audio-on-your-acer-device/"><u>Fixing Silent Issues: Restoring Audio on Your Acer Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gameplay-initiates-pc-reboot/"><u>Gameplay Initiates PC Reboot</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-restoring-your-steam-games-after-missing-file-issues-fixed/"><u>Guide To Restoring Your Steam Games After Missing File Issues [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-printer-driver-not-found-error-on-windows-systems/"><u>How to Fix 'Printer Driver Not Found' Error on Windows Systems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-oppo-reno-11-5g-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Oppo Reno 11 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-touchpad-functionality-when-scrolling-fails-in-windows-11/"><u>How to Restore Touchpad Functionality When Scrolling Fails in Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-honor-90-lite-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Honor 90 Lite FRP Bypass With Best Methods</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Xiaomi 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-limitations-for-personalizing-your-computer-navigating-it-rules-on-windows/"><u>Overcoming Limitations for Personalizing Your Computer: Navigating IT Rules on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-for-off-screen-windows-how-to-bring-them-back-visible-on-your-monitor/"><u>Quick Fix for Off-Screen Windows: How to Bring Them Back Visible on Your Monitor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/razer-keyboard-not-glowing-common-issues-and-fixes-discovered/"><u>Razer Keyboard Not Glowing: Common Issues and Fixes Discovered!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/razer-keyboards-not-glowing-heres-how-to-restore-their-brightness/"><u>Razer Keyboards Not Glowing? Here's How to Restore Their Brightness!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixes-for-your-pc-when-it-gets-stuck-at-boot-up/"><u>Resolved: Fixes for Your PC When It Gets Stuck at Boot Up</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-fix-corrupted-windows-store-cache/"><u>Resolved: How to Fix Corrupted Windows Store Cache</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-typing-issues-on-your-keyboard-are-now-fixed/"><u>Resolved: Typing Issues on Your Keyboard Are Now Fixed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-ineterr-missing-resource-issue-a-step-by-step-guide/"><u>Resolving the [InetErr] Missing Resource Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/selecting-holy-songs-for-ringtone-amplification-for-2024/"><u>Selecting Holy Songs for Ringtone Amplification for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-dealing-with-a-computer-that-cant-shut-down-windows-10/"><u>Solved! Dealing with a Computer That Can't Shut Down Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-windows-cant-find-appropriate-printer-drivers/"><u>Solving the Issue: Windows Can't Find Appropriate Printer Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-of-a-disconnected-bluetooth-keypad-on-laptopdesktop/"><u>Solving the Problem of a Disconnected Bluetooth Keypad on Laptop/Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-troubleshooting-ethernet-in-windows-operating-systems/"><u>Step-by-Step Solutions for Troubleshooting Ethernet in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-unreachable-steam-content-services/"><u>Step-by-Step Solutions for Unreachable Steam Content Services</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-vivo-y200-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Vivo Y200 Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fix-for-repeatedly-encountered-usb-device-not-recognized-tips-and-techniques-that-work/"><u>The Ultimate Fix for Repeatedly Encountered 'USB Device Not Recognized': Tips & Techniques That Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-corrupt-or-unsupported-images-in-windows-11-and-windows-10/"><u>Troubleshooting Corrupt or Unsupported Images in Windows 11 & Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-high-wudfhostexe-cpu-load-in-windows-10-systems/"><u>Troubleshooting High wudfhost.exe CPU Load in Windows 10 Systems</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-unexpected-website-appearances-in-iphone-screen-time/"><u>Troubleshooting Unexpected Website Appearances in iPhone Screen Time</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-causes-the-parameter-is-incorrect-solve-your-loadlibrary-error-87-now/"><u>What Causes 'The Parameter Is Incorrect?' Solve Your LoadLibrary Error 87 Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-to-do-when-left-and-right-arrow-keys-stop-responding-quick-remedies/"><u>What to Do When Left and Right Arrow Keys Stop Responding: Quick Remedies!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-update-brings-new-cast-features-solve-common-casting-errors-here/"><u>Windows 11 Update Brings New Cast Features - Solve Common Casting Errors Here!</u></a></li>
</ul></div>
