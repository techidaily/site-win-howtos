---
title: "Camera Selection: Integrating with Windows Hello"
date: 2024-10-02T19:05:29.918Z
updated: 2024-10-09T20:05:29.715Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Camera Selection: Integrating with Windows Hello"
excerpt: "This Article Describes Camera Selection: Integrating with Windows Hello"
thumbnail: https://thmb.techidaily.com/c07b7ea823a20fff0d48f1accc60826d6016566f3469f152eba0254ae0b7e1bc.jpg
---

## Shopping Guide: Cameras & Windows Hello

 Among various Windows sign-in options, Windows Hello Face can be said to be the most secure and instant way to log in to a device. There isn’t even a need to move a finger—just a smile will do. Despite how convenient it is, some Windows users who try to use this feature have received such an error message:   **We couldn’t find a camera compatible with Windows Hello Face** .

 If you’re also struggling with the same issue even though you’re using an infrared (IR) camera as required, this post may help you fix it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

 Here are the 7 fixes that have helped many users solve the Windows Hello Face not working problem.  
 You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. **[Ensure the feature is installed](#fix-1)**
2. **[Update your IR camera drivers](#fix-2)**
3. **[Install the FaceDriver file](#fix-3)**
4. **[Restart Windows Biometric Service](#fix-4)**
5. **[Run System File Checker](#fix-5)**
6. **[Disable ESS (Enhanced Sign-in Security)](#ess)**
7. **[Try the Get Help app](#fix-6)**

## Fix 1 – Ensure the feature is installed

 Windows Hello Face is an optional feature available in Windows 10 and 11\. To utilize it properly, You need to ensure first that it has been active and installed under the optional features. Here’s how it’s done:

1. Press**Windows + I** keys to open the settings and then select**Apps** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/04/win-settings-apps.jpg)
2. Click**Optional features** .  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2022/08/optional-features.jpg)
3. Check if Windows Hello Face is in the list under**Installed features** . If it isn’t, click**Add a feature** .  
 (If it’s already installed, then you don’t do anything)  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/add-a-feature.jpg)
4. Scroll down the list and find Windows Hello Face. Tick the box near it and then click**Install** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/install-hello-faca-app.jpg)
5. Reboot your computer and check to see if Windows Hello Face can work successfully now.

 If this method doesn’t work, go on and try the next fix below.

## Fix 2 – Update your IR camera drivers

 This issue may occur if you are using the wrong IR camera driver or it’s out of date. So you should update your camera driver to see if it fixes your problem. There are two ways you can get the right drivers for your camera: manually or automatically.

#### Manual driver update

 You can update your camera drivers manually by going to the manufacturer’s website for your camera, and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

#### Automatic driver update

 If you don’t have the time, patience or computer skills to update your camera drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact camera, and your Windows version, and it will download and install them correctly.

 You can update your drivers automatically with either the [**7 days free trial**](https://tools.techidaily.com/drivereasy/download/) or the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) of Driver Easy. It takes just 2 clicks, and you get full support and a 30-day money-back guarantee with the Pro version:

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2020/10/6_0_scan-now.jpg)
3. Click the**Activate & Update** button next to the flagged device to automatically download and install the correct version of this driver.  

 Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (You’ll need the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  for this – when you select Update All, you’ll get a prompt to upgrade. If you’re not prepared to purchase the Pro version yet, Driver Easy provides a 7-day trial at no cost, granting access to all Pro features like fast downloads and easy installation. No charges will occur until after your 7-day trial period ends.)  
![](https://www.drivereasy.com/wp-content/uploads/2022/08/realtek-ir-camera.png)
4. After updating, restart your computer to take effect.

[**The Pro version of Driver Easy**](https://tools.techidaily.com/drivereasy/download/) comes with full technical support. If you need assistance, please contact **Driver Easy’s support** **team** at [support@drivereasy.com](https://bellelily.pxf.io/m5azgm) **.**

## Fix 3 – Install the FaceDriver file

 This is also a solution that has worked for some people who have received the same Windows Hello Face error message. To try this solution:

1. Press**Windows + E** keys to open the File Explorer. Copy and paste the following path into the address bar, then hit**Enter** .  
`**C:\Windows\System32\WinBioPlugIns\FaceDriver**`  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/face-driver1.jpg)
2. Right-click on**HelloFace.inf** and select**Install** from the pop-up menu.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027162/19272" target="_top" id="2027162">
  <img src="//a.impactradius-go.com/display-ad/19272-2027162" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027162/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2022/08/face-dirver2.jpg)
3. After the file is successfully installed, restart your device and check if you can use the Windows Hello Face now.

If this trick doesn’t give you luck, try the next one.

## Fix 4 – Restart Windows Biometric Service

 The Windows Biometric Service is responsible for managing the Windows Hello feature and allowing client applications to access and handle biometric data. So resetting the Biometric Service may help with the Windows Hello Face not working issue. This is how it’s done:

1. Press**Windows + R** keys to open the Run box, type**services.msc** in it and then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/Run-services.msc_.jpg)
2. In the Service windows, find**Windows Biometric Service** and right-click on it, then select**Restart** form the pop-up menu.  

![](https://images.drivereasy.com/wp-content/uploads/2022/08/windows-bio-service.jpg)
3. Right-click on the Press**Windows + I** keys to open the settings and then select**Accounts** .  

![](https://images.drivereasy.com/wp-content/uploads/2022/08/setting-accounts-1.jpg)
4. Click the**Sign-in options** in the left panel, select**Windows Hello Face** and then register the Hello Face data again.  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/signin-option-hello-face.jpg)
5. Restart your PC and check if you can use the Windows Hello Face now.

Move on to the next fix if this one doesn’t work for you.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111995/7443" target="_top" id="2111995">
  <img src="//a.impactradius-go.com/display-ad/7443-2111995" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111995/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 5 – Run System File Checker

 Corrupted or damaged system files on your computer could also be the cause of the problem. To check your computer for problematic system files, you can perform a system scan.

 You can always use Command Prompt to run the**sfc /scannow** command, but this local utility has some limitations in performing a full in-depth scan. As an alternative, we recommend you use **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  . This is a powerful Windows repair tool that can scan, diagnose, and identify faulty system files before automatically and safely repairing them. And it takes only a few clicks:

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Fortect.  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/fortect-download-page-1.jpg)
2. Run Fortect. It will start a deep scan of your system. (This process may take a few minutes).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938745/19272" target="_top" id="1938745">
  <img src="//a.impactradius-go.com/display-ad/19272-1938745" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938745/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. After the scan is completed, click **Start Repair** if Fortect detects any missing or broken system files or other issues.  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The repair is available with the paid version of Fortect which comes with a 60-day money-back guarantee. If you encounter any issues while using Fortect, please contact **[Fortect support](https://www.fortect.com/company/contacts/) .**

## Fix 6: Disable ESS (Enhanced Sign-in Security)

 If you can still use your camera for other activities, and Windows Hello is the only one that’s with trouble, you can try to disable the ESS to see if it helps. To do so:

1. On your keyboard, press the**Windows** key and the**I** key at the same time. Select**Accounts > Sign-in options** .  
![](https://www.drivereasy.com/wp-content/uploads/2024/06/image-54.png)
2. Toggle off the option for**Sign in with an external camera or fingerprint reader** .  

![](https://www.drivereasy.com/wp-content/uploads/2024/06/image-55.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068412/7443" target="_top" id="2068412">
  <img src="//a.impactradius-go.com/display-ad/7443-2068412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Restart your computer and see if the Windows Hello error message is gone.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902319/19272" target="_top" id="1902319">
  <img src="//a.impactradius-go.com/display-ad/19272-1902319" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902319/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 6 – Try the Get Help app

 The Get Help app is a built-in Windows service that can answer your tech-support questions, provide solutions, and troubleshoot some of computer issues. If none of the above solutions work for you, you can try this app to see if it can help.

1. Type**Get Help** in the search box on the taskbar and select it from the search results.  
![](https://images.drivereasy.com/wp-content/uploads/2022/08/get-help-1.jpg)
2. Enter the problem you need to solve, then you’ll have a chat with a virtual agent who will run a troubleshooter to help you fix the Hello Face problems  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925570/19272" target="_top" id="1925570">
  <img src="//a.impactradius-go.com/display-ad/19272-1925570" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925570/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2022/08/get-help-2-1.jpg)

---

 That’s it – hopefully, the six fixes we have here can help you resolve your camera not compatible with the Windows Hello Face problem. If you have other solutions or ideas for this problem, please leave a comment below and share them with us!

* [error massage](/tag-search/?tagId=62091)
* [Windows Hello Face](/tag-search/?tagId=62090)

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-unlock-video-potential-premium-lens-selection-tips/"><u>[New] 2024 Approved Unlock Video Potential Premium Lens Selection Tips</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-distraction-free-deliberations-perfecting-backdrop-blur-on-mobile-devices/"><u>[New] In 2024, Distraction-Free Deliberations Perfecting Backdrop Blur on Mobile Devices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-advanced-gopro-editing-straightening-fisheye-lens/"><u>2024 Approved Advanced GoPro Editing Straightening Fisheye Lens</u></a></li>
<li><a href="https://win-howtos.techidaily.com/failed-installation-of-windows-11-1607-fixes-and-solutions/"><u>Failed Installation of Windows 11 1607: Fixes and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fatal-circuitry-issue-system-halt/"><u>Fatal Circuitry Issue: System Halt</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Samsung Galaxy M14 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-addressing-persistent-pauses-at-0-during-windows-updates/"><u>Mastering the Fix: Addressing Persistent Pauses at 0% During Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimize-performance-managing-high-cpu-use-by-microsoft-defender-antivirus-in-windows-10-devices/"><u>Optimize Performance: Managing High CPU Use by Microsoft Defender Antivirus in Windows 10 Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-spooler-service-activated-windows-7/"><u>Print Spooler Service Activated, Windows 7</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-how-to-getting-started-with-pokemon-go/"><u>The Ultimate How-To: Getting Started with Pokémon GO</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-your-ps4-dualshocks-charging-issue/"><u>Troubleshooting Guide: Fixing Your PS4 Dualshock's Charging Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-permanent-100-on-windows-update/"><u>Troubleshooting Guide: Resolving Permanent 100% on Windows Update</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ding-finesse-imovie-videos-meeting-youtube-standards/"><u>Uploading Finesse IMovie Videos Meeting YouTube Standards</u></a></li>
</ul></div>

