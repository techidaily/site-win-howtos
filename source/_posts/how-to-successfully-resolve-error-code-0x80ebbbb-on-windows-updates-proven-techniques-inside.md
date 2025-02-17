---
title: How to Successfully Resolve Error Code 0X80ebbbb on Windows Updates - Proven Techniques Inside
date: 2025-02-12T20:23:11.352Z
updated: 2025-02-16T21:17:33.533Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Successfully Resolve Error Code 0X80ebbbb on Windows Updates - Proven Techniques Inside
excerpt: This Article Describes How to Successfully Resolve Error Code 0X80ebbbb on Windows Updates - Proven Techniques Inside
thumbnail: https://thmb.techidaily.com/1bbd0a3f8dc1d9288d108f379c03c690ea0ce4f3426715024680a4a4a0f123c3.jpg
---

## How to Successfully Resolve Error Code 0X80ebbbb on Windows Updates - Proven Techniques Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-capturing-your-mi-11-screens-step-by-step/"><u>[New] In 2024, Capturing Your Mi 11 Screens - Step by Step</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-sculpting-soundscapes-gradual-volume-reduction/"><u>[Updated] Sculpting Soundscapes Gradual Volume Reduction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-solutions-how-to-fix-werfaultexe-application-errors-on-your-pc-running-windows/"><u>Effortless Solutions: How to Fix WerFault.exe Application Errors on Your PC Running Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-troubleshooting-for-persistent-stop-errors-in-hamachi-connection-services/"><u>Essential Troubleshooting for Persistent Stop Errors in Hamachi Connection Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-getting-your-hp-laptops-webcam-up-and-working-with-windows-11/"><u>Expert Advice: Getting Your HP Laptop's Webcam Up and Working with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-broken-updown-keys-on-your-keyboard-expert-advice-here/"><u>Fix Broken Up/Down Keys on Your Keyboard – Expert Advice Here!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixes-for-non-responsive-custom-settings-in-account/"><u>Fixes for Non-Responsive Custom Settings in Account</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-call-of-duty-wwii-error-4220-heres-your-complete-troubleshooting-solution/"><u>Fixing Call of Duty WWII Error 4220? Here's Your Complete Troubleshooting Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-disk-read-error-issue-in-windows-11-a-step-by-step-guide/"><u>Fixing the 'Disk Read Error' Issue in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-easily-correct-the-windows-update-issue-error-80000e/"><u>How to Easily Correct the Windows Update Issue (Error 80^000E)</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/how-to-effortlessly-move-concealed-images-from-iphone-to-pc-with-fonebackup/"><u>How to Effortlessly Move Concealed Images From iPhone to PC with FoneBackup</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-how-to-choose-the-background-music-for-the-trailer/"><u>In 2024, How to Choose the Background Music for the Trailer</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-macwebcam-tutorial-filming-basics-decoded/"><u>In 2024, MacWebCam Tutorial Filming Basics Decoded</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-infinix-note-30-vip-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Infinix Note 30 VIP</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-trailer-magic-top-video-editing-software-for-mac-and-pc/"><u>New Trailer Magic Top Video Editing Software for Mac and PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/soundless-speed-heres-how-to-get-the-audio-back-in-forza-horizon-4/"><u>Soundless Speed? Here's How to Get the Audio Back in Forza Horizon ⁩4!₭</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/superior-virtual-music-showcase-for-2024/"><u>Superior Virtual Music Showcase for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-essentials-of-net-neutrality-for-a-free-and-open-internet/"><u>The Essentials of Net Neutrality for a Free and Open Internet</u></a></li>
<li><a href="https://screen-recording.techidaily.com/win-11-guide-to-storing-mov-files-effectively/"><u>Win 11 Guide to Storing .mov Files Effectively</u></a></li>
</ul></div>

