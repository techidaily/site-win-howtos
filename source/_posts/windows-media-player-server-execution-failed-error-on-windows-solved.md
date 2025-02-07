---
title: Windows Media Player Server Execution Failed Error on Windows [Solved]
date: 2025-02-01T06:24:25.264Z
updated: 2025-02-07T00:01:40.585Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows Media Player Server Execution Failed Error on Windows [Solved]
excerpt: This Article Describes Windows Media Player Server Execution Failed Error on Windows [Solved]
thumbnail: https://thmb.techidaily.com/755e6887211290e7a3605c3c466915e29d575ef749d02f8bbbc7b8223952f6c6.jpg
---

## How to Overcome Unexpected Shutdown (Error 1067) on Your Windows PC - Now Solved

 Windows background services enable Windows features function properly. If some errors happen to services, you will face trouble then. Here in this article, we will be telling you how to fix one of the errors occurring to Windows services — **Error 1067: The process terminated unexpectedly** . Follow the tried-and-true solution below.

## Step 1

 On you keyboard, press**Windows** key +**R** key together to open Run box.  
 Type**regedit** in the box and hit**Enter** to open Registry Editor window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/2-1.png)

## Step 2

 Click **Yes**  when prompted by UAC (User Account Control).

![](https://images.drivereasy.com/wp-content/uploads/2017/06/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Step 3\

 On Registry Editor window, expand **HKEY\_LOCAL\_MACHINE**  \> **SYSTEM**  \> **CurrentControlSet**  \> **Services** .

![](https://images.drivereasy.com/wp-content/uploads/2017/06/4-1.png)

## **Step 4.**

 Find and**right-click** on your service with error 1067 under Services dialog.  
 Then choose**Export** .  
 Choose a place to save it on the pop-up window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/5-1.png)

## **Step 5.**

 Back on Registry Editor window,**right-click** on the same service.  
 This time choose**Delete** .  
 Then close the window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/6-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Step 6.**

 Type**cmd** in the search box.  
 Right-click on**Command Prompt** to choose**Run as administrator** .

![](https://www.drivereasy.com/wp-content/uploads/2023/12/win11-cmd-Run-as-administrator.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Step 7.**

 Click **Yes**  when prompted by UAC.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/10-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Step 8.**

 Type**sfc /scannow** in the pop-up window.  
 Press**Enter** to run it.  
 Wait till verification**100%** complete.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/11-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Step 9.**

 Close the window and**restart** your computer.  
 Then find your service file saved at Step 4.  
 Right-click on it to choose**Merge** .  
 Click **Yes**  when prompted by UAC.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/7-1.png)

## **Step 10.**

 Open a Run box to type **services.msc**  in it and press **Enter**  to open Services window.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/8.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Step 11.**

 On Services window, find and right-click on your service.  
 Then click**Start** and close the window.  
 See if the error still exists.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/9.png)

That’s it. Hope it did help you.

For any confusion, please feel free to leave your comment below, thanks.

* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://desktop-recording.techidaily.com/new-capture-and-save-your-desktop-free-ways-on-windows/"><u>[New] Capture & Save Your Desktop - Free Ways on Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-ps4-broadcast-simplified-detailed-steps-using-obs/"><u>[New] In 2024, PS4 Broadcast Simplified Detailed Steps Using OBS</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-audio-assimilation-for-inshot-projects/"><u>[Updated] Audio Assimilation for InShot Projects</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-discovering-the-most-engaging-facebook-vids/"><u>[Updated] Discovering the Most Engaging Facebook Vids</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-samsung-galaxy-s24-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Samsung Galaxy S24 to iPhone | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/all-systems-green-issue-with-response-detected/"><u>All Systems Green: Issue with Response Detected</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-your-disabled-apple-iphone-13-mini-without-itunes-in-5-ways-by-drfone-ios/"><u>In 2024, Unlock Your Disabled Apple iPhone 13 mini Without iTunes in 5 Ways</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205548832-local-security-defenses-restored-ensure-safe-operations-today/"><u>Local Security Defenses Restored – Ensure Safe Operations Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-the-hassle-of-error-0x80072f8f-effective-fixes-for-modern-windows-users/"><u>Overcome the Hassle of Error 0X80072F8f - Effective Fixes for Modern Windows Users</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/er-the-future-of-youtube-content-with-tubebuddy/"><u>Pioneer the Future of YouTube Content with TubeBuddy</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/scripting-significant-soliloquies-for-2024/"><u>Scripting Significant Soliloquies for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/steps-to-reduce-100-drive-consumption-in-windows-11/"><u>Steps to Reduce 100% Drive Consumption in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-resolving-problems-with-your-windows-system-updates/"><u>Successfully Resolving Problems with Your Windows System Updates</u></a></li>
</ul></div>

