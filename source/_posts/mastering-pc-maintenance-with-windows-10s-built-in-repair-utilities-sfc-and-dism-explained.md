---
title: "Mastering PC Maintenance with Windows 10'S Built-In Repair Utilities: SFC & DISM Explained"
date: 2024-08-19T06:11:32.799Z
updated: 2024-08-20T06:11:32.799Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Mastering PC Maintenance with Windows 10'S Built-In Repair Utilities: SFC & DISM Explained"
excerpt: "This Article Describes Mastering PC Maintenance with Windows 10'S Built-In Repair Utilities: SFC & DISM Explained"
thumbnail: https://thmb.techidaily.com/3bbe537e8e6d43ee38a009c5ba9253564dbe37ab479840f5e7760ebe6f9d088b.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
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
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
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
<li><a href="https://win-howtos.techidaily.com/1723206909000-solved-wmi-provider-host-high-cpu-usage-on-windows-1111-quickly-and-easily/"><u>[Solved] WMI Provider Host: High CPU Usage on Windows 11/11 | Quickly & Easily</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-tiktok-feasts-current-favorites-explored/"><u>[Updated] TikTok Feasts  Current Favorites Explored</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-spotifys-ad-landscape-a-beginners-guide/"><u>2024 Approved  Navigating Spotify's Ad Landscape  A Beginner's Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/advanced-transitions-techniques-for-audios/"><u>Advanced Transitions Techniques for Audios</u></a></li>
<li><a href="https://win-howtos.techidaily.com/audio-glitch-solutions-eliminating-crackling-sounds-from-computers-speakers-under-windows-os/"><u>Audio Glitch Solutions: Eliminating Crackling Sounds From Computers' Speakers Under Windows OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-the-irqlnotlessorequal-fault-error-code-0xc00000005-in-microsoft-operating-systems/"><u>Comprehensive Fixes for the 'IRQL_NOT_LESS_OR_EQUAL' Fault (Error Code 0XC0지0000005) in Microsoft Operating Systems</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/decipher-the-netflix-phenomenon-learn-korean/"><u>Decipher the Netflix Phenomenon: Learn Korean</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dota-2-fix-overcome-change-rendering-api-error-2024-in-a-flash/"><u>Dota 2 Fix: Overcome 'Change Rendering API' Error 2024 in a Flash!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dota-e-2-error-e2024-a-comprehensive-guide-to-restoring-graphics-functionality/"><u>Dota E 2 Error E2024: A Comprehensive Guide to Restoring Graphics Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-how-to-fix-windows-crashing-issue-error-0xc00000e9-explained-and-resolved/"><u>Expert Advice: How to Fix Windows Crashing Issue - Error 0Xc00#000e9 Explained and Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-changed-network-environment-warning-in-windows-10-easy-guide/"><u>Fix Changed Network Environment Warning in Windows 10 Easy Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-issues-why-your-usb-composite-device-wont-function-with-usb-echnology/"><u>Fixing Issues: Why Your USB Composite Device Won't Function With USB Echnology</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-correcting-unresponsive-keys-when-logging-into-your-pc/"><u>Guide: Correcting Unresponsive Keys When Logging Into Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210759329-how-to-fix-oddworld-soulstorm-pc-game-crashes-solved/"><u>How to Fix Oddworld: Soulstorm PC Game Crashes - Solved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-10-taskbar-visibility-issue-solutions-inside/"><u>How to Fix Windows 10 Taskbar Visibility Issue - Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-and-restore-a-non-functional-microphone-on-windows-11-pcs/"><u>How to Repair and Restore a Non-Functional Microphone on Windows 11 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-logitechs-unresponsive-vertical-scroll-on-your-device/"><u>How to Repair Logitech's Unresponsive Vertical Scroll on Your Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-audio-functionality-when-windows-reports-no-installed-speakers-or-headphones/"><u>How to Restore Audio Functionality When Windows Reports No Installed Speakers or Headphones</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-xls-document-online-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>How to sign a .xls document online</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-asus-rog-phone-8-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Asus ROG Phone 8 to Roku | Dr.fone</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-5-ways-change-your-home-address-in-googleapple-map-on-apple-iphone-13-miniipad-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Ways Change Your Home Address in Google/Apple Map on Apple iPhone 13 mini/iPad | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-poco-m6-pro-4g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Poco M6 Pro 4G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-tecno-spark-10-5g-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Tecno Spark 10 5G online without jailbreak</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigate-through-the-0xc000012f-dilemma-quick-fixes-for-a-smooth-windows-experience/"><u>Navigate Through the 0xC000012F Dilemma: Quick Fixes for a Smooth Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-mspcm-bar-with-finesse-in-windows-11-environment/"><u>Navigating MSPCM Bar with Finesse in Windows 11 Environment</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-create-unforgettable-home-videos-top-dvd-authoring-software-for-2024/"><u>New Create Unforgettable Home Videos Top DVD Authoring Software for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-monster-hunter-world-gameplay-interruptions-with-these-pc-optimization-techniques/"><u>Overcome 'Monster Hunter: World' Gameplay Interruptions with These PC Optimization Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-10-hurdles-a-fix-for-broken-right-click-buttons/"><u>Overcoming Windows 10 Hurdles: A Fix for Broken Right-Click Buttons</u></a></li>
<li><a href="https://win-howtos.techidaily.com/razer-keyboard-issues-why-isnt-it-lights-up-solutions-inside/"><u>Razer Keyboard Issues - Why Isn't It Lights Up? Solutions Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issue-non-responsive-keyboard-functionality-restored/"><u>Resolved Issue: Non-Responsive Keyboard Functionality Restored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-crashes-in-oddworld-soulstorm-on-windows-computers/"><u>Resolving Crashes in Oddworld: Soulstorm on Windows Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-touchpad-problems-effective-solutions-for-scroll-functionality/"><u>Resolving Windows 11 Touchpad Problems - Effective Solutions for Scroll Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-the-problem-of-an-unresponsive-microphone-on-your-pc-or-macbook/"><u>Solve the Problem of an Unresponsive Microphone on Your PC or MacBook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-of-error-0xc0000098-in-windows-a-step-by-step-guide/"><u>Solving the Mystery of Error 0xC0000098 in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speeding-up-the-shutdown-process-on-windows-10-a-step-by-step-guide/"><u>Speeding Up the Shutdown Process on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steelseries-arctis-5-microphone-not-working-heres-how-you-can-fix-it/"><u>SteelSeries Arctis 5 Microphone Not Working? Here's How You Can Fix It!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-overcoming-the-0x80072efd-error-on-your-windows-11-machine/"><u>Step-by-Step Guide: Overcoming the 0X80072EFD Error on Your Windows 11 Machine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-non-responsive-right-clicks-on-a-windows-10-pc/"><u>Step-by-Step Solution for Non-Responsive Right Clicks on a Windows 10 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-troubleshooting-for-fixing-non-recognized-usb-devices-and-failed-resets-on-windows-1n/"><u>Step-by-Step Troubleshooting for Fixing Non-Recognized USB Devices and Failed Resets on Windows 1N</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210506511-stop-waiting-start-typing-smoothly-solve-keyboard-lag-in-windows-10/"><u>Stop Waiting, Start Typing Smoothly - Solve Keyboard Lag in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-nonfunctional-mic-on-your-arctis-er-series-headset/"><u>Troubleshooting a Nonfunctional Mic on Your Arctis Er Series Headset</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-repair-your-non-responsive-bluetooth-mouse-on-windows/"><u>Troubleshooting Guide: How to Repair Your Non-Responsive Bluetooth Mouse on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206096917-troubleshooting-tips-resolving-a-warframe-update-failure-fix-your-game/"><u>Troubleshooting Tips: Resolving a 'Warframe Update Failure' - Fix Your Game!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-resolving-issues-with-a-non-functional-logitech-scroll-wheel/"><u>Troubleshooting Tips: Resolving Issues with a Non-Functional Logitech Scroll Wheel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unblocked-horizons-wows-breakthrough-in-full-spectrum-3d-graphics/"><u>Unblocked Horizons: WoW's Breakthrough in Full-Spectrum 3D Graphics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212125458-warframe-update-problems-heres-how-you-can-successfully-resolve-them/"><u>Warframe Update Problems? Here's How You Can Successfully Resolve Them</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Honor 90 Pro | Dr.fone</u></a></li>
</ul></div>
