---
title: "Troubleshooting Guide: Fixing Stuck File Explorer on Windows 11"
date: 2024-08-15T11:30:13.392Z
updated: 2024-08-16T11:30:13.392Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: Fixing Stuck File Explorer on Windows 11"
excerpt: "This Article Describes Troubleshooting Guide: Fixing Stuck File Explorer on Windows 11"
thumbnail: https://thmb.techidaily.com/dc54f112c78b3afb0110331eb25c5f493a4d3b2149d6ee352dfe8394d4845198.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Solution 3: Update your network adapter driver

 This problem could be also due to**a corrupted, old or missing network driver** on your system. So you can solve it through updating your network driver.

 Updating drivers require Internet connection on your computer. If your computer can’t access the wireless network, try to connect your computer to a wired network connection or, you can try the[Offline Scan](https://tools.techidaily.com/drivereasy/download/) feature of Driver Easy.

You can update your network driver either manually or automatically.

#### Manual driver update

 You can update your network driver manually by going to the manufacturer’s website for your network adapter, say,**Realtek** , and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

#### Automatic driver update

 If you don’t have the time, patience or computer skills to update your network driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly.

 You can click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the Pro version which comes with**full support** and a**30-day money back guarantee** . You’ll be prompted to upgrade when you click Update All.)  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b891580f3aca.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

You’re done. Feel free to comment below if you have any question.

