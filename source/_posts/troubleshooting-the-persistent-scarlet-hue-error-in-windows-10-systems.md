---
title: Troubleshooting the Persistent Scarlet Hue Error in Windows 10 Systems
date: 2024-09-01T04:53:47.710Z
updated: 2024-09-02T04:53:47.710Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting the Persistent Scarlet Hue Error in Windows 10 Systems
excerpt: This Article Describes Troubleshooting the Persistent Scarlet Hue Error in Windows 10 Systems
thumbnail: https://thmb.techidaily.com/a44de758792af2fb67431bc0cd10b70e0176e5a8a3e2c53a5711bc4054272247.jpg
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

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## Method 3: Manually download and install updates

If Windows Update can’t help you download certain system updates, you can try doing so on your own. Microsoft has put all its system updates online, and you can download these updates and install them on your computer without the help of Windows Update. To manually download and install updates:**1)**Click the**Start**button in the lower left corner of your screen. Then type “_**information**_“. In the list of results, click**System Information**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c0faa09e19.png)

**2)**In the System Information window, check**System Type**. Its value is usually **x64-based** or **x86-based**(or sometimes**ARM64-based**).

 This is an important piece of information and you should note it down. It will be useful when you are looking for the updates that match your Windows later.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c104b5d2ee.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
**3)** On Windows Update, note down the system updates that failed to install. (You may need to get the information from the update history.)

 Note down the codes of these updates that start with “**KB** “.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fafbba7758.png)

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb0182b995.png)

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**4)**Go to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)** . Then search for the updates you have failed to install.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb3a1da130.jpg)

**5)** In the search results, find the update that matches your**operating system**and**system type**(_x86-,_ _x64- or ARM64-based_). Then click**Download**next to the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb49473bae.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
**6)** Click the link on the new window to download the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb79898ae2.png)

**7)**Open the file you’ve just downloaded and follow the on-screen instructions to install the update.

## Method 4: Run DISM and System File Checker

It’s also possible that your Windows Update can’t work because of the corrupted files on your operating system. Windows has two built-in tools called**SFC (System File Checker)**and**DISM (Deployment Imaging and Servicing Management)**that scan your computer and fix various issues on it. To run these tools:**1)** Click the**Start**button in the lower corner of your screen. Then type “_**cmd**_“. Right-click**Command Prompt**in the list of results and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbd72bc9a4.png)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
**2)** In Command Prompt, to run System File Checker, type “_**sfc /scannow**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbe8bbd499.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**3)**To run DISM, type “_**dism /online /cleanup-image /restorehealth**_“. and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbeb602fef.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**4)**Wait for the process to complete, then restart your computer. After that, check to see if your Windows Update recovers.

## Method 5: Disable your antivirus

Sometimes your system can’t install new updates due to the interference from your antivirus software. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.

**IMPORTANT:** Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Method 6: Update your drivers

You may get issues with your Windows Update if you are using wrong or out-of-date device drivers. You should regularly check your device drivers and keep them up to date so as to prevent your computer from many annoying issues. But you may not have the time or patience to check and update your drivers manually. If you want to have this done easily and automatically, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .**Driver Easy**will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee): **1) [Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.**2)**Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713a84159a4.png) **3)** Click the **Update** button next to each driver to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713ba9d0320.jpg)

## Method 7: Restore your Windows

Perhaps the issues with your Windows come from some changes you’ve made to your system. You can perform a system restore. This will restore your system from a restore point (you need to have one that has been created before your Windows Update issue occurs) undo those changes made. To do so:**1)**Click the **Start**button in the lower corner of your screen. Then type “_**restore**_“. In the list of results, click “**Create a restore point**“. The System Properties dialog will appear.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc666d51a9.png)

