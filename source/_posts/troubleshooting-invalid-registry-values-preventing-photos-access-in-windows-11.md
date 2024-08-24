---
title: Troubleshooting Invalid Registry Values Preventing Photos Access in Windows 11
date: 2024-08-23T14:02:46.116Z
updated: 2024-08-24T14:02:46.116Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Invalid Registry Values Preventing Photos Access in Windows 11
excerpt: This Article Describes Troubleshooting Invalid Registry Values Preventing Photos Access in Windows 11
thumbnail: https://thmb.techidaily.com/503f764ce718cdd5118d7c5be0e25d96b4338086cc102ad3bcea32f94e910963.jpg
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
**3)** On Windows Update, note down the system updates that failed to install. (You may need to get the information from the update history.)

 Note down the codes of these updates that start with “**KB** “.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fafbba7758.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb0182b995.png)

**4)**Go to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)** . Then search for the updates you have failed to install.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb3a1da130.jpg)

**5)** In the search results, find the update that matches your**operating system**and**system type**(_x86-,_ _x64- or ARM64-based_). Then click**Download**next to the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb49473bae.jpg)

**6)** Click the link on the new window to download the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb79898ae2.png)

**7)**Open the file you’ve just downloaded and follow the on-screen instructions to install the update.

## Method 4: Run DISM and System File Checker

It’s also possible that your Windows Update can’t work because of the corrupted files on your operating system. Windows has two built-in tools called**SFC (System File Checker)**and**DISM (Deployment Imaging and Servicing Management)**that scan your computer and fix various issues on it. To run these tools:**1)** Click the**Start**button in the lower corner of your screen. Then type “_**cmd**_“. Right-click**Command Prompt**in the list of results and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbd72bc9a4.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
**2)** In Command Prompt, to run System File Checker, type “_**sfc /scannow**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbe8bbd499.png)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**3)**To run DISM, type “_**dism /online /cleanup-image /restorehealth**_“. and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbeb602fef.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
**4)**Wait for the process to complete, then restart your computer. After that, check to see if your Windows Update recovers.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## Method 5: Disable your antivirus

Sometimes your system can’t install new updates due to the interference from your antivirus software. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.

**IMPORTANT:** Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

##  Method 6: Update your drivers

You may get issues with your Windows Update if you are using wrong or out-of-date device drivers. You should regularly check your device drivers and keep them up to date so as to prevent your computer from many annoying issues. But you may not have the time or patience to check and update your drivers manually. If you want to have this done easily and automatically, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .**Driver Easy**will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee): **1) [Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.**2)**Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713a84159a4.png) **3)** Click the **Update** button next to each driver to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713ba9d0320.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 7: Restore your Windows

