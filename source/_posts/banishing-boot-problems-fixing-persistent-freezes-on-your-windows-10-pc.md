---
title: "Banishing Boot Problems: Fixing Persistent Freezes on Your Windows 10 PC"
date: 2024-08-19T07:46:06.034Z
updated: 2024-08-20T07:46:06.034Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Banishing Boot Problems: Fixing Persistent Freezes on Your Windows 10 PC"
excerpt: "This Article Describes Banishing Boot Problems: Fixing Persistent Freezes on Your Windows 10 PC"
thumbnail: https://thmb.techidaily.com/b2c741db963ad00df201883adf5f82b0b65621c38ea9e6dfe43b98273ae04085.jpg
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**2)**In the System Information window, check**System Type**. Its value is usually **x64-based** or **x86-based**(or sometimes**ARM64-based**).

 This is an important piece of information and you should note it down. It will be useful when you are looking for the updates that match your Windows later.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c104b5d2ee.jpg)

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**3)** On Windows Update, note down the system updates that failed to install. (You may need to get the information from the update history.)

 Note down the codes of these updates that start with “**KB** “.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fafbba7758.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb0182b995.png)

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**4)**Go to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)** . Then search for the updates you have failed to install.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb3a1da130.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
**5)** In the search results, find the update that matches your**operating system**and**system type**(_x86-,_ _x64- or ARM64-based_). Then click**Download**next to the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb49473bae.jpg)

**6)** Click the link on the new window to download the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb79898ae2.png)

**7)**Open the file you’ve just downloaded and follow the on-screen instructions to install the update.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 4: Run DISM and System File Checker

It’s also possible that your Windows Update can’t work because of the corrupted files on your operating system. Windows has two built-in tools called**SFC (System File Checker)**and**DISM (Deployment Imaging and Servicing Management)**that scan your computer and fix various issues on it. To run these tools:**1)** Click the**Start**button in the lower corner of your screen. Then type “_**cmd**_“. Right-click**Command Prompt**in the list of results and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbd72bc9a4.png)

**2)** In Command Prompt, to run System File Checker, type “_**sfc /scannow**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbe8bbd499.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**3)**To run DISM, type “_**dism /online /cleanup-image /restorehealth**_“. and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbeb602fef.png)

**4)**Wait for the process to complete, then restart your computer. After that, check to see if your Windows Update recovers.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## Method 5: Disable your antivirus

Sometimes your system can’t install new updates due to the interference from your antivirus software. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.

**IMPORTANT:** Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

##  Method 6: Update your drivers

