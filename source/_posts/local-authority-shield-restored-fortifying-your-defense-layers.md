---
title: Local Authority Shield Restored - Fortifying Your Defense Layers
date: 2024-08-19T06:54:43.577Z
updated: 2024-08-20T06:54:43.577Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Local Authority Shield Restored - Fortifying Your Defense Layers
excerpt: This Article Describes Local Authority Shield Restored - Fortifying Your Defense Layers
thumbnail: https://thmb.techidaily.com/c2364ce1ce1631cf3307292a0e382081e93d8f200b22ab446d3c669b5473d173.jpg
---

## Restore Your Device's Safety - Turn On LSA Shield Again

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-24.png)

Local Security Authority Protection is off

 No need to worry if your Local Security Authority Protection is toggled off: in most cases, it was a UI bug with a certain Windows update patch, meaning that it’s not off, just appears to be off, and you can install another update patch to get it fixed. In other rare cases, you can change your computer settings to get it enabled again. Read on and see how you can fix the Local Security Authority Protection being off problem.

## Try these fixes to enable the Local Security Authority Protection

 As mentioned, in most cases, your Local Security Authority is off because of a UI bug with a Windows patch, so the first method should be enough to help. If it doesn’t, please move on to methods 2 and 3.

1. **[Install Windows Update patch KB5007651](#m1)**
2. **[Modify Registry Editor](#m2)**
3. **[Configure Group Policy Editor](#m3)**

---

## 1\. Install Windows Update patch KB5007651

 The Local Security Authority Protection being off bug was actually a bug that shipped with Windows 11’s March 2023 mandatory security update, patch KB5007651\. Windows then released the updated version of this patch that fixed this problem. So if you still haven’t already, please update your Windows now for the latest patch KB5007651 to install.

To do so:

1. On your keyboard, hit the**Windows** key, then type**check for update** s, then click C**heck for updates** .  

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-18.png)
2. Click**Check for updates** , and Windows will scan for any available updates.  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-19.png)
3. If there are available updates, Windows will automatically download them for you. Restart your computer for the update to take effect if needed.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-20.png)
4. If there are_no_ available updates, you’ll see**You’re up to date** like this.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-21.png)

Then see if the Local Security Authority Protection is still off.

 If so, please download the installation file for KB5007651 from[here](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5007651) , then double-click the installation file to get it installed.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-25.png)

 If the “Local Security protection is off” notification is still there when you manually install the KB5007651 update, please move on to the next fix.

---

## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

 Then see if your Local Security Authority protection can be toggled back on.

