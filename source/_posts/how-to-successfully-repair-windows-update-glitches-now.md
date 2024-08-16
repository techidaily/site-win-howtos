---
title: How To Successfully Repair Windows Update Glitches, Now
date: 2024-08-15T11:26:38.760Z
updated: 2024-08-16T11:26:38.760Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How To Successfully Repair Windows Update Glitches, Now
excerpt: This Article Describes How To Successfully Repair Windows Update Glitches, Now
thumbnail: https://thmb.techidaily.com/cf530c2c593b6932cef8db0cdf4cd19063a18ed96567f34da25c1f69a7f2e22f.jpg
---

## How To Successfully Repair Windows Update Glitches, Now

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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
##  Method 2: Reset the Windows Update related components

Your Windows Update may fail to update your Windows because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this can fix your problem. To reset these components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right-click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type the following lines of command and press**Enter**on your keyboard after typing each:
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## Method 3: Manually download and install updates

If Windows Update can’t help you download certain system updates, you can try doing so on your own. Microsoft has put all its system updates online, and you can download these updates and install them on your computer without the help of Windows Update. To manually download and install updates:**1)**Click the**Start**button in the lower left corner of your screen. Then type “_**information**_“. In the list of results, click**System Information**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c0faa09e19.png)

**2)**In the System Information window, check**System Type**. Its value is usually **x64-based** or **x86-based**(or sometimes**ARM64-based**).

 This is an important piece of information and you should note it down. It will be useful when you are looking for the updates that match your Windows later.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c104b5d2ee.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

**3)** On Windows Update, note down the system updates that failed to install. (You may need to get the information from the update history.)

 Note down the codes of these updates that start with “**KB** “.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fafbba7758.png)

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb0182b995.png)

**4)**Go to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)** . Then search for the updates you have failed to install.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb3a1da130.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->

**5)** In the search results, find the update that matches your**operating system**and**system type**(_x86-,_ _x64- or ARM64-based_). Then click**Download**next to the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb49473bae.jpg)
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->

**6)** Click the link on the new window to download the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb79898ae2.png)

**7)**Open the file you’ve just downloaded and follow the on-screen instructions to install the update.

## Method 4: Run DISM and System File Checker

It’s also possible that your Windows Update can’t work because of the corrupted files on your operating system. Windows has two built-in tools called**SFC (System File Checker)**and**DISM (Deployment Imaging and Servicing Management)**that scan your computer and fix various issues on it. To run these tools:**1)** Click the**Start**button in the lower corner of your screen. Then type “_**cmd**_“. Right-click**Command Prompt**in the list of results and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbd72bc9a4.png)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**2)** In Command Prompt, to run System File Checker, type “_**sfc /scannow**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbe8bbd499.png)

**3)**To run DISM, type “_**dism /online /cleanup-image /restorehealth**_“. and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbeb602fef.png)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->

**4)**Wait for the process to complete, then restart your computer. After that, check to see if your Windows Update recovers.

## Method 5: Disable your antivirus

Sometimes your system can’t install new updates due to the interference from your antivirus software. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.

**IMPORTANT:** Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
##  Method 6: Update your drivers

You may get issues with your Windows Update if you are using wrong or out-of-date device drivers. You should regularly check your device drivers and keep them up to date so as to prevent your computer from many annoying issues. But you may not have the time or patience to check and update your drivers manually. If you want to have this done easily and automatically, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .**Driver Easy**will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee): **1) [Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.**2)**Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713a84159a4.png) **3)** Click the **Update** button next to each driver to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713ba9d0320.jpg)

## Method 7: Restore your Windows

Perhaps the issues with your Windows come from some changes you’ve made to your system. You can perform a system restore. This will restore your system from a restore point (you need to have one that has been created before your Windows Update issue occurs) undo those changes made. To do so:**1)**Click the **Start**button in the lower corner of your screen. Then type “_**restore**_“. In the list of results, click “**Create a restore point**“. The System Properties dialog will appear.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc666d51a9.png)

