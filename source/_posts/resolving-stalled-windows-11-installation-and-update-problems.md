---
title: Resolving Stalled Windows 11 Installation and Update Problems
date: 2024-12-01T18:41:55.964Z
updated: 2024-12-07T17:49:52.558Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-how-to-swiftly-excise-your-youtube-comment-spam/"><u>[New] 2024 Approved How to Swiftly Excise Your Youtube Comment Spam</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-demystifying-the-instagram-selfie-process/"><u>[Updated] 2024 Approved Demystifying the Instagram Selfie Process</u></a></li>
<li><a href="https://win-howtos.techidaily.com/flacalac-3/"><u>人気の自由版 FLAC/ALAC 変換ソフトウェア 上位3つ</u></a></li>
<li><a href="https://win-cloud.techidaily.com/aomei-backupper-erfolgreiche-datensicherung-mit-integrierten-unterstutzungsdateisystemen/"><u>AOMEI Backupper: Erfolgreiche Datensicherung Mit Integrierten Unterstützungsdateisystemen</u></a></li>
<li><a href="https://discover-fantastic.techidaily.com/boosting-your-dellhplenovos-recovery-drive-a-step-by-step-tutorial/"><u>Boosting Your Dell/HP/Lenovo's Recovery Drive - A Step-by-Step Tutorial</u></a></li>
<li><a href="https://facebook.techidaily.com/cyber-ethics-in-limitations-justifiable-ban-on-trump-but-not-everlasting/"><u>Cyber Ethics in Limitations: Justifiable Ban on Trump, But Not Everlasting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-guide-to-installing-inshot-on-your-windows-computer/"><u>Easy Guide to Installing InShot on Your Windows Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-converting-ts-files-to-mp4-at-no-cost-11-methods/"><u>Easy Steps: Converting TS Files to MP4 at No Cost (11 Methods)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-transforming-ts-files-into-mp4-format-with-ffmpeg/"><u>Easy Steps: Transforming TS Files Into MP4 Format with FFmpeg</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-solving-recurring-error-messages-in-4k-video-downloader-software/"><u>Expert Tips for Solving Recurring Error Messages in 4K Video Downloader Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/flv-mp42/"><u>FLV形式への変換: MP4を手動で変換する2つの効果的な方法</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-turn-on-video-crop-functionality-in-lightworks-a-detailed-walkthrough/"><u>How To Turn On Video Crop Functionality In Lightworks - A Detailed Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/imovie-mp4-formats-not-compatible-unveil-our-step-by-step-solution-for-seamless-importing/"><u>IMovie MP4 Formats Not Compatible? Unveil Our Step-by-Step Solution for Seamless Importing!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/improving-screen-recording-clarity-tips-and-tricks-for-enhanced-video-quality/"><u>Improving Screen Recording Clarity: Tips & Tricks for Enhanced Video Quality</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-dominate-any-space-the-ultimate-metaverse-device-guide/"><u>In 2024, Dominate Any Space The Ultimate Metaverse Device Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-nubia-z50-ultra-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Nubia Z50 Ultra Android SIM Unlock APK</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/initial-thoughts-on-the-samsung-galaxy-s24-ultra-a-comprehensive-review/"><u>Initial Thoughts on the Samsung Galaxy S24 Ultra: A Comprehensive Review</u></a></li>
<li><a href="https://win-reviews.techidaily.com/windows-11-outlook-backup-made-easy/"><u>Windows 11 Outlook Backup Made Easy</u></a></li>
</ul></div>

