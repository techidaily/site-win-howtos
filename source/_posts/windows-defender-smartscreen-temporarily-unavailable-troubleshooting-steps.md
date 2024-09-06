---
title: Windows Defender SmartScreen Temporarily Unavailable - Troubleshooting Steps
date: 2024-09-05T10:07:58.754Z
updated: 2024-09-06T10:07:58.754Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows Defender SmartScreen Temporarily Unavailable - Troubleshooting Steps
excerpt: This Article Describes Windows Defender SmartScreen Temporarily Unavailable - Troubleshooting Steps
thumbnail: https://thmb.techidaily.com/e66e28dff9a78d29ac6c41d0e2dd487a7c339d734ca57b3143f21e9c629c5f8e.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115949/19272" target="_top" id="2115949">
  <img src="//a.impactradius-go.com/display-ad/19272-2115949" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115949/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afe2f523108.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff3f6500f3.jpg)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-advanced-steps-a-compre-point-of-view-on-screen-record-with-adobe-captivate-for-2024/"><u>[New] Advanced Steps  A Compre Point of View on Screen Record with Adobe Captivate for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-audiophiles-guide-to-the-finest-window-based-podcast-tools-8/"><u>[New] Audiophile's Guide to the Finest Window-Based Podcast Tools (#8)</u></a></li>
<li><a href="https://youtube-data.techidaily.com/udiovisual-harmony-merging-audio-and-visual-elements-on-youtube-for-2024/"><u>[New] Audiovisual Harmony  Merging Audio and Visual Elements on YouTube for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-rdr2-out-of-memory-please-increase-the-page-file-size-error/"><u>[Quick Fix] RDR2 Out of Memory Please Increase the Page File Size Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-your-connection-is-not-secured-firefox-error/"><u>[Solved] Your Connection Is Not Secured Firefox Error</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-unveiling-ig-reels-vs-ig-stories-essential-insights/"><u>[Updated] Unveiling IG Reels vs IG Stories  Essential Insights</u></a></li>
<li><a href="https://some-approaches.techidaily.com/macm2ts-to-avimov-mpeg-2/"><u>無料Mac向けM2TS to AVI/MOVコンバータ: MPEG-2テープ動画をスムーズ変換！</u></a></li>
<li><a href="https://fox-helps.techidaily.com/audiovisual-harmony-perfecting-voiceover-in-videos/"><u>Audiovisual Harmony  Perfecting Voiceover in Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-the-battery-not-found-error-with-simple-fast-remedies/"><u>Bypass the 'Battery Not Found' Error with Simple, Fast Remedies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/device-managers-await-your-touchpad-returns/"><u>Device Managers Await - Your Touchpad Returns!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-to-fix-d3dx943dll-missing-on-windows/"><u>Easy to Fix d3dx9_43.dll Missing on Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722963767993-effortlessly-upgrade-your-connection-secure-the-latest-wireless-adapter-drivers-here/"><u>Effortlessly Upgrade Your Connection: Secure the Latest Wireless Adapter Drivers Here!</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-infinix-hot-30-5g-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-directx-component-creation-obstacles-successfully/"><u>How to Overcome DirectX Component Creation Obstacles Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-a-non-functional-backspace-key-on-your-device/"><u>How to Resolve a Non-Functional Backspace Key on Your Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212238529-how-to-speed-up-your-league-of-legends-game-files-fixed-download-issues-revealed/"><u>How to Speed Up Your League of Legends Game Files: Fixed Download Issues Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-overcome-a-failed-group-policy-client-authentication-process/"><u>How to Successfully Overcome a Failed Group Policy Client Authentication Process</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-oppo-reno-11f-5g-phone-without-google-account-by-drfone-android/"><u>How to Unlock Oppo Reno 11F 5G Phone without Google Account?</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-6s-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-poco-c65-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Poco C65 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovate-your-iphones-selfie-quality-the-10-best-free-apps/"><u>In 2024, Innovate Your iPhone's Selfie Quality  The 10 Best Free Apps</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-the-ultimate-ranking-8-best-ios-compatible-daws-for-ipad-and-iphone-enthusiasts/"><u>In 2024, The Ultimate Ranking 8 Best iOS-Compatible DAWs for iPad and iPhone Enthusiasts</u></a></li>
<li><a href="https://extra-tips.techidaily.com/polarrs-complete-guide-mastering-image-editing/"><u>Polarr's Complete Guide  Mastering Image Editing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-when-windows-cant-finish-installing-software/"><u>Quick Solutions for When Windows Can't Finish Installing Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-windows-error-unable-to-link-with-system-event-notification-service/"><u>Resolved: Windows Error - Unable To Link With System Event Notification Service</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-device-not-found-errors-fix-code-2ergy-on-windows-11-8-and-7/"><u>Resolving 'Device Not Found' Errors: Fix Code 2Ergy on Windows 11, 8 & 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-with-unresponsive-usb-ports-in-windows-11-systems/"><u>Resolving Issues with Unresponsive USB Ports in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-fixing-a-non-functional-microphone-on-your-computer/"><u>Solved: Fixing a Non-Functional Microphone on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-why-your-airpods-wont-pair-with-windows-11-step-by-step-guide/"><u>Solving the Issue: Why Your AirPods Won't Pair with Windows 11 – Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-malfunctioning-keyboard-during-user-authentication-phase/"><u>Step-by-Step Fix for Malfunctioning Keyboard During User Authentication Phase</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208212180-stuck-on-a-pdf-that-wont-print-discover-swift-solutions-now/"><u>Stuck on a PDF That Won't Print? Discover Swift Solutions Now!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-comparison-guide-to-public-private-and-individual-use-ai-technologies/"><u>The Comparison Guide to Public, Private, and Individual Use AI Technologies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/touchpad-problems-heres-how-you-can-restore-functionality/"><u>Touchpad Problems? Here's How You Can Restore Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-how-to-fix-the-non-functioning-aoc-monitor-issue-on-windows-11/"><u>Troubleshooting Steps: How to Fix the Non-Functioning AOC Monitor Issue on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-audio-enhancer-features-for-improved-performance/"><u>Troubleshooting Windows' Audio Enhancer Features for Improved Performance</u></a></li>
</ul></div>
