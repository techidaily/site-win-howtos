---
title: Windows 10 Users, Here's How to Overcome the 'Port Reset Failed' Error with Your USB Device!
date: 2024-11-04T04:34:18.516Z
updated: 2024-11-08T06:15:55.314Z
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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857869/11832" target="_top" id="857869">
  <img src="//a.impactradius-go.com/display-ad/11832-857869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857869/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186864/12108" target="_top" id="1186864">
  <img src="//a.impactradius-go.com/display-ad/12108-1186864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186864/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2144299/7443" target="_top" id="2144299">
  <img src="//a.impactradius-go.com/display-ad/7443-2144299" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144299/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vimeo-videos.techidaily.com/new-effortless-online-video-access-via-vimeo-for-2024/"><u>[New] Effortless Online Video Access via Vimeo for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-direct-pathway-iphone-files-on-your-desktop/"><u>[Updated] In 2024, Direct Pathway IPhone Files on Your Desktop</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovate-and-revamp-your-desktop-on-win11/"><u>2024 Approved Innovate and Revamp Your Desktop on Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-solving-windows-11-and-7-ethernet-connectivity-issues/"><u>Diagnosing & Solving Windows 11 and 7 Ethernet Connectivity Issues</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/exploring-the-future-of-home-cleaning-with-the-newly-launched-ai-enhanced-eufy-x8-pro-vacuum/"><u>Exploring the Future of Home Cleaning with the Newly Launched, AI-Enhanced Eufy X8 Pro Vacuum</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-error-0x80073cf9-ultimate-guide-to-resolve-store-issues-on-windows-11/"><u>Fixing Error 0X80073CF9: Ultimate Guide to Resolve Store Issues on Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-vivo-x90s-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Vivo X90S Pattern Lock Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-fatal-error-code-1603-and-complete-the-setup-successfully/"><u>How to Resolve 'Fatal Error Code 1603' And Complete the Setup Successfully</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-itel-a05s-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Itel A05s to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205270636-immediate-fixes-for-when-your-dns-server-is-down-no-stress-required/"><u>Immediate Fixes for When Your DNS Server Is Down - No Stress Required</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-tecno-spark-20c-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Tecno Spark 20C Face Lock?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-windows-maintenance-resolving-issues-in-windows-11-via-sfcdism/"><u>Master Windows Maintenance: Resolving Issues in Windows 11 via SFC/DISM</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/premier-list-of-affordable-virtual-meetings-and-live-desktop-sharing/"><u>Premier List of Affordable Virtual Meetings & Live Desktop Sharing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211965095-recover-lost-taskbar-icons-in-windows-10-with-these-easy-troubleshooting-tips/"><u>Recover Lost Taskbar Icons in Windows 10 with These Easy Troubleshooting Tips</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-microphone-malfunctions-sony-wh-1xm3-and-wh-1xm4-on-computers/"><u>Resolving Microphone Malfunctions: Sony WH-1#XM3 and WH-1#XM4 on Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-sudden-failures-of-wireless-mouse-connectivity-in-windows-11-and-10-environments/"><u>Step-by-Step Fixes for Sudden Failures of Wireless Mouse Connectivity in Windows 11 and 10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-users-say-goodbye-to-that-troublesome-sticking-keyboard-problem/"><u>Windows Users, Say Goodbye to That Troublesome Sticking Keyboard Problem!</u></a></li>
</ul></div>