Perhaps the issues with your Windows come from some changes you’ve made to your system. You can perform a system restore. This will restore your system from a restore point (you need to have one that has been created before your Windows Update issue occurs) undo those changes made. To do so:**1)**Click the **Start**button in the lower corner of your screen. Then type “_**restore**_“. In the list of results, click “**Create a restore point**“. The System Properties dialog will appear.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc666d51a9.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
**2)** Click**System Restore**. The System Restore wizard will pop up.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc6fa8971e.png)

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-the-essential-voice-manual-for-tiktok-creators/"><u>[New] 2024 Approved  The Essential Voice Manual for TikTok Creators</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-ultimate-list-of-excellent-4k-cameras-for-2024/"><u>[New] Ultimate List of Excellent 4K Cameras for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-navigating-to-superior-cloud-solutions-for-your-needs/"><u>[Updated] 2024 Approved  Navigating to Superior Cloud Solutions for Your Needs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-syncing-soundscape-and-scene-editing-tips-for-canva-videographers/"><u>[Updated] Syncing Soundscape and Scene  Editing Tips for Canva Videographers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corsair-hs50-headset-mic-failures-heres-how-to-fix-and-restore-functionality/"><u>Corsair HS50 Headset Mic Failures? Here's How to Fix and Restore Functionality</u></a></li>
<li><a href="https://win-answers.techidaily.com/defeat-the-stubborn-start-up-solving-minecraft-loading-issues/"><u>Defeat the Stubborn Start-Up: Solving Minecraft Loading Issues</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/earning-power-through-engagement-ajays-success-on-youtube-monetization-for-2024/"><u>Earning Power Through Engagement  Ajay’s Success on YouTube Monetization for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-when-your-razer-synapse-device-wont-pair/"><u>Effective Solutions for When Your Razer Synapse Device Won't Pair</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ensuring-seamless-sleep-in-windows-11/"><u>Ensuring Seamless Sleep in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-update-issue-how-to-resolve-the-0x80070490-error/"><u>Fixing the Windows Update Issue: How to Resolve the 0X80070490 Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/flawless-typing-ahead-diagnosing-and-fixing-bluetooth-keyboard-pairing-failures-with-laptops-or-desktops/"><u>Flawless Typing Ahead: Diagnosing and Fixing Bluetooth Keyboard Pairing Failures with Laptops or Desktops</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/glow-dynamics-enhancing-visual-storytelling-through-lighting-for-2024/"><u>Glow Dynamics  Enhancing Visual Storytelling Through Lighting for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-address-and-fix-constant-crashes-of-battlefield-2042-on-your-computer/"><u>How to Address and Fix Constant Crashes of Battlefield 2042 on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-enhance-your-gaming-experience-by-reducing-fallout-4-latency-tips/"><u>How to Enhance Your Gaming Experience by Reducing Fallout 4 Latency (Tips )</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-itel-p55-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Itel P55 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-specified-file-missing-issues-successfully/"><u>How to Fix 'Specified File Missing' Issues Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-printer-driver-not-found-on-your-windows-pc-fixed/"><u>How to Overcome 'Printer Driver Not Found' On Your Windows PC [FIXED]</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-stop-airpods-from-switching-between-apple-devices/"><u>How to Stop AirPods From Switching Between Apple Devices</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-tecno-spark-20-proplus-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Tecno Spark 20 Pro+ Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-the-security-questions-of-your-apple-id-on-your-iphone-11-pro-by-drfone-ios/"><u>In 2024, How To Reset the Security Questions of Your Apple ID On Your iPhone 11 Pro</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/melodies-for-millions-insta-music-secrets-for-2024/"><u>Melodies for Millions  Insta Music Secrets for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/process-halted-no-execution/"><u>Process Halted: No Execution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-clipboard-problems-on-windows-11-computers/"><u>Resolved! Troubleshooting Clipboard Problems on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-driver-failure-message-due-to-incorrect-user-settings/"><u>Resolving the 'Driver Failure' Message Due to Incorrect User Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-login-issues-fixing-user-profile-service-failures/"><u>Resolving Windows 11 Login Issues: Fixing User Profile Service Failures</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-a05s-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy A05s Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-audio-renderer-repair-tutorial-for-smooth-youtube-experience-in-windows-10-environment/"><u>Step-by-Step Audio Renderer Repair Tutorial for Smooth YouTube Experience in Windows 10 Environment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-making-your-dvd-playable-on-a-windows-system/"><u>Step-by-Step Guide to Making Your DVD Playable on a Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-unresponsive-file-explorer-in-windows-10-environments/"><u>Step-by-Step Solutions for Unresponsive File Explorer in Windows 10 Environments</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-10-drone-propeller-choices-for-enhanced-aerial-mobility/"><u>Top 10 Drone Propeller Choices for Enhanced Aerial Mobility</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-windows-media-source-errors-for-games/"><u>Troubleshooting and Resolving Windows Media Source Errors for Games</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-error-code-31-on-your-pc-essential-tips-for-windows-users/"><u>Troubleshooting Error Code 31 on Your PC - Essential Tips for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-your-non-responsive-bluetooth-mouse-on-a-pc/"><u>Troubleshooting Guide: Fixing Your Non-Responsive Bluetooth Mouse on a PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-repair-a-non-functional-windows-11-start-menu/"><u>Troubleshooting Guide: How to Repair a Non-Functional Windows 11 Start Menu</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win10-renders-computer-inactive-suddenly/"><u>Win10 Renders Computer Inactive Suddenly</u></a></li>
</ul></div>
