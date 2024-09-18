---
title: "Step-by-Step Solution for Windows 10 Setup Error Code 80240020: A Comprehensive Guide"
date: 2024-09-13T00:07:45.260Z
updated: 2024-09-17T18:31:41.096Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Solution for Windows 10 Setup Error Code 80240020: A Comprehensive Guide"
excerpt: "This Article Describes Step-by-Step Solution for Windows 10 Setup Error Code 80240020: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/6b363964fc2e56f73bd871dd934c71ef94eb37eb3e4be61bfc1959bf2c673820.jpg
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

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148773/18498" target="_top" id="2148773">
  <img src="//a.impactradius-go.com/display-ad/18498-2148773" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148773/18498" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-crafting-illusions-spatial-and-temporal-shifts/"><u>[Updated] 2024 Approved Crafting Illusions Spatial and Temporal Shifts</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-audio-layers-for-professional-videography-premiere-pro-edition/"><u>[Updated] Audio Layers for Professional Videography Premiere Pro Edition</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-boost-your-earnings-on-youtube-shorts-a-guide-for-2024/"><u>[Updated] Boost Your Earnings on YouTube Shorts A Guide for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pc4k/"><u>「PC上での4K解像度動画記録術 - 最新トップレコーダー推薦ガイド」</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/best-free-apple-iphone-15-plus-imei-checker-by-drfone-ios/"><u>Best Free Apple iPhone 15 Plus IMEI Checker</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-streamline-your-recordings-fix-frames-out-of-sync-in-obs/"><u>In 2024, Streamline Your Recordings Fix Frames Out of Sync in OBS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-adding-the-q-sports-extension-in-kodi-version-194/"><u>Step-by-Step Guide to Adding the Q Sports Extension in Kodi Version 19.4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-recording-high-quality-wav-audio-on-windows-11/"><u>Step-by-Step Guide: Recording High-Quality WAV Audio on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On OnePlus Nord CE 3 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/the-persistent-echoes-of-eternal-return-a-look-at-black-endurance/"><u>The Persistent Echoes of 'Eternal Return': A Look at Black Endurance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/title-compare-and-contrast-the-key-differences-between-dvd-r-disc-and-dvdplusr-disc/"><u>Title: Compare & Contrast: The Key Differences Between DVD-R Disc and DVD+R Disc</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-strategies-for-effortlessly-adding-tunes-to-your-powerpoint-presentations/"><u>Top Strategies for Effortlessly Adding Tunes to Your PowerPoint Presentations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transfer-your-work-with-ease-guide-to-exporting-and-importing-webm-files-in-adobe-premiere-pro/"><u>Transfer Your Work with Ease - Guide to Exporting and Importing WebM Files in Adobe Premiere Pro</u></a></li>
</ul></div>

