---
title: Winning the Battle Against Disappearing Mice in Windows 11 [Solved]
date: 2024-09-11T15:19:03.596Z
updated: 2024-09-12T15:19:03.596Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Winning the Battle Against Disappearing Mice in Windows 11 [Solved]
excerpt: This Article Describes Winning the Battle Against Disappearing Mice in Windows 11 [Solved]
thumbnail: https://thmb.techidaily.com/549ca928829525c9c386345bc34f0e1c4ffcbb4613654a88c4a76774162c73c8.jpg
---

## Winning the Battle Against Failed Feature Updates in Windows 10 v1803 - Now Solved

![](https://images.drivereasy.com/wp-content/uploads/2019/01/snap000800.png)

**Feature update to Windows 10 version 1803 failed to install?** Don’t worry… Although it’s incredibly frustrating, you’re definitely not the only person to experience this problem. Thousands of Windows 10 users have recently reported the very same issue. More importantly, you should be able to fix it pretty easily…

 Here’s a list of fixes that have resolved this issue for other Windows 10 users. You don’t have to try them all. Just work your way through the list until you find the one that does the trick for you.

1. **[Run the Windows Update Troubleshooter](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
3. **[Run the DISM tool](https://tools.techidaily.com/drivereasy/download/)**
4. **[Run System File Checker](https://tools.techidaily.com/drivereasy/download/)**
5. **[Update your drivers](https://tools.techidaily.com/drivereasy/download/)**
6. **[Update Windows from the Windows 10 ISO file](https://tools.techidaily.com/drivereasy/download/)**

---

### Fix 1: Run the Windows Update Troubleshooter  

**Windows Update troubleshooter** is a built-in tool that can help you analyze and resolve issues related to Windows update. Try running Windows Update troubleshooter to see if you can resolve this issue. Here is how to do it:

 1) On your keyboard, press **the Windows logo key** and type **troubleshoot** . In the list of search results, select **Troubleshoot** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap828.png)

 2) In the pop-up window, select **Windows Update** and click **Run the troubleshooter** . You’ll be prompted for permission. Click **Yes** to run Windows Update troubleshooter.

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap829-2.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Click **Apply this fix** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2018/12/Snap830.png)

4) Follow the on-screen instructions to troubleshoot this issue.

 Perform Windows update again to see if you can install the update. If not, try the next fix, below.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115936/19272" target="_top" id="2115936">
  <img src="//a.impactradius-go.com/display-ad/19272-2115936" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115936/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 2: Reset Windows Update components

 This issue may occur if there’s something wrong with Windows Update components. If Windows Update components corrupted, Windows Update may not work properly. In this case, try resetting Windows Update components. Here is how to do it:

 1) On your keyboard, press **the Windows logo key** and **R** at the same time to open the Run dialog. Type **cmd** and press **Ctrl** , **Shift** and **Enter** at the same time to **run Command Prompt as administrator** . You’ll be prompted for permission. Click **Yes** to open Command Prompt.

 2) In Command Prompt, type the command lines below and press **Enter** on your keyboard **after typing each** :

net stop bits  
  
net stop wuauserv  
  
net stop appidsvc  
  
net stop cryptsvc

 The Windows Update related system services will be stopped after executing the command lines above.

 3) In Command Prompt, type the following command lines and press **Enter** after typing each:

ren %systemroot%\SoftwareDistribution SoftwareDistribution.old  
  
ren %systemroot%\system32\catroot2 catroot2.old

 You will**rename** the**SoftwareDistribution** and**catroot2** folder as**SoftwareDistribution.old** and**catroot2.old** after you run these two command lines. These two folders are used by Windows Update to save temporary update files.  

 By renaming these two folders, **Windows will think these two folders are missing, and Windows will create new ones to store Windows update files.** By doing that, you can avoid many Windows Update issues caused by the old corrupted temporary files in these two folders.

 4) In Command Prompt, type the following command lines and press **Enter** after each:

net start bits  
  
net start wuauserv  
  
net start appidsvc  
  
net start cryptsvc

 After you executing the command lines above, you start the Windows Update related system services.

 Check to see if this resolved your Windows Update problem. Hopefully it did. But if not, try the next fix, below.

