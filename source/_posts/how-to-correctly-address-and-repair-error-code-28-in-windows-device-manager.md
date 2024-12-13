---
title: How to Correctly Address and Repair 'Error Code 28' In Windows Device Manager
date: 2024-12-11T20:27:01.634Z
updated: 2024-12-13T21:37:20.696Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Correctly Address and Repair 'Error Code 28' In Windows Device Manager
excerpt: This Article Describes How to Correctly Address and Repair 'Error Code 28' In Windows Device Manager
thumbnail: https://thmb.techidaily.com/368cd26d3749cfcc0c9a3f4f17a7f654d421407edf74d20f4dbbf4dfcbdaf09d.jpg
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-tips.techidaily.com/fficiently-removing-youtube-channels-a-device-centric-approach-for-2024/"><u>[New] Efficiently Removing Youtube Channels A Device-Centric Approach for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-the-filmmakers-toolkit-essential-color-grading-of-7-techniques-for-2024/"><u>[New] The Filmmaker's Toolkit Essential Color Grading of 7 Techniques for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transform-your-vfx-workflow-implementing-luts-within-after-effects/"><u>[New] Transform Your VFX Workflow Implementing LUTs Within After Effects</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-brilliant-question-bank-to-entice-audio-enthusiasts/"><u>2024 Approved Brilliant Question Bank to Entice Audio Enthusiasts</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-detailed-instructions-for-embedding-and-displaying-youtube-playlists-online/"><u>2024 Approved Detailed Instructions for Embedding and Displaying YouTube Playlists Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-functional-mic-issue-in-windows-11/"><u>Fixing a Non-Functional Mic Issue in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-address-device-unavailable-error-24-for-windows-users/"><u>How to Correctly Address Device Unavailable Error (#24) for Windows Users</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-fix-asus-laptop-screen-flickering/"><u>How To Fix ASUS Laptop Screen Flickering</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-shockwave-flash-problems-on-google-chrome-platform/"><u>How to Repair Shockwave Flash Problems on Google Chrome Platform</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-top-10-affordable-and-easy-online-passport-pics-tools/"><u>In 2024, Top 10 Affordable & Easy Online Passport Pics Tools</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/oxford-3000-revolutionized-by-mondly-for-learning/"><u>Oxford 3000, Revolutionized by Mondly for Learning</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210065638-pdf-printer-problems-quick-fixes-for-immediate-relief/"><u>PDF Printer Problems: Quick Fixes for Immediate Relief!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-key-issues-in-windows-11-easy-step-by-step-solutions/"><u>Resolving Windows Key Issues in Windows 11 - Easy Step-by-Step Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-getting-microsoft-store-back-online-after-failure-to-open/"><u>Solution Guide: Getting Microsoft Store Back Online After Failure to Open</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-to-tailored-settings-malfunctioning-on-your-device/"><u>Solutions to Tailored Settings Malfunctioning on Your Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/taming-the-high-cpu-demands-of-win10/"><u>Taming the High-CPU Demands of Win10</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-vivo-s17e-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ultimate-guide-to-hp-dock-g2-thunderbolt-setup-obtain-the-essential-120w230w-device-drivers-today/"><u>Ultimate Guide to HP Dock G2 Thunderbolt Setup: Obtain the Essential 120W/230W Device Drivers Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wwe-2k-battlegrounds-directx-compatibility-fixing-feature-level-100-issue/"><u>WWE 2K Battlegrounds DirectX Compatibility: Fixing Feature Level 10.0 Issue</u></a></li>
</ul></div>

