---
title: "How to Fix a Non-Responsive Laptop Trackpad on Windows 10, 8 & 7: Troubleshooting Guide"
date: 2024-10-08T17:45:09.801Z
updated: 2024-10-09T17:51:31.244Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Fix a Non-Responsive Laptop Trackpad on Windows 10, 8 & 7: Troubleshooting Guide"
excerpt: "This Article Describes How to Fix a Non-Responsive Laptop Trackpad on Windows 10, 8 & 7: Troubleshooting Guide"
thumbnail: https://thmb.techidaily.com/104a8ce1329a7cadce28c36353075eec1970039296b8147989b16ec309b7b44b.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

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
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1828647/21290" target="_top" id="1828647">
  <img src="//a.impactradius-go.com/display-ad/21290-1828647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1828647/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137202/26400" target="_top" id="2137202">
  <img src="//a.impactradius-go.com/display-ad/26400-2137202" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137202/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915810/19272" target="_top" id="1915810">
  <img src="//a.impactradius-go.com/display-ad/19272-1915810" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915810/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-mastering-screen-sharing-on-skype-for-remote-collaboration/"><u>[New] 2024 Approved Mastering Screen Sharing on Skype for Remote Collaboration</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-explore-unlimited-free-fun-with-top-meme-templates/"><u>[New] In 2024, Explore Unlimited Free Fun with Top Meme Templates</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-inspiring-hexa-flying-drones-10/"><u>[New] In 2024, Inspiring Hexa-Flying Drones 10</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-hunt-down-the-best-free-vfx-platforms-for-your-editing-needs/"><u>[Updated] Hunt Down the Best Free VFX Platforms for Your Editing Needs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-collection-no-cost-ae-template-gold/"><u>2024 Approved Ultimate Collection No-Cost AE Template Gold</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-windows-1eb-error-0x80072fed-a-complete-walkthrough/"><u>Comprehensive Fixes for Windows 1Eb Error (0X80072FED) – A Complete Walkthrough</u></a></li>
<li><a href="https://extra-tips.techidaily.com/curated-collection-of-top-tamil-ringtone-downloads-platforms/"><u>Curated Collection of Top Tamil Ringtone Downloads Platforms</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effectively-reducing-high-resource-demand-of-wudfhostexe-in-windows-10-systems/"><u>Effectively Reducing High Resource Demand of WUDFHost.exe in Windows 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-for-resolving-windows-upgrade-frustrations/"><u>Essential Techniques for Resolving Windows Upgrade Frustrations</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-failed-windows-update-permanently/"><u>How to Fix Failed Windows Update Permanently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-user-profile-service-failure-during-login-a-comprehensive-guide/"><u>How to Resolve 'User Profile Service Failure During Login': A Comprehensive Guide</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-fix-guide-to-delete-windows-graphics-driver-files/"><u>Quick Fix Guide to Delete Windows Graphics Driver Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-pubg-lag-issues-how-to-fix-connection-lags-and-enhance-your-gameplay/"><u>Solving PUBG Lag Issues: How to Fix Connection Lags and Enhance Your Gameplay</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-xiaomi-redmi-a2-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Xiaomi Redmi A2</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-locked-system-drive-on-windows-11/"><u>Troubleshooting a Locked System Drive on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-to-fix-error-code-0x800f0922-on-windows-11-systems/"><u>Troubleshooting Tips to Fix Error Code 0X800f0922 on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unveiling-the-solutions-to-nvidia-installer-failures/"><u>Unveiling the Solutions to NVIDIA Installer Failures</u></a></li>
</ul></div>

