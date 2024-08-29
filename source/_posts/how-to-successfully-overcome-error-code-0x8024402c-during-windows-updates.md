---
title: How to Successfully Overcome Error Code 0X8024402c During Windows Updates
date: 2024-08-28T00:27:24.997Z
updated: 2024-08-29T00:27:24.997Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Successfully Overcome Error Code 0X8024402c During Windows Updates
excerpt: This Article Describes How to Successfully Overcome Error Code 0X8024402c During Windows Updates
thumbnail: https://thmb.techidaily.com/795b74ea54cc5678eb54323c8f0f4911a2d522641c62a676cf0d7c5aa1dfbffa.jpg
---

## How to Successfully Resolve Error Code 0X80ebbbb on Windows Updates - Proven Techniques Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Now try to install Windows Updates now.

After the fixes above, Windows Update should be good to go now.

* [Windows Update](/tag-search/?tagId=62)


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
<li><a href="https://youtube-docs.techidaily.com/024-approved-which-video-platform-suits-you-better-tiktok-or-youtube-shorts/"><u>[New] 2024 Approved  Which Video Platform Suits You Better  TikTok or YouTube Shorts?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-5-quick-hacks-to-sharpen-your-indie-filmmaking-skills/"><u>[New] 5 Quick Hacks to Sharpen Your Indie Filmmaking Skills</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-essential-tips-for-rl-screen-recording/"><u>[New] Essential Tips for RL Screen Recording</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-pathway-to-personalizing-your-virtual-existence/"><u>[New] The Pathway to Personalizing Your Virtual Existence</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-unlocking-crossfade-magic-using-audacity-effectively-for-2024/"><u>[New] Unlocking Crossfade Magic  Using Audacity Effectively for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-8-pioneering-exercise-videos-to-keep-your-viewers-active/"><u>[Updated] 2024 Approved  8 Pioneering Exercise Videos To Keep Your Viewers Active</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-precision-style-capturing-your-macootd-tiktok-guide/"><u>[Updated] Precision Style Capturing  Your MacOOTD TikTok Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-dos-and-donts-of-interacting-with-youtube-viewers/"><u>[Updated] The Do's and Don'ts of Interacting with YouTube Viewers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-top-picks-excellent-fb-lite-video-downloaders-of-2023/"><u>[Updated] The Top Picks  Excellent FB Lite Video Downloaders of 2023</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-top-12-clicker-games-on-pc-for-2024/"><u>[Updated] Top 12 Clicker Games on PC for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-chuckles-unleashed-best-sites-for-funny-tones/"><u>2024 Approved  Chuckles Unleashed  Best Sites for Funny Tones</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-leading-meaningful-conversations-an-interviewers-journey/"><u>2024 Approved  Leading Meaningful Conversations  An Interviewer's Journey</u></a></li>
<li><a href="https://extra-hints.techidaily.com/auroras-high-dynamic-range-a-game-changer-in-2024/"><u>Aurora's High Dynamic Range  A Game Changer, In 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-in-class-meme-modification-software/"><u>Best in Class Meme Modification Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/call-of-duty-world-war-ii-troubleshooting-guide-overcome-error-4220/"><u>Call of Duty World War II Troubleshooting Guide - Overcome Error 4220</u></a></li>
<li><a href="https://games-able.techidaily.com/claiming-your-money-back-from-xbox-game-bets/"><u>Claiming Your Money Back From Xbox Game Bets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-solution-to-input-source-unavailable-error-on-your-screen/"><u>Complete Solution to 'Input Source Unavailable' Error On Your Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cracking-the-code-on-windows-update-failure-error-0x8024200d-a-comprehensive-solution-guide/"><u>Cracking the Code on Windows Update Failure (Error 0X8024200D): A Comprehensive Solution Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-dx-feature-level-10-issue-on-your-wwe-gamehttpswwwexample-game-linkcom-2k-battl/"><u>Effective Fixes for DX Feature Level 10 Issue on Your WWE ([^Game](https://www.example-game-link.com)) 2K Battl</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-to-resolve-freezing-issues-with-windows-11-taskbar/"><u>Effective Strategies to Resolve Freezing Issues with Windows 11 Taskbar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-ways-to-resolve-lack-of-sound-device-in-windows-10-or-11/"><u>Effective Ways to Resolve Lack of Sound Device in Windows 10 or 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-repairing-and-reviving-a-damaged-igfxem-unit/"><u>Expert Advice: Repairing and Reviving a Damaged IgfxEM Unit</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-recommendations-the-ideal-accessories-every-iphone-owner-needs/"><u>Expert Recommendations: The Ideal Accessories Every iPhone Owner Needs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-techniques-for-repairing-a-broken-camera-on-your-lenovo-device/"><u>Expert Techniques for Repairing a Broken Camera on Your Lenovo Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-restoring-functionality-to-your-quick-capture-tool-with-the-windows-key-combo-on-new-versions-of-windows-os/"><u>Expert Tips: Restoring Functionality to Your Quick Capture Tool with the Windows Key Combo on New Versions of Windows OS</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-llama-2-comprehensive-guide-for-effective-utilization/"><u>Exploring Llama 2: Comprehensive Guide for Effective Utilization</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fail-to-initialize-directx-easy-fix/"><u>Fail to Initialize DirectX - Easy Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-dota-2-change-rendering-api-error-code-2024-in-minutes/"><u>Fix Your Dota 2 'Change Rendering API' Error Code 2024 in Minutes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-netflix-keeps-freezing-on-computer/"><u>Fixed: Netflix Keeps Freezing on Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-recurring-problems-with-unrecognized-external-devices-on-pc-expert-advice/"><u>Fixing Recurring Problems with Unrecognized External Devices on PC – Expert Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-invisible-mouse-pointer-problem-on-windows-11-systems/"><u>Fixing the Invisible Mouse Pointer Problem on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-total-war-rome-remastered-game-crashes-complete-solution/"><u>Fixing Total War: Rome Remastered Game Crashes – Complete Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-your-mouses-right-click-functionality-issues-in-windows-11/"><u>Fixing Your Mouse's Right Click Functionality Issues in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-class-registration-issues-in-windows-11-a-comprehensive-guide/"><u>How to Fix Class Registration Issues in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-elevated-cpu-load-caused-by-microsofts-sound-isolation-tech/"><u>How to Fix Elevated CPU Load Caused by Microsoft's Sound Isolation Tech</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-device-not-found-message-with-code-24-in-windows-operating-systems/"><u>How to Fix the 'Device Not Found' Message with Code 24 in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-prevent-auto-sleep-on-pc-or-laptop-easy-steps-inside/"><u>How to Prevent Auto-Sleep on PC or Laptop - Easy Steps Inside</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On OnePlus 12R? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-oppo-a2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-iphone-14-plus-device-from-icloud-by-drfone-ios/"><u>In 2024, How to Remove iPhone 14 Plus Device from iCloud</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-sony-xperia-10-v-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Sony Xperia 10 V Phone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-vimeos-gratis-editing-guide-enhance-videos-on-budget/"><u>In 2024, Vimeo's Gratis Editing Guide  Enhance Videos on Budget</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-connection-woes-how-to-establish-a-bond-with-your-xbox-one-gaming-peripheral/"><u>Mastering Connection Woes: How to Establish a Bond with Your Xbox One Gaming Peripheral</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigate-past-windows-update-snags-with-proven-techniques-for-resolving-error-0x802n105/"><u>Navigate Past Windows Update Snags with Proven Techniques for Resolving Error 0X802n105</u></a></li>
<li><a href="https://buynow-info.techidaily.com/navigating-photoscapes-features-a-detailed-analysis-of-free-high-quality-image-editing-software/"><u>Navigating PhotoScape's Features – A Detailed Analysis of Free High-Quality Image Editing Software</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-guide-how-to-check-icloud-activation-lock-status-from-your-iphone-14-by-drfone-ios/"><u>New Guide How To Check iCloud Activation Lock Status From Your iPhone 14</u></a></li>
<li><a href="https://win-howtos.techidaily.com/nier-automata-pc-game-keep-crashing-try-these-fixes-now/"><u>Nier: Automata PC Game Keep Crashing? Try These Fixes Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-the-missing-dll-hurdle-restoring-vcruntime140dll-on-windows-10-solution/"><u>Overcome the Missing DLL Hurdle: Restoring VCRUNTIME140.dll on Windows 10 [Solution]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210919609-quick-guide-resolve-error-0x88a0006-in-minutes-with-simple-fixes/"><u>Quick Guide: Resolve Error 0X88^A0006 in Minutes with Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-start-solution-how-to-resolve-slow-lol-download-speed-bottlenecks/"><u>Quick-Start Solution: How to Resolve Slow LoL Download Speed Bottlenecks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-boot-issues-in-windows-10-common-causes-and-solutions/"><u>Resolving Boot Issues in Windows 10: Common Causes and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-lack-of-touchpen-responsiveness-on-displays/"><u>Resolving Lack of Touch/Pen Responsiveness on Displays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-dilemma-when-skype-microphone-fails-to-work/"><u>Resolving the Dilemma: When Skype Microphone Fails to Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-why-your-wd-my-passport-ultra-may-not-appear-on-windows/"><u>Resolving the Issue: Why Your WD My Passport Ultra May Not Appear on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-touchscreen-on-windows-11-top-5-methods/"><u>Reviving Your Touchscreen on Windows 11: Top 5 Methods</u></a></li>
<li><a href="https://extra-information.techidaily.com/richer-screen-content-filter-integration-on-devices/"><u>Richer Screen Content  Filter Integration on Devices</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1715701261028-snap-and-save-your-android-no-price-tag/"><u>Snap & Save Your Android - No Price Tag!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-connectivity-issues-with-usb-ports-in-recent-windows-versions/"><u>Solving Connectivity Issues with USB Ports in Recent Windows Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-non-functional-scroll-wheel-issues-on-synaptics-trackpads-post-windows-11-update/"><u>Solving Non-Functional Scroll Wheel Issues on Synaptics Trackpads Post-Windows 11 Update</u></a></li>
<li><a href="https://facebook.techidaily.com/stealthy-step-down-tactics-to-delete-multiple-business-profiles-on-facebook/"><u>Stealthy Step-Down Tactics to Delete Multiple Business Profiles on Facebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-nonfunctional-night-light-setting-in-modern-windows-pcs/"><u>Step-by-Step Fixes for Nonfunctional Night Light Setting in Modern Windows PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-instructions-addressing-the-unknown-usb-device-and-port-reset-complications-in-your-windows-10-system/"><u>Step-by-Step Instructions: Addressing the 'Unknown USB Device' And Port Reset Complications in Your Windows 10 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-restoring-healthy-file-integrity-for-windows-11-systems/"><u>Step-by-Step Tutorial: Restoring Healthy File Integrity for Windows 11 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-social-sphere-understanding-facebook-twitter-instagram-and-youtube/"><u>The Quintessential Social Sphere: Understanding Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-the-livekernelevent-144-issue/"><u>Troubleshooting and Resolving the 'LiveKernelEvent 144' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-vanishing-desktop-symbols-on-windows-11-devices/"><u>Troubleshooting Tips for Vanishing Desktop Symbols on Windows 11 Devices</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-slowing-down-gif-with-the-best-available-methods/"><u>Updated 2024 Approved Slowing Down GIF With The Best Available Methods</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-is-my-dell-wireless-keyboard-unresponsive-lets-resolve-it-together/"><u>Why Is My Dell Wireless Keyboard Unresponsive? Let's Resolve It Together</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-10-not-closing-complete-guide-for-successful-system-shutdown/"><u>Win 10 Not Closing? Complete Guide for Successful System Shutdown</u></a></li>
</ul></div>
