---
title: How to Correctly Address and Repair 'Error Code 28' In Windows Device Manager
date: 2024-11-27T10:01:44.264Z
updated: 2024-11-28T04:34:27.066Z
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

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-boxes.techidaily.com/new-breaking-down-the-free-fcp-puzzle/"><u>[New] Breaking Down The Free FCP Puzzle</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-capture-and-convert-your-instagram-feeds-top-15-free-exporters-for-windows-and-macos-users/"><u>[New] Capture and Convert Your Instagram Feeds Top 15 Free Exporters For Windows & macOS Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-frozen-frontier-showcasing-2022s-olympic-peaks-and-precision-riders/"><u>[New] Frozen Frontier Showcasing 2022'S Olympic Peaks and Precision Riders</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-the-art-of-visual-storytelling-with-iphone-xs-new-lens/"><u>[Updated] The Art of Visual Storytelling with iPhone X's New Lens</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-essentials-of-time-stamped-photography/"><u>2024 Approved The Essentials of Time-Stamped Photography</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-youtubers-ultimate-guide-10-keys-to-unique-short-form-videos/"><u>2024 Approved Youtubers' Ultimate Guide 10 Keys to Unique Short-Form Videos</u></a></li>
<li><a href="https://program-issues.techidaily.com/comprehensive-solutions-to-tackle-microsoft-edge-malfunction-on-your-windows-tenth-gen-pc/"><u>Comprehensive Solutions to Tackle Microsoft Edge Malfunction on Your Windows Tenth-Gen PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehhemic-approach-to-repairing-and-preventing-cod-black-ops-4-malfunctions/"><u>Comprehhemic Approach to Repairing and Preventing COD Black Ops 4 Malfunctions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-restore-your-windows-11-computers-broken-usb-connections/"><u>Effective Solutions to Restore Your Windows 11 Computer's Broken USB Connections</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-ce-34878-0-issue-quickly-for-your-ps4-console/"><u>How to Fix the CE-34878-0 Issue Quickly for Your PS4 Console</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-art-of-fixing-steam-disk-error-write-failed-instantly/"><u>Mastering the Art of Fixing Steam 'Disk Error: Write Failed' Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-frozen-chromium-experience-with-easy-relaunch-steps/"><u>Overcome Frozen Chromium Experience with Easy Relaunch Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-hurdle-correcting-error-0x800f081f-in-net-framework-35-implementation/"><u>Overcoming the Hurdle: Correcting Error 0X800F081F in .NET Framework 3.5 Implementation</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-cooldown-chart-on-oneplus-ace-2-pro-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tech-tip-reducing-microsoft-telemetrys-impact-on-hard-drive-space-for-windows-10/"><u>Tech Tip: Reducing Microsoft Telemetry's Impact on Hard Drive Space for Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-functional-usb-ports-on-windows-11-a-step-by-step-guide/"><u>Troubleshooting Non-Functional USB Ports on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-solutions.techidaily.com/world-of-warcraft-stability-tweaks-fix-your-crashes-in-minutes/"><u>World of Warcraft Stability Tweaks: Fix Your Crashes in Minutes</u></a></li>
</ul></div>