---

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Bonus tip

 If turning on the Local Security Authority protection doesn’t help to fix your computer problems, you can always try to repair any damaged or corrupted system files, as**the integrity of Windows system files is** essential for proper operation and stability for your computer.

 Tools like **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  can automate the repair process by scanning system files and replacing corrupted ones.

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect. It will run a free scan of your PC and give you**a detailed report of your PC status** .  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-scan.jpg)
3. Once finished, you’ll see a report showing all the issues. To fix all the issues automatically, click**Start Repair** (You’ll need to purchase the full version. It comes with a**60-day Money-Back Guarantee** so you can refund anytime if Fortect doesn’t fix your problem).  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

 Fortect comes with a 60-day Money-Back Guarantee. If you’re not satisfied with Fortect, you can contact <support@fortect.com> for a full refund.

 Still unsure if Fortect is what you need? Check this [Fortec Review](https://tools.techidaily.com/drivereasy/download/) !

---

 The above is what we have to offer regarding “Local Security Authority protection is off” problem. If you have any other suggestions, please feel free to leave a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-unveiling-the-magic-of-end-screens-for-vimeo-content/"><u>[Updated] 2024 Approved  Unveiling the Magic of End Screens for Vimeo Content</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-free-or-paid-top-8-ios-film-watching-apps-reviewed/"><u>[Updated] Free or Paid? Top 8 iOS Film-Watching Apps Reviewed</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-is-active-the-premier-choice-for-tech-enthusiasts/"><u>[Updated] Is Active the Premier Choice for Tech Enthusiasts?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pushing-boundaries-with-high-speed-cinematography/"><u>[Updated] Pushing Boundaries with High-Speed Cinematography</u></a></li>
<li><a href="https://win-howtos.techidaily.com/key-not-responding-here-are-proven-ways-to-restore-its-functionality/"><u>@ Key Not Responding? Here Are Proven Ways to Restore Its Functionality!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-code-crafters-battle-assessing-chatgpt-versus-gemini-for-programming-excellence/"><u>AI Code Crafters Battle: Assessing ChatGPT Versus Gemini for Programming Excellence</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dealing-with-unwanted-automatic-restart-cycles-when-powering-off-windows-11-devices/"><u>Dealing With Unwanted Automatic Restart Cycles When Powering Off Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-persistent-reboot-problems-in-windows-10/"><u>Easy Fixes for Persistent Reboot Problems in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-fixing-cast-to-device-failures-in-windows-10-systems/"><u>Effective Solutions for Fixing 'Cast to Device' Failures in Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/errtoomanyredirects-clear-it-up-in-minutes-with-these-tips/"><u>ERR_TOO_MANY_REDIRECTS? Clear It Up in Minutes with These Tips</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-guide-to-the-top-10-no-cost-visual-vaults/"><u>Essential Guide to The Top 10 No-Cost Visual Vaults</u></a></li>
<li><a href="https://win-howtos.techidaily.com/getting-your-webcam-back-on-track-a-guide-for-hp-laptops-on-windows-10/"><u>Getting Your Webcam Back on Track: A Guide for HP Laptops on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-i-overcame-the-problem-of-enabling-hosted-networks-on-windows-11/"><u>How I Overcame the Problem of Enabling Hosted Networks on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-internet-explorer-when-it-refuses-to-launch-solutions-inside/"><u>How to Fix Internet Explorer When It Refuses to Launch - Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-lenovo-mouse-pad-problems-in-various-windows-systems/"><u>How to Resolve Lenovo Mouse Pad Problems in Various Windows Systems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-honor-play-8t-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Honor Play 8T to iPod | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-poco-m6-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Poco M6 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-top-notch-solutions-for-disabled-apple-id-on-iphone-6s-making-it-possible-by-drfone-ios/"><u>In 2024, Top-Notch Solutions for Disabled Apple ID On iPhone 6s Making It Possible</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-is-ipogo-not-working-on-htc-u23-pro-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On HTC U23 Pro? Fixed | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-fixes-for-power-state-driver-issues-in-windows-devices/"><u>Mastering Fixes for Power State Driver Issues in Windows Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/oddworld-soulstorm-steps-to-solve-pc-installation-problems/"><u>Oddworld: Soulstorm - Steps to Solve PC Installation Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ps4-power-dilemma-no-more-solve-your-controllers-charging-woes-here/"><u>PS4 Power Dilemma No More - Solve Your Controller's Charging Woes Here</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-persistent-buffering-problems-on-kodi-fixed-solutions/"><u>Resolve Persistent Buffering Problems on Kodi - Fixed Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-compatibility-woes-of-wd-my-passport-ultra-with-the-windows-operating-system/"><u>Resolved: Compatibility Woes of WD My Passport Ultra with the Windows Operating System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-user-profile-service-failure-during-sign-in-on-windows-1011-a-step-by-step-guide/"><u>Resolving 'User Profile Service' Failure During Sign-In on Windows 10/11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-sound-setbacks-astro-a40-microphone-not-working-guide/"><u>Resolving Sound Setbacks: Astro A40 Microphone Not Working Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-windows-11-touch-screen-effective-fixes-you-must-know-5/"><u>Revive Your Windows 11 Touch Screen: Effective Fixes You Must Know (5)</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ifying-the-path-to-understanding-youtube-numbers/"><u>Simplifying the Path to Understanding YouTube Numbers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-to-make-unsupported-graphics-driver-compatible-with-miracast-technology/"><u>Solution to Make Unsupported Graphics Driver Compatible with Miracast Technology</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-persistent-usb-mouse-connection-issues-a-comprehensive-guide/"><u>Solving Persistent USB Mouse Connection Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-weak-signature-algorithms-neterrcert-enhancing-your-browsers-security/"><u>Step-by-Step Fix for Weak Signature Algorithms (NET::ERR_CERT): Enhancing Your Browser's Security</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-repairing-the-troublesome-red-screen-in-windows-10/"><u>Step-by-Step Guide: Repairing the Troublesome Red Screen in Windows 10</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-guide-tackling-cutting-out-audio-glitches-in-windows-10/"><u>Step-by-Step Guide: Tackling Cutting Out Audio Glitches in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-guide-for-a-quick-clean-boot-into-windows-11-os/"><u>The Ultimate Guide for a Quick Clean Boot Into Windows 11 OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-enhance-your-keyboards-reaction-time-quickly/"><u>Troubleshoot and Enhance Your Keyboard's Reaction Time Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-unable-to-complete-wrp-requested-operation-quickly/"><u>Troubleshoot and Fix 'Unable to Complete WRP Requested Operation' Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723205491215-troubleshooting-nonfunctional-usb-ports-on-windows-1011-fixed/"><u>Troubleshooting Nonfunctional USB Ports on Windows 10/11 - Fixed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723201556389-troubleshooting-overwatch-voice-chat-malfunctions-simple-solutions/"><u>Troubleshooting Overwatch Voice Chat Malfunctions: Simple Solutions!</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-preventing-frequent-crashes-in-minecraft-dungeons-for-windows-users/"><u>Troubleshooting Tips: Preventing Frequent Crashes in Minecraft Dungeons for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-world-of-warcraft-connection-lags/"><u>Troubleshooting Your World of Warcraft Connection Lags</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fixes-for-the-persistent-error-code-0x800705b4-on-your-windows-10-system/"><u>Ultimate Fixes for the Persistent Error Code 0X800705b4 on Your Windows 10 System</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-the-button-symphony-locating-the-percussive-elements-in-gaming-for-2024/"><u>Updated The Button Symphony Locating the Percussive Elements in Gaming for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/upgraded-graphics-engine-geforce-210-for-windows-users/"><u>Upgraded Graphics Engine: GeForce 210 for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-is-my-ps4-making-noise-identifying-problems-with-the-cooling-system-and-solutions/"><u>Why Is My PS4 Making Noise? Identifying Problems with the Cooling System and Solutions</u></a></li>
</ul></div>
