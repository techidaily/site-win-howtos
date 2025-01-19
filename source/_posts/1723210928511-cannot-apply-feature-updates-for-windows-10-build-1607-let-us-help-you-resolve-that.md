---
title: Cannot Apply Feature Updates for Windows 10 Build 1607? Let Us Help You Resolve That!
date: 2025-01-12T17:58:50.449Z
updated: 2025-01-19T16:02:50.483Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-stream.techidaily.com/2024-approved-increase-your-channels-reach-with-these-2-tricks/"><u>2024 Approved Increase Your Channel's Reach with These 2 Tricks</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-redefining-the-silver-screen-virtual-reality-cinema/"><u>2024 Approved Redefining the Silver Screen Virtual Reality Cinema</u></a></li>
<li><a href="https://games-able.techidaily.com/comparison-of-steam-deck-options/"><u>Comparison of Steam Deck Options</u></a></li>
<li><a href="https://buynow-info.techidaily.com/elite-list-of-2024s-high-performance-pc-audio-cards-you-cant-miss/"><u>Elite List of 2024'S High-Performance PC Audio Cards You Can't Miss</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-and-guide-resolving-non-responsive-issues-in-google-chrome/"><u>Fix & Guide: Resolving Non-Responsive Issues in Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-lost-bluetooth-support-in-windows-11-steps-for-rapid-resolution/"><u>Fix Lost Bluetooth Support in Windows 11: Steps for Rapid Resolution</u></a></li>
<li><a href="https://tech-haven.techidaily.com/generative-ai-and-next-gen-chatbots-unlocking-future-possibilities-in-human-ai-interaction/"><u>Generative AI & Next-Gen Chatbots: Unlocking Future Possibilities in Human-AI Interaction</u></a></li>
<li><a href="https://win-community.techidaily.com/how-to-troubleshoot-a-scanner-thats-giving-you-wrong-outputs-tips-from-yl-computing/"><u>How To Troubleshoot a Scanner That's Giving You Wrong Outputs - Tips From YL Computing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mestizo/"><u>Mestizo:</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcome-ios-16s-lock-screen-depth-effect-malfunction-with-these-7-tips/"><u>Overcome iOS 16'S Lock Screen Depth Effect Malfunction with These 7 Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-11-v1803-update-issues-a-step-by-step-guide/"><u>Overcoming Windows 11 v1803 Update Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/savor-these-delightful-kitchen-escapes-a-culinary-enthusiasts-guide-to-the-finest-cooking-series-on-netflix/"><u>Savor These Delightful Kitchen Escapes: A Culinary Enthusiast's Guide to the Finest Cooking Series on Netflix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solutions-how-to-resolve-your-computer-stuck-during-windows-setup/"><u>Solutions: How to Resolve Your Computer Stuck During Windows Setup</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/your-complete-guide-to-using-telegram-web-interface/"><u>Your Complete Guide to Using Telegram Web Interface</u></a></li>
</ul></div>

