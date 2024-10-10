---
title: "Step-by-Step Solution: Overcoming the 'Cannot Read File or Folder' Error in Windows"
date: 2024-10-05T17:35:31.830Z
updated: 2024-10-09T20:38:32.125Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Solution: Overcoming the 'Cannot Read File or Folder' Error in Windows"
excerpt: "This Article Describes Step-by-Step Solution: Overcoming the 'Cannot Read File or Folder' Error in Windows"
thumbnail: https://thmb.techidaily.com/4f252061500e08e9c2f2521977c5b0253a500625454298afd84e9855ed4fbb6b.jpg
---

## The Ultimate Fix Guide for Overcoming Error 1068 in Windows – Expert Advice Included

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148639/16836" target="_top" id="2148639">
  <img src="//a.impactradius-go.com/display-ad/16836-2148639" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148639/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

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
<a href="https://appsumo.8odi.net/c/5597632/2037334/7443" target="_top" id="2037334">
  <img src="//a.impactradius-go.com/display-ad/7443-2037334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037334/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1883998/19272" target="_top" id="1883998">
  <img src="//a.impactradius-go.com/display-ad/19272-1883998" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1883998/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043597/7443" target="_top" id="2043597">
  <img src="//a.impactradius-go.com/display-ad/7443-2043597" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043597/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-videos.techidaily.com/updated-challenge-accepted-top-10-tiktok-trends-you-should-try/"><u>[Updated] Challenge Accepted Top 10 TikTok Trends You Should Try</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-essential-info-on-crafting-engaging-yt-shorts-for-2024/"><u>[Updated] Essential Info on Crafting Engaging YT Shorts for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-from-novice-to-pro-the-complete-creator-hub-guide/"><u>[Updated] In 2024, From Novice to Pro The Complete Creator Hub Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-fixing-the-troublesome-update-error-0x8024401c-on-windows-11/"><u>Comprehensive Guide: Fixing the Troublesome Update Error 0X8024401c on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-windows-11s-notorious-red-screen-anomaly/"><u>Diagnosing and Repairing Windows 11'S Notorious Red Screen Anomaly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-how-to-restore-pasting-functionality-on-windows-11/"><u>Fixing the Issue: How to Restore Pasting Functionality on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/forza-horizon-n4-silent-mode-error-resolved-enjoy-racing-sounds-again/"><u>Forza Horizon N°4 Silent Mode Error Resolved! Enjoy Racing Sounds Again</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-bypass-apple-iphone-6-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>How to Bypass Apple iPhone 6 Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>How To Teleport Your GPS Location On Apple iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-oppo-find-x6-pro-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Oppo Find X6 Pro Phone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-crafting-the-perfect-gaming-channel-header/"><u>In 2024, Crafting the Perfect Gaming Channel Header</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-motorola-moto-g-stylus-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Motorola Moto G Stylus 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-challenges-in-steam-games-setup-and-update-quick-guide/"><u>Overcoming Challenges in Steam Games Setup & Update - Quick Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rev-up-your-soundscape-overcoming-sound-challenges-in-forza-horizon-4/"><u>Rev Up Your Soundscape: Overcoming Sound Challenges in Forza Horizon 4</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-rated-video-game-systems-in-2e-2024-a-comprehensive-guide/"><u>Top-Rated Video Game Systems in 2E 2024: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-a-nonfunctional-surface-pen/"><u>Troubleshooting Guide: Fixing a Nonfunctional Surface Pen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolve-no-signal-screen-issue-detailed-steps/"><u>Troubleshooting Guide: Resolve 'No Signal' Screen Issue - Detailed Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-infamous-google-chrome-black-screen-tips-and-solutions/"><u>Troubleshooting the Infamous Google Chrome Black Screen: Tips & Solutions</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-no-downloads-needed-10-free-online-video-compressor-options/"><u>Updated 2024 Approved No Downloads Needed 10 Free Online Video Compressor Options</u></a></li>
</ul></div>

