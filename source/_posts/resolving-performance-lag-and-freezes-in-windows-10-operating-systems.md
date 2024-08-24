---
title: Resolving Performance Lag and Freezes in Windows 10 Operating Systems
date: 2024-08-23T14:07:32.083Z
updated: 2024-08-24T14:07:32.083Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Performance Lag and Freezes in Windows 10 Operating Systems
excerpt: This Article Describes Resolving Performance Lag and Freezes in Windows 10 Operating Systems
thumbnail: https://thmb.techidaily.com/aa75ccceb27df582eb4900ae099d99b1731677ace1a8dcb38cd4f8698fb9bdda.jpg
---

## Optimizing System Performance by Reducing MsMpEngine.exe CPU Drainage in Windows 10

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## Want us to fix the problem for you?

 If the fix above didn’t work, and you don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

 That’s it – top 3 fixes for your **MsMpEng.exe-eating-up-too-much-CPU-in-Windows 10** problem. Hope this helps and feel free to comment below if you have any further questions. 🙂

* [high CPU](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://eaxpv-info.techidaily.com/new-gentle-request-for-a-greater-genuine-community-for-2024/"><u>[New] Gentle Request for a Greater, Genuine Community for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-innovative-5-websites-eclipsing-twitter/"><u>[New] In 2024, Innovative 5 Websites Eclipsing Twitter</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-guide-to-youtubes-latest-income-strategies-for-2024/"><u>[Updated] Guide to YouTube's Latest Income Strategies for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-mastering-asmr-filming-techniques-essential-tips-unveiled-for-2024/"><u>[Updated] Mastering ASMR Filming Techniques  Essential Tips Unveiled for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-professional-review-prime-drone-gimbals/"><u>[Updated] Professional Review  Prime Drone Gimbals</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-free-speech-finesse-in-online-combat/"><u>2024 Approved  Free Speech Finesse in Online Combat</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unraveling-the-mystery-of-online-broadcast-archiving/"><u>2024 Approved  Unraveling the Mystery of Online Broadcast Archiving</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-honor-magic-v2-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Honor Magic V2 FRP</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-zte-nubia-flip-5g-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from ZTE Nubia Flip 5G to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-disk-read-error-occurred-on-windows-11-solved/"><u>A Disk Read Error Occurred on Windows 11 [Solved]</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/avoiding-escalation-stealthy-yet-effective-techniques-to-address-grievances-on-discord/"><u>Avoiding Escalation  Stealthy Yet Effective Techniques to Address Grievances on Discord</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bridging-the-gap-how-to-seamlessly-pair-airpods-with-windows-11/"><u>Bridging the Gap: How to Seamlessly Pair AirPods with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solution-for-resolving-update-error-0xc1900208-on-windows-11-systems/"><u>Comprehensive Solution for Resolving Update Error 0Xc1900208 on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-troubleshooting-guide-for-dealing-with-fn-key-issues-in-your-dell-laptop/"><u>DIY Troubleshooting Guide for Dealing with FN-Key Issues in Your Dell Laptop</u></a></li>
<li><a href="https://fox-info.techidaily.com/easy-to-follow-action-cam-buyers-blueprint-23/"><u>Easy-to-Follow Action Cam Buyers’ Blueprint '23</u></a></li>
<li><a href="https://win-howtos.techidaily.com/efficient-wdf-techniques-for-decreased-cpu-usage-on-windows/"><u>Efficient WDF Techniques for Decreased CPU Usage on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-fix-for-non-functioning-voice-chat-in-overwatch/"><u>Effortless Fix for Non-Functioning Voice Chat in Overwatch</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/enhancing-visual-content-consumption-via-edges-pip/"><u>Enhancing Visual Content Consumption via Edge’s PIP</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/enhancing-your-video-impact-a-compreranble-plan-for-youtube-success-for-2024/"><u>Enhancing Your Video Impact  A Compreranble Plan for YouTube Success for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-failed-windows-updates-on-your-computer/"><u>Expert Tips For Repairing Failed Windows Updates On Your Computer</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-honor-80-pro-straight-screen-edition-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Honor 80 Pro Straight Screen Edition Quickly | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-restore-keyboard-letters-that-arent-responding-in-windows-10-and-11/"><u>Guide to Restore Keyboard Letters That Aren't Responding in Windows 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-reactivating-windows-11s-screen-saver-feature-with-ease/"><u>Guide: Reactivating Windows 11'S Screen Saver Feature with Ease</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-correctly-address-the-persistent-code-28-glitch-in-windows-device-manager/"><u>How to Correctly Address the Persistent 'Code 28' Glitch in Windows Device Manager</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unresponsive-file-explorer-on-windows-10-solutions-explored/"><u>How to Fix Unresponsive File Explorer on Windows 10 - Solutions Explored</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-gain-authorization-from-trustedinstaller-for-changing-protected-files/"><u>How to Gain Authorization From TrustedInstaller for Changing Protected Files</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-the-brightness-control-back-in-working-order-on-windows-11/"><u>How to Get the Brightness Control Back in Working Order on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-of-your-laptops-touchpad-for-windows-1187-users/"><u>How to Restore Functionality of Your Laptop's Touchpad for Windows 11/8/7 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-power-off-your-pc-running-windows-11-solutions-explored/"><u>How to Successfully Power Off Your PC Running Windows 11: Solutions Explored</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-vivo-x100-pro-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Vivo X100 Pro Activity | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/in-depth-analysis-of-asus-rog-swift-pg49wcd-2023s-top-oled-gaming-display/"><u>In-Depth Analysis of Asus ROG Swift PG49WCD - 2023'S Top OLED Gaming Display</u></a></li>
<li><a href="https://win-howtos.techidaily.com/installation-error-windows-11-v1607-feature-update-uninstallable/"><u>Installation Error: Windows 11 v1607 Feature Update Uninstallable</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722961067504-intel-nvme-driver-installation-made-effortless-start-here/"><u>Intel NVME Driver Installation Made Effortless – Start Here!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/microsoft-store-malfunction-heres-how-you-can-fix-it-now/"><u>Microsoft Store Malfunction? Here's How You Can Fix It Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigate-through-win-10s-update-challenges-8-remedies-for-error-0x800f0922/"><u>Navigate Through Win 10'S Update Challenges: 8 Remedies for Error 0X800F0922</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-update-completed-errors-at-100-on-your-windows-pc-fixed/"><u>Overcoming 'Update Completed' Errors at 100%% on Your Windows PC [FIXED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-windows-update-error-8007000e-simple-steps/"><u>Quick Fixes for Windows Update Error 8007000E – Simple Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-for-your-non-charging-laptop-battery-a-simple-guide/"><u>Quick Fixes for Your Non-Charging Laptop Battery: A Simple Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/re-enabled-local-security-framework-ensuring-robust-protection/"><u>Re-Enabled Local Security Framework - Ensuring Robust Protection</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-livekernelevent-type-144-mistake/"><u>Resolve LiveKernelEvent Type 144 Mistake</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-error-due-to-lack-of-system-resources/"><u>Resolved! Error Due to Lack of System Resources</u></a></li>
<li><a href="https://driver-download.techidaily.com/resolving-beats-audio-driver-conflicts-on-hp-devices-in-windows-operating-systems/"><u>Resolving Beats Audio Driver Conflicts on HP Devices in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-kernel32dll-fails/"><u>Resolving Kernel32.dll Fails</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ess-google-meet-integration-for-youtube-enthusiasts-for-2024/"><u>Seamless Google Meet Integration for YouTube Enthusiasts for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-instructions-to-restore-visibility-on-dell-laptop-screens/"><u>Step-by-Step Instructions to Restore Visibility on Dell Laptop Screens</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-for-resolving-windows-update-issue-error-0x80240017/"><u>Step-by-Step Solution for Resolving Windows Update Issue (Error 0X80240017)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/step-by-step-to-premium-audio-with-audacity/"><u>Step-by-Step to Premium Audio with Audacity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-restoring-sound-capabilities-in-windows-systems/"><u>Step-by-Step Tutorial: Restoring Sound Capabilities in Windows Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-guide-to-gaining-complete-control-over-your-steam-installation/"><u>The Ultimate Guide to Gaining Complete Control Over Your Steam Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-solution-for-overcoming-youtubes-audio-playback-problem-in-the-windows-10-ecosystem/"><u>The Ultimate Solution for Overcoming YouTube's Audio Playback Problem in the Windows 10 Ecosystem</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transform-valorant-gameplay-top-ranked-costless-voice-alterer-revealed-for-2024/"><u>Transform Valorant Gameplay  Top-Ranked, Costless Voice Alterer Revealed for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-successfully-install-battleye-anti-cheat-now/"><u>Troubleshoot and Successfully Install BattlEye Anti-Cheat Now</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-wacom-device-drivers-missing-error-in-windows-11/"><u>Troubleshooting Steps for Wacom Device Drivers Missing Error in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-solution-for-call-of-duty-world-war-ii-error-code-4220-issues/"><u>Ultimate Solution for Call of Duty World War II Error Code 4220 Issues</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-amazon-live-for-beginners-features-pro-tips-and-future-trends-for-2024/"><u>Updated Amazon Live for Beginners Features, Pro Tips & Future Trends for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/updated-reactivate-the-local-user-account-verification-mechanism/"><u>Updated: Reactivate the Local User Account Verification Mechanism</u></a></li>
</ul></div>
