---
title: Cannot Apply Feature Updates for Windows 10 Build 1607? Let Us Help You Resolve That!
date: 2025-01-11T16:26:27.477Z
updated: 2025-01-13T16:20:45.906Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-crafting-team-videos-to-foster-viewership-and-following/"><u>[New] 2024 Approved Crafting Team Videos to Foster Viewership and Following</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-learn-illustration-magic-a-guide-to-adobe-motion-blur/"><u>[New] 2024 Approved Learn Illustration Magic A Guide to Adobe Motion Blur</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-how-to-safeguard-your-feed-remove-followers/"><u>[New] In 2024, How to Safeguard Your Feed Remove Followers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-identifying-your-individual-song-collection-on-youtube/"><u>[New] In 2024, Identifying Your Individual Song Collection on YouTube</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-chuckle-factory-designing-7-video-ideas-for-humorists/"><u>[Updated] 2024 Approved Chuckle Factory Designing 7 Video Ideas for Humorists</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-the-ultimate-guide-to-top-online-tools-for-perfecting-your-video-subtitles-for-2024/"><u>[Updated] The Ultimate Guide to Top Online Tools for Perfecting Your Video Subtitles for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-mastery-in-making-advanced-tiktok-editing-techniques/"><u>2024 Approved Mastery in Making Advanced TikTok Editing Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/discovering-if-your-windows-device-is-under-group-policy-management-by-the-organization/"><u>Discovering If Your Windows Device Is Under Group Policy Management by the Organization</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-stop-crackling-sounds-from-speakers-in-windows-operating-systems/"><u>How to Stop Crackling Sounds From Speakers in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-reboot-process-solutions-to-common-windows-11-startup-problems/"><u>Mastering the Reboot Process: Solutions to Common Windows 11 Startup Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-missing-dlls-and-classes-for-smooth-windows-11-operation/"><u>Resolving Missing DLLs and Classes for Smooth Windows 11 Operation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-excessive-disk-space-consumed-by-microsoft-compatibility-telemetry-on-windows-10/"><u>Resolving the Issue: Excessive Disk Space Consumed by Microsoft Compatibility Telemetry on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/say-goodbye-to-skyrim-infinite-loading-a-complete-troubleshooting-walkthrough/"><u>Say Goodbye to Skyrim Infinite Loading: A Complete Troubleshooting Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-getting-your-xbox-one-controller-to-work-when-wont-sync/"><u>Step-by-Step Guide: Getting Your Xbox One Controller to Work When Won't Sync</u></a></li>
<li><a href="https://win-howtos.techidaily.com/streamlined-windows-drivers-for-better-cpu-consumption-fixed/"><u>Streamlined Windows Drivers for Better CPU Consumption (Fixed)</u></a></li>
<li><a href="https://fox-that.techidaily.com/the-secret-to-iphones-smart-display-10-reasons-for-auto-brightness-adjustments/"><u>The Secret to iPhone's Smart Display: 10 Reasons for Auto-Brightness Adjustments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-solutions-for-windows-10-crimson-halt-problem/"><u>Troubleshooting and Solutions for Windows 10 Crimson Halt Problem</u></a></li>
<li><a href="https://facebook.techidaily.com/unveiling-deceptive-design-poor-privacy-decisions/"><u>Unveiling Deceptive Design: Poor Privacy Decisions</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-say-goodbye-to-windows-10-photos-top-8-alternative-image-viewers/"><u>Updated In 2024, Say Goodbye to Windows 10 Photos Top 8 Alternative Image Viewers</u></a></li>
</ul></div>

