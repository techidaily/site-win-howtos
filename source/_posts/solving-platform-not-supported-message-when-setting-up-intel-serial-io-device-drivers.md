---
title: Solving 'Platform Not Supported' Message When Setting Up Intel Serial IO Device Drivers
date: 2025-02-12T18:37:44.661Z
updated: 2025-02-16T23:58:52.349Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving 'Platform Not Supported' Message When Setting Up Intel Serial IO Device Drivers
excerpt: This Article Describes Solving 'Platform Not Supported' Message When Setting Up Intel Serial IO Device Drivers
thumbnail: https://thmb.techidaily.com/0b6ddfcc355a034bc5a8feec71361dd4191fefb9c46706aa01bde874e33ab2b8.jpeg
---

## Biomarker Testing Is Essential for Identifying Patients Who Will Benefit From Targeted Therapy

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca1709cae9.png)

You may encounter an error with a code of **1603** when you are attempting to install something on your Windows. The error message is basically something like “**Error: -1603 Fatal error during installation.**” It usually occurs when you are using a Windows Installer package to install the program. You can try the methods below that can be help you fix the error. **1)[Change installation location](https://tools.techidaily.com/drivereasy/download/)**   **2) [Completely uninstall the same program installed](https://tools.techidaily.com/drivereasy/download/)**   **3)[Start and re-register Microsoft Installer service](https://tools.techidaily.com/drivereasy/download/)**   **4)[Acquire full permissions on the drive for installation](https://tools.techidaily.com/drivereasy/download/)**

## 1) Change installation location

You may encounter an error 1603 because the installation location is you choose is not available due to various reasons — such as being encrypted. You can use another installation folder to install the program and see if the error is gone.

## 2) Completely uninstall the same program installed

If you have previously installed the same program (or its earlier version), the error can occur when you try to install the application again. If you want to install your program successfully, you need to perform a **clean uninstall** of the one installed on your computer. This means you need to remove all the temporary files and preferences it leaves in addition to the major program. Sometimes you may lose the desktop shortcut of a program due to some reasons and therefore you may forget that you have installed it. In this case you can go to**Control Panel**to check if it is still on your computer: Press**Win + R**, and enter “ _**control**_“;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9bf012d25.png)

Find and open**Programs and Features**;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9c81105c5.png)

Then you can check if the application is listed here. If it is, uninstall it.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9d00544d7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3) Start and re-register Microsoft Installer service

There may be something going wrong with**Microsoft Installer service**and therefore resulting in error 1603\. You can fix the problem by (re)starting and re-registering Microsoft Installer service. To**start**Windows Installer service:**a)** Press**Win + R**and enter “_**services.msc**_“;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca68fd8714.png)

**b)** Find and double click on**Windows Installer**;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca70c399c1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**c)** Hit**Start**button under**Service status**and hit**OK**. (If its service status is**running**, you should click on**Stop**first and then hit**Start**.)

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca7cbbdf36.png)

To**re-register**Windows Installer service:**a)** Press**Win + R**, type “_**msiexec /unregister**_” and hit**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9370d810.png)

**b)** Press**Win + R** again and enter “ _**msiexec /regserve** **r**_ “.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9952ad21.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4) Acquire full permissions on the drive for installation

It is possible that the error 1603 occurs because you don’t have**full permissions**on the file location. Try getting the permissions on the drive you are installing your application to and see if this fixes the problem.**a)** Open**File Explorer**, right click on the drive containing the installation location and select**Properties**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cac402cfce.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**b)** Go to**Security**tab and click on**Edit**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595caf24696ae.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**c)** Single click on **SYSTEM**and ensure that the**Allow**box of every item in**Permissions for SYSTEM** is checked (if it is checkable). Do the same check for**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb123f210b.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**d)** Click on**OK**to go back to**Properties**dialog. Then click on**Advanced**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb3cf25a0c.png)

**e)** Click on**Change Permissions**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb5c235c54.png)

**f)** On**Permissions**tab, double click on**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb67382950.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**g)** Select**This folder, subfolders and files**for**Applies to**field and**tick** **all the available basic permissions**. After that hit**OK**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb7074c180.png)

**h)** Do the same operation above for**SYSTEM**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb8202ef5a.png)

**i)** Click on**OK** all the way out. Now you have acquired full permissions on this drive. Try installing your application and see if the issue is fixed.

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
<li><a href="https://youtube-web.techidaily.com/024-approved-zoom-in-or-out-tailoring-your-youtube-viewing-pace/"><u>[New] 2024 Approved Zoom in or Out? Tailoring Your YouTube Viewing Pace</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-discovering-bargains-inexpensive-gopro-purchasing-guide/"><u>[New] In 2024, Discovering Bargains Inexpensive GoPro Purchasing Guide</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-from-novice-to-expert-a-guide-for-effective-single-stream-livestreams/"><u>[Updated] 2024 Approved From Novice to Expert A Guide for Effective Single-Stream Livestreams</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-skyrocket-visibility-mastering-google-analytics-for-youtubers/"><u>[Updated] In 2024, Skyrocket Visibility Mastering Google Analytics for YouTubers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-refresh-your-virtual-space-in-google-meet-pc-and-mobile-way/"><u>[Updated] Refresh Your Virtual Space in Google Meet, PC & Mobile Way</u></a></li>
<li><a href="https://fox-http.techidaily.com/a-deep-dive-into-whatsapps-vocal-communication-tools/"><u>A Deep Dive Into WhatsApp's Vocal Communication Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/confirmation-of-setting-resource-reluctant-to-respond/"><u>Confirmation of Setting: Resource Reluctant to Respond</u></a></li>
<li><a href="https://win-howtos.techidaily.com/data-integrity-restored-addressing-and-solving-cyclic-redundancy-errors/"><u>Data Integrity Restored: Addressing and Solving Cyclic Redundancy Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/gaming-frustrations-unexpected-computer-lockups/"><u>Gaming Frustrations: Unexpected Computer Lockups</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-entering-metaverse-ranked-best-virtual-reality-gear/"><u>In 2024, Entering Metaverse Ranked Best Virtual Reality Gear</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/leading-portable-powerhouses-discover-the-finest-mini-gaming-rigs/"><u>Leading Portable Powerhouses: Discover the Finest Mini Gaming Rigs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-internet-explorer-no-longer-responding-error-a-step-by-step-guide/"><u>Solving the 'Internet Explorer No Longer Responding' Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-order-code-compliance-needed/"><u>Stop Order: Code Compliance Needed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-excessive-cpu-consumption-due-to-faulty-audio-drivers-on-your-computer/"><u>Tackling Excessive CPU Consumption Due to Faulty Audio Drivers on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-guide-to-resolving-unrecoverable-directx-errors/"><u>The Ultimate Guide to Resolving Unrecoverable DirectX Errors</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unleashing-potential-windows-10s-new-upgrades-for-2024/"><u>Unleashing Potential Windows 10'S New Upgrades for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-permanent-fixes-for-continuous-load-screens-on-skyrim-gameplay/"><u>Unlocking Permanent Fixes for Continuous Load Screens on Skyrim Gameplay</u></a></li>
</ul></div>

