---
title: Solving the 'Windows Update Error Code 0X802n401c' On Your Windows 11 PC
date: 2024-09-23T17:38:46.241Z
updated: 2024-09-28T22:21:14.906Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving the 'Windows Update Error Code 0X802n401c' On Your Windows 11 PC
excerpt: This Article Describes Solving the 'Windows Update Error Code 0X802n401c' On Your Windows 11 PC
thumbnail: https://thmb.techidaily.com/0464d20c8383250ad5eec7dae311ce3366a21c1ceecc558739dbb36535dbfcf9.jpg
---

## Resolving the Troublesome 0X80240017 Windows Update Issue: Proven Solutions

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04d8761fcdb.jpg)

 The**0x80240017** error is a common Windows Update error which happens when you’re downloading or installing your Windows updates and indicates the Windows update failed. It’s generally caused by system files corruption or driver issues. But don’t worry. You can try the solutions below to fix this problem easily.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

 Here are the solutions that have helped other Windows users resolve error 0x80240017\. You don’t need to try them all; just work your way down the list until everything’s working again.

1. **[Run Windows Update Troubleshooter](#F1)**
2. **[Reset Windows Update Components](#F2)**
3. **[Repair corrupted system files](#F3)**
4. **[Update available drivers](#F4)**

 Note: the screenshots below com from Windows 10, and fixes apply to Windows 11, 8 and 7.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123511/26400" target="_top" id="2123511">
  <img src="//a.impactradius-go.com/display-ad/26400-2123511" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123511/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 1: Run Windows Update Troubleshooter

 Windows Update Troubleshooter is a helpful tool built in Windows system, and you can use it to scan and fix the Windows Update error 0x80240017.

Here’s what you can do:

1. Type**Troubleshoot** in the search box on your desktop, and click**Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04da616dafa.jpg)
2. Click**Troubleshoot** on the left. Click**Windows Update** \>**Run the troubleshooter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

### Fix 2: Reset Windows Update Components

 Windows Update components ensure Windows Update runs properly and the updates can be installed successfully in your computer. If there’s anything wrong during the process, you can try resetting Windows Update components and see how it works.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Copy and paste the following commands one by one in Command Prompt, and press**Enter** on your keyboard.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**net stop wuauserv**  
**net stop cryptSvc**  
**net stop bits**  
**net stop msiserver**  
 **ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old**  
**ren C:\\Windows\\System32\\catroot2 catroot2.old**  
**net start wuauserv**  
**net start cryptSvc**  
**net start bits**  
**net start msiserver**  
**pause**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dd3338a3f.jpg)
3. Wait for the commands to complete, and exit Command Prompt.
4. Open Windows Update and see if it works properly.

 If your issue still persists, don’t worry, There is something else to try.

### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Try to update Windows again and see if it fixes your error 0x80240017\. Still no luck? There’s one more thing to try.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 4: Update available drivers

 To ensure your computer operates without problems, you should keep your devices drivers up to date. And here are two ways for you to update drivers:**manually** and**automatically** .

**Manually update your driver** – You can go to the manufacturer’s website of your devices, find the latest driver that’s compatible with your Windows operating system, and download it. Once done, open the downloaded file and follow the instruction to install it to your computer.

**Automatically update your driver** **(recommended)** – If you don’t have time or patience, you can do it automatically with[**Driver** **Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  it takes just 2 clicks (and you get full support and a**30-day money back guarantee** ):

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Then Driver Easy will scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/driver-easy-scan.jpg)
3. Click the**Update** button next to the flagged device(s) to automatically download the driver (you can do that with the FREE version), then install it in your computer.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886003/19272" target="_top" id="1886003">
  <img src="//a.impactradius-go.com/display-ad/19272-1886003" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886003/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Or click**Update All** to automatically download and install all the correct drivers for problem drivers (you can do this with the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) , and you’ll be prompted to upgrade when your click**Update All** ).  
![](https://images.drivereasy.com/wp-content/uploads/2023/07/driver-easy-update.jpg)
4. Restart your computer to take effect.

 Open Windows Update to download and install updates and it should working now.

 So there you have it – Hope this post helps in resolving your**Windows Update error** **0x80240017** . If you have any questions or suggestions, feel free to leave a comment below.

* [error](https://tools.techidaily.com/drivereasy/download/)
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
<li><a href="https://extra-resources.techidaily.com/2024-approved-adding-soundtracks-to-your-inshot-projects/"><u>2024 Approved Adding Soundtracks to Your InShot Projects</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-excellence-on-the-screen-best-six-video-tools-for-big-sur/"><u>2024 Approved Excellence on the Screen Best Six Video Tools for Big Sur</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-compelling-podcast-names-a-detailed-guide-with-idea-examples/"><u>Crafting Compelling Podcast Names A Detailed Guide with Idea Examples</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/decoding-the-functionality-and-benefits-of-the-windows-11-battery-health-dashboard/"><u>Decoding the Functionality and Benefits of the Windows 11 Battery Health Dashboard</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-samsung-device-adb-drivers-for-usb-debugging-secure-download-link/"><u>Get the Latest Samsung Device ADB Drivers for USB Debugging – Secure Download Link</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-honor-x50iplus-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Honor X50i+ to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/humor-and-memes-galore-iphones-for-2024/"><u>Humor & Memes Galore, iPhones for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-performance-strategies-for-reducing-system-idle-process-cpu-strain/"><u>Optimizing Performance: Strategies for Reducing System Idle Process CPU Strain</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-why-does-wudfhostexe-consume-high-cpu-on-windows-10/"><u>Resolved: Why Does wudfhost.exe Consume High CPU on Windows 10?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-hardware-malfunctions-fixing-a-frozen-hddssd-on-windows-11/"><u>Resolving Hardware Malfunctions: Fixing a Frozen HDD/SSD on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-unable-to-start-application-issue-error-0xc000007b-explained-and-fixed/"><u>Resolving the 'Unable to Start Application' Issue: Error 0xC000007B Explained and Fixed</u></a></li>
<li><a href="https://youtube-data.techidaily.com/e-guide-youtube-to-mp3-on-mac-for-2024/"><u>Simple Guide YouTube to MP3 on Mac for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-stalled-windows-updates-at-100-mark/"><u>Step-by-Step Guide: Resolving Stalled Windows Updates at 100% Mark</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-5-essential-factors-to-evaluate-when-choosing-a-smartwatch/"><u>Top 5 Essential Factors To Evaluate When Choosing A Smartwatch</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/top-swf-player-software-for-windows-11-users/"><u>Top SWF Player Software for Windows 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-continuous-system-reboots-ultimate-solutions-for-windows-1110-users/"><u>Troubleshooting Continuous System Reboots - Ultimate Solutions for Windows 11/10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-sudden-shutdown-of-windows-processes-understanding-error-1067/"><u>Troubleshooting the Sudden Shutdown of Windows Processes - Understanding Error 10^67</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-fix-unresponsive-function-key-issues/"><u>Troubleshooting: How to Fix Unresponsive Function Key Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-mse-insights-into-microsoft-security-essentials-and-its-impact-on-disk-utilization/"><u>Understanding MSE: Insights Into Microsoft Security Essentials & Its Impact on Disk Utilization</u></a></li>
</ul></div>

