---
title: Definitive Guide to Overcome Stalled 100%% Progress in Windows Updates [FIXED]
date: 2024-08-23T14:01:30.277Z
updated: 2024-08-24T14:01:30.277Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Definitive Guide to Overcome Stalled 100%% Progress in Windows Updates [FIXED]
excerpt: This Article Describes Definitive Guide to Overcome Stalled 100%% Progress in Windows Updates [FIXED]
thumbnail: https://thmb.techidaily.com/dae0a2870112b9a4ab1d756c066c8118fc25545f432e94a76fa542274edb47a5.jpg
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
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

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-discovering-linuxs-top-screenshots-tools/"><u>[New] 2024 Approved  Discovering Linux's Top Screenshots Tools</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-eliminating-unrequested-podcast-episodes-on-spotify-app/"><u>[New] 2024 Approved  Eliminating Unrequested Podcast Episodes on Spotify App</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-expert-recommendations-high-quality-mac-video-grabber-tools/"><u>[New] Expert Recommendations  High-Quality Mac Video Grabber Tools</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-perfect-playback-overcoming-mutes-on-linkedin-video-posts/"><u>[New] In 2024, Perfect Playback  Overcoming Mutes on LinkedIn Video Posts</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-prime-psd-visual-enhancements/"><u>[New] Prime PSD Visual Enhancements</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-top-mac-frame-freezes-collection-limit-156-chars/"><u>[New] Top Mac Frame Freezes Collection (Limit  156 Chars)</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/alorant-screenshots-transformed-by-rapid-skilled-designers-for-2024/"><u>[New] Valorant Screenshots Transformed by Rapid, Skilled Designers for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-from-basic-snaps-to-spectacular-shots-snapchats-edits-for-everyone/"><u>[Updated] 2024 Approved  From Basic Snaps to Spectacular Shots  Snapchat's Edits for Everyone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-unlock-the-full-potential-with-these-top-6-music-videos-on-android/"><u>[Updated] 2024 Approved  Unlock the Full Potential with These Top 6 Music Videos on Android</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-beyond-views-and-likes-pursuing-profits-on-youtube/"><u>[Updated] Beyond Views and Likes  Pursuing Profits on YouTube</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-elevate-your-yt-marketing-essential-tips-for-higher-rankings/"><u>[Updated] In 2024, Elevate Your YT Marketing  Essential Tips for Higher Rankings</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-enhancing-gameplay-with-switch-pro-a-compreran-guide-for-steam-gamers/"><u>[Updated] In 2024, Enhancing Gameplay with Switch Pro  A Compreran Guide for Steam Gamers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-the-ultimate-checklist-for-growing-youtube-subscribers/"><u>[Updated] In 2024, The Ultimate Checklist for Growing YouTube Subscribers</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-navigating-a-world-of-videos-made-easy-with-vidas-aid/"><u>2024 Approved  Navigating a World of Videos Made Easy with Vida's Aid</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-try-these-10-music-video-templates-to-make-your-work-easy/"><u>2024 Approved Try These 10 Music Video Templates To Make Your Work Easy</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/amd-ryzen-9-9950x-test-results-in-depth-blender-performance-analysis-across-different-thermal-design-power-configurations/"><u>AMD Ryzen 9 9950X Test Results: In-Depth Blender Performance Analysis Across Different Thermal Design Power Configurations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-resolution-of-system-resource-shortages-to-ensure-seamless-service-delivery/"><u>Complete Resolution of System Resource Shortages to Ensure Seamless Service Delivery</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comprehensive-kinetics-study-2023/"><u>Comprehensive Kinetics Study 2023</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-troubleshooting-techniques-when-to-find-d3dx92e26dll/"><u>Comprehensive Troubleshooting Techniques: When to Find d3dx9_2e_26.dll</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211158318-eradicate-unwanted-on-screen-flashing-ultimate-fixes-for-a-steady-point/"><u>Eradicate Unwanted On-Screen Flashing: Ultimate Fixes for a Steady Point</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205707776-explain-how-problem-solving-skills-contribute-to-career-advancement-and-effective-teamwork-in-the-workplace/"><u>Explain How Problem-Solving Skills Contribute to Career Advancement and Effective Teamwork in the Workplace</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fast-track-your-download-speed-with-these-simple-fixes/"><u>Fast Track Your Download Speed with These Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-vcruntime140dll-error-and-launch-your-windows-11-apps-without-issues-solutions-inside/"><u>Fix VCRUNTIME140.dll Error & Launch Your Windows 11 Apps Without Issues – Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-and-repair-issues-with-an-inactive-lenovo-keyboard/"><u>How to Address and Repair Issues with an Inactive Lenovo Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unable-to-switch-to-desired-screen-size-error-easily/"><u>How to Fix 'Unable to Switch to Desired Screen Size' Error Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-installation-issues-error-code-0x80070643-on-windows-systems/"><u>How to Overcome Installation Issues (Error Code 0X80070643) on Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-a-non-responsive-chromecast-device/"><u>How to Troubleshoot a Non-Responsive Chromecast Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/huion-pen-not-responding-5-rapid-repair-techniques-for-artists/"><u>Huion Pen Not Responding? 5 Rapid Repair Techniques for Artists</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-restore-lost-watch-icon-on-facebook/"><u>In 2024, Restore Lost Watch Icon on Facebook</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-input-delay-no-more-a-guide-to-tackle-window-11-typing-lags/"><u>Keyboard Input Delay No More – A Guide to Tackle Window 11 Typing Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209460952-playstation-4-trouble-solve-the-mystery-of-error-code-ce-34878-0-today/"><u>PlayStation 4 Trouble? Solve the Mystery of Error Code CE-34878-0 Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-missing-bluetooth-in-windows-10-systems/"><u>Quick Fixes for Missing Bluetooth in Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-windows-11-bluetooth-not-detected-problem-fast-and-easy-step-by-step-guide/"><u>Resolve Your Windows 11 Bluetooth Not Detected Problem Fast and Easy - Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-class-registration-issues-in-windows-10-a-comprehensive-guide/"><u>Resolving Class Registration Issues in Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-repairing-corsair-keyboards-that-wont-work/"><u>Solution Guide: Repairing Corsair Keyboards That Won't Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-troubleshooting-minecrafts-opengl-issues/"><u>Step-by-Step Guide: Troubleshooting Minecraft's OpenGL Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-fix-windows-hello-not-supported-error-message-on-your-device-running-windows-10/"><u>Steps to Fix Windows Hello Not Supported Error Message on Your Device Running Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trim-wmis-firm-grip-on-cores/"><u>Trim WMI's Firm Grip on Cores</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-dns-server-issues-discover-4-simple-fixes/"><u>Troubleshooting DNS Server Issues: Discover 4 Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-change-rendering-api-dota-2-error-error-202-fast-solutions-inside/"><u>Troubleshooting the 'Change Rendering API' Dota 2 Error (Error 202^): Fast Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-dealing-with-a-non-functional-backspace-button/"><u>Troubleshooting Tips: Dealing with a Non-Functional Backspace Button</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-restore-your-windows-11-start-menu/"><u>Troubleshooting Tips: Restore Your Windows 11 Start Menu</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/us-celebration-spoken-in-many-tongues/"><u>U.S. Celebration Spoken in Many Tongues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-correcting-printer-error-code-30-for-seamless-printing-experience/"><u>Understanding and Correcting Printer Error Code -30 for Seamless Printing Experience</u></a></li>
<li><a href="https://hardware-help.techidaily.com/winning-the-fight-against-windows-10s-bluetooth-driver-glitches-solved/"><u>Winning the Fight Against Windows 10'S Bluetooth Driver Glitches [SOLVED]</u></a></li>
</ul></div>