### Fix 3: Run the DISM tool

 This issue is probably caused by the corrupted Windows update files. In this case, running   **the Deployment Image Servicing and Management (DISM) tool** may resolve this issue. Just follow the step-by-step instructions to run the DISM tool:

 1) On your keyboard, press **the Windows logo key** and **R** at the same time to open the Run dialog. Type **cmd** and press **Ctrl** , **Shift** and **Enter** at the same time to **run Command Prompt as administrator** . You’ll be prompted for permission. Click **Yes** to open Command Prompt.

 2) On your keyboard, type the command lines below one by one and press **Enter** .

Dism /Online /Cleanup-Image /ScanHealth

 When you run the command mentioned above, the DISM tool will scan all the system files and compare them with official system files. The function of this command line is to see if the system file on your PC is consistent with its official source or not. This command line doesn’t fix the corruption.

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap1-2.jpg)

 It may take several minutes for this command operation to be completed.

Dism /Online /Cleanup-Image /CheckHealth

 When you run the command line **Dism /Online /Cleanup-Image /CheckHealth** , the DISM tool will check whether your Windows 10 image exists corruptions or not. This command line also doesn’t repair the corrupted files.

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap2-5.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137395/7443" target="_top" id="2137395">
  <img src="//a.impactradius-go.com/display-ad/7443-2137395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 It may take several minutes for this command operation to be completed.

Dism /Online /Cleanup-Image /RestoreHealth

 The command line **Dism /Online /Cleanup-Image /RestoreHealth** tells the DISM tool to try to repair the corrupted files detected. It will replace the corrupted files with the files from official source online.

 It may take several minutes for this command operation to be completed.

3) Close Command Prompt when the restore operation completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap4-6.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115948/19272" target="_top" id="2115948">
  <img src="//a.impactradius-go.com/display-ad/19272-2115948" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115948/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Try performing a Windows update to see if this fixes works. If this issue persists, try running the System File Checker.

### Fix 4: Run System File Checker

**System File Checker** can scan for corruptions in Windows system files and restore corrupted files. If the feature update to Windows 10 version 1803 failed to install, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

 1) On your keyboard, press **the Windows logo key** and **R** at the same time to open the Run dialog. Type **cmd** and press **Ctrl** , **Shift** and **Enter** at the same time to **run Command Prompt as administrator** . You’ll be prompted for permission. Click **Yes** to open Command Prompt.

 2) On your keyboard, type the following command and press **Enter** .

sfc /scannow

It may take some time for the command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/09/Snap1-3.jpg)

 3) When this command operation is completed, close **Command Prompt** .

 Perform a Windows update to check whether this fix works or not. If you still fail to install updates for your Windows system, try the next fix, below.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 5: Update your drivers

 This issue may also be triggered by some missing or outdated drivers. Some Windows users reported that this issue is resolved after they update their audio drivers. Try updating your drivers to see if you can fix this issue.

 There are two ways to update your drivers: **manually** and **automatically** .

**Update your drivers manually** – You can update your drivers manually by going to the manufacturer’s website, and searching for the latest driver for each device on your PC.

 Be sure to choose the driver **that’s compatible with your PC model** and **your version of Windows** .

**Or**

**Update your drivers automatically** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. **Driver Easy handles it all** .

**All the drivers in Driver Easy** come straight from **the manufacturer** . They‘re **all certified safe and secure** .

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

 2) Run Driver Easy and click **Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-4.png)

<!-- affiliate ads begin -->
<span id="1424529">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424529.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424529">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424529.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424529%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424529/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Click **Update** next to any device to automatically download the correct version of its driver, then you can install it manually. Or click **Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click **Update All.**  You get **full support** and a **30-day money back** guarantee).

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-5.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

_You can do it for free if you like, but it’s partly manual._

 If you need assistance, please contact **Driver Easy’s support team** at [**support@drivereasy.com**](https://tools.techidaily.com/drivereasy/download/) .

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 6: Update Windows from the Windows 10 ISO file

 If none of the fixes above works for you, you can try updating Windows form Windows 10 ISO file. You download the ISO file from the official website of Microsoft and then perform an Offline Update. Here is how to do it:

#### Step 1: Download the Windows 10 ISO file from the Microsoft official website

 1) Click [here](https://www.microsoft.com/en-us/software-download/windows10/) to visit the Microsoft official website for downloading Windows 10.

 2) Click **Download tool now** on the web page to download the media creation tool.

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-7-1024x511.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3)**Double-click** the downloaded file to open the media creation tool. Click **Yes**  when you’re prompted for permission.

 4) Click **Accept**  when you see the window below.

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-13.png)

 5) Select   **Create installation media (USB flash drive, DVD, or ISO file) for another PC**  and click**Next** .

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-14.png)

 6) Select the language and architecture of your Windows 10 ISO file and click **Next** .

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-15.png)

