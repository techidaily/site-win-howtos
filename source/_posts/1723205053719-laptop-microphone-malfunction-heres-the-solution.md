---
title: Laptop Microphone Malfunction? Here's the Solution!
date: 2025-01-20T17:30:50.209Z
updated: 2025-01-25T16:58:23.070Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Laptop Microphone Malfunction? Here's the Solution!
excerpt: This Article Describes Laptop Microphone Malfunction? Here's the Solution!
thumbnail: https://thmb.techidaily.com/e92d1325fd1f2f901796fdd1123502e68b5122756c762090fd4b289d5054368b.jpg
---

## Diagnostic Policy Service Malfunction? Here's the Solution

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)

3) Click the **Update**  button next to a flagged network adapter driver to automatically download and install the correct version of this driver (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **Pro** version – you’ll be prompted to upgrade when you click Update All).

 Driver Easy requires network connection to update drivers. If your windows can’t access the Internet, please use the Offline Scan feature of Driver Easy to help you.

 4) After updating your network adapter driver, please restart your computer.

 5) Run the Network Diagnostics to see if it goes well.

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
<li><a href="https://fox-blue.techidaily.com/new-ai-powered-virtual-patient-interactions/"><u>[New] AI-Powered Virtual Patient Interactions</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-discovering-8-prime-video-advancement-aids/"><u>[New] In 2024, Discovering 8 Prime Video Advancement Aids</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-influencer-insight-essential-hashtags-for-maximum-impact/"><u>[New] In 2024, Influencer Insight Essential Hashtags for Maximum Impact</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-tweeting-tides-the-rising-wave-of-viral-videos/"><u>[Updated] Tweeting Tides The Rising Wave of Viral Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-how-to-optimize-zoom-effectiveness-during-your-google-meet/"><u>2024 Approved How to Optimize Zoom Effectiveness During Your Google Meet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movqt-movavi-qt/"><u>手軽にフリーでMOVからQTへのデジタル変換 - Movavi QTコンバータ</u></a></li>
<li><a href="https://win-howtos.techidaily.com/webcr2jpeg-movavi/"><u>無料WEBサービスでCR2フォーマットをJPEGへ変換する方法 - Movaviコンバーター</u></a></li>
<li><a href="https://win-howtos.techidaily.com/cambie-mov-a-avi-online-sin-coste-con-moovavi/"><u>Cambie MOV a AVI Online Sin Coste Con Moovavi</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-explore-and-review-every-application-az-screenshotters-way/"><u>In 2024, Explore & Review Every Application - AZ Screenshotter's Way</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-camon-20-pro-5g-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Tecno Camon 20 Pro 5G to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-htc-u23-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For HTC U23</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-vivid-8-enhancements-to-transform-your-live-footage/"><u>In 2024, Vivid 8 Enhancements to Transform Your Live Footage</u></a></li>
<li><a href="https://network-issues.techidaily.com/leap-over-delays-in-your-gaming/"><u>Leap Over Delays in Your Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movavi-pourquoi-opter-pour-cette-solution-video/"><u>Movavi: Pourquoi Opter Pour Cette Solution Vidéo?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726227687647-mpegmp4/"><u>MPEG到MP4自由下載的移動維護 - 無限可能化</u></a></li>
<li><a href="https://win-howtos.techidaily.com/online-free-conversion-transforming-flv-and-aiff-files-without-cost-movavi/"><u>Online FREE Conversion: Transforming FLV & AIFF Files Without Cost - Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/swiftly-switch-flac-audiovideo-to-mkv-using-our-complimentary-web-based-tool/"><u>Swiftly Switch FLAC Audio/Video to MKV Using Our Complimentary Web-Based Tool</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tout-de-suite-gratuit-transformez-votre-fichier-aiff-en-format-mov-sur-linternet-avec-movieave/"><u>Tout De Suite Gratuit : Transformez Votre Fichier AIFF en Format MOV Sur L'internet Avec Movieave</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wi-fi-qt-online-movavi/"><u>무료 Wi-Fi용 QT 모항을 바꿀 수 있는 Online 도구 - Movavi</u></a></li>
</ul></div>

