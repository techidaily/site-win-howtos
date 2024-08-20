---
title: Troubleshooting Steps for Fixing a Red Cross Appearing Over Your Network Symbol
date: 2024-08-19T06:13:53.508Z
updated: 2024-08-20T06:13:53.508Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps for Fixing a Red Cross Appearing Over Your Network Symbol
excerpt: This Article Describes Troubleshooting Steps for Fixing a Red Cross Appearing Over Your Network Symbol
thumbnail: https://thmb.techidaily.com/acfd39cea130b7076ba0e472a472a7627f6c0d070677e69a7cb579139c188cc2.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-the-global-communicators-essential-list-of-top-36-platforms-for-video-conversion/"><u>[New] In 2024, The Global Communicator’s Essential List of Top 36 Platforms for Video Conversion</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-the-beginner-pro-marketing-playbook-secrets-of-facebook-success-for-2024/"><u>[New] The Beginner-Pro Marketing Playbook  Secrets of Facebook Success for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-is-higher-frame-rate-better-weighing-30-vs-60fps-in-video-for-2024/"><u>[Updated] Is Higher Frame Rate Better? Weighing 30 Vs. 60Fps in Video for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-unlock-iphone-editing-magic-shorter-smaller-videos/"><u>[Updated] Unlock iPhone Editing Magic  Shorter, Smaller Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-premier-5-iphones-for-podcast-aficionados/"><u>2024 Approved  Premier 5 iPhones for Podcast Aficionados</u></a></li>
<li><a href="https://win-howtos.techidaily.com/address-and-correct-the-network-connection-error-0x800704cf-a-detailed-walkthrough-for-windows-users/"><u>Address and Correct the Network Connection Error 0X800704cf: A Detailed Walkthrough for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avoiding-memory-integrity-risks-in-ftdibus-systems-with-compatible-device-drivers/"><u>Avoiding Memory Integrity Risks in Ftdibus Systems with Compatible Device Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/best-practices-to-resolve-freezing-issues-with-windows-10-taskbar/"><u>Best Practices to Resolve Freezing Issues with Windows 10 Taskbar</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/capturing-stunning-selfies-with-the-best-selfie-light-setup-tips/"><u>Capturing Stunning Selfies with the Best Selfie Light Setup Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/code-24-in-windows-overcoming-this-device-is-not-present-issues-across-versions-11-8-and-397/"><u>Code 24 in Windows: Overcoming 'This Device Is Not Present' Issues Across Versions 11, 8, & #39;7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/common-causes-and-solutions-for-mistyping-on-your-keyboard/"><u>Common Causes and Solutions for Mistyping on Your Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-rectify-resolving-issues-with-compromised-filesystems-in-windows-11/"><u>Diagnose & Rectify: Resolving Issues with Compromised Filesystems in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dll-installer-not-executed-for-crtdll/"><u>DLL Installer Not Executed for crt.dll</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-the-google-chrome-black-screen-dilemma-a-step-by-step-guide/"><u>Easy Fixes for the Google Chrome Black Screen Dilemma: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-when-your-game-library-is-inaccessible-due-to-steam-network-connection-failures/"><u>Effective Fixes for When Your Game Library Is Inaccessible Due to Steam Network Connection Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-message-deciphered-solutions-for-installing-windows-11-with-error-80240020/"><u>Error Message Deciphered: Solutions for Installing Windows 11 with Error 80240020</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-responding-to-hanging-windows-10-issues-quickly-and-effectively/"><u>Expert Guide: Responding to Hanging Windows 10 Issues Quickly and Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-update-hiccups-conquering-error-0x800705b-and-related-codes/"><u>Fixing Windows Update Hiccups: Conquering Error 0X800705b and Related Codes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-activate-a-virtual-wifi-hotspot-in-windows-11-fixed/"><u>How to Activate a Virtual WiFi Hotspot in Windows 11 (Fixed)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unresponsive-file-explorer-issues-in-windows-11-quickly-and-efficiently/"><u>How to Fix Unresponsive File Explorer Issues in Windows 11 Quickly & Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-recover-the-hidden-or-missing-wi-fi-features-in-windows-11/"><u>How to Recover the Hidden or Missing Wi-Fi Features in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-failed-user-profile-service-sign-in-problems-in-windows-11/"><u>How to Repair Failed User Profile Service Sign-In Problems in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Samsung Galaxy XCover 6 Pro Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-shockwave-flash-on-google-chrome-overcome-the-compatibility-hurdle-today/"><u>No More Shockwave Flash on Google Chrome: Overcome the Compatibility Hurdle Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212441035-pdf-wont-print-out-check-these-rapid-remedies/"><u>PDF Won't Print Out? Check These Rapid Remedies!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-guide-overcoming-startup-problems-with-amd-catalyst-utility/"><u>Quick Fix Guide: Overcoming Startup Problems with AMD Catalyst Utility</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reactivating-the-windows-update-feature-efficiently/"><u>Reactivating the Windows Update Feature Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-personalization-feature-non-responsiveness-errors/"><u>Resolving Personalization Feature Non-Responsiveness Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-for-when-your-corsair-keyboard-stops-responding/"><u>Solutions for When Your Corsair Keyboard Stops Responding</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/solutions-to-spy-on-apple-iphone-12-pro-max-with-and-without-jailbreak-drfone-by-drfone-virtual-ios/"><u>Solutions to Spy on Apple iPhone 12 Pro Max with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-mouse-cursor-visibility-problems-on-your-windows-11-laptop/"><u>Solve Mouse Cursor Visibility Problems on Your Windows 11 Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-store-not-working-heres-how-to-restore-access/"><u>Steam Store Not Working? Here’s How to Restore Access!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-when-your-bluetooth-mouse-wont-connect-with-windows/"><u>Step-by-Step Solutions: When Your Bluetooth Mouse Won't Connect with Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/svchostexe-and-windows-11-overcoming-high-cpu-usage-problems-easily/"><u>svchost.exe and Windows 11: Overcoming High CPU Usage Problems Easily</u></a></li>
<li><a href="https://facebook.techidaily.com/the-enigma-of-shadowban-and-how-to-circumvent-it/"><u>The Enigma of Shadowban and How to Circumvent It</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-infinix-zero-5g-2023-turbo-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Infinix Zero 5G 2023 Turbo Phone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-overwatch-audio-solving-voice-chat-glitches-fast/"><u>Troubleshoot Your Overwatch Audio: Solving Voice Chat Glitches Fast!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-slow-reaction-times-in-windows-10-keyboards/"><u>Troubleshooting and Resolving Slow Reaction Times in Windows 10 Keyboards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-error-code-5-access-is-denied-while-running-files-in-temp-folder/"><u>Troubleshooting Error Code 5: Access Is Denied While Running Files in Temp Folder</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixes-for-non-functional-function-key-issues-on-asus-computers/"><u>Troubleshooting Fixes for Non-Functional Function Key Issues on Asus Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-the-issue-when-your-keyboards-backspace-function-isnt-responding/"><u>Troubleshooting Guide: Fixing the Issue When Your Keyboard's 'Backspace' Function Isn't Responding</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-functional-usb-ports-on-windows-11/"><u>Troubleshooting Non-Functional USB Ports on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-persistent-restarts-in-windows-11-made-easy/"><u>Troubleshooting Persistent Restarts in Windows 11 Made Easy</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-sound-issues-windows-11-lacks-an-input-device/"><u>Troubleshooting Sound Issues: Windows 11 Lacks an Input Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-resolving-secured-connection-not-established-in-mozilla-firefox/"><u>Troubleshooting Steps: Resolving 'Secured Connection Not Established' In Mozilla Firefox</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-overcoming-timeout-problems-when-downloading-content/"><u>Troubleshooting Tips: Overcoming 'Timeout' Problems When Downloading Content</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-issues-with-your-lenovo-laptop-webcam/"><u>Ultimate Guide: Resolving Issues with Your Lenovo Laptop Webcam</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-solving-code-31-issues-in-windows-computers/"><u>Understanding and Solving Code 31 Issues in Windows Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/your-rendering-device-has-been-lost-overwatch-error-fix/"><u>Your Rendering Device Has Been Lost Overwatch Error Fix</u></a></li>
</ul></div>
