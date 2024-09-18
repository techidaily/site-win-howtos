---
title: "How to Successfully Elevate Permissions: Addressing 'Operation Requires Elevation' On Windows Platforms"
date: 2024-09-11T02:24:07.550Z
updated: 2024-09-18T02:59:27.064Z
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1160850">
					<video width="576" height="324" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1160850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1160850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1160850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1160850%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1160850/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997695/19272" target="_top" id="1997695">
  <img src="//a.impactradius-go.com/display-ad/19272-1997695" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997695/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-in-game-magic-discover-4-ways-to-preserve-your-gaming-sessions/"><u>[New] 2024 Approved In-Game Magic Discover 4 Ways to Preserve Your Gaming Sessions</u></a></li>
<li><a href="https://win-able.techidaily.com/solved-snowrunner-keeps-crashing-on-pc/"><u>[SOLVED] SnowRunner Keeps Crashing on PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/2024mp3-mkv/"><u>2024年に最適な無料MP3変換アプリ: MKVファイル用のベストセレクション</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726026294858-dvd/"><u>一般的DVDバックアップにおけるエラー解析とトラブルシューティング</u></a></li>
<li><a href="https://win-howtos.techidaily.com/adobe-premiere-promovmp4/"><u>Adobe Premiere Proを使用したMOVファイルからMP4への変換ガイド</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726026577681-aviutl/"><u>AviUtlでシンプルに動画のカラーコレクト技術</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726030456331-dvddvd/"><u>DVDデクリプター使用方法｜効果的にDVDをコピーするテクニック</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-tecno-pova-6-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Tecno Pova 6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-learn-to-create-custom-sequence-presets-in-premiere-pro-for-efficient-video-editing-ensure-consistency-and-speed-up-your-workflow-with-personalized-/"><u>In 2024, Learn to Create Custom Sequence Presets in Premiere Pro for Efficient Video Editing. Ensure Consistency and Speed up Your Workflow with Personalized Settings</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-two-ways-to-sync-contacts-from-vivo-x100-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Two Ways to Sync Contacts from Vivo X100 to Gmail | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/life-beyond-likes-7-reasons-for-reducing-social-media-usage/"><u>Life Beyond Likes: 7 Reasons for Reducing Social Media Usage</u></a></li>
<li><a href="https://technical-tips.techidaily.com/samsung-unpacked-2025-the-comprehensive-guide-to-whats-new-and-rumored-for-the-next-gen-gadgets/"><u>Samsung Unpacked 2025: The Comprehensive Guide to What’s New and Rumored for the Next Gen Gadgets</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-fixing-the-issue-of-bluetooth-connection-with-no-audio/"><u>Troubleshooting Guide: Fixing the Issue of Bluetooth Connection with No Audio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726027630263-windows-pc/"><u>Windows PCで楽器の質感を出すためのステレオミキシング技術</u></a></li>
<li><a href="https://win-howtos.techidaily.com/44oe44or44ob44oh44oh44kj44ki44ov44kh44kk44or44gl44kj44gu44k144ow44k44kk44oi44or5oqc44gn5yplusw44kk5pa55rov/"><u>マルチメディアファイルからのサブタイトル抜き取り方法</u></a></li>
</ul></div>

