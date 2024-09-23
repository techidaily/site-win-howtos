---
title: Understanding and Repairing 'Disk Is Dirty' Mistake (Error 0X80071AC3)
date: 2024-09-20T20:49:09.601Z
updated: 2024-09-22T21:33:42.954Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Understanding and Repairing 'Disk Is Dirty' Mistake (Error 0X80071AC3)
excerpt: This Article Describes Understanding and Repairing 'Disk Is Dirty' Mistake (Error 0X80071AC3)
thumbnail: https://thmb.techidaily.com/a7b063e2c5f1e938dc6e32e2ce85c52239dfc8e7739a5c0ead2c07ab91e735b6.png
---

## Unlocking Success: Expert Advice for Tackling and Repairing Error 1603 on Your Device

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca1709cae9.png)

You may encounter an error with a code of **1603** when you are attempting to install something on your Windows. The error message is basically something like “**Error: -1603 Fatal error during installation.**” It usually occurs when you are using a Windows Installer package to install the program. You can try the methods below that can be help you fix the error. **1)[Change installation location](https://tools.techidaily.com/drivereasy/download/)**   **2) [Completely uninstall the same program installed](https://tools.techidaily.com/drivereasy/download/)**   **3)[Start and re-register Microsoft Installer service](https://tools.techidaily.com/drivereasy/download/)**   **4)[Acquire full permissions on the drive for installation](https://tools.techidaily.com/drivereasy/download/)**

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

To**re-register**Windows Installer service:**a)** Press**Win + R**, type “_**msiexec /unregister**_” and hit**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9370d810.png)

**b)** Press**Win + R** again and enter “ _**msiexec /regserve** **r**_ “.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9952ad21.png)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4) Acquire full permissions on the drive for installation

It is possible that the error 1603 occurs because you don’t have**full permissions**on the file location. Try getting the permissions on the drive you are installing your application to and see if this fixes the problem.**a)** Open**File Explorer**, right click on the drive containing the installation location and select**Properties**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cac402cfce.png)

**b)** Go to**Security**tab and click on**Edit**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595caf24696ae.png)

**c)** Single click on **SYSTEM**and ensure that the**Allow**box of every item in**Permissions for SYSTEM** is checked (if it is checkable). Do the same check for**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb123f210b.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111967/7443" target="_top" id="2111967">
  <img src="//a.impactradius-go.com/display-ad/7443-2111967" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111967/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**d)** Click on**OK**to go back to**Properties**dialog. Then click on**Advanced**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb3cf25a0c.png)

**e)** Click on**Change Permissions**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb5c235c54.png)

**f)** On**Permissions**tab, double click on**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb67382950.png)

**g)** Select**This folder, subfolders and files**for**Applies to**field and**tick** **all the available basic permissions**. After that hit**OK**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb7074c180.png)

**h)** Do the same operation above for**SYSTEM**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb8202ef5a.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934138/19272" target="_top" id="1934138">
  <img src="//a.impactradius-go.com/display-ad/19272-1934138" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934138/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-elevate-your-cinematography-skills-editing-and-sharing-360-videos-on-youtube/"><u>[Updated] 2024 Approved Elevate Your Cinematography Skills Editing and Sharing 360° Videos on YouTube</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-smooth-soundscape-creation-with-audacity/"><u>[Updated] 2024 Approved Smooth Soundscape Creation with Audacity</u></a></li>
<li><a href="https://vp-tips.techidaily.com/1726223640777-4/"><u>4년</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosis-and-repair-non-functioning-right-click-on-windows-11-systems/"><u>Diagnosis & Repair: Non-Functioning Right Click on Windows 11 Systems</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-iphone-15-plus-when-we-dont-have-apple-id-or-password-by-drfone-ios/"><u>How to Unlock Apple iPhone 15 Plus When We Dont Have Apple ID or Password?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-your-privileges-on-steam-for-absent-files-easy-fixes-inside/"><u>Restore Your Privileges on Steam for Absent Files – Easy Fixes Inside!</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-installation-of-synaptics-drivers-on-windows-free-download-and-updates/"><u>Seamless Installation of Synaptics Drivers on Windows - Free Download & Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-restoring-functionality-to-a-broken-backspace-key/"><u>Solution Found: Restoring Functionality to a Broken Backspace Key</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-fixing-your-keyboard-by-performing-a-fresh-restart/"><u>Step-by-Step Guide: Fixing Your Keyboard by Performing a Fresh Restart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-windows-1011-revamping-using-winbubble/"><u>The Complete Guide to Windows 10/11 Revamping Using WinBubble</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-troubleshooting-guide-for-error-code-0xc1900208-in-windows-10-updates/"><u>The Ultimate Troubleshooting Guide for Error Code 0xC1900208 in Windows 10 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooting-steelseries-x70-keyboard-solving-pen-not-responding-issues-comprehensive-guide/"><u>Ultimate Troubleshooting SteelSeries X70 Keyboard: Solving 'Pen Not Responding' Issues (Comprehensive Guide)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-solving-windows-process-termination-issue-error-1067/"><u>Understanding and Solving Windows Process Termination Issue, Error 1067</u></a></li>
<li><a href="https://fox-info.techidaily.com/x-racing-olympics-the-top-sections-of-22-for-2024/"><u>X-Racing Olympics The Top Sections of '22 for 2024</u></a></li>
</ul></div>

