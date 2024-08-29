---
title: "Optimizing System Resources: Reducing MsMpEng.exe Load in Windows 11"
date: 2024-08-28T00:30:13.922Z
updated: 2024-08-29T00:30:13.922Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Optimizing System Resources: Reducing MsMpEng.exe Load in Windows 11"
excerpt: "This Article Describes Optimizing System Resources: Reducing MsMpEng.exe Load in Windows 11"
thumbnail: https://thmb.techidaily.com/6ea42b82e55f6c668ff7a393a7539803912a1c23ef44a3dc870ec2d24d91150f.jpg
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

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-disabling-apex-legends-cross-play-best-platform-tactics-unveiled-for-2024/"><u>[New] Disabling Apex Legends Cross-Play  Best Platform Tactics Unveiled for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210498463-solved-wmi-provider-host-high-cpu-usage-on-windows-1011-quickly-and-easily/"><u>[Solved] WMI Provider Host: High CPU Usage on Windows 10/11 | Quickly & Easily</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-broadcasting-best-practices-twitch-facebook-integration/"><u>[Updated] 2024 Approved  Broadcasting Best Practices  Twitch-Facebook Integration</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-dance-the-viral-dance-mix-in-some-tiktok-flavor-for-insta-success-for-2024/"><u>[Updated] Dance the Viral Dance  Mix in Some TikTok Flavor for Insta Success for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-expert-recommendations-top-5-video-recording-software/"><u>[Updated] Expert Recommendations  Top 5 Video Recording Software</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-from-digital-sketches-to-dynamic-lives-the-pc-guide-for-tiktok-broadcasting/"><u>[Updated] From Digital Sketches to Dynamic Lives  The PC Guide for TikTok Broadcasting</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/2024-approved-ultimate-guide-to-shopee-livestream-selling-maximize-profits/"><u>2024 Approved Ultimate Guide to Shopee Livestream Selling Maximize Profits</u></a></li>
<li><a href="https://change-location.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-tecno-camon-20-pro-5g-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Tecno Camon 20 Pro 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/best-solution-to-fix-ps4-mic-not-working/"><u>Best Solution to Fix PS4 Mic Not Working</u></a></li>
<li><a href="https://win-howtos.techidaily.com/breakthrough-for-xbox-ones-use-on-personal-computers/"><u>Breakthrough for Xbox One's Use on Personal Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/common-causes-of-minecraft-multiplayer-lan-failures-and-solutions/"><u>Common Causes of Minecraft Multiplayer LAN Failures and Solutions</u></a></li>
<li><a href="https://extra-resources.techidaily.com/curated-list-top-5-engaging-book-trailers/"><u>Curated List  Top 5 Engaging Book Trailers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-correcting-the-frequent-disconnection-problem-in-your-personal-computer-mouse/"><u>Diagnosing and Correcting the Frequent Disconnection Problem in Your Personal Computer Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-stuck-or-defective-keys-for-windows-10-and-11-users/"><u>Diagnosing and Repairing Stuck or Defective Keys for Windows 10 & 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-persistent-windows-11-update-errors-a-step-by-step-guide/"><u>Fixing Persistent Windows 11 Update Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207534072-fixing-windows-11-installation-failure-resolve-error-code-802/"><u>Fixing Windows 11 Installation Failure: Resolve Error Code 802#</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-successfully-setting-up-your-smartaudio-device-after-initial-hiccups/"><u>Guide: Successfully Setting Up Your SmartAudio Device After Initial Hiccups</u></a></li>
<li><a href="https://win-howtos.techidaily.com/improving-display-synchronization-between-your-device-and-monitor/"><u>Improving Display Synchronization Between Your Device and Monitor</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-prime-listening-windows-episode-releases/"><u>In 2024, Prime Listening Windows  Episode Releases</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-application-failed-to-initialize-0xc000007b-problem-on-your-computer/"><u>Overcoming the 'Application Failed to Initialize: 0Xc000007b' Problem on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-overcoming-startup-problems-with-error-code-1053/"><u>Quick Fixes: Overcoming Startup Problems with Error Code 1053</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rectified-power-surge-issue-with-gateway-hub/"><u>Rectified: Power Surge Issue with Gateway Hub</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-couldnt-perform-action-for-windows-resources-issue-easily/"><u>Resolve 'Couldn't Perform Action for Windows Resources' Issue Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-windows-10-update-issue-with-error-code-0x800f0922-using-these-easy-fixes/"><u>Resolve Windows 10 Update Issue with Error Code 0X800f0922 Using These Easy Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issue-the-infamous-green-error-in-nba-2k21/"><u>Resolved Issue: The Infamous Green Error in NBA 2K21</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-adjusted-security-preferences-now-permit-download-of-this-file/"><u>Resolved: Adjusted Security Preferences Now Permit Download of This File</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-unexpected-auto-boot-on-your-windows-11-machine-a-comprehensive-guide/"><u>Solve Unexpected Auto-Boot on Your Windows 11 Machine: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-audio-output-device-not-found-errors-for-windows-users/"><u>Step-by-Step Guide: Correcting 'Audio Output Device Not Found' Errors for Windows Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210725290-top-remedies-for-when-your-laptops-usb-mouse-wont-work-restore-functionality-today/"><u>Top Remedies for When Your Laptop's USB Mouse Won't Work – Restore Functionality Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-frozen-taskbar-in-windows-11-with-these-reliable-techniques/"><u>Troubleshoot & Fix Frozen Taskbar in Windows 11 with These Reliable Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211270590-troubleshoot-file-explorer-woes-in-windows-11-expert-tips-inside/"><u>Troubleshoot File Explorer Woes in Windows 11 - Expert Tips Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-nonfunctional-usb-ports-on-windows-11/"><u>Troubleshooting and Fixing Nonfunctional USB Ports on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-overcoming-delayed-keystrokes-in-windows-10-environments/"><u>Troubleshooting and Overcoming Delayed Keystrokes in Windows 10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-freezing-issues-on-your-pc-or-laptop/"><u>Troubleshooting Guide: Resolving Freezing Issues on Your PC or Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-fixing-windows-drive-letter-not-found-errors/"><u>Understanding & Fixing Windows Drive Letter Not Found Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlock-full-potential-expert-techniques-to-restore-your-galaxy-tab-pen-functionality/"><u>Unlock Full Potential: Expert Techniques to Restore Your Galaxy Tab Pen Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206126371-why-is-my-windows-10-taking-long-to-shut-down-solutions-inside/"><u>Why Is My Windows 10 Taking Long to Shut Down? Solutions Inside</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-broken-scroll-gestures-in-windows-10s-touchpad/"><u>Winning the Battle Against Broken Scroll Gestures in Windows 10'S Touchpad</u></a></li>
</ul></div>
