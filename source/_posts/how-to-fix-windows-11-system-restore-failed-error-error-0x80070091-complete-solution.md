---
title: How to Fix Windows 11 'System Restore Failed' Error (Error 0X80070091) - Complete Solution
date: 2024-08-28T00:31:22.621Z
updated: 2024-08-29T00:31:22.621Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Windows 11 'System Restore Failed' Error (Error 0X80070091) - Complete Solution
excerpt: This Article Describes How to Fix Windows 11 'System Restore Failed' Error (Error 0X80070091) - Complete Solution
thumbnail: https://thmb.techidaily.com/6f8c62fe2349a0f207bb9e67da92ccbc024b72458dedec8efed25d3d7ef6c0d1.png
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-tips.techidaily.com/024-approved-how-to-pick-a-unique-name-for-youtube-channel-filmora/"><u>[New] 2024 Approved  How To Pick a Unique Name for YouTube Channel - Filmora</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-mastering-the-art-of-sound-in-tiktok-videos/"><u>[Updated] 2024 Approved  Mastering the Art of Sound in TikTok Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-budget-pc-screen-capture-apps/"><u>[Updated] In 2024, Budget PC Screen Capture Apps</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-unmatched-5-ios-backdrop-change-solutions-iphone-x87/"><u>[Updated] In 2024, Unmatched 5 iOS Backdrop Change Solutions (iPhone X/8/7)</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024s-ultimate-fixes-for-when-voicemod-wont-launch-or-work-properly/"><u>2024'S Ultimate Fixes for When Voicemod Won't Launch or Work Properly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-step-by-step-tutorial-for-fixing-the-red-screen-anomaly-on-windows-10-computers/"><u>A Step-by-Step Tutorial for Fixing the Red Screen Anomaly on Windows 10 Computers</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ace-your-signature-rapid-background-cleansing-guide-for-2024/"><u>Ace Your Signature  Rapid Background Cleansing Guide for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-your-iphone-14-plus-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From your iPhone 14 Plus</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-port-reset-failed-warnings-with-easy-fixes-for-your-windows-11-computer/"><u>Bypassing 'Port Reset Failed' Warnings with Easy Fixes for Your Windows 11 Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-guide-to-overcome-initializing-issues-in-destiny-2/"><u>Complete Guide to Overcome Initializing Issues in Destiny 2</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-svchostexe-netsvcs-how-to-fix-excessive-bandwidth-usage-and-improve-your-pcs-efficiency/"><u>Decoding svchost.exe (NETsvcs) - How to Fix Excessive Bandwidth Usage & Improve Your PC's Efficiency</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-mending-broken-operating-system-files-in-windows-10-and-11/"><u>Diagnosing and Mending Broken Operating System Files in Windows 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-troubleshooting-guide-resolving-minecraft-performance-problems/"><u>Easy Troubleshooting Guide: Resolving Minecraft Performance Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/end-crackling-audio-from-computer-speakers-effective-techniques-for-windows-users/"><u>End Crackling Audio From Computer Speakers: Effective Techniques for Windows Users</u></a></li>
<li><a href="https://win-solutions.techidaily.com/end-the-frustration-step-by-step-guide-to-eliminate-deathloop-crashes-on-computer/"><u>End the Frustration: Step-by-Step Guide to Eliminate Deathloop Crashes on Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-resolving-usb-mouse-connectivity-issues-on-your-personal-computer/"><u>Expert Tips for Resolving USB Mouse Connectivity Issues on Your Personal Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-track-guide-to-fixing-errors-in-directx-setup-processes-effortlessly/"><u>Fast Track Guide to Fixing Errors in DirectX Setup Processes Effortlessly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/file-explorer-tricks-for-windows-11-users-quick-help-and-easy-fixes/"><u>File Explorer Tricks for Windows 11 Users - Quick Help & Easy Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-applicationexe-has-stopped-error-a-complete-guide/"><u>Fixing 'Application.exe Has Stopped' Error – A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-your-connection-a-step-by-step-guide-to-when-steam-is-offline/"><u>Fixing Your Connection: A Step-by-Step Guide to When Steam Is Offline</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-when-your-hp-laptops-mouse-pad-wont-work/"><u>How to Fix When Your HP Laptop's Mouse Pad Won't Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-werfaultexe-malfunction-a-step-by-step-guide/"><u>How to Fix Windows werFault.exe Malfunction: A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-install-the-latest-iosipados-beta-version-on-apple-iphone-6-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS/iPadOS Beta Version on Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-visibility-of-your-touchpad-cursor-on-windows-11-systems/"><u>How to Restore Visibility of Your Touchpad Cursor on Windows 11 Systems</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-nubia-z50-ultra-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Nubia Z50 Ultra?</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-streamlined-video-submission-mmc-to-vimeo-journey-explained/"><u>In 2024, Streamlined Video Submission  MMC to Vimeo Journey Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/microsoft-wireless-screen-projector-connectivity-woes-on-windows-10-heres-the-solution/"><u>Microsoft Wireless Screen Projector Connectivity Woes on Windows 10? Here's the Solution!</u></a></li>
<li><a href="https://article-files.techidaily.com/navigating-video-data-in-high-capacity-drives-64128gb/"><u>Navigating Video Data in High-Capacity Drives (64/128GB)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-system-resources-managing-msmpengineexe-high-cpu-drain-on-windows-11-machines/"><u>Optimizing System Resources: Managing MsMpEngine.exe High CPU Drain on Windows 11 Machines</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-cannot-start-hardware-device-error-due-to-damaged-registry-configuration-code-19/"><u>Resolving 'Windows 11 Cannot Start Hardware Device' Error Due to Damaged Registry Configuration - Code 19</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-trackpad-effective-fixes-for-windows-11-8-and-7-not-working-scenarios/"><u>Revive Your Trackpad: Effective Fixes for Windows 11, 8 & 7 Not Working Scenarios</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-for-microsoft-store-failure-to-open-issue/"><u>Solution Guide for Microsoft Store Failure to Open Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-microsoft-wireless-adapter-connectivity-error-in-windows-10-environments/"><u>Step-by-Step Solutions for Microsoft Wireless Adapter Connectivity Error in Windows 10 Environments</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tailoring-your-iphone-photographs-size-alteration-for-2024/"><u>Tailoring Your iPhone Photographs  Size Alteration for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshoot-and-restore-your-discord-overlay-in-minutes-learn-how-today/"><u>Troubleshoot and Restore Your Discord Overlay in Minutes - Learn How Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-computer-during-windows-installation-professional-fixes-and-tips/"><u>Unstick Your Computer During Windows Installation: Professional Fixes and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209086261-winning-the-battle-against-failing-windows-updates-now-fixed/"><u>Winning the Battle Against Failing Windows Updates - Now Fixed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-svchostexes-heavy-load-on-windows-11-solution/"><u>Winning the Battle Against Svchost.exe's Heavy Load on Windows 11 [Solution]</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->