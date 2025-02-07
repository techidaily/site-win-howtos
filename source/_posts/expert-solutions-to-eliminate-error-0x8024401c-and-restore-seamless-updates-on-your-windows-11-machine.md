---
title: Expert Solutions to Eliminate Error 0X8024401c & Restore Seamless Updates on Your Windows 11 Machine
date: 2025-02-03T21:32:33.355Z
updated: 2025-02-06T21:52:26.432Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-harness-the-power-of-look-up-tables-luts-for-professionals/"><u>[New] In 2024, Harness the Power of Look-Up Tables (LUTs) for Professionals</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-how-youtube-really-measures-your-contents-popularity/"><u>[Updated] 2024 Approved How YouTube Really Measures Your Content's Popularity</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-the-complete-guide-to-virtual-whiteboard-excellence-for-zoom-sessions-desktopiosandroid/"><u>[Updated] In 2024, The Complete Guide to Virtual Whiteboard Excellence for Zoom Sessions (Desktop/iOS/Android)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-rapid-viewer-for-10-windows-photos/"><u>[Updated] Rapid Viewer for 10 Windows Photos</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-step-by-step-guide-signing-up-for-a-new-facebook-profile/"><u>[Updated] Step-by-Step Guide Signing Up for a New Facebook Profile</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-tips-for-extending-instagram-videos-beyond-limits/"><u>2024 Approved Tips for Extending Instagram Videos Beyond Limits</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-now-ultimate-guide-to-using-your-targus-dock-with-simple-driver-installation/"><u>Download Now! Ultimate Guide to Using Your Targus Dock with Simple Driver Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-strategies-to-enhance-computer-boot-time-performance/"><u>Efficient Strategies to Enhance Computer Boot Time Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-your-laptop-microphone-working-again-expert-tips-and-fixes/"><u>How to Get Your Laptop Microphone Working Again - Expert Tips & Fixes</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-when-apple-account-locked-on-apple-iphone-14-by-drfone-ios/"><u>In 2024, How to Fix when Apple Account Locked On Apple iPhone 14?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-systemprofile-desktop-inaccessibility-error-in-microsoft-windows-environment/"><u>Overcoming the Systemprofile Desktop Inaccessibility Error in Microsoft Windows Environment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-high-disk-space-consumption-by-microsoft-telemetry-in-windows-11/"><u>Resolving High Disk Space Consumption by Microsoft Telemetry in Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1723964490170-sennheisers-high-end-hd-620s-audiophile-headphones-new-low-price-at-just-50/"><u>Sennheiser's High-End HD 지620S Audiophile Headphones: New Low Price at Just $50</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-flash-content-glitches-on-google-chrome-with-these-fixes/"><u>Solve Your Flash Content Glitches on Google Chrome with These Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-touchpad-issues-for-optimal-usage/"><u>Step-by-Step Guide: Resolving Touchpad Issues for Optimal Usage</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-persistent-booting-problems-solutions-inside/"><u>Troubleshooting Persistent Booting Problems: Solutions Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-why-isnt-your-dell-keyboard-responding/"><u>Troubleshooting Steps: Why Isn't Your Dell Keyboard Responding?</u></a></li>
</ul></div>

