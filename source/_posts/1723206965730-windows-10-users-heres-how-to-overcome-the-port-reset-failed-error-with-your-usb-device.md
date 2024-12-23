---
title: Windows 10 Users, Here's How to Overcome the 'Port Reset Failed' Error with Your USB Device!
date: 2024-12-18T23:40:42.151Z
updated: 2024-12-22T16:36:25.630Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/new-effortless-video-capture-using-screencastify-app/"><u>[New] Effortless Video Capture Using Screencastify App</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-how-to-choose-between-youtubers-game-entrance-tutorials-cost-included/"><u>[New] In 2024, How to Choose Between Youtubers' Game Entrance Tutorials (Cost Included?)</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-livechat-recorder-pro-hd-for-2024/"><u>[New] LiveChat Recorder Pro HD for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-best-free-screencasting-solutions-for-everyone/"><u>[Updated] Best Free Screencasting Solutions for Everyone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/crafting-compelling-online-livestreams-from-a-single-source/"><u>Crafting Compelling Online Livestreams From a Single Source</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/enhanced-performance-via-cookiebot-integration/"><u>Enhanced Performance via Cookiebot Integration</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-access-denied-by-device-path-error-in-windows-systems/"><u>How to Resolve the 'Access Denied by Device Path' Error in Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-malfunction-in-windows-11-heres-the-solution-to-unresponsive-characters/"><u>Keyboard Malfunction in Windows 11? Here's the Solution to Unresponsive Characters!</u></a></li>
<li><a href="https://win-bytes.techidaily.com/losung-fur-systemwiederherstellungskompatibilitat-und-unbekannter-fehler-code-0x80070-groovytxt-entschlusselt/"><u>Lösung Für Systemwiederherstellungskompatibilität Und Unbekannter Fehler (Code 0X80070 groovy.txt) [Entschlüsselt]</u></a></li>
<li><a href="https://win-able.techidaily.com/master-the-stability-of-metro-exoduss-pc-enhanced-edition-crashes-no-more/"><u>Master the Stability of Metro Exodus's PC Enhanced Edition: Crashes No More!</u></a></li>
<li><a href="https://data-wizards.techidaily.com/reviving-lost-visual-stories-in-videos/"><u>Reviving Lost Visual Stories in Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-connection-refused-error-on-your-device-a-visual-guide/"><u>Solving the Issue of Connection Refused Error on Your Device – A Visual Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-windows-11-mic-troubles-expert-tips-for-restoring-voice-input/"><u>Tackling Windows 11 Mic Troubles - Expert Tips for Restoring Voice Input</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-disk-read-errors-on-your-windows-10-pc-today/"><u>Troubleshoot and Fix Disk Read Errors on Your Windows 10 PC Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-laptop-that-wont-charge-simple-steps-for-an-immediate-fix/"><u>Troubleshooting a Laptop That Won't Charge: Simple Steps for an Immediate Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-windows-update-error-code-0x802eb3ae/"><u>Ultimate Guide: Resolving Windows Update Error Code 0X802eb3ae</u></a></li>
</ul></div>

