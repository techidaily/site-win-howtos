---
title: "Troubleshooting Tips: Resolve Windows 10'S 0X80072EFD Error Efficiently"
date: 2025-03-04T17:31:23.929Z
updated: 2025-03-05T17:13:58.308Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Tips: Resolve Windows 10'S 0X80072EFD Error Efficiently"
excerpt: "This Article Describes Troubleshooting Tips: Resolve Windows 10'S 0X80072EFD Error Efficiently"
thumbnail: https://thmb.techidaily.com/d9d28999ab80c3fe303824be9f1e02b9cc335e9a7ef77a5fdd8ceeee3dcb3523.jpg
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
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap795.png)  
 When all the files are deleted, you shall see “This folder is empty”.
5. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open   **File Explorer**  . Copy the path below and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.  

**`C:\Windows\SoftwareDistribution\Download**  
**`**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap796.png)
6. Delete all the files in the folder   **Download**  .  
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
<li><a href="https://fox-boxes.techidaily.com/new-elevate-your-photos-tips-and-apps-on-android-for-2024/"><u>[New] Elevate Your Photos Tips & Apps on Android for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-mosaicmind-pro-unleashing-creative-potential/"><u>[New] In 2024, MosaicMind Pro Unleashing Creative Potential</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-how-to-incorporate-your-podcast-into-app-store-for-2024/"><u>[Updated] How To Incorporate Your Podcast Into App Store for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-frugal-filmmakers-guide-to-affordable-camera-gear/"><u>[Updated] The Frugal Filmmaker's Guide to Affordable Camera Gear</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-path-to-cross-media-popularity-via-television-and-fb-live/"><u>2024 Approved The Path to Cross-Media Popularity via Television and FB Live</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-unleashing-potential-strategic-hashtags-for-video-success/"><u>2024 Approved Unleashing Potential Strategic Hashtags for Video Success</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-dell-usb-issues-a-comprehensive-step-by-step-solution/"><u>Fixing Dell USB Issues - A Comprehensive Step-by-Step Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-windows-10-update-error-code-0x80070541-step-by-step-guide/"><u>Fixing the Windows 10 Update Error Code 0X80070541: Step-by-Step Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-common-issues-with-your-unresponsive-bose-audio-equipment/"><u>Solving Common Issues with Your Unresponsive Bose Audio Equipment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speed-up-your-pc-solve-sluggish-startup-problems-on-windows-7/"><u>Speed Up Your PC: Solve Sluggish Startup Problems on Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-fixing-a-livekernelevent-117-mishap/"><u>Step-by-Step Solutions for Fixing a LiveKernelEvent 117 Mishap</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/streamlining-your-photo-editing-the-crop-essentials/"><u>Streamlining Your Photo Editing The Crop Essentials</u></a></li>
<li><a href="https://win-howtos.techidaily.com/system-upgrade-successfully-eliminates-insufficient-resources-for-service-requests/"><u>System Upgrade Successfully Eliminates Insufficient Resources for Service Requests</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-the-secure-connection-failed-problem-in-firefox-easily/"><u>Troubleshoot and Fix the 'Secure Connection Failed' Problem in Firefox Easily</u></a></li>
<li><a href="https://hardware-help.techidaily.com/trustworthy-hardware-advice-from-toms-reliable-source/"><u>Trustworthy Hardware Advice From Tom's Reliable Source</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstuck-scroll-wheels-solving-common-issues-with-logitech-mice/"><u>Unstuck Scroll Wheels: Solving Common Issues with Logitech Mice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/usb-connection-problems-in-windows-solutions-for-windows-10-and-11-users/"><u>USB Connection Problems in Windows: Solutions for Windows 10 and 11 Users</u></a></li>
</ul></div>

