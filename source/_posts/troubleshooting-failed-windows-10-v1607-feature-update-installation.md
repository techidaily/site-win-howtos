---
title: "Troubleshooting: Failed Windows 10 v1607 Feature Update Installation"
date: 2024-08-19T07:35:29.513Z
updated: 2024-08-20T07:35:29.513Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: Failed Windows 10 v1607 Feature Update Installation"
excerpt: "This Article Describes Troubleshooting: Failed Windows 10 v1607 Feature Update Installation"
thumbnail: https://thmb.techidaily.com/d91c4abed318157a8b08fbc6c0ecb400619fc39e3e859b7ef1ec6d0563fa86aa.jpg
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
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

## Method 3: Run the DISM utility

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
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
<li><a href="https://win-howtos.techidaily.com/fixed-bluetooth-keyboard-not-connecting-to-pc/"><u>[FIXED] Bluetooth Keyboard Not Connecting to PC</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-horizon-capture-setup-vr/"><u>[New] Horizon Capture Setup VR</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-flipping-photo-lightness-for-an-alternate-look/"><u>[New] In 2024, Flipping Photo Lightness for an Alternate Look</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovative-shooting-with-drones-in-media/"><u>[New] Innovative Shooting with Drones in Media</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-transform-how-you-talk-best-mobile-apps-to-alter-vocal-quality/"><u>[New] Transform How You Talk  Best Mobile Apps to Alter Vocal Quality</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-building-a-broad-spectrum-audience-with-multichannel-strategy-for-2024/"><u>[Updated] Building a Broad-Spectrum Audience with Multichannel Strategy for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-crafting-a-digital-identity-with-inspiring-instagram-captions/"><u>[Updated] In 2024, Crafting a Digital Identity with Inspiring Instagram Captions</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-elite-10-audio-amplifiers-desktops-to-smartphones/"><u>[Updated] In 2024, Elite 10 Audio Amplifiers  Desktops to Smartphones</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-exploring-bandicam-ultimate-guide-to-screen-capture/"><u>[Updated] In 2024, Exploring Bandicam  Ultimate Guide to Screen Capture</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-mvps-of-frugal-filmmaking-tech/"><u>[Updated] The MVPs of Frugal Filmmaking Tech</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-ultimate-guide-to-group-photo-and-video-uploads-in-instagram/"><u>[Updated] The Ultimate Guide to Group Photo and Video Uploads in Instagram</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-iphone-close-up-tips-for-astounding-photos/"><u>2024 Approved  Innovative iPhone Close-Up Tips for Astounding Photos</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-realme-c53-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Realme C53 | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/audiophiles-guide-to-choosing-between-google-nest-audio-and-nest-mini/"><u>Audiophile's Guide to Choosing Between Google Nest Audio and Nest Mini</u></a></li>
<li><a href="https://change-location.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-struggles-top-tricks-for-seamless-pairing-with-windows-11-update-insights/"><u>Bluetooth Struggles? Top Tricks for Seamless Pairing with Windows 11 - Update Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/browser-security-alert-decoded-how-to-deal-with-firefox-secerrorunknownissuer/"><u>Browser Security Alert Decoded - How to Deal with FireFox SEC_ERROR_UNKNOWN_ISSUER</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/capture-without-capsule-the-no-limit-story-saving-app/"><u>Capture Without Capsule  The No-Limit Story Saving App</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-guide-to-overcome-installation-setbacks-solving-error-1603/"><u>Complete Guide to Overcome Installation Setbacks: Solving Error 1603</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-to-follow-instructions-turning-on-bluetooth-for-your-windows-7-operating-system/"><u>Easy-to-Follow Instructions: Turning On Bluetooth for Your Windows 7 Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fixes-for-when-your-lenovo-fingerprint-recognition-stops-working/"><u>Effortless Fixes for When Your Lenovo Fingerprint Recognition Stops Working</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209717563-error-free-updates-ahead-conquer-windows-update-glitch-0x80070002-with-ease/"><u>Error-Free Updates Ahead! Conquer Windows Update Glitch 0X80070002 With Ease!</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/essential-tools-for-every-mac-user-free-screen-recorder-guide-for-2024/"><u>Essential Tools for Every Mac User – Free Screen Recorder Guide for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-diagnosing-and-fixing-improper-computer-boot-up-problems/"><u>Expert Advice on Diagnosing and Fixing Improper Computer Boot-Up Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-eliminating-crackling-sounds-from-pc-speakers-on-windowss/"><u>Expert Advice: Eliminating Crackling Sounds From PC Speakers on Windowss</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-rdr2-cannot-load-increase-pagefile-with-easy-steps/"><u>Fix 'RDR2 Cannot Load - Increase Pagefile' With Easy Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-common-errors-overcoming-the-driver-failure-in-user-settings-problem/"><u>Fixing Common Errors: Overcoming the 'Driver Failure in User Settings' Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-dirty-volume-problem-with-code-0x80071ac3-on-your-pc/"><u>Fixing the Dirty Volume Problem with Code 0X80071AC3 on Your PC</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/free-video-fiddling-unleash-potential-with-vimeo-editing-for-2024/"><u>Free Video Fiddling  Unleash Potential with Vimeo Editing for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-your-dell-camera-up-and-running-again-on-windows-pcs-top-fixes-revealed/"><u>Get Your Dell Camera Up and Running Again on Windows PCs – Top Fixes Revealed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-steam-error-code-80/"><u>How to Fix Steam Error Code 80</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-undetected-devices-problems-with-bluetooth-on-windows-11-systems/"><u>How to Fix Undetected Devices Problems with Bluetooth on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-windows-shell-common-dll-error-a-step-by-step-guide/"><u>How to Resolve 'Windows Shell Common DLL Error' – A Step-by-Step Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-se-2020-to-other-iphone-14-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone SE (2020) To Other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-in-ar-games-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Simulate GPS Movement in AR games On Vivo T2 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-ultimate-audio-experience-budget-friendly-asmr-mics-reviewed/"><u>In 2024, Ultimate Audio Experience  Budget-Friendly ASMR Mics Reviewed</u></a></li>
<li><a href="https://extra-skills.techidaily.com/leading-workspace-cloud-storage-hub-for-2024/"><u>Leading Workspace Cloud Storage Hub for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-error-651-repairs-simple-strategies-for-a-smooth-windows-experience/"><u>Mastering Error 651 Repairs: Simple Strategies for a Smooth Windows Experience</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/olympic-sprint-spotlight-year-2022-for-2024/"><u>Olympic Sprint Spotlight  Year 2022 for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-skype-visual-glitches-in-windows-11-with-easy-fixes/"><u>Overcome Skype Visual Glitches in Windows 11 with Easy Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ps4-whirring-buzzing-identifying-causes-and-applying-repairs/"><u>PS4 Whirring, Buzzing: Identifying Causes and Applying Repairs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-how-to-repair-your-huion-pen-when-it-stops-functioning/"><u>Quick Solutions: How to Repair Your Huion Pen When It Stops Functioning</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issues-with-geforce-experience-not-fetching-configurations-correctly/"><u>Resolved: Issues with GeForce Experience Not Fetching Configurations Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-startup-problems-in-microsoft-configurations-on-your-windows-10-pc-step-by-step/"><u>Resolving Startup Problems in Microsoft Configurations on Your Windows 10 PC [Step-by-Step]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-0x800f0831-error-instantly-a-guide-to-updating-your-windows-system/"><u>Solve 0X800f0831 Error Instantly: A Guide to Updating Your Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-black-screen-dilemma-with-your-asus-webcam-in-windows-11/"><u>Solving the Black Screen Dilemma with Your ASUS Webcam in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-problems-with-steam-store-ultimate-guide/"><u>Solving Your Problems with Steam Store: Ultimate Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-call-of-duty-world-war-ii-error-code-4220-malfunction/"><u>Step-by-Step Fix for Call of Duty World War II Error Code 4220 Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-rectify-windows-11s-error-code-0x80240034-during-updates/"><u>Step-by-Step Guide to Rectify Windows 11'S Error Code: 0X80240034 During Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-fixing-your-keyboard-by-rebooting/"><u>Step-by-Step Guide: Fixing Your Keyboard by Rebooting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-strategies-to-overcome-and-prevent-error-0x8000ffff-from-crashing-your-windows-system/"><u>Top Strategies to Overcome and Prevent Error 0X8000ffff From Crashing Your Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210003398-triumph-over-silent-touchpad-in-device-realm/"><u>Triumph Over Silent Touchpad in Device Realm!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-persistent-disappearance-of-cursor-on-windows-10-devices/"><u>Troubleshooting: Persistent Disappearance of Cursor on Windows 10 Devices</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-oppo-a79-5g-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Oppo A79 5G Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/xbox-one-controller-woes-heres-how-to-fix-connection-issues/"><u>Xbox One Controller Woes? Here’s How to Fix Connection Issues</u></a></li>
</ul></div>
