---
title: Cannot Apply Feature Updates for Windows 10 Build 1607? Let Us Help You Resolve That!
date: 2024-10-26T16:08:26.998Z
updated: 2024-10-27T17:33:02.917Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Cannot Apply Feature Updates for Windows 10 Build 1607? Let Us Help You Resolve That!
excerpt: This Article Describes Cannot Apply Feature Updates for Windows 10 Build 1607? Let Us Help You Resolve That!
thumbnail: https://thmb.techidaily.com/84f8ffb2622461b5b8ae41bcaa2a7a63b43c8ca478ec4a5288c1fa6d62881340.jpg
---

## Cannot Apply Feature Updates for Windows 10 Build 1607? Let Us Help You Resolve That

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

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
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

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398455/3022" target="_top" id="398455">
  <img src="//a.impactradius-go.com/display-ad/3022-398455" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398455/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100537/7443" target="_top" id="2100537">
  <img src="//a.impactradius-go.com/display-ad/7443-2100537" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100537/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112007/7443" target="_top" id="2112007">
  <img src="//a.impactradius-go.com/display-ad/7443-2112007" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112007/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-full-time-careers-meet-video-content-a-harmonious-mix/"><u>[New] 2024 Approved Full-Time Careers Meet Video Content A Harmonious Mix</u></a></li>
<li><a href="https://youtube-web.techidaily.com/nlock-free-youtube-introend-customization/"><u>[New] Unlock Free YouTube Intro/End Customization</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-optimizing-colors-in-films-via-luts/"><u>[Updated] Optimizing Colors in Films via Luts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/1-free-online-video-shrinker-effortless-video-downsizing-tools/"><u>1. Free Online Video Shrinker: Effortless Video Downsizing Tools</u></a></li>
<li><a href="https://win-answers.techidaily.com/banish-game-crashes-in-nba-2k23-on-pc-with-these-7-strategies/"><u>Banish Game Crashes in NBA 2K23 on PC with These 7 Strategies</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-your-course-to-youtube-riches-the-essential-500-threshold/"><u>Chart Your Course to Youtube Riches The Essential 500 Threshold</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-ways-to-address-a-broken-or-stuck-backspace-key/"><u>Effective Ways to Address a Broken or Stuck Backspace Key</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-setup-tip-the-importance-of-having-an-up-to-date-d3d11-graphics-processor-to-run-your-game-engine-smoothly/"><u>Essential Setup Tip: The Importance of Having an Up-to-Date D3D11 Graphics Processor to Run Your Game Engine Smoothly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/high-resource-consumption-of-ntoskrnlexe-solved/"><u>High Resource Consumption of ntoskrnl.exe: Solved</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-realme-gt-3-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Realme GT 3 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-stuck-on-loading-screen-bypass-the-glitches-with-this-updated-fixing-guide-releases/"><u>PUBG Stuck on Loading Screen? Bypass the Glitches with This Updated Fixing Guide Releases</u></a></li>
<li><a href="https://extra-information.techidaily.com/snowy-scores-winter-2022-wonders-unveiled/"><u>Snowy Scores Winter 2022 Wonders Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-apex-legends-simple-fixes-for-the-anti-cheat-issue/"><u>Solving Apex Legends: Simple Fixes for the Anti-Cheat Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-strategies-to-address-and-fix-the-windows-update-issue-error-0x80070652/"><u>Step-by-Step Strategies to Address and Fix the Windows Update Issue (Error 0X80070652)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-dimensions-of-a-rectangular-tank-are-needed-to-calculate-its-volume-volume-length-x-width-x-depth/"><u>The Dimensions of a Rectangular Tank Are Needed to Calculate Its Volume: Volume = Length X Width X Depth.</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-5-strategies-for-boosting-your-productivity-on-facebook/"><u>Top 5 Strategies for Boosting Your Productivity on Facebook</u></a></li>
</ul></div>

