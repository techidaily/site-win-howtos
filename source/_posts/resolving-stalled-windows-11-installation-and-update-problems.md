---
title: Resolving Stalled Windows 11 Installation and Update Problems
date: 2024-11-21T08:03:33.326Z
updated: 2024-11-28T06:10:06.988Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-boost-visual-impact-selecting-excellent-edges-for-instagram-shots/"><u>[New] In 2024, Boost Visual Impact Selecting Excellent Edges for Instagram Shots</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-turning-off-instagrams-igtv-in-a-nutshell/"><u>[New] In 2024, Turning Off Instagram's IGTV in a Nutshell</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-mastering-youtube-monetization-a-cpm-perspective/"><u>[New] Mastering YouTube Monetization A CPM Perspective</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-disabling-youtube-ads-across-chrome-firefox-android-and-ios-browsers-for-2024/"><u>[Updated] Disabling YouTube Ads Across Chrome, Firefox, Android & iOS Browsers for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ceasing-the-unplanned-boot-troubleshooting-autostart-in-windows-10-systems/"><u>Ceasing the Unplanned Boot: Troubleshooting Autostart in Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-message-deciphered-fixing-the-camera-not-available-code-0xa0aturatecdouble-d-in-windows/"><u>Error Message Deciphered: Fixing the 'Camera Not Available, Code 0xA0aturate(c_double D);' In Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/essential-driver-packs-for-asrock-motherboards-free-firmware-installs-available/"><u>Essential Driver Packs for ASRock Motherboards - Free Firmware Installs Available</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-fixing-significant-bugs-in-call-of-duty-black-ops-4/"><u>Expert Tips for Fixing Significant Bugs in Call of Duty: Black Ops 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-geforce-experience-launch-problem-a-comprehensive-solution/"><u>Fixing the GeForce Experience Launch Problem: A Comprehensive Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-igfxem-driver-errors-and-restore-graphics-functionality/"><u>How to Fix igfxEM Driver Errors and Restore Graphics Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-volume-is-dirty-mistake-error-0x80071ac3-on-your-pc/"><u>How to Resolve 'Volume Is Dirty' Mistake (Error 0X80071AC3) on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-write-data-into-a-0x-memory-space-that-has-been-referenced-by-an-instruction/"><u>How to Successfully Write Data Into a 0X Memory Space That Has Been Referenced by an Instruction</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-analyzing-instagram-de-followings/"><u>In 2024, Analyzing Instagram De-Followings</u></a></li>
<li><a href="https://driver-download.techidaily.com/installing-logitech-sound-drivers-on-your-pc-running-windows-versions-11-7-or-8/"><u>Installing Logitech Sound Drivers on Your PC Running Windows Versions 11, 7, or 8</u></a></li>
<li><a href="https://win-howtos.techidaily.com/silent-streams-no-more-fixing-netflixs-sound-problem-with-simple-tips/"><u>Silent Streams No More - Fixing Netflix's Sound Problem with Simple Tips</u></a></li>
<li><a href="https://technical-tips.techidaily.com/tips-for-retrieving-personal-email-ids-a-step-by-step-approach/"><u>Tips for Retrieving Personal Email IDs: A Step-by-Step Approach</u></a></li>
<li><a href="https://win-ratings.techidaily.com/transforming-success-effortless-tactics-to-change-vlc-format-into-mp4/"><u>Transforming Success: Effortless Tactics to Change VLC Format Into MP4</u></a></li>
</ul></div>

