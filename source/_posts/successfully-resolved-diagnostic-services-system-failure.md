---
title: "Successfully Resolved: Diagnostic Services System Failure"
date: 2024-12-03T19:39:28.994Z
updated: 2024-12-07T21:51:18.040Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Successfully Resolved: Diagnostic Services System Failure"
excerpt: "This Article Describes Successfully Resolved: Diagnostic Services System Failure"
thumbnail: https://thmb.techidaily.com/ab68550bed8939ff878aaece9b28e90d8b0465006aaa80a48dab2ef20ecc47cd.jpg
---

## Resolving 'Diagnostics Policy Service Is Offline – Here’s What To Do

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

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

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
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-step-by-step-guide-to-making-spectacular-slow-motion-images-for-instagram/"><u>[Updated] 2024 Approved Step-by-Step Guide to Making Spectacular Slow Motion Images for Instagram</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-efficiently-downloading-youtube-sections-in-minutes/"><u>[Updated] Efficiently Downloading YouTube Sections in Minutes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-art-of-playback-anarchy-youtube-playlists-unordered-again-for-2024/"><u>[Updated] The Art of Playback Anarchy YouTube Playlists Unordered Again for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/vob-asf-movavi/"><u>網路直接 VOB 到 ASF 無成本轉化 - 使用 Movavi 視頻工具</u></a></li>
<li><a href="https://tech-haven.techidaily.com/begin-your-journey-with-the-advanced-ai-powered-search-tool-bing-by-microsoft/"><u>Begin Your Journey with the Advanced AI-Powered Search Tool – Bing by Microsoft</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comment-decouper-des-clips-dans-une-video-avec-le-logiciel-vlc/"><u>Comment Découper Des Clips Dans Une Vidéo Avec Le Logiciel VLC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/convert-opus-files-to-mp3-for-free-with-movavis-web-based-converter-service/"><u>Convert OPUS Files to MP3 for Free with Movavi's Web-Based Converter Service</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decouvrez-les-12-meilleures-applications-denregistrement-voip-pour-skype-sous-mac-selectionne-par-movavi/"><u>Découvrez Les 12 Meilleures Applications D'enregistrement VoIP Pour Skype Sous Mac, Sélectionné Par Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/discover-exceptional-gratuitous-and-premium-whatsapp-emoji-design-tools-top-selections/"><u>Discover Exceptional Gratuitous & Premium WhatsApp Emoji Design Tools - Top Selections</u></a></li>
<li><a href="https://common-error.techidaily.com/effortlessly-resolve-kb4056892-a-user-friendly-guide-to-installing-windows-10-updates/"><u>Effortlessly Resolve KB4056892: A User-Friendly Guide to Installing Windows 10 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/google-hangouts-ingangstappen-6-kostenloze-methoden-via-movavi/"><u>Google Hangouts Ingangstappen: 6 Kostenloze Methoden via Movavi</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-xiaomi-14-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-track-imei-number-of-oppo-find-x7-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Oppo Find X7 Through Google Earth?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-elevate-your-contents-visibility-with-these-gadgets/"><u>In 2024, Elevate Your Content's Visibility with These Gadgets</u></a></li>
<li><a href="https://win-howtos.techidaily.com/maximize-savings-with-movavi-kortingscode-exclusive-deals-inside/"><u>Maximize Savings with Movavi-Kortingscode – Exclusive Deals Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tapez-vous-des-idees-transformez-votre-video-rapidement-avec-les-meilleurs-logiciels-de-montage/"><u>Tapez Vous Des Idées ? - Transformez Votre Vidéo Rapidement Avec Les Meilleurs Logiciels De Montage</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/top-solutions-fixing-the-persistent-black-screen-problem-in-zoom/"><u>Top Solutions: Fixing the Persistent Black Screen Problem in Zoom</u></a></li>
</ul></div>

