---
title: Resolving the 'Widevine Content Decryption Unable' Problem in Windows Environments
date: 2024-12-01T22:00:24.180Z
updated: 2024-12-07T17:39:51.767Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving the 'Widevine Content Decryption Unable' Problem in Windows Environments
excerpt: This Article Describes Resolving the 'Widevine Content Decryption Unable' Problem in Windows Environments
thumbnail: https://thmb.techidaily.com/6d3bb4c433103a9800faaf6de96c171f6d26a01b47da5a3ba04abf6fa06e5e49.jpeg
---

## Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7be8093704.jpg)

 Your computer startup very slow? or you cannot log in Windows on your computer with the standard user account? After you log in with an administrative account, you’re seeing an error saying:

**Failed to connect to a windows services**
  
 **Windows could not connect to the System Event Notification Service service.**

 I know you’re likely frustrating. But don’t worry. Usually it’s easy to solve out. Read on to see how…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Try these fixes

 The methods below have helped other users solve the problem. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. **[Check the setting of System Event Notification Service on your computer](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset your Winsock Catalog](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your video card driver](https://tools.techidaily.com/drivereasy/download/)**
4. **[Uninstall the KB2952664 update](https://tools.techidaily.com/drivereasy/download/)**
5. [**Remove klhkum.dll**](https://tools.techidaily.com/drivereasy/download/)

 The following screenshots are from Windows 10\. But you can also follow the steps if you’re having the problem on Windows 7.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Fix 1: Check the setting of System Event Notification Service on your computer

 You may have the problem due to the incorrect setting of System Event Notification Service.  
 Follow these steps to modify the setting:

1. On your keyboard, hold down the**Windows logo key** and**R** to invoke the Run box.
2. Type**services.msc** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf596c06c.jpg)
3. Right-click**System Event Notification Service** , then select**Restart** . If Restart grayed out, click**Start** instead.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf9e2c9b8.jpg)
4. Right-click System Event Notification Service again, this time select**Properties** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bfcea31f4.jpg)
5. Set the**Startup type** to**Automatic** . Then click **Apply**  \> **OK** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c08c50e91.jpg)

 Restart your computer to see if the error has gone. If you still see the error, you have something else to try…

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Fix 2: Reset your Winsock Catalog

 You very likely have the problem on your computer that joins in a domain network. You could have problem due to some interference of your Winsock Catalog setting.

Follow these steps to reset your Winsock Catalog:

1. On your keyboard, hold down the**Windows logo key** and press**R** to invoke the Run box.
2. Type**cmd** , then press**Shift + Ctrl + Enter** keys together.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c0804d3b9.jpg)
3. An elevated Command Prompt would be open. Type the following command and press Enter.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**netsh winsock reset**

 Restart your computer to see if the error has gone. If you still see the error, don’t worry, move onto the next methods.  
 If resetting Winsock worked temporarily, you can move to Fix 5.

---

### Fix 3: Update your video card driver

 You could probably encounter this error if the video card driver on your computer is outdated, incompatible or corrupt. So you should**update your video card driver** to see if it fixes your problem. If you don’t have the time, patience or skills to update the driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to be troubled by the wrong driver you would be downloading, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the**FREE** or the**Pro version** of Driver Easy. But with the Pro version it takes just 2 steps (and you get**full support and a 30-day money back guarantee** ):

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c1c42f3f2.jpg)
3. C  lick **Update All** to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All).  

**Note** : You can do it for free if you like, but it’s partly manual.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2297ff06.jpg)

 Restart your computer to see if the error has gone. If the error persists, don’t give up hope, see if the last method could help you…

---

### Fix 4: Uninstall the KB2952664 update

 According to many users’ report, this error could be due to the**KB2952664** Windows Update. If none of the methods above helps you, go with the following steps to**uninstall the KB2952664 update** on your computer:

1. On your keyboard, press the**Windows logo key** and**R** to invoke the Run box.
2. Type**control** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c29a46965.jpg)
3. Select**Uninstall a program** under**Programs** when**View by Category** selected.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2c7bbb7b.jpg)
4. Click View installed updates.  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2f3ae739.jpg)
5. Find and right-click the update with KB2952664, then Uninstall.

