---
title: Common Fixes for Unsuccessful Windows 10 v1607 Feature Installation
date: 2024-11-05T18:32:00.517Z
updated: 2024-11-08T07:17:27.826Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Common Fixes for Unsuccessful Windows 10 v1607 Feature Installation
excerpt: This Article Describes Common Fixes for Unsuccessful Windows 10 v1607 Feature Installation
thumbnail: https://thmb.techidaily.com/d03489546d1b061501196d90eec003105f028cda35360df03f790bed178f4837.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/1884017/19272" target="_top" id="1884017">
  <img src="//a.impactradius-go.com/display-ad/19272-1884017" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884017/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1880927/19272" target="_top" id="1880927">
  <img src="//a.impactradius-go.com/display-ad/19272-1880927" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139123/17108" target="_top" id="2139123">
  <img src="//a.impactradius-go.com/display-ad/17108-2139123" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139123/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/new-leveraging-tech-for-better-facebook-live-records/"><u>[New] Leveraging Tech for Better Facebook Live Records</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-unlock-the-secrets-to-flawless-instagram-videos/"><u>2024 Approved Unlock the Secrets to Flawless Instagram Videos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unlocking-the-secret-how-to-display-youtube-playlists-on-websites/"><u>2024 Approved Unlocking the Secret How to Display YouTube Playlists on Websites</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/act-fast-secure-your-spot-playing-top-video-games-soon-facing-sunset/"><u>Act Fast: Secure Your Spot Playing Top Video Games Soon Facing Sunset!</u></a></li>
<li><a href="https://article-tips.techidaily.com/asymmetric-soothing-sound-the-best-asmr-gear-without-a-heavy-price-tag/"><u>Asymmetric Soothing Sound The Best ASMR Gear Without a Heavy Price Tag</u></a></li>
<li><a href="https://win-howtos.techidaily.com/constraint-c-for-every-redaction-made-include-an-asterisk-in-its-place-within-the-main-body-text-and-list-out-the-redacted-segments-with-their-corresponding30/"><u>Constraint C: For Every Redaction Made, Include an Asterisk () in Its Place Within the Main Body Text and List Out the Redacted Segments with Their Corresponding Sentence in Reverse Order Under Confidential Financial Optimism.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-solutions-for-troubleshooting-and-fixing-tech-issues-on-your-device/"><u>DIY Solutions for Troubleshooting and Fixing Tech Issues on Your Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-the-persistent-halo-e4ue4-crash-glitches-edition/"><u>Effective Solutions for the Persistent Halo E4UE4 Crash Glitches Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-to-recover-and-repair-corrupt-file-systems-on-windows-11-computers/"><u>Effective Strategies to Recover and Repair Corrupt File Systems on Windows 11 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-troubleshooting-and-repairing-windows-error-code-0xc0000005/"><u>Expert Tips for Troubleshooting and Repairing Windows Error Code 0XC0000005</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-world-of-playful-input-gadgets-a-journey-through-charm-to-convenience-as-featured-on-zdnet/"><u>Exploring the World of Playful Input Gadgets: A Journey Through Charm to Convenience, as Featured on ZDNet</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-honor-90-lite-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Honor 90 Lite to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/integrating-facebook-video-into-home-screen-apps/"><u>Integrating Facebook Video Into Home Screen Apps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-mystery-of-svchostexe-high-network-use-in-netsvcs-and-how-to-optimize-performance/"><u>Resolving the Mystery of svchost.exe High Network Use in NETSVCS & How to Optimize Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-usb-ports-from-failure-handling-the-port-reset-failed-issue-in-windows-10-environments/"><u>Reviving Your USB Ports From Failure: Handling the 'Port Reset Failed' Issue in Windows 10 Environments</u></a></li>
<li><a href="https://some-guidance.techidaily.com/sharpen-your-memories-learn-how-to-remove-blurs-using-ais-powerful-methods-visageai/"><u>Sharpen Your Memories: Learn How to Remove Blurs Using AI's Powerful Methods – VisageAI</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-11-effective-fixes-for-unresponsive-device-casting-issues/"><u>Troubleshooting Windows 11: Effective Fixes for Unresponsive Device Casting Issues</u></a></li>
</ul></div>

