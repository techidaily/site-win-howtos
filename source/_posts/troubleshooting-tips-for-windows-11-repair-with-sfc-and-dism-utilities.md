---
title: Troubleshooting Tips for Windows 11 Repair with SFC & DISM Utilities
date: 2024-08-19T06:46:58.107Z
updated: 2024-08-20T06:46:58.107Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Tips for Windows 11 Repair with SFC & DISM Utilities
excerpt: This Article Describes Troubleshooting Tips for Windows 11 Repair with SFC & DISM Utilities
thumbnail: https://thmb.techidaily.com/a3895cce3360de5913e31306b1dac3362ecfc87f8052e7d36fccdff1f24bd61a.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afe2f523108.jpg)

When you met boot error with Windows 10, you hoped that automatic repair will help fix the problem. But it got you more troubles. The worse thing is that repair process seems never end. Then what to do to end the loop? Read on to find the solutions.  

 Since the Windows keeps restarting, it is impossible for you access Advanced Options, that you can fix the problem there. In this case, you can boot from a USB or DVD.
  
 To use the solutions below, you’ll need to prepare a bootable USB or a DVD with an installation file on it. If you are not sure how to create a bootable USB, refer [How to Burn Windows 10 ISO to USB](https://tools.techidaily.com/drivereasy/download/) . Note you need to do this on another computer.
  
 **First start your PC from the USB or DVD and open Command Prompt**
  
 1.  
  
 For USB bootable way:  
  
 Plug the USB the computer that has the problem.After you power on the computer, press function key, usually F2 or F12, to enter boot menu. The key to enter boot menu depends on the computers that you are using. You can go to the PC manufacturer’s website to check for it.
  
 For DVD bootable way:  
  
 Insert the DVD to the computer that has the problem. Wait until you see the message “Press any key to boot from CD or DVD”. Press any key to continue. If you don’t see this message, you probably have to change the boot order in the BIOS (Basic Input/Output System) .  
  
 Learn[How to Boot from a USB Drive, DVD or CD](https://tools.techidaily.com/drivereasy/download/) .  
  
 2\. When you go to the setup screen, select the Language that you wish to use.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff3f6500f3.jpg)
  
 2\. Type **bcdedit /set GUID recoveryenabled No** and hit**Enter** . Replace GUID with the number that you noted in last step. (For example, if the number is 7ce0dd34-d277-11e4-8263-68f7286346fb, the full command will be “bcdedit /set 7ce0dd34-d277-11e4-8263-68f7286346fb recoveryenabled No”)  
  
 3\. Reboot your PC and Windows should start without no problem.

 **Solution 3: Remove Your RAM**
  
 The loop error can be fixed by simply removing the RAM. You can try this solution. Before removing, remember to turn off the PC.If you have more than one RAM, remove one at a time then start your PC without it. You might need to do this a few times until you test every RAM module.

 After entering Windows, run a disk check to check if there is any problem with the disk, and run a system file check to check if some system files are corrupted. If neither of them work, try to restore Windows registry.  
  
**Run a disk check**
  
 Follow steps below:  
  
 1\. Open[**Command Prompt**](https://tools.techidaily.com/drivereasy/download/) as an administrator.
  
 2\. Type**chkdsk /f /r** and hit**Enter** . You need to wait a while until the process completes.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affd826668f.png)
  
**Run a system file check**
  
 Follow steps below:  
  
 1\. Open**Command Prompt** as an administrator.  
  
 2\. Type or paste**sfc /scannow** and hit**Enter** . The process will also take some time to complete.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affee4bc504.png)
  
 Hope the solutions here will help you fix the Windows 10 Automatic Repair loop error.

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
<li><a href="https://win-howtos.techidaily.com/fixed-copypaste-on-win-11-os/"><u>[FIXED]: Copy/Paste on Win 11 OS</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-unleashing-the-power-of-whiteboards-on-zoom-platforms-across-multiple-devices/"><u>[New] 2024 Approved  Unleashing the Power of Whiteboards on Zoom Platforms Across Multiple Devices</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-capture-and-share-immedienas-unprecedented-journey-with-dslr-and-facebook-live/"><u>[New] In 2024, Capture and Share Immedienas Unprecedented Journey with DSLR & Facebook LIVE</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-from-footage-to-narrative-the-essential-guide-to-instagram-descriptive-texts/"><u>[New] In 2024, From Footage to Narrative  The Essential Guide to Instagram Descriptive Texts</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/nderstanding-recent-youtube-financial-policies-for-2024/"><u>[New] Understanding Recent YouTube Financial Policies for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/nlocking-the-money-machine-of-youtube-videos-for-creators-for-2024/"><u>[New] Unlocking the Money Machine of YouTube Videos for Creators for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-pixelpilot-expert-tips-for-screen-snagging/"><u>[Updated] 2024 Approved  PixelPilot  Expert Tips for Screen Snagging</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-expert-tips-for-avoiding-instagram-video-troubles-for-2024/"><u>[Updated] Expert Tips for Avoiding Instagram Video Troubles for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-premier-portals-to-retro-playstation-gaming-on-your-desktop/"><u>[Updated] In 2024, Premier Portals to Retro PlayStation Gaming on Your Desktop</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-ultimate-guide-to-top-hd-video-recorders-for-2024/"><u>[Updated] Ultimate Guide to Top HD Video Recorders for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-advanced-5-cloud-view-recorder/"><u>2024 Approved  Advanced 5 Cloud View Recorder</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-top-5-online-film-editors/"><u>2024 Approved  Top 5 Online Film Editors</u></a></li>
<li><a href="https://android-unlock.techidaily.com/7-ways-to-unlock-a-locked-asus-rog-phone-8-pro-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Asus ROG Phone 8 Pro Phone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209292613-app-cant-open-using-built-in-administrator-account-solved/"><u>App Can't Open Using Built-In Administrator Account [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/common-causes-and-fixes-for-a-non-working-laptop-touchpad-a-comprehensive-guide/"><u>Common Causes and Fixes for a Non-Working Laptop Touchpad – A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-fixes-to-tackle-the-blue-screen-of-death-code-0x0000007e-in-windows-7/"><u>Comprehensive Fixes to Tackle the Blue Screen of Death (Code: 0X0000007E) in Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-for-excessive-network-traffic-caused-by-svchostexe-netsvcs/"><u>Comprehensive Solutions for Excessive Network Traffic Caused by svchost.exe (Netsvcs)</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/disabling-iphone-14-parental-restrictions-withwithout-password-by-drfone-ios/"><u>Disabling iPhone 14 Parental Restrictions With/Without Password</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-steps-for-restoring-functionality-to-a-broken-shift-key/"><u>Essential Steps for Restoring Functionality to a Broken Shift Key</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-for-monitors-now-displays-fullscreen-on-win11/"><u>Fix for Monitors: Now Displays Fullscreen on Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-failed-feature-enhancements-on-windows-11-insights-for-build-1803/"><u>Fixing Failed Feature Enhancements on Windows 11 - Insights for Build 1803</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-microsoft-wi-fi-display-connection-issues-on-windows-11-a-step-by-step-guide/"><u>Fixing Microsoft Wi-Fi Display Connection Issues on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/full-rotational-rigging-solutions-for-2024/"><u>Full-Rotational Rigging Solutions for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-common-errors-in-windows-installation-packages/"><u>How to Fix Common Errors in Windows Installation Packages</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-distorted-audio-output-from-youtube-on-a-windows-10-machine/"><u>How to Fix Distorted Audio Output From YouTube on a Windows 10 Machine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-fortnites-graphics-card-compatibility-issues-on-windows/"><u>How to Fix Fortnite's Graphics Card Compatibility Issues on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-intel-rapid-storage-technology-rst-malfunction-in-windows-11-systems/"><u>How to Resolve Intel Rapid Storage Technology (RST) Malfunction in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-western-digital-ultra-portable-drive-detection-issues-on-windows-machines/"><u>How To Resolve Western Digital Ultra Portable Drive Detection Issues on Windows Machines</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-missing-desktop-icons-on-your-pc-running-windows/"><u>How to Restore Missing Desktop Icons on Your PC Running Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-your-windows-11-wallpaper-screensaver-functionality-comprehensive-fix/"><u>How to Restore Your Windows 11 Wallpaper Screensaver Functionality [Comprehensive Fix]</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instamosaic-syncing-videos-across-oses/"><u>InstaMosaic  Syncing Videos Across OSes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/managing-high-network-traffic-caused-by-svchostexe-unraveling-netsvcs-and-techniques-for-swift-resolution/"><u>Managing High Network Traffic Caused by svchost.exe: Unraveling NETsvcs and Techniques for Swift Resolution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/maximize-windows-11-tackle-wmi-provider-host-overheat/"><u>Maximize Windows 11: Tackle WMI Provider Host Overheat</u></a></li>
<li><a href="https://win-howtos.techidaily.com/nvidia-setup-success-overcoming-issues-solved/"><u>NVIDIA Setup Success - Overcoming Issues (Solved)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-display-issues-with-missing-touch-or-stylus-functionality/"><u>Overcoming Display Issues with Missing Touch or Stylus Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-challenge-fixing-audio-hardware-problems-for-windows-10-and-11-users/"><u>Overcoming the Challenge: Fixing Audio Hardware Problems for Windows 10 and 11 Users</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/proven-youtube-seo-tricks-boosting-video-reach-and-visibility/"><u>Proven YouTube SEO Tricks  Boosting Video Reach and Visibility</u></a></li>
<li><a href="https://win-blog.techidaily.com/repair-guide-what-to-do-when-your-internet-explorer-keeps-freezing/"><u>Repair Guide: What To Do When Your Internet Explorer Keeps Freezing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-10-audio-problems-getting-your-microphone-back-on-track/"><u>Resolving Windows 10 Audio Problems: Getting Your Microphone Back on Track</u></a></li>
<li><a href="https://fox-http.techidaily.com/snapshots-and-snickers-the-art-of-memery/"><u>Snapshots and Snickers  The Art of Memery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-for-non-responsive-windows-update-service-a-complete-fix-guide/"><u>Solution for Non-Responsive Windows Update Service - A Complete Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-reducing-high-cpu-usage-by-svchostexe-in-windows-10-systems/"><u>Step-by-Step Guide to Reducing High CPU Usage by svchost.exe in Windows 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-changing-proxies-on-windows-11/"><u>Step-by-Step: Changing Proxies on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-guide-to-repairing-your-windows-10-crimson-display-problem/"><u>The Ultimate Guide to Repairing Your Windows 10 Crimson Display Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-6-solutions-for-resolving-werfaultexe-malfunction-in-windows/"><u>Top 6 Solutions for Resolving werfault.exe Malfunction in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-stuck-keys-on-windows-desktops/"><u>Troubleshooting and Repairing Stuck Keys on Windows Desktops</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-audio-issues-resolving-windows-107-speaker-crackling-problems/"><u>Troubleshooting Audio Issues: Resolving Windows 10/7 Speaker Crackling Problems</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-oneplus-11-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive OnePlus 11 5G Screen | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-monster-hunter-worlds-startup-void-how-to-overcome-total-black-screen-problems/"><u>Troubleshooting Monster Hunter: World's Startup Void - How to Overcome Total Black Screen Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-how-to-tell-if-netflix-is-offline-or-malfunctioning/"><u>Troubleshooting Tips: How to Tell If Netflix Is Offline or Malfunctioning</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-resolving-the-crusader-kings-ii-unlaunched-problem/"><u>Troubleshooting Tips: Resolving the Crusader Kings II Unlaunched Problem</u></a></li>
</ul></div>