You may get issues with your Windows Update if you are using wrong or out-of-date device drivers. You should regularly check your device drivers and keep them up to date so as to prevent your computer from many annoying issues. But you may not have the time or patience to check and update your drivers manually. If you want to have this done easily and automatically, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .**Driver Easy**will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee): **1) [Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.**2)**Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713a84159a4.png) **3)** Click the **Update** button next to each driver to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713ba9d0320.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-simplified-processes-instantly-clearing-youtube-comments/"><u>[New] 2024 Approved  Simplified Processes  Instantly Clearing Youtube Comments</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-sonicscope-in-depth-auditory-evaluation/"><u>[New] 2024 Approved  SonicScope  In-Depth Auditory Evaluation</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-architects-of-unique-virtual-environments/"><u>[New] Architects of Unique Virtual Environments</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovateimages-ai-next-level-editing-excellence/"><u>[New] InnovateImages AI  Next-Level Editing Excellence</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-iphone-flash-optimization-tips/"><u>[New] IPhone Flash Optimization Tips</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-camstudio-2023-screen-recorder-insights-and-reviews/"><u>[Updated] CamStudio  2023 Screen Recorder Insights & Reviews</u></a></li>
<li><a href="https://article-helps.techidaily.com/capturing-breathtaking-photos-with-iphone-hdr/"><u>Capturing Breathtaking Photos with iPhone HDR</u></a></li>
<li><a href="https://win-howtos.techidaily.com/confirmed-lack-of-opengl-from-drivers/"><u>Confirmed: Lack of OpenGL From Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/exploring-windows-10-recovery-solutions-sfc-and-dism-explained/"><u>Exploring Windows 10 Recovery Solutions: SFC & DISM Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-tracking-pc-boot-speed-expert-advice-and-strategies/"><u>Fast-Tracking PC Boot Speed: Expert Advice and Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-previously-restricted-now-fully-accessible-content-unveiled/"><u>Fixed! Previously Restricted, Now Fully Accessible Content Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-wacom-device-driver-not-installed-problem-in-windows-11-environments/"><u>Fixing the 'Wacom Device Driver Not Installed' Problem in Windows 11 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-10-blue-screen-error-permanently/"><u>Fixing the Windows 10 Blue Screen Error Permanently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-xbox-one-audio-back-on-track-a-complete-guide/"><u>Getting Your Xbox One Audio Back on Track – A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-incompatible-drivers-lead-to-memory-problems-in-the-ftdi-bus-system/"><u>How Incompatible Drivers Lead to Memory Problems in the FTDI Bus System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-ensure-seamless-integration-of-airpods-with-windows-1011-essential-hacks/"><u>How to Ensure Seamless Integration of AirPods with Windows 10/11 - Essential Hacks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-invalid-registry-setting-making-photos-not-open-in-windows-continue-httpt4speccxresolve-invalid-registry-errors-on-windows-10/"><u>How to Fix the Invalid Registry Setting Making Photos Not Open in Windows [Continue] http://t4.spec.cx/resolve-invalid-registry-errors-on-windows-10/</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-clearing-up-black-screens-in-youtube-playback/"><u>In 2024, Clearing Up Black Screens in YouTube Playback</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-se-2020-apples-new-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone SE (2020), Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/joining-sonys-gaming-world-a-tutorial-on-psn-account-setup/"><u>Joining Sony’s Gaming World: A Tutorial on PSN Account Setup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-fixes-top-tips-for-resolving-oculus-equipment-malfunctions/"><u>Master the Fixes: Top Tips for Resolving Oculus Equipment Malfunctions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203444449-minecraft-multiplayer-lag-solve-your-lan-woes-here/"><u>Minecraft Multiplayer Lag? Solve Your LAN Woes Here</u></a></li>
<li><a href="https://win-howtos.techidaily.com/netflix-outage-guide-identifying-and-resolving-streaming-errors/"><u>Netflix Outage Guide – Identifying and Resolving Streaming Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-wireless-woes-a-beginners-guide-to-repairing-wifi-issues/"><u>Overcoming Wireless Woes: A Beginner’s Guide to Repairing WiFi Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211242910-resolve-your-windows-10-bluetooth-disappearance-problem-with-simple-steps/"><u>Resolve Your Windows 10 Bluetooth Disappearance Problem with Simple Steps!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-faulty-keyboard-during-system-startup/"><u>Resolved: Faulty Keyboard During System Startup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-graphic-glitches-a-solution-for-windows-11-and-10-images-issues/"><u>Resolving Graphic Glitches: A Solution for Windows 11 and 10 Images Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-svchostexes-excessive-cpu-drain-on-windows-10-a-complete-guide/"><u>Resolving svchost.exe's Excessive CPU Drain on Windows 10 - A Complete Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11-bluetooth-connection-errors-for-paired-devices-not-communicating/"><u>Resolving Windows 11 Bluetooth Connection Errors for Paired Devices Not Communicating</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-your-pcs-built-in-webcam-problems-with-these-tips-for-windows-users/"><u>Solve Your PC's Built-In Webcam Problems with These Tips for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-windows-710-devices-that-wont-charge/"><u>Troubleshooting Guide for Windows 7/10 Devices That Won't Charge</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-intermittent-disconnects-of-wireless-mouse-in-windows-11-and-10/"><u>Troubleshooting Guide: Fixing Intermittent Disconnects of Wireless Mouse in Windows 11 & 10</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/tune-up-guide-new-gadgets-reviewed-for-2024/"><u>Tune-Up Guide  New Gadgets Reviewed for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unpredicted-keystroke-pause/"><u>Unpredicted Keystroke Pause</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212525383-unveiling-remedies-overcoming-the-chrome-screen-turned-pitch-black/"><u>Unveiling Remedies: Overcoming the Chrome Screen Turned Pitch Black!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/upgrade-your-canon-eos-digital-rebel-xs-d530-with-the-newest-software-patches/"><u>Upgrade Your Canon EOS Digital Rebel XS (D530) with the Newest Software Patches</u></a></li>
</ul></div>
