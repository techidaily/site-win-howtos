---
title: Windows 10 Users, Here's How to Overcome the 'Port Reset Failed' Error with Your USB Device!
date: 2024-12-09T17:42:52.736Z
updated: 2024-12-13T17:59:05.608Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 10 Users, Here's How to Overcome the 'Port Reset Failed' Error with Your USB Device!
excerpt: This Article Describes Windows 10 Users, Here's How to Overcome the 'Port Reset Failed' Error with Your USB Device!
thumbnail: https://thmb.techidaily.com/cd939fa7a6d55f7872fb793de3dd6a0a1cf42f10f319881184a8db53e138fd0a.jpg
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/new-in-2024-how-to-use-chromes-picture-in-progress-screensuitably-across-platforms/"><u>[New] In 2024, How to Use Chrome’s Picture In Progress Screensuitably Across Platforms</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-methods-for-installing-latest-drivers-on-dell-xps-15-running-windows-os/"><u>Easy Methods for Installing Latest Drivers on Dell XPS # 15 Running Windows OS</u></a></li>
<li><a href="https://buynow-help.techidaily.com/expert-analysis-of-the-garmin-forerunner-945-a-complete-gps-smartwatch-breakdown/"><u>Expert Analysis of the Garmin Forerunner 945: A Complete GPS Smartwatch Breakdown</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-missing-vc-runtime-140-dll-file-expert-solutions-revealed/"><u>Fixing the Missing VC Runtime 140 DLL File - Expert Solutions Revealed</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-a-step-by-step-approach-how-to-record-and-archive-online-radio/"><u>In 2024, A Step-by-Step Approach How To Record & Archive Online Radio</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-nubia-red-magic-8s-pro-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Nubia Red Magic 8S Pro via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-solve-invisible-buffer-problems-in-video-games/"><u>In 2024, Solve Invisible Buffer Problems in Video Games</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Honor X50i | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-error-resolution-for-unwritable-0x-referenced-memory-instances/"><u>Mastering Error Resolution for Unwritable 0X Referenced Memory Instances</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-pc-maintenance-effective-use-of-sfc-and-dism-in-windows-10-fixes/"><u>Mastering PC Maintenance: Effective Use of SFC and DISM in Windows 10 Fixes</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-digital-drawing-board-how-to-convert-videos-into-cartoons-and-animations/"><u>New Digital Drawing Board How to Convert Videos Into Cartoons and Animations</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/pumpless-vs-pump-powered-the-24naio-coolers-remarkable-performance-just-8c-behind-competitors/"><u>Pumpless Vs. Pump-Powered: The 24nAiO Cooler's Remarkable Performance Just 8C Behind Competitors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-an-issue-occurred-while-rebooting-message-in-windows-11-a-complete-guide/"><u>Solving the 'An Issue Occurred While Rebooting' Message in Windows 11: A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-solving-windows-1n0-continuous-auto-repair-issue/"><u>Step-by-Step Guide: Solving Windows 1N0 Continuous Auto Repair Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-pubg-non-loading-buildings-fix/"><u>Step-by-Step Solution for PUBG Non-Loading Buildings Fix</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-guide-top-10-places-to-download-inspiring-slideshow-designs-for-2024/"><u>The Ultimate Guide Top 10 Places to Download Inspiring Slideshow Designs for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-sign-in-issues-with-windows-1011-user-profiles/"><u>Troubleshooting Sign-In Issues with Windows 10/11 User Profiles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-your-ps4s-excessive-sound-diagnosis-and-resolution-steps/"><u>Understanding Your PS4’s Excessive Sound: Diagnosis and Resolution Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202538499-valorant-launch-stuck-on-infinite-load-heres-how-to-fix-it/"><u>Valorant Launch Stuck on Infinite Load? Here's How to Fix It!</u></a></li>
</ul></div>

