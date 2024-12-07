---
title: Windows 10 Users, Here's How to Overcome the 'Port Reset Failed' Error with Your USB Device!
date: 2024-12-01T18:11:12.223Z
updated: 2024-12-07T21:00:29.233Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-skills.techidaily.com/new-the-essential-guide-to-enhancing-ar-with-lut-knowledge/"><u>[New] The Essential Guide to Enhancing AR with LUT Knowledge</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-enhancing-connectivity-ios-photo-library-and-snapchat-merge-for-2024/"><u>[Updated] Enhancing Connectivity IOS Photo Library & Snapchat Merge for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-rediscover-lost-eyes-only-pics-for-2024/"><u>[Updated] Rediscover Lost Eyes-Only Pics for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-visionary-tech-review-the-video-hub/"><u>2024 Approved Visionary Tech Review The Video Hub</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mpem4r/"><u>線上自由改變MPE到M4R的方法 – 摩瓦市音符轉換器</u></a></li>
<li><a href="https://fox-info.techidaily.com/a-beginners-guide-to-creating-impactful-slug-lines/"><u>A Beginner's Guide to Creating Impactful Slug Lines</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-apple-iphone-11-pro-max-icloud-activation-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing Apple iPhone 11 Pro Max iCloud Activation Lock</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-unlock-ultimate-clarity-choosing-the-perfect-4k-screen/"><u>In 2024, Unlock Ultimate Clarity Choosing the Perfect 4K Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/kop-movavi-video-converter-av-handelsstiftelsen-basta-pris-god-kallavsattning-och-full-gorlig-dataskicklighet/"><u>Köp Movavi Video Converter Av Handelsstiftelsen - Bästa Pris, God Kallavsättning Och Full Görlig Dataskicklighet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movavi-video-transcoder-streamlined-downloading-of-movies-and-videos/"><u>Movavi Video Transcoder - Streamlined Downloading of Movies & Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movavis-online-audio-converter-convertendo-midi-para-flac-aqui-sem-custo-algum/"><u>Movavi's Online Audio Converter - Convertendo Midi Para Flac Aqui Sem Custo Algum!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transformador-de-video-online-y-gratis-convertir-contenido-mp4-en-formato-mpeg-con-facilidad/"><u>Transformador De Vídeo Online Y Gratis: Convertir Contenido MP4 en Formato MPEG Con Facilidad</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transformer-facilement-un-fichier-jp2-en-format-jpeg-gratuitement-conversion-video-online/"><u>Transformer Facilement Un Fichier JP2 en Format JPEG Gratuitement - Conversion Vidéo Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trier-gratuitement-un-fichier-vob-au-format-flac-en-ligne-convertisseur-video-rapide/"><u>Trier Gratuitement Un Fichier VOB Au Format FLAC en Ligne - Convertisseur Vidéo Rapide</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-transform-low-res-videos-into-hd-masterpieces-with-these-tools/"><u>Updated Transform Low-Res Videos Into HD Masterpieces with These Tools</u></a></li>
</ul></div>

