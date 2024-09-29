---
title: Complete Walkthrough to Correct the Windows Update Malfunction 0X8024401C on Win 10 & 11
date: 2024-09-26T00:08:16.086Z
updated: 2024-09-28T23:11:29.168Z
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
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

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938745/19272" target="_top" id="1938745">
  <img src="//a.impactradius-go.com/display-ad/19272-1938745" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938745/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/1938693/19272" target="_top" id="1938693">
  <img src="//a.impactradius-go.com/display-ad/19272-1938693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938693/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012434/19272" target="_top" id="2012434">
  <img src="//a.impactradius-go.com/display-ad/19272-2012434" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012434/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-auditory-appeal-modifying-voices-in-instagrams-storytelling-for-2024/"><u>[New] Auditory Appeal Modifying Voices in Instagram's Storytelling for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-bi-panel-screen-transcription/"><u>[New] Bi-Panel Screen Transcription</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-boosting-your-youtube-views-a-strategy-guide/"><u>[New] Boosting Your YouTube Views A Strategy Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-how-to-use-filters-on-instagram-in-2024/"><u>[New] How to Use Filters on Instagram, In 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-efficient-screen-saving-solutions-in-windows-8-edition-for-2024/"><u>[Updated] Efficient Screen Saving Solutions in Windows 8 Edition for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-step-by-step-guide-the-most-effective-7-artwork-to-nft-services/"><u>2024 Approved A Step-by-Step Guide - The Most Effective 7 Artwork-to-NFT Services</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-triller-unveiled-the-non-tiktok-tiktok-alternatives-secrets/"><u>2024 Approved Triller Unveiled The Non-TikTok, TikTok Alternative's Secrets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-a-damaged-volume-error-code-0x80071ac3-a-troubleshooting-guide/"><u>Dealing with a Damaged Volume (Error Code 0X80071AC3) - A Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/device-silence-amidst-configuration-success/"><u>Device Silence Amidst Configuration Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-failed-renderer-start-up-in-your-browser-new-patch-released/"><u>Fixing the Failed Renderer Start-Up in Your Browser (New Patch Released)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-updated-drivers-for-your-hp-deskjet-2540-free-downloads-available-now/"><u>Get the Updated Drivers for Your HP DeskJet 2540 - FREE Downloads Available Now!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-touchscreen-troubleshooting-in-windows-10-a-comprehensive-5-way-approach/"><u>Mastering Touchscreen Troubleshooting in Windows 10: A Comprehensive 5-Way Approach</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-service-failed-problem-with-your-windows-1011-account-expert-solutions/"><u>Overcoming 'Service Failed' Problem with Your Windows 10/11 Account - Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-11-night-light-problems-a-comprehensive-tutorial/"><u>Solving Windows 11 Night Light Problems - A Comprehensive Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-file-retrieval-tips-restoring-missing-privileges-successfully/"><u>Steam File Retrieval Tips: Restoring Missing Privileges Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-how-to-fix-computer-not-closing-windows-10/"><u>Troubleshooting Steps: How To Fix Computer Not Closing Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-resolving-the-dreaded-0x800f0922-update-glitch-in-windows-10/"><u>Troubleshooting Tips for Resolving the Dreaded 0X800f0922 Update Glitch in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-door-with-elongated-pin-strategies-for-windows-1011/"><u>Unlock the Door with Elongated Pin Strategies for Windows 10/11</u></a></li>
</ul></div>

