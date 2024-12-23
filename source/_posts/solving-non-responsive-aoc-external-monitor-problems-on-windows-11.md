---
title: Solving Non-Responsive AOC External Monitor Problems on Windows 11
date: 2024-12-20T16:17:43.132Z
updated: 2024-12-22T21:32:35.688Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving Non-Responsive AOC External Monitor Problems on Windows 11
excerpt: This Article Describes Solving Non-Responsive AOC External Monitor Problems on Windows 11
thumbnail: https://thmb.techidaily.com/064bb5c43db4056e998dcb4f406cb778296c7343d435216b9b3443b144736cca.jpg
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-links.techidaily.com/updated-streamline-your-podcast-with-ease-for-2024/"><u>[Updated] Streamline Your Podcast With Ease for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208127772-beating-the-blues-overcoming-update-failed-hurdles-in-warframe-solved/"><u>Beating the Blues: Overcoming 'Update Failed' Hurdles in Warframe – Solved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dell-laptop-keyboards-that-wont-work-solutions-at-your-fingertips/"><u>Dell Laptop Keyboards That Won't Work - Solutions at Your Fingertips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-fixing-inactive-usb-hardware-on-windows-11/"><u>Effective Solutions for Fixing Inactive USB Hardware on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-resolving-windows-11s-0x8072efd-issue/"><u>Effective Solutions for Resolving Windows 11'S 0X80#72EFD Issue</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/tial-techniques-in-creating-youtube-thumbnails-that-stand-out-for-2024/"><u>Essential Techniques in Creating YouTube Thumbnails That Stand Out for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-broken-keyboard-when-you-cant-even-access-your-computer-essential-troubleshooting-steps/"><u>How to Fix a Broken Keyboard When You Can't Even Access Your Computer – Essential Troubleshooting Steps</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-magic-5-lite-by-drfone-android-unlock-remove-google-frp/"><u>How to remove Google FRP Lock on Magic 5 Lite</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-an-issue-occurred-when-reinstalling-windows-11-message/"><u>How to Resolve the 'An Issue Occurred When Reinstalling Windows 11' Message</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-best-action-recorders-with-front-view-panels/"><u>In 2024, Best Action Recorders with Front View Panels</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-zte-by-drfone-android/"><u>In 2024, How to Bypass FRP from ZTE?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/managed-system-configurations-for-windows-solving-the-mystery-of-auto-settings-adjustment-in-business-environments/"><u>Managed System Configurations for Windows - Solving the Mystery of Auto-Settings Adjustment in Business Environments</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pioneering-sky-hdr-images-at-your-fingertips-for-2024/"><u>Pioneering Sky HDR Images at Your Fingertips for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/reaping-rewards-a-comprehensive-guide-to-7-14-stardew-mods-for-2024/"><u>Reaping Rewards A Comprehensive Guide to #7-14 Stardew Mods for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/samsung-galaxy-tab-s4-review-versatile-android-tablet/"><u>Samsung Galaxy Tab S4 Review: Versatile Android Tablet</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-solutions-for-resolving-windows-update-error-code-0x80070652/"><u>Simple Solutions for Resolving Windows Update Error Code 0X80070652</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-tips-for-logitech-mouse-scroll-wheel-problems/"><u>Solution Tips for Logitech Mouse Scroll Wheel Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/speeding-up-league-of-legends-file-transfers-expert-troubleshooting-guide/"><u>Speeding Up League of Legends File Transfers – Expert Troubleshooting Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-notch-low-speed-mobile-video-tools-iosandroid/"><u>Top-Notch Low-Speed Mobile Video Tools iOS/Android</u></a></li>
</ul></div>

