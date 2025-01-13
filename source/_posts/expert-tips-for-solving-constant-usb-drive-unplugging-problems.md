---
title: Expert Tips for Solving Constant USB Drive Unplugging Problems
date: 2025-01-10T17:36:30.180Z
updated: 2025-01-13T16:40:02.061Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-commanding-youtube-realm-through-strategic-creator-studio-utilization/"><u>[New] 2024 Approved Commanding YouTube Realm Through Strategic Creator Studio Utilization</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-your-route-to-revisiting-fbs-recently-viewed-gems/"><u>[New] Your Route to Revisiting Fb’s Recently Viewed Gems</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-boost-communication-merging-skype-and-zoom-functionality/"><u>[Updated] 2024 Approved Boost Communication Merging Skype and Zoom Functionality</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-refine-your-images-quickly-freepaid-lut-options-for-canon/"><u>[Updated] 2024 Approved Refine Your Images Quickly - Free/Paid LUT Options for Canon</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-revamped-tiktok-visuals-the-ultimate-guide-for-background-swapping/"><u>[Updated] 2024 Approved Revamped TikTok Visuals The Ultimate Guide for Background Swapping</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-unleashing-the-full-capabilities-of-macoss-screen-recording-feature/"><u>[Updated] 2024 Approved Unleashing the Full Capabilities of macOS's Screen Recording Feature</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-guide-stop-that-constant-cursor-fix-blink-issue-now/"><u>Easy Guide: Stop That Constant Cursor - Fix Blink Issue Now!</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-does-microsoft-office-vary-across-windows-and-mac-operating-systems/"><u>How Does Microsoft Office Vary Across Windows and Mac Operating Systems?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-increase-system-memory-for-windows-10-solution/"><u>How to Increase System Memory for Windows 10 [Solution]</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-enhancing-soundscapes-mastering-audacitys-crossfade-feature/"><u>In 2024, Enhancing Soundscapes Mastering Audacity's Crossfade Feature</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-navigating-through-the-best-tools-to-monitor-instagram-metrics-effectively/"><u>In 2024, Navigating Through the Best Tools to Monitor Instagram Metrics Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-enabling-hosted-networks-on-windows-11/"><u>Solving the Issue: Enabling Hosted Networks on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/streamlined-support-for-using-file-explorer-in-windows-10-step-by-step-guidance/"><u>Streamlined Support for Using File Explorer in Windows 10 – Step-by-Step Guidance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/touchpad-dilemma-unveil-and-repair-instantly/"><u>Touchpad Dilemma: Unveil & Repair Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-techniques-for-eradicating-flicker-errors-on-your-win-10-computer-display/"><u>Troubleshooting Techniques for Eradicating Flicker Errors on Your Win-10 Computer Display</u></a></li>
</ul></div>

