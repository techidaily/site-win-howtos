---
title: How to Correctly Address and Repair 'Error Code 28' In Windows Device Manager
date: 2025-02-26T16:12:42.459Z
updated: 2025-03-05T16:16:52.567Z
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-taste-the-difference-top-7-tactics-for-cutting-edge-cookery-films/"><u>[New] 2024 Approved Taste the Difference Top 7 Tactics for Cutting-Edge Cookery Films</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-optimal-record-solution-chromebook-edition/"><u>[Updated] 2024 Approved Optimal Record Solution Chromebook Edition</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-achieve-the-perfect-look-youtubes-guide-to-video-aspect-ratios-for-2024/"><u>[Updated] Achieve the Perfect Look YouTube's Guide to Video Aspect Ratios for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-easy-guide-turning-your-favorite-youtube-videos-into-animated-gifs-for-2024/"><u>[Updated] Easy Guide Turning Your Favorite YouTube Videos Into Animated GIFs for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1-effortless-video-downloads-from-crunchyroll-two-no-cost-techniques/"><u>1. Effortless Video Downloads From Crunchyroll: Two No-Cost Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028472447-pc2024/"><u>新解釈！PCで最新インスタグラムビデオをダウンロードする詳細手引き202#4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726029019327-windows-10/"><u>最新Windows 10でのマイクと内部オーディオ使用による録音プロセスガイド</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210756752-9780760383957-divination-for-beginners/"><u>Divination for Beginners | Free Book</u></a></li>
<li><a href="https://techidaily.com/hard-reset-xiaomi-redmi-a2-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Xiaomi Redmi A2 in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/rh5770windowsrtkdrivers/"><u>RH5770WindowsRTKDrivers</u></a></li>
<li><a href="https://facebook.techidaily.com/the-upsurge-of-crypto-in-online-advertising-spaces/"><u>The Upsurge of Crypto in Online Advertising Spaces</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726029213837-tiktok/"><u>TikTok 動画直接下載及錄音的最基本方法 - 超簡単！</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/top-10-des-meilleurs-convertisseurs-videos-gratuites-compatibles-avec-windows-10-guide-2023/"><u>Top 10 Des Meilleurs Convertisseurs Vidéos Gratuites Compatibles Avec Windows 10 - Guide 2023</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-1011my-cinema-app/"><u>Windows 10/11版でMy Cinema Appをスムーズに動画録画するチュートリアル</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wmam4a/"><u>WMA音楽ファイルをM4A形式に効果的に変換する方法」</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028428055-youtube/"><u>ダウンロード可能なYouTube動画とその字幕:手引き</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-1/"><u>フリーかつ簡単な方法 - Windows 1</u></a></li>
</ul></div>

