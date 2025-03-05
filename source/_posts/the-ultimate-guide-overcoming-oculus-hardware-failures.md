---
title: "The Ultimate Guide: Overcoming Oculus Hardware Failures"
date: 2025-03-04T17:07:30.772Z
updated: 2025-03-05T16:37:22.517Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes The Ultimate Guide: Overcoming Oculus Hardware Failures"
excerpt: "This Article Describes The Ultimate Guide: Overcoming Oculus Hardware Failures"
thumbnail: https://thmb.techidaily.com/815d7d8c09f8175fd88f64c74fcffe4ff27128461391bb250305d7aa226764d0.jpg
---

## Overcome the Challenge of Frozen Windows Updates - Now Fixed

 If you see the message **“Working on updates, 100% complete. Don’t turn off your computer”** when performing a Windows update, don’t worry!

 Although it’s incredibly frustrating, you’re not the only person to experience this issue. Thousands of Windows users have recently reported the very same issue. More importantly, you should be able to fix it pretty easily…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

 Perform a Windows update again to see if you can install the update. If this issue reappears, try the next fix, below.

### Fix 4: Reset Windows Update components

 If Windows Update components are corrupted, Windows Update may not work properly. Maybe that’s the reason behind this issue. To resolve it, try resetting Windows Update components. Here is how to do it:

1. On your keyboard, press **the Windows logo key** and **R** at the same time to invoke the Run dialog. Type **cmd** and press **Ctrl** , **Shift** and **Enter** at the same time to **run Command Prompt as administrator** . You’ll be prompted for permission. Click **Yes** to open the Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap468-1.png)
2. In Command Prompt, type the command lines below and press Enter on your keyboard after typing each:  

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

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap472-1.png)  

 Note: “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .

Now, you can follow the steps below to download Windows updates manually:

1. On your keyboard, press **the Windows logo key** and type **windows update** , then press **Enter** to open **Windows Update** .
2. Click **View update history** to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download that update and install it manually.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap470-1.png)
3. Visit **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)**  .

4. Type the update number that you want to download. In this example, type KB3006137 and then click **Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap473-1.png)
5. In the list of search results, select the correct update for your operating system and click **Download** .  

 Note: If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap474-1.png)
6. In the pop-up window, click the link to start downloading the updates.  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap475-1.png)
7. **Double-click** the downloaded file and follow the on-screen instructions to install the update.

 Restart your PC to see if this issue persists. If not, congratulations! You’ve resolved this annoying issue! But if this issue reappears, you can try the last fix, below.

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
<li><a href="https://article-helps.techidaily.com/new-breaking-barriers-in-drone-races-and-top-5-innovative-fpv-units/"><u>[New] Breaking Barriers in Drone Races & Top 5 Innovative FPV Units</u></a></li>
<li><a href="https://win-blog.techidaily.com/solved-pathfinder-wrath-of-the-righteous-freezing-on-pc/"><u>[SOLVED] Pathfinder: Wrath of the Righteous Freezing on PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-ordinary-to-outstanding-transforming-your-meetings-with-zoom-filters/"><u>2024 Approved From Ordinary to Outstanding Transforming Your Meetings with Zoom Filters</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-tecno-camon-30-pro-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Tecno Camon 30 Pro 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-steps-how-to-update-graphics-driver-on-amd-ryzen-5-2400g/"><u>Easy Steps: How to Update Graphics Driver on AMD Ryzen 5 2400G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-non-operational-usb-ports-in-modern-windows-environments/"><u>Effective Solutions for Non-Operational USB Ports in Modern Windows Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-5-in-minecraft-comprehensive-solutions-for-a-smooth-gaming-experience/"><u>Error Code 5 in Minecraft: Comprehensive Solutions for a Smooth Gaming Experience</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-delving-deep-into-ios-video-recording-capabilities/"><u>In 2024, Delving Deep Into IO's Video Recording Capabilities</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-teleport-your-gps-location-on-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Teleport Your GPS Location On Samsung Galaxy A15 4G? | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-virtual-horizons-exploring-vrs-advancements/"><u>In 2024, Virtual Horizons Exploring VR’s Advancements</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209730276-no-charge-detected-heres-how-to-troubleshoot-and-restore-in-a-flash/"><u>No Charge Detected? Here’s How to Troubleshoot & Restore in a Flash!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-and-simple-easycap-driver-software-free-download-for-smooth-operation/"><u>Quick and Simple EasyCap Driver Software Free Download for Smooth Operation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issues-with-launching-the-microsoft-store-fix-guide/"><u>Resolved: Issues with Launching the Microsoft Store - Fix Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-successfully-restoring-secured-connections-in-mozilla-firefox/"><u>Step-by-Step Solutions: Successfully Restoring Secured Connections in Mozilla Firefox</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-to-bypass-destiny-2-initialization-errors-successfully/"><u>Step-by-Step Tutorial to Bypass Destiny 2 Initialization Errors Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-successful-overcoming-initial-boot-failures-on-pcs/"><u>Troubleshooting Successful: Overcoming Initial Boot Failures on PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-0x80072efd-problem-on-your-pc-with-windows-10/"><u>Troubleshooting the 0X80072EFD Problem on Your PC with Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208952957-uninterrupted-workflow-on-windows-11-how-your-files-remain-unchanged-post-bootup/"><u>Uninterrupted Workflow on Windows 11: How Your Files Remain Unchanged Post Bootup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-steps-to-replace-missing-msvcrt120dll-in-windows/"><u>Unveiling Steps to Replace Missing msvcrt120.dll in Windows</u></a></li>
</ul></div>