**2)** Click**System Restore**. The System Restore wizard will pop up.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc6fa8971e.png)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
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
<li><a href="https://fox-helps.techidaily.com/new-charting-the-course-to-cash-how-much-does-pewdopeep-make/"><u>[New] Charting the Course to Cash  How Much Does PewDoPeep Make?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-create-shareable-memes-with-adobe-photoshop/"><u>[Updated] Create Shareable Memes with Adobe Photoshop</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/67962671-2024-approved-elevate-your-videos-with-complimentary-banners-here/"><u>2024 Approved  Elevate Your Videos with Complimentary Banners, Here!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unique-identity-creation-accessible-logo-base-and-personal-customization-for-no-cost/"><u>2024 Approved  Unique Identity Creation  Accessible Logo Base & Personal Customization for No-Cost</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ac1st16dll-error-fixes-how-to-recover-or-prevent-it-from-disappearing/"><u>Ac1st16.dll Error Fixes - How to Recover or Prevent It From Disappearing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/civilization-vi-overcoming-the-compatibility-problems-between-game-and-gpu/"><u>Civilization VI: Overcoming the Compatibility Problems Between Game and GPU</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-to-restoring-ethernet-functionality-on-your-windows-10-and-7-device/"><u>Comprehensive Guide to Restoring Ethernet Functionality on Your Windows 10 & 7 Device</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-walkthrough-for-recording-and-sending-voice-messages-on-iphones/"><u>Comprehensive Walkthrough for Recording and Sending Voice Messages on iPhones</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-resolving-usb-port-failures-in-windows-10-and-11-computers-efficiently/"><u>Diagnosing and Resolving USB Port Failures in Windows 10 & 11 Computers Efficiently</u></a></li>
<li><a href="https://extra-information.techidaily.com/do-shopping-blogs-have-a-payment-scheme-for-reports/"><u>Do Shopping Blogs Have a Payment Scheme for Reports?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortlessly-fix-the-constant-reboot-problem-in-windows-10/"><u>Effortlessly Fix the Constant Reboot Problem in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expand-your-systems-memory-fixing-the-not-enough-storage-error/"><u>Expand Your System's Memory: Fixing the Not-Enough-Storage Error</u></a></li>
<li><a href="https://driver-install.techidaily.com/fasten-driver-updates-for-logitech-audio-cables/"><u>Fasten Driver Updates for Logitech Audio Cables</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-cause-of-window-10s-screen-tremors-a-step-by-step-guide/"><u>Fixing the Cause of Window 10'S Screen Tremors: A Step-by-Step Guide</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/guide-to-setting-up-your-android-as-a-personal-wi-fi-hotspot/"><u>Guide to Setting Up Your Android as a Personal Wi-Fi Hotspot</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-insufficient-memory-on-rdr2-boost-your-gaming-experience/"><u>How to Fix 'Insufficient Memory' On RDR2 - Boost Your Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-microsofts-wireless-display-adapter-when-it-fails-to-pair-with-windows-10/"><u>How to Fix Microsoft's Wireless Display Adapter When It Fails to Pair with Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hp-laptop-keyboard-troubles-heres-how-to-make-it-work-again/"><u>HP Laptop Keyboard Troubles? Here's How to Make It Work Again</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-vivo-s17e-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Vivo S17e Activity | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-mouse-pad-not-working-in-windows-1187-fixed/"><u>Lenovo Mouse Pad Not Working in Windows 11/8/7 [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-fixing-windows-10-bluetooth-pairing-woes-tips-and-tricks/"><u>Master the Art of Fixing Windows 10 Bluetooth Pairing Woes: Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-solution-for-system-error-5-on-windows-10-7-and-8-a-complete-fix-tutorial/"><u>Master the Solution for System Error 5 on Windows 10, 7, and 8: A Complete Fix Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-windows-11-error-code-0x80070426-step-by-step-troubleshooting-guide/"><u>Resolve Windows 11 Error Code 0X80070426: Step-by-Step Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-volume-muting-glitches-for-smooth-playback-experience/"><u>Resolving Windows 11 Volume Muting Glitches for Smooth Playback Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-your-disappeared-desktop-icons-with-these-simple-tips-for-windows-11-users/"><u>Restore Your Disappeared Desktop Icons with These Simple Tips for Windows 11 Users</u></a></li>
<li><a href="https://techidaily.com/solved-photos-disappeared-from-iphone-12-pro-max-suddenly-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Solved Photos Disappeared from iPhone 12 Pro Max Suddenly | Stellar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-the-issue-of-svchostexes-elevated-cpu-usage-in-windows-10-systems-steps-to-resolve/"><u>Tackling the Issue of Svchost.exe's Elevated CPU Usage in Windows 10 Systems: Steps to Resolve</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-windows-11-pc-setup-problems-effectively-solved/"><u>Troubleshooting and Fixing Windows 11 PC Setup Problems Effectively [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-connection-issues-with-airpods-on-windows-10-and-11/"><u>Troubleshooting Guide: Resolving Connection Issues with AirPods on Windows 10 and 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-correcting-the-dx11-feature-level-100-glitch-in-wwe-2k-battlegrounds/"><u>Troubleshooting Steps for Correcting the DX11 Feature Level 10.0 Glitch in WWE 2K Battlegrounds</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-lost-desktop-icons-glitch-on-windows-11-systems/"><u>Troubleshooting the Lost Desktop Icons Glitch on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-when-your-built-in-camera-wont-work-on-a-pc/"><u>Troubleshooting Tips: When Your Built-In Camera Won't Work on a PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-pc-how-to-restore-windows-1er-volume-control-functionality/"><u>Troubleshooting Your PC: How to Restore Windows 1Er Volume Control Functionality</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ultimate-guide-selecting-the-perfect-mouse-for-your-mac-in-202/"><u>Ultimate Guide: Selecting the Perfect Mouse for Your Mac in 202</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-microsoft-security-essentials-unveiling-the-causes-of-mssecuesexes-high-disk-consumption/"><u>Understanding Microsoft Security Essentials: Unveiling the Causes of mssecues.exe's High Disk Consumption</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-quick-connectivity-a-simple-way-to-enable-bluetooth-in-windows-11-and-10-systems/"><u>Unlocking Quick Connectivity: A Simple Way to Enable Bluetooth in Windows 11 & 10 Systems</u></a></li>
</ul></div>
