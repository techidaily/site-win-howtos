---
title: "Overcoming the 'Windows Update Failed' Hurdle in Windows 11: Decoding Error 0X800705b4"
date: 2024-08-19T06:51:59.828Z
updated: 2024-08-20T06:51:59.828Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming the 'Windows Update Failed' Hurdle in Windows 11: Decoding Error 0X800705b4"
excerpt: "This Article Describes Overcoming the 'Windows Update Failed' Hurdle in Windows 11: Decoding Error 0X800705b4"
thumbnail: https://thmb.techidaily.com/0e4e69a266c0e21cfaa72121cb274553aaa959ab8154e71b42e7a2317f1338de.png
---

## Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
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

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-upgrading-your-playlists-for-seamless-integration-from-spotify-to-youtube-music/"><u>[New] 2024 Approved  Upgrading Your Playlists for Seamless Integration From Spotify to YouTube Music</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-examining-youtubes-mobile-app-for-iosandroid-devices-for-2024/"><u>[Updated] Examining YouTube's Mobile App for iOS/Android Devices for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-prime-8-instagram-managers-for-mobile-devices/"><u>[Updated] Prime 8 Instagram Managers for Mobile Devices</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-melodic-mastery-in-visual-storytelling/"><u>2024 Approved  Melodic Mastery in Visual Storytelling</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-frustration-of-continual-windows-11-reinstalls-with-simple-solutions/"><u>Bypassing the Frustration of Continual Windows 11 Reinstalls with Simple Solutions</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/converting-youtube-videos-into-engaging-gifs-on-devices/"><u>Converting YouTube Videos Into Engaging GIFs on Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/crt-dll-absence-on-system/"><u>CRT DLL Absence on System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-damaged-windows-store-caches-heres-your-guide-to-success/"><u>Dealing with Damaged Windows Store Caches? Here's Your Guide to Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dhcp-connectivity-problems-understanding-and-solving-the-issue/"><u>DHCP Connectivity Problems – Understanding and Solving the Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-a-broken-fingerprint-recognition-system-on-lenovo-devices/"><u>Diagnosing and Fixing a Broken Fingerprint Recognition System on Lenovo Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-fixes-to-correct-driverpowerstatefailure-issues-on-your-pc/"><u>DIY Fixes to Correct DRIVER_POWER_STATE_FAILURE Issues on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-when-your-playstation-4-mic-stops-working-a-step-by-step-solution/"><u>Effective Fixes for When Your PlayStation 4 Mic Stops Working: A Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-repair-techniques-for-a-non-functional-lenovo-fingerprint-reader/"><u>Effortless Repair Techniques for a Non-Functional Lenovo Fingerprint Reader</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-5-in-minecraft-easy-fixes-for-a-smooth-gaming-experience/"><u>Error Code 5 in Minecraft: Easy Fixes for a Smooth Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolution-overcoming-the-0x887a0006-issue-with-simple-steps/"><u>Error Resolution - Overcoming the 0X887A0006 Issue with Simple Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-implemented-for-print-driver-host-stopped-working-on-32-bit-systems-seamless-printing-restored/"><u>Fix Implemented for 'Print Driver Host Stopped Working' On 32-Bit Systems – Seamless Printing Restored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-laptop-trackball-issues-on-windows-10-8-and-7-solutions-revealed/"><u>Fix Laptop Trackball Issues on Windows 10, 8 & 7 – Solutions Revealed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-failed-feature-installation-on-windows-10-version-1607/"><u>Fixing Failed Feature Installation on Windows 10 Version 1607</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-mysterious-error-1067-when-your-windows-app-crashes-without-warning/"><u>Fixing the Mysterious 'Error 1067' – When Your Windows App Crashes Without Warning</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-11-couldnt-be-installed-error-80240020-expert-solutions-revealed/"><u>How To Fix 'Windows 11 Couldn't Be Installed Error 80240020 - Expert Solutions Revealed</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-corrupt-video-files-of-xiaomi-civi-3-disney-100th-anniversary-edition-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Fix corrupt video files of Xiaomi Civi 3 Disney 100th Anniversary Edition using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unplayable-dvd-issues-on-your-windows-device/"><u>How to Fix Unplayable DVD Issues on Your Windows Device</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-7-to-other-iphone-14-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 7 to other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-laptop-webcam-woes-master-the-art-of-fixing-it-with-our-proven-methods/"><u>Lenovo Laptop Webcam Woes? Master the Art of Fixing It with Our Proven Methods</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/live-recording-mastery-with-innovative-webcams-explored/"><u>Live Recording Mastery with Innovative WebCams Explored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-accurate-typing-remedying-the-issue-of-miskeyed-letters/"><u>Mastering Accurate Typing: Remedying the Issue of Miskeyed Letters</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-device-not-supported-miracast-setup-tips/"><u>Overcoming 'Device Not Supported' - Miracast Setup Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-error-0x8024002e-your-ultimate-guide-to-updating-windows-successfully-fixed/"><u>Overcoming Error 0X8024002e: Your Ultimate Guide to Updating Windows Successfully [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-problem-of-windows-10-prolonged-shutdown-periods/"><u>Overcoming the Problem of Windows 10 Prolonged Shutdown Periods</u></a></li>
<li><a href="https://screen-recording.techidaily.com/perfecting-your-technique-a-vr-recordists-manual/"><u>Perfecting Your Technique  A VR Recordist's Manual</u></a></li>
<li><a href="https://extra-support.techidaily.com/pinnacle-of-intellect-trivia-videos-for-2024/"><u>Pinnacle of Intellect Trivia Videos for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repair-tips-making-your-windows-11-touchscreen-work-like-new-5-ways/"><u>Repair Tips: Making Your Windows 11 Touchscreen Work Like New (5 Ways)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-this-device-is-unavailable-error-code-24-on-windows-1087/"><u>Resolved: Fixing 'This Device Is Unavailable' Error Code 24 on Windows 10/8/7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-reviving-a-broken-lenovo-keyboard/"><u>Step-by-Step Guide: Reviving a Broken Lenovo Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-the-download-timed-out-problem/"><u>Step-by-Step Solution for the 'Download Timed Out' Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-tutorial-to-switch-on-bluetooth-for-windows-7-users/"><u>The Ultimate Tutorial to Switch On Bluetooth for Windows 7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-steam-disk-writing-problems-with-these-easy-fixes/"><u>Troubleshoot Steam Disk Writing Problems with These Easy Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-input-unsupported-errors-on-your-display-device/"><u>Troubleshooting 'Input Unsupported' Errors on Your Display Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-driver-failed-errors-in-user-setup-procedures/"><u>Troubleshooting and Fixing 'Driver Failed' Errors in User Setup Procedures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-astro-a40-microphone-issues-fixes-and-solutions/"><u>Troubleshooting Astro A40 Microphone Issues: Fixes and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-solving-windows-10-and-7-ethernet-connectivity-problems/"><u>Troubleshooting Guide: Solving Windows 10 & 7 Ethernet Connectivity Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-solving-your-integrated-webcam-issues-in-windows/"><u>Troubleshooting Steps: Solving Your Integrated Webcam Issues in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-windows-1011s-damaged-system-files/"><u>Ultimate Guide: Resolving Windows 10/11'S Damaged System Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unshackle-your-console-stop-freeze-issues-now/"><u>Unshackle Your Console: Stop Freeze Issues Now</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-vivo-y100a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Vivo Y100A | Dr.fone</u></a></li>
</ul></div>
