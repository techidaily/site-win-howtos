---
title: In-Depth Solution for the Persistent Update Error (0X80240034) on Windows 11 Systems
date: 2024-11-02T06:58:30.547Z
updated: 2024-11-08T07:07:19.488Z
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
<a href="https://appsumo.8odi.net/c/5597632/2137379/7443" target="_top" id="2137379">
  <img src="//a.impactradius-go.com/display-ad/7443-2137379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2016165/19272" target="_top" id="2016165">
  <img src="//a.impactradius-go.com/display-ad/19272-2016165" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016165/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918698/19272" target="_top" id="1918698">
  <img src="//a.impactradius-go.com/display-ad/19272-1918698" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918698/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972665/19272" target="_top" id="1972665">
  <img src="//a.impactradius-go.com/display-ad/19272-1972665" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972665/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-hastyhit-freezevidsnapshot/"><u>[New] HastyHit FreezeVidSnapshot</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-non-retweeted-video-tweet-guide-for-iphone-and-android-users/"><u>[Updated] In 2024, Non-Retweeted Video Tweet Guide for iPhone & Android Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-tips-on-finding-optimal-free-srt-translator-services/"><u>2024 Approved Expert Tips on Finding Optimal Free SRT Translator Services</u></a></li>
<li><a href="https://extra-information.techidaily.com/adding-captions-to-videos-using-microsoft-photos-windows-11-for-2024/"><u>Adding Captions to Videos Using Microsoft Photos (Windows 11) for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/all-inclusive-vsco-lens-manual-for-2024/"><u>All-Inclusive VSCO Lens Manual for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203546122-boost-your-wow-experience-eliminate-latency-problems-today/"><u>Boost Your WoW Experience: Eliminate Latency Problems Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-free-data-transfer-overcoming-challenges-with-cyclic-redundancy-check/"><u>Error-Free Data Transfer: Overcoming Challenges with Cyclic Redundancy Check</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-bluetooth-missing-from-windows-device-manager-solutions/"><u>Fix: Bluetooth Missing From Windows Device Manager - Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-reestablish-audio-hardware-on-your-pc-after-a-missing-output-device-warning/"><u>How to Reestablish Audio Hardware on Your PC After a Missing Output Device Warning</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-your-drawing-experience-addressing-wacom-pen-failures-on-win11-and-win10/"><u>Optimizing Your Drawing Experience: Addressing Wacom Pen Failures on Win11 & Win10</u></a></li>
<li><a href="https://review-topics.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-vivo-y100t-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://discover-comparisons.techidaily.com/unleash-the-power-of-chicken8-content-seamless-video-collection-awaits-at-your-fingertips/"><u>Unleash the Power of Chicken8 Content: Seamless Video Collection Awaits at Your Fingertips!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-itel-p40-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Itel P40 | Dr.fone</u></a></li>
</ul></div>

