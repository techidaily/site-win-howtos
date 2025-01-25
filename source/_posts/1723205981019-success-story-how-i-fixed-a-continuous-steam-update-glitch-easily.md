---
title: "Success Story: How I Fixed a Continuous Steam Update Glitch Easily!"
date: 2025-01-22T18:17:48.009Z
updated: 2025-01-25T16:41:33.089Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Success Story: How I Fixed a Continuous Steam Update Glitch Easily!"
excerpt: "This Article Describes Success Story: How I Fixed a Continuous Steam Update Glitch Easily!"
thumbnail: https://thmb.techidaily.com/d27bd20369a0206f3a047b7bb4f9e0b9ec6c2aca32544460f90baebbc95c9231.jpg
---

## Definitive Solutions to Error 0X802^24200D – Successfully Update Your Windows System Now

If you’re seeing an**error code 0x8024200d**  when performing a Windows update,  you’re not alone. Many Windows users are reporting it. This error code usually appears when they try to update to a new build of the Windows system. The reason behind it is that some updated files are missing or corrupted.

 The good news is you can fix it. You should be able to fix the problem quite easily using one of the solutions we’ve listed below. You may not have to try them all. Just work your way down the list until you find the one that works.

1. [**Running the Windows Update Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. **[Restarting the Windows Update service](https://tools.techidaily.com/drivereasy/download/)**
3. **[Running System File Checker](https://tools.techidaily.com/drivereasy/download/)**
4. **[Downloading updates from Microsoft Update Catalog manually](https://tools.techidaily.com/drivereasy/download/)**

## Method 1: Running the Windows Update Troubleshooter

 You can download and run**the Windows Update Troubleshooter** to automatically diagnose and resolve any issues regarding Windows Update.

**1)** Click **[here](http://aka.ms/diag%5Fwu)**  to download the Windows Update Troubleshooter.

**2)** Double-click the downloaded file (**WindowsUpdate.diagcab** ) to run the troubleshooter, and then click**Next** .

**If your current operating system is Windows 7** , you just need to wait until the troubleshooter finishes the process and shows you the process result.**If your current operating system is Windows 8 or Windows 10** , you may need to follow the steps below.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap3-1.png)

**3)** If there is a more recent version of Windows Update troubleshooter available, click to run it.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap4-2.png)

**4)** In the new version of Windows Update troubleshooter, Click **Next** . The troubleshooter will check the available updates for your machine.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap5-1.png)

**5)** Click **Apply this fix**  to start the update process in the background immediately.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap7.png)

 The troubleshooter will try to fix the issue for you. You can restart your computer and try to perform the Windows update again. If it still doesn’t work, please try the next method.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 2: Restarting the Windows Update service

 You may see this error code if there is something wrong with the Windows Update service. You can try to restart the Windows Update service to resolve this problem. Here’s how to do it:

**1)** On your keyboard, press**the Windows Logo key** and**R** at the same time to open the Run dialog, then type**services.msc** and press**Enter** to open the Services window.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap13.png)

**2)** Right-click **Windows Update**  and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap14-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** On your keyboard, press**the Windows Logo Key** and**E** at the same time to open **File Explorer** . Copy the path below and paste it into the address bar, then press **Enter** on your keyboard to go to the **DataStore**  folder.

`C:\Windows\SoftwareDistribution\DataStore`

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap18-2.png)

Please paste it in the address bar.

**4)** Delete all the files in the folder **DataStore** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap20-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 When all the files are deleted, you shall see “This folder is empty”.

**5)** On your keyboard, press**the Windows Logo Key** and**E** at the same time to open**File Explorer** . Copy the path below and paste it into the address bar, then press **Enter** on your keyboard to open the**Download** folder.

`` `C:\Windows\SoftwareDistribution\Download`

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap21-1.png)

Please paste it in the address bar.

**6)** Delete all the files in the folder**Download** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap22-3.png)

 When all the files are deleted, you shall see “This folder is empty”.

**7)** In the Services window, right-click **Windows Update**  and select**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap24-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Go and check Windows Update again to see whether you can perform the Windows update or not. If it still doesn’t work, please try the next method.

## Method 3: Running System File Checker

 System File Checker can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

**1)**  On your keyboard, press**the Windows Logo Key** and then type**cmd** in the search box. When you see **Command Prompt** in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **Ok** to run the **Command Prompt** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap37.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**2)** On your keyboard, type the command below and press **Enter** . **If your current operating system is Windows 7, please skip this step.**

