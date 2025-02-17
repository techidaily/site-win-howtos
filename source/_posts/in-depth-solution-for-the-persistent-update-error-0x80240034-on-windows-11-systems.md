---
title: In-Depth Solution for the Persistent Update Error (0X80240034) on Windows 11 Systems
date: 2025-02-15T16:28:32.537Z
updated: 2025-02-16T20:10:42.319Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/right-ideas-effective-lighting-in-vlogging-for-2024/"><u>[New] Bright Ideas Effective Lighting in Vlogging for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ncrease-your-online-presence-youtube-methods/"><u>[New] Increase Your Online Presence YouTube Methods</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-rich-resource-repository-prime-sites-for-free-high-quality-vector-art-for-2024/"><u>[New] Rich Resource Repository Prime Sites for Free High-Quality Vector Art for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-signal-id-video-overview-width-x-height-encoding-minutes/"><u>[Updated] Signal ID Video Overview Width X Height, Encoding, Minutes</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-rotated-video-conundrum-in-instagrams-feed/"><u>[Updated] The Rotated Video Conundrum in Instagram's Feed</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/discover-the-lesser-known-page-picks-for-memelings/"><u>Discover the Lesser-Known Page Picks for Memelings</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211455291-9798330398102-hacking-the-universe/"><u>Hacking the Universe | Free Book</u></a></li>
<li><a href="https://solve-info.techidaily.com/how-to-fix-sound-card-problems-expert-advice-by-yl-software-professionals/"><u>How to Fix Sound Card Problems: Expert Advice by YL Software Professionals</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-quickly-resolve-non-functioning-ps4-headset-audio-problems/"><u>How to Quickly Resolve Non-Functioning PS4 Headset Audio Problems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-two-ways-to-sync-contacts-from-honor-x7b-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Two Ways to Sync Contacts from Honor X7b to Gmail | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-printer-update-failures-a-comprehensive-fix-for-xerox-error-code-0x800f02eb-in-windows-systems/"><u>Overcoming Printer Update Failures: A Comprehensive Fix for Xerox Error Code 0X800f02eb in Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-crashing-hurdle-fixing-error-0xc00n00005-in-windows-systems/"><u>Overcoming the Crashing Hurdle: Fixing Error 0Xc00n00005 in Windows Systems</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/pre-purchase-tips-for-your-next-tv-recorder/"><u>Pre-Purchase Tips for Your Next TV Recorder</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolve-windows-error-code-0x800f020b-from-xerox-printer-updates/"><u>Troubleshooting Guide: Resolve Windows Error Code 0X800F020B From Xerox Printer Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-to-repair-a-malfunctioning-cddvd-drive-on-windows-pcs/"><u>Troubleshooting Steps to Repair a Malfunctioning CD/DVD Drive on Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-windows-users-correcting-user-profile-service-error-messages/"><u>Troubleshooting Tips for Windows Users: Correcting User Profile Service Error Messages</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-youtube-sound-issues-fixing-audio-renderer-errors-in-windows-11/"><u>Troubleshooting YouTube Sound Issues: Fixing Audio Renderer Errors in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-unsupported-input-errors-on-computer-screens/"><u>Troubleshooting: Unsupported Input Errors on Computer Screens</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-media-player-server-execution-failed-error-on-windows-solved/"><u>Windows Media Player Server Execution Failed Error on Windows [Solved]</u></a></li>
</ul></div>