Restart your computer to see if the error has gone.

---

### Fix 5: Remove klhkum.dll

 If you have to reset Winsock tens of times a day, you need to try this method. What you should do is checking whether you have “klhkum.dll” or not.

 klhkum.dll’s description is “**System Interceptors PDK usermode service interceptor** ” and it’s intercepting the system when it shouldn’t.  
 So how to remove it? Follow the guide:

1. Press**Ctrl+Shift+Esc** to open the Task Manager.
2. Click the**Startup** tab and find**klhkum.dll** process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-52-10.jpg)
3. Right-click on it and choose**Disable** . You can also open its file location and delete it permanently.  

![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-55-36.jpg)
4. Restart your computer to see if the error has gone.

 One more tip: If you’re using Kaspersky security software and possibly on Windows 7, you need to turn off Kaspersky manually to fix the issue.

---

 Tada! Hopefully this helps. Feel free to comment below with your own experiences.

* [error](https://tools.techidaily.com/drivereasy/download/)
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-24-hour-film-size-gb-measurement-guide/"><u>[New] 2024 Approved 24-Hour Film Size GB Measurement Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-microvid-viewer-analysis-and-comparison-tools/"><u>[New] MicroVid Viewer Analysis & Comparison Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-navigating-the-world-of-instagram-endorsements-five-essential-steps-for-2024/"><u>[Updated] Navigating the World of Instagram Endorsements Five Essential Steps for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mobile-video-experience-review-report/"><u>2024 Approved Mobile Video Experience Review Report</u></a></li>
<li><a href="https://win-howtos.techidaily.com/convertidor-libre-y-descentralizado-para-cambiar-flac-a-wav-por-movavi-sin-pagos/"><u>Convertidor Libre Y Descentralizado Para Cambiar FLAC a WAV Por Movavi - Sin Pagos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/convertir-en-ligne-au-format-ogv-a-partir-dogg-pour-rien-service-gratuite-movavi/"><u>Convertir en Ligne Au Format OGV À Partir D'OGG Pour Rien - Service Gratuite Movavi</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-failed-dvd-movie-playback-on-windows-pcs/"><u>Diagnosing and Repairing Failed DVD Movie Playback on Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/earn-1000-fast-enter-movavi-scholarship-contest-in-under-two-minutes/"><u>Earn $1,000 Fast - Enter Movavi Scholarship Contest in Under Two Minutes!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/free-online-conversion-transform-nef-files-to-jpeg-format-with-ease-using-movavi/"><u>Free Online Conversion: Transform NEF Files to JPEG Format with Ease Using Movavi</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-show-wi-fi-password-on-samsung-galaxy-f14-5g-by-drfone-android/"><u>How to Show Wi-Fi Password on Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-the-apple-ipad-mini-5-compact-device-immense-capabilities/"><u>In-Depth Analysis of the Apple iPad Mini 5: Compact Device, Immense Capabilities</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/superior-tools-for-watching-fb-videos-for-2024/"><u>Superior Tools for Watching FB Videos for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-15-video-editing-apps-of-2024-free-and-paid-options-for-ultimate-visual-stability/"><u>Top 15 Video Editing Apps of 2024: Free & Paid Options for Ultimate Visual Stability</u></a></li>
<li><a href="https://win-howtos.techidaily.com/transcode-mp4-files-to-3gpp-streaming-quality-videos-for-free-with-movavis-web-service/"><u>Transcode MP4 Files to 3GPP Streaming Quality Videos For Free with Movavi's Web Service</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-cutting-edge-video-editing-on-mac-the-top-software-of/"><u>Updated Cutting-Edge Video Editing on Mac The Top Software Of</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1726228274213-mpeg-asf-movavi/"><u>제공자가 아닌 웹사이트에서 무료 MPEG ASF 영상 데이터 교체 - Movavi</u></a></li>
</ul></div>

