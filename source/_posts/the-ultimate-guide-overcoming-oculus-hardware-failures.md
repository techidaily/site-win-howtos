---
title: "The Ultimate Guide: Overcoming Oculus Hardware Failures"
date: 2025-01-09T17:26:46.513Z
updated: 2025-01-13T17:32:26.117Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

#### If you’re using Windows 11

1. On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.
2. From the left navigation panel, select**System** . Find**Troubleshoot** and click on it.  
![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-System-Troubleshoot.jpg)
3. Click**Other troubleshooters** .  

![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-Other-troubleshooters.jpg)
4. Click on the**Run** button next to Windows Update. Then wait for it to troubleshoot your issues.  

![](https://www.drivereasy.com/wp-content/uploads/2023/11/win11-run-Windows-Update-troubleshooter.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Perform a Windows update again to see if you can install the update. If this issue reappears, try the next fix, below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Type the update number that you want to download. In this example, type KB3006137 and then click **Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap473-1.png)
5. In the list of search results, select the correct update for your operating system and click **Download** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note: If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap474-1.png)
6. In the pop-up window, click the link to start downloading the updates.  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap475-1.png)
7. **Double-click** the downloaded file and follow the on-screen instructions to install the update.

 Restart your PC to see if this issue persists. If not, congratulations! You’ve resolved this annoying issue! But if this issue reappears, you can try the last fix, below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-skills.techidaily.com/new-key-concepts-of-interactive-storytelling/"><u>[New] Key Concepts of Interactive Storytelling</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-perfected-beats-on-the-go-no-cost-just-download-and-play/"><u>[Updated] In 2024, Perfected Beats on the Go - No Cost, Just Download and Play</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-mastering-ffpm-a-guide-to-firefoxs-pip-feature/"><u>[Updated] Mastering FFPM A Guide to Firefox's PIP Feature</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2020s-best-gratis-convertitori-multimediali-per-windows-11-ottenere-la-qualita-full-hd4k-con-efficienza-assoluta/"><u>2020'S Best Gratis Convertitori Multimediali per Windows 11: Ottenere La Qualità Full HD/4K Con Efficienza Assoluta</u></a></li>
<li><a href="https://solve-news.techidaily.com/1725288774935-dvd/"><u>高品質、長持ち型: DVD動画に最適な安全な保存テクニックを解明</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203390423-dell-laptop-fn-key-problem-heres-how-to-get-it-working-again/"><u>Dell Laptop Fn-Key Problem? Here’s How to Get It Working Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-aoc-monitor-to-work-again-on-a-windows-10-system-expert-tips-and-fixes/"><u>Getting Your AOC Monitor to Work Again on a Windows 10 System: Expert Tips and Fixes</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-se-2020-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone SE (2020) without iTunes? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-virtual-realms-iphone-vr-video-playback/"><u>In 2024, Navigating Virtual Realms IPhone VR Video Playback</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-the-obstacle-of-error-code-80240020-your-guide-to-a-smooth-windows-11-upgrade/"><u>Overcome the Obstacle of Error Code 80240020 – Your Guide to a Smooth Windows 11 Upgrade</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speed-unleashed-discover-how-this-gadget-achieves-lightning-fast-performance/"><u>Speed Unleashed: Discover How This Gadget Achieves Lightning-Fast Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-definitive-solution-for-fixing-non-running-audio-services-on-windows-7-pcs/"><u>The Definitive Solution for Fixing Non-Running Audio Services on Windows 7 PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-altplustab-windows-switching-problems/"><u>Troubleshooting Guide: Resolving Alt+Tab Windows Switching Problems</u></a></li>
<li><a href="https://win-remarkable.techidaily.com/troubleshooting-your-computers-hardware-on-windows-expert-tips-from-yl-computing-and-software-services/"><u>Troubleshooting Your Computer's Hardware on Windows: Expert Tips From YL Computing & Software Services</u></a></li>
</ul></div>

