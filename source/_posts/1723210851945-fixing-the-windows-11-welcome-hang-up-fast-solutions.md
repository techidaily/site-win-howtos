---
title: "Fixing the Windows 11 Welcome Hang-Up: Fast Solutions!"
date: 2024-08-28T00:26:45.486Z
updated: 2024-08-29T00:26:45.486Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the Windows 11 Welcome Hang-Up: Fast Solutions!"
excerpt: "This Article Describes Fixing the Windows 11 Welcome Hang-Up: Fast Solutions!"
thumbnail: https://thmb.techidaily.com/48b583faa31b393aa904516c2278bd0e1546bcda1fa4122648e108e1ee1f91de.jpg
---

## Fixing the Endless Loop: Windows Update Stuck on 100 Percent - Solution Inside

 If you see the message **“Working on updates, 100% complete. Don’t turn off your computer”** when performing a Windows update, don’t worry!

 Although it’s incredibly frustrating, you’re not the only person to experience this issue. Thousands of Windows users have recently reported the very same issue. More importantly, you should be able to fix it pretty easily…

## Try these fixes

 Here’s a list of fixes that have resolved this problem for other Windows users. You don’t have to try them all. Just work your way through the list until you find the one that does the trick for you.

1. **[Remove any USB peripherals and wait for the update process to finish](#f1)**
2. **[Force restart your PC](#f2)**
3. **[Run Windows Update troubleshooter](#f3)**
4. **[Reset Windows Update components](#f4)**
5. **[Download updates from Microsoft Update Catalog manually](#f5)**
6. **[Pro tip: Want us to fix the problem for you?](#p)**

### Fix 1: Remove any USB peripherals and wait for the update process to finish

 If you seldom check for Windows updates, it may take a long time for Windows to complete the update process. Maybe your PC is not “stuck” at Windows update, and Windows is just configuring and installing update packages.

 If you temporarily don’t need to use your PC, you can just wait for 2 to 3 hours to see if the update process can be completed. If there are any USB devices (like printers, USB flash drives, etc.) connected to your PC, you can try removing them from your PC. Some Windows users reported that after they disconnect all the USB peripherals from their PCs, the update process completes quickly.

 See if this issue persists after you wait for 2 to 3 hours. If it persists, try the next fix below to force restart your PC.

### Fix 2: Force restart your PC

 If Your PC gets stuck at 100% when you’re performing a Windows update, you need to force restart your PC first. If you don’t know how to do it, you can follow the instructions below:

1. Press and **keep holding** the power button on your computer case **until your PC shuts down** .
2. **Disconnect** any external power supply or remove the battery from your laptop.
3. **Hold down** the power button for about **15** seconds.
4. **Wait a few minutes** and then plug in your PC or connect the battery to your laptop.
5. Press the power button again to reboot your system.
6. **Select the option to boot normally** if you get a notice that the computer shuts down improperly.

 If you still cannot access the desktop, you can try starting your PC in safe mode with the network. When you sign into your Windows system in safe mode with the network, try the next fix below to run the Windows Update troubleshooter.

### Fix 3: Run Windows Update troubleshooter

 Windows Update troubleshooter is a built-in tool that can help you analyze and resolve issues related to Windows updates. Try running Windows Update troubleshooter to see if you can resolve this issue. Here is how to do it:

#### If you’re on Windows 10

1. On your keyboard, press **the Windows logo key** and type **troubleshoot** . In the list of search results, select **Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap465-1.png)
2. In the pop-up window, select **Windows Update** and click **Run the troubleshooter** . You’ll be prompted for permission. Click **Yes** to run Windows Update troubleshooter.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap466-1.png)
3. Click **Apply this fix** to continue.  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap467-1.png)
4. Follow the on-screen instructions to troubleshoot this issue.

#### If you’re using Windows 11

1. On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.
2. From the left navigation panel, select**System** . Find**Troubleshoot** and click on it.  
![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-System-Troubleshoot.jpg)
3. Click**Other troubleshooters** .  
![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-Other-troubleshooters.jpg)
4. Click on the**Run** button next to Windows Update. Then wait for it to troubleshoot your issues.  
![](https://www.drivereasy.com/wp-content/uploads/2023/11/win11-run-Windows-Update-troubleshooter.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Perform a Windows update again to see if you can install the update. If this issue reappears, try the next fix, below.

### Fix 4: Reset Windows Update components

 If Windows Update components are corrupted, Windows Update may not work properly. Maybe that’s the reason behind this issue. To resolve it, try resetting Windows Update components. Here is how to do it:

1. On your keyboard, press **the Windows logo key** and **R** at the same time to invoke the Run dialog. Type **cmd** and press **Ctrl** , **Shift** and **Enter** at the same time to **run Command Prompt as administrator** . You’ll be prompted for permission. Click **Yes** to open the Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap468-1.png)
2. In Command Prompt, type the command lines below and press Enter on your keyboard after typing each:  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

 net stop bits  
 net stop wuauserv  
 net stop appidsvc  
 net stop cryptsvc  

 Note: The Windows Update-related system services will be stopped after executing the command lines above.
3. In Command Prompt, type the following command lines and press Enter after typing each:  

 ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old  
 ren %systemroot%\\system32\\catroot2 catroot2.old  

 Note: You will rename the SoftwareDistribution and catroot2 folder as SoftwareDistribution.old and catroot2.old after you run these two command lines. These two folders are used by Windows Update to save temporary update files.  

 By renaming these two folders, Windows will think these two folders are missing, and Windows will create new ones to store Windows update files. By doing that, you can avoid many Windows Update issues caused by the old corrupted temporary files in these two folders.
4. In Command Prompt, type the following command lines and press Enter after each:  

 net start bits  
 net start wuauserv  
 net start appidsvc  
 net start cryptsvc  

 Note: After you execute the command lines above, you start the Windows Update-related system services.

 Check to see if this resolves your Windows Update problem. Hopefully, it did. But if not, try the next fix, below.

### Fix 5: Download updates from Microsoft Update Catalog manually

**[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)**  offers updates for Windows 2000 SP3 and later versions of the Windows operating system. You can try downloading the updates you failed to install from the Microsoft Update Catalog and install them manually to see if you can fix this issue.

 Before you download updates, you need to **check the system type** of your Windows OS. If you don’t know how to do it, follow the instructions below to view your system type:

1. On your keyboard, press **the Windows Logo key** and **R** at the same time to open the Run dialog. Type **cmd** and press **Enter** to open Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap471-1.png)
2. Type the command line **systeminfo** and press **Enter** to view your system type.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap472-1.png)  

 Note: “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .

Now, you can follow the steps below to download Windows updates manually:

1. On your keyboard, press **the Windows logo key** and type **windows update** , then press **Enter** to open **Windows Update** .
2. Click **View update history** to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download that update and install it manually.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap470-1.png)
3. Visit **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)**  .
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Type the update number that you want to download. In this example, type KB3006137 and then click **Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap473-1.png)
5. In the list of search results, select the correct update for your operating system and click **Download** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->

 Note: If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap474-1.png)
