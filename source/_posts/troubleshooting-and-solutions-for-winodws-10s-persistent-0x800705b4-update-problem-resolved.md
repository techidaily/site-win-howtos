---
title: Troubleshooting & Solutions for Winodws 10'S Persistent 0X800705b4 Update Problem [Resolved]
date: 2024-08-23T14:03:39.151Z
updated: 2024-08-24T14:03:39.151Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting & Solutions for Winodws 10'S Persistent 0X800705b4 Update Problem [Resolved]
excerpt: This Article Describes Troubleshooting & Solutions for Winodws 10'S Persistent 0X800705b4 Update Problem [Resolved]
thumbnail: https://thmb.techidaily.com/7d954d5ef5beb31b578dcda4509d16e23f0ef0d1b79a76b01e4834ddb01328ea.jpg
---

## Troubleshooting the KB4056892 Error for Smooth Windows 10 Updates - Solved

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap787-300x95.png)

**Failed to install KB4056892** when you perform Windows Update on your Windows 10 PC? Don’t worry…  Although it’s incredibly frustrating, you’re definitely not the only person to experience this problem. Thousands of Windows 10 users have recently reported the very same issue. More importantly, you should be able to fix it pretty easily…

## **Try these fixes**

1. [**Running Windows Update Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. [**Restarting Windows Update service**](https://tools.techidaily.com/drivereasy/download/)
3. [**Setting the trustedInstaller service to auto start**](https://tools.techidaily.com/drivereasy/download/)
4. [**Running System File Checker**](https://tools.techidaily.com/drivereasy/download/)
5. [**Downloading update KB4056892 from Microsoft Update Catalog manually**](https://tools.techidaily.com/drivereasy/download/)
6. [**Pro tip: Want us to fix the problem for you?**](https://tools.techidaily.com/drivereasy/download/)

---

### **Fix 1: Running Windows Update Troubleshooter**

 Windows Update troubleshooter is a built-in tool that can help you analyze and resolve issues related to Windows update. Try running Windows Update troubleshooter to see if you can resolve this issue. Here is how to do it:

1. On your keyboard, press **the Windows logo key**  and type **troubleshoot** . In the list of search results, select **Troubleshoot**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap788.png)
2. In the pop-up window, select **Windows Update**   and click **Run the troubleshooter** . You’ll be prompted for permission. Click **Yes**   to run Windows Update troubleshooter.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap789.png)
3. Click **Apply this fix**   to continue.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap790.png)
4. Follow the on-screen instructions to troubleshoot this issue.

 Perform a Windows update again to see if you can install the update. If not, try the next fix, below.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
### **Fix 2: Restarting Windows Update service**

 You may run into this issue if there is something wrong with the Windows Update service. You can try restarting the Windows Update service to resolve this problem. Here’s how to do it:

1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog, then type **services.msc**  and press **Enter**  to open the Services window.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap791.png)
2. Right-click **Windows Update** and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap792.png)
3. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open **File Explorer** .  Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to go to the **DataStore**  folder.  

**`C:\Windows\SoftwareDistribution\DataStore`**  

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap794.png)
4. Delete all the files in the folder **DataStore**  .  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap795.png)  
 When all the files are deleted, you shall see “This folder is empty”.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
5. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open   **File Explorer**  . Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.  

**`C:\Windows\SoftwareDistribution\Download**  
**`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap796.png)
6. Delete all the files in the folder   **Download**  .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap797.png)  
 When all the files are deleted, you shall see “This folder is empty”.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
7. In the Services window, right-click **Windows Update** and select **Start**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap798.png)

 Check Windows Update again to see whether you can install the update. If not, try the next fix, below.

### **Fix 3: Setting the TrustedInstaller service to auto start**

 This issue may occur if you didn’t set the trustedInstaller service to auto start. So try setting the TrustedInstaller service to auto start before you install the update KB4056892\. Here is how to do it:

1. On your keyboard, press**the Windows logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Ctrl** ,**Shift** and**Enter** at the same time to**run Command Prompt as administrator** . You’ll be prompted for permission. Click**Yes** to open Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)
2. In Command Prompt, type the command line below and press enter:  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
**SC config trustedinstaller start=auto**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap800.png)
3. Close Command Prompt and restart your PC.

 Perform Windows Update again after your restart your PC. See if you can install the update KB4056892\. If you can install it, congratulations! You’ve fixed this issue.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
