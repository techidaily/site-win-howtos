---
title: Effortless Ways to Overcome the Window's Update Failure (Error 0X80070652)
date: 2024-09-10T23:34:10.913Z
updated: 2024-09-18T00:05:48.397Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Effortless Ways to Overcome the Window's Update Failure (Error 0X80070652)
excerpt: This Article Describes Effortless Ways to Overcome the Window's Update Failure (Error 0X80070652)
thumbnail: https://thmb.techidaily.com/28e42e440f02f5ea5682c6780700b9aec886bd9aca849f4db3b0e7bc708ddb0e.jpg
---

## Error-Free Windows Updates: Overcome Error 8007000E Effortlessly

![](https://images.drivereasy.com/wp-content/uploads/2019/10/Windows-Update-error-800700e.jpg)

 If you’re seeing an **error code 8007000e** when performing a Windows update,  you’re not alone. Many Windows users are reporting it. This error code usually appears when they try to update to a new build of Windows system. The reason behind it is that some update files are missing or corrupted.

 The good news is you can fix it. You should be able to fix the problem quite easily using one of the solutions we’ve listed below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

 You may not have to try them all. Just work your way down the list until you find the one that works.

1. **[Install the latest version of IE for Windows 7](https://tools.techidaily.com/drivereasy/download/)**
2. **[Run the Windows Update Troubleshooter](https://tools.techidaily.com/drivereasy/download/)**
3. **[Restart the Windows Update service](https://tools.techidaily.com/drivereasy/download/)**
4. **[Run the DISM tool](https://tools.techidaily.com/drivereasy/download/)**
5. **[Run System File Checker](https://tools.techidaily.com/drivereasy/download/)**
6. **[Download updates from Microsoft Update Catalog manually](https://tools.techidaily.com/drivereasy/download/)**
7. **[Want us to fix the problem for you?](https://tools.techidaily.com/drivereasy/download/)**

---

### Fix 1: Install the latest version of IE for Windows 7

 This fix is for the users who are using **Windows 7** operating system. If the current OS of your PC is not Windows 7, you can skip this fix.

 An outdated IE web browser and certain Hot fixes may trigger the **Windows Update error 8007000e** . Try updating your IE to the latest version and removing two hot fixes to see if this issue persists. Here is how to do it:

1. Click **[here](https://www.microsoft.com/en-us/download/Internet-Explorer-11-for-Windows-7-details.aspx)**  to visit Microsoft Download Center.
2. Click Download to download the latest version of IE 11.  
![download the latest version of IE 11](https://images.drivereasy.com/wp-content/uploads/2018/09/download-the-latest-version-of-IE-11.jpg)
3. Install the latest version of IE 11 on your PC.

4. On your keyboard, press **the Windows logo key** and **R** at the same time to open the Run dialog. Then Type **control** and press **Enter** to open the Control Panel.  
![step 4](https://images.drivereasy.com/wp-content/uploads/2018/09/step-4.jpg)
5. In the search box in the upper-right corner, type **installed update** . Click **View installed updates** under **Programs and Features**  to view installed updates on your PC.  
![View installed updates](https://images.drivereasy.com/wp-content/uploads/2018/09/View-installed-updates.jpg)
6. Delete **Hotfix for Microsoft Windows (KB2534111)** and **Hotfix for Microsoft Windows (KB2639308)** .   **If you don’t find these two hot fixes, please skip this step.**  
![step 6](https://images.drivereasy.com/wp-content/uploads/2018/09/step-6.jpg)
7. Restart your PC.
8. Open IE and go through the welcome screen. Then close all the tabs to close IE.
9. Restart your PC.

 Go and check Windows Update again to see whether you can perform the Windows update or not. If you can perform a Windows update, then you’ve fix this issue.

### Fix 2: Run the Windows Update Troubleshooter

 You can download and run **the Windows Update Troubleshooter** to automatically diagnose and resolve any issues regarding Windows Update. Here is how to do it:

1. Click **[here](http://aka.ms/diag%5Fwu)** to download the Windows Update Troubleshooter.
2. **Double-click** the downloaded file (**WindowsUpdate.diagcab** ) to run the troubleshooter, and then click **Next** .  
![Windows Update](https://images.drivereasy.com/wp-content/uploads/2018/09/Windows-Update.jpg)  
**Note:** If your current operating system is **Windows 7** , you just need to wait until the troubleshooter finishes the process and shows you the process result. If your current operating system is **Windows 8** or **Windows 10** , you may need to follow the steps below.

3. If there is a more recent version of Windows Update troubleshooter available, click to run it.  
![Updated Troubleshooter Available](https://images.drivereasy.com/wp-content/uploads/2018/09/Updated-Troubleshooter-Available.jpg)
4. In the new version of Windows Update troubleshooter, click **Next** . The troubleshooter will check the available updates for your machine.  
![Fix 2 Step 4](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-2-Step-4.jpg)
5. Click **Apply this fix**  to start the update process in the background immediately.  
![Fix 2 Step 5](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-2-Step-5.jpg)

 The troubleshooter will try to fix the issue for you. You can restart your computer and try performing the Windows update again. If it still doesn’t work, please try the next fix.

### Fix 3: Restart the Windows Update service

 You may see this error code if there is something wrong with the Windows Update service. You can try restarting the Windows Update service to resolve this problem. Here’s how to do it:

1. On your keyboard, press **the Windows Logo key** and **R** at the same time to open the Run dialog, then type **services.msc** and press **Enter** to open the Services window.  
![Fix 3 step 1](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-3-step-1.jpg)
2. Right-click **Windows Update**  and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.  

![Fix 3 step 2](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-3-step-2.jpg)
3. On your keyboard, press **the Windows Logo Key** and **E** at the same time to open **File Explorer** . Copy the path below and paste it in the address bar, then press **Enter** on your keyboard to go to the **DataStore**  folder.  

**C:\\Windows\\SoftwareDistribution\\DataStore**  

![Fix 3 step 3](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-3-step-3.jpg)
4. Delete all the files in the folder **DataStore** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. On your keyboard, press **the Windows Logo Key** and **E** at the same time to open **File Explorer** . Copy the path below and paste it in the address bar, then press **Enter** on your keyboard to open the **Download**  folder.  

**C:\\Windows\\SoftwareDistribution\\Download**  

![Fix 3 step 5](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-3-step-5.jpg)
6. Delete all the files in the folder **Download** .

7. In the Services window, right-click **Windows Update**  and select **Start** .  
![Fix 3 step 7](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-3-step-7.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075483/7443" target="_top" id="2075483">
  <img src="//a.impactradius-go.com/display-ad/7443-2075483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075483/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Go and check Windows Update again to see whether you can perform the Windows update or not. If it still doesn’t work, please try the next fix.

### Fix 4: Run the DISM tool

 This annoying issue is probably caused by the corrupted Windows update files. In this case, running   **the Deployment Image Servicing and Management (DISM) tool** may resolve this issue. Just follow the step-by-step instructions to run the DISM tool:

1. On your keyboard, press **the Windows Logo Key** and **R** at the same time to open the Run dialog. Type**cmd**  and then press **Ctrl** , **Shift** , and **Enter**  on your keyboard at the same time to **run the Command Prompt as administrator** . You will be prompted for permission. Click **Yes** to run the **Command Prompt** .  
![Fix 4 step 1](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-4-step-1.jpg)
2. On your keyboard, type the command lines below one by one and press **Enter** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123729/7443" target="_top" id="2123729">
  <img src="//a.impactradius-go.com/display-ad/7443-2123729" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123729/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Dism /Online /Cleanup-Image /ScanHealth**  
![DISM ScanHealth](https://images.drivereasy.com/wp-content/uploads/2018/09/DISM-ScanHealth.jpg)  
**Note:** When you run the command mentioned above, the DISM tool will scan all the system files and compare them with official system files. The function of this command line is to see if the system file on your PC is consistent with its official source or not. This command line doesn’t fix the corruption.  

**Dism /Online /Cleanup-Image /CheckHealth**  
![DISM CheckHealth](https://images.drivereasy.com/wp-content/uploads/2018/09/DISM-CheckHealth.jpg)  
**Note:** When you run the command line **Dism /Online /Cleanup-Image /CheckHealth** , the DISM tool will check whether your Windows 10 image exists corruptions or not. This command line also doesn’t repair the corrupted files.  

**Dism /Online /Cleanup-Image /RestoreHealth**  
![DISM RestoreHealth](https://images.drivereasy.com/wp-content/uploads/2018/09/DISM-RestoreHealth.jpg)  
 Note: The command line **Dism /Online /Cleanup-Image /RestoreHealth** tells the DISM tool to try to repair the corrupted files detected. It will replace the corrupted files with the files from official source online.

3. Close Command Prompt when the restore operation completed.  
![Fix 4 step 3](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-4-step-3.jpg)

 See if you can perform a Windows update. If this issue persists, try running the System File Checker.

### Fix 5: Run System File Checker

**System File Checker** can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

1. On your keyboard, press **the Windows Logo Key** and then type **cmd** in the search box. When you see **Command Prompt** in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **OK** to run **Command Prompt** .  
![Fix 5 step 1](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-5-step-1.jpg)
2. On your keyboard, type the following command and press **Enter** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885943/19272" target="_top" id="1885943">
  <img src="//a.impactradius-go.com/display-ad/19272-1885943" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885943/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**sfc /scannow**  
![sfc sacannow](https://images.drivereasy.com/wp-content/uploads/2018/09/sfc-sacannow.jpg)
3. When this command operation is completed, close the Command Prompt.

 Run Windows Update again to check whether this fix works or not. If you still fail to install updates for your Windows system, please try the next fix.

### Fix 6: Download updates from Microsoft Update Catalog manually

 If all the fixes above don’t work for you, you can try downloading the updates you failed to install from **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  and install them manually.

 Before downloading Windows updates manually, you need to know the system type of your Windows OS. You can follow the steps below to view the system type information:

1. On your keyboard, press **the Windows Logo key** and **R** at the same time to open the Run dialog. Type **cmd** and press **Enter** to open the Command Prompt.
2. Type the command line **systeminfo** and press **Enter** to view your system type.  
![view system type](https://images.drivereasy.com/wp-content/uploads/2018/09/view-system-type.jpg)

 “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .

**To download and install Windows updates manually:**

1. On your keyboard, press **the Windows Logo Key** and type **Windows Update** , and then press **Enter** to open Windows Update.
2. Click **View update history** to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.
3. Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .
4. Type the update number that you want to download. In this example, type KB3006137 and then click **Search** .  
![Fix 6 step 4](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-6-step-4.jpg)
5. In the list of search results, select right update for your operating system and click **Download** .  

**Note:** If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.
6. In the pop-up window, click the link to start downloading the updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/Fix-6-step-6.jpg)
7. **Double-click** the downloaded file and follow the on-screen instructions to install the update.

## This issue persists?

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576474/17382" target="_top" id="1576474">
  <img src="//a.impactradius-go.com/display-ad/17382-1576474" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576474/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Want us to fix the problem for you?

 If none of the fixes above worked, or you just don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you.

![](https://images.drivereasy.com/wp-content/uploads/2022/04/Free-Tech-Support.jpg)

 All you need to do is **[buy a 1-year subscription to Driver Easy (just $29.95) and you get free technical support as part of your purchase](https://www.drivereasy.com/buy.php?comeid=de-buy-indirect)**  . Then you can contact our computer technicians directly, explain your problem, and they’ll investigate to see if they can resolve it remotely.

 Hopefully one of the fixes above can help you resolve this annoying issue. Please leave your comment below if you have any questions!

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-enhance-your-artistic-expression-10plus-luts-for-zero-price/"><u>[New] 2024 Approved Enhance Your Artistic Expression – 10+ LUTs for Zero Price</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-enhance-your-gopro-footage-top-5-sd-cards-hero-8-7-for-2024/"><u>[Updated] Enhance Your GoPro Footage Top 5 SD Cards (Hero 8, 7) for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-mastering-video-spin-perfecting-instagram-posts/"><u>[Updated] In 2024, Mastering Video Spin Perfecting Instagram Posts</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-shaping-imagery-the-most-innovative-vector-designers-ranked/"><u>[Updated] Shaping Imagery The Most Innovative Vector Designers Ranked</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-and-correcting-insufficient-system-resources-exist-issues-easily/"><u>Addressing and Correcting 'Insufficient System Resources Exist' Issues Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209064984-fix-rdr2-cannot-load-increase-pagefile-with-easy-steps/"><u>Fix 'RDR2 Cannot Load - Increase Pagefile' With Easy Steps!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-crimson-display-issue-overcoming-the-notorious-red-screen-glitch/"><u>Fixing The Crimson Display Issue - Overcoming the Notorious Red Screen Glitch!</u></a></li>
<li><a href="https://network-issues.techidaily.com/immediate-action-for-clear-screens/"><u>Immediate Action for Clear Screens</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-wondering-the-best-alternative-to-hola-on-honor-v-purse-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>In 2024, Wondering the Best Alternative to Hola On Honor V Purse? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212336112-key-trouble-no-more-fixing-inoperative-buttons-on-your-toshiba-laptop/"><u>Key Trouble No More: Fixing Inoperative Buttons on Your Toshiba Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lte-advanced-category-13-with-up-to-600-mbits-download-speeds-using-band-41-2x20-mhz-channel-arrangement-and-up-to-75-mbitn-upload-speeds-also-supports-dl-r99/"><u>LTE Advanced – Category 13 with up to 600 Mbit/S Download Speeds Using Band 41 (2X20 MHz) Channel Arrangement and up to 75 Mbit/N Upload Speeds. Also Supports DL-RevA Protocol Aggregation, but only with Other TANGO Radios on the Network</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-voice-chat-hurdles-in-overwatch-simple-solutions-inside/"><u>Overcoming Voice Chat Hurdles in Overwatch - Simple Solutions Inside</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-wi-fi-setup-addressing-inadequate-actions-on-pcs/"><u>Streamlining Wi-Fi Setup: Addressing Inadequate Actions on PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-high-gpu-usage-from-desktop-window-manager-in-windows-10-and-11-a-step-by-step-guide/"><u>Troubleshooting High GPU Usage From Desktop Window Manager in WINDOWS 10 and 11 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-hdmi-connection-solving-windows-11s-tv-detection-problem/"><u>Troubleshooting the HDMI Connection: Solving Windows 11'S TV Detection Problem</u></a></li>
</ul></div>

