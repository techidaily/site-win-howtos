---
title: Resolving Stalled Windows 11 Installation and Update Problems
date: 2024-11-06T06:47:51.387Z
updated: 2024-11-07T20:20:07.276Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Stalled Windows 11 Installation and Update Problems
excerpt: This Article Describes Resolving Stalled Windows 11 Installation and Update Problems
thumbnail: https://thmb.techidaily.com/72bac3551a829f100e80929327a859a230ef81a06fa60256119f57f4b98caf7a.jpg
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

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997662/19272" target="_top" id="1997662">
  <img src="//a.impactradius-go.com/display-ad/19272-1997662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997662/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144274/7443" target="_top" id="2144274">
  <img src="//a.impactradius-go.com/display-ad/7443-2144274" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144274/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896532/19272" target="_top" id="1896532">
  <img src="//a.impactradius-go.com/display-ad/19272-1896532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896532/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-alleviate-problem-buffering-tweets-in-chromebook/"><u>[New] 2024 Approved Alleviate Problem Buffering Tweets in Chromebook</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-instant-subtitling-hacks-for-all-your-facebook-videos-for-2024/"><u>[New] Instant Subtitling Hacks for All Your Facebook Videos for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-ultimate-guide-to-cost-effective-media-providers-online/"><u>[New] The Ultimate Guide to Cost-Effective Media Providers Online</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-xsplit-source-centralized-game-downloads-and-insights/"><u>2024 Approved XSplit Source Centralized Game Downloads & Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-address-no-device-found-error-on-windows-7-guide/"><u>Easy Steps to Address 'No Device Found' Error on Windows 7 [Guide]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-guide-restore-your-steam-file-access-rights-successfully/"><u>Fix Guide: Restore Your Steam File Access Rights Successfully</u></a></li>
<li><a href="https://tech-hub.techidaily.com/google-elevates-ai-with-the-release-of-its-advanced-palm-2-large-language-model/"><u>Google Elevates AI with the Release of Its Advanced PaLM 2 Large Language Model</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-fix-windows-update-error-0x8024402c-comprehensive-guide-solution-included/"><u>How to Troubleshoot and Fix Windows Update Error 0X8024402c - Comprehensive Guide [Solution Included]</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-view-comments-on-youtube-for-2024/"><u>How to View Comments on YouTube for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On OnePlus Nord CE 3 5G? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-the-iron-throne-of-sound-best-websites-for-got-ringtone-downloads/"><u>In 2024, The Iron Throne of Sound Best Websites for GoT Ringtone Downloads</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-xiaomi-redmi-note-12r-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Xiaomi Redmi Note 12R? Fixed | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-the-process-of-getting-trustee-approval-from-trustedinstaller-to-change-files/"><u>Navigating the Process of Getting Trustee Approval From TrustedInstaller to Change Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-inaccessible-servers-in-destiny-2-proven-fixes-for-gamers/"><u>Overcoming Inaccessible Servers in Destiny 2 – Proven Fixes for Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-correct-audio-device-not-found-on-your-pc-running-windows/"><u>Steps to Correct 'Audio Device Not Found' On Your PC Running Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-solutions-resolving-xbox-one-and-xbox-live-connection-problems/"><u>Successful Solutions: Resolving Xbox One and Xbox Live Connection Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-solving-your-bluetooth-connection-woes-in-windows-11/"><u>Ultimate Guide: Solving Your Bluetooth Connection Woes in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wow-unveiled-enhanced-depth-and-immersion-with-3d-rendering/"><u>WoW Unveiled: Enhanced Depth and Immersion with 3D Rendering</u></a></li>
</ul></div>