### **Fix 4: Running System File Checker**

**System File Checker**  can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

1. On your keyboard, press**the Windows logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Ctrl** ,**Shift** and**Enter** at the same time to**run Command Prompt as administrator** . You’ll be prompted for permission. Click**Yes** to open Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)
2. In Command Prompt, type the following command and press **Enter**  .  
**sfc /scannow**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap801.png)  
 It may take some time for the command operation to be completed.
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
3. When this command operation is completed, close Command Prompt.

Run Windows Update  again to check whether this fix works or not. If you still fail to install the update KB4056892 for your Windows system, try downloading it from Microsoft Update Catalog manually.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 5: Downloading the update KB4056892 from Microsoft Update Catalog manually**

 You can try downloading the updates you failed to install from **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)**  and install them manually. Here is how to do it:

1. Follow the instructions below to**view your system type** before you download the update KB4056892 from Microsoft Update Catalog manually:  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap802.png)  
    “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .
2. Visit[**Microsoft Update Catalog**](https://www.catalog.update.microsoft.com/home.aspx) .
3. Type**KB4056892**  and then click **Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap803.png)
4. In the list of search results, select right update for your operating system and click **Download**  .  
 If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap806.png)
5. In the pop-up window, click the link to start downloading the updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap807.png)
6. **Double-click** the downloaded file and follow the on-screen instructions to install the update.

