---
title: "Troubleshooting Guide: How to Restore Print to PDF Functionality on Windows 10 and 11"
date: 2024-09-05T10:00:18.013Z
updated: 2024-09-06T10:00:18.013Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: How to Restore Print to PDF Functionality on Windows 10 and 11"
excerpt: "This Article Describes Troubleshooting Guide: How to Restore Print to PDF Functionality on Windows 10 and 11"
thumbnail: https://thmb.techidaily.com/099f29eab2c71ad55d4343f08e03217de8a45609b98e37e8d331924ca8f4791a.jpg
---

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121332/18498" target="_top" id="2121332">
  <img src="//a.impactradius-go.com/display-ad/18498-2121332" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121332/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Troubleshooting Nonfunctional USB Ports on Windows 10/11 - Fixed

 If you find one of your USB devices on Windows 10 isn’t working, read on. Whether it’s a USB mouse, keyboard, pen drive, printer, or some other USB devices altogether, this guide should resolve your problem.

 Note that there are 5 possible solutions here. You may not need to try them all; just start at the top of the list and work your way down.

[1:**Check if the device itself is faulty**](#1)
[2:**Check your power supply**](#2)
[3: **Check your power management settings**](#3)
[4:**Check your USB device drivers**](#4)
[5:**Check your USB ports**](#5)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Method 1: Check if the device itself is faulty**

 If the USB device was working before you upgraded to Windows 10, it’s unlikely to be faulty. But coincidences do occur. It’s certainly_possible_ that your device just happened to die right at the same time that you upgraded Windows. So it’s best to rule that possibility out for sure before spending time on more complex troubleshooting.

 To check if the USB device is faulty, simply unplug it (‘Eject’ it if it’s a USB storage device) and plug it into another computer. If it works, the device is fine. If it doesn’t, then you’ve isolated the problem! You just need to buy a replacement.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139123/17108" target="_top" id="2139123">
  <img src="//a.impactradius-go.com/display-ad/17108-2139123" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139123/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Method 2: Check your power supply (laptop only)**

 Your laptop’s power supply delivers power to your USB ports. If, for some reason, it fails to do this properly, the devices plugged into those USB ports may stop working. Sometimes, this can be fixed quite simply:

1) Unplug the power supply and charger plug from your laptop

2) Restart your laptop

3) Connect your USB device to the laptop again

4) Plug the power supply back in

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123469/16836" target="_top" id="2123469">
  <img src="//a.impactradius-go.com/display-ad/16836-2123469" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123469/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Method 3: Check your power management settings**

 In order to save power, by default, Windows switches your USB controllers off when they’re not in use, and switches them back on again when they’re needed. Unfortunately, sometimes this approach doesn’t work as intended, and Windows fails to switch your USB controllers on again.

 To rule this out as the cause of your USB woes, just stop Windows from ‘managing’ power to your USB controllers and devices:

 1) Open Device Manager (type “Device Manager” in the Windows search field)

![](https://www.drivereasy.com/wp-content/uploads/2015/11/run-devmgmt.msc_.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135371/19272" target="_top" id="2135371">
  <img src="//a.impactradius-go.com/display-ad/19272-2135371" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135371/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Expand the**Universal Serial Bus controllers** branch

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430ac388d01.png)

 3) Double-click the first **USB Root Hub** device in the list (if you see only one USB Root Hub device, that’s fine)  

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430af9a6bc2.png)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Click the **Power Management**  tab  

![](https://images.drivereasy.com/wp-content/uploads/2016/05/img_57342d99c355a.png)

5) Un-check the **Allow the computer to turn off this device to save power**  checkbox, and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2016/05/img_57342dd22bb58.png)

 6) Repeat steps 3-5 for each  USB Root Hub device in your list of Universal Serial Bus controllers

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430b577123a.png)

## **Method 4: Check your USB device drivers**

 Your USB ports not working problem is probably being caused by driver issues. The steps above may resolve it, but if they don’t, or you’re not confident playing around with drivers manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

 2) Run Driver Easy and click**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_594841d4c15c1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the**Update** button next to a flagged USB driver to automatically download and install the correct version of this driver (you can do this with the FREE version).

 Or click**Update All**  to automatically download and install the correct version of_all_ the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_5948dbf290aa4.jpg)

**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

## **Method 5: Check your USB ports**

 If none of the above methods resolve your problem, your USB ports might be damaged. To find out, you can take your PC to a repair store and ask them to check. If your USB ports are damaged, the repairer should be able to replace them fairly inexpensively.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-art-of-retracing-instagram-pictures-roots/"><u>[New] 2024 Approved  The Art of Retracing Instagram Pictures' Roots</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-optimal-tactics-for-saving-android-interactions/"><u>[New] In 2024, Optimal Tactics for Saving Android Interactions</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-iphone-lens-wisdom-stunning-image-secrets/"><u>[New] IPhone Lens Wisdom  Stunning Image Secrets</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-top-techniques-for-optimal-steam-gameplay-capture/"><u>[Updated] 2024 Approved  Top Techniques for Optimal Steam Gameplay Capture</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-highest-rated-video-call-software-not-zoom-for-pcs-and-phones/"><u>[Updated] In 2024, Highest-Rated Video Call Software (Not Zoom) for PCs & Phones</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-from-playtime-to-pixels-the-ultimate-list-of-6-ways-to-record-minecraft/"><u>2024 Approved  From Playtime to Pixels  The Ultimate List of 6 Ways to Record Minecraft</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-quick-and-easy-caption-crafting-for-engaging-fb-video-posts/"><u>2024 Approved  Quick and Easy Caption Crafting for Engaging FB Video Posts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-comprehensive-guide-adding-modifying-and-deleting-page-breaks-in-excel/"><u>A Comprehensive Guide: Adding, Modifying, and Deleting Page Breaks in Excel</u></a></li>
