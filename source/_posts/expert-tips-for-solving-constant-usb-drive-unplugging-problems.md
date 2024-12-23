---
title: Expert Tips for Solving Constant USB Drive Unplugging Problems
date: 2024-12-16T16:29:00.542Z
updated: 2024-12-23T01:01:52.231Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-streaming-showdown-the-duo/"><u>[New] In 2024, Streaming Showdown The Duo</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-melodic-integration-for-engaging-insta-posts/"><u>[New] Melodic Integration for Engaging Insta Posts</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-skype-call-recording-for-windows-os-x-users/"><u>[New] Skype Call Recording for Windows, OS X Users</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-essential-guide-to-capturing-your-screens-stepwise-approach/"><u>[Updated] 2024 Approved Essential Guide to Capturing Your Screens - Stepwise Approach</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-decoding-youtubes-intricate-view-count-mechanics/"><u>[Updated] In 2024, Decoding YouTube's Intricate View Count Mechanics</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-elevate-your-hiring-game-with-the-best-vids-in-town/"><u>[Updated] In 2024, Elevate Your Hiring Game with the Best Vids in Town</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-perfect-pages-with-premieres-fade-techniques/"><u>2024 Approved Perfect Pages with Premiere's Fade Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-87-fixing-the-parameter-is-incorrect-in-loadlibrary-issues/"><u>Error Code 87: Fixing 'The Parameter Is Incorrect' In LoadLibrary Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206059037-fast-track-to-fixing-error-code-0x887a0006-a-speedier-solution-guide/"><u>Fast Track to Fixing Error Code 0X887A0006 – A Speedier Solution Guide!</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-unlock-seamless-edits-audio-video-syncing-in-fcpx-2024-explaine/"><u>New Unlock Seamless Edits Audio-Video Syncing in FCPX 2024 Explaine</u></a></li>
<li><a href="https://fox-helps.techidaily.com/perfecting-profile-collaboration-add-linktree-to-your-tiktok-bio/"><u>Perfecting Profile Collaboration Add Linktree to Your TikTok Bio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-the-rpc-server-accessibility-error-in-windows/"><u>Step-by-Step Guide: Correcting the RPC Server Accessibility Error in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-with-your-touchscreen-in-windows-10-discover-how-to-fix-it-using-5-different-approaches/"><u>Trouble with Your Touchscreen in Windows 10? Discover How to Fix It Using 5 Different Approaches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202609749-trouble-with-your-windows-11-taskbar-easy-fixes-to-restore-functionality-now/"><u>Trouble with Your Windows 11 Taskbar? Easy Fixes to Restore Functionality Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-right-click-issues-on-windows-11-a-step-by-step-guide/"><u>Troubleshooting Right-Click Issues on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-fix-destiny-2-wont-initialize-issue/"><u>Troubleshooting: How to Fix 'Destiny 2 Won't Initialize' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-11-volume-troubleshooting-guide-get-your-sounds-back-today/"><u>Win 11 Volume Troubleshooting Guide - Get Your Sounds Back Today!</u></a></li>
</ul></div>