**2)** Click**System Restore**. The System Restore wizard will pop up.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc6fa8971e.png)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-the-ultimate-hunt-and-harvest-game-plan/"><u>[New] 2024 Approved  The Ultimate Hunt and Harvest Game Plan</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-free-youtube-artwork-hacks-snag-high-res-thumbnails-now-for-2024/"><u>[New] Free YouTube Artwork Hacks - Snag High-Res Thumbnails Now for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-memes-for-iphone/"><u>[New] Memes for iPhone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-navigating-social-media-creating-a-facebook-account-for-2024/"><u>[New] Navigating Social Media  Creating a Facebook Account for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-algorithm-behind-youtubes-post-upload-logic/"><u>[New] The Algorithm Behind YouTube's Post-Upload Logic</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/hich-video-platform-suits-you-better-tiktok-or-youtube-shorts/"><u>[New] Which Video Platform Suits You Better  TikTok or YouTube Shorts?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-windows-10-stuck-on-welcome-screen-quickly-and-easily/"><u>[Solved] | Windows 10 Stuck on Welcome Screen | Quickly & Easily</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-secret-social-scrolls-best-kept-facebook-memes/"><u>[Updated] In 2024, Secret Social Scrolls  Best-Kept Facebook Memes</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-preeminent-5-photo-background-changer-tools-iphone-x87-edition/"><u>2024 Approved  Preeminent 5 Photo Background Changer Tools  IPhone X/8/7 Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-the-critical-error-the-semaphore-timeout-deadline-exceeded-code-0x80070079/"><u>Addressing the Critical Error: The Semaphore Timeout Deadline Exceeded - Code 0X80070079</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/aiming-high-selecting-the-best-webcams-for-live-gameplay-streams/"><u>Aiming High  Selecting the Best Webcams for Live Gameplay Streams</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/all-you-need-to-know-about-mega-greninja-for-realme-12-5g-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-samsung-galaxy-z-fold-5-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Samsung Galaxy Z Fold 5 is off? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/drive-engagement-with-instagram-top-10-video-marketing-ideas-unveiled/"><u>Drive Engagement with Instagram  Top 10 Video Marketing Ideas Unveiled</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/explore-best-selections-for-youtube-ringtone-downloads/"><u>Explore Best Selections for YouTube Ringtone Downloads</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-sticky-keyboard-issues-on-your-hp-laptop-simple-solutions/"><u>Fixing Sticky Keyboard Issues on Your HP Laptop - Simple Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-11-upstart-hiccups-steps-for-a-smooth-boot-process/"><u>Fixing Windows 11 Upstart Hiccups: Steps for a Smooth Boot Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-correcting-usb-connectivity-issues-dealing-with-unknown-devices-and-port-reset-failures-on-windows-11/"><u>Guide: Correcting USB Connectivity Issues - Dealing with Unknown Devices and Port Reset Failures on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-overcoming-the-persistent-error-code-0x80072f8f-in-windows-11-and-10/"><u>Guide: Overcoming the Persistent Error Code 0X80072F8F in Windows 11 and 10</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/h501x4-fpv-quadcopter-unveiled-review-breakdown-for-2024/"><u>H501X4 FPV Quadcopter Unveiled - Review Breakdown for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-error-unknown-usb-device-descriptor-request-failed-on-windows-a-step-by-step-guide/"><u>How to Fix the Error 'Unknown USB Device - Descriptor Request Failed' On Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-the-problem-of-non-starting-hosted-networks-on-windows-10-devices/"><u>How to Overcome the Problem of Non-Starting Hosted Networks on Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-windows-update-or-installation-glitch-tips-for-resolving-error-0x80070643/"><u>How to Overcome Window's Update or Installation Glitch: Tips for Resolving Error 0X80070643</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-the-persistent-windows-update-issue-error-8007000e/"><u>How to Resolve the Persistent Windows Update Issue: Error 8007000E</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-note-12r-phone-without-pin-by-drfone-android/"><u>How to Unlock Xiaomi Redmi Note 12R Phone without PIN</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-cut-to-a-new-beginning-four-fade-techniques/"><u>In 2024, Cut to a New Beginning  Four Fade Techniques</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-logitechs-premium-4k-webcam-full-review-and-usability-insights/"><u>In 2024, Logitech's Premium 4K Webcam - Full Review & Usability Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206718516-laptop-mouse-malfunctions-heres-how-to-restore-functionality-and-beat-the-lag/"><u>Laptop Mouse Malfunctions? Here's How to Restore Functionality and Beat the Lag!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-for-windows-10s-troublesome-0xc1900208-update-issue/"><u>Mastering the Fix for Windows 10'S Troublesome 0XC1900208 Update Issue</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/masterpiece-collaborations-a-list-of-top-photo-and-video-making-maestros-with-music/"><u>Masterpiece Collaborations  A List of Top Photo & Video Making Maestros with Music</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-wudfhostexe-for-better-cpu-usage-on-your-windows-11-device/"><u>Optimizing wudfhost.exe for Better CPU Usage on Your Windows 11 Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-code-24-restoring-missing-devices-on-your-windows-pc/"><u>Overcoming Code 24: Restoring Missing Devices on Your Windows PC</u></a></li>
<li><a href="https://extra-tips.techidaily.com/prime-directors-cut-trailers/"><u>Prime Director's Cut Trailers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-a-seamless-minecraft-adventure-overcoming-performance-lags/"><u>Quick Solutions for a Seamless Minecraft Adventure: Overcoming Performance Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-cannot-reach-windows-installer-service-problem-efficiently/"><u>Resolving the 'Cannot Reach Windows Installer Service' Problem Efficiently</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-directx-troubles-in-call-of-duty-modern-warfare-2-a-step-by-step-guide/"><u>Solving DirectX Troubles in Call of Duty: Modern Warfare 2 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-correcting-livekernelevent-error-code-117/"><u>Step-by-Step Solution: Correcting LiveKernelEvent Error Code 117</u></a></li>
<li><a href="https://win-howtos.techidaily.com/system-rests-to-cool-down-post-gaming/"><u>System Rests to Cool Down Post-Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-successful-update-of-windows-11-without-hitches/"><u>Troubleshooting Guide: Successful Update of Windows 11 Without Hitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-restore-your-lenovos-laptop-camera-functionality/"><u>Troubleshooting Tips: Restore Your Lenovo's Laptop Camera Functionality</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-srt-openedit-manual-for-mac-users/"><u>Ultimate SRT Open/Edit Manual for Mac Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-resolving-unplanned-boot-sequences-in-windows-11-devices/"><u>Understanding and Resolving Unplanned Boot Sequences in Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-cant-i-scroll-on-my-touchpad-master-the-fixes-for-smooth-operation/"><u>Why Can't I Scroll on My Touchpad? Master the Fixes for Smooth Operation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210659244-why-isnt-my-razer-keyboard-lighting-up-solutions-inside/"><u>Why Isn't My Razer Keyboard Lighting Up? Solutions Inside</u></a></li>
</ul></div>
