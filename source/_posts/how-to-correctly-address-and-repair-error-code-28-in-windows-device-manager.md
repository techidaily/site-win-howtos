---
title: How to Correctly Address and Repair 'Error Code 28' In Windows Device Manager
date: 2024-10-14T20:49:28.422Z
updated: 2024-10-21T16:58:07.421Z
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1975821/19272" target="_top" id="1975821">
  <img src="//a.impactradius-go.com/display-ad/19272-1975821" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975821/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-quick-windows-surfing-guide-unveiled/"><u>[New] 2024 Approved Quick Windows Surfing Guide Unveiled</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-transcend-media-limits-selecting-top-alternatives-from-flv-to-youtubes/"><u>[New] Transcend Media Limits Selecting Top Alternatives From FLV to YouTubes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unleash-creativity-in-instagram-with-looping-tricks/"><u>[New] Unleash Creativity in Instagram with Looping Tricks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-from-black-and-white-to-richness-embracing-hdrs-power-for-2024/"><u>[Updated] From Black and White to Richness Embracing HDR's Power for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpts-evolution-interactive-dialogue-unleashed/"><u>ChatGPT's Evolution: Interactive Dialogue Unleashed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-eliminating-excessive-cpu-demand-from-svchostexe-in-windows-10-complete-walkthrough/"><u>Diagnosing and Eliminating Excessive CPU Demand From Svchost.exe in Windows 10 [Complete Walkthrough]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-remedies-for-a-rogue-computer-cursor/"><u>Effortless Remedies for a Rogue Computer Cursor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-and-solutions-when-your-surface-is-connected-but-wont-charge/"><u>Fixes & Solutions: When Your Surface Is Connected but Won't Charge</u></a></li>
<li><a href="https://win-amazing.techidaily.com/gigabyte-ethernet-driver-installation-guide-secure-it-today/"><u>Gigabyte Ethernet Driver Installation Guide – Secure It Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-your-pc-when-it-refuses-to-power-down-in-windows-10/"><u>How to Fix Your PC When It Refuses to Power Down in Windows 10</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-8-mobile-montages-androidios-screenshot-wonders/"><u>In 2024, Top 8 Mobile Montages Android/iOS Screenshot Wonders</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-mouse-pad-troubles-in-windows-87-discover-the-quick-fix/"><u>Lenovo Mouse Pad Troubles in Windows 8/7? Discover the Quick Fix!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/logitech-lifesaver-unplugging-troubleshooting/"><u>Logitech Lifesaver: Unplugging Troubleshooting</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-motorola-moto-g34-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Motorola Moto G34 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/triumphing-with-troubleshooting-a-faulty-nvidia-setup/"><u>Triumphing with Troubleshooting a Faulty NVIDIA Setup</u></a></li>
</ul></div>

