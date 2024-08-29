---
title: Overcoming Windows 11'S 0X802e401c Update Malfunction
date: 2024-08-28T00:24:51.848Z
updated: 2024-08-29T00:24:51.848Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Overcoming Windows 11'S 0X802e401c Update Malfunction
excerpt: This Article Describes Overcoming Windows 11'S 0X802e401c Update Malfunction
thumbnail: https://thmb.techidaily.com/852a46d71ad08464710a61d161bf50e16562d6afe64893bd392e2b875addd5c7.jpg
---

## Overcoming Problems with Windows 10 Version 1903 Update (KB4056892) – Solutions Inside

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
### **Fix 2: Restarting Windows Update service**

 You may run into this issue if there is something wrong with the Windows Update service. You can try restarting the Windows Update service to resolve this problem. Here’s how to do it:

1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog, then type **services.msc**  and press **Enter**  to open the Services window.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap791.png)
2. Right-click **Windows Update** and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap792.png)
3. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open **File Explorer** .  Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to go to the **DataStore**  folder.  
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**`C:\Windows\SoftwareDistribution\DataStore`**  

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap794.png)
4. Delete all the files in the folder **DataStore**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap795.png)  
 When all the files are deleted, you shall see “This folder is empty”.
5. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open   **File Explorer**  . Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.  

**`C:\Windows\SoftwareDistribution\Download**  
**`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap796.png)
6. Delete all the files in the folder   **Download**  .  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap797.png)  
 When all the files are deleted, you shall see “This folder is empty”.
7. In the Services window, right-click **Windows Update** and select **Start**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap798.png)

 Check Windows Update again to see whether you can install the update. If not, try the next fix, below.

### **Fix 3: Setting the TrustedInstaller service to auto start**

 This issue may occur if you didn’t set the trustedInstaller service to auto start. So try setting the TrustedInstaller service to auto start before you install the update KB4056892\. Here is how to do it:

1. On your keyboard, press**the Windows logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Ctrl** ,**Shift** and**Enter** at the same time to**run Command Prompt as administrator** . You’ll be prompted for permission. Click**Yes** to open Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)
2. In Command Prompt, type the command line below and press enter:  
**SC config trustedinstaller start=auto**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap800.png)
3. Close Command Prompt and restart your PC.

 Perform Windows Update again after your restart your PC. See if you can install the update KB4056892\. If you can install it, congratulations! You’ve fixed this issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
### **Fix 4: Running System File Checker**

**System File Checker**  can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

1. On your keyboard, press**the Windows logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Ctrl** ,**Shift** and**Enter** at the same time to**run Command Prompt as administrator** . You’ll be prompted for permission. Click**Yes** to open Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)
2. In Command Prompt, type the following command and press **Enter**  .  
**sfc /scannow**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap801.png)  
 It may take some time for the command operation to be completed.
3. When this command operation is completed, close Command Prompt.

Run Windows Update  again to check whether this fix works or not. If you still fail to install the update KB4056892 for your Windows system, try downloading it from Microsoft Update Catalog manually.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 5: Downloading the update KB4056892 from Microsoft Update Catalog manually**

 You can try downloading the updates you failed to install from **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)**  and install them manually. Here is how to do it:

1. Follow the instructions below to**view your system type** before you download the update KB4056892 from Microsoft Update Catalog manually:  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap799.png)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
   ![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap802.png)  
    “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Visit[**Microsoft Update Catalog**](https://www.catalog.update.microsoft.com/home.aspx) .
3. Type**KB4056892**  and then click **Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap803.png)
4. In the list of search results, select right update for your operating system and click **Download**  .  
 If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap806.png)
5. In the pop-up window, click the link to start downloading the updates.  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap807.png)
6. **Double-click** the downloaded file and follow the on-screen instructions to install the update.

