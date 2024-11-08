---
title: "How to Successfully Elevate Permissions: Addressing 'Operation Requires Elevation' On Windows Platforms"
date: 2024-11-01T07:34:45.606Z
updated: 2024-11-08T05:34:47.799Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Successfully Elevate Permissions: Addressing 'Operation Requires Elevation' On Windows Platforms"
excerpt: "This Article Describes How to Successfully Elevate Permissions: Addressing 'Operation Requires Elevation' On Windows Platforms"
thumbnail: https://thmb.techidaily.com/ac559d48bd17f3abbbc061aaa86ec644753f92e76f6e17526af1715e861dd9a8.jpg
---

## How to Successfully Resolve Error Code 0X80ebbbb on Windows Updates - Proven Techniques Inside

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475">
  <img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885932/19272" target="_top" id="1885932">
  <img src="//a.impactradius-go.com/display-ad/19272-1885932" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885932/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://review-au.sjv.io/c/5597632/2135315/14409" target="_top" id="2135315">
  <img src="//a.impactradius-go.com/display-ad/14409-2135315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135315/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100541/7443" target="_top" id="2100541">
  <img src="//a.impactradius-go.com/display-ad/7443-2100541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398449/3022" target="_top" id="398449">
  <img src="//a.impactradius-go.com/display-ad/3022-398449" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398449/3022" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-clips.techidaily.com/new-create-captivate-independent-animation-innovations/"><u>[New] Create, Captivate Independent Animation Innovations</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-10-proven-techniques-for-skyrocketing-social-media-supporters/"><u>[New] In 2024, 10 Proven Techniques for Skyrocketing Social Media Supporters</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-logitech-4k-pro-webcam-complete-specifications-and-features-for-2024/"><u>[Updated] Logitech 4K Pro Webcam Complete Specifications & Features for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-next-level-designers-post-acid-tools-explored/"><u>[Updated] Next-Level Designers Post-ACID Tools Explored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/come-eccellente-strategie-di-mixaggio-audio-video-top-3/"><u>Come Eccellente: Strategie Di Mixaggio Audio-Video Top 3</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/descubre-las-mejores-tecnicas-para-tomar-screenshots-de-google-maps-sin-costo-alguno-guia-paso-a-paso/"><u>Descubre Las Mejores Técnicas Para Tomar Screenshots De Google Maps Sin Costo Alguno - Guía Paso a Paso</u></a></li>
<li><a href="https://facebook.techidaily.com/privacy-in-sight-concealing-posts-with-archive-function/"><u>Privacy in Sight: Concealing Posts with Archive Function</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211241403-9798869207548-spiritual-blindness/"><u>Spiritual Blindness | Free Book</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-five-critical-considerations-for-acquiring-used-and-revamped-laptops/"><u>The Five Critical Considerations for Acquiring Used and Revamped Laptops</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-11-effektivte-metoder-for-omskiftning-fra-ts-til-mp4-format-windows-mac-and-online-optimering/"><u>Top 11 Effektivte Metoder for Omskiftning Fra TS Til MP4-Format - Windows, Mac & Online Optimering</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-alternatives-a-inshot-para-windows-optimizar-tus-snapshots-en-la-pc/"><u>Top Alternatives a Inshot Para Windows: Optimizar Tus Snapshots en La PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/vice-o-nahravkach-obrazovych-soustaveni-s-vlc-media-player-refreshed-tutorial/"><u>Více O Nahrávkách Obrazových Soustavení S VLC Media Player - Refreshed Tutorial</u></a></li>
</ul></div>

