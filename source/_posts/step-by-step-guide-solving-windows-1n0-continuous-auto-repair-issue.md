---
title: "Step-by-Step Guide: Solving Windows 1N0 Continuous Auto Repair Issue"
date: 2024-08-19T07:06:45.280Z
updated: 2024-08-20T07:06:45.280Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Guide: Solving Windows 1N0 Continuous Auto Repair Issue"
excerpt: "This Article Describes Step-by-Step Guide: Solving Windows 1N0 Continuous Auto Repair Issue"
thumbnail: https://thmb.techidaily.com/85034a62a15df819e619fec4e6d0909e5ab4845fbca98b126bdfe343d56fc596.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
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
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affd826668f.png)
  
**Run a system file check**
  
 Follow steps below:  
  
 1\. Open**Command Prompt** as an administrator.  
  
 2\. Type or paste**sfc /scannow** and hit**Enter** . The process will also take some time to complete.  
  
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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-which-ios-app-crushes-in-video-editing-cameo-or-filmorago/"><u>[New] 2024 Approved  Which iOS App Crushes in Video Editing? Cameo or FilmoraGo?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-impact-of-authenticity-in-insta-self-portraits/"><u>[New] The Impact of Authenticity in Insta Self-Portraits</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-ensuring-visual-presentation-youtube-shorts-thumbnails-fix/"><u>[Updated] 2024 Approved  Ensuring Visual Presentation  YouTube Shorts Thumbnails Fix</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-innovative-chroma-techniques-for-stunning-visual-storytelling/"><u>[Updated] In 2024, Innovative Chroma Techniques for Stunning Visual Storytelling</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-stepping-up-your-game-understanding-mcns-and-their-impact-on-creators-for-2024/"><u>[Updated] Stepping Up Your Game  Understanding MCNs and Their Impact on Creators for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Xiaomi 13T | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-crafting-the-auditory-journey-in-a-film-teaser/"><u>2024 Approved  Crafting the Auditory Journey in a Film Teaser</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-steps-to-ensure-quality-film-with-your-iphone/"><u>2024 Approved  Steps to Ensure Quality Film with Your iPhone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamline-your-images-in-canva-without-clutter/"><u>2024 Approved  Streamline Your Images in Canva Without Clutter</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-streamlining-video-content-with-effective-xml-ttml-and-srt-solutions/"><u>2024 Approved  Streamlining Video Content with Effective XML, TTML & SRT Solutions</u></a></li>
<li><a href="https://video-capture.techidaily.com/capturing-victories-effective-strategies-with-w11-for-2024/"><u>Capturing Victories  Effective Strategies with W11 for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/chrome-troubles-eradicate-errnamenotresolved-with-this-easy-method/"><u>Chrome Troubles? Eradicate 'ERR_NAME_NOT_RESOLVED' With This Easy Method!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/definitive-solutions-to-windows-10-setup-error-code-80240020-get-your-system-running-now/"><u>Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-sporadic-wi-fi-mouse-failures-in-modern-operating-systems-windows-1110/"><u>Diagnosing and Repairing Sporadic Wi-Fi Mouse Failures in Modern Operating Systems (Windows 11/10)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-and-tricks-for-resolving-windows-10-taskbar-freeze-issues/"><u>Expert Tips and Tricks for Resolving Windows 10 Taskbar Freeze Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-effortless-csgo-stability-and-no-more-unexpected-shutdowns/"><u>Expert Tips for Effortless CS:GO Stability and No More Unexpected Shutdowns</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-desktop-not-available-issue-on-system-profile-windows/"><u>Fixing the 'Desktop Not Available' Issue on System Profile - Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-update-error-code-0x80070490-a-comprehensive-guide/"><u>Fixing Windows Update Error Code 0X80070490 - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-circumventing-the-persistent-windows-10-0x800f0922-update-hurdle/"><u>Guide To Circumventing The Persistent Windows 10 0X800f0922 Update Hurdle</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hearthstone-performance-boost-effortless-lag-fixes/"><u>Hearthstone Performance Boost: Effortless Lag Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-bluetooth-disabled-issue/"><u>How To Fix Bluetooth Disabled Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-d3dx942dll-missing-or-not-found-errors/"><u>How to Fix d3dx9_42.dll Missing or Not Found Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-user-profile-service-service-failed-the-sign-in-error-windows-1111/"><u>How to Fix The User Profile Service Service Failed the Sign-In Error Windows 11/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-total-war-rome-remastered-game-crashing-issues-easily/"><u>How to Fix Total War: Rome Remastered Game Crashing Issues Easily</u></a></li>
<li><a href="https://win-answers.techidaily.com/improving-pc-game-performance-solutions-for-reducing-fps-drops/"><u>Improving PC Game Performance: Solutions for Reducing FPS Drops</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-nokia-c22-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Nokia C22?</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-media-streaming-overcoming-windows-10-cast-failures-detailed-steps/"><u>Mastering Media Streaming: Overcoming Windows 10 Cast Failures [Detailed Steps]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-oculus-repair-strategies-to-tackle-errors-and-enhance-your-vr-experience/"><u>Mastering Oculus Repair Strategies to Tackle Errors and Enhance Your VR Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-pc-restoration-in-windows-11-overcoming-common-problem-resetting-errors/"><u>Mastering PC Restoration in Windows 11: Overcoming Common Problem Resetting Errors</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-the-art-of-buying-cutting-edge-360cams-for-2024/"><u>Mastering the Art of Buying Cutting-Edge 360Cams for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-technique-repair-methods-for-windows-startup-issues/"><u>Mastering the Technique: Repair Methods for Windows Startup Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nircmd-guide-for-power-users-optimize-win-commands/"><u>NirCmd Guide for Power Users: Optimize Win Commands</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimize-and-accelerate-your-windows-7-systems-boot-speed/"><u>Optimize and Accelerate Your Windows 7 System's Boot Speed</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/origami-like-folded-havens-in-mc-for-2024/"><u>Origami-Like Folded Havens in MC for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-computers-stuck-at-windows-setup-a-step-by-step-guide/"><u>Resolve Your Computer's 'Stuck at Windows Setup': A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-insufficient-system-resources-errors-in-your-application/"><u>Resolved: Fixing 'Insufficient System Resources' Errors in Your Application</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-prompt-fixes-for-error-1053-non-responsive-services/"><u>Resolved: Prompt Fixes for 'Error 1053' - Non-Responsive Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-how-to-enable-your-devices-wireless-functionality/"><u>Resolving Issues: How to Enable Your Device's Wireless Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-minecraft-performance-issues-ultimate-guide/"><u>Resolving Minecraft Performance Issues: Ultimate Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-shift-key-failure-expert-troubleshooting-tips/"><u>Solving 'Shift Key Failure': Expert Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-plugged-in-but-not-charging-problems-on-your-microsoft-surface/"><u>Solving Plugged In But Not Charging Problems on Your Microsoft Surface</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-csgo-crashes-in-their-tracks-simple-tips-for-stability/"><u>Stop CSGO Crashes in Their Tracks - Simple Tips for Stability</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/top-best-5-free-mpeg-video-joiners-for-2024/"><u>Top Best 5 Free MPEG Video Joiners for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-installing-the-latest-feature-update-on-windows-10-build-1607/"><u>Trouble Installing the Latest Feature Update on Windows 10 Build 1607</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-aoc-monitor-steps-to-restore-functionality-on-windows-10-devices/"><u>Troubleshoot Your AOC Monitor: Steps to Restore Functionality on Windows 10 Devices</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-and-fixing-idt-hd-audio-codec-issues-for-windows-11-users/"><u>Troubleshooting and Fixing IDT HD Audio Codec Issues for Windows 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-connection-issues-with-microsoft-wi-fi-display-adapter-on-windows-11/"><u>Troubleshooting Guide: Fixing Connection Issues with Microsoft Wi-Fi Display Adapter on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-microsoft-print-to-pdf-issues-on-windows-10-and-11/"><u>Troubleshooting Microsoft Print to PDF Issues on Windows 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-correcting-the-monitor-has-no-video-output-error/"><u>Troubleshooting Tips: Correcting the 'Monitor Has No Video Output' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-update-service-failures-quick-and-effective-fixes/"><u>Troubleshooting Windows Update Service Failures - Quick and Effective Fixes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-the-importance-of-system-speed-how-quick-does-your-pc-really-need-to-be/"><u>Understanding the Importance of System Speed: How Quick Does Your PC Really Need To Be?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unleashing-visual-potential-incorporating-new-fonts-in-ae/"><u>Unleashing Visual Potential  Incorporating New Fonts in AE</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-wireless-potential-easy-bluetooth-setup-instructions-for-win11-and-win10-users/"><u>Unlocking Wireless Potential: Easy Bluetooth Setup Instructions for Win11 & Win10 Users</u></a></li>
</ul></div>
