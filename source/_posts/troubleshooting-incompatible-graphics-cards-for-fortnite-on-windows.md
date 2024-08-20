---
title: Troubleshooting Incompatible Graphics Cards for Fortnite on Windows
date: 2024-08-19T06:57:06.470Z
updated: 2024-08-20T06:57:06.470Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Incompatible Graphics Cards for Fortnite on Windows
excerpt: This Article Describes Troubleshooting Incompatible Graphics Cards for Fortnite on Windows
thumbnail: https://thmb.techidaily.com/faf305db1bff9ec7cfb8fafeb68d0a5e6478101d40a48c00d6fe1d681c9c048c.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
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
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
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
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-seamless-access-watching-fb-videos-on-apple-tv-explained/"><u>[New] 2024 Approved  Seamless Access  Watching FB Videos on Apple TV Explained</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-converting-youtube-to-gif-a-comprehensive-online-process-for-2024/"><u>[New] Converting YouTube to GIF  A Comprehensive Online Process for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-expert-fb-video-sharing-tactics-for-desktop-and-handheld-devices/"><u>[New] Expert FB Video Sharing Tactics for Desktop and Handheld Devices</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-maximizing-video-reach-sharing-youtube-content-via-facebook-network/"><u>[New] In 2024, Maximizing Video Reach  Sharing YouTube Content via Facebook Network</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-the-monetization-blueprint-for-your-youtube-ventures-on-fb/"><u>[New] The Monetization Blueprint for Your YouTube Ventures on FB</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-prime-choices-for-cost-effective-sharp-4k-projection/"><u>[Updated] 2024 Approved  Prime Choices for Cost-Effective, Sharp 4K Projection</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-master-the-dark-and-light-iphone-silhouette-tips/"><u>[Updated] Master the Dark & Light  IPhone Silhouette Tips</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-professional-tricks-for-youtube-audio-amplification/"><u>[Updated] Professional Tricks for YouTube Audio Amplification</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-turn-your-iphone-images-upside-down-with-precision/"><u>2024 Approved  Turn Your iPhone Images Upside Down with Precision</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-samsung-galaxy-a14-4g-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-guide-to-addressing-windows-10s-red-screen-malfunction-successfully/"><u>Complete Guide to Addressing Windows 10'S Red Screen Malfunction Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-to-fixing-hps-built-in-camera-issues-when-running-on-windows-11/"><u>Comprehensive Guide to Fixing HP's Built-In Camera Issues When Running on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-tutorial-on-solving-xbox-wireless-pen-problems-for-optimal-gaming-performance/"><u>Comprehensive Tutorial on Solving Xbox Wireless Pen Problems for Optimal Gaming Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/correct-display-2-issue-on-modern-pcs-solved/"><u>Correct Display #2 Issue on Modern PCs (Solved)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-solutions-for-audio-output-device-not-found-error-on-your-windows-11-computer/"><u>Easy Solutions for 'Audio Output Device Not Found' Error on Your Windows 11 Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208622216-effortlessly-fix-keyboard-issues-on-your-hp-laptop-troubleshooting-steps-inside/"><u>Effortlessly Fix Keyboard Issues on Your HP Laptop – Troubleshooting Steps Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/escaping-the-startup-spiral-expert-fixes-for-computers-frozen-at-boot-screen/"><u>Escaping the Startup Spiral: Expert Fixes for Computers Frozen at Boot Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-repairing-and-optimizing-io-device-performance/"><u>Expert Advice on Repairing and Optimizing I/O Device Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-how-to-stop-screens-from-tearing-during-valorant-matches/"><u>Expert Tips on How to Stop Screens From Tearing During Valorant Matches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-correct-the-error-when-rpc-service-fails-in-windows-environments/"><u>Expert Tips to Correct the Error When RPC Service Fails in Windows Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-sticky-or-unresponsive-backspace-button-now-a-step-by-step-guide/"><u>Fix Your Sticky or Unresponsive Backspace Button Now - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-mysterious-black-screen-expert-advice-for-dell-laptop-users/"><u>Fixing the Mysterious Black Screen: Expert Advice for Dell Laptop Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-svchostexe-causing-high-system-load-on-windows-10-effective-solutions/"><u>How to Fix svchost.exe Causing High System Load on Windows 10: Effective Solutions</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-honor-x9b-to-mac-drfone-by-drfone-android/"><u>How to Mirror Honor X9b to Mac? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-correct-directx-not-starting-up-issues-instantly/"><u>How to Troubleshoot and Correct 'DirectX Not Starting Up' Issues Instantly</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-samsung-galaxy-s23-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Samsung Galaxy S23</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-streamline-music-craft-with-our-high-quality-beat-detection-software/"><u>In 2024, Streamline Music Craft with Our High-Quality Beat Detection Software</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-supreme-boundless-data-depot/"><u>In 2024, Supreme Boundless Data Depot</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/iphone-12-pro-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>iPhone 12 Pro Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/locating-the-start-menu-in-windows-11-a-comprehensive-guide/"><u>Locating the Start Menu in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-successful-deployment-fixes-for-windows-version-1903-updates/"><u>Mastering Successful Deployment: Fixes for Windows Version 1903 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208523630-minecraft-stability-restored-correcting-video-card-driver-errors-on-your-windows-pc/"><u>Minecraft Stability Restored: Correcting Video Card Driver Errors On Your Windows PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/nba-2k21-explains-unveiling-the-mystery-behind-the-green-glitch-fix/"><u>NBA 2K21 Explains: Unveiling the Mystery Behind the 'Green Glitch' Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-logildadll-missing-alert/"><u>Quick-Fix: LogiLDA.dll Missing Alert</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-d3derrnotavailable-a-step-by-step-guide/"><u>Resolving 'D3DERR_NOTAVAILABLE': A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-undetected-storage-device-problem-making-wd-my-passport-work-with-windows/"><u>Resolving Undetected Storage Device Problem: Making WD My Passport Work with Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-samsung-galaxy-a14-5g-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Samsung Galaxy A14 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-repairing-compromised-windows-store-caches/"><u>Solution Guide: Repairing Compromised Windows Store Caches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-how-to-fix-microsoft-store-not-launching-issues/"><u>Solved: How to Fix Microsoft Store Not Launching Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-puzzle-fix-xerox-update-error-0x800f020b-on-your-pc-a-step-by-step-guide/"><u>Solving the Puzzle: Fix Xerox Update Error 0X800F020B on Your PC - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speedy-marvel-how-this-gadget-triumphs-with-incredible-velocity/"><u>Speedy Marvel: How This Gadget Triumphs with Incredible Velocity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-damaged-or-broken-usb-connections-in-windows-1011/"><u>Step-by-Step Fixes for Damaged or Broken USB Connections in Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-when-your-dell-wireless-keyboard-fails-to-function/"><u>Step-by-Step Solution: When Your Dell Wireless Keyboard Fails to Function</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-making-your-wd-my-passport-ultra-drive-detectable-by-windows/"><u>Step-by-Step Tutorial: Making Your WD My Passport Ultra Drive Detectable by Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-addressed-troubleshooting-directx-hardware-setup-problems/"><u>Successfully Addressed: Troubleshooting DirectX Hardware Setup Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-errorcachemiss-on-google-chrome-tips-and-solutions/"><u>Troubleshooting ERROR_CACHE_MISS on Google Chrome: Tips and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-sims-4-failure-to-launch-problem/"><u>Ultimate Guide: Resolving the Sims 4 Failure to Launch Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-fortnites-start-up-success/"><u>Unlocking Fortnite's Start-Up Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-class-registration-issue-easy-fixes-and-solutions/"><u>Windows 10 Class Registration Issue: Easy Fixes and Solutions</u></a></li>
</ul></div>
