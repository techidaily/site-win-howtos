---
title: "Step-by-Step Fixes for 'This Device Is Not Present' - Error Code 24 in Windows Versions: 11, 8 and 7"
date: 2024-08-19T07:47:12.762Z
updated: 2024-08-20T07:47:12.762Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Fixes for 'This Device Is Not Present' - Error Code 24 in Windows Versions: 11, 8 and 7"
excerpt: "This Article Describes Step-by-Step Fixes for 'This Device Is Not Present' - Error Code 24 in Windows Versions: 11, 8 and 7"
thumbnail: https://thmb.techidaily.com/fb8053ac7214659fa378f042df998d4365da978dd3a640439d6ee68045b0a185.jpg
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
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
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
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-elevate-video-decks-smart-description-templates/"><u>[New] 2024 Approved  Elevate Video Decks  Smart Description Templates</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-30-second-guide-to-fast-fortnite-graphics/"><u>[New] In 2024, 30-Second Guide to Fast Fortnite Graphics</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-swift-rescaling-perfect-mac-pixels-with-youtube/"><u>[New] In 2024, Swift Rescaling  Perfect Mac Pixels with YouTube</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-the-evolved-2023-samsung-bd-j5900-a-deep-dive-for-2024/"><u>[New] The Evolved 2023 Samsung BD-J5900  A Deep Dive for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-ultimate-hash-tracker-list-for-major-social-media-sites-fbtwitterinsta/"><u>[New] Ultimate Hash Tracker List for Major Social Media Sites (FB/Twitter/Insta)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-spacebar-not-working-on-windows-11/"><u>[Solved] Spacebar Not Working on Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-beyond-marketing-hype-the-genuine-facts-of-reels/"><u>[Updated] Beyond Marketing Hype  The Genuine Facts of Reels</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-eco-friendly-cities-redefining-urban-spaces-for-nature/"><u>[Updated] In 2024, Eco-Friendly Cities  Redefining Urban Spaces for Nature</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-unveiling-synergy-youtube-content-on-facebook-network/"><u>[Updated] In 2024, Unveiling Synergy  YouTube Content on Facebook Network</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-mastering-video-edits-essential-mp4-tools-for-mac-users/"><u>[Updated] Mastering Video Edits  Essential MP4 Tools for Mac Users</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-mirthful-media-youtubes-top-20-for-a-chuckle-for-2024/"><u>[Updated] Mirthful Media  YouTube's Top 20 for a Chuckle for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-turning-off-instagrams-igtv-in-a-nutshell-for-2024/"><u>[Updated] Turning Off Instagram's IGTV in a Nutshell for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-achieving-youtube-financial-goals-via-viewer-statistics/"><u>2024 Approved  Achieving Youtube Financial Goals via Viewer Statistics</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-start-participate-in-and-organize-zoom-calls-for-android-users/"><u>2024 Approved  How to Start, Participate in, and Organize Zoom Calls for Android Users</u></a></li>
<li><a href="https://win-solutions.techidaily.com/5-fixes-to-fix-csgo-no-user-logon-error/"><u>5 Fixes To Fix CSGO No User Logon Error</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/breaking-the-barrier-easy-livestream-setup-for-podcasters-for-2024/"><u>Breaking the Barrier  Easy Livestream Setup for Podcasters for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dell-camera-malfunction-in-windows-solutions-for-reviving-image-capture-features/"><u>Dell Camera Malfunction in Windows - Solutions for Reviving Image Capture Features</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-huawei-p60-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Huawei P60 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/drive-windows-kernel32-problems-away/"><u>Drive Windows' Kernel32 Problems Away</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-remedies-for-windows-10-cast-to-device-malfunctions-solutions-inside/"><u>Effective Remedies for Windows 10 Cast To Device Malfunctions – Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fixes-for-when-your-laptop-keeps-docking-into-sleep-mode/"><u>Effortless Fixes for When Your Laptop Keeps Docking Into Sleep Mode</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ensuring-file-permanence-how-windows-10-preserves-locations-upon-reboot/"><u>Ensuring File Permanence: How Windows 10 Preserves Locations Upon Reboot</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x800f081f-on-your-mind-solving-the-dotnet-35-install-problems/"><u>Error Code 0X800F081F on Your Mind? Solving the DotNet 3.5 Install Problems!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-fixing-constant-usb-reconnection-problems/"><u>Expert Advice on Fixing Constant USB Reconnection Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-to-repairing-usb-port-issues-in-windows-10-and-11-systems/"><u>Expert Guide to Repairing USB Port Issues in Windows 10 and 11 Systems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-reviews-by-toms-hardware-find-the-best-tech-gear/"><u>Expert Reviews by Tom's Hardware: Find the Best Tech Gear</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-fixes-for-overcoming-windows-persistent-update-error-code-0x80amelioration-of-update-malfunction/"><u>Fast Fixes for Overcoming Window's Persistent Update Error: Code 0X80amelioration of Update Malfunction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-unable-to-print-to-pdf-on-windows-11/"><u>Fixing the Issue: Unable to Print to PDF on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-automatic-updates-that-arent-working-comprehensive-guide/"><u>Fixing Windows Automatic Updates That Aren't Working – Comprehensive Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-honor-magic-5-pro-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Honor Magic 5 Pro?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correct-the-failed-driver-setting-issue-on-your-device/"><u>How to Correct the 'Failed Driver' Setting Issue on Your Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-frozen-google-chrome-and-reboot-successfully/"><u>How to Fix a Frozen Google Chrome and Reboot Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-maintain-constant-connection-for-your-wireless-mouse/"><u>How to Maintain Constant Connection for Your Wireless Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-and-repair-compromised-system-files-within-windows-11/"><u>How to Resolve and Repair Compromised System Files Within Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-apply-the-latest-windows-patches-and-enhancements/"><u>How to Successfully Apply the Latest Windows Patches & Enhancements</u></a></li>
<li><a href="https://win-howtos.techidaily.com/identifying-and-fixing-the-causes-of-overly-loud-ps4-units/"><u>Identifying and Fixing the Causes of Overly-Loud PS4 Units</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-poco-f5-5g-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Poco F5 5G FRP Locks</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-honor-v-purse-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Honor V Purse Phones with/without a PC</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-lava-blaze-pro-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Lava Blaze Pro 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-infinix-note-30-vipfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Infinix Note 30 VIPFRP Lock</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-realme-narzo-60x-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Realme Narzo 60x 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-checklist-preparing-your-room-and-pc-for-oculus-rift/"><u>In 2024, Ultimate Checklist  Preparing Your Room and PC for Oculus Rift</u></a></li>
<li><a href="https://tech-hub.techidaily.com/inside-gpt4alls-operational-framework/"><u>Inside GPT4All's Operational Framework</u></a></li>
<li><a href="https://win-howtos.techidaily.com/interrupted-service-blizzard-inaccessible/"><u>Interrupted Service: Blizzard Inaccessible</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-compatible-device-drivers-for-toshiba-portable-computers-free-download-and-installation-steps/"><u>Latest Compatible Device Drivers for Toshiba Portable Computers - Free Download & Installation Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lsa-defense-reactivated-how-to-secure-your-system-effectively/"><u>LSA Defense Reactivated: How to Secure Your System Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-bug-free-code-tips-and-solutions-to-eliminate-abrupt-software-halts/"><u>Mastering Bug-Free Code: Tips and Solutions to Eliminate Abrupt Software Halts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/nba-2k21-bug-fixed-no-more-green-mishap/"><u>NBA 2K21 Bug Fixed: No More Green Mishap</u></a></li>
<li><a href="https://win-howtos.techidaily.com/netflix-trouble-heres-how-to-fix-the-using-a-proxyvpn-error-message/"><u>Netflix Trouble? Here's How to Fix the 'Using a Proxy/VPN' Error Message</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-hurdle-fixing-errors-when-your-program-cant-find-necessary-modules/"><u>Overcoming the Hurdle: Fixing Errors When Your Program Can't Find Necessary Modules</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-videos-from-asus-rog-phone-8-by-fonelab-android-recover-video/"><u>Possible solutions to restore deleted videos from Asus ROG Phone 8</u></a></li>
<li><a href="https://win-howtos.techidaily.com/render-engine-failed-to-launch-solutions-for-21-patching-needs/"><u>Render Engine Failed to Launch - Solutions for 2^1 Patching Needs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-a-step-by-step-guide-to-fixing-black-screen-on-google-chrome/"><u>Resolving the Issue: A Step-by-Step Guide to Fixing Black Screen on Google Chrome</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-windows-1011-acer-laptop-keys-please/"><u>Revive Windows 10/11 Acer Laptop Keys, Please!</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-vivo-t2-5g-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Vivo T2 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-approach-to-resolving-windows-10-problems-using-system-file-checker-sfc-and-deployment-image-servicing-and-management-dism/"><u>Step-by-Step Approach to Resolving Windows 10 Problems Using System File Checker (SFC) & Deployment Image Servicing and Management (DISM)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-overcoming-hamachi-halted-error/"><u>Step-by-Step Guide to Overcoming Hamachi Halted Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-overcoming-0x80070652-windows-update-errors-easily/"><u>Step-by-Step Guide: Overcoming 0X80070652 Windows Update Errors Easily</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-updating-your-ac-95s60-wifi-adapter-with-intels-latest-driver/"><u>Step-by-Step Guide: Updating Your AC 95S60 WiFi Adapter with Intel's Latest Driver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracking-and-tallying-windows-app-sizes/"><u>Tracking and Tallying Windows App Sizes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-successful-fixes-on-warframe-patch-errors/"><u>Troubleshooting Successful Fixes on Warframe Patch Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-why-is-my-spacebar-unresponsive-in-windows-11/"><u>Troubleshooting: Why Is My Spacebar Unresponsive in Windows 11?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-the-windows-bsod-beep-series-error-0xc00000e9/"><u>Ultimate Guide: Resolving the Windows BSOD (Beep Series) Error 0xC00000E9</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-the-potential-of-file-explorer-in-windows-10-made-easy/"><u>Unlocking the Potential of File Explorer in Windows 10 Made Easy</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-is-my-razer-keyboard-not-lights-fix-and-prevent-this-common-problem/"><u>Why Is My Razer Keyboard Not Lights? Fix and Prevent This Common Problem!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-update-stuck-or-frozen-how-do-i-fix-it/"><u>Windows 10 Update Stuck or Frozen - How Do I Fix It?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-upgrade-avoiding-crashes/"><u>Windows Upgrade: Avoiding Crashes</u></a></li>
</ul></div>
