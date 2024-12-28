---
title: Solving the Dxgkrnl Critical Failure in Videos on Your PC
date: 2024-12-23T04:06:19.552Z
updated: 2024-12-28T04:21:49.658Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving the Dxgkrnl Critical Failure in Videos on Your PC
excerpt: This Article Describes Solving the Dxgkrnl Critical Failure in Videos on Your PC
thumbnail: https://thmb.techidaily.com/3c1c3c36ffd528acf80507ec017f8e098843112bc4dbcec6bba024f6534d2781.jpg
---

## Resolving the Critical Installer Crash - How to Fix Error Code 1603

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca1709cae9.png)

You may encounter an error with a code of **1603** when you are attempting to install something on your Windows. The error message is basically something like “**Error: -1603 Fatal error during installation.**” It usually occurs when you are using a Windows Installer package to install the program. You can try the methods below that can be help you fix the error. **1)[Change installation location](https://tools.techidaily.com/drivereasy/download/)**   **2) [Completely uninstall the same program installed](https://tools.techidaily.com/drivereasy/download/)**   **3)[Start and re-register Microsoft Installer service](https://tools.techidaily.com/drivereasy/download/)**   **4)[Acquire full permissions on the drive for installation](https://tools.techidaily.com/drivereasy/download/)**

## 1) Change installation location

You may encounter an error 1603 because the installation location is you choose is not available due to various reasons — such as being encrypted. You can use another installation folder to install the program and see if the error is gone.

## 2) Completely uninstall the same program installed

If you have previously installed the same program (or its earlier version), the error can occur when you try to install the application again. If you want to install your program successfully, you need to perform a **clean uninstall** of the one installed on your computer. This means you need to remove all the temporary files and preferences it leaves in addition to the major program. Sometimes you may lose the desktop shortcut of a program due to some reasons and therefore you may forget that you have installed it. In this case you can go to**Control Panel**to check if it is still on your computer: Press**Win + R**, and enter “ _**control**_“;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9bf012d25.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Find and open**Programs and Features**;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9c81105c5.png)

Then you can check if the application is listed here. If it is, uninstall it.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9d00544d7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3) Start and re-register Microsoft Installer service

There may be something going wrong with**Microsoft Installer service**and therefore resulting in error 1603\. You can fix the problem by (re)starting and re-registering Microsoft Installer service. To**start**Windows Installer service:**a)** Press**Win + R**and enter “_**services.msc**_“;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca68fd8714.png)

**b)** Find and double click on**Windows Installer**;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca70c399c1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**c)** Hit**Start**button under**Service status**and hit**OK**. (If its service status is**running**, you should click on**Stop**first and then hit**Start**.)

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca7cbbdf36.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

To**re-register**Windows Installer service:**a)** Press**Win + R**, type “_**msiexec /unregister**_” and hit**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9370d810.png)

**b)** Press**Win + R** again and enter “ _**msiexec /regserve** **r**_ “.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9952ad21.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4) Acquire full permissions on the drive for installation

It is possible that the error 1603 occurs because you don’t have**full permissions**on the file location. Try getting the permissions on the drive you are installing your application to and see if this fixes the problem.**a)** Open**File Explorer**, right click on the drive containing the installation location and select**Properties**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cac402cfce.png)

**b)** Go to**Security**tab and click on**Edit**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595caf24696ae.png)

**c)** Single click on **SYSTEM**and ensure that the**Allow**box of every item in**Permissions for SYSTEM** is checked (if it is checkable). Do the same check for**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb123f210b.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**d)** Click on**OK**to go back to**Properties**dialog. Then click on**Advanced**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb3cf25a0c.png)

**e)** Click on**Change Permissions**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb5c235c54.png)

**f)** On**Permissions**tab, double click on**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb67382950.png)

**g)** Select**This folder, subfolders and files**for**Applies to**field and**tick** **all the available basic permissions**. After that hit**OK**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb7074c180.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-elite-mp4-streamer-system-for-fb/"><u>[New] 2024 Approved Elite MP4 Streamer System for FB</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-revolutionary-strategies-for-youtube-and-facebook-integration/"><u>[New] Revolutionary Strategies for YouTube & Facebook Integration</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-top-5-mac-cam-alternatives-to-elevate-your-digital-screens/"><u>2024 Approved Top 5 Mac Cam Alternatives to Elevate Your Digital Screens</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202094236-fixing-missing-desktop-icons-on-windows-11-complete-solution/"><u>Fixing Missing Desktop Icons on Windows 11 - Complete Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-play-fortnite-solutions-for-incompatible-graphics-cards-under-windows/"><u>How to Play Fortnite: Solutions for Incompatible Graphics Cards Under Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-touch-functionality-on-your-microsoft-surface-pro-4/"><u>How to Restore Touch Functionality on Your Microsoft Surface Pro 4</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-of-the-best-in-drone-following-capabilities/"><u>In 2024, Best of the Best in Drone Following Capabilities</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-prime-ringtone-retailers-for-game-of-thrones-fans/"><u>In 2024, Prime Ringtone Retailers for Game of Thrones Fans</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-process-of-transforming-pal-dvds-into-universal-video-standards/"><u>Mastering the Process of Transforming PAL DVDs Into Universal Video Standards</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-what-to-do-when-your-computer-fails-to-boot/"><u>Troubleshoot and Fix: What To Do When Your Computer Fails to Boot</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixes-for-corrupted-pictures-in-windows-10-and-11/"><u>Troubleshooting Fixes for Corrupted Pictures in Windows 10 and 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-non-functional-night-light-on-windows-11/"><u>Troubleshooting Guide for Non-Functional Night Light on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-windows-widgets-for-real-time-resource-tracking/"><u>Utilizing Windows Widgets for Real-Time Resource Tracking</u></a></li>
</ul></div>

