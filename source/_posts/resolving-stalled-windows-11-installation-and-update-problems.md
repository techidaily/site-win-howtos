---
title: Resolving Stalled Windows 11 Installation and Update Problems
date: 2024-12-23T02:08:12.518Z
updated: 2024-12-28T14:16:16.891Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-decoding-the-revised-youtube-earnings-criteria/"><u>[New] 2024 Approved Decoding the Revised YouTube Earnings Criteria</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-enhancing-call-clarity-silencing-distractions/"><u>[New] Enhancing Call Clarity Silencing Distractions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effortless-history-handling-top-4-extensions-for-gpt-3/"><u>Effortless History Handling - Top 4 Extensions for GPT-3</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/hp-printer-driver-downloads-get-them-now/"><u>HP Printer Driver Downloads - Get Them Now!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-oppo-a78-5g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Oppo A78 5G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/offline-viewing-simple-steps-to-downloading-your-favorite-films-series-tunes/"><u>Offline Viewing: Simple Steps to Downloading Your Favorite Films, Series, Tunes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pc-windows-11/"><u>PC画面動画キャプチャツールをお勧めする - Windows 11で使う方法</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-guide-how-to-transform-avchd-videos-into-mp4-with-simple-tools/"><u>Quick Guide: How to Transform AVCHD Videos Into MP4 with Simple Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rapid-and-simple-mts-file-consolidation-made-easy-discover-leading-merger-solutions-today/"><u>Rapid & Simple MTS File Consolidation Made Easy: Discover Leading Merger Solutions Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-computers-clock-display-top-5-tools-for-animated-windows-screensaver-creation/"><u>Revamp Your Computer's Clock Display: Top 5 Tools for Animated Windows Screensaver Creation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rotate-your-videos-like-a-pro-with-these-easy-tips-for-adobe-premiere-pro-users/"><u>Rotate Your Videos Like a Pro with These Easy Tips for Adobe Premiere Pro Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-steps-converting-your-dvds-into-mkv-format-with-windows-11-and-10/"><u>Simple Steps: Converting Your DVDs Into MKV Format with Windows 11 & 10</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721452345211-speeding-up-a-slow-iphone-here-are-6-reasons-and-fixes-you-cant-miss/"><u>Speeding Up a Slow iPhone? Here Are 6 Reasons & Fixes You Can't Miss</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-converting-mp4-files-to-3gp-format-online-and-offline/"><u>Step-by-Step Guide: Converting MP4 Files to 3GP Format Online and Offline</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-mastering-video-editing-techniques-in-windows-11/"><u>Step-by-Step Guide: Mastering Video Editing Techniques in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-enable-offline-accessibility-on-your-youtube-content/"><u>Step-by-Step Tutorial: Enable Offline Accessibility on Your YouTube Content</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/trailblaze-your-way-to-success-insights-on-youtube-metrics-with-social-blade-for-2024/"><u>Trailblaze Your Way to Success Insights on YouTube Metrics with Social Blade for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/vimeo-earnings-unlocked-strategies-for-content-creators/"><u>Vimeo Earnings Unlocked Strategies for Content Creators</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/wie-man-emails-sicher-exportiert-masterclass-fur-den-transfer-von-mails-vom-postfach-auf-macos/"><u>Wie Man Emails Sicher Exportiert: Masterclass Für Den Transfer Von Mails Vom Postfach Auf macOS</u></a></li>
</ul></div>

