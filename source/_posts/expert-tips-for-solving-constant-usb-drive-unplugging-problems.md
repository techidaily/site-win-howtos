---
title: Expert Tips for Solving Constant USB Drive Unplugging Problems
date: 2025-02-11T17:14:08.260Z
updated: 2025-02-17T01:50:28.007Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Tips for Solving Constant USB Drive Unplugging Problems
excerpt: This Article Describes Expert Tips for Solving Constant USB Drive Unplugging Problems
thumbnail: https://thmb.techidaily.com/6d6cac7e56858e74f7b2bccf55f62023ebda6695ca7ede5596cad05ed3aac833.jpg
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-top-3-strategies-for-capturing-real-time-sports-events-online/"><u>[Updated] 2024 Approved Top 3 Strategies for Capturing Real-Time Sports Events Online</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-top-10-impressive-srt-converters-for-mac-and-windows/"><u>2024 Approved Top 10 Impressive SRT Converters for Mac and Windows</u></a></li>
<li><a href="https://fox-direct.techidaily.com/crafting-professionally-recorded-audio-via-audacity-for-2024/"><u>Crafting Professionally Recorded Audio via Audacity for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-guide-repairing-an-unresponsive-hdmi-adapter-linked-to-usb/"><u>DIY Guide: Repairing an Unresponsive HDMI Adapter Linked to USB</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-tackling-miracast-rejection-by-device-a-comprehensive-guide-success/"><u>Expert Advice on Tackling 'Miracast Rejection by Device': A Comprehensive Guide Success</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-screen-mirroring-failures-on-windows-10-devices/"><u>How to Fix Screen Mirroring Failures on Windows 10 Devices</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/m1-processor-transforming-the-video-editing-experience/"><u>M1 Processor Transforming the Video Editing Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-error-code-24-this-device-is-unavailable-on-windows-1187-systems/"><u>Resolving Error Code 24: 'This Device Is Unavailable' On Windows 11/8/7 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-fixes-for-when-your-windows-update-gets-stuck-on-0/"><u>Simple Fixes for When Your Windows Update Gets Stuck on 0%</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-of-an-unresponsive-start-button-on-windows-11-systems/"><u>Solving the Problem of an Unresponsive Start Button on Windows 11 Systems</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/top-5-low-cost-pinterest-video-download-software-for-2024/"><u>Top 5 Low-Cost Pinterest Video Download Software for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-resolving-firefoxs-unknown-certificate-issue-secerror/"><u>Troubleshooting Tips: Resolving Firefox's Unknown Certificate Issue (SEC_ERROR)</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-make-unforgettable-moments-top-video-collage-apps-for-ios-for-2024/"><u>Updated Make Unforgettable Moments Top Video Collage Apps for iOS for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/zoom-meetings-at-your-fingertips-from-gmail/"><u>Zoom Meetings at Your Fingertips From Gmail</u></a></li>
<li><a href="https://win-amazing.techidaily.com/movavi-avi-mp4-ram/"><u>무료 인터넷용 Movavi AVI에서 MP4로 리모델링: RAM 라이피틱 강화</u></a></li>
</ul></div>

