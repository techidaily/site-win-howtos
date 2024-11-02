---
title: How to Correctly Address and Repair 'Error Code 28' In Windows Device Manager
date: 2024-10-28T10:49:28.882Z
updated: 2024-11-01T18:09:58.881Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115937/19272" target="_top" id="2115937">
  <img src="//a.impactradius-go.com/display-ad/19272-2115937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115937/19272" style="position:absolute;visibility:hidden;" border="0" />
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

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657395/16446" target="_top" id="1657395">
  <img src="//a.impactradius-go.com/display-ad/16446-1657395" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657395/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-seamless-integration-vimeo-uploads-with-windows-media-center/"><u>[New] 2024 Approved Seamless Integration Vimeo Uploads with Windows Media Center</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-pushing-boundaries-innovative-hdr-portrait-techniques-for-2024/"><u>[New] Pushing Boundaries Innovative HDR Portrait Techniques for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-from-video-to-animation-easy-youtube-gif-creation-tips/"><u>[Updated] In 2024, From Video to Animation Easy YouTube GIF Creation Tips</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/dissecting-failures-in-attempted-gpt-alteration/"><u>Dissecting Failures in Attempted GPT Alteration</u></a></li>
<li><a href="https://extra-information.techidaily.com/dji-inspire-2-full-review/"><u>DJI Inspire 2 Full Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-watch-videos-on-psp-a-comprehensive-guide-to-supported-file-types-and-conversion-tips/"><u>How to Watch Videos on PSP: A Comprehensive Guide to Supported File Types and Conversion Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/installing-the-morpheus-extension-for-enhanced-kodi-viewing-experience-is-it-matrix-ready/"><u>Installing the Morpheus Extension for Enhanced Kodi Viewing Experience - Is It Matrix Ready?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/m4riphonewav/"><u>M4R形式でiPhone着信音にWAVを転換する手順</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-quick-h264-edits-the-ultimate-tutorial-on-cutting-videos-with-ease/"><u>Mastering Quick H.264 Edits: The Ultimate Tutorial on Cutting Videos with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mkv-to-itunes-transformation-learn-the-top-three-techniques-for-seamless-playback/"><u>MKV to iTunes Transformation: Learn the Top Three Techniques for Seamless Playback</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movae/"><u>MOV形式でAEが認識できなくなった時、効果的なトラブルシューティング手順</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mp4mp3wav/"><u>MP4/MP3ビデオ音声をWAVフォーマットにアップコンバートする詳細ガイド</u></a></li>
<li><a href="https://win-howtos.techidaily.com/new-release-alert-enhanced-watermarks-with-wonderfoxs-latest-photography-software-v11/"><u>New Release Alert: Enhanced Watermarks with WonderFox's Latest Photography Software V1.1</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/silver-chords-shorts-actor-melodies-for-2024/"><u>Quicksilver Chords Shorts' Actor Melodies for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/sdmp3/"><u>SDカード内MP3再生トラブルシューティングテクニック</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/ultimate-guide-mastering-winx-mediatrans-for-seamless-audio-video-and-photo-conversions/"><u>Ultimate Guide: Mastering WinX MediaTrans for Seamless Audio, Video & Photo Conversions</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-samsungs-image-editing-software-insights-for-2024/"><u>Unveiling Samsung's Image Editing Software Insights for 2024</u></a></li>
</ul></div>

