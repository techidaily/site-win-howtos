---
title: Overcoming the Obstacle of Windows Update Error Code 0X80070490 with Ease
date: 2024-08-15T11:38:19.454Z
updated: 2024-08-16T11:38:19.454Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Overcoming the Obstacle of Windows Update Error Code 0X80070490 with Ease
excerpt: This Article Describes Overcoming the Obstacle of Windows Update Error Code 0X80070490 with Ease
thumbnail: https://thmb.techidaily.com/dd1b377f0a177d81939c2e9879a9449aa15d2816c9d71de8279c052980247986.jpg
---

## Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside

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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

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

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
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

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
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
<li><a href="https://extra-skills.techidaily.com/new-seamless-manipulation-of-iphone-magnification/"><u>[New] Seamless Manipulation of iPhone Magnification</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-best-no-cost-cross-platform-laptop-dvd-decoders/"><u>[Updated] Best No-Cost, Cross-Platform Laptop DVD Decoders</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-clashing-kings-the-top-battle-royale-games-for-2024/"><u>[Updated] Clashing Kings  The Top Battle Royale Games for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/answered-troubleshooting-directx-device-instantiation-mishap/"><u>Answered: Troubleshooting DirectX Device Instantiation Mishap</u></a></li>
<li><a href="https://fox-helps.techidaily.com/beginners-overview-of-animation-trends/"><u>Beginner's Overview of Animation Trends</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-open-chrome-try-these-win11-solutions-now/"><u>Can't Open Chrome? Try These Win11 Solutions Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-to-fix-your-stuck-touchpad-scroll-wheel/"><u>Comprehensive Solutions to Fix Your Stuck Touchpad Scroll Wheel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-walkthrough-to-correct-file-path-not-found-in-windows/"><u>Comprehensive Walkthrough to Correct 'File Path Not Found' In Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-elevated-cpu-load-from-windows-update-host-wu-dll-in-windows-11/"><u>Diagnosing and Repairing Elevated CPU Load From Windows Update Host (Wu-Dll) in Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-on-apple-iphone-6-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud on Apple iPhone 6 Safe and Legal</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-solutions-for-wacom-tablet-connectivity-and-functionality-issues/"><u>Essential Solutions for Wacom Tablet Connectivity and Functionality Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-window-10-sluggish-shutdown-problems-simple-solutions/"><u>Fix Your Window 10 Sluggish Shutdown Problems - Simple Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-endless-loop-windows-update-stuck-on-100-percent-solution-inside/"><u>Fixing the Endless Loop: Windows Update Stuck on 100 Percent - Solution Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-frozen-prepare-to-configure-phase-on-your-windows-device-now-resolved/"><u>Fixing the Frozen Prepare-to-Configure Phase on Your Windows Device - Now Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/geforce-experience-wont-open-issue-solved/"><u>GeForce Experience Won't Open Issue [Solved]</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-lock-apps-on-honor-x9a-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Honor X9a to Protect Your Individual Information</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-nokia-c300-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Nokia C300 FRP In 3 Different Ways</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/instagram-growth-hacks-how-to-gain-a-massive-follower-base/"><u>Instagram Growth Hacks: How to Gain a Massive Follower Base</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207956611-laptop-microphone-not-working-heres-how-to-fix-it-right-now/"><u>Laptop Microphone Not Working? Here's How to Fix It Right Now</u></a></li>
<li><a href="https://screen-capture.techidaily.com/mastery-in-video-creation-using-captivate-software/"><u>Mastery in Video Creation Using Captivate Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-usb-dropout-effective-strategies-for-stable-connectivity-fixes/"><u>Overcoming USB Dropout: Effective Strategies for Stable Connectivity Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restoring-mouse-pointer-visibility-issues-on-windows-11-expert-fixes/"><u>Restoring Mouse Pointer Visibility Issues on Windows 11: Expert Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-the-popping-resolving-crackle-sound-problems-in-windows-operating-systems/"><u>Stop the Popping: Resolving Crackle Sound Problems in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-obs-screenshots-and-captures-the-ultimate-fix-for-black-image-dilemmas/"><u>Tackling OBS Screenshots and Captures - The Ultimate Fix for Black Image Dilemmas</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-connoisseurs-guide-to-youtube-music-orchestration-for-2024/"><u>The Connoisseur's Guide to YouTube Music Orchestration for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-right-click-issues-on-a-mouse-with-windows-11/"><u>Troubleshooting Guide: Fixing Right-Click Issues on a Mouse with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-functional-function-key-issues-on-your-asus-laptop/"><u>Troubleshooting Non-Functional Function Key Issues on Your ASUS Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-dealing-with-unresponsive-numeric-keys/"><u>Troubleshooting Tips: Dealing with Unresponsive Numeric Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-unsupported-device-inputs-monitor-compatibility-solutions/"><u>Troubleshooting Unsupported Device Inputs – Monitor Compatibility Solutions</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-oneplus-nord-ce-3-5g-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your OnePlus Nord CE 3 5G Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-teredo-did-not-make-the-cut-a-comprehensive-breakdown/"><u>Why Teredo Did Not Make the Cut: A Comprehensive Breakdown</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-user-guide-fixing-hosted-wi-fi-connection-startup-failures/"><u>Windows 10 User Guide: Fixing Hosted Wi-Fi Connection Startup Failures</u></a></li>
<li><a href="https://hardware-help.techidaily.com/windows-7-sound-driver-download-improve-your-pcs-audio-experience/"><u>Windows 7 Sound Driver Download: Improve Your PC's Audio Experience</u></a></li>
</ul></div>
