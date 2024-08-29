---
title: "Mastering Precision with Excel's TRUNCATE Feature: A Step-by-Step Guide"
date: 2024-08-28T00:19:24.946Z
updated: 2024-08-29T00:19:24.946Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/56c09995c4310ae28019d3390616d9116d70341b815aee65c7667ed39de0e4c8.jpg
---

## Mastering Precision with Excel's TRUNCATE Feature: A Step-by-Step Guide

### Quick Links

* [What Is the TRUNC Function?](https://extra-resources.techidaily.com/systematic-upgrade-procedures-for-macos-sierra-users/)
* [How to Use the TRUNC Function](https://data-wizards.techidaily.com/immediate-fix-to-freezing-problem-in-vlc/)
* [Remove the Time from a Date-Time Stamp](https://fox-direct.techidaily.com/exploring-interconnected-digital-universes-meta-and-omni-for-2024/)
* [Use TRUNC to Shorten Numbers](https://fox-info.techidaily.com/updated-the-ultimate-strategy-for-posting-srt-content-socially/)

 There are a variety of ways in Excel to remove decimal points and shortening number values. In this article, we explain how to use the TRUNC function and what makes it different from other techniques.

##  What Is the TRUNC Function?

 The TRUNC function truncates a number to a specified number of decimal places. The key factor that makes TRUNC different from other functions that remove decimal places is that the TRUNC function does not round values. If you use TRUNC to remove all the decimals from the value 4.68, the result is 4.

 The TRUNC function requires two pieces of information:

=TRUNC(number, [digits])

 The number is the value you want to truncate. Digits are the number of numerals you want to truncate the value to. The digits portion is optional, and if not answered, TRUNC will remove all decimal places.

##  How to Use the TRUNC Function

 Let's look at examples of the TRUNC function with some sample data. The below example uses the following TRUNC function.

=TRUNC(A2)

 If you do not specify how many digits to truncate, all decimal places will be removed.

![First TRUNC function example](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/first-example.png) 

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can see with the value in cell A2 that the TRUNC function does not apply any rounding. It simply truncates the number to 411.

 Let's see another example. This time we will reduce the values to two decimal places.

=TRUNC(A2,2)

![TRUNC function to two decimal places](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/two-decimal-places.png) 

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
 The TRUNC function will not display extra decimals if you ask it to show more than you have.

 Take the following example, and let's truncate it to two decimal places.

=TRUNC(A2,2)

![No extra decimals shown by TRUNC](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/no-extra-decimals.png) 

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The value in cell A4 is reduced to two decimal places, but the values in A2 and A3 stay as they are because they have less than two decimal places already.

 If you want to display the two decimals, the cells will need to be formatted to be forced to show them.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
##  Remove the Time from a Date-Time Stamp

 A useful example of TRUNC is to remove the time from a date and time stamp in Excel.

 Imagine having the following date and time stamps, but we just want the date in a column for analysis.

![Date and time sample data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/date-and-time-data.png) 

 The following formula will work to remove the time.

=TRUNC(A2)

![Time removed from a date in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/time-removed.png) 

 Although the time is removed, the resulting cells will still need to be formatted as a date only.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
##  Use TRUNC to Shorten Numbers

 This is a rare technique, but it is worth knowing that the TRUNC function will also accept negative numbers for the digits argument. When you use a negative number, the formula truncates the numbers to the left of the decimal point. However, it does not change the number of digits. It will replace them with zeroes.

 Let's look at the following example.

=TRUNC(A2,-1)

![Entering minus digits for the second argument](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/minus-digits.png) 

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can see in each example that zero was used to replace the number that was removed from the left of the decimal point.

---

 There are multiple ways in Excel to remove decimal places, however, most of these will apply a rounding of some nature. The strength of the TRUNC function is that it does not round values and simply shortens them to the specified decimal place amount.

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
<li><a href="https://screen-video-capture.techidaily.com/new-discover-the-10-leading-no-cost-webcalls-for-businesses/"><u>[New] Discover the 10 Leading No-Cost Webcalls for Businesses</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-full-exploration-of-googles-voice-to-text-speech-recognition-tool-for-2024/"><u>[New] Full Exploration of Google's Voice-to-Text Speech Recognition Tool for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-geforce-experience-unable-to-retrieve-settings/"><u>[SOLVED] GeForce Experience Unable to Retrieve Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-screen-flickering-in-windows-10/"><u>[Solved] Screen Flickering in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-unreal-engine-is-exiting-due-to-d3d-device-being-lost/"><u>[Solved] Unreal Engine Is Exiting Due to D3D Device Being Lost</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-dive-into-fb-360-videos-recording-and-sharing-secrets/"><u>[Updated] 2024 Approved  Dive Into FB 360 Videos  Recording and Sharing Secrets</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-enablingdisabling-youtube-video-comments/"><u>[Updated] 2024 Approved  Enabling/Disabling YouTube Video Comments</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-screenshoting-made-easy-leveraging-ezvid-video-maker/"><u>[Updated] 2024 Approved  Screenshoting Made Easy  Leveraging Ezvid Video Maker</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-24-revolutionary-metaverse-concepts-explored-diligently/"><u>[Updated] 24 Revolutionary Metaverse Concepts Explored Diligently</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-discover-and-make-the-fb-most-watched-song-videos-for-2024/"><u>[Updated] Discover & Make the #FB Most-Watched Song Videos for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-steps-for-unlocking-stuck-obs-fullscreen-mode-for-2024/"><u>[Updated] Steps for Unlocking Stuck OBS Fullscreen Mode for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-top-picks-for-cutting-edge-websites-of-text-styling-tools/"><u>[Updated] Top Picks for Cutting-Edge Websites of Text Styling Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/backspace-button-malfunction-solutions-and-remedies-explored/"><u>Backspace Button Malfunction - Solutions and Remedies Explored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-to-restore-functionality-of-your-broken-dell-laptop-keys/"><u>Comprehensive Guide to Restore Functionality of Your Broken Dell Laptop Keys</u></a></li>
<li><a href="https://extra-hints.techidaily.com/cutting-edge-or-just-another-app-discover-vida-inside-out/"><u>Cutting Edge or Just Another App? Discover Vida Inside Out</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-87-fixing-the-parameter-is-incorrect-in-loadlibrary-issues/"><u>Error Code 87: Fixing 'The Parameter Is Incorrect' In LoadLibrary Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-fixes-for-unexpected-system-restarts-in-windows-10/"><u>Expert Fixes for Unexpected System Restarts in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-get-your-keyboards-light-turned-on-again-in-mac-oswindows/"><u>Expert Tips to Get Your Keyboard's Light Turned On Again in Mac OS/Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206059037-fast-track-to-fixing-error-code-0x887a0006-a-speedier-solution-guide/"><u>Fast Track to Fixing Error Code 0X887A0006 – A Speedier Solution Guide!</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-zte-axon-40-lite-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on ZTE Axon 40 Lite Quickly | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-laptops-non-charging-battery-issues-simple-solutions-inside/"><u>Fix Your Laptop's Non-Charging Battery Issues - Simple Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-frame-drops-and-lag-in-fallout-2022-resolutions/"><u>Fixing Frame Drops and Lag in Fallout ([2022 Resolutions])</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-back-online-expert-advice-on-fixing-service-stopped-errors-in-hamachi/"><u>Get Back Online: Expert Advice on Fixing 'Service Stopped' Errors in Hamachi</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-samsung-galaxy-z-fold-5-frp-by-drfone-android/"><u>How Can We Bypass Samsung Galaxy Z Fold 5 FRP?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-itel-a60s-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Itel A60s to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unable-to-start-program-error-code-0xc000007b/"><u>How to Fix 'Unable to Start Program' Error Code 0xC000007B</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unresponsive-usb-connectivity-issues-in-windows-11-devices/"><u>How to Fix Unresponsive USB Connectivity Issues in Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-microsoft-wireless-display-adapter-up-and-running-on-windows-10-problem-solved/"><u>How to Get Your Microsoft Wireless Display Adapter Up and Running on Windows 10 (Problem Solved)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-solve-the-there-was-an-issue-when-restoring-your-pc-error-in-windows-11/"><u>How to Solve the There Was an Issue When Restoring Your PC Error in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-not-working-heres-how-to-restore-full-functionality/"><u>Keyboard Not Working? Here's How to Restore Full Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204633189-lenovo-fingerprint-recognition-woes-heres-how-you-can-fix-it-without-a-hitch/"><u>Lenovo Fingerprint Recognition Woes? Here’s How You Can Fix It Without a Hitch</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-more-crashes-in-nier-automata-on-windows-comprehensive-solutions/"><u>No More Crashes in Nier: Automata on Windows - Comprehensive Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-touchpad-trouble-expert-tips-to-restore-functionality-on-your-pc/"><u>Overcoming Touchpad Trouble: Expert Tips to Restore Functionality on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-slow-shutdown-woes-on-windows-10-devices/"><u>Quick Fixes for Slow Shutdown Woes on Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-steps-for-fixing-your-windows-update-hang-on-0-barrier/"><u>Simple Steps for Fixing Your Windows' Update Hang on 0%% Barrier</u></a></li>
<li><a href="https://win-howtos.techidaily.com/small-cell-lung-cancer-sclc-is-highly-aggressive-with-rapid-growth-rates-and-early-metastasis/"><u>Small Cell Lung Cancer (SCLC) Is Highly Aggressive, with Rapid Growth Rates and Early Metastasis.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-laptops-touchpad-problems-in-windows-11-8-and-7/"><u>Solving Your Laptop's Touchpad Problems in Windows 11, 8 and 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-the-rpc-server-accessibility-error-in-windows/"><u>Step-by-Step Guide: Correcting the RPC Server Accessibility Error in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-your-touchscreen-in-windows-10-discover-how-to-fix-it-using-5-different-approaches/"><u>Trouble with Your Touchscreen in Windows 10? Discover How to Fix It Using 5 Different Approaches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202609749-trouble-with-your-windows-11-taskbar-easy-fixes-to-restore-functionality-now/"><u>Trouble with Your Windows 11 Taskbar? Easy Fixes to Restore Functionality Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solutions-for-winodws-10s-persistent-0x800705b4-update-problem-resolved/"><u>Troubleshooting & Solutions for Winodws 10'S Persistent 0X800705b4 Update Problem [Resolved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-right-click-issues-on-windows-11-a-step-by-step-guide/"><u>Troubleshooting Right-Click Issues on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-fix-destiny-2-wont-initialize-issue/"><u>Troubleshooting: How to Fix 'Destiny 2 Won't Initialize' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-11-volume-troubleshooting-guide-get-your-sounds-back-today/"><u>Win 11 Volume Troubleshooting Guide - Get Your Sounds Back Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-camera-malfunction-overcome-error-code-0xa00f4292-with-these-simple-fixes/"><u>Windows Camera Malfunction? Overcome Error Code 0XA00F4292 with These Simple Fixes</u></a></li>
</ul></div>
