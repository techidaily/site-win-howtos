---
title: In-Depth Solution for the Persistent Update Error (0X80240034) on Windows 11 Systems
date: 2024-12-12T16:31:00.666Z
updated: 2024-12-13T16:26:42.684Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes In-Depth Solution for the Persistent Update Error (0X80240034) on Windows 11 Systems
excerpt: This Article Describes In-Depth Solution for the Persistent Update Error (0X80240034) on Windows 11 Systems
thumbnail: https://thmb.techidaily.com/e310ec62b9e76066416bdd2ef743a630e77fd957f894ef784fb3007ebc56c01f.jpg
---

## Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-access.techidaily.com/new-2024-approved-discover-the-best-premiere-pro-templates-free-2023/"><u>[New] 2024 Approved Discover the Best Premiere Pro Templates (FREE) 2023</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-a-step-by-step-approach-to-enhanced-roblox-views/"><u>[New] A Step-by-Step Approach to Enhanced Roblox Views</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-10-expert-suggestions-to-make-your-yt-shorts-stand-out/"><u>[Updated] 2024 Approved 10 Expert Suggestions to Make Your YT Shorts Stand Out</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-best-free-screencasting-solutions-for-everyone-for-2024/"><u>[Updated] Best Free Screencasting Solutions for Everyone for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dhcp-server-unreachable-heres-the-resolved-technique/"><u>DHCP Server Unreachable? Here's the Resolved Technique</u></a></li>
<li><a href="https://win-dash.techidaily.com/fixing-common-drivers-error-for-the-hp-laserjet-p2-a-the-value-of-a-is-incorrect-and-it-cannot-be-set-to-100/"><u>Fixing Common Drivers Error for the HP LaserJet P2# A: The Value of #A Is Incorrect, and It Cannot Be Set to 100</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-your-game-requires-a-system-restart-to-play-valorant/"><u>How to Fix Your Game Requires a System Restart to Play'' Valorant</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-gunners-gratitude-discovering-our-top-7-shooter-games/"><u>In 2024, Gunner's Gratitude Discovering Our Top 7 Shooter Games</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-apple-iphone-15-with-7-methods-drfone-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for Apple iPhone 15 With 7 Methods | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/logitech-mouse-woes-heres-how-to-restore-your-scroll-wheel-functionality/"><u>Logitech Mouse Woes? Here’s How to Restore Your Scroll Wheel Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209914137-quick-guide-solve-your-sims-4-launching-issues-today/"><u>Quick Guide: Solve Your Sims 4 Launching Issues Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-screen-mirroring-woes-a-step-by-step-guide-for-windows-n-11-users/"><u>Resolve Your Screen Mirroring Woes: A Step-by-Step Guide for Windows N 11 Users</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-motorola-moto-g73-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Motorola Moto G73 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-tips-for-solving-lag-in-world-of-warcraft-efficiently/"><u>Top Tips for Solving Lag in World of Warcraft Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-responsive-fn-keys-on-dell-laptops-effective-solutions/"><u>Troubleshooting Non-Responsive Fn Keys on Dell Laptops: Effective Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-and-solutions-for-stabilizing-total-war-rome-remastered/"><u>Troubleshooting Tips and Solutions for Stabilizing Total War: Rome Remastered</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Nokia C32? | Dr.fone</u></a></li>
</ul></div>

