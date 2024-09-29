---
title: "Success Story: How I Fixed a Continuous Steam Update Glitch Easily!"
date: 2024-08-23T14:10:33.503Z
updated: 2024-08-24T14:10:33.503Z
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

## Method 2: Restarting the Windows Update service

 You may see this error code if there is something wrong with the Windows Update service. You can try to restart the Windows Update service to resolve this problem. Here’s how to do it:

**1)** On your keyboard, press**the Windows Logo key** and**R** at the same time to open the Run dialog, then type**services.msc** and press**Enter** to open the Services window.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap13.png)

**2)** Right-click **Windows Update**  and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap14-2.png)

**3)** On your keyboard, press**the Windows Logo Key** and**E** at the same time to open **File Explorer** . Copy the path below and paste it into the address bar, then press **Enter** on your keyboard to go to the **DataStore**  folder.

`C:\Windows\SoftwareDistribution\DataStore`

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap18-2.png)

Please paste it in the address bar.

**4)** Delete all the files in the folder **DataStore** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap20-1.png)

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

 Go and check Windows Update again to see whether you can perform the Windows update or not. If it still doesn’t work, please try the next method.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
## Method 3: Running System File Checker

 System File Checker can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

**1)**  On your keyboard, press**the Windows Logo Key** and then type**cmd** in the search box. When you see **Command Prompt** in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **Ok** to run the **Command Prompt** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap37.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
## Method 4: Downloading updates from Microsoft Update Catalog manually

 If all the methods mentioned above still don’t work for you, you can try to download the updates you failed to install from **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  and install them manually.

**1)** On your keyboard, press**the Windows Logo Key** and type**Windows Update** , and then press**Enter** to open Windows Update.

**2)** Click **View update history**  to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.

**3)** Follow the instructions below to view your system type:

**i.** On your keyboard, press**the Windows Logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Enter** to open the Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap40.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
**ii.**  Type the command line**systeminfo** and press**Enter** to view your system type.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap31-2.png)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 “**X64-based PC** ” indicates that your Windows OS is 64-bit; “**X86-based PC** ” means that your Windows OS is 32-bit.

**4)** Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .

**5)**  Type the update number that you want to download. In this example, type KB 3006137 and then click **Search** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap42.png)

**6)** In the list of search results, select the right update for your operating system and click **Download** .

 If your Windows OS is 64-bit, you should download the update whose name contains “**x64-based** ”.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap26-1.png)

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**7)** In the pop-up window, click the link to start downloading the updates.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap27.png)

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


