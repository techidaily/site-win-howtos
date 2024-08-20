---
title: Step-by-Step Guide to Troubleshooting Failed Feature Updates on Windows 10 Version 1607
date: 2024-08-19T07:51:47.969Z
updated: 2024-08-20T07:51:47.969Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Guide to Troubleshooting Failed Feature Updates on Windows 10 Version 1607
excerpt: This Article Describes Step-by-Step Guide to Troubleshooting Failed Feature Updates on Windows 10 Version 1607
thumbnail: https://thmb.techidaily.com/3e64ab7fbedf01adf094c0f7a07b62ec8466f937073c7188969d1624a01e5f53.jpg
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
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
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
<li><a href="https://extra-tips.techidaily.com/new-best-choice-in-motion-typography-designs/"><u>[New] Best Choice in Motion Typography Designs</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-a-guide-to-mastering-steams-switch-pro-controller/"><u>[New] In 2024, A Guide to Mastering Steam's Switch Pro Controller</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-captivate-your-circle-the-art-of-sending-gifs-on-snapchat/"><u>[New] In 2024, Captivate Your Circle  The Art of Sending Gifs on Snapchat</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-kickstart-your-social-life-setting-up-a-facebook-account/"><u>[New] In 2024, Kickstart Your Social Life  Setting up a Facebook Account</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-pro-level-performance-a-compre-cookie-box-for-2024/"><u>[New] Pro-Level Performance  A Compre Cookie Box for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-smartphone-tools-for-crafting-your-ideal-vocal-sound/"><u>[New] Smartphone Tools for Crafting Your Ideal Vocal Sound</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-ultimate-guide-to-watching-fb-live-on-roku/"><u>[New] The Ultimate Guide to Watching FB Live on Roku</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-share-and-celebrate-with-instagram-videos/"><u>[Updated] 2024 Approved  Share & Celebrate with Instagram Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-remove-background-noise-from-your-youtube-video/"><u>[Updated] In 2024, How To Remove Background Noise From Your Youtube Video</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-obs-not-recording-audio-solved-for-2024/"><u>[Updated] OBS Not Recording Audio [Solved] for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-essential-media-makers-software-linux-edition/"><u>2024 Approved  Essential Media Makers' Software  Linux Edition</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-realities-redefined-the-metaverse-vs-omniverse-showdown-explained/"><u>2024 Approved  Realities Redefined  The Metaverse Vs. Omniverse Showdown Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/8-fixes-for-windows-11-update-error-code-0x800f0922/"><u>8 Fixes for Windows 11 Update Error Code 0X800f0922</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/amplifi-hd-wi-fi-networking-solution-say-goodbye-to-connectivity-dead-spots/"><u>Amplifi HD Wi-Fi Networking Solution: Say Goodbye to Connectivity Dead Spots</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-honor-90-lite-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Honor 90 Lite? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/buzzing-silence-addressing-laptop-and-headset-issues/"><u>Buzzing Silence: Addressing Laptop & Headset Issues</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-nokia-c12-plus-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-walkthrough-solve-your-windows-11s-persistent-0x800705b4-update-problem/"><u>Complete Walkthrough: Solve Your Windows 11'S Persistent 0X800705B4 Update Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-to-fix-unresponsive-audio-jack-on-pc-and-laptop/"><u>Comprehensive Guide To Fix: Unresponsive Audio Jack on PC & Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-displays-that-dont-recognize-pen-or-touch-inputs-a-step-by-step-guide/"><u>Dealing With Displays That Don't Recognize Pen or Touch Inputs: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-solutions-for-fixing-persistent-windows-solved-not-updating-glitches/"><u>Efficient Solutions for Fixing Persistent Windows ([Solved] - Not Updating) Glitches</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-installation-of-nahimic-audio-drivers-latest-update/"><u>Effortless Installation of Nahimic Audio Drivers - Latest Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-strategies-for-troubleshooting-bluetooth-pairing-problems-on-windows-10/"><u>Expert Strategies for Troubleshooting Bluetooth Pairing Problems on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-how-to-correctly-address-opengl-errors-in-minecraft/"><u>Expert Tips on How to Correctly Address OpenGL Errors in Minecraft</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-persistent-usb-connection-loss-step-by-step-guide/"><u>Fixing Persistent USB Connection Loss - Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-freeze-steps-to-successfully-complete-a-stagnant-windows-11-update/"><u>Fixing the Freeze: Steps to Successfully Complete a Stagnant Windows 11 Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-update-error-code-802e4019-step-by-step-solution-guide/"><u>Fixing Windows Update Error Code 802E4019: Step-by-Step Solution Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722977667015-free-hp-network-adapter-drivers-for-windows-10-7-and-8-download-now/"><u>Free HP Network Adapter Drivers for Windows 10, 7 & 8 - Download Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/from-isolation-to-connection-pcplusheadphones-resume-talking/"><u>From Isolation to Connection: PC+Headphones Resume Talking</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-tutorial-to-bypass-your-nokia-xr21-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Nokia XR21 Face Lock?</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-xr-to-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone XR To Android devices? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On OnePlus Nord CE 3 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ineteresourceerror-fixed-master-the-approach-to-rectify-missing-files/"><u>INET_E_RESOURCE_ERROR Fixed! Master the Approach to Rectify Missing Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210707915-jump-start-your-dead-laptop-battery-with-these-easy-troubleshooting-steps/"><u>Jump-Start Your Dead Laptop Battery with These Easy Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-unity-correcting-initialization-issues-related-to-graphics/"><u>Mastering Unity: Correcting Initialization Issues Related to Graphics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-guide-resolve-error-code-0x800f0831-using-windows-updates/"><u>Quick Fix Guide: Resolve Error Code 0X800f0831 Using Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-the-semaphore-timeout-interval-exceeded-error-code-0x80070079/"><u>Resolved: Fixing the 'Semaphore Timeout Interval Exceeded' Error Code 0X80070079</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-stuck-loading-screen-problem-in-destiny-2-quickly-and-easily/"><u>Resolving the Stuck Loading Screen Problem in Destiny 2 Quickly and Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-update-error-code-0x8023c401c-on-windows-10-and-11/"><u>Resolving Windows Update Error Code 0X802^3C401C on Windows 10 and 11</u></a></li>
<li><a href="https://fox-http.techidaily.com/ridiculousrender-hub-for-2024/"><u>RidiculousRender Hub for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/seamlessly-switch-between-languages-with-the-power-of-chatgpt/"><u>Seamlessly Switch Between Languages with the Power of ChatGPT</u></a></li>
<li><a href="https://extra-support.techidaily.com/selecting-audio-for-your-movie-trailer-for-2024/"><u>Selecting Audio for Your Movie Trailer for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-bluetooth-dilemma-reviving-windows-compatibility-with-a-malfunctioning-wireless-mouse/"><u>Solve Your Bluetooth Dilemma: Reviving Windows Compatibility with a Malfunctioning Wireless Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-issues-with-your-lenovo-laptops-webcam-a-step-by-step-guide/"><u>Solving Issues with Your Lenovo Laptop's Webcam: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/technical-troubles-gameplay-disruptions-on-pc/"><u>Technical Troubles: Gameplay Disruptions on PC</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-ultimate-guide-to-transforming-your-youtube-channel-via-wirecast-for-2024/"><u>The Ultimate Guide to Transforming Your Youtube Channel via WireCast for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-visual-vault-techniques-for-capturing-tweets-animated-content/"><u>The Visual Vault  Techniques for Capturing Tweets’ Animated Content</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-updating-to-windows-10-version-1607/"><u>Trouble with Updating to Windows 10 Version 1607?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solving-winodwss-error-code-eb-step-by-step-instructions/"><u>Troubleshooting and Solving Winodws's Error Code Eb - Step-by-Step Instructions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-the-non-responsive-spacebar-issue-in-windows-11/"><u>Troubleshooting Guide: Fixing the Non-Responsive Spacebar Issue in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-why-is-my-screen-not-recognizing-the-input-signal-timing/"><u>Troubleshooting Guide: Why Is My Screen Not Recognizing the Input Signal Timing?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-why-minecraft-fails-to-start-on-windows-solutions-inside/"><u>Troubleshooting Guide: Why Minecraft Fails to Start on Windows - Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211532287-troubleshooting-non-functional-volume-buttons-in-windows-11-solved/"><u>Troubleshooting Non-Functional Volume Buttons in Windows 11 – Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212225460-troubleshooting-total-war-rome-remastered-crashes-solved/"><u>Troubleshooting Total War Rome Remastered Crashes – Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-successfully-starting-hosted-networks-on-windows-11/"><u>Troubleshooting: Successfully Starting Hosted Networks on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-windows-11-installation-from-99-expert-tips-and-tricks/"><u>Unstick Your Windows 11 Installation From 99%% - Expert Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-to-do-if-there-is-a-red-x-on-the-wireless-network-icon/"><u>What to Do if There Is a Red X on the Wireless Network Icon</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-to-do-when-the-latest-windows-11-version-1607-update-wont-install-successfully/"><u>What to Do When the Latest Windows 11 Version 1607 Update Won't Install Successfully?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->