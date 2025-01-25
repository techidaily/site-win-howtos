---
title: "Troubleshooting: Resolving Issues During Steam Game Update Process"
date: 2025-01-18T17:08:17.331Z
updated: 2025-01-25T17:24:06.463Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: Resolving Issues During Steam Game Update Process"
excerpt: "This Article Describes Troubleshooting: Resolving Issues During Steam Game Update Process"
thumbnail: https://thmb.techidaily.com/99e083d06891d6b9709e3f748eff8a9d6ada1ef3054d20b60fdb2ab68b2e719b.png
---

## Troubleshooting Persistent Windows Updates Issues - Solved

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fddb113ec0.png)

Window Update is an important component of your Windows system. It helps you install updates on your system. Windows Update is designed to keep your Windows up to date and healthy and it usually does. But unfortunately, in many cases, it fails to do so and instead become the source of multiple annoying problems. Many Windows users have reported that they have got this or that kind of issues with their Windows Update. They have been told that Windows Update “failed to install” certain updates or these updates’ “installation failed”. They’ve got an error popping up with a code and an associated message, which stops them from installing updates. Or they couldn’t download or install the updates with no clear message but get stuck in the update process. No matter how these issues look like, it stops you from installing the updates on your Windows. You can’t fix your system security vulnerabilities, fix bugs, and enjoy new system features without those updates. This can be extremely frustrating. But don’t panic. All Windows Update issues can be fixed. You can fix them by trying the methods below. You don’t have to try them all; just work your way down the list until you find the one that really works for you.**Methods that fix your Windows Update issues:**

1. [**Run Windows Update Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. [**Restart Windows Update related services**](https://tools.techidaily.com/drivereasy/download/)
3. [**Manually download and install updates**](https://tools.techidaily.com/drivereasy/download/)
4. [**Run DISM and System File Checker**](https://tools.techidaily.com/drivereasy/download/)
5. [**Disable your antivirus**](https://tools.techidaily.com/drivereasy/download/)
6. [**Update your drivers**](https://tools.techidaily.com/drivereasy/download/)
7. [**Restore your Windows**](https://tools.techidaily.com/drivereasy/download/)

## Method 1: Run Windows Update Troubleshooter

Windows Update Troubleshooter is a tool released by Microsoft that can help you troubleshoot issues with your Windows Update. You can run it to check your Windows Update when it fails to work properly. To do so:**1)**Download **[Windows Update Troubleshooter](https://aka.ms/diag%5Fwu)** (the program is from a Microsoft site and it’s verified and safe).**2)** Run the tool you’ve just downloaded and follow the on-screen instructions to complete the troubleshooting process.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c046d056cc.png)

##  Method 2: Reset the Windows Update related components

Your Windows Update may fail to update your Windows because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this can fix your problem. To reset these components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right-click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type the following lines of command and press**Enter**on your keyboard after typing each:

* _**net stop bits**_
* _**net stop wuauserv**_
* _**net stop appidsvc**_
* _**net stop cryptsvc**_
(These commands will stop the services that Windows Update requires to download and install updates.)**3)** Type these lines of command and press**Enter** after typing each in Command Prompt:
* _**Ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old**_
* _**Ren %systemroot%\\system32\\catroot2 catroot2.old**_
(This will rename the_SoftwareDistribution_and_catroot2_folder, which are used by Windows Update to store data and temporary files. Your system will detect that these folders are missing, and then it’ll create new ones. The purpose of this is to make the system use the new_SoftwareDistribution_and _catroot2_folders so that Windows Update can avoid issues from the old ones.)**4)** In Command Prompt, type these commands and press**Enter**after each to restart the services you closed just now:
* _**net start bits**_
* _**net start wuauserv**_
* _**net start appidsvc**_
* _**net start cryptsvc**_
**5)**Check your Windows Update to see if it works fine.

## Method 3: Manually download and install updates

If Windows Update can’t help you download certain system updates, you can try doing so on your own. Microsoft has put all its system updates online, and you can download these updates and install them on your computer without the help of Windows Update. To manually download and install updates:**1)**Click the**Start**button in the lower left corner of your screen. Then type “_**information**_“. In the list of results, click**System Information**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c0faa09e19.png)

**2)**In the System Information window, check**System Type**. Its value is usually **x64-based** or **x86-based**(or sometimes**ARM64-based**).

 This is an important piece of information and you should note it down. It will be useful when you are looking for the updates that match your Windows later.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c104b5d2ee.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** On Windows Update, note down the system updates that failed to install. (You may need to get the information from the update history.)

 Note down the codes of these updates that start with “**KB** “.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fafbba7758.png)

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb0182b995.png)

**4)**Go to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)** . Then search for the updates you have failed to install.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb3a1da130.jpg)

**5)** In the search results, find the update that matches your**operating system**and**system type**(_x86-,_ _x64- or ARM64-based_). Then click**Download**next to the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb49473bae.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**6)** Click the link on the new window to download the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb79898ae2.png)

**7)**Open the file you’ve just downloaded and follow the on-screen instructions to install the update.

