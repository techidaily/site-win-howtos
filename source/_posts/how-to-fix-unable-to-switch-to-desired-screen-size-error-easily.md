---
title: How to Fix 'Unable to Switch to Desired Screen Size' Error Easily
date: 2024-08-19T07:44:53.342Z
updated: 2024-08-20T07:44:53.342Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix 'Unable to Switch to Desired Screen Size' Error Easily
excerpt: This Article Describes How to Fix 'Unable to Switch to Desired Screen Size' Error Easily
thumbnail: https://thmb.techidaily.com/5fff478f3be544d568418507cea4779277edfa2a7ab7bd041018e6ff63ff5cdd.jpg
---

## Trouble with Windows 10 Version 1607'S New Features? Here's How to Fix It

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

**2)** In Command Prompt, type the following lines of command and press**Enter**on your keyboard after typing each:

* _**net stop bits**_
* _**net stop wuauserv**_
* _**net stop appidsvc**_
* _**net stop cryptsvc**_
(These commands will stop the services that Windows Update requires to download and install updates.)**3)** Type these lines of command and press**Enter** after typing each in Command Prompt:
* _**Ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old**_
* _**Ren %systemroot%\\system32\\catroot2 catroot2.old**_
(This will rename the_SoftwareDistribution_and_catroot2_folder, which are used by Windows Update to store data and temporary files. Your system will detect that these folders are missing, and then it’ll create new ones. The purpose of this is to make the system use the new_SoftwareDistribution_and _catroot2_folders so that Windows Update can avoid issues from the old ones.)**4)**Still in Command Prompt, type these commands and press Enter after each to restart the services you closed just now:
* _**net start bits**_
* _**net start wuauserv**_
* _**net start appidsvc**_
* _**net start cryptsvc**_
**5)**Run Windows Update and check to see if your computer can install the 1607 update.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Method 4: Temporarily disable your antivirus software

