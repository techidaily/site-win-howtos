---
title: "Solving the Problem: Why Your Steam Updates Won't Download"
date: 2024-09-27T17:46:20.000Z
updated: 2024-09-29T04:54:03.873Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solving the Problem: Why Your Steam Updates Won't Download"
excerpt: "This Article Describes Solving the Problem: Why Your Steam Updates Won't Download"
thumbnail: https://thmb.techidaily.com/7677f4cd9df16c6a66672a56bd970deac980e4b074d81c3008e2f891a827245d.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2049382/7443" target="_top" id="2049382">
  <img src="//a.impactradius-go.com/display-ad/7443-2049382" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049382/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134503/19576" target="_top" id="2134503">
  <img src="//a.impactradius-go.com/display-ad/19576-2134503" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134503/19576" style="position:absolute;visibility:hidden;" border="0" />
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

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148771/18498" target="_top" id="2148771">
  <img src="//a.impactradius-go.com/display-ad/18498-2148771" border="0" alt="https://techidaily.com" width="350" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148771/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/coring-big-on-youtube-how-much-do-ad-revenues-add-up-for-2024/"><u>[New] Scoring Big on YouTube How Much Do Ad Revenues Add Up for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-content-layout-on-social-networks-facebooks-perspective/"><u>[Updated] 2024 Approved Content Layout on Social Networks Facebook’s Perspective</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-an-introductory-overview-using-ez-grabber-software/"><u>[Updated] In 2024, An Introductory Overview Using EZ Grabber Software</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-twitters-visuals-on-the-social-media-giant-fb-for-2024/"><u>[Updated] Twitters' Visuals on the Social Media Giant FB for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-7-tips-to-create-teaching-videos/"><u>2024 Approved 7 Tips to Create Teaching Videos</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-nubia-red-magic-9-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/in-depth-walkthrough-correcting-errors-in-user-profile-logon-services/"><u>In-Depth Walkthrough: Correcting Errors in User Profile Logon Services</u></a></li>
<li><a href="https://win-howtos.techidaily.com/installation-issues-why-the-windows-10-version-1-update-failed-and-how-to-overcome-them/"><u>Installation Issues: Why the Windows 10 Version 1 Update Failed and How to Overcome Them</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-solving-your-pcs-persistent-snooze-problem/"><u>Quick Fixes: Solving Your PC's Persistent Snooze Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reinstating-sound-capabilities-on-your-windows-7-pc-restored/"><u>Reinstating Sound Capabilities on Your Windows 7 PC ([Restored])</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repairing-your-lenovos-fn-key-swift-solutions/"><u>Repairing Your Lenovo's FN Key: Swift Solutions</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/erfect-proposal-to-perfection-8-best-weddings-online-for-2024/"><u>The Perfect Proposal to Perfection 8 Best Weddings Online for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-to-resolve-error-8007000e-in-windows-update-without-delay/"><u>Troubleshooting Tips to Resolve Error 8007000E in Windows Update Without Delay</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-making-your-aoc-screen-function-again-in-windows-10-environment/"><u>Troubleshooting Tips: Making Your AOC Screen Function Again in Windows 10 Environment</u></a></li>
</ul></div>

