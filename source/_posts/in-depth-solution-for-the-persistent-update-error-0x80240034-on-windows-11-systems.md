---
title: In-Depth Solution for the Persistent Update Error (0X80240034) on Windows 11 Systems
date: 2025-02-06T01:50:40.856Z
updated: 2025-02-06T22:03:22.962Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://remote-screen-capture.techidaily.com/updated-best-5-quick-video-capture-tools-for-2024/"><u>[Updated] Best 5 Quick Video Capture Tools for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-peak-viewing-valor-youtubes-daily-top-ten-highlights/"><u>[Updated] Peak Viewing Valor YouTube's Daily Top Ten Highlights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-repair-tackling-the-persistent-sound-crackles-in-windows-11-and-windows-abcdessors-win7/"><u>Diagnose & Repair: Tackling the Persistent Sound Crackles in Windows 11 & Windows Abcdessors (Win7)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-guide-to-choosing-a-motherboard-understanding-the-7-main-points/"><u>Essential Guide to Choosing a Motherboard: Understanding the 7 Main Points</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-getting-your-igfxem-module-back-up-and-running/"><u>Expert Tips on Getting Your Igfxem Module Back Up and Running</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fix-d3d9-dll-missing-issue-simple-steps-to-follow/"><u>Fix D3D9 DLL Missing Issue - Simple Steps to Follow</u></a></li>
<li><a href="https://win-howtos.techidaily.com/forgotten-sd-card-discover-remedies/"><u>Forgotten SD Card, Discover Remedies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-offscreen-window-issues-a-comprehensive-walkthrough/"><u>How To Fix Offscreen Window Issues: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-10-may-update-version-1903-installation-problems-a-comprehensive-guide/"><u>How to Fix Windows 10 May Update (Version 1903) Installation Problems: A Comprehensive Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-huawei-p60-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Huawei P60 Phone that is Locked?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-reconnect-to-the-steam-shop-after-unexpected-disruptions/"><u>How To Successfully Reconnect to The Steam Shop After Unexpected Disruptions</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-gionee-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Gionee FRP</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-latency-problems-with-your-keyboard-in-windows-11-systems/"><u>Resolving Latency Problems with Your Keyboard in Windows 11 Systems</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/reviewcast-analysis/"><u>ReviewCast Analysis</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/steady-snapstreaks-tips-to-never-miss-a-snap/"><u>Steady Snapstreaks Tips to Never Miss a Snap</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-to-fix-windows-installation-failure-error-0x80code0x080070643-on-windows-systems/"><u>Step-by-Step Solutions to Fix 'Windows Installation Failure Error 0X80([code]0X080070643) on Windows Systems</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-plain-truth-about-virtual-conversations-dispelling-ai-bot-fables/"><u>The Plain Truth About Virtual Conversations - Dispelling AI Bot Fables</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-to-resolving-videodxgkrnlcriticalfailures-in-windows-os/"><u>Ultimate Guide to Resolving Video_Dxgkrnl_Critical_Failures in Windows OS</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/uncovering-the-features-of-the-xp-pen-artist-16-pro-the-ultimate-digital-sketchers-companion/"><u>Uncovering the Features of the XP-Pen Artist 16 Pro – The Ultimate Digital Sketcher’s Companion</u></a></li>
</ul></div>