<li><a href="https://win-able.techidaily.com/avatar-pandora-a-trouble-free-enhanced-gaming-experience-for-windows-users/"><u>Avatar: Pandora - A Trouble-Free, Enhanced Gaming Experience for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/boost-productivity-in-excel-with-its-revolutionary-time-saving-feature/"><u>Boost Productivity in Excel with Its Revolutionary Time-Saving Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/calculating-cagr-with-ease-using-microsoft-excel-tips-and-tricks-for-accurate-results/"><u>Calculating CAGR with Ease Using Microsoft Excel: Tips and Tricks for Accurate Results</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-exploration-of-windows-narrators-legacy-keys/"><u>Comprehensive Exploration of Windows Narrator's Legacy Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-tutorial-crafting-effective-headers-using-microsoft-excel-tools/"><u>Comprehensive Tutorial: Crafting Effective Headers Using Microsoft Excel Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/customizing-your-excel-changing-header-and-footer-in-first-sheet-layout/"><u>Customizing Your Excel: Changing Header & Footer in First Sheet Layout</u></a></li>
<li><a href="https://win-howtos.techidaily.com/discovering-enhancements-and-improvements-in-microsofts-windows-11-creators-version-update/"><u>Discovering Enhancements and Improvements in Microsoft’s Windows 11 Creator’s Version Update</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-it-guide-combatting-nvidia-drivers-glitches/"><u>Fix-It Guide: Combatting Nvidia Drivers Glitches</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-zte-blade-a73-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from ZTE Blade A73 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-to-do-if-your-iphone-6-plus-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>In 2024, What to do if your iPhone 6 Plus has bad ESN or blacklisted IMEI?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-precision-with-excels-truncate-feature-a-step-by-step-guide/"><u>Mastering Precision with Excel's TRUNCATE Feature: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-index-function-a-step-by-step-guide-to-extract-data-in-microsoft-excel/"><u>Mastering the Index Function: A Step-by-Step Guide to Extract Data in Microsoft Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-technique-of-cutting-out-images-without-backgrounds-using-excel-tools/"><u>Mastering the Technique of Cutting Out Images Without Backgrounds Using Excel Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-uniqueness-a-guide-to-identifying-and-organizing-distinct-data-with-microsoft-excel/"><u>Mastering Uniqueness: A Guide to Identifying and Organizing Distinct Data with Microsoft Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/potential-threats-when-using-microsoft-office-on-apples-macos-platform/"><u>Potential Threats when Using Microsoft Office on Apple's macOS Platform</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolve-your-2k21-nba-basketball-game-freezing-problems-with-our-expert-fixes-202n4/"><u>Resolve Your 2K21 NBA Basketball Game Freezing Problems with Our Expert Fixes (202N4)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revolutionary-upgrade-new-features-in-the-latest-version-of-microsoft-excel-web-app/"><u>Revolutionary Upgrade: New Features in the Latest Version of Microsoft Excel Web App</u></a></li>
<li><a href="https://win-howtos.techidaily.com/setting-microsoft-excel-as-your-macs-primary-spreadsheet-software-a-step-by-step-guide/"><u>Setting Microsoft Excel as Your Mac's Primary Spreadsheet Software: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-techniques-for-transposing-rows-into-columns-in-microsoft-excel/"><u>Simple Techniques for Transposing Rows Into Columns in Microsoft Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-on-applying-universal-cell-formatting-in-multiple-excel-workbooks/"><u>Step-by-Step Guide on Applying Universal Cell Formatting in Multiple Excel Workbooks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-building-your-project-schedule-with-ms-excel/"><u>Step-by-Step Guide: Building Your Project Schedule with MS Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-transferring-pictured-data-into-excel-apps-on-smartphones/"><u>Step-by-Step Guide: Transferring Pictured Data Into Excel Apps on Smartphones</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-on-converting-excel-charts-to-picture-format-for-easy-sharing-and-editing/"><u>Step-by-Step Tutorial on Converting Excel Charts to Picture Format for Easy Sharing and Editing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-tutorial-on-splitting-your-excel-window-for-enhanced-productivity/"><u>The Ultimate Tutorial on Splitting Your Excel Window for Enhanced Productivity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-mastering-cell-splitting-techniques-in-microsoft-excel/"><u>Ultimate Guide: Mastering Cell Splitting Techniques in Microsoft Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-the-hidden-potential-of-mail-merge-discover-4-essential-applications/"><u>Unlocking the Hidden Potential of Mail Merge: Discover 4 Essential Applications</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-cool-video-editor-how-to-add-cool-effects-to-video/"><u>Updated In 2024, Cool Video Editor How to Add Cool Effects to Video</u></a></li>
<li><a href="https://win-howtos.techidaily.com/utilizing-excels-embedded-stock-market-tool-for-efficient-data-analysis/"><u>Utilizing Excel's Embedded Stock Market Tool for Efficient Data Analysis</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/visual-victory-amd-radeon-evolution-for-2024/"><u>Visual Victory  AMD Radeon Evolution for 2024</u></a></li>
</ul></div>
