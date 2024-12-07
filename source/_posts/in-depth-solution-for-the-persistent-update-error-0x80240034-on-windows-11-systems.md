---
title: In-Depth Solution for the Persistent Update Error (0X80240034) on Windows 11 Systems
date: 2024-12-05T18:08:28.147Z
updated: 2024-12-07T17:04:28.777Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/ed-fast-track-to-1000-fans-through-captivating-content-for-2024/"><u>[Updated] Fast-Track To 1,000 Fans Through Captivating Content for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-leading-workplace-cloud-reservoirs/"><u>[Updated] In 2024, Leading Workplace Cloud Reservoirs</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/best-practices-for-engaging-with-facebook-live-content-for-2024/"><u>Best Practices for Engaging with Facebook Live Content for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypass-freezing-issues-on-your-desktop-machine/"><u>Bypass Freezing Issues on Your Desktop Machine</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/clear-your-twitter-timeline-fast-topunfollowtools-revealed-for-2024/"><u>Clear Your Twitter Timeline Fast #TopUnfollowTools Revealed for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-tutorial-on-linking-amazon-firestick-to-wifi-via-cellular-data/"><u>Easy Tutorial on Linking Amazon Firestick to WiFi via Cellular Data</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/expert-chromebook-zoom-techniques-unveiled/"><u>Expert Chromebook Zoom Techniques Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-disappearing-taskbar-in-windows-11-top-4-icon-troubleshooting-solutions/"><u>How to Fix a Disappearing Taskbar in Windows 11: Top 4 Icon Troubleshooting Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-video-input-failure-on-your-display-step-by-step-instructions/"><u>How to Repair Video Input Failure on Your Display - Step-by-Step Instructions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203932336-keyboard-numeric-key-malfunction-heres-how-you-fixed-it/"><u>Keyboard Numeric Key Malfunction? Here's How You Fixed It</u></a></li>
<li><a href="https://fox-blue.techidaily.com/realtime-av-enthusiasts-community-for-2024/"><u>RealTime AV Enthusiasts Community for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/reimagine-old-school-vhs-with-modern-computer-techniques-for-2024/"><u>Reimagine Old-School VHS with Modern Computer Techniques for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211564877-step-by-step-solution-for-windowss-persistent-network-error-0x800704cf-now-resolved/"><u>Step-by-Step Solution for Windows's Persistent Network Error: 0X800704cf - Now Resolved</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-honor-x50i-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Honor X50i for Parents | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-tackle-non-responsive-file-explorer-problems-in-windows-10/"><u>Troubleshoot and Tackle Non-Responsive File Explorer Problems in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-correcting-invalid-directory-errors/"><u>Troubleshooting Tips for Correcting ‘Invalid Directory’ Errors</u></a></li>
</ul></div>