See if you can install the update. If not, try the next fix, below.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/-easy-youtube-audio-extraction-methods-free-and-secure/"><u>[New] 3 Easy YouTube Audio Extraction Methods  Free & Secure</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-aerial-titans-clash-dji-and-gopros-quest/"><u>[New] Aerial Titans Clash  DJI and GoPro's Quest</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-pro-monitor-snapshot-software-w10-for-2024/"><u>[New] Pro Monitor Snapshot Software W10 for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-reducing-excessive-encoding-obs-broadcast-for-2024/"><u>[New] Reducing Excessive Encoding (OBS Broadcast) for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-expert-tips-to-seamlessly-retrieve-youtube-srt-subtitles/"><u>[Updated] Expert Tips to Seamlessly Retrieve YouTube SRT Subtitles</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-navigating-through-vrs-bright-side-and-dark-hole/"><u>[Updated] Navigating Through VR's Bright Side & Dark Hole</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-premier-images-backup-portals/"><u>2024 Approved  Premier Images Backup Portals</u></a></li>
<li><a href="https://extra-information.techidaily.com/android-mastery-for-virtual-reality-and-panoramic-videos-for-2024/"><u>Android Mastery for Virtual Reality & Panoramic Videos for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-the-future-of-virtual-health-advice-7-compelling-reasons-to-trust-ai-in-wellness/"><u>ChatGPT: The Future of Virtual Health Advice - 7 Compelling Reasons to Trust AI in Wellness</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-zte-nubia-flip-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for ZTE Nubia Flip 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-boosting-world-of-warcraft-speed-and-reducing-lag/"><u>Comprehensive Guide: Boosting World of Warcraft Speed & Reducing Lag</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209839104-csgo-crash-woes-heres-how-you-can-achieve-a-smooth-gaming-experience/"><u>CS:GO Crash Woes? Here's How You Can Achieve a Smooth Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-eliminating-windows-11-screenshake-problem/"><u>Effective Solutions for Eliminating Window's 11 Screenshake Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/end-the-loop-expert-tips-for-fixing-recurring-restart-issues-on-windows-1110/"><u>End the Loop: Expert Tips for Fixing Recurring Restart Issues on Windows 11/10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/eradicating-scam-alerts-solutions-for-google-chromes-fake-critical-error/"><u>Eradicating Scam Alerts: Solutions for Google Chrome's Fake Critical Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-requirement-compatible-with-directx-11-gpus-only-to-enable-engine-usage/"><u>Essential Requirement: Compatible with DirectX 11 GPUs Only to Enable Engine Usage</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-the-issue-how-to-restore-your-discord-overlay-feature/"><u>Fixing the Issue: How to Restore Your Discord Overlay Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-successfully-shutting-down-a-frozen-computer-running-windows-11-fixed/"><u>Guide to Successfully Shutting Down a Frozen Computer Running Windows 11 [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-quickly-start-your-pc-addressing-windows-7-boot-latency-issues/"><u>How to Quickly Start Your PC: Addressing Windows 7 Boot Latency Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-your-wacom-stylus-when-it-fails-to-work-on-windows-11-or-windows-10-systems/"><u>How to Repair Your Wacom Stylus When It Fails to Work on Windows 11 or Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-casting-functionality-on-windows-10-a-step-by-step-solution/"><u>How to Restore Casting Functionality on Windows 10 - A Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-overcome-windows-system-error-0xc00000e9-a-comprehensive-tutorial/"><u>How to Successfully Overcome Windows System Error 0XC00000E9 – A Comprehensive Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-when-your-computer-is-frozen-during-windows-setup/"><u>How to Troubleshoot When Your Computer Is Frozen During Windows Setup</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On iPhone 14 Pro Max</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-polishing-the-final-product-perfect-for-instagrams-audience/"><u>In 2024, Polishing the Final Product  Perfect for Instagram's Audience</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-streamline-your-youtube-video-process-with-faster-techniques/"><u>In 2024, Streamline Your YouTube Video Process with Faster Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reset-or-refresh-mastering-the-easy-ways-to-reboot-windows-10/"><u>Reset or Refresh? Mastering the Easy Ways to Reboot Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-elevated-cpu-consumption-troubleshooting-wudfhostexe-on-windows-11/"><u>Resolving Elevated CPU Consumption: Troubleshooting WUDFHost.exe on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-volume-is-dirty-issue-understanding-error-0x80071ac3/"><u>Solving the 'Volume Is Dirty' Issue - Understanding Error 0X80071AC3</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-tnm-system-is-essential-for-accurate-lung-cancer-staging-and-treatment-planning/"><u>The TNM System Is Essential for Accurate Lung Cancer Staging and Treatment Planning.</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-strategies-leveraging-chatgpt-for-educational-success/"><u>Top 5 Strategies: Leveraging ChatGPT for Educational Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixes-for-a-non-functional-corsair-illuminated-keyboard/"><u>Troubleshooting and Fixes for a Non-Functional Corsair Illuminated Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-overcoming-slow-shutdown-woes-in-windows-11-systems/"><u>Troubleshooting and Overcoming Slow Shutdown Woes in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-non-responsive-shift-key/"><u>Troubleshooting Guide: Fixing a Non-Responsive Shift Key</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-overcoming-windows-10-build-1803-upgrade-failures/"><u>Troubleshooting Guide: Overcoming Windows 10 Build 1803 Upgrade Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missing-os-errors-on-your-computer-easy-fixes-and-best-practices/"><u>Troubleshooting Missing OS Errors on Your Computer - Easy Fixes and Best Practices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-the-failed-device-descriptor-request-on-usbs-guide/"><u>Troubleshooting Tips for the Failed Device Descriptor Request on USBs [Guide]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-usb-connections-resolve-port-reset-failed-messages-in-windows-10/"><u>Troubleshooting USB Connections: Resolve ‘Port Reset Failed’ Messages in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-10-update-issues-solutions-for-a-freezing-or-stalled-system/"><u>Troubleshooting Windows 10 Update Issues: Solutions for a Freezing or Stalled System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-11-issues-using-sfcdism-tools-a-comprehensive-guide/"><u>Troubleshooting Windows 11 Issues Using SFC/DISM Tools – A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-how-to-troubleshoot-and-repair-your-ps4-microphone/"><u>Ultimate Guide: How to Troubleshoot and Repair Your PS4 Microphone</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-itel-p40plus-by-fonelab-android-recover-data/"><u>Undelete lost data from Itel P40+</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-repairing-the-constant-usb-device-unrecognized-message/"><u>Understanding and Repairing the Constant 'USB Device Unrecognized' Message</u></a></li>
<li><a href="https://win-howtos.techidaily.com/usb-troubleshooting-made-easy-overcoming-the-port-reset-failed-error-in-windows-11/"><u>USB Troubleshooting Made Easy: Overcoming the 'Port Reset Failed' Error in Windows 11</u></a></li>
</ul></div>
