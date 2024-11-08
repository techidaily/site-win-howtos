---
title: How to Correctly Address and Repair 'Error Code 28' In Windows Device Manager
date: 2024-11-01T07:59:08.534Z
updated: 2024-11-08T01:18:31.470Z
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

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959773/19272" target="_top" id="1959773">
  <img src="//a.impactradius-go.com/display-ad/19272-1959773" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959773/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997675/19272" target="_top" id="1997675">
  <img src="//a.impactradius-go.com/display-ad/19272-1997675" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997675/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-leading-20-non-copyrighted-pubg-image-sequences/"><u>[New] 2024 Approved Leading 20 Non-Copyrighted PUBG Image Sequences</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-2024-approved-lightning-fast-windows-photo-inspector/"><u>[New] 2024 Approved Lightning-Fast Windows Photo Inspector</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-how-to-fix-obs-studio-drop-frames-issue/"><u>[Updated] How To Fix OBS Studio Drop Frames Issue?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/can-you-rely-on-ai-spotters-insights-into-zerogpts-stealth-capabilities/"><u>Can You Rely on AI Spotters? Insights Into ZeroGPT's Stealth Capabilities</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defying-expectations-wow-sets-new-standards-with-3d-acceleration/"><u>Defying Expectations: WoW Sets New Standards with 3D Acceleration</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-y78-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo Y78 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-10-igtv-channels-shaping-content-trends/"><u>In 2024, The 10 IGTV Channels Shaping Content Trends</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Poco M6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/is-netflix-down-or-not-working-fix-your-netflix-problems/"><u>Is Netflix Down or Not Working? Fix Your Netflix Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-keeping-your-device-alert-no-more-interruptions/"><u>Master the Art of Keeping Your Device Alert: No More Interruptions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-charge-problems-with-your-sony-dualshock-ps4-controller/"><u>Overcoming Charge Problems with Your Sony DualShock PS4 Controller</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/section-3b-five-factays-to-remember/"><u>Section 3B: Five Factays to Remember</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-csgo-lag-problems-top-tips-and-tricks/"><u>Solving Your CS:GO Lag Problems - Top Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-port-reset-failed-on-windows-11-when-connected-to-an-unknown-usb-device/"><u>Step-by-Step Fix for 'Port Reset Failed' On Windows 11 When Connected to an Unknown USB Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooting-tactics-for-fixing-game-crashes-in-total-war-rome-re-mastered/"><u>Ultimate Troubleshooting Tactics for Fixing Game Crashes in Total War: Rome Re-Mastered</u></a></li>
<li><a href="https://article-files.techidaily.com/unveiling-the-power-of-grading-insights-from-dr-john-doe-for-2024/"><u>Unveiling the Power of Grading Insights From Dr. John Doe for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-brightness-malfunction-solved-steps-to-regain-control/"><u>Windows 10 Brightness Malfunction Solved: Steps to Regain Control</u></a></li>
</ul></div>

