---
title: "Resolving Connection Issues: Steps to Troubleshoot 'Cannot Connect to Remote Server'"
date: 2024-08-19T07:00:20.363Z
updated: 2024-08-20T07:00:20.363Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Connection Issues: Steps to Troubleshoot 'Cannot Connect to Remote Server'"
excerpt: "This Article Describes Resolving Connection Issues: Steps to Troubleshoot 'Cannot Connect to Remote Server'"
thumbnail: https://thmb.techidaily.com/6f7d0e2a43b07618a84ad4bb4532a87360d4eb5cc4017e6eac185e39f8838773.jpg
---

## Troubleshooting Persistent Windows Updates Issues - Solved

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c046d056cc.png)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c104b5d2ee.jpg)

**3)** On Windows Update, note down the system updates that failed to install. (You may need to get the information from the update history.)

 Note down the codes of these updates that start with “**KB** “.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fafbba7758.png)

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb0182b995.png)

**4)**Go to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)** . Then search for the updates you have failed to install.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb3a1da130.jpg)

**5)** In the search results, find the update that matches your**operating system**and**system type**(_x86-,_ _x64- or ARM64-based_). Then click**Download**next to the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb49473bae.jpg)

**6)** Click the link on the new window to download the update.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb79898ae2.png)

**7)**Open the file you’ve just downloaded and follow the on-screen instructions to install the update.

## Method 4: Run DISM and System File Checker

It’s also possible that your Windows Update can’t work because of the corrupted files on your operating system. Windows has two built-in tools called**SFC (System File Checker)**and**DISM (Deployment Imaging and Servicing Management)**that scan your computer and fix various issues on it. To run these tools:**1)** Click the**Start**button in the lower corner of your screen. Then type “_**cmd**_“. Right-click**Command Prompt**in the list of results and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbd72bc9a4.png)

**2)** In Command Prompt, to run System File Checker, type “_**sfc /scannow**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbe8bbd499.png)

**3)**To run DISM, type “_**dism /online /cleanup-image /restorehealth**_“. and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbeb602fef.png)

**4)**Wait for the process to complete, then restart your computer. After that, check to see if your Windows Update recovers.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
## Method 5: Disable your antivirus

Sometimes your system can’t install new updates due to the interference from your antivirus software. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.

**IMPORTANT:** Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

##  Method 6: Update your drivers

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
You may get issues with your Windows Update if you are using wrong or out-of-date device drivers. You should regularly check your device drivers and keep them up to date so as to prevent your computer from many annoying issues. But you may not have the time or patience to check and update your drivers manually. If you want to have this done easily and automatically, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .**Driver Easy**will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee): **1) [Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.**2)**Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713a84159a4.png) **3)** Click the **Update** button next to each driver to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713ba9d0320.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## Method 7: Restore your Windows

Perhaps the issues with your Windows come from some changes you’ve made to your system. You can perform a system restore. This will restore your system from a restore point (you need to have one that has been created before your Windows Update issue occurs) undo those changes made. To do so:**1)**Click the **Start**button in the lower corner of your screen. Then type “_**restore**_“. In the list of results, click “**Create a restore point**“. The System Properties dialog will appear.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc666d51a9.png)

