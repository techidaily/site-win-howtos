---
title: "Resolved: Fix Guide for Windows 11 Update Error Code 0X8024401C"
date: 2024-11-21T00:13:38.219Z
updated: 2024-11-28T11:11:47.879Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Fix Guide for Windows 11 Update Error Code 0X8024401C"
excerpt: "This Article Describes Resolved: Fix Guide for Windows 11 Update Error Code 0X8024401C"
thumbnail: https://thmb.techidaily.com/95c7607cc85834758f594e36f86b8274633568f32ba37267dd79e6e802f121e2.png
---

## Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://program-issues.techidaily.com/fixed-dark-souls-3-crashing-issues/"><u>[Fixed] Dark Souls 3 Crashing Issues</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-a-closer-look-at-asuss-proart-pa-329q-an-in-depth-review-of-its-professional-standards/"><u>[New] A Closer Look at Asus's ProArt PA 329Q – An In-Depth Review of Its Professional Standards</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-elevate-your-ppt-game-with-clear-concise-voiceover-techniques/"><u>[Updated] 2024 Approved Elevate Your PPT Game with Clear, Concise Voiceover Techniques</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-acid-pro-analysis-and-related-tools-reviewed/"><u>[Updated] ACID Pro Analysis and Related Tools Reviewed</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-unlocking-the-power-of-srt-editing-for-mac-users-for-2024/"><u>[Updated] Unlocking the Power of SRT Editing for Mac Users for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/8-fixes-for-windows-11-update-error-code-0x800f0922/"><u>8 Fixes for Windows 11 Update Error Code 0X800f0922</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-update-atheros-network-interface-cards-nic/"><u>How to Update Atheros Network Interface Cards (NIC)</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-expand-access-to-creative-works-pick-from-the-best-free-youtube-shorts-downloader-apps/"><u>In 2024, Expand Access to Creative Works Pick From the Best Free YouTube Shorts Downloader Apps</u></a></li>
<li><a href="https://extra-hints.techidaily.com/maximizing-your-iphones-photographic-skills-in-ios-11/"><u>Maximizing Your iPhone's Photographic Skills in iOS 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-guide-resolve-error-code-0x800f0831-using-windows-updates/"><u>Quick Fix Guide: Resolve Error Code 0X800f0831 Using Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/technical-troubles-gameplay-disruptions-on-pc/"><u>Technical Troubles: Gameplay Disruptions on PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-updating-to-windows-10-version-1607/"><u>Trouble with Updating to Windows 10 Version 1607?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-the-non-responsive-spacebar-issue-in-windows-11/"><u>Troubleshooting Guide: Fixing the Non-Responsive Spacebar Issue in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-why-minecraft-fails-to-start-on-windows-solutions-inside/"><u>Troubleshooting Guide: Why Minecraft Fails to Start on Windows - Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212225460-troubleshooting-total-war-rome-remastered-crashes-solved/"><u>Troubleshooting Total War Rome Remastered Crashes – Solved</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Oppo Find X6 | Dr.fone</u></a></li>
</ul></div>

