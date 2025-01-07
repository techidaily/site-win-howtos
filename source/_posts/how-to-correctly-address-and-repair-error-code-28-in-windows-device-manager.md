---
title: How to Correctly Address and Repair 'Error Code 28' In Windows Device Manager
date: 2024-12-31T22:44:57.159Z
updated: 2025-01-07T04:16:00.914Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-learn-to-turn-videos-on-the-fly-using-vlc/"><u>[New] 2024 Approved Learn to Turn Videos on the Fly Using VLC</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-inside-tips-for-maximizing-your-creator-studio-potential/"><u>[Updated] In 2024, Inside Tips for Maximizing Your Creator Studio Potential</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-playback-problem-why-cant-i-watch-video-on-sony-a6400/"><u>[Updated] In 2024, Playback Problem Why Can't I Watch Video on Sony A6400?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-ultimate-list-of-prime-15-cameras-for-vloggers/"><u>[Updated] The Ultimate List of Prime 15 Cameras for Vloggers</u></a></li>
<li><a href="https://some-tips.techidaily.com/apple-revamps-personas-with-the-arrival-of-visionos-update-discover-additional-improvements-detailed-by-zdnet/"><u>Apple Revamps Personas with the Arrival of VisionOS Update - Discover Additional Improvements Detailed by ZDNET</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-methods-to-reduce-ntoskrnlexe-load/"><u>Effective Methods to Reduce Ntoskrnl.exe Load</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-fixes-for-handling-specified-module-could-not-be-found-errors-on-windowsmac/"><u>Efficient Fixes for Handling 'Specified Module Could Not Be Found' Errors on Windows/Mac</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-restoring-functionality-to-your-dells-defective-usb-interface/"><u>Expert Tips for Restoring Functionality to Your Dell's Defective USB Interface</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-windows-cannot-start-device-error-for-dvdcd-rom-in-windows-11-a-step-by-step-troubleshooting-tutorial/"><u>Fix 'Windows Cannot Start Device' Error for DVD/CD-ROM in Windows 지원(11): A Step-by-Step Troubleshooting Tutorial</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-xiaomi-by-fonelab-android-recover-video/"><u>How to recover old videos from your Xiaomi</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-troubleshoot-and-repair-frequent-iphone-airpods-connection-drops-top-11-tips/"><u>How to Troubleshoot and Repair Frequent iPhone-AirPods Connection Drops: Top 11 Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-launch-failures-a-fix-for-the-opening-failed-geforce-experience-problem/"><u>Overcoming Launch Failures: A Fix for the 'Opening Failed' GeForce Experience Problem</u></a></li>
<li><a href="https://win-blog.techidaily.com/qt-wmv-online-gratis-conversion-tool/"><u>QT WMV파일을 깨끗한 방식대로 구조화된 코드 쉼표 및 새 형식으로 바꾸기: Online Gratis Conversion Tool</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-to-overcome-pasting-obstacles-in-windows-11/"><u>Step-by-Step Solutions to Overcome Pasting Obstacles in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-creme-de-la-creme-of-vr-development-talent/"><u>The Crème De La Crème of VR Development Talent</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-non-functional-dell-laptop-keys/"><u>Troubleshooting Guide: Fixing Non-Functional Dell Laptop Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-fixed-youtube-sound-problem-for-windows-1amousers-and-macos-users/"><u>Troubleshooting the Fixed YouTube Sound Problem for Windows 1amoUsers and MacOS Users</u></a></li>
</ul></div>

