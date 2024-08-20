---
title: Troubleshooting Tips for Fixing Windows 11'S Persistent Black Screen Fault
date: 2024-08-19T06:31:53.412Z
updated: 2024-08-20T06:31:53.412Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Tips for Fixing Windows 11'S Persistent Black Screen Fault
excerpt: This Article Describes Troubleshooting Tips for Fixing Windows 11'S Persistent Black Screen Fault
thumbnail: https://thmb.techidaily.com/2ba5849aea90d4e5d7bbd18adc2a2c9c0f1eeac29f573eb68f13f17cdd7b780f.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
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
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
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
  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affd826668f.png)
  
**Run a system file check**
  
 Follow steps below:  
  
 1\. Open**Command Prompt** as an administrator.  
  
 2\. Type or paste**sfc /scannow** and hit**Enter** . The process will also take some time to complete.  
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://win-howtos.techidaily.com/fixed-bluetooth-keyboard-not-connecting-to-pc/"><u>[FIXED] Bluetooth Keyboard Not Connecting to PC</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-performers-the-leading-8k-camera-lineup/"><u>[New] Best Performers  The Leading 8K Camera Lineup</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-close-up-cinematic-magic-with-kinemaster-software/"><u>[New] Close-Up Cinematic Magic with Kinemaster Software</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-dive-into-ios-screenshots-a-comprehensive-youtube-guide/"><u>[New] In 2024, Dive Into iOS Screenshots  A Comprehensive YouTube Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-execute-a-budget-friendly-youtube-seminar/"><u>[New] In 2024, How to Execute a Budget-Friendly Youtube Seminar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-win-api-load-library-not-located/"><u>[Resolved]: Win API Load Library Not Located</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-inside-the-tech-top-reviews-for-home-videotaping-tools/"><u>[Updated] In 2024, Inside the Tech  Top Reviews for Home Videotaping Tools</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-zoom-essentials-for-webinar-novices-an-introductory-walkthrough/"><u>[Updated] Zoom Essentials for Webinar Novices  An Introductory Walkthrough</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-living-by-the-youtube-number-game-understanding-your-view-requirements/"><u>2024 Approved  Living by the YouTube Number Game  Understanding Your View Requirements</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-secrets-to-a-reliable-windows-11-photo-viewer/"><u>2024 Approved  Secrets to a Reliable Windows 11 Photo Viewer</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-transform-your-videos-presence-with-youtube-thumbnail-tailoring/"><u>2024 Approved  Transform Your Video's Presence with YouTube Thumbnail Tailoring</u></a></li>
<li><a href="https://fox-glue.techidaily.com/a-step-by-step-guide-to-professional-gopro-footage-for-2024/"><u>A Step-by-Step Guide to Professional Gopro Footage for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-struggles-top-tricks-for-seamless-pairing-with-windows-11-update-insights/"><u>Bluetooth Struggles? Top Tricks for Seamless Pairing with Windows 11 - Update Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/browser-security-alert-decoded-how-to-deal-with-firefox-secerrorunknownissuer/"><u>Browser Security Alert Decoded - How to Deal with FireFox SEC_ERROR_UNKNOWN_ISSUER</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clipboard-errors-in-windows-10-copypaste-functionality/"><u>Clipboard Errors in Windows 10 Copy/Paste Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-guide-to-overcome-installation-setbacks-solving-error-1603/"><u>Complete Guide to Overcome Installation Setbacks: Solving Error 1603</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-to-follow-instructions-turning-on-bluetooth-for-your-windows-7-operating-system/"><u>Easy-to-Follow Instructions: Turning On Bluetooth for Your Windows 7 Operating System</u></a></li>
<li><a href="https://network-issues.techidaily.com/effortless-correction-of-screen-aspect-ratios/"><u>Effortless Correction of Screen Aspect Ratios</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fixes-for-when-your-lenovo-fingerprint-recognition-stops-working/"><u>Effortless Fixes for When Your Lenovo Fingerprint Recognition Stops Working</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209717563-error-free-updates-ahead-conquer-windows-update-glitch-0x80070002-with-ease/"><u>Error-Free Updates Ahead! Conquer Windows Update Glitch 0X80070002 With Ease!</u></a></li>
<li><a href="https://buynow-help.techidaily.com/experience-the-epitome-of-fantasy-gaming-a-review-of-the-remastered-demons-souls-graphics/"><u>Experience the Epitome of Fantasy Gaming: A Review of the Remastered Demon's Souls Graphics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-diagnosing-and-fixing-improper-computer-boot-up-problems/"><u>Expert Advice on Diagnosing and Fixing Improper Computer Boot-Up Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-eliminating-crackling-sounds-from-pc-speakers-on-windowss/"><u>Expert Advice: Eliminating Crackling Sounds From PC Speakers on Windowss</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-rdr2-cannot-load-increase-pagefile-with-easy-steps/"><u>Fix 'RDR2 Cannot Load - Increase Pagefile' With Easy Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-common-errors-overcoming-the-driver-failure-in-user-settings-problem/"><u>Fixing Common Errors: Overcoming the 'Driver Failure in User Settings' Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-dirty-volume-problem-with-code-0x80071ac3-on-your-pc/"><u>Fixing the Dirty Volume Problem with Code 0X80071AC3 on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-your-dell-camera-up-and-running-again-on-windows-pcs-top-fixes-revealed/"><u>Get Your Dell Camera Up and Running Again on Windows PCs – Top Fixes Revealed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-steam-error-code-80/"><u>How to Fix Steam Error Code 80</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-undetected-devices-problems-with-bluetooth-on-windows-11-systems/"><u>How to Fix Undetected Devices Problems with Bluetooth on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-make-your-wd-my-passport-ultra-external-drive-visible-in-windows-systems/"><u>How to Make Your WD My Passport Ultra External Drive Visible in Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-windows-shell-common-dll-error-a-step-by-step-guide/"><u>How to Resolve 'Windows Shell Common DLL Error' – A Step-by-Step Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Google Pixel Fold? | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-improving-box-pull-back-pleasure/"><u>In 2024, Improving Box Pull-Back Pleasure</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Nokia C12 Pro? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-spotting-the-top-10-discreet-instagram-story-followers/"><u>In 2024, Spotting the Top 10 Discreet Instagram Story Followers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlocking-the-full-potential-of-apods-downloads/"><u>In 2024, Unlocking the Full Potential of APods Downloads</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-honor-magic-6-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Honor Magic 6 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lag-free-gaming-in-pubg-the-definitive-guide-to-best-performance-tweaks/"><u>Lag-Free Gaming in PUBG: The Definitive Guide to Best Performance Tweaks</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/master-screen-recording-on-windows-macos-and-android-devices/"><u>Master Screen Recording on Windows, macOS, and Android Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-error-651-repairs-simple-strategies-for-a-smooth-windows-experience/"><u>Mastering Error 651 Repairs: Simple Strategies for a Smooth Windows Experience</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/mastering-sewn-in-tiktoks-the-ultimate-guide/"><u>Mastering Sewn-In TikToks  The Ultimate Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-skype-visual-glitches-in-windows-11-with-easy-fixes/"><u>Overcome Skype Visual Glitches in Windows 11 with Easy Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ps4-whirring-buzzing-identifying-causes-and-applying-repairs/"><u>PS4 Whirring, Buzzing: Identifying Causes and Applying Repairs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-how-to-repair-your-huion-pen-when-it-stops-functioning/"><u>Quick Solutions: How to Repair Your Huion Pen When It Stops Functioning</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issues-with-geforce-experience-not-fetching-configurations-correctly/"><u>Resolved: Issues with GeForce Experience Not Fetching Configurations Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-overcoming-ssl-errors-and-establishing-a-secure-connection-in-firefox/"><u>Resolved: Overcoming SSL Errors and Establishing a Secure Connection in Firefox</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-startup-problems-in-microsoft-configurations-on-your-windows-10-pc-step-by-step/"><u>Resolving Startup Problems in Microsoft Configurations on Your Windows 10 PC [Step-by-Step]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-fix-for-usb-device-not-recognized-get-back-to-business/"><u>Simple Fix for 'USB Device Not Recognized': Get Back to Business!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-0x800f0831-error-instantly-a-guide-to-updating-your-windows-system/"><u>Solve 0X800f0831 Error Instantly: A Guide to Updating Your Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-black-screen-dilemma-with-your-asus-webcam-in-windows-11/"><u>Solving the Black Screen Dilemma with Your ASUS Webcam in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-problems-with-steam-store-ultimate-guide/"><u>Solving Your Problems with Steam Store: Ultimate Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-call-of-duty-world-war-ii-error-code-4220-malfunction/"><u>Step-by-Step Fix for Call of Duty World War II Error Code 4220 Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-rectify-windows-11s-error-code-0x80240034-during-updates/"><u>Step-by-Step Guide to Rectify Windows 11'S Error Code: 0X80240034 During Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-fixing-your-keyboard-by-rebooting/"><u>Step-by-Step Guide: Fixing Your Keyboard by Rebooting</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-vivo-x90s-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on Vivo X90S without backup.</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-free-ai-imagery-tools-using-open-source-technology/"><u>Top 5 Free AI Imagery Tools Using Open Source Technology</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-strategies-to-overcome-and-prevent-error-0x8000ffff-from-crashing-your-windows-system/"><u>Top Strategies to Overcome and Prevent Error 0X8000ffff From Crashing Your Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210003398-triumph-over-silent-touchpad-in-device-realm/"><u>Triumph Over Silent Touchpad in Device Realm!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-fixing-the-absent-d3dx939dll-error-message/"><u>Troubleshooting Steps for Fixing the Absent D3DX9_39.dll Error Message</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-persistent-disappearance-of-cursor-on-windows-10-devices/"><u>Troubleshooting: Persistent Disappearance of Cursor on Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/xbox-one-controller-woes-heres-how-to-fix-connection-issues/"><u>Xbox One Controller Woes? Here’s How to Fix Connection Issues</u></a></li>
</ul></div>
