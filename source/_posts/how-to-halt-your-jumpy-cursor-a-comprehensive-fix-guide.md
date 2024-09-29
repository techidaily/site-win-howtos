---
title: How to Halt Your Jumpy Cursor - A Comprehensive Fix Guide
date: 2024-09-27T23:01:46.034Z
updated: 2024-09-28T16:46:27.006Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Halt Your Jumpy Cursor - A Comprehensive Fix Guide
excerpt: This Article Describes How to Halt Your Jumpy Cursor - A Comprehensive Fix Guide
thumbnail: https://thmb.techidaily.com/e29e93d35845e0087f7b9052aff9cbe637121c31e79b4423801c6a206d9b7bce.jpg
---

## Fixing Error 1068 in Windows: A Comprehensive Guide - SOLUTION FOUND

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389">
  <img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151871/7443" target="_top" id="2151871">
  <img src="//a.impactradius-go.com/display-ad/7443-2151871" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151871/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105867/7443" target="_top" id="2105867">
  <img src="//a.impactradius-go.com/display-ad/7443-2105867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105867/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/updated-essential-techniques-for-enhancing-obs-studio-edits-for-2024/"><u>[Updated] Essential Techniques for Enhancing OBS Studio Edits for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-social-media-mirrors-the-science-of-true-ig-selfies/"><u>2024 Approved Social Media Mirrors The Science of True IG Selfies</u></a></li>
<li><a href="https://tech-revival.techidaily.com/a-comprehensive-guide-to-adjusting-video-pace-in-youtube-viewing-mode/"><u>A Comprehensive Guide to Adjusting Video Pace in YouTube Viewing Mode</u></a></li>
<li><a href="https://extra-resources.techidaily.com/classic-1980s-visual-elements-in-editing-workflow-for-2024/"><u>Classic 1980S Visual Elements in Editing Workflow for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-fixes-for-sims-4-not-loading-up-a-step-by-step-guide/"><u>Effective Fixes for Sims 4 Not Loading Up: A Step-by-Step Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-factory-unlock-your-telstra-apple-iphone-se-2020-by-drfone-ios/"><u>How To Factory Unlock Your Telstra Apple iPhone SE (2020)</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Motorola Edge+ (2023)? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-mutt-melodies-an-array-of-authentic-dog-audio-experiences/"><u>In 2024, Mutt Melodies An Array of Authentic Dog Audio Experiences</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transform-shots-to-boost-circular-vignette-features/"><u>In 2024, Transform Shots to Boost Circular Vignette Features</u></a></li>
<li><a href="https://extra-support.techidaily.com/laughoutloud-maker-get-funny-faces-on-the-web-for-2024/"><u>LaughOutLoud Maker Get Funny Faces on the Web for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigate-past-windows-11-update-blockages-solutions-that-work/"><u>Navigate Past Windows 11 Update Blockages – Solutions That Work</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-netcertweaksignature-problem-to-ensure-website-safety-and-integrity/"><u>Overcoming the NET::CERT_WEAK_SIGNATURE Problem to Ensure Website Safety and Integrity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-quick-guide-windows-cannot-complete-installing-software/"><u>Resolving the Quick Guide: Windows Cannot Complete Installing Software</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-for-keyboards-where-the-number-pad-doesnt-respond/"><u>Solution Guide for Keyboards Where the Number Pad Doesn’t Respond</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-your-non-responsive-xbox-one-controller/"><u>Troubleshooting Guide: Fixing Your Non-Responsive Xbox One Controller</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-halo-4s-critical-ue4-bugs-for-smooth-gaming/"><u>Troubleshooting Halo 4'S Critical UE4 Bugs for Smooth Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-persistent-freezing-problems-on-windows-11-boot-up/"><u>Troubleshooting Persistent Freezing Problems on Windows 11 Boot-Up</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-inactive-diagnostics-policy-service-fixed/"><u>Troubleshooting Steps for Inactive Diagnostics Policy Service [Fixed]</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Xiaomi Redmi 13C? | Dr.fone</u></a></li>
</ul></div>