See if you can install the update. If not, try the next fix, below.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Pro tip: Want us to fix the problem for you?**

 If none of the fixes above worked, or you just don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you.

 All you need to do is[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/) (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

**IMPORTANT:**  Please attach **the URL of this article** when you contact us, so we could help you resolve the problem ASAP. You can expect us to respond within two working days.

 You can contact us easily via the **Driver Easy Feedback tool** . To learn how to use this tool, please visit this link: [https://www.drivereasy.com/help55/feedback/](https://tools.techidaily.com/drivereasy/download/) .

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
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
<li><a href="https://facebook-video-footage.techidaily.com/new-channel-branding-hacks-10-must-use-online-tools-for-2024/"><u>[New] Channel Branding Hacks  10 Must-Use Online Tools for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-comprehensive-guide-to-viewing-facebook-videos-on-apple-tv-devices/"><u>[New] Comprehensive Guide to Viewing Facebook Videos on Apple TV Devices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-launching-an-impactful-instagram-live-session/"><u>[New] Launching an Impactful Instagram Live Session</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-colorful-cinematography-the-evolving-world-of-4k-chroma-blades/"><u>[Updated] Colorful Cinematography  The Evolving World of 4K Chroma Blades</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-stream-perfecting-tweets-with-correct-video-formats-for-2024/"><u>[Updated] Stream-Perfecting Tweets with Correct Video Formats for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-the-anatomy-of-apple-m1-chip-redefining-tech/"><u>2024 Approved  The Anatomy of Apple M1 Chip, Redefining Tech</u></a></li>
<li><a href="https://win-howtos.techidaily.com/baffled-by-sticky-keys-successfully-reinitialize-any-keyboard-in-no-time/"><u>Baffled by Sticky Keys? Successfully Reinitialize Any Keyboard in No Time</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-device-migration-issues-on-windows-10-a-step-by-step-guide/"><u>Bypassing Device Migration Issues on Windows 10 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/debugging-the-igfxem-module-a-comprehensive-fix-guide/"><u>Debugging the Igfxem Module: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-guide-overcoming-steam-write-disc-errors-quickly/"><u>Effortless Guide: Overcoming Steam Write Disc Errors Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eliminate-the-disappearing-act-fix-your-windows-11-touchpad-cursor-issues/"><u>Eliminate the Disappearing Act: Fix Your Windows 11 Touchpad Cursor Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eliminating-barriers-in-nvidia-deployment/"><u>Eliminating Barriers in NVIDIA Deployment</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/esteemed-experts-premium-instragram-highlight-designs-online/"><u>Esteemed Experts  Premium Instragram Highlight Designs Online</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-overcoming-windows-installation-issues-understanding-error-0x80070610/"><u>Expert Tips on Overcoming Windows Installation Issues: Understanding Error 0X800706[:10]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-safari-page-loading-problems-simple-steps-for-success/"><u>Fixing Safari Page Loading Problems - Simple Steps for Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-i-successfully-completed-my-pending-windows-update-at-100/"><u>How I Successfully Completed My Pending Windows Update at 100%%</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-ensuring-a-stable-connection-for-devices-pairing-via-bluetooth-on-windows-11/"><u>How to Fix: Ensuring a Stable Connection for Devices Pairing via Bluetooth on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-quickly-resolve-dota-2-error-code-2024-change-rendering-api-issue/"><u>How to Quickly Resolve Dota 2 Error Code 2024: Change Rendering API Issue</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-c110-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on C110</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209101959-how-to-restore-the-missing-d3dx939dll-file-and-fix-related-issues-quickly/"><u>How To Restore The Missing D3DX9_39.dll File & Fix Related Issues Quickly!</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-7-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 7 without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/ideal-acquisitions-starting-off-with-profitable-youtube-channel-buys/"><u>Ideal Acquisitions  Starting Off with Profitable YouTube Channel Buys</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Samsung Galaxy F15 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205290979-lost-in-no-sense-fix-your-sd-card/"><u>Lost in No-Sense: Fix Your SD Card!</u></a></li>
<li><a href="https://youtube-help.techidaily.com/monetization-verification-maximizing-streamer-incomes-for-2024/"><u>Monetization Verification  Maximizing Streamer Incomes for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-download-compatible-drivers-for-arduino-mega-2560/"><u>Quick Download: Compatible Drivers for Arduino Mega 2560</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-guide-speeding-up-your-league-of-legends-installation/"><u>Quick Guide: Speeding Up Your League of Legends Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205634049-quickly-restore-bluetooth-functionality-on-your-windows-11-pc-easy-methods-inside/"><u>Quickly Restore Bluetooth Functionality on Your Windows 11 PC: Easy Methods Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-when-your-windows-11-version-1607-update-wont-go-through/"><u>Solving the Problem: When Your Windows 11 (Version 1607) Update Won't Go Through</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-a-non-functional-mouse-on-your-computer-screen/"><u>Step-by-Step Guide: Resolving a Non-Functional Mouse on Your Computer Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-laptops-experiencing-constant-whiteblack-screens/"><u>Step-by-Step Solutions for Laptops Experiencing Constant White/Black Screens</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-the-common-error-0x80071ac3-volume-issues/"><u>Step-by-Step Solutions for the Common Error: 0X80071AC3 - Volume Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/surface-pro-4-active-pen-malfunctions-heres-how-you-can-resolve-them-easily/"><u>Surface Pro 4 Active Pen Malfunctions? Here's How You Can Resolve Them Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-fix-for-invisible-wi-fi-networks-on-a-windows-11-system/"><u>The Fix for Invisible Wi-Fi Networks on a Windows 11 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210590262-troubleshoot-your-unresponsive-dns-quick-and-effective-solutions/"><u>Troubleshoot Your Unresponsive DNS: Quick & Effective Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-pitch-black-display-at-monster-hunter-world-startup/"><u>Troubleshooting a Pitch-Black Display at Monster Hunter: World Startup</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-bluetooth-issues-why-your-device-is-paired-but-remains-unconnected-in-windows-11/"><u>Troubleshooting Bluetooth Issues: Why Your Device Is Paired but Remains Unconnected in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-when-your-computers-touchpad-fails/"><u>Troubleshooting Steps When Your Computer's Touchpad Fails</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fixing-the-non-responsive-right-click-function-on-a-windows-10-system/"><u>Troubleshooting: Fixing the Non-Responsive Right-Click Function on a Windows 10 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-overcome-your-pcs-perpetual-startup-loop/"><u>Troubleshooting: Overcome Your PC's Perpetual Startup Loop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fixes-for-common-oculus-equipment-failures-in-the-new-year-of-2024/"><u>Ultimate Fixes for Common Oculus Equipment Failures in the New Year of 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultra-wideband-uwb/"><u>Ultra-Wideband (UWB):</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208583632-winning-against-the-incorrect-side-by-side-config-error-on-windows-11-solutions-within/"><u>Winning Against the 'Incorrect Side by Side Config' Error on Windows 11 - Solutions Within</u></a></li>
</ul></div>
