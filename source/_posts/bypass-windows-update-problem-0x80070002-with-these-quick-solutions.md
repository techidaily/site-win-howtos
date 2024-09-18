---
title: Bypass Windows Update Problem 0X80070002 with These Quick Solutions!
date: 2024-09-10T22:12:11.153Z
updated: 2024-09-17T21:32:48.392Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Bypass Windows Update Problem 0X80070002 with These Quick Solutions!
excerpt: This Article Describes Bypass Windows Update Problem 0X80070002 with These Quick Solutions!
thumbnail: https://thmb.techidaily.com/102c7cf0ada16d45d73aab06a0df3c1b4bd516c1e4675a811bb1bd88b724571c.jpg
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
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-clearview-recorder-xtreme-win10/"><u>[New] 2024 Approved ClearView Recorder Xtreme (Win10)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-conversion-handbook-from-gif-to-sticker-across-messaging-services/"><u>[Updated] The Ultimate Conversion Handbook From GIF to Sticker Across Messaging Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/weband/"><u>最新のWeb動画ダウンロード&保存ツール、無料オンラインリファレンスガイド</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-ad-dollars-boost-your-view-count-for-free/"><u>Avoid Ad Dollars – Boost Your View Count for Free</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-the-cutting-edge-of-uhd-with-lgs-27ud68-for-2024/"><u>Exploring the Cutting-Edge of UHD with LG's 27UD68 for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-no-1s-choice-optimal-sierra-video-apps/"><u>In 2024, No. 1'S Choice Optimal Sierra Video Apps</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://discover-docs.techidaily.com/step-by-step-guide-upscaling-your-videos-to-hd-or-4k-resolution-on-pcs-and-macs/"><u>Step-by-Step Guide: Upscaling Your Videos to HD or 4K Resolution on PCs & Macs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-12-free-software-convert-wmv-files-into-mp4-format-with-ease/"><u>Top 12 Free Software: Convert WMV Files Into MP4 Format with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-techniques-for-effortlessly-downloading-videos-from-firefox/"><u>Top Techniques for Effortlessly Downloading Videos From Firefox</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-vivo-v29e-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-top-10-free-media-player-apps-compatible-with-all-platforms-windows-macos-android-and-ios/"><u>Ultimate Guide: Top 10 Free Media Player Apps Compatible with All Platforms (Windows, macOS, Android & iOS)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-step-by-step-tutorial-discreetly-capturing-screenshots-on-bereal-no-notifications-required-updated/"><u>Ultimate Step-by-Step Tutorial: Discreetly Capturing Screenshots on BeReal (No Notifications Required) - Updated !</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-forget-the-90-pro-password-or-pattern-lock-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you forget the 90 Pro password or pattern lock</u></a></li>
<li><a href="https://win-howtos.techidaily.com/watching-avi-files-with-chromecast-three-easy-techniques/"><u>Watching AVI Files with Chromecast: Three Easy Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/xbox-one-disc-error-troubleshooting-latest-solutions-for-reading-problems-as-of-april-2024/"><u>Xbox One Disc Error Troubleshooting - Latest Solutions for Reading Problems as of April 2024</u></a></li>
</ul></div>

