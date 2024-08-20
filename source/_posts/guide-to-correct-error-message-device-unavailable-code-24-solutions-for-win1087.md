---
title: Guide to Correct Error Message - Device Unavailable (Code 24), Solutions for Win10/8/7
date: 2024-08-19T07:44:06.981Z
updated: 2024-08-20T07:44:06.981Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Guide to Correct Error Message - Device Unavailable (Code 24), Solutions for Win10/8/7
excerpt: This Article Describes Guide to Correct Error Message - Device Unavailable (Code 24), Solutions for Win10/8/7
thumbnail: https://thmb.techidaily.com/a5249e9b13fd437412102feed5c7841b8ccf98fdf0188fbbf3a215fd35680a08.JPG
---

## Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here

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

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-leading-speech-recording-software-for-mac-discovering-our-five-favorites/"><u>[New] In 2024, Leading Speech Recording Software for Mac  Discovering Our Five Favorites</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solvedwhat-is-mse-and-why-microsoft-security-essentials-mssecesexe-high-disk-usage/"><u>[Solved]What Is MSE and Why Microsoft Security Essentials (msseces.exe) High Disk Usage</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-instagram-perfection-sizing-your-video-just-right/"><u>[Updated] 2024 Approved  Instagram Perfection  Sizing Your Video Just Right</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-asmrs-role-in-better-nights-expert-vocal-guides/"><u>[Updated] ASMR's Role in Better Nights  Expert Vocal Guides</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-captivate-crowds-mastering-hashtag-use-in-high-traffic-short-videos/"><u>[Updated] In 2024, Captivate Crowds  Mastering Hashtag Use in High-Traffic Short Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-redefining-visual-storytelling-adding-and-altering-twitter-video-thumbnails/"><u>[Updated] Redefining Visual Storytelling  Adding and Altering Twitter Video Thumbnails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/0x80073712-error-code-in-windows-11-solved/"><u>0X80073712 Error Code in Windows 11 [SOLVED]</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unveil-the-finest-vr-cycling-worlds/"><u>2024 Approved  Unveil the Finest VR Cycling Worlds</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>8 Solutions to Fix Find My Friends Location Not Available On Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-step-by-step-guide-resolving-issues-with-your-stylus-on-xperia-devices/"><u>Complete Step-by-Step Guide: Resolving Issues with Your Stylus on Xperia Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/deciphering-the-hurdles-in-teredos-network-connection-process/"><u>Deciphering the Hurdles in Teredo's Network Connection Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-windows-error-the-case-of-the-d3dxx32dll-that-wont-load/"><u>Easy Fixes for Windows Error - The Case of the d3dxx_32.dll That Won't Load</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-realme-11-5g-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Realme 11 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workspace-drawing-on-windows-desktop/"><u>Elevate Your Workspace: Drawing on Windows Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-restoring-functionality-to-a-broken-lenovo-f-key-with-ease/"><u>Expert Advice: Restoring Functionality to a Broken Lenovo F-Key with Ease</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1723807875667-find-out-what-motherboard-you-have-easily/"><u>Find Out What Motherboard You Have Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-back-your-racetrack-roar-expert-solutions-for-restoring-sounds-in-forza-horizon-4/"><u>Get Back Your Racetrack Roar: Expert Solutions for Restoring Sounds in Forza Horizon 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208360473-get-your-youtube-sound-back-addressing-and-repairing-audio-renderer-errors-in-windows-1nvite-the-audio-troubleshooting-community-with-expert-tips/"><u>Get Your YouTube Sound Back: Addressing and Repairing Audio Renderer Errors in Windows 1Nvite the Audio Troubleshooting Community with Expert Tips.</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-samsung-galaxy-a15-5g-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Samsung Galaxy A15 5G Phone | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-unresponsive-windows-11-after-turning-it-on-a-comprehensive-guide/"><u>How to Address Unresponsive Windows 11 After Turning It On - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-enable-detecting-bluetooth-gadgets-on-your-windows-update/"><u>How to Enable Detecting Bluetooth Gadgets on Your Windows # Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-print-to-pdf-not-working-in-windows-1011-by-microsoft/"><u>How to Fix 'Print to PDF Not Working' In Windows 10/11 by Microsoft</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-windows-10-not-booting-due-to-recent-updates/"><u>How to Overcome Windows 10 Not Booting Due to Recent Updates</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-flashlight-from-apple-iphone-8-plus-lock-screen-drfone-by-drfone-ios/"><u>How To Remove Flashlight From Apple iPhone 8 Plus Lock Screen | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-elevated-permission-error-in-windows-11-10-and-7/"><u>How to Resolve the 'Elevated Permission' Error in Windows 11, 10 and 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-connectivity-with-destiny-2-servers-when-theyre-down/"><u>How to Restore Connectivity with Destiny 2 Servers When They're Down</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-unlocked-apple-iphone-15-plus-by-drfone-ios/"><u>In 2024, Everything You Need To Know About Unlocked Apple iPhone 15 Plus</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-revitalize-your-shots-10-cost-free-expandable-with-additional-luts/"><u>In 2024, Revitalize Your Shots  10 Cost-Free, Expandable With Additional LUTs</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/is-the-investment-in-m3-macbook-air-rewarding/"><u>Is the Investment in M3 MacBook Air Rewarding?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/out-of-sight-not-out-of-reach-bringing-offscreen-windows-back-into-view/"><u>Out of Sight, Not Out of Reach: Bringing Offscreen Windows Back Into View</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-hurdle-of-the-troublesome-windows-error-understanding-and-fixing-0x8000ffff/"><u>Overcoming the Hurdle of the Troublesome Windows Error: Understanding and Fixing 0X8000FFFF</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-building-errors-resolved-load-up-without-interruption/"><u>PUBG Building Errors Resolved: Load Up Without Interruption</u></a></li>
<li><a href="https://win-howtos.techidaily.com/red-screen-resolved-step-by-step-fix-for-common-software-glitches/"><u>Red Screen Resolved: Step-by-Step Fix for Common Software Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-windows-11-update-error-0xc1900208-step-by-step-tutorial/"><u>Resolve Your Windows 11 Update Error (0xC1900208) - Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-problem-setting-up-a-virtual-router-on-windows-11-guide/"><u>Resolved Problem: Setting Up a Virtual Router on Windows 11 (Guide)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-fix-a-persistent-laptop-displaying-only-a-white-screen/"><u>Resolved: How to Fix a Persistent Laptop Displaying Only a White Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-rpc-server-unreachable-issue-on-your-windows-pc/"><u>Resolving the 'RPC Server Unreachable' Issue on Your Windows PC</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/reveal-the-disenchanted-instagrams-unfollowers-for-2024/"><u>Reveal the Disenchanted  Instagram's Unfollowers for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/shadowy-sheen-visual-puzzle/"><u>Shadowy Sheen: Visual Puzzle</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-windows-11-surveillance-measures/"><u>Sidestep Windows 11 Surveillance Measures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-auto-boot-puzzle-for-windows-10-systems/"><u>Solving the Auto-Boot Puzzle for Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-on-overcoming-geforce-experience-launch-failures/"><u>Step-by-Step Tutorial on Overcoming GeForce Experience Launch Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-lost-sound-devices-in-windows-1011-expert-fixes/"><u>Troubleshooting Lost Sound Devices in Windows 10/11 - Expert Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-solving-common-oculus-hardware-issues/"><u>Troubleshooting Tips: Solving Common Oculus Hardware Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-10-updates-solutions-for-when-installation-freezes/"><u>Troubleshooting Windows 10 Updates: Solutions for When Installation Freezes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unsticking-your-video-tiktoks-guide/"><u>Unsticking Your Video  TikTok's Guide</u></a></li>
</ul></div>
