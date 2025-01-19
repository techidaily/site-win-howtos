---
title: Mastering the Resolution of 'Fatal Error During Installation' (Error 1603) in Software Deployment
date: 2025-01-12T17:10:31.760Z
updated: 2025-01-19T18:35:36.813Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Mastering the Resolution of 'Fatal Error During Installation' (Error 1603) in Software Deployment
excerpt: This Article Describes Mastering the Resolution of 'Fatal Error During Installation' (Error 1603) in Software Deployment
thumbnail: https://thmb.techidaily.com/9fa9e4346708270d82530e01172580b66a8c63e17b3edbe0866986af1acde6f2.jpg
---

## Resolving the Critical Installer Crash - How to Fix Error Code 1603

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

## 3) Start and re-register Microsoft Installer service

There may be something going wrong with**Microsoft Installer service**and therefore resulting in error 1603\. You can fix the problem by (re)starting and re-registering Microsoft Installer service. To**start**Windows Installer service:**a)** Press**Win + R**and enter “_**services.msc**_“;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca68fd8714.png)

**b)** Find and double click on**Windows Installer**;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca70c399c1.png)

**c)** Hit**Start**button under**Service status**and hit**OK**. (If its service status is**running**, you should click on**Stop**first and then hit**Start**.)

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca7cbbdf36.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

To**re-register**Windows Installer service:**a)** Press**Win + R**, type “_**msiexec /unregister**_” and hit**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9370d810.png)

**b)** Press**Win + R** again and enter “ _**msiexec /regserve** **r**_ “.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9952ad21.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4) Acquire full permissions on the drive for installation

It is possible that the error 1603 occurs because you don’t have**full permissions**on the file location. Try getting the permissions on the drive you are installing your application to and see if this fixes the problem.**a)** Open**File Explorer**, right click on the drive containing the installation location and select**Properties**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cac402cfce.png)

**b)** Go to**Security**tab and click on**Edit**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595caf24696ae.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**c)** Single click on **SYSTEM**and ensure that the**Allow**box of every item in**Permissions for SYSTEM** is checked (if it is checkable). Do the same check for**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb123f210b.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**d)** Click on**OK**to go back to**Properties**dialog. Then click on**Advanced**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb3cf25a0c.png)

**e)** Click on**Change Permissions**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb5c235c54.png)

**f)** On**Permissions**tab, double click on**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb67382950.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**g)** Select**This folder, subfolders and files**for**Applies to**field and**tick** **all the available basic permissions**. After that hit**OK**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb7074c180.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**h)** Do the same operation above for**SYSTEM**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb8202ef5a.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-data.techidaily.com/n-2024-7-comedy-youtube-video-ideas-that-only-funny-people-are-allowed-to-try/"><u>[New] In 2024, 7 Comedy YouTube Video Ideas That Only Funny People Are Allowed to Try</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-legal-framework-of-instagram-tunes/"><u>[Updated] 2024 Approved Legal Framework of Instagram Tunes</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-the-powerhouse-q500-typhoon/"><u>[Updated] Unveiling the Powerhouse Q500 Typhoon</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/directly-delivering-tiktok-videos-to-twitters-feed-for-2024/"><u>Directly Delivering TikTok Videos to Twitter's Feed for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-eliminating-windows-11-screenshake-problem/"><u>Effective Solutions for Eliminating Window's 11 Screenshake Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-reactivating-the-windows-firewall-system/"><u>Fixes for Reactivating the Windows Firewall System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-overcome-windows-system-error-0xc00000e9-a-comprehensive-tutorial/"><u>How to Successfully Overcome Windows System Error 0XC00000E9 – A Comprehensive Tutorial</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-c300-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Nokia C300 Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-realme-11-proplus-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Realme 11 Pro+ Phone</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-response-from-hp-wireless-keyboard-follow-these-proven-methods-to-get-it-up-and-running-again/"><u>No Response From HP Wireless Keyboard? Follow These Proven Methods to Get It Up and Running Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-volume-is-dirty-issue-understanding-error-0x80071ac3/"><u>Solving the 'Volume Is Dirty' Issue - Understanding Error 0X80071AC3</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-tnm-system-is-essential-for-accurate-lung-cancer-staging-and-treatment-planning/"><u>The TNM System Is Essential for Accurate Lung Cancer Staging and Treatment Planning.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-10-update-issues-solutions-for-a-freezing-or-stalled-system/"><u>Troubleshooting Windows 10 Update Issues: Solutions for a Freezing or Stalled System</u></a></li>
</ul></div>

