---
title: "Troubleshooting Guide: Resolving Windows Update and Installation Issues (Error Code 0X80070643)"
date: 2024-08-19T06:17:27.606Z
updated: 2024-08-20T06:17:27.606Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: Resolving Windows Update and Installation Issues (Error Code 0X80070643)"
excerpt: "This Article Describes Troubleshooting Guide: Resolving Windows Update and Installation Issues (Error Code 0X80070643)"
thumbnail: https://thmb.techidaily.com/65e1faefe5d8c9d98372975f4c9ce7cc4de93a99d55ba88c99cb9cdaa749d8eb.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
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
  
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-jotunheims-gambit-warriors-of-ragnarok/"><u>[New] 2024 Approved  Jotunheim's Gambit  Warriors of Ragnarok</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-leveraging-youtubes-features-to-improve-visuals/"><u>[New] Leveraging YouTube's Features to Improve Visuals</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-the-art-of-quantitative-vs-qualitative-analysis-a-guide-for-professionals/"><u>[New] Mastering the Art of Quantitative vs Qualitative Analysis  A Guide for Professionals</u></a></li>
<li><a href="https://youtube-web.techidaily.com/he-easiest-way-to-convert-your-youtube-videos-into-texts-for-free-for-2024/"><u>[New] The Easiest Way to Convert Your YouTube Videos Into Texts for FREE for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-tickletech-instant-creation-of-laughter-graphics/"><u>[New] TickleTech  Instant Creation of Laughter Graphics</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-unseen-wealth-the-underground-auction-of-elusive-artifacts-2023-edition/"><u>[New] Unseen Wealth  The Underground Auction of Elusive Artifacts, 2023 Edition</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-downloading-twitters-animated-content-simplified-for-2024/"><u>[Updated] Downloading Twitter's Animated Content Simplified for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-home-sweet-habitat-6-basic-mc-dwellings-demystified/"><u>[Updated] Home Sweet Habitat  6 Basic MC Dwellings Demystified</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-gain-more-loyal-viewers-unlock-top-strategies-for-enhancing-viewer-retention-on-youtube/"><u>[Updated] In 2024, Gain More Loyal Viewers  Unlock Top Strategies for Enhancing Viewer Retention on YouTube</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-next-gen-hd-video-recording-the-pinnacle-choices-for-2024/"><u>[Updated] Next-Gen HD Video Recording  The Pinnacle Choices for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-social-media-melody-ownership-laws/"><u>2024 Approved  Social Media Melody Ownership Laws</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-instagram-editors-companion-for-effective-video-cropping/"><u>2024 Approved  The Instagram Editor's Companion for Effective Video Cropping</u></a></li>
<li><a href="https://win-howtos.techidaily.com/arctis-5-wireless-headset-mic-repair-guide-tips-and-tricks-for-optimal-performance/"><u>Arctis 5 Wireless Headset Mic Repair Guide: Tips and Tricks for Optimal Performance</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-denied-learn-why-youre-banned-and-how-to-successfully-appeal-with-these-4-tactics/"><u>ChatGPT Denied? Learn Why You're Banned and How to Successfully Appeal with These 지정된 4 Tactics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-startup-issues-understanding-error-message-0xc000007b/"><u>Diagnosing and Fixing Startup Issues: Understanding Error Message 0Xc000007b</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-techniques-to-fix-and-prevent-power-surges-in-your-computers-usb-connections-on-windows-10/"><u>Effective Techniques to Fix and Prevent Power Surges in Your Computer's USB Connections on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-fixing-windows-10-computer-wont-power-off-problem/"><u>Expert Guide: Fixing Windows 10 Computer Won't Power Off Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-bluetooth-detection-problems-with-windows-10-solutions/"><u>Fix Your Bluetooth Detection Problems with Windows 10 Solutions</u></a></li>
<li><a href="https://win-able.techidaily.com/fixing-pc-lag-problems-in-resident-evil-village-step-by-step-solutions/"><u>Fixing PC Lag Problems in Resident Evil Village: Step-by-Step Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-vanishing-mouse-pointer-issue-in-windows-10-a-complete-guide/"><u>Fixing the Vanishing Mouse Pointer Issue in Windows 10 - A Complete Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>How to Change Netflix Location to Get More Country Version On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-windows-unable-to-find-printer-driver-issue/"><u>How To Resolve 'Windows Unable To Find Printer Driver' Issue</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-itel-a60s-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Itel A60s Devices</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-your-easy-route-to-tiktok-bliss-on-a-macbook/"><u>In 2024, Your Easy Route to TikTok Bliss on a MacBook</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/learn-how-to-lock-stolen-your-apple-iphone-se-2022-properly-drfone-by-drfone-ios/"><u>Learn How To Lock Stolen Your Apple iPhone SE (2022) Properly | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206451105-oddworld-soulstorm-crashing-on-windows-10-heres-the-solution/"><u>Oddworld Soulstorm Crashing On Windows 10? Here's The Solution!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-hang-ups-tips-for-unsticking-windows-11-performance-issues/"><u>Overcoming Hang-Ups: Tips for Unsticking Windows 11 Performance Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210991538-overcoming-voice-chat-hurdles-in-overwatch-simple-solutions-inside/"><u>Overcoming Voice Chat Hurdles in Overwatch - Simple Solutions Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-excessive-cpu-usage-by-svchostexe-in-windows-11-systems-efficiently/"><u>Resolve Excessive CPU Usage by svchost.exe in Windows 11 Systems Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fortnite-compatibility-with-unsupported-windows-graphics-cards/"><u>Resolved: Fortnite Compatibility with Unsupported Windows Graphics Cards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-connection-issues-with-unreachable-dhcp-servers/"><u>Resolved: Troubleshooting Connection Issues with Unreachable DHCP Servers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-high-cpu-consumption-issues-caused-by-wudfhostexe-on-windows-10/"><u>Resolving High CPU Consumption Issues Caused by wudfhost.exe on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-unexpected-bootups-in-windows-11-insights-and-solutions/"><u>Resolving Unexpected Bootups in Windows 11: Insights & Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-silent-companion-the-touchpad/"><u>Revive Your Silent Companion - The Touchpad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-access-denied-how-to-overcome-error-5-when-trying-to-run-files/"><u>Solving 'Access Denied': How to Overcome Error 5 When Trying to Run Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-of-a-non-functional-aoc-usb-monitor-under-windows-11-operating-system/"><u>Solving the Problem of a Non-Functional AOC USB Monitor Under Windows 11 Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-broken-night-light-on-windows-11-computers/"><u>Step by Step Solution for Broken Night Light on Windows 11 Computers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-changing-your-iphones-locale-settings/"><u>Step-by-Step Guide: Changing Your iPhone's Locale Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tips-on-eliminating-fatal-errors-from-call-of-duty-black-ops-iv/"><u>Step-by-Step Tips on Eliminating Fatal Errors From Call of Duty: Black Ops IV</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stuck-with-a-non-printable-pdf-heres-how-to-solve-it-fast/"><u>Stuck with a Non-Printable PDF? Here's How to Solve It Fast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-error-code-0x80224200d-when-updating-windows-solutions-inside/"><u>Troubleshooting Guide: Fixing Error Code 0X802^24200D When Updating Windows – Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-physxloaderdll-missing-on-launch-issues/"><u>Troubleshooting Guide: Resolving 'PhysXloader.dll' Missing on Launch Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-when-user-preferences-arent-working-properly/"><u>Troubleshooting Tips for When User Preferences Aren't Working Properly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-unresponsive-file-explorer-on-your-pc-windows-solutions-for-a-smooth-experience/"><u>Troubleshooting Unresponsive File Explorer on Your PC: Windows # Solutions for a Smooth Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-11-install-errors-your-ultimate-guide-to-handling-error-code-80240020/"><u>Troubleshooting Windows 11 Install Errors: Your Ultimate Guide to Handling Error Code 80240020</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-0xc0000005-exception-on-your-pc/"><u>Ultimate Guide: Resolving the 0xC0000005 Exception on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-solving-pubgs-startup-problems-in-the-exciting-2culed-edition-of-2024/"><u>Ultimate Guide: Solving PUBG's Startup Problems in the Exciting 2Culed Edition of 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-tips-for-pairing-your-xbox-one-controller-when-synching-issues-arise/"><u>Ultimate Tips for Pairing Your Xbox One Controller When Synching Issues Arise</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211877979-wacom-tablet-not-responding-heres-what-you-need-to-know/"><u>Wacom Tablet Not Responding? Here's What You Need to Know</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-interrupts-calm-down-overly-active-cpu/"><u>Windows Interrupts Calm Down Overly Active CPU</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-power-crisis-fixing-code-41/"><u>Windows Power Crisis: Fixing Code 41</u></a></li>
<li><a href="https://win-howtos.techidaily.com/xbox-one-wont-connect-to-xbox-live-solved/"><u>Xbox One Won’t Connect to Xbox Live [SOLVED]</u></a></li>
</ul></div>
