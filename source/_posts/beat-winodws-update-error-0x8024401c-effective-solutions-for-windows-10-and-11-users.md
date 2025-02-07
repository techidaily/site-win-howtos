---
title: "Beat Winodws Update Error 0X8024401c: Effective Solutions for Windows 10 & 11 Users"
date: 2025-01-31T12:58:55.504Z
updated: 2025-02-07T13:03:06.669Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Beat Winodws Update Error 0X8024401c: Effective Solutions for Windows 10 & 11 Users"
excerpt: "This Article Describes Beat Winodws Update Error 0X8024401c: Effective Solutions for Windows 10 & 11 Users"
thumbnail: https://thmb.techidaily.com/bab37a5357094e09dd42f37d3cc78e25fe907bbcf4a7b3121bebc119dc83e730.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-ideal-echo-reapers-in-colleges/"><u>[New] 2024 Approved Ideal Echo Reapers in Colleges</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-streaming-masterpieces-best-movie-directories-on-yt/"><u>[New] Streaming Masterpieces Best Movie Directories on YT</u></a></li>
<li><a href="https://youtube-data.techidaily.com/our-blueprint-to-youtube-success-top-tips-for-outstanding-shorts-for-2024/"><u>[New] Your Blueprint to Youtube Success Top Tips for Outstanding Shorts for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-optimal-zero-dollar-valorant-sound-manipulator-alert/"><u>[Updated] Optimal Zero Dollar Valorant Sound Manipulator Alert</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-expert-review-ricoh-theta-s-unveiled-in-detail/"><u>2024 Approved Expert Review Ricoh Theta S Unveiled in Detail</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-xsplit-hub-centralized-download-and-evaluation/"><u>2024 Approved XSplit Hub Centralized Download & Evaluation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beating-the-0x80073712-error-proven-fixes-for-a-smooth-windows-10-experience/"><u>Beating the 0X80073712 Error: Proven Fixes for a Smooth Windows 10 Experience</u></a></li>
<li><a href="https://tech-hub.techidaily.com/google-pixel-watch-against-apple-watch-series-9-which-smartwatch-ticks-all-the-boxes-for-you-techspot/"><u>Google Pixel Watch Against Apple Watch Series 9 - Which Smartwatch Ticks All The Boxes For You? | TechSpot</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-failed-update-issues-in-your-favorite-mmo-warframe/"><u>How to Overcome Failed Update Issues in Your Favorite MMO, Warframe</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1721816290619-just-start-chatting-chatgpt-ready/"><u>Just Start Chatting - ChatGPT Ready</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-battlefield-solutions-for-fixing-interruptions-in-online-gaming-arenas/"><u>Mastering the Battlefield: Solutions for Fixing Interruptions in Online Gaming Arenas</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-a-non-functional-spacebar-keys-under-windows-10-environments/"><u>Step-by-Step Fixes for a Non-Functional Spacebar Keys Under Windows 10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-troubleshooting-for-connecting-airpods-with-windows-11-latest-techniques/"><u>Step-by-Step Troubleshooting for Connecting AirPods with Windows 11 - Latest Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-when-bluetooth-doesnt-appear-in-windows-device-manager/"><u>Troubleshooting Tips When Bluetooth Doesn't Appear in Windows Device Manager</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-your-usb-to-hdmi-converter-wont-work-solutions-included/"><u>Why Your USB to HDMI Converter Won't Work - Solutions Included</u></a></li>
</ul></div>