Sometimes your system can’t install new updates due to the interference from your**antivirus software**. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.**IMPORTANT:**Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-master-the-art-of-superior-image-quality-enable-youtubes-av1/"><u>[New] Master the Art of Superior Image Quality  Enable YouTube's AV1</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-unveiling-the-power-of-magix-clip-studio-for-2024/"><u>[New] Unveiling the Power of MAGIX Clip Studio for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-3-top-notch-smartphones-excelling-at-video-capture/"><u>2024 Approved  3 Top-Notch Smartphones Excelling at Video Capture</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-kinemaster-focus-mastery-a-filmmakers-guide-to-sharper-images/"><u>2024 Approved  Kinemaster Focus Mastery  A Filmmaker's Guide to Sharper Images</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-photography-on-instagram-adding-images-made-simple/"><u>2024 Approved  Photography on Instagram  Adding Images Made Simple</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-premier-macos-sierra-tools-for-video-changeovers/"><u>2024 Approved  Premier macOS Sierra Tools for Video Changeovers</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/6-proven-ways-to-unlock-oppo-reno-8t-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Oppo Reno 8T Phone When You Forget the Password</u></a></li>
<li><a href="https://win-howtos.techidaily.com/best-techniques-for-unfreezing-the-windows-11-taskbar-issue/"><u>Best Techniques for Unfreezing the Windows 11 Taskbar Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/combat-blizzards-wow-lag-proven-strategies-for-smooth-gameplay/"><u>Combat Blizzard's Wow Lag: Proven Strategies for Smooth Gameplay</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-to-fix-amd-catalyst-control-center-cannot-be-started/"><u>Easy to Fix AMD Catalyst Control Center Cannot Be Started</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-tackle-the-windows-11-update-error-0xc190n0028-a-users-manual/"><u>Effective Solutions to Tackle the Windows 11 Update Error 0XC190n0028: A User's Manual</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-correcting-the-port-reset-failed-warning-for-your-usb-gadget-in-windows-10/"><u>Expert Advice: Correcting the 'Port Reset Failed' Warning for Your USB Gadget in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-fixing-the-minecraft-wont-start-error-in-windows-computers/"><u>Expert Advice: Fixing the 'Minecraft Won't Start' Error in Windows Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-successfully-connecting-bluetooth-gadgets-to-windows-10-this-year/"><u>Expert Advice: Successfully Connecting Bluetooth Gadgets to Windows 10 This Year</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-how-to-fix-your-pc-when-it-gets-stuck-on-initial-boot-display/"><u>Fixed: How to Fix Your PC When It Gets Stuck on Initial Boot Display</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-htc-u23-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-infinite-load-ultimate-guide-to-overcoming-stuck-screens-in-valorant/"><u>Fixing the Infinite Load: Ultimate Guide to Overcoming Stuck Screens in Valorant</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-basic-to-bold-installing-unique-customizable-ringtones-and-sounds-on-android/"><u>From Basic to Bold  Installing Unique, Customizable Ringtones & Sounds on Android</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-poco-x5-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Poco X5 Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-application-print-driver-host-failure-for-older-windows-versions/"><u>How to Repair 'Application Print Driver Host Failure' For Older Windows Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-no-audio-device-installed-error-in-windows-operating-systems/"><u>How to Resolve No Audio Device Installed Error in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-fix-windows-11-update-failure-error-code-0xc1e90208/"><u>How to Successfully Fix Windows 11 Update Failure (Error Code: 0XC1e90208)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Nokia G22? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-open-your-iphone-13-pro-without-a-home-button-drfone-by-drfone-ios/"><u>In 2024, How To Open Your iPhone 13 Pro Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-master-video-transitions-and-effects-using-gopro-studio-protips/"><u>In 2024, Master Video Transitions and Effects Using GoPro Studio ProTips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-and-mouse-woes-revitalize-a-broken-usb-mouse-with-these-proven-fix-techniques/"><u>Laptop and Mouse Woes? Revitalize a Broken USB Mouse with These Proven Fix Techniques!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-mouse-pad-not-responding-heres-how-you-can-fix-it-on-any-window-os/"><u>Lenovo Mouse Pad Not Responding? Here's How You Can Fix It on Any Window OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202987997-mac-camera-issues-resolve-them-with-these-easy-techniques/"><u>Mac Camera Issues? Resolve Them with These Easy Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-fixing-unexpected-shutdowns-in-windows-11-step-by-step-strategies/"><u>Master the Art of Fixing Unexpected Shutdowns in Windows 11 – Step by Step Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-a-guide-to-repairing-unknown-usb-and-port-reset-faults-in-windows-11-systems/"><u>Mastering the Fix: A Guide to Repairing Unknown USB and Port Reset Faults in Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-system-challenges-with-absent-xinput13dll/"><u>Navigating System Challenges with Absent XINPUT1_3.dll</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-device-recognition-issues-bluetooth-setup-fixed-in-windows-11/"><u>Overcoming Device Recognition Issues: Bluetooth Setup Fixed in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-limited-memory-challenges-fixing-windows-10-errors/"><u>Overcoming Limited Memory Challenges: Fixing Windows 10 Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-timely-start-issues-solutions-to-service-error-1053/"><u>Overcoming Timely Start Issues - Solutions to Service Error 1053</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-fix-minecraft-not-starting-on-windows-os/"><u>Resolved: How to Fix 'Minecraft Not Starting on Windows OS'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-steelseries-arctis-5-mic-expert-solutions-to-get-it-working-again/"><u>Revive Your SteelSeries Arctis 5 Mic: Expert Solutions to Get It Working Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-corsair-keyboard-expert-troubleshooting-guide/"><u>Reviving Your Corsair Keyboard: Expert Troubleshooting Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-mystery-of-missing-power-sources-in-electronics-easy-tips/"><u>Solving the Mystery of Missing Power Sources in Electronics: Easy Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-eradicating-the-stop-error-0xc0000005-in-microsoft-windows-systems/"><u>Step-by-Step Solution: Eradicating the STOP Error 0XC0000005 in Microsoft Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-unfreezing-your-laptops-trackpad-or-external-mouse/"><u>Step-by-Step Solutions: Unfreezing Your Laptop's Trackpad or External Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-excessive-sound-on-your-ps4-console-troubleshooting-steps/"><u>Tackling Excessive Sound on Your PS4 Console: Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-criticality-of-xinput13dll-and-troubleshooting-its-missing-status/"><u>The Criticality of XINPUT1_3.dll & Troubleshooting Its Missing Status</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolution-for-elevated-cpu-drain-by-microsofts-msmpeng-process-on-windows-10/"><u>Troubleshooting and Resolution for Elevated CPU Drain by Microsoft's MsMpEng Process on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlock-touchpad-integrity-with-quick-fixes/"><u>Unlock Touchpad Integrity with Quick Fixes!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-your-gpu-to-the-new-nvidia-gtx-1650-super-drivers-compatible-with-windows-1011/"><u>Update Your GPU to the New NVIDIA GTX 1650 Super Drivers: Compatible with Windows 10/11</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-auto-translate-youtube-videos-into-different-languages/"><u>Updated Auto Translate YouTube Videos Into Different Languages</u></a></li>
<li><a href="https://win-howtos.techidaily.com/vcruntime140dll-not-found-heres-how-to-quickly-correct-it/"><u>VCRUNTIME140.dll Not Found? Here's How to Quickly Correct It!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-how-to-resolve-problems-when-trying-to-cast-devices/"><u>Windows 11: How to Resolve Problems When Trying to Cast Devices</u></a></li>
</ul></div>
