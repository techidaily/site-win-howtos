---
title: Resolving Stalled Windows 11 Installation and Update Problems
date: 2024-10-14T17:19:26.050Z
updated: 2024-10-21T21:24:09.778Z
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
<a href="https://appsumo.8odi.net/c/5597632/2043617/7443" target="_top" id="2043617">
  <img src="//a.impactradius-go.com/display-ad/7443-2043617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043617/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-customizing-facebook-memories-with-look-back-edits/"><u>[Updated] 2024 Approved Customizing Facebook Memories with Look Back Edits</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-transform-your-instagram-vids-with-advanced-editing-skills/"><u>[Updated] 2024 Approved Transform Your Instagram Vids with Advanced Editing Skills</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-best-study-partners-in-history-top-10-youtubers-and-channels/"><u>[Updated] Best Study Partners in History Top 10 Youtubers & Channels</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-calm-to-captivating-techniques-for-motion-blur-mastery/"><u>[Updated] From Calm to Captivating Techniques for Motion Blur Mastery</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-top-10-sites-for-vector-graphics-collection/"><u>2024 Approved Top 10 Sites for Vector Graphics Collection</u></a></li>
<li><a href="https://technical-tips.techidaily.com/android-sms-silence-overcoming-communication-glitches-and-getting-notified-again/"><u>Android SMS Silence: Overcoming Communication Glitches and Getting Notified Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210209964-fixing-windows-installation-failed-fast-solutions/"><u>Fixing 'Windows Installation Failed' – Fast Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-overcome-signal-loss-in-logitechs-g93-groove-headset/"><u>Guide to Overcome Signal Loss in Logitech's G93 Groove Headset</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-handle-the-error-code-0x80070643-during-windows-updatesinstallations/"><u>How to Correctly Handle the Error Code 0X80070643 During Windows Updates/Installations</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-poco-f5-pro-5g-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Poco F5 Pro 5G to PC? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-open-your-iphone-12-pro-max-without-a-home-button-by-drfone-ios/"><u>In 2024, How To Open Your iPhone 12 Pro Max Without a Home Button</u></a></li>
<li><a href="https://win-howtos.techidaily.com/proper-techniques-for-addressing-msvcp140dll-lack/"><u>Proper Techniques for Addressing MSVCP140.dll Lack</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-fixing-total-war-rome-remastered-game-crashes/"><u>Ultimate Guide: Fixing Total War: Rome Remastered Game Crashes</u></a></li>
<li><a href="https://change-location.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Vivo Y55s 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-10-audio-issue-overcome-how-to-guide/"><u>Win 10 Audio Issue Overcome - How To Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-blue-screen-blues-heres-how-to-end-the-loop-of-unexpected-reboots/"><u>Windows 10 Blue Screen Blues? Here's How to End the Loop of Unexpected Reboots!</u></a></li>
</ul></div>

