---
title: Troubleshooting Steps when Microsoft's Print to PDF Feature Fails on Windows 11
date: 2024-08-23T14:07:08.140Z
updated: 2024-08-24T14:07:08.140Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps when Microsoft's Print to PDF Feature Fails on Windows 11
excerpt: This Article Describes Troubleshooting Steps when Microsoft's Print to PDF Feature Fails on Windows 11
thumbnail: https://thmb.techidaily.com/cbd55a60b36d243580c486b7896cd6baf0fe5a1c6ab330fc24fdad62a19d7e96.jpeg
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
<li><a href="https://sound-issues.techidaily.com/2024-fix-rainbow-six-siege-voice-chat-not-working/"><u>[2024 Fix] Rainbow Six Siege Voice Chat Not Working</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-a-guide-to-top-screen-capture-for-zoom/"><u>[New] In 2024, A Guide to Top Screen Capture for Zoom</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-decoding-digital-dazzle-an-initial-journey-into-video-standards/"><u>[New] In 2024, Decoding Digital Dazzle  An Initial Journey Into Video Standards</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-instagram-riches-guide-ranking-the-top-earner-posts/"><u>[New] In 2024, Instagram Riches Guide  Ranking the Top Earner Posts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-pro-level-strategies-for-remote-audio-capture/"><u>[New] Pro-Level Strategies for Remote Audio Capture</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-fine-tune-viewing-the-ultimate-zoom-journey/"><u>[Updated] Fine-Tune Viewing  The Ultimate Zoom Journey</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-captivating-spokesperson-appraisal-8th-analysis/"><u>[Updated] In 2024, Captivating Spokesperson Appraisal 8Th Analysis</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-iphones-in-action-capturing-and-altering-slow-motion-content/"><u>[Updated] IPhones in Action  Capturing & Altering Slow Motion Content</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-overview-of-magix-audio-enhancer/"><u>[Updated] Overview of MAGIX Audio Enhancer</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-3-simple-methods-for-color-correction-in-adobe-photoshop/"><u>2024 Approved  3 Simple Methods for Color Correction in Adobe Photoshop</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-cam-division-is-splitcam-the-1-choice/"><u>2024 Approved  Cam Division  Is SplitCam the #1 Choice?</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-framing-frontiers-cutting-edge-app-innovations-24/"><u>2024 Approved  Framing Frontiers  Cutting-Edge App Innovations '24</u></a></li>
<li><a href="https://win-howtos.techidaily.com/baffled-by-sticky-keys-successfully-reinitialize-any-keyboard-in-no-time/"><u>Baffled by Sticky Keys? Successfully Reinitialize Any Keyboard in No Time</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-twitch-error-4000-your-ultimate-guide-to-a-smooth-streaming-experience/"><u>Beat Twitch Error 4000: Your Ultimate Guide to a Smooth Streaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-woes-no-more-effective-solutions-for-windows-users-facing-mouse-connectivity-problems/"><u>Bluetooth Woes No More: Effective Solutions for Windows Users Facing Mouse Connectivity Problems</u></a></li>
<li><a href="https://fox-http.techidaily.com/breaking-through-with-stunning-hdr-portrait-shots/"><u>Breaking Through with Stunning HDR Portrait Shots</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-device-migration-issues-on-windows-10-a-step-by-step-guide/"><u>Bypassing Device Migration Issues on Windows 10 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ceasing-the-unplanned-boot-troubleshooting-autostart-in-windows-10-systems/"><u>Ceasing the Unplanned Boot: Troubleshooting Autostart in Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-a-disappearing-touchpad-cursor-on-windows-11/"><u>Effective Solutions for a Disappearing Touchpad Cursor on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-errors-encountered-during-steam-games-installupdate/"><u>Effective Solutions for Errors Encountered During Steam Games Install/Update</u></a></li>
<li><a href="https://fox-info.techidaily.com/effortless-auditory-transition-with-logic-pro-x-for-2024/"><u>Effortless Auditory Transition with Logic Pro X for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-message-deciphered-fixing-the-camera-not-available-code-0xa0aturatecdouble-d-in-windows/"><u>Error Message Deciphered: Fixing the 'Camera Not Available, Code 0xA0aturate(c_double D);' In Windows</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/expert-picks-leading-software-options-for-iphone-contacts-restoration/"><u>Expert Picks: Leading Software Options for iPhone Contacts Restoration</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-significant-bugs-in-call-of-duty-black-ops-4/"><u>Expert Tips for Fixing Significant Bugs in Call of Duty: Black Ops 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-fix-resolving-windows-update-error-code-8007000e-in-minutes/"><u>Fast Fix: Resolving Windows Update Error Code 8007000E in Minutes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-common-problems-solutions-for-when-your-wacom-tablet-fails/"><u>Fixing Common Problems: Solutions for When Your Wacom Tablet Fails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-safari-page-loading-problems-simple-steps-for-success/"><u>Fixing Safari Page Loading Problems - Simple Steps for Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-0x80073712-problem-on-your-windows-10-pc-a-step-by-step-guide/"><u>Fixing the '0X80073712' Problem on Your Windows 10 PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-geforce-experience-launch-problem-a-comprehensive-solution/"><u>Fixing the GeForce Experience Launch Problem: A Comprehensive Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-igfxem-driver-errors-and-restore-graphics-functionality/"><u>How to Fix igfxEM Driver Errors and Restore Graphics Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unresponsive-computer-systems-expert-advice-for-a-smooth-run/"><u>How To Fix Unresponsive Computer Systems: Expert Advice for a Smooth Run</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-volume-is-dirty-mistake-error-0x80071ac3-on-your-pc/"><u>How to Resolve 'Volume Is Dirty' Mistake (Error 0X80071AC3) on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209101959-how-to-restore-the-missing-d3dx939dll-file-and-fix-related-issues-quickly/"><u>How To Restore The Missing D3DX9_39.dll File & Fix Related Issues Quickly!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-write-data-into-a-0x-memory-space-that-has-been-referenced-by-an-instruction/"><u>How to Successfully Write Data Into a 0X Memory Space That Has Been Referenced by an Instruction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/huion-pen-not-working-5-ways-to-fix-it-fast/"><u>Huion Pen Not Working? 5 Ways to Fix It Fast</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-chuckle-craft-ranking-the-top-10-memes-by-wow-factor/"><u>In 2024, Chuckle Craft  Ranking the Top 10 Memes by Wow Factor</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-oppo-reno-8t-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Oppo Reno 8T for Free? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-memorize-mastery-galaxy-phone-gameplay-archive/"><u>In 2024, Memorize Mastery  Galaxy Phone Gameplay Archive</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-revolutionary-process-to-blend-gopro-videos-into-360-degree-panoramas/"><u>In 2024, Revolutionary Process to Blend GoPro Videos Into 360-Degree Panoramas</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205290979-lost-in-no-sense-fix-your-sd-card/"><u>Lost in No-Sense: Fix Your SD Card!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-art-of-fast-shutdowns-in-windows-11-top-strategies-to-try-now/"><u>Mastering the Art of Fast Shutdowns in Windows 11: Top Strategies to Try Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/missing-dll-files-correct-vcruntime140-error-on-windows-11-for-smooth-program-execution-a-detailed-walkthrough-solved/"><u>Missing DLL Files? Correct VCRUNTIME140^ Error on Windows 11 for Smooth Program Execution: A Detailed Walkthrough [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-guide-speeding-up-your-league-of-legends-installation/"><u>Quick Guide: Speeding Up Your League of Legends Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-mouse-cursor-vanishing-issues-in-windows-11-a-complete-guide/"><u>Resolving Mouse Cursor Vanishing Issues in Windows 11 - A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/say-goodbye-to-buffering-easy-fix-for-your-kodi-playback-issues/"><u>Say Goodbye to Buffering: Easy Fix for Your Kodi Playback Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/silent-streams-no-more-fixing-netflixs-sound-problem-with-simple-tips/"><u>Silent Streams No More - Fixing Netflix's Sound Problem with Simple Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-laptops-experiencing-constant-whiteblack-screens/"><u>Step-by-Step Solutions for Laptops Experiencing Constant White/Black Screens</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-restore-functionality-to-your-non-responsive-ps4-dualshock/"><u>Step-by-Step Tutorial: Restore Functionality to Your Non-Responsive PS4 DualShock</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-gain-trustee-access-from-trustedinstaller-file-modification-guidance/"><u>Steps to Gain Trustee Access From TrustedInstaller: File Modification Guidance</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-oneplus-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to OnePlus FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-repair-how-to-correctly-resolve-windows-10-soundrenderer-errors-for-youtube-videos/"><u>Troubleshoot & Repair: How To Correctly Resolve Windows 10 SoundRenderer Errors for YouTube Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-desktop-not-available-error-in-windows-system-profile/"><u>Troubleshooting 'Desktop Not Available' Error in Windows System Profile</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-fix-skype-video-problems-in-windows-10/"><u>Troubleshooting Guide: How to Fix Skype Video Problems in Windows 10</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-tips-for-fixing-missing-binkw32dll-issues-efficiently/"><u>Troubleshooting Tips for Fixing Missing binkw32.dll Issues Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-update-failures-expert-tips-and-solutions/"><u>Troubleshooting Windows Update Failures - Expert Tips & Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-overcome-your-pcs-perpetual-startup-loop/"><u>Troubleshooting: Overcome Your PC's Perpetual Startup Loop</u></a></li>
<li><a href="https://win-solutions.techidaily.com/ultimate-tricks-to-enhance-origin-download-speed-for-a-faster-2024-experience/"><u>Ultimate Tricks to Enhance Origin Download Speed for a Faster 2024 Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208583632-winning-against-the-incorrect-side-by-side-config-error-on-windows-11-solutions-within/"><u>Winning Against the 'Incorrect Side by Side Config' Error on Windows 11 - Solutions Within</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->