6. In the pop-up window, click the link to start downloading the updates.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap475-1.png)
7. **Double-click** the downloaded file and follow the on-screen instructions to install the update.
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC to see if this issue persists. If not, congratulations! You’ve resolved this annoying issue! But if this issue reappears, you can try the last fix, below.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
### Pro tip: Want us to fix the problem for you?

 If none of the fixes above worked, or you just don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is [buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/) (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

**IMPORTANT:** Please attach **the URL of this article** when you contact us, so we can help you resolve the problem ASAP. You can expect us to respond within two working days.

 You can contact us easily via the **Driver Easy Feedback tool** . To learn how to use this tool, please visit this link:  
[https://www.drivereasy.com/help55/feedback/](https://tools.techidaily.com/drivereasy/download/) .

* [Windows Update](/tag-search/?tagId=62)

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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-broadcasting-higher-integrating-dji-drones-for-facebook-live/"><u>[New] 2024 Approved  Broadcasting Higher - Integrating DJI Drones for Facebook Live</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-retrieve-flawless-copyright-free-images/"><u>[New] How to Retrieve Flawless, Copyright-Free Images</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-untangling-box-mystery-ideas-to-boost-joy/"><u>[New] Untangling Box Mystery  Ideas to Boost Joy</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-a-compreayers-guide-to-capturing-console-games-on-a-computer-for-2024/"><u>[Updated] A Compreayer's Guide to Capturing Console Games on a Computer for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-step-by-step-approach-to-enhanced-roblox-views-for-2024/"><u>A Step-by-Step Approach to Enhanced Roblox Views for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-winodws-update-error-0x8024401c-effective-solutions-for-windows-10-and-11-users/"><u>Beat Winodws Update Error 0X8024401c: Effective Solutions for Windows 10 & 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0xc00solved-troubleshooting-and-fixes-for-windows-users/"><u>Error Code 0XC00#Solved: Troubleshooting and Fixes for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-problem-what-to-do-when-logitechs-scroll-wheel-malfunctions/"><u>Fixing the Problem: What to Do When Logitech's Scroll Wheel Malfunctions</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-apple-iphone-13-mini-drfone-by-drfone-ios/"><u>How To Change Your Apple ID Password On your Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-macs-new-edge-converting-youtube-tracks-to-mp3/"><u>In 2024, Mac's New Edge  Converting YouTube Tracks to MP3</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-your-game-security-install-and-configure-battleye-without-a-glitch/"><u>Master Your Game Security - Install and Configure BattlEye Without a Glitch</u></a></li>
<li><a href="https://program-issues.techidaily.com/netflix-not-working-as-usual-a-guide-to-finding-out-if-theres-a-widespread-issue-today/"><u>Netflix Not Working as Usual? A Guide to Finding Out if There's a Widespread Issue Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210538704-resolving-problem-during-restore-mistake-in-windows-10-fixed/"><u>Resolving 'Problem During Restore' Mistake in Windows 10 – Fixed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723201180829-resolving-windows-update-error-code-0x80cuh0002-quickly-and-easily/"><u>Resolving Windows Update Error Code 0X80cuh0002 Quickly and Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-laptop-mousepad-a-resolved-guide-for-windows-11-8-and-7-users/"><u>Reviving Your Laptop Mousepad: A Resolved Guide for Windows 11, 8 & 7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/securing-system-with-proper-msvcp140dll-management/"><u>Securing System with Proper MSVCP140.dll Management</u></a></li>
<li><a href="https://win-howtos.techidaily.com/sharpen-your-windows-11-viewing-experience-fixes-for-unclear-characters/"><u>Sharpen Your Windows 11 Viewing Experience - Fixes for Unclear Characters</u></a></li>
<li><a href="https://extra-hints.techidaily.com/solo-sounder-snafu-remedy-plan/"><u>Solo Sounder Snafu  Remedy Plan</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-lenovo-mouse-pad-malfunctions-across-all-windows-os-variants-windows-10-8-and-7/"><u>Solving Lenovo Mouse Pad Malfunctions Across All Windows OS Variants (Windows 10, 8 & 7)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-dilemma-how-to-overcome-windows-update-error-code-0x80070643/"><u>Solving the Dilemma: How to Overcome Windows Update Error Code 0X80070643</u></a></li>
<li><a href="https://win-answers.techidaily.com/strategies-to-lower-elevated-cpu-usage-in-current-windows-editions/"><u>Strategies to Lower Elevated CPU Usage in Current Windows Editions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trimming-unnecessary-processes-in-win10/"><u>Trimming Unnecessary Processes in Win10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-resolve-overwatch-voip-problems-instantly/"><u>Troubleshoot and Resolve Overwatch VOIP Problems Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-missing-bluetooth-settings-in-windows-10-quick-and-easy-methods/"><u>Troubleshoot Missing Bluetooth Settings in Windows 10 - Quick & Easy Methods!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-non-functional-usb-ports-on-a-dell-device/"><u>Troubleshooting and Repairing Non-Functional USB Ports on a Dell Device</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-tecno-camon-20-premier-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Tecno Camon 20 Premier 5G Screen | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-successfully-update-your-pc-with-fixes-for-error-0x800f0922-on-windows-11/"><u>Troubleshooting Tips: Successfully Update Your PC with Fixes for Error 0X800f0922 on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fix-for-windows-10-users-solving-google-chrome-cant-load-plugins-errors-easily/"><u>Ultimate Fix for Windows 10 Users: Solving 'Google Chrome Can't Load Plugins' Errors Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-correcting-unable-to-qualify-in-teredo-networking-scenarios/"><u>Understanding and Correcting 'Unable to Qualify' In Teredo Networking Scenarios</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unsticking-windows-11-updates-solutions-for-when-your-system-freezes/"><u>Unsticking Windows 11 Updates: Solutions for When Your System Freezes</u></a></li>
</ul></div>
