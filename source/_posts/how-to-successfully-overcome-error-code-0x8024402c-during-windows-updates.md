---
title: How to Successfully Overcome Error Code 0X8024402c During Windows Updates
date: 2025-01-17T18:07:02.289Z
updated: 2025-01-19T17:46:03.495Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Successfully Overcome Error Code 0X8024402c During Windows Updates
excerpt: This Article Describes How to Successfully Overcome Error Code 0X8024402c During Windows Updates
thumbnail: https://thmb.techidaily.com/795b74ea54cc5678eb54323c8f0f4911a2d522641c62a676cf0d7c5aa1dfbffa.jpg
---

## How to Successfully Resolve Error Code 0X80ebbbb on Windows Updates - Proven Techniques Inside

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-files.techidaily.com/new-a-study-of-silliness-the-goofy-narrative-unpacked-for-2024/"><u>[New] A Study of Silliness The Goofy Narrative Unpacked for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-discovering-androids-and-ioss-best-rated-wedding-clock-apps/"><u>[New] Discovering Android's and iOS's Best-Rated Wedding Clock Apps</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-guide-to-avoiding-fees-in-fcp/"><u>[New] The Ultimate Guide to Avoiding Fees in FCP</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-silence-to-soundscape-step-by-step-in-audition/"><u>[Updated] From Silence to Soundscape Step-by-Step in Audition</u></a></li>
<li><a href="https://some-guidance.techidaily.com/7-effective-techniques-to-sync-your-iphone-with-windows-11-a-comprehensive-guide-by-movavi/"><u>7 Effective Techniques to Sync Your iPhone with Windows 11: A Comprehensive Guide by Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeating-windows-update-hurdles-expert-strategies-to-address-error-0x8024a105/"><u>Defeating Windows Update Hurdles: Expert Strategies to Address Error 0X8024a105</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/ethereal-evenings-select-10-websites-for-hd-astronomical-shots-for-2024/"><u>Ethereal Evenings Select 10 Websites for HD Astronomical Shots for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-capturing-moments-in-motion-a-review-on-panasonic-hx-a1-actioncam/"><u>In 2024, Capturing Moments in Motion - A Review on Panasonic HX-A1 ActionCam</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-vivo-y02t-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Vivo Y02T FRP In 3 Different Ways</u></a></li>
<li><a href="https://win-howtos.techidaily.com/issue-resolved-keyboard-now-responding-say-goodbye-to-typos/"><u>Issue Resolved: Keyboard Now Responding - Say Goodbye to Typos!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-fixing-windows-boot-up-missing-executable-file-issue/"><u>Step-by-Step Solutions for Fixing Windows Boot Up: Missing Executable File Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tame-cpu-surge-from-wmis/"><u>Tame CPU Surge From WMIs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-ps4-network-issues-a-detailed-walkthrough/"><u>Troubleshooting and Fixing PS4 Network Issues: A Detailed Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-to-resolve-the-dx11-feature-level-100-issue-in-wwe-2k-battlegrounds/"><u>Troubleshooting Steps to Resolve the DX11 Feature Level 10.0 Issue in WWE 2K Battlegrounds</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/unraveling-15-trendy-tiktok-stunts-today/"><u>Unraveling 15 Trendy TikTok Stunts Today</u></a></li>
</ul></div>

