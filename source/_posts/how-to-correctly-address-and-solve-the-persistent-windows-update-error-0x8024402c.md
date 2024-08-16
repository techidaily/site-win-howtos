---
title: How to Correctly Address and Solve the Persistent Windows Update Error 0X8024402C
date: 2024-08-15T11:38:23.556Z
updated: 2024-08-16T11:38:23.556Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Correctly Address and Solve the Persistent Windows Update Error 0X8024402C
excerpt: This Article Describes How to Correctly Address and Solve the Persistent Windows Update Error 0X8024402C
thumbnail: https://thmb.techidaily.com/c67ae945d13a65a17a2d97a04bd087435fddfcab73758269188b74f1d1383195.jpg
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
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
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

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-gastronomy-goals-attractive-food-network-branding-ideas/"><u>[New] In 2024, Gastronomy Goals  Attractive Food Network Branding Ideas</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-make-stunning-tiktok-videos-using-these-templates/"><u>[New] In 2024, Make Stunning TikTok Videos Using These Templates</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-unlimited-screen-capture-tool/"><u>[New] In 2024, Unlimited Screen Capture Tool</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-podcast-perfection-editing-techniques-in-garageband/"><u>[New] Podcast Perfection  Editing Techniques in GarageBand</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-essential-media-makers-software-linux-edition/"><u>[Updated] 2024 Approved  Essential Media Makers' Software  Linux Edition</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-efficiently-downloading-youtube-sections-in-minutes/"><u>[Updated] In 2024, Efficiently Downloading YouTube Sections in Minutes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-engaging-viewers-with-ease-the-art-of-confidently-filming/"><u>[Updated] In 2024, Engaging Viewers with Ease  The Art of Confidently Filming</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-enhance-dji-flight-aesthetics-start-with-free-trial-lutts/"><u>[Updated] In 2024, Enhance DJI Flight Aesthetics – Start With Free Trial LUTTs</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-quick-twitterscape-snag-gifs-with-these-tips/"><u>2024 Approved  Quick Twitterscape  Snag Gifs with These Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/application-exe-crashes-solving-the-stopped-working-issue/"><u>Application Exe Crashes: Solving the 'Stopped Working' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211956051-destiny-nagged-on-boot-heres-the-solution/"><u>Destiny Nagged on Boot? Here's the Solution!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-auto-start-issues-in-windows-11-a-comprehensive-guide/"><u>Diagnosing Auto Start Issues in Windows 11 – A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-auto-start-problems-for-your-windows-10-device-a-comprehensive-guide/"><u>Diagnosing Auto-Start Problems for Your Windows 10 Device - A Comprehensive Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-asus-vg248qe-monitor-driver-updates-on-windows-simple-guide/"><u>Download and Install Asus VG248QE Monitor Driver Updates on Windows - Simple Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-to-restore-your-windows-groovy-11-taskbar-functionality-when-it-freezes/"><u>Effective Fixes to Restore Your Windows Groovy 11 Taskbar Functionality When It Freezes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-correcting-windows-defender-resource-errors-quickly/"><u>Expert Guide: Correcting Windows Defender Resource Errors Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-copy-and-paste-feature-failures-on-windows-11-systems/"><u>Expert Tips for Repairing 'Copy and Paste' Feature Failures on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/failed-attempt-to-install-windows-11s-feature-update-for-build-1607/"><u>Failed Attempt to Install Windows 11'S Feature Update for Build 1607</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-miracast-connectivity-problems-on-incompatible-graphic-cards-guide/"><u>Fixing Miracast Connectivity Problems on Incompatible Graphic Cards - Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-hosted-network-unable-to-start-issue-in-windows-11/"><u>How to Fix 'Hosted Network Unable to Start' Issue in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-no-playable-sources-found-error-in-windows-comprehensive-solution/"><u>How to Fix 'No Playable Sources Found' Error in Windows - Comprehensive Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-10-installation-issue-error-code-80240020/"><u>How to Fix Windows 10 Installation Issue - Error Code 80240020</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-of-a-broken-touchscreen-in-windows-10-five-solutions/"><u>How to Restore Functionality of a Broken Touchscreen in Windows 10 [Five Solutions]</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-11-pro-to-other-iphone-13-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 11 Pro to other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-building-your-screencasting-skills-from-the-ground-up/"><u>In 2024, Building Your Screencasting Skills From the Ground Up</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-the-art-of-monochrome-modification/"><u>Mastering the Art of Monochrome Modification</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-performance-reducing-wudfhostexes-impact-on-cpu-in-windows-11/"><u>Optimizing Performance: Reducing WUDFHost.exe's Impact on CPU in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-your-windows-10-update-hiccups-with-these-simple-solutions/"><u>Overcome Your Windows 10 Update Hiccups with These Simple Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-booting-problems-caused-by-recent-updates/"><u>Resolving Windows 11 Booting Problems Caused by Recent Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-the-problem-of-dead-keys-on-your-hp-computer-effective-solutions-await/"><u>Solve the Problem of Dead Keys on Your HP Computer – Effective Solutions Await</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-instructions-fixing-compromised-windows-os-components/"><u>Step-by-Step Instructions: Fixing Compromised Windows OS Components</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-rectify-kernel32-issues/"><u>Steps to Rectify Kernel32 Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-you-cant-reach-the-dhcp-server/"><u>Troubleshooting Steps When You Can't Reach the DHCP Server</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fix-for-wd-my-passport-ultra-undetected-by-pc-operating-system/"><u>Ultimate Fix for 'WD My Passport Ultra' Undetected by PC Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-repairing-the-32bit-applications-print-driver-host-has-stopped/"><u>Understanding and Repairing the 32Bit Application's 'Print Driver Host Has Stopped'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210426810-warframe-patch-trouble-heres-how-to-resolve-update-issues-successfully/"><u>Warframe Patch Trouble? Here's How to Resolve Update Issues Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-power-issues-solved-how-to-force-your-computer-to-turn-off/"><u>Windows 10 Power Issues Solved – How to Force Your Computer to Turn Off</u></a></li>
</ul></div>
