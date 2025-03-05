---
title: Master the Fix of Error 0X8024401c on Windows Update for Users of Windows 10 and 11 Systems
date: 2025-03-04T19:56:52.555Z
updated: 2025-03-05T18:36:33.858Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Master the Fix of Error 0X8024401c on Windows Update for Users of Windows 10 and 11 Systems
excerpt: This Article Describes Master the Fix of Error 0X8024401c on Windows Update for Users of Windows 10 and 11 Systems
thumbnail: https://thmb.techidaily.com/49ffa66d38abced0cb3f87fd6a7f07b59b78823dd67224be4906012f3135d98a.jpg
---

## Untangling the Windows 10 Update Mess - Error 0Xc1900208 Fixed Here

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap391.png)Seeing the error code**0xc1900208**when you’re performing a Windows update? Don’t worry… Although it’s incredibly frustrating, you’re definitely not the only one to experience this problem. Thousands of Windows 10 users have recently reported the very same issue. More importantly, you should be able to fix it pretty easily…

## **Fixes to try**

 Here’s a list of fixes that have resolved this problem for other Windows 10 users. You don’t have to try them all. Just work your way through the list until you find the one that does the trick for you.

1. [**Run Windows Update troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. [**Restart the Windows Update service**](https://tools.techidaily.com/drivereasy/download/)
3. [**Run the DISM tool**](https://tools.techidaily.com/drivereasy/download/)
4. [**Running System File Checker**](https://tools.techidaily.com/drivereasy/download/)
5. [**Downloading updates from Microsoft Update Catalog manually**](https://tools.techidaily.com/drivereasy/download/)
6. [**Want us to fix the problem for you?**](https://tools.techidaily.com/drivereasy/download/)

---

### **Fix 1: Run Windows Update troubleshooter**

This is the quickest and easiest fix to try when you’re seeing the error code **0xc1900208**. Windows Update troubleshooter is a built-in tool in Windows operating system that can automatically diagnose and resolve any issues regarding Windows Update. Follow the instructions below to run Windows Update troubleshooter:

1. On your keyboard, press**the Windows logo key** and type**troubleshoot** . In the list of search results, select **Troubleshoot** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap392-1.png)
2. In the pop-up window, select**Windows Update** and click**Run the troubleshooter** . You’ll be prompted for permission. Click**Yes** to run**Windows Update troubleshooter** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap393.png)
3. Click**Apply this fix** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap395.png)
 Windows Update troubleshooter will try to fix the issue for you. You can restart your PC and try to perform a Windows update again. If it still doesn’t work, try the next fix, below.

### **Fix 2: Restart the Windows Update service**

 You may see the error code 0xc1900208 if there is something wrong with the Windows Update service. Try restarting the Windows Update service to see if you can resolve this problem. Here’s how to do it:

1. On your keyboard, press **the Windows Logo key**   and **R**   at the same time to open the Run dialog, then type **services.msc** and press **Enter**   to open the Services window.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap396.png)
2. Right-click **Windows Update** and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap397.png)
3. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open **File Explorer** .  Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to go to the **DataStore**  folder.**`C:\Windows\SoftwareDistribution\DataStore`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap398.png)  
 Please paste it in the address bar.
4. **Delete** all the files in the folder **DataStore** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap399.png)  
 When all the files are deleted, you shall see “This folder is empty”.
5. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open   **File Explorer**  . Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.**`C:\Windows\SoftwareDistribution\Download`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap400.png)  
 Please paste it in the address bar.
6. **Delete** all the files in the folder   **Download** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap401.png)  
 When all the files are deleted, you shall see “This folder is empty”.
 Perform a Windows update again. If it still doesn’t work, try the next fix.

### **Fix 3: Run the DISM tool**

 The error code 0xc1900208 can also be triggered by the corrupted Windows update files. In this case, running **the Deployment Image Servicing and Management (DISM) tool**  may resolve this issue. Just follow the step-by-step instructions below to run the DISM tool:

1. On your keyboard, press **the Windows Logo Key**  and **R**  at the same time to open the Run dialog. Type **cmd** and then press **Ctrl** , **Shift** , and **Enter** on your keyboard   at the same time to **run Command Prompt as administrator** . You will be prompted for permission. Click **Yes**  to run **Command Prompt**  .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap402.png)
2. On your keyboard, type the command lines below one by one and press **Enter** .  
   1. **Dism /Online /Cleanup-Image /ScanHealth**  
    When you run command mentioned above, the DISM tool will scan all the system files and compare them with official system files. The function of this command line is to see if the system file on your PC is consistent with its official source or not. This command line doesn’t fix the corruption.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap403.png)  
    It may take several minutes for this command operation to be completed.  
   2. **Dism /Online /Cleanup-Image /CheckHealth**  
    When you run the command line **Dism /Online /Cleanup-Image /CheckHealth** , the DISM tool will check whether your Windows 10 image exists corruptions or not. This command line also doesn’t repair the corrupted files.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap404.png)  
    It may take several minutes for this command operation to be completed.  
   3. **Dism /Online /Cleanup-Image /RestoreHealth**  
    The command line**Dism /Online /Cleanup-Image /RestoreHealth** tells the DISM tool to try to repair the corrupted files detected. It will replace the corrupted files with the files from official source online.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap405.png)  
    It may take several minutes for this command operation to be completed.
3. Close Command Prompt when the restore operation completed.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap406.png)
 See if you can perform a Windows update. If this issue persists, try running the System File Checker.

### **Fix 4: Running System File Checker**