* [error](https://tools.techidaily.com/drivereasy/download/)
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-enhancing-youtube-videos-proper-lighting-methods/"><u>[New] 2024 Approved  Enhancing YouTube Videos  Proper Lighting Methods</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-ultimate-mac-device-visuals-and-acoustics-in-one/"><u>[New] 2024 Approved  Ultimate Mac Device  Visuals & Acoustics in One</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-enhance-photos-with-our-best-grid-app-list-for-2024/"><u>[New] Enhance Photos with Our Best Grid App List for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-snapping-wonders-how-to-find-optimal-iphone-viewing-points/"><u>[New] Snapping Wonders  How to Find Optimal iPhone Viewing Points</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-the-ultimate-guide-to-slicing-and-dicing-vimeo-videos-online/"><u>[New] The Ultimate Guide to Slicing and Dicing Vimeo Videos Online</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-the-secrets-of-negative-video-spinning-in-snapchat/"><u>[Updated] 2024 Approved  The Secrets of Negative Video Spinning in Snapchat</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-unlocking-the-secret-to-a-streamlined-tiktok-bio-with-linktree/"><u>[Updated] In 2024, Unlocking the Secret to a Streamlined TikTok Bio with Linktree</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-step-by-step-emojis-in-youtube-comments/"><u>[Updated] Step-by-Step  Emojis in YouTube Comments</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-maximize-inshot-usage-import-feature-walkthrough/"><u>2024 Approved  Maximize InShot Usage  Import Feature Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/chrome-troubles-eradicate-errnamenotresolved-with-this-easy-method/"><u>Chrome Troubles? Eradicate 'ERR_NAME_NOT_RESOLVED' With This Easy Method!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/definitive-solutions-for-fixing-the-perplexing-unknown-usb-and-failed-port-reset-challenges-on-windows-11-devices/"><u>Definitive Solutions for Fixing the Perplexing Unknown USB and Failed Port Reset Challenges on Windows 11 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-sporadic-wi-fi-mouse-failures-in-modern-operating-systems-windows-1110/"><u>Diagnosing and Repairing Sporadic Wi-Fi Mouse Failures in Modern Operating Systems (Windows 11/10)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-update-error-code-0x80070490-a-comprehensive-guide/"><u>Fixing Windows Update Error Code 0X80070490 - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-circumventing-the-persistent-windows-10-0x800f0922-update-hurdle/"><u>Guide To Circumventing The Persistent Windows 10 0X800f0922 Update Hurdle</u></a></li>
<li><a href="https://win-howtos.techidaily.com/hearthstone-performance-boost-effortless-lag-fixes/"><u>Hearthstone Performance Boost: Effortless Lag Fixes</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/how-chatbots-are-crafting-tomorrows-media-landscape/"><u>How Chatbots Are Crafting Tomorrow's Media Landscape</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-nubia-red-magic-8s-pro-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Nubia Red Magic 8S Pro Location on Skout | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-bluetooth-disabled-issue/"><u>How To Fix Bluetooth Disabled Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-d3dx942dll-missing-or-not-found-errors/"><u>How to Fix d3dx9_42.dll Missing or Not Found Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-user-profile-service-service-failed-the-sign-in-error-windows-1111/"><u>How to Fix The User Profile Service Service Failed the Sign-In Error Windows 11/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-total-war-rome-remastered-game-crashing-issues-easily/"><u>How to Fix Total War: Rome Remastered Game Crashing Issues Easily</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-disabling-iphone-11-pro-parental-restrictions-withwithout-password-by-drfone-ios/"><u>In 2024, Disabling iPhone 11 Pro Parental Restrictions With/Without Password</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/laughs-at-your-service-web/"><u>Laughs at Your Service (Web)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-media-streaming-overcoming-windows-10-cast-failures-detailed-steps/"><u>Mastering Media Streaming: Overcoming Windows 10 Cast Failures [Detailed Steps]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-oculus-repair-strategies-to-tackle-errors-and-enhance-your-vr-experience/"><u>Mastering Oculus Repair Strategies to Tackle Errors and Enhance Your VR Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-technique-repair-methods-for-windows-startup-issues/"><u>Mastering the Technique: Repair Methods for Windows Startup Issues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-deceptive-language-models-spotting-bogus-chatgpt-on-apple-devices/"><u>Navigating Deceptive Language Models: Spotting Bogus 'ChatGPT' On Apple Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimize-and-accelerate-your-windows-7-systems-boot-speed/"><u>Optimize and Accelerate Your Windows 7 System's Boot Speed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-your-computers-stuck-at-windows-setup-a-step-by-step-guide/"><u>Resolve Your Computer's 'Stuck at Windows Setup': A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-insufficient-system-resources-errors-in-your-application/"><u>Resolved: Fixing 'Insufficient System Resources' Errors in Your Application</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-error-code-0x80072f8f-a-step-by-step-guide-for-windows-11-and-10-users/"><u>Resolving Error Code 0X80072F8F: A Step-by-Step Guide for Windows 11 & 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-how-to-enable-your-devices-wireless-functionality/"><u>Resolving Issues: How to Enable Your Device's Wireless Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-minecraft-performance-issues-ultimate-guide/"><u>Resolving Minecraft Performance Issues: Ultimate Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-for-correcting-steams-unavailable-file-rights-issue/"><u>Solution Guide for Correcting Steam's Unavailable File Rights Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-shift-key-failure-expert-troubleshooting-tips/"><u>Solving 'Shift Key Failure': Expert Troubleshooting Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-plugged-in-but-not-charging-problems-on-your-microsoft-surface/"><u>Solving Plugged In But Not Charging Problems on Your Microsoft Surface</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-csgo-crashes-in-their-tracks-simple-tips-for-stability/"><u>Stop CSGO Crashes in Their Tracks - Simple Tips for Stability</u></a></li>
<li><a href="https://win-howtos.techidaily.com/trouble-installing-the-latest-feature-update-on-windows-10-build-1607/"><u>Trouble Installing the Latest Feature Update on Windows 10 Build 1607</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-huion-tablet-issues-top-5-quick-solutions/"><u>Troubleshoot Huion Tablet Issues: Top 5 Quick Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-aoc-monitor-steps-to-restore-functionality-on-windows-10-devices/"><u>Troubleshoot Your AOC Monitor: Steps to Restore Functionality on Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-microsoft-print-to-pdf-issues-on-windows-10-and-11/"><u>Troubleshooting Microsoft Print to PDF Issues on Windows 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-responsive-prtscn-shortcut-in-microsofts-latest-operating-systems/"><u>Troubleshooting Non-Responsive PrtScn Shortcut in Microsoft's Latest Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-correcting-the-monitor-has-no-video-output-error/"><u>Troubleshooting Tips: Correcting the 'Monitor Has No Video Output' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-update-service-failures-quick-and-effective-fixes/"><u>Troubleshooting Windows Update Service Failures - Quick and Effective Fixes</u></a></li>
<li><a href="https://techtrends.techidaily.com/turning-off-the-subtitles-functionality-on-amazons-online-video-platform/"><u>Turning Off the Subtitles Functionality on Amazon's Online Video Platform</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-10-audio-issue-overcome-how-to-guide/"><u>Win 10 Audio Issue Overcome - How To Guide</u></a></li>
</ul></div>