DISM.exe /Online /Cleanup-image /Restorehealth

 It may take several minutes for this command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap11.png)

**3)** When this command operation is completed, on your keyboard, type the following command and press **Enter** .

sfc /scannow

It may take some time for the command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap12-1.png)

**4)** When this command operation is completed, close the **Command Prompt** and run **Windows Update**  again to check whether this method works or not. If you still fail to install updates for your Windows system, please try the next method.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 4: Downloading updates from Microsoft Update Catalog manually

 If all the methods mentioned above still don’t work for you, you can try to download the updates you failed to install from **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  and install them manually.

**1)** On your keyboard, press**the Windows Logo Key** and type**Windows Update** , and then press**Enter** to open Windows Update.

**2)** Click **View update history**  to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.

**3)** Follow the instructions below to view your system type:

**i.** On your keyboard, press**the Windows Logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Enter** to open the Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap40.png)

**ii.**  Type the command line**systeminfo** and press**Enter** to view your system type.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap31-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 “**X64-based PC** ” indicates that your Windows OS is 64-bit; “**X86-based PC** ” means that your Windows OS is 32-bit.

**4)** Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .

**5)**  Type the update number that you want to download. In this example, type KB 3006137 and then click **Search** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap42.png)

**6)** In the list of search results, select the right update for your operating system and click **Download** .

 If your Windows OS is 64-bit, you should download the update whose name contains “**x64-based** ”.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap26-1.png)

**7)** In the pop-up window, click the link to start downloading the updates.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap27.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**8)** Double-click the downloaded file and follow the on-screen instructions to install the update.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://win-howtos.techidaily.com/g-is-the-acceleration-due-to-gravity-approximately-981-ms2/"><u> (G ) Is the Acceleration Due to Gravity (Approximately 9.81 M/S (^2 ))</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-unlocking-the-potential-of-your-ppt-with-professional-recording/"><u>[Updated] 2024 Approved Unlocking the Potential of Your PPT with Professional Recording</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-curating-youtube-music-experiences/"><u>[Updated] Curating YouTube Music Experiences</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-convenient-curvature-creation-techniques-in-pixels/"><u>[Updated] In 2024, Convenient Curvature Creation Techniques in Pixels</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-transcribing-chats-efficient-techniques-for-fb-live-recordings/"><u>[Updated] In 2024, Transcribing Chats Efficient Techniques for FB Live Recordings</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-thriving-in-stardew-insiders-guide-to-ginger-island/"><u>2024 Approved Thriving in Stardew Insider's Guide to Ginger Island</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mmfwav-movavi/"><u>如何免费将MMF文件转换为WAV: 利用Movavi工具的步骤指南</u></a></li>
<li><a href="https://win-howtos.techidaily.com/webmmp3/"><u>無縫的 WEBM到MP3適配 - 動感維予電影格式變更器</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/deciding-on-the-best-gopro-max-or-hero-11/"><u>Deciding on the Best GoPro Max or Hero 11?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/exploring-high-performance-video-editors-the-ultimate-guide-to-top-9-free-options-replacing-lightworks-and-movavi/"><u>Exploring High-Performance Video Editors: The Ultimate Guide to Top 9 Free Options Replacing Lightworks & Movavi</u></a></li>
<li><a href="https://facebook.techidaily.com/exploring-tools-provided-for-common-facebook-issues/"><u>Exploring Tools Provided for Common Facebook Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guia-simple-para-conversion-libre-de-mp4-a-mkv-online-con-movavi/"><u>Guía Simple Para Conversión Libre De MP4 a MKV Online Con Movavi</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/instabeats-blending-music-and-visuals-tactfully-for-2024/"><u>InstaBeats Blending Music & Visuals Tactfully for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movaviape/"><u>Movavi提供線上免費的APE類型音效更換工具</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-key-steps-effective-obs-streaming-directly-to-facebook-users-for-2024/"><u>The Key Steps Effective OBS Streaming Directly to Facebook Users for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trasforma-i-tuoi-file-avi-in-formato-flv-gratuitamente-con-il-servizio-online-di-convertitore-movavi/"><u>Trasforma I Tuoi File AVI in Formato FLV Gratuitamente Con Il Servizio Online Di Convertitore Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trp-mpg/"><u>TRP 이동판 값을 MPG로 바꾸기: 웹상인 무료 해시</u></a></li>
</ul></div>

