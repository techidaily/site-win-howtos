---
title: In-Depth Solution for the Persistent Update Error (0X80240034) on Windows 11 Systems
date: 2024-10-26T18:00:56.338Z
updated: 2024-10-27T18:34:01.181Z
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

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884002/19272" target="_top" id="1884002">
  <img src="//a.impactradius-go.com/display-ad/19272-1884002" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884002/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2148648/16836" target="_top" id="2148648">
  <img src="//a.impactradius-go.com/display-ad/16836-2148648" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148648/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2105867/7443" target="_top" id="2105867">
  <img src="//a.impactradius-go.com/display-ad/7443-2105867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105867/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094428/7443" target="_top" id="2094428">
  <img src="//a.impactradius-go.com/display-ad/7443-2094428" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094428/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/n-2024-manipulate-sound-rate-in-youtube-playback/"><u>[New] In 2024, Manipulate Sound Rate in YouTube Playback</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-study-simplified-hdr-mastery/"><u>[New] In-Depth Study Simplified HDR Mastery</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-streamline-video-using-vimeo-record-for-live-captures/"><u>[Updated] In 2024, Streamline Video Using Vimeo Record for Live Captures</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unveiling-the-ideal-12-vlogging-cameras-with-seamless-screen-control/"><u>[Updated] Unveiling the Ideal 12 Vlogging Cameras with Seamless Screen Control</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-motorola-razr-40-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Motorola Razr 40 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/destiny-the-second-server-problems-heres-how-to-resolve-them-efficiently/"><u>Destiny the Second Server Problems? Here's How to Resolve Them Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-tricks-to-unfreeze-and-optimize-your-windows-11-taskbar-experience/"><u>Effective Tricks to Unfreeze and Optimize Your Windows 11 Taskbar Experience</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/how-to-resolve-file-size-exceeds-drive-capacity-on-your-external-memory-device/"><u>How to Resolve 'File Size Exceeds Drive Capacity' On Your External Memory Device</u></a></li>
<li><a href="https://review-topics.techidaily.com/huawei-nova-y71-won-t-play-hevc-h-265-media-how-to-fix-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Huawei Nova Y71 won’t play HEVC H.265 media, how to fix? </u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-complete-guide-to-final-cut-pro-for-film-professionals/"><u>In 2024, Complete Guide to Final Cut Pro for Film Professionals</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-strategies-to-fix-frame-rate-drops-and-lags-in-world-of-warcraft/"><u>In-Depth Strategies to Fix Frame Rate Drops and Lags in World of Warcraft</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-dns-failure-discover-4-effortless-solutions-for-restoring-connectivity/"><u>Overcome DNS Failure: Discover 4 Effortless Solutions for Restoring Connectivity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/preventing-automatic-startups-tips-and-tricks-for-windows-11-users/"><u>Preventing Automatic Startups: Tips and Tricks for Windows 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-how-to-fix-bluetooth-stack-service-not-starting-problem/"><u>Resolving Issues: How to Fix 'Bluetooth Stack Service Not Starting' Problem</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-the-most-popular-online-video-editors-for-chromebook-users/"><u>Updated 2024 Approved The Most Popular Online Video Editors for Chromebook Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wi-fi-troubleshooting-guide-reactivating-wi-fi-on-all-devices/"><u>Wi-Fi Troubleshooting Guide: Reactivating Wi-Fi on All Devices</u></a></li>
</ul></div>