**2)** Click**System Restore**. The System Restore wizard will pop up.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-chuckle-cache-the-best-humor-tweets-on-twitch/"><u>[New] In 2024, Chuckle Cache  The Best Humor Tweets on Twitch</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-discover-the-top-8-android-platforms-for-large-gatherings-for-2024/"><u>[Updated] Discover the Top 8 Android Platforms for Large Gatherings for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-subscribe-bonanza-thousands-acquired-for-just-5/"><u>[Updated] In 2024, Subscribe Bonanza  Thousands Acquired for Just $5</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-mobile-audio-speed-the-fastest-app-list/"><u>[Updated] Mobile Audio Speed  The Fastest App List</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-mathematics-behind-making-money-from-snippets/"><u>[Updated] The Mathematics Behind Making Money From Snippets</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-diy-unleashing-creative-power-in-animation-effects/"><u>2024 Approved  DIY  Unleashing Creative Power in Animation Effects</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-seamless-fb-to-mp4-conversion-service/"><u>2024 Approved  Seamless FB to MP4 Conversion Service</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-connectivity-problems-with-microsoft-defender-smartscreen-a-user-friendly-fix-guide/"><u>Addressing Connectivity Problems with Microsoft Defender SmartScreen: A User-Friendly Fix Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-samsung-galaxy-a05s-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Samsung Galaxy A05s? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/baffled-by-a-broken-laptop-mouse-discover-proven-techniques-to-restore-functionality/"><u>Baffled by a Broken Laptop Mouse? Discover Proven Techniques to Restore Functionality</u></a></li>
<li><a href="https://extra-information.techidaily.com/complete-visual-storytellers-guide-to-vsco-app-for-2024/"><u>Complete Visual Storyteller's Guide to VSCO App for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-browser-cache-errors-correcting-errcachemiss-on-google-chrome/"><u>Dealing with Browser Cache Errors: Correcting ERR_CACHE_MISS on Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-troubleshooting-for-missing-bluetooth-in-windows-11-step-by-step-tutorial/"><u>Easy Troubleshooting for Missing Bluetooth in Windows 11 - Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expedited-recover-lost-logildadll/"><u>Expedited: Recover Lost LogiLDA.dll</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-repairing-frequent-usb-disconnection-problems/"><u>Expert Tips on Repairing Frequent USB Disconnection Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-video-source-missing-error-on-monitors-a-detailed-guide/"><u>Fixing 'Video Source Missing' Error on Monitors – A Detailed Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-error-1053-strategies-for-prompt-start-up-and-control-of-services/"><u>Fixing Error 1053: Strategies for Prompt Start-Up and Control of Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-non-sleepy-windows-11-system/"><u>Fixing Non-Sleepy Windows 11 System</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/high-quality-streaming-choice-go-with-obs-or-fraps/"><u>High-Quality Streaming Choice  Go With OBS or Fraps?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-decide-on-msdatspeakerdll-management-preservation-or-purging/"><u>How to Decide on msdatspeaker.dll Management: Preservation or Purging</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-persistent-keyboard-lag-problems-on-windows-10-devices/"><u>How to Resolve Persistent Keyboard Lag Problems on Windows 10 Devices</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Honor X8b? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/integrating-social-networks-sharing-fb-videos-on-whatsapp/"><u>Integrating Social Networks  Sharing FB Videos on WhatsApp</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-issues-fix-inactive-letters-on-your-win-10-or-win-11-system-today/"><u>Keyboard Issues? Fix Inactive Letters on Your Win 10 or Win 11 System Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-pc-maintenance-with-windows-10s-built-in-repair-utilities-sfc-and-dism-explained/"><u>Mastering PC Maintenance with Windows 10'S Built-In Repair Utilities: SFC & DISM Explained</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-system-issues-by-updating-missing-integral-computer-media-drivers-now/"><u>Resolve System Issues by Updating Missing Integral Computer Media Drivers Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rev-up-your-game-with-clear-sounds-a-step-by-step-solution-to-fix-forza-horizon-4s-sound-problem/"><u>Rev Up Your Game with Clear Sounds: A Step-by-Step Solution to Fix Forza Horizon 4'S Sound Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-hp-laptops-dead-usb-port-with-this-proven-solution/"><u>Revive Your HP Laptop's Dead USB Port with This Proven Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/role-of-rituals/"><u>Role of Rituals</u></a></li>
<li><a href="https://facebook.techidaily.com/social-networks-side-effects-uncover-the-top-10-reasons-for-parting-with-facebook/"><u>Social Networks' Side Effects? Uncover the Top 10 Reasons for Parting with Facebook</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-the-problem-of-your-laptop-constantly-falling-asleep-simple-fixes/"><u>Solve the Problem of Your Laptop Constantly Falling Asleep - Simple Fixes!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-plugged-in-not-charging-issue-on-your-windows-surface/"><u>Solving the Plugged In, Not Charging Issue on Your Windows Surface</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-how-to-turn-on-and-use-bluetooth-on-your-pc-windows-1110/"><u>Step-by-Step Tutorial: How to Turn On and Use Bluetooth on Your PC (Windows 11/10)</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-oppo-f25-pro-5g-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Oppo F25 Pro 5G Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-guide-to-professional-level-notes-via-chatgpt/"><u>The Ultimate Guide to Professional-Level Notes via ChatGPT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-overcoming-limited-system-capacity-issues/"><u>Troubleshooting: Overcoming Limited System Capacity Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unavailable-microsoft-smartscreen-service-temporarily-offline/"><u>Unavailable: Microsoft SmartScreen Service Temporarily Offline</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-windows-10-update-hurdles-solve-code-0x800f0922-with-these-fixes/"><u>Winning Against Windows 10 Update Hurdles - Solve Code 0X800f0922 With These Fixes</u></a></li>
</ul></div>
