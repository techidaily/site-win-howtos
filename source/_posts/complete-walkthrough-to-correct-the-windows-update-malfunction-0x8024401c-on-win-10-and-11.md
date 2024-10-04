---
title: Complete Walkthrough to Correct the Windows Update Malfunction 0X8024401C on Win 10 & 11
date: 2024-09-30T02:59:12.755Z
updated: 2024-10-04T00:04:41.508Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Complete Walkthrough to Correct the Windows Update Malfunction 0X8024401C on Win 10 & 11
excerpt: This Article Describes Complete Walkthrough to Correct the Windows Update Malfunction 0X8024401C on Win 10 & 11
thumbnail: https://thmb.techidaily.com/fcc2142966c5b1ee29ff8b93fc6fb55850db39c56e2485dc6f07b17bf29f5810.jpg
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

<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-clips.techidaily.com/new-enhance-engagement-top-tools-and-tips-for-properly-tagged-videos/"><u>[New] Enhance Engagement Top Tools and Tips for Properly Tagged Videos</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-tech-tutorial-exporting-and-storing-your-snaps-safely-for-2024/"><u>[New] Tech Tutorial Exporting and Storing Your Snaps Safely for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/outubes-time-loop-video-recovery-explained-for-2024/"><u>[New] YouTube's Time Loop Video Recovery Explained for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-mouse-scroll-wheel-jumps-win-1011/"><u>[SOLVED] Mouse Scroll Wheel Jumps Win 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/2024-solutions-overcoming-miracast-not-supported-on-this-device-error/"><u>2024 Solutions: Overcoming 'Miracast Not Supported on This Device' Error</u></a></li>
<li><a href="https://iphone-location.techidaily.com/3-smart-and-simple-ways-to-change-home-address-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>3 Smart and Simple Ways to Change Home Address on Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-turn-on-bluetooth-on-windows-1110-solved/"><u>How to Turn on Bluetooth on Windows 11/10 [Solved]</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-realme-narzo-60x-5g-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Realme Narzo 60x 5G Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-stuck-screens-steps-to-successfully-turn-off-windows-10-on-laptops-and-desktops/"><u>Overcoming Stuck Screens: Steps to Successfully Turn Off Windows 10 on Laptops and Desktops</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/smartwatch-evolution-through-conversation-gpts-top-6-innovations/"><u>Smartwatch Evolution Through Conversation: GPT's Top 6 Innovations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-winupdate-error-0x80070002-in-a-jiffy-step-by-step-tutorial/"><u>Solve WinUpdate Error 0X80070002 in a Jiffy - Step-by-Step Tutorial</u></a></li>
<li><a href="https://fix-guide.techidaily.com/solved-warning-camera-failed-on-meizu-21-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-troubleshooting-for-windows-11-and-10s-error-code-0x80072f8f/"><u>Step-by-Step Troubleshooting for Windows 11 and 10'S Error Code: 0X80072F8F</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-to-do-when-your-microsoft-surface-shows-its-plugged-in-yet-wont-charge/"><u>What to Do When Your Microsoft Surface Shows It's Plugged In, Yet Won't Charge</u></a></li>
</ul></div>

