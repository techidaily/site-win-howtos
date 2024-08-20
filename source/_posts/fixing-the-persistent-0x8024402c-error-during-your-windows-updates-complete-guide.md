---
title: Fixing the Persistent 0X8024402C Error During Your Windows Updates - Complete Guide
date: 2024-08-19T06:54:52.341Z
updated: 2024-08-20T06:54:52.341Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing the Persistent 0X8024402C Error During Your Windows Updates - Complete Guide
excerpt: This Article Describes Fixing the Persistent 0X8024402C Error During Your Windows Updates - Complete Guide
thumbnail: https://thmb.techidaily.com/30c3f68025cf60445ca0af9503de0d05421151fac72dff09f39b3449e1fcd630.jpg
---

## Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-maximizing-memories-techniques-for-gameplay-recording/"><u>[New] 2024 Approved  Maximizing Memories  Techniques for Gameplay Recording</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-the-powerhouse-guide-to-screen-recording-with-tunefab/"><u>[New] In 2024, The Powerhouse Guide to Screen Recording with Tunefab</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-profit-potential-earning-from-your-youtube-mobile-subscribers/"><u>[New] Profit Potential  Earning From Your YouTube Mobile Subscribers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mobile-cinema-app-assessment-review/"><u>[Updated] Mobile Cinema App Assessment Review</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-streamline-your-vfx-creation-with-story-remix-and-windows-10-photos/"><u>[Updated] Streamline Your VFX Creation with Story Remix and Windows 10 Photos</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/23-key-metaverse-implementations-unveiling-future-prospects-for-2024/"><u>23 Key Metaverse Implementations Unveiling Future Prospects for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-step-by-step-solution-to-reactivating-a-printer-with-error-code-30/"><u>A Step-by-Step Solution to Reactivating a Printer with Error Code -30</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/audiovisual-synchronization-in-facebook-content-creation-for-2024/"><u>Audiovisual Synchronization in Facebook Content Creation for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beating-sims-4-does-not-launch-top-solutions-explored/"><u>Beating 'Sims 4 Does Not Launch': Top Solutions Explored</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-updated-drivers-optimize-your-rtx-2080-on-windows-1178/"><u>Download Updated Drivers: Optimize Your RTX 2080 on Windows 11/7/8</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-dead-lenovo-mousepads-a-cross-platform-win-11-8-and-nw-solution/"><u>Expert Tips for Fixing Dead Lenovo Mousepads: A Cross-Platform Win 11, 8 & Nw Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-user-profile-service-failed-to-sign-in-error-on-windows-pcs/"><u>Fixing the 'User Profile Service Failed to Sign In' Error on Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-frustrating-frozen-windows-update-showing-zero-progress-made-simple/"><u>Fixing the Frustrating Frozen Windows Update Showing Zero Progress Made Simple</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-sluggish-closure-solutions-to-your-windows-10-shutdown-woes/"><u>Fixing the Sluggish Closure: Solutions to Your Windows 10 Shutdown Woes</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/gif-revolution-free-transformation-of-tweets-to-gifs/"><u>Gif Revolution  Free Transformation of Tweets to GIFs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-rectifying-setup-problems-with-your-game-on-origin-platform/"><u>Guide to Rectifying Setup Problems with Your Game on Origin Platform</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hit-compliant-update-addressed-previous-missing-tap-response/"><u>HIT-Compliant Update: Addressed Previous Missing Tap Response</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-pictures-files-from-tecno-spark-go-2024-by-fonelab-android-recover-pictures/"><u>How To  Restore Missing Pictures Files from Tecno Spark Go (2024).</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-create-a-successful-live-stream/"><u>How to Create A Successful Live Stream</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgotten-the-voicemail-password-of-samsung-galaxy-s23-tactical-edition-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Samsung Galaxy S23 Tactical Edition? Try These Fixes</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-max-360-or-hero-11-a-comparative-look-at-gopro-cameras-footage/"><u>In 2024, Max 360 or Hero 11? A Comparative Look at GoPro Cameras' Footage</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-snapshot-surge-no-money-required-image-uplift/"><u>In 2024, Snapshot Surge  No Money Required Image Uplift</u></a></li>
<li><a href="https://win-howtos.techidaily.com/local-authority-shield-restored-fortifying-your-defense-layers/"><u>Local Authority Shield Restored - Fortifying Your Defense Layers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastery-in-unfreezing-windows-7-stuck-updates-latest-strategies-for-users-seeking-help-edition-expert-advice-and-tips/"><u>Mastery in Unfreezing Windows 7 Stuck Updates - Latest Strategies for Users Seeking Help Edition (Expert Advice & Tips)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210757311-netflix-not-working-diagnose-and-solve-common-streaming-problems-today/"><u>Netflix Not Working: Diagnose & Solve Common Streaming Problems Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-pcs-to-prevent-win10-cpu-spike/"><u>Optimizing PCs to Prevent Win10 CPU Spike</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-how-to-setup-and-use-bluetooth-devices-with-windows-7/"><u>Quick Fix: How To Setup and Use Bluetooth Devices With Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-dilemma-step-by-step-guide-to-overcoming-glexttexturecompression-level-compression-format-opengl-error-1281/"><u>Resolving the Dilemma: Step-by-Step Guide to Overcoming GL_EXT_texture_compression Level Compression Format OpenGL Error #1281</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-keyboard-delays-expert-troubleshooting-steps/"><u>Resolving Windows 11 Keyboard Delays - Expert Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-access-denied-to-device-pathfile-on-windows-troubleshooting-guide/"><u>Solve Access Denied to Device Path/File on Windows – Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-directx-d3d-creation-issues-a-step-by-step-tutorial/"><u>Solving DirectX D3D Creation Issues: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-windows-error-0xc0000098/"><u>Step-by-Step Guide: Resolving Windows Error 0xC0000098</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-nokia-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Nokia FRP</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-hidden-layer-capturing-chats-as-fb-media-files/"><u>The Hidden Layer  Capturing Chats as FB Media Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-continuous-shutdown-restart-cycles-for-windows-10-computers/"><u>Troubleshoot Continuous Shutdown-Restart Cycles for Windows 10 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-mouse-fixing-right-click-issues-on-windows-11/"><u>Troubleshooting the Mouse: Fixing Right-Click Issues on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-groovy-guide-resolve-registry-error-while-opening-pictures/"><u>Windows Groovy Guide: Resolve 'Registry Error' While Opening Pictures</u></a></li>
</ul></div>
