---
title: Cannot Apply Feature Updates for Windows 10 Build 1607? Let Us Help You Resolve That!
date: 2025-02-05T08:32:39.388Z
updated: 2025-02-07T01:09:30.639Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-tips.techidaily.com/n-2024-the-art-of-crafting-youtube-content-expert-tips-with-imovie-integration/"><u>[New] In 2024, The Art of Crafting YouTube Content Expert Tips with iMovie Integration</u></a></li>
<li><a href="https://fox-info.techidaily.com/elite-list-8-amazing-3d-websites-and-glittering-text-for-2024/"><u>Elite List 8 Amazing 3D Websites & Glittering Text for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207637089-endless-cursor-heres-how-you-can-put-a-stop-to-it/"><u>Endless Cursor? Here's How You Can Put a Stop to It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-87-fixed-overcoming-the-parameter-is-incorrect-issue-in-loadlibrary/"><u>Error 87 Fixed: Overcoming 'The Parameter Is Incorrect' Issue in LoadLibrary</u></a></li>
<li><a href="https://solve-latest.techidaily.com/guida-facile-come-masterare-il-processo-di-duplicazione-dei-dvd-su-un-macbook-pro-o-air/"><u>Guida Facile: Come Masterare Il Processo Di Duplicazione Dei DVD Su Un MacBook Pro O Air</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-maximizing-click-through-rates-with-youtube-images/"><u>In 2024, Maximizing Click-Through Rates with Youtube Images</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-top-15-cine-luts-for-gopro-action-cam/"><u>In 2024, Top 15 Cine LUTs for Gopro Action Cam</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-absence-of-sound-devices-error-on-a-windows-11-operating-system/"><u>Overcoming the Absence of Sound Devices Error on a Windows 11 Operating System</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-and-simple-guide-reducing-the-size-of-your-quicktime-movies/"><u>Quick and Simple Guide: Reducing the Size of Your QuickTime Movies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-the-missing-startup-file-on-your-pc/"><u>Troubleshooting and Fixing the Missing Startup File on Your PC</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unbeatable-bargain-alert-up-to-230-off-on-the-ultimate-156-hp-laptop-with-touch-display-insider-info-from-zdnet/"><u>Unbeatable Bargain Alert! Up to $230 Off on the Ultimate 15.6 HP Laptop with Touch Display - Insider Info From ZDNET.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11s-proxy-settings-path/"><u>Unveiling Windows 11'S Proxy Settings Path</u></a></li>
</ul></div>

