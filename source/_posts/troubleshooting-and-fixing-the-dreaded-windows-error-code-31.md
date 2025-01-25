---
title: Troubleshooting and Fixing the Dreaded Windows Error Code 31
date: 2025-01-21T16:49:09.840Z
updated: 2025-01-25T17:31:09.302Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Fixing the Dreaded Windows Error Code 31
excerpt: This Article Describes Troubleshooting and Fixing the Dreaded Windows Error Code 31
thumbnail: https://thmb.techidaily.com/c773b247e1e0895c35ac3965c0957524900af663f812d6e184693495dab0728b.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-accelerating-instagram-videos-mobile-and-desktop-tips/"><u>[Updated] In 2024, Accelerating Instagram Videos Mobile & Desktop Tips</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-innovative-ways-to-log-ps3-competitive-sessions-for-2024/"><u>[Updated] Innovative Ways to Log PS3 Competitive Sessions for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-quick-fixes-to-keep-your-photos-app-fixed-on-win-11/"><u>[Updated] Quick Fixes to Keep Your Photos App Fixed on Win 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-visualtwitter-quickly-download-and-share-videos-on-mobile/"><u>[Updated] VisualTwitter Quickly Download and Share Videos on Mobile</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-prime-ringtone-reserves-retro-rhythms-online/"><u>2024 Approved Prime Ringtone Reserves Retro Rhythms Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726026703106-720p1080p/"><u>高解像度への移行 - 720Pビデオを1080pにアップコンバートする手順</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028801534-usbdvd/"><u>記憶の永遠の保存 – USBメモリへのライブDVD複製方法</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726026518358-wonderfox/"><u>現在ある限り、WonderFoxで受けられるオンライン上の専門知識と最新ニュース</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028255517-android/"><u>Androidでの音楽再生がうまくいかない時、その理由と解決策を詳しく見てみよう</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-lock-apps-on-tecno-camon-20-premier-5g-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Tecno Camon 20 Premier 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://win-blog.techidaily.com/resident-evil-village-pc-performance-overcoming-fps-dips/"><u>Resident Evil Village PC Performance: Overcoming FPS Dips</u></a></li>
<li><a href="https://win-help.techidaily.com/sandisk-ssdwindows-2/"><u>Sandisk SSDをWindowsで消去するための簡単マニュアル - 2手順</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-tech-through-artificial-intelligence/"><u>Transforming Windows Tech Through Artificial Intelligence</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726028571800-5/"><u>ビデオ撮影者が選ぶ5つのおすすめ動画文字化シーンアプリ - 見やすく、使い勝手良し！</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726026739742-dailymotion/"><u>ブラウザでDailymotion動画を安全に保存するためのテクニック</u></a></li>
</ul></div>