**System File Checker** can scan for corruptions in Windows system files and restore corrupted files. When you see the error code 0xc1900208, it may be caused by some corruption error. Running System File Checker may help you resolve this issue. Here is how to do it:

1. On your keyboard, press **the Windows Logo Key**  and then type **cmd**  in the search box. When you see **Command Prompt**  in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **OK**  to run **Command Prompt**  .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap407.png)
2. On your keyboard, type the following command and press **Enter** .  
**sfc /scannow**  
 It may take some time for the command operation to be completed.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap408.png)
3. When this command operation is completed, close **Command Prompt** .
Run Windows Update  again to check whether this fix works or not. If you still fail to install updates for your Windows system, don’t worry. Try the next fix.

### **Fix 5: Downloading updates from Microsoft Update Catalog manually**

 You can try downloading the updates you failed to install from[**Microsoft Update Catalog**](https://www.catalog.update.microsoft.com/home.aspx)  and install them manually. Here is how to do it:

1. On your keyboard, press   **the Windows Logo Key**  and type **Windows Update** . Then press **Enter**  to open**Windows Update**  window.
2. Click **View update history**   to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.
3. Before you download the update, follow the instructions below to view your system type:  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap409.png)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap410.png)  
    “**X64-based PC** ” indicates that your Windows OS is**64-bit** ; “**X86-based PC** ” means that your Windows OS is**32-bit** .
4. Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)** .
5. Type the update number that you want to download. In this example, type KB  3006137 and then click **Search** .![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap411.png)
6. In the list of search results, select right update for your operating system and click **Download** .  
 If your**Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap412.png)
7. In the pop-up window, click the link to start downloading the updates.![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap413.png)
8. **Double-click** the downloaded file and follow the on-screen instructions to install the update.
See if the error code 0xc1900208 reappears. If this error persists, try the next fix.

### **Pro tip: Want us to fix the problem for you?**

 If none of the fixes above worked, or you just don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you.  All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

**IMPORTANT:** Please attach**the URL of this article** when you contact us, so we could help you resolve the problem ASAP. You can expect us to respond within two working days.

 You can contact us easily via the**Driver Easy Feedback tool** . To learn how to use this tool, please visit this link: [https://www.drivereasy.com/help55/feedback/](https://tools.techidaily.com/drivereasy/download/) .

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
<li><a href="https://youtube-webster.techidaily.com/n-2024-a-practical-approach-to-creating-captivating-youtube-shorts-templates/"><u>[New] In 2024, A Practical Approach to Creating Captivating YouTube Shorts Templates</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-crafting-immersive-video-experiences-using-captivate/"><u>[New] In 2024, Crafting Immersive Video Experiences Using Captivate</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-unveiling-youtubes-complex-view-count-system/"><u>[New] In 2024, Unveiling YouTube's Complex View Count System</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-perfecting-presentations-through-adobe-captivates-tools/"><u>[Updated] In 2024, Perfecting Presentations Through Adobe Captivate's Tools</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/15-fluency-boosting-proverbs-in-modern-spanish/"><u>15 Fluency-Boosting Proverbs in Modern Spanish</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/affordable-powerhouse-the-ultimate-asus-rog-azoth-extreme-review-at-half-a-grand/"><u>Affordable Powerhouse: The Ultimate Asus ROG Azoth Extreme Review at Half-a-Grand</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/bargain-hunters-gem-snag-a-30-discount-on-the-durable-anker-er-737-power-bank-deals-curated/"><u>Bargain Hunter’s Gem: Snag a $30 Discount on the Durable Anker Er 737 Power Bank | Deals Curated</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-your-livekernelevent-complication-error-117/"><u>Comprehensive Fixes for Your LiveKernelEvent Complication: Error #117</u></a></li>
<li><a href="https://win-howtos.techidaily.com/criteria-for-choosing-windows-hello-friendly-camera/"><u>Criteria for Choosing Windows Hello-Friendly Camera</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-dark-launch-overcoming-initial-boot-issues-in-monster-hunter-world/"><u>Fixing the Dark Launch: Overcoming Initial Boot Issues in Monster Hunter: World</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/fun-meets-functionality-the-ultimate-ddpai-mini3-dashcam-review/"><u>Fun Meets Functionality: The Ultimate DDPai Mini3 Dashcam Review</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211535017-getting-your-microphone-back-on-track-with-windows-11-quick-solutions/"><u>Getting Your Microphone Back on Track with Windows 11 - Quick Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-error-1603-critical-failure-in-software-setup-process/"><u>How to Resolve Error 1603: Critical Failure in Software Setup Process</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-crisis-management-for-pcs-comprehensive-strategies-to-repair-windows-error-code-0xc00000e9/"><u>Mastering Crisis Management for PCs: Comprehensive Strategies to Repair Windows Error Code 0xC00000E9</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-system-lockups-expert-advice-for-defrosting-frozen-computers/"><u>Overcoming System Lockups: Expert Advice for Defrosting Frozen Computers</u></a></li>
<li><a href="https://fox-where.techidaily.com/step-by-step-tutorial-to-manage-programs-with-windows-control-panel-from-yl-software-experts/"><u>Step-by-Step Tutorial to Manage Programs with Windows Control Panel From YL Software Experts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-correcting-the-missing-entry-point-error-on-windows/"><u>Troubleshooting and Correcting the Missing Entry Point Error on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-system-error-5-has-occurred-in-windows-operating-systems-windows-10-7-and-8/"><u>Troubleshooting and Repairing 'System Error 5 Has Occurred' In Windows Operating Systems (Windows 10, 7 & 8)</u></a></li>
</ul></div>

