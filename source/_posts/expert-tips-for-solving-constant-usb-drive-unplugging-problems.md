---
title: Expert Tips for Solving Constant USB Drive Unplugging Problems
date: 2024-12-06T17:30:44.706Z
updated: 2024-12-13T17:27:40.966Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://video-capture.techidaily.com/new-terrarias-richest-realms-5-best-gold-hunt-spots-for-2024/"><u>[New] Terraria's Richest Realms 5 Best Gold Hunt Spots for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-sparkle-with-screenshots-vlogging-for-value-creation/"><u>[Updated] In 2024, Sparkle with Screenshots Vlogging for Value Creation</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/2024-approved-ever-changing-era-of-ai-video-translation-a-reality-to-be-fulfilled/"><u>2024 Approved Ever-Changing Era of AI Video Translation A Reality to Be Fulfilled</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/climate-denial-and-the-role-of-media-bias-explored/"><u>Climate Denial and the Role of Media Bias Explored</u></a></li>
<li><a href="https://fox-helps.techidaily.com/cutting-edge-radio-theatre-scripting-for-2024/"><u>Cutting-Edge Radio Theatre Scripting for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-solution-to-overcome-problem-0x800f0831-using-windows-update-feature/"><u>Effortless Solution to Overcome Problem 0X800F0831 Using Windows Update Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-your-computers-startup-eliminate-slow-boot-issues-on-windows-7/"><u>Enhance Your Computer's Startup: Eliminate Slow Boot Issues on Windows 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-your-wow-experience-by-eliminating-latency-problems/"><u>Enhance Your WoW Experience by Eliminating Latency Problems</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-top-5-best-video-editing-apps-for-iphone/"><u>In 2024, Top 5 Best Video Editing Apps for iPhone</u></a></li>
<li><a href="https://os-tips.techidaily.com/iphone-unlock-mastery-deactivating-apples-icloud-lock-without-hitches/"><u>IPhone Unlock Mastery: Deactivating Apple's iCloud Lock Without Hitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-fixing-critical-process-died-with-error-code-0xc00000e9-on-windows/"><u>Master Fixing Critical Process Died with Error Code 0xC00000E9 on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reactivate-the-stalled-windows-update-feature-step-by-step-solutions/"><u>Reactivate the Stalled Windows Update Feature – Step-by-Step Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-steps-for-unsuccessful-feature-updates-in-windows-11-version-1803/"><u>Resolved: Troubleshooting Steps for Unsuccessful Feature Updates in Windows 11 (Version 1803)</u></a></li>
<li><a href="https://win11.techidaily.com/simple-sign-up-process-mastering-user-registration/"><u>Simple Sign-Up Process - Mastering User Registration</u></a></li>
<li><a href="https://extra-support.techidaily.com/simplified-transfer-tactics-from-iphone-to-computer-for-2024/"><u>Simplified Transfer Tactics From iPhone to Computer for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-required-module-missing-error-a-step-by-step-guide/"><u>Solving the 'Required Module Missing' Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-stalled-diagnostics-policy-service-expert-advice/"><u>Troubleshooting a Stalled Diagnostics Policy Service – Expert Advice</u></a></li>
</ul></div>

