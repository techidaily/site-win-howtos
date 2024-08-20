---
title: How to Fix Windows Update Error 0X8024402c [Solved]
date: 2024-08-19T06:48:38.069Z
updated: 2024-08-20T06:48:38.069Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Windows Update Error 0X8024402c [Solved]
excerpt: This Article Describes How to Fix Windows Update Error 0X8024402c [Solved]
thumbnail: https://thmb.techidaily.com/8b607e0e604394629b363ae69329923c5b752c9a4c4af741aef58011df0d7554.jpg
---

## Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
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
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
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

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
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

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-accessing-your-curated-music-lists-on-youtube/"><u>[New] 2024 Approved  Accessing Your Curated Music Lists on Youtube</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-guide-to-set-up-zoom-meetings/"><u>[New] 2024 Approved  Guide to Set up Zoom Meetings</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-camsphere-exploration-what-else-can-we-see-for-2024/"><u>[New] CamSphere Exploration  What Else Can We See for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-crafting-cinema-magic-with-fcps-top-10-plugin-choices/"><u>[New] Crafting Cinema Magic with FCP’s Top 10 Plugin Choices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-effortless-visual-enhancement-auto-scaling-videos-for-mac-instagramers-for-2024/"><u>[New] Effortless Visual Enhancement  Auto-Scaling Videos for Mac Instagramers for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-humble-beginnings-jake-paul-on-youtube-triumph-for-2024/"><u>[New] From Humble Beginnings  Jake Paul on YouTube Triumph for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-optimize-social-media-visual-clarity-for-iphoneandroid-users/"><u>[New] In 2024, Optimize Social Media Visual Clarity for iPhone/Android Users</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-instagrams-backward-glimpse-reverse-video-tips/"><u>[New] Instagram's Backward Glimpse  Reverse Video Tips</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-laughter-and-tears-on-insta-the-ultimate-meme-page-list/"><u>[Updated] In 2024, Laughter & Tears on Insta  The Ultimate Meme Page List</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-step-by-step-manual-upside-down-movies-in-snap/"><u>[Updated] In 2024, Step-by-Step Manual  Upside Down Movies in Snap</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-connection-issues-how-to-restore-your-mouses-functionality-on-windows-pcs/"><u>Bluetooth Connection Issues? How to Restore Your Mouse's Functionality on Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-bugs-with-ease-quick-resolution-techniques-for-error-code-0x887a0006/"><u>Bypassing Bugs with Ease: Quick Resolution Techniques for Error Code 0X887A0006</u></a></li>
<li><a href="https://win-howtos.techidaily.com/call-of-duty-world-war-ii-error-4220-solutions-and-steps-to-correct-the-problem/"><u>Call of Duty World War II Error 4220: Solutions and Steps to Correct the Problem</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-in-the-classroom-unveiling-5-beneficial-ways-for-pupils/"><u>ChatGPT in the Classroom: Unveiling 5 Beneficial Ways for Pupils</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decode-windows-camera-errors-a-detailed-look-at-fixing-code-0xa00f4292/"><u>Decode Windows Camera Errors: A Detailed Look at Fixing Code 0xA00F4292</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-the-mystery-behind-failed-windows-update-downloads-restore-your-pcs-update-functionality/"><u>Decoding the Mystery Behind Failed Windows ^Update Downloads - Restore Your PC's Update Functionality!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-ways-to-fix-broken-usb-interface-on-windows-11-pcs/"><u>Effective Ways to Fix Broken USB Interface on Windows 11 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-encountered-heres-why-input-not-supported-messages-appear-on-displays/"><u>Error Encountered? Here's Why 'Input Not Supported' Messages Appear on Displays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-resolving-issues-with-a-malfunctioning-corsair-keyboard/"><u>Expert Guide: Resolving Issues with a Malfunctioning Corsair Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-and-preventing-windows-error-code-0x800704cf-from-recurring/"><u>Expert Tips for Fixing and Preventing Windows Error Code 0X800704CF From Recurring</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/exploring-the-amazfit-gtss-balance-of-chic-design-and-exercise-capability-reviews-and-findings/"><u>Exploring the Amazfit GTS's Balance of Chic Design and Exercise Capability - Reviews & Findings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-airpods-pairing-woes-in-windows-11-updated-strategies-for-smooth-audio-playback/"><u>Fix AirPods Pairing Woes in Windows 11 – Updated Strategies for Smooth Audio Playback</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-dhcp-communication-errors-why-your-device-cant-reach-the-server/"><u>Fixing DHCP Communication Errors: Why Your Device Can't Reach the Server</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-diagnose-and-solve-the-unknown-usb-device-detected-port-reset-issue-on-your-windows-11-pc/"><u>How to Diagnose and Solve the ‘Unknown USB Device Detected: Port Reset’ Issue on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-non-responsive-fn-key-issues-on-your-computer/"><u>How to Fix Non-Responsive Fn Key Issues on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212471643-how-to-locate-the-start-menu-in-windows-10-a-step-by-step-guide/"><u>How to Locate the Start Menu in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-crackling-sound-from-speakers-on-pc-windows-10-and-7/"><u>How To Resolve Crackling Sound From Speakers on PC (Windows 10 & 7)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-0x80n0541-windows-10-updating-issue-successfully/"><u>How to Resolve the 0X80n0541 Windows 10 Updating Issue Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-resolve-high-network-usage-by-svchostexe-netsvcs/"><u>How to Troubleshoot & Resolve High Network Usage by svchost.exe NETSVCS</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlink-your-iphone-se-from-your-apple-id-by-drfone-ios/"><u>How To Unlink Your iPhone SE From Your Apple ID</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-itel-s23-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Itel S23</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-on-your-apple-iphone-xs-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock On your Apple iPhone XS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-broken-arrow-key-issues-masterful-remedies-for-smooth-typing/"><u>Overcome Broken Arrow Key Issues: Masterful Remedies for Smooth Typing!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-steam-bootloader-hiccup-solutions-for-a-smooth-launcher-experience/"><u>Overcoming the Steam Bootloader Hiccup: Solutions for a Smooth Launcher Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-buying-windows-11-vcs/"><u>Pro Tips for Buying Windows 11 VCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-resolving-steams-disk-write-error/"><u>Quick Solutions for Resolving Steam's Disk Write Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-to-stop-endless-restarts-on-windows-11-systems/"><u>Quick Solutions to Stop Endless Restarts on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-connection-errors-overcoming-the-challenge-of-an-unreachable-dhcp-server/"><u>Resolving Connection Errors: Overcoming the Challenge of an Unreachable DHCP Server</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-infinite-load-issues-in-valorant-tips-and-tricks/"><u>Resolving Infinite Load Issues in Valorant - Tips and Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-of-vanishing-mouse-pointer-in-windows-11/"><u>Resolving the Issue of Vanishing Mouse Pointer in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-non-working-hp-laptop-keys-quick-solutions-at-hand/"><u>Reviving Non-Working HP Laptop Keys: Quick Solutions at Hand</u></a></li>
<li><a href="https://win-howtos.techidaily.com/security-features-reinstated-local-authorization-now-active/"><u>Security Features Reinstated – Local Authorization Now Active</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202776326-shift-key-issues-heres-how-you-can-get-it-working-again/"><u>Shift Key Issues? Here's How You Can Get It Working Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-safari-woes-instant-fixes-when-webpages-dont-load/"><u>Solve Your Safari Woes: Instant Fixes When Webpages Don't Load</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-issue-wolfenstein-ii-unable-to-generate-crash-report/"><u>Solved Issue: Wolfenstein II Unable To Generate Crash Report</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speaker-crackling-in-windows-107-solved/"><u>Speaker Crackling in Windows 10/7 [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-broken-dell-speaker-connections-and-performance/"><u>Step-by-Step Fixes for Broken Dell Speaker Connections and Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-eliminating-the-0xc0000098-error-in-windows-systems/"><u>Step-by-Step Guide: Eliminating the 0xC0000098 Error in Windows Systems</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-smudge-solution-blurring-visions-in-video-content/"><u>The Smudge Solution  Blurring Visions in Video Content</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-correcting-the-0x8024c01c-update-failure-on-windows-platforms/"><u>Troubleshooting Guide: Correcting the 0X802^4C01C Update Failure on Windows Platforms</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-the-net-framework-35-installation-hurdle-overcoming-error-code-0x800f081f/"><u>Troubleshooting Guide: Resolving the .NET Framework 3.5 Installation Hurdle - Overcoming Error Code 0X800F081F</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-hidden-usb-problems-how-to-repair-a-failure-in-device-descriptor-requests/"><u>Troubleshooting Hidden USB Problems: How to Repair a Failure in Device Descriptor Requests</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-right-click-issue-on-your-windows-11-mouse/"><u>Troubleshooting the Right-Click Issue on Your Windows 11 Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-restoring-hidden-or-missing-icons-on-windows-10/"><u>Troubleshooting Tips: Restoring Hidden or Missing Icons on Windows 10</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unboxing-the-propella-7s-40-a-budget-friendly-and-nimble-adventure-companion/"><u>Unboxing the Propella 7S 4.0: A Budget-Friendly and Nimble Adventure Companion</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208333454-unstick-your-windows-update-from-100-with-these-proven-fixes/"><u>Unstick Your Windows Update From 100%% with These Proven Fixes!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-refresh-and-reset-easily/"><u>Windows 10 Refresh & Reset Easily</u></a></li>
</ul></div>
