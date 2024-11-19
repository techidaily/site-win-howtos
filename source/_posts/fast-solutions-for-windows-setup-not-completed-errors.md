---
title: Fast Solutions for Windows Setup Not Completed Errors
date: 2024-11-12T21:06:14.593Z
updated: 2024-11-18T17:14:14.904Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fast Solutions for Windows Setup Not Completed Errors
excerpt: This Article Describes Fast Solutions for Windows Setup Not Completed Errors
thumbnail: https://thmb.techidaily.com/7fed1c054c54c404a50983c16bd1d7d403eb3f6cb3fe1e73cdb94850018ef126.jpg
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135412/19272" target="_top" id="2135412">
  <img src="//a.impactradius-go.com/display-ad/19272-2135412" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135412/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528681/16446" target="_top" id="1528681">
  <img src="//a.impactradius-go.com/display-ad/16446-1528681" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528681/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896510/19272" target="_top" id="1896510">
  <img src="//a.impactradius-go.com/display-ad/19272-1896510" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896510/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

<!-- affiliate ads begin -->
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
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

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068426/7443" target="_top" id="2068426">
  <img src="//a.impactradius-go.com/display-ad/7443-2068426" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068426/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-capture-and-record-a-2023-look-at-camstudios-capabilities/"><u>[New] In 2024, Capture and Record A 2023 Look at CamStudio's Capabilities</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-techniques-for-streaming-seminars-on-a-fee-free-basis-for-2024/"><u>[New] Techniques for Streaming Seminars on a Fee-Free Basis for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-elevating-videogame-recording-the-steam-methodology/"><u>2024 Approved Elevating Videogame Recording The Steam Methodology</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-professional-gear-tips-gopro-edition/"><u>2024 Approved Professional Gear Tips GoPro Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/connectivity-restored-laptop-recognizes-headphones/"><u>Connectivity Restored: Laptop Recognizes Headphones</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-a-non-responsive-left-click-on-computer-mice/"><u>Easy Fixes for a Non-Responsive Left Click on Computer Mice</u></a></li>
<li><a href="https://driver-download.techidaily.com/effortlessly-upgrade-to-latest-drivers-on-acer-predator-xb271h-screen/"><u>Effortlessly Upgrade to Latest Drivers on Acer Predator XB271H Screen</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-enable-audio-in-google-chrome-when-faced-with-no-sound-errors/"><u>How to Enable Audio in Google Chrome When Faced with 'No Sound' Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastery-over-kernel32-faults/"><u>Mastery over Kernel32 Faults</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-steam-update-challenges-how-to-ensure-successful-downloads/"><u>Overcoming Steam Update Challenges: How to Ensure Successful Downloads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-how-to-fix-an-unresponsive-google-chrome-instance/"><u>Resolving the Issue: How to Fix an Unresponsive Google Chrome Instance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-for-malfunctioning-keys-preceding-user-logon/"><u>Solution for Malfunctioning Keys Preceding User Logon</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-getting-microsoft-print-to-pdf-feature-up-and-running-on-windows-1011/"><u>Step-by-Step: Getting Microsoft Print to PDF Feature Up and Running on Windows 10/11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/streamsaver-fb-video-downloader-suite-for-2024/"><u>StreamSaver FB Video Downloader Suite for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-videographers-companion-the-ion-air-pro-3-deep-dive/"><u>The Ultimate Videographer's Companion The ION Air Pro 3 Deep Dive</u></a></li>
</ul></div>

