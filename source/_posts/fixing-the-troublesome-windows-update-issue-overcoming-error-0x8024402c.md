---
title: Fixing the Troublesome Windows Update Issue - Overcoming Error 0X8024402c
date: 2025-01-22T17:42:28.463Z
updated: 2025-01-25T17:11:15.705Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing the Troublesome Windows Update Issue - Overcoming Error 0X8024402c
excerpt: This Article Describes Fixing the Troublesome Windows Update Issue - Overcoming Error 0X8024402c
thumbnail: https://thmb.techidaily.com/fba56e471126861872d44702a4719c3712dd082c4310b4a45ca55ed512e735ed.jpg
---

## Overcome the Challenge of Frozen Windows Updates - Now Fixed

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap467-1.png)
4. Follow the on-screen instructions to troubleshoot this issue.

#### If you’re using Windows 11

1. On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.
2. From the left navigation panel, select**System** . Find**Troubleshoot** and click on it.  
![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-System-Troubleshoot.jpg)
3. Click**Other troubleshooters** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note: If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap474-1.png)
6. In the pop-up window, click the link to start downloading the updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap475-1.png)
7. **Double-click** the downloaded file and follow the on-screen instructions to install the update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC to see if this issue persists. If not, congratulations! You’ve resolved this annoying issue! But if this issue reappears, you can try the last fix, below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-best-practices-for-documenting-live-streamed-sporting-matches/"><u>[New] 2024 Approved Best Practices for Documenting Live-Streamed Sporting Matches</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-effortless-editing-secrets-for-fresh-filmmakers-for-2024/"><u>[New] Effortless Editing Secrets for Fresh Filmmakers for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-unlocking-creative-potential-a-deep-dive-into-screenflow-for-mac/"><u>[New] Unlocking Creative Potential A Deep Dive Into ScreenFlow for Mac</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-essential-tips-for-successful-hulu-capturing-on-various-platforms/"><u>2024 Approved Essential Tips for Successful Hulu Capturing on Various Platforms</u></a></li>
<li><a href="https://blog-min.techidaily.com/8-ways-to-transfer-photos-from-zte-nubia-flip-5g-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>8 Ways to Transfer Photos from ZTE Nubia Flip 5G to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://discover-blog.techidaily.com/apng-movavin/"><u>APNGファイル自動変換サービスオンラインで不可能に? - Movaviの安心無料オプショn</u></a></li>
<li><a href="https://win-howtos.techidaily.com/concern-is-rising-that-equities-have-become-overvalued-and-too-expensive-to-be-worth-buying-in-the-long-run-despite-recent-gains/"><u>Concern Is Rising that Equities Have Become Overvalued and Too Expensive to Be Worth Buying in the Long Run, Despite Recent Gains.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-techniques-to-repair-and-rectify-http-503-service-interruption/"><u>Effortless Techniques to Repair and Rectify HTTP 503 Service Interruption</u></a></li>
<li><a href="https://win-answers.techidaily.com/guide-to-fixing-your-astro-a50s-inability-to-detect-command-center/"><u>Guide to Fixing Your Astro A50's Inability to Detect Command Center</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Xiaomi Redmi 13C 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/kodi-playback-smoother-now-how-to-overcome-buffering-troubles/"><u>Kodi Playback Smoother Now - How to Overcome Buffering Troubles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-graphics-hurdles-in-fortnite-a-guide-for-windows-users/"><u>Overcoming Graphics Hurdles in Fortnite: A Guide for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-usb-connectivity-problems-on-your-windows-11-pc/"><u>Solving USB Connectivity Problems on Your Windows 11 PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-unfreezing-a-non-responsive-laptop-or-desktop/"><u>Step-by-Step Solutions for Unfreezing a Non-Responsive Laptop or Desktop</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-programmers-handbook-mastering-flawless-job-applications-insights-from-zdnet/"><u>The Ultimate Programmer's Handbook: Mastering Flawless Job Applications - Insights From ZDNet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-vcruntime140dll-not-found-issue-on-windows-10-for-seamless-program-running/"><u>Troubleshooting the VCRUNTIME140.dll Not Found Issue on Windows 10 for Seamless Program Running</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-resolving-the-windows-resource-protection-couldnt-execute-requests/"><u>Understanding and Resolving the 'Windows Resource Protection Couldn't Execute Requests'</u></a></li>
</ul></div>

