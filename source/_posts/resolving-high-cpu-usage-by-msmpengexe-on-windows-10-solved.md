---
title: Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved
date: 2024-08-15T11:29:03.730Z
updated: 2024-08-16T11:29:03.730Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved
excerpt: This Article Describes Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved
thumbnail: https://thmb.techidaily.com/59bb6881bb451ab6f15e5a33afa6f776cb1ec0282754802f441bb66f0c3a3719.jpg
---

## Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved

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
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/-step-by-step-guide-for-earning-with-youtube-shorts-for-2024/"><u>[New] A Step-by-Step Guide for Earning with YouTube Shorts for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-surprise-uncovered-secrets-to-take-your-window-11-experience-up-a-notch-for-2024/"><u>[New] Surprise! Uncovered Secrets to Take Your WINDOW 11 Experience Up a Notch for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-invisible-stories-unveiled-a-complete-snapguide/"><u>[Updated] In 2024, Invisible Stories Unveiled  A Complete Snapguide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-mastering-mac-lecture-recording-techniques/"><u>[Updated] In 2024, Mastering Mac  Lecture Recording Techniques</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-depth-analysis-of-altering-facial-gender-on-social-platforms-for-2024/"><u>[Updated] In-Depth Analysis of Altering Facial Gender on Social Platforms for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-video-creation-journey-from-adobe-premiere-to-youtube/"><u>[Updated] Video Creation Journey  From Adobe Premiere to YouTube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/answered-troubleshooting-directx-device-instantiation-mishap/"><u>Answered: Troubleshooting DirectX Device Instantiation Mishap</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-to-fix-your-stuck-touchpad-scroll-wheel/"><u>Comprehensive Solutions to Fix Your Stuck Touchpad Scroll Wheel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210011861-expert-solutions-for-windows-users-with-unresponsive-usb-input-gear-mice-and-keyboards-made-functional-again/"><u>Expert Solutions for Windows ^Users with Unresponsive USB Input Gear – Mice and Keyboards Made Functional Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-how-to-successfully-resolve-and-prevent-windows-update-error-0x8024401c-in-windows-10-and-11-os/"><u>Expert Tips: How to Successfully Resolve and Prevent Windows Update Error 0X8024401c in Windows 10 & 11 OS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/fixing-overencoded-obs-videos/"><u>Fixing Overencoded OBS Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/geforce-experience-wont-open-issue-solved/"><u>GeForce Experience Won't Open Issue [Solved]</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-tecno-spark-10-pro-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Tecno Spark 10 Pro Phone | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-break-free-from-continuous-restarting-in-windows-operating-systems/"><u>How to Break Free From Continuous Restarting in Windows Operating Systems</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-samsung-galaxy-f14-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Samsung Galaxy F14 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-crafting-convincing-movie-markers/"><u>In 2024, Crafting Convincing Movie Markers</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-still-using-pattern-locks-with-nokia-xr21-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Nokia XR21? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-eliminate-error-code-0x800f081f-for-seamless-net-framework-t-35-installation/"><u>Mastering the Fix: Eliminate Error Code 0X800F081F for Seamless .NET Framework T 3.5 Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-usb-dropout-effective-strategies-for-stable-connectivity-fixes/"><u>Overcoming USB Dropout: Effective Strategies for Stable Connectivity Fixes</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/positive-interaction-not-pressure-a-subscription-success-story/"><u>Positive Interaction, Not Pressure  A Subscription Success Story</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issues-with-vital-components-of-the-windows-update-system/"><u>Resolved Issues with Vital Components of the Windows Update System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-the-perplexing-code-28-issue-on-your-windows-device-manager/"><u>Resolved: Fixing the Perplexing 'Code 28' Issue on Your Windows Device Manager</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-missing-desktop-icons-on-windows-11-a-comprehensive-guide/"><u>Restore Missing Desktop Icons on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-a-malfunctioning-laptop-touch-pad-across-different-windows-versions/"><u>Step-by-Step Fixes for a Malfunctioning Laptop Touch Pad Across Different Windows Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-laptop-battery-woes-rapid-repair-techniques-for-non-charging-issues/"><u>Stop Laptop Battery Woes - Rapid Repair Techniques for Non-Charging Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-the-popping-resolving-crackle-sound-problems-in-windows-operating-systems/"><u>Stop the Popping: Resolving Crackle Sound Problems in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/surpassing-hurdles-in-nvidia-installation-woes/"><u>Surpassing Hurdles in NVIDIA Installation Woes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/svchostexe-overload-in-windows-11-diagnosis-and-efficient-fixes-revealed/"><u>svchost.exe Overload in Windows 11: Diagnosis and Efficient Fixes Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/system-recovery-halted-fixing-the-persistent-windows-11-error-0x80070091-during-system-restore/"><u>System Recovery Halted: Fixing the Persistent Windows 11 Error 0X80070091 During System Restore</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-right-click-issues-on-a-mouse-with-windows-11/"><u>Troubleshooting Guide: Fixing Right-Click Issues on a Mouse with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-functional-function-key-issues-on-your-asus-laptop/"><u>Troubleshooting Non-Functional Function Key Issues on Your ASUS Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-dealing-with-unresponsive-numeric-keys/"><u>Troubleshooting Tips: Dealing with Unresponsive Numeric Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-teredo-did-not-make-the-cut-a-comprehensive-breakdown/"><u>Why Teredo Did Not Make the Cut: A Comprehensive Breakdown</u></a></li>
</ul></div>