**Note:**  If the installed memory of your PC is less than**4GB** , it’s recommended that you select the 32-bit architecture.

 7) Select **ISO file** and click **Next** .

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-16.png)

<!-- affiliate ads begin -->
<span id="1328679">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328679.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328679">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328679.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328679%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328679/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 8) Select the location to save the Windows 10 ISO file. After that, the media creation tool will start to download **Windows 10 ISO file** .

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-17.png)

 9) Click **Finish** to close the media creation tool.

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-18.png)

#### Step 2: Start updating

 1)**Right-click** on the downloaded ISO file then select**Mount** .

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-8.png)

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114267/17093" target="_top" id="2114267">
  <img src="//a.impactradius-go.com/display-ad/17093-2114267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114267/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) In the pop-up window, double-click the file**setup** .**exe** . You’ll be prompted for permission. Click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-10.png)

 3) When you see the following window, select**Not right now** then click**Next** .

![](https://images.drivereasy.com/wp-content/uploads/2019/01/image-19.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Follow the on-screen instructions to update your Windows 10 OS. During the installation, your computer will restart several times.

 When the Windows 10 feature update is installed, check for Windows Update for latest updates.

 Hopefully, one of the fixes above resolved the feature update to Windows 10 version 1803 failed to install issue for you. If you have any questions or suggestions, please leave your comment below.

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
<li><a href="https://fox-links.techidaily.com/new-from-beginner-to-pro-transforming-windows-videos-with-minimal-tools-for-2024/"><u>[New] From Beginner to Pro Transforming Windows Videos with Minimal Tools for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-essential-zoom-substitutes-for-pcs-tablets/"><u>[New] In 2024, Essential Zoom Substitutes for PCs, Tablets</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-experience-the-new-unleash-a-set-of-50-designs-for-free/"><u>[New] In 2024, Experience the New Unleash a Set of 50 Designs for Free</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-live-stream-tech-showdown-soft-vs-hardscape-winners/"><u>[New] Live Stream Tech Showdown Soft vs Hardscape Winners</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-becoming-a-director-top-film-tips-and-tricks-on-youtube/"><u>[Updated] 2024 Approved Becoming a Director Top Film Tips & Tricks on YouTube</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-straightforward-guide-to-ios-screen-share-simplicity-for-2024/"><u>[Updated] Straightforward Guide to IOS Screen Share Simplicity for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comprehensive-breakdown-features-and-benefits-of-philips-somneo-sleep-time-machine/"><u>Comprehensive Breakdown: Features & Benefits of Philips Somneo Sleep Time Machine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-windows-10-bluetooth-malfunctions-avoid-delays/"><u>Comprehensive Fixes for Windows 10 Bluetooth Malfunctions – Avoid Delays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-solutions-to-overcome-error-code-28-in-windows-device-manager/"><u>Easy Solutions to Overcome 'Error Code 28' In Windows Device Manager</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/edit-like-a-championtop-strategies-for-beginner-youtubers-for-2024/"><u>Edit Like a Champion—Top Strategies for Beginner YouTubers for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209493947-effortless-fixes-for-keyboard-malfunctions-in-your-hp-notebook-now/"><u>Effortless Fixes for Keyboard Malfunctions in Your HP Notebook – Now!</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-capture-and-compose-best-writing-apps-for-photos-iosandroid/"><u>In 2024, Capture and Compose Best Writing Apps for Photos (iOS/Android)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-strategies-to-combat-lag-issues-in-minecraft/"><u>In-Depth Strategies to Combat Lag Issues in Minecraft</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restoring-night-mode-solutions-for-windows-11-users-facing-display-issues/"><u>Restoring Night Mode: Solutions for Windows 11 Users Facing Display Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-tv-a-step-by-step-guide-to-restoring-netflix-sounds/"><u>Troubleshoot Your TV: A Step-by-Step Guide to Restoring Netflix Sounds</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-a-faulty-astro-a40-microphone-simple-fixes-to-try-first/"><u>Troubleshooting Guide for a Faulty Astro A40 Microphone - Simple Fixes to Try First</u></a></li>
</ul></div>

