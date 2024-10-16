---
title: "Getting Past Windows 11 Freezing Point: Update Solutions Unveiled"
date: 2024-10-14T18:15:43.693Z
updated: 2024-10-15T16:52:46.230Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Getting Past Windows 11 Freezing Point: Update Solutions Unveiled"
excerpt: "This Article Describes Getting Past Windows 11 Freezing Point: Update Solutions Unveiled"
thumbnail: https://thmb.techidaily.com/d0ab1cb7b8b22999ef087a383ed3db769492e1f7dd341f7046ddf8ecb2ad394e.png
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
<a href="https://appsumo.8odi.net/c/5597632/2100538/7443" target="_top" id="2100538">
  <img src="//a.impactradius-go.com/display-ad/7443-2100538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868571/19272" target="_top" id="1868571">
  <img src="//a.impactradius-go.com/display-ad/19272-1868571" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868571/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2144273/7443" target="_top" id="2144273">
  <img src="//a.impactradius-go.com/display-ad/7443-2144273" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144273/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

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
<li><a href="https://instagram-video-files.techidaily.com/new-building-brand-buzz-the-power-of-instagram-story-quizzes/"><u>[New] Building Brand Buzz The Power of Instagram Story Quizzes</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-mastering-webinar-recording-techniques/"><u>[Updated] Mastering Webinar Recording Techniques</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/capture-memories-in-teams-snap-camera-guide/"><u>Capture Memories in Teams Snap Camera Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comment-transformer-vos-fichiers-mp2-en-videos-avi-sur-internet-gratuitement-solution-de-movavi/"><u>Comment Transformer Vos Fichiers Mp2 en Vidéos Avi Sur Internet Gratuitement - Solution De Movavi</u></a></li>
<li><a href="https://solve-news.techidaily.com/cookiebot-driven-success-boosting-online-engagement-through-smart-data-tracking/"><u>Cookiebot-Driven Success: Boosting Online Engagement Through Smart Data Tracking</u></a></li>
<li><a href="https://win-howtos.techidaily.com/discover-professional-video-production-with-ben-jacklin-at-movavi/"><u>Discover Professional Video Production with Ben Jacklin at Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/edit-your-videos-on-an-iphone-swiftly-with-these-6-simple-steps-explore-movavi-clips/"><u>Edit Your Videos on an iPhone Swiftly with These 6 Simple Steps - Explore Movavi Clips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/free-online-converter-change-avif-format-arw-to-png-images-with-ease/"><u>Free Online Converter: Change AVIF Format (ARW) to PNG Images with Ease</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-s17-pro-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Vivo S17 Pro Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Vivo Y77t? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/movate-a-la-era-digital-con-conversion-de-archivos-alaw-libre-y-descarga-gratuita-de-movavi/"><u>Móvate a La Era Digital Con Conversión De Archivos Alaw Libre Y Descarga Gratuita De Movavi</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-quick-guide-to-correcting-6-common-chatgpt-faults/"><u>The Quick Guide to Correcting 6 Common ChatGPT Faults</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/top-trending-snapchat-augmentations-for-your-photos-for-2024/"><u>Top Trending Snapchat Augmentations for Your Photos for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trasforma-i-tuoi-gif-in-file-swf-free-online-usando-leditor-di-movavi/"><u>Trasforma I Tuoi GIF in File SWF Free Online Usando L'editor Di Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trasforma-i-tuoi-libri-audiolibro-con-ease-ottieni-una-conversione-gratuita-da-m4b-a-m4a-usando-il-metodo-online-di-movavi/"><u>Trasforma I Tuoi Libri Audiolibro Con Ease: Ottieni Una Conversione Gratuita Da M4B a M4A Usando Il Metodo Online Di Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharging-yuzus-performance-on-pcs/"><u>Turbocharging Yuzu's Performance on PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/online-flv-webm-movavi/"><u>우아한 방식으로 Online FLV를 WebM로 자유성 전환: Movavi의 통합</u></a></li>
</ul></div>

