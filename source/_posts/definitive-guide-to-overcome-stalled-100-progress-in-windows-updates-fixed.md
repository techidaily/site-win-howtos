---
title: Definitive Guide to Overcome Stalled 100%% Progress in Windows Updates [FIXED]
date: 2025-02-10T17:24:40.584Z
updated: 2025-02-16T19:03:38.955Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://win-howtos.techidaily.com/fixed-computer-crashes-when-playing-games-in-windows-1011/"><u>[FIXED] Computer Crashes When Playing Games in Windows 10/11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-nikon-z7-ii-analysis-deep-dive/"><u>[New] Nikon Z7 II Analysis Deep-Dive</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-quickrestore-reviewers-thoughts/"><u>[Updated] 2024 Approved QuickRestore Reviewers Thoughts</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-one-youtube-feed-how-to-merge-multiple-videos/"><u>[Updated] In 2024, One YouTube Feed How to Merge Multiple Videos</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-affordable-hd-action-cam-hits-top-list/"><u>2024 Approved Affordable HD Action Cam Hits Top List</u></a></li>
<li><a href="https://media-tips.techidaily.com/convert-video-output-box-vob-files-to-3gp-format-in-just-3-simple-steps-pc-guide/"><u>Convert Video Output Box (VOB) Files to 3GP Format in Just 3 Simple Steps - PC Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-repairing-ethernet-network-errors-for-windows-10-and-7-users/"><u>Guide to Repairing Ethernet Network Errors for Windows 10 and 7 Users</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-samsung-galaxy-a14-5g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-non-responsive-laptop-mousepad-on-windows-8-and-7-step-by-step-guide/"><u>How to Fix a Non-Responsive Laptop Mousepad on Windows 8 & 7: Step-by-Step Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-fix-microsoftdirectxdirectinputdll-errors/"><u>How to Fix Microsoft.directx.directinput.dll Errors</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-oneplus-ace-3-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your OnePlus Ace 3 FRP Locks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-with-unsupported-platforms-during-intel-serial-io-driver-setup/"><u>Resolving Issues with Unsupported Platforms During Intel Serial IO Driver Setup</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/seamless-integration-making-your-youtube-videos-available-on-facebook-for-2024/"><u>Seamless Integration Making Your YouTube Videos Available on Facebook for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-update-issues-in-windows-10-resolve-error-code-0x800f0922/"><u>Solving Update Issues in Windows 10: Resolve Error Code 0X800f0922</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205370097-troubleshooting-persistent-booting-problems-solutions-inside/"><u>Troubleshooting Persistent Booting Problems: Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fix-for-dell-laptop-black-screen-problems-a-comprehensive-guide/"><u>Ultimate Fix for Dell Laptop Black Screen Problems – A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/usb-malfunctioning-problem-solved-guides-for-windows-10-and-11/"><u>USB Malfunctioning Problem Solved: Guides for Windows 10 and 11</u></a></li>
</ul></div>

