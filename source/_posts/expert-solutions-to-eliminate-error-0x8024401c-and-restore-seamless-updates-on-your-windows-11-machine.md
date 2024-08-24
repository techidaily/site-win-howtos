---
title: Expert Solutions to Eliminate Error 0X8024401c & Restore Seamless Updates on Your Windows 11 Machine
date: 2024-08-23T14:09:53.991Z
updated: 2024-08-24T14:09:53.991Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Solutions to Eliminate Error 0X8024401c & Restore Seamless Updates on Your Windows 11 Machine
excerpt: This Article Describes Expert Solutions to Eliminate Error 0X8024401c & Restore Seamless Updates on Your Windows 11 Machine
thumbnail: https://thmb.techidaily.com/3ca289f4707af5e0ebcc0fe8b2f301906af8c014f3bb06033bb1a4fefba543ee.jpg
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

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

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
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-become-a-pro-in-calculating-youtube-ratio-measures-for-2024/"><u>[New] Become a Pro in Calculating YouTube Ratio Measures for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-critical-analysis-leading-screencast-applications-of-today/"><u>[New] In 2024, Critical Analysis  Leading Screencast Applications of Today</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-mastering-snapchat-boomerangs-ultimate-instructions/"><u>[New] In 2024, Mastering Snapchat Boomerangs  Ultimate Instructions</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-5-must-know-strategies-for-effective-team-video-calls/"><u>[Updated] 5 Must-Know Strategies for Effective Team Video Calls</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-finding-the-best-replacement-for-magixs-acid-pro/"><u>2024 Approved  Finding the Best Replacement for Magix's ACID Pro</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-fundamentals-of-color-grading-using-luts-in-ae/"><u>2024 Approved  The Fundamentals of Color Grading Using LUTs in AE</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/advanced-text-tools-and-ae-plug-ins/"><u>Advanced Text Tools & AE Plug-Ins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-cpu-and-gpu-for-smooth-online-engagement/"><u>Balancing CPU and GPU for Smooth Online Engagement</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-plugin-sync-troubles-how-to-overcome-connection-errors/"><u>ChatGPT Plugin Sync Troubles: How to Overcome Connection Errors</u></a></li>
<li><a href="https://article-posts.techidaily.com/crafting-engaging-storytelling-podcasts-with-applee-devices-for-2024/"><u>Crafting Engaging Storytelling Podcasts with Apple'e Devices for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-fixes-restoring-functionality-to-a-broken-dell-wireless-keyboard/"><u>DIY Fixes: Restoring Functionality to a Broken Dell Wireless Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-troubleshooting-guide-for-dealing-with-fn-key-issues-in-your-dell-laptop/"><u>DIY Troubleshooting Guide for Dealing with FN-Key Issues in Your Dell Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-the-persistent-windows-10-failed-to-download-updates-problem-error-code-0xc1900208/"><u>Effective Fixes for the Persistent 'Windows 10 Failed to Download Updates' Problem (Error Code 0Xc1900208)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/effective-strategies-for-verifying-health-advice-from-chatgpt-and-artificial-intelligence/"><u>Effective Strategies for Verifying Health Advice From ChatGPT and Artificial Intelligence</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-failed-windows-updates-on-your-computer/"><u>Expert Tips For Repairing Failed Windows Updates On Your Computer</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-claude-2-its-essence-and-uses/"><u>Exploring Claude 2: Its Essence & Uses</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-xiaomi-redmi-a2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-restore-keyboard-letters-that-arent-responding-in-windows-10-and-11/"><u>Guide to Restore Keyboard Letters That Aren't Responding in Windows 10 & 11</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-nokia-xr21-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Nokia XR21 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-elevated-cpu-use-by-svchost-process-in-windows-10/"><u>How to Fix Elevated CPU Use by Svchost Process in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-gain-authorization-from-trustedinstaller-for-changing-protected-files/"><u>How to Gain Authorization From TrustedInstaller for Changing Protected Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-mic-functionality-on-your-steelseries-arctis-5-headset-easy-fix-tips-for-gamers/"><u>How to Restore Mic Functionality on Your SteelSeries Arctis 5 Headset - Easy Fix Tips for Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-power-off-your-pc-running-windows-11-solutions-explored/"><u>How to Successfully Power Off Your PC Running Windows 11: Solutions Explored</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-exquisite-selection-idle-games-with-infinite-play/"><u>In 2024, Exquisite Selection  Idle Games with Infinite Play</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-windows-update-error-8007000e-simple-steps/"><u>Quick Fixes for Windows Update Error 8007000E – Simple Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reboot-anomalies-in-win10-environment/"><u>Reboot Anomalies in Win10 Environment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-kernel32dll-fails/"><u>Resolving Kernel32.dll Fails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-eliminating-slow-response-times-from-your-windows-11-keyboard/"><u>Solution Found: Eliminating Slow Response Times From Your Windows 11 Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-resolving-windows-update-issue-error-0x80240017/"><u>Step-by-Step Solution for Resolving Windows Update Issue (Error 0X80240017)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-guide-to-gaining-complete-control-over-your-steam-installation/"><u>The Ultimate Guide to Gaining Complete Control Over Your Steam Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-successfully-install-battleye-anti-cheat-now/"><u>Troubleshoot and Successfully Install BattlEye Anti-Cheat Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-solution-for-call-of-duty-world-war-ii-error-code-4220-issues/"><u>Ultimate Solution for Call of Duty World War II Error Code 4220 Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/updated-reactivate-the-local-user-account-verification-mechanism/"><u>Updated: Reactivate the Local User Account Verification Mechanism</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/xbox-one-audio-woes-discover-how-to-restore-headset-functionality-today/"><u>Xbox One Audio Woes? Discover How to Restore Headset Functionality Today</u></a></li>
</ul></div>