## Method 4: Run DISM and System File Checker

It’s also possible that your Windows Update can’t work because of the corrupted files on your operating system. Windows has two built-in tools called**SFC (System File Checker)**and**DISM (Deployment Imaging and Servicing Management)**that scan your computer and fix various issues on it. To run these tools:**1)** Click the**Start**button in the lower corner of your screen. Then type “_**cmd**_“. Right-click**Command Prompt**in the list of results and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbd72bc9a4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**2)** In Command Prompt, to run System File Checker, type “_**sfc /scannow**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbe8bbd499.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)**To run DISM, type “_**dism /online /cleanup-image /restorehealth**_“. and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbeb602fef.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)**Wait for the process to complete, then restart your computer. After that, check to see if your Windows Update recovers.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 5: Disable your antivirus

Sometimes your system can’t install new updates due to the interference from your antivirus software. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.

**IMPORTANT:** Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

##  Method 6: Update your drivers

You may get issues with your Windows Update if you are using wrong or out-of-date device drivers. You should regularly check your device drivers and keep them up to date so as to prevent your computer from many annoying issues. But you may not have the time or patience to check and update your drivers manually. If you want to have this done easily and automatically, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .**Driver Easy**will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee): **1) [Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.**2)**Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713a84159a4.png) **3)** Click the **Update** button next to each driver to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713ba9d0320.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 7: Restore your Windows

Perhaps the issues with your Windows come from some changes you’ve made to your system. You can perform a system restore. This will restore your system from a restore point (you need to have one that has been created before your Windows Update issue occurs) undo those changes made. To do so:**1)**Click the **Start**button in the lower corner of your screen. Then type “_**restore**_“. In the list of results, click “**Create a restore point**“. The System Properties dialog will appear.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc666d51a9.png)

**2)** Click**System Restore**. The System Restore wizard will pop up.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc6fa8971e.png)

**3)** Follow the on-screen instructions to choose a system restore point and restore your Windows.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc712671f3.png)

**4)** Wait for the restore process to complete and then check to see if your Windows Update gets back to normal.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-examining-youtubes-mobile-app-for-iosandroid-devices/"><u>[New] 2024 Approved Examining YouTube's Mobile App for iOS/Android Devices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-chill-challenge-highlighting-the-speed-and-skill-of-winter-olympics-x-c-skiers/"><u>[New] Chill Challenge Highlighting the Speed and Skill of Winter Olympics X-C Skiers</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-safe-no-cost-methods-for-youtube-tracks-extraction/"><u>[New] In 2024, Safe, No-Cost Methods for YouTube Tracks Extraction</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/astering-your-videos-top-youtube-friendly-cameras-for-2024/"><u>[New] Mastering Your Videos Top YouTube-Friendly Cameras for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-premium-online-meeting-applications-no-zoom/"><u>[New] Premium Online Meeting Applications (No Zoom)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-error-set-user-settings-to-driver-failed/"><u>[Solved] Error: Set User Settings To Driver Failed</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-unlock-your-true-instagram-potential-followers-guide/"><u>[Updated] Unlock Your True Instagram Potential - Followers Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-error-0x887a0006-in-no-time-step-by-step-guide-awaits-you/"><u>Beat Error 0X887A0006 in No Time! Step-by-Step Guide Awaits You</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-vivo-y100-device-sim-by-drfone-android/"><u>Easily Unlock Your Vivo Y100 Device SIM</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-activating-your-pcs-bluetooth-feature-in-windows-7/"><u>Easy Fixes: Activating Your PC's Bluetooth Feature in Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-failed-to-load-steamuidll-error-in-steam-for-windows/"><u>How to Fix the “Failed to Load steamui.dll” Error in Steam for Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208398099-quick-fixes-for-unresponsive-buttons-on-hp-laptops-troubleshoot-now/"><u>Quick Fixes for Unresponsive Buttons on HP Laptops - Troubleshoot Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-directx-device-creation-failed/"><u>SOLVED: DirectX Device Creation Failed</u></a></li>
<li><a href="https://printer-issues.techidaily.com/speedy-updates-for-sluggish-printers/"><u>Speedy Updates for Sluggish Printers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-guide-to-correcting-failed-to-play-video-issue-error-224003/"><u>The Ultimate Guide to Correcting 'Failed to Play' Video Issue (Error 224003)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-solving-microsoft-wireless-display-adapter-problems-on-windows-10/"><u>Troubleshooting Guide: Solving Microsoft Wireless Display Adapter Problems on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-lenovo-mouse-pad-issues-on-windows-11-8-and-7-solutions-included/"><u>Troubleshooting Lenovo Mouse Pad Issues on Windows 11, 8 & 7 - Solutions Included</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-fixing-the-semaphore-timed-out-problem-error-0x80070079/"><u>Understanding and Fixing the 'Semaphore Timed Out' Problem (Error 0X80070079)</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/windows-11-cloudlocal/"><u>Windows 11: 最適なインストール方法 - CloudダウンロードかLocal再インストールかを決定する</u></a></li>
</ul></div>

