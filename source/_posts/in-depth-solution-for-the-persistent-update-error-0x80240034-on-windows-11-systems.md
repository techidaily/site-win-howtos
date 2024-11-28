---
title: In-Depth Solution for the Persistent Update Error (0X80240034) on Windows 11 Systems
date: 2024-11-22T00:42:55.055Z
updated: 2024-11-28T02:04:23.857Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-posts.techidaily.com/new-pro-video-enhancement-ranking-the-superior-15-gopro-lut-tools/"><u>[New] Pro Video Enhancement Ranking the Superior 15 GoPro LUT Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-masterful-methods-for-keeping-track-of-messenger-communications/"><u>[Updated] In 2024, Masterful Methods for Keeping Track of Messenger Communications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-fix-guide-overcoming-the-challenge-of-error-code-0x80072f8f-in-windows-operating-systems/"><u>Complete Fix Guide: Overcoming the Challenge of Error Code 0X80072F8F in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-asus-webcam-issues-with-no-display-on-windows-nix-11/"><u>Diagnosing and Fixing ASUS Webcam Issues with No Display on Windows Nix-11</u></a></li>
<li><a href="https://win-exceptional.techidaily.com/easy-tutorial-on-integrating-gif-images-into-powerpoint-slides-for-engaging-presentations/"><u>Easy Tutorial on Integrating GIF Images Into PowerPoint Slides for Engaging Presentations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-overcoming-excessive-cpu-use-by-wudfhostexe-in-windows-10-systems/"><u>Effective Solutions for Overcoming Excessive CPU Use by wudfhost.exe in Windows 10 Systems</u></a></li>
<li><a href="https://fox-that.techidaily.com/fixing-hold-alert-while-charging-your-iphone-explore-8-proven-techniques/"><u>Fixing Hold Alert While Charging Your iPhone - Explore 8 Proven Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-windows-11-tips-mastering-memo-making/"><u>Free Windows 11 Tips: Mastering Memo-Making</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-repair-the-configuration-failure-on-windows-11/"><u>How to Troubleshoot and Repair the Configuration Failure on Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/overview-of-various-cameras-used-in-film-and-tv-for-2024/"><u>Overview of Various Cameras Used in Film & TV for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-windows-7s-slow-booting-dilemma/"><u>Quick Fixes for Windows 7'S Slow Booting Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-unsupported-os-message-setup-closing-with-easy-fixes/"><u>Resolve 'Unsupported OS Message: Setup Closing' With Easy Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-how-to-get-back-windows-that-have-vanished-off-screen/"><u>Step by Step: How to Get Back Windows That Have Vanished Off-Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-instructions-to-get-your-left-click-mouse-working-again/"><u>Step-by-Step Instructions to Get Your Left-Click Mouse Working Again</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-wasteland-2-directors-cut-review/"><u>The Wasteland 2: Director’s Cut Review</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-itel-p55-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Itel P55 | Dr.fone</u></a></li>
</ul></div>

