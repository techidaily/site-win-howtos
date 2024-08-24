---
title: Local Safeguard Protocols Need Activation – Action Steps Inside
date: 2024-08-23T14:02:42.689Z
updated: 2024-08-24T14:02:42.689Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Local Safeguard Protocols Need Activation – Action Steps Inside
excerpt: This Article Describes Local Safeguard Protocols Need Activation – Action Steps Inside
thumbnail: https://thmb.techidaily.com/b95ff97ef31c24150b8b202a85720fb4906b9c98a9f5fb5115fa67b8c7b12e76.jpg
---

## Local Safeguard Protocols Need Activation – Action Steps Inside

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

![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-18.png)
2. Click**Check for updates** , and Windows will scan for any available updates.  
![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-19.png)
3. If there are available updates, Windows will automatically download them for you. Restart your computer for the update to take effect if needed.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-20.png)
4. If there are_no_ available updates, you’ll see**You’re up to date** like this.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-21.png)

Then see if the Local Security Authority Protection is still off.

 If so, please download the installation file for KB5007651 from[here](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5007651) , then double-click the installation file to get it installed.

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-25.png)

 If the “Local Security protection is off” notification is still there when you manually install the KB5007651 update, please move on to the next fix.

---

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

 Then see if your Local Security Authority protection can be toggled back on.

---

## Bonus tip

 If turning on the Local Security Authority protection doesn’t help to fix your computer problems, you can always try to repair any damaged or corrupted system files, as**the integrity of Windows system files is** essential for proper operation and stability for your computer.

 Tools like **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  can automate the repair process by scanning system files and replacing corrupted ones.

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect. It will run a free scan of your PC and give you**a detailed report of your PC status** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-scan.jpg)
3. Once finished, you’ll see a report showing all the issues. To fix all the issues automatically, click**Start Repair** (You’ll need to purchase the full version. It comes with a**60-day Money-Back Guarantee** so you can refund anytime if Fortect doesn’t fix your problem).  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
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
<li><a href="https://vp-tips.techidaily.com/new-illustrating-brilliance-the-most-trusted-vector-tools-reviewed-for-2024/"><u>[New] Illustrating Brilliance  The Most Trusted Vector Tools Reviewed for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-masterful-traffic-puller-genius/"><u>[New] Masterful Traffic Puller Genius</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-of-decreasing-audio-intensity-in-logic-pro/"><u>[New] The Art of Decreasing Audio Intensity in Logic Pro</u></a></li>
<li><a href="https://win-howtos.techidaily.com/audio-service-halted-in-win-11-solution-provided/"><u>Audio Service Halted in Win 11, Solution Provided</u></a></li>
<li><a href="https://win-howtos.techidaily.com/best-practices-for-handling-system-level-resource-contention-issues/"><u>Best Practices for Handling System-Level Resource Contention Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/breaking-down-nvidia-installation-blockers/"><u>Breaking Down NVIDIA Installation Blockers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-repair-resolving-issues-with-internet-explorer-malfunctions/"><u>DIY Repair: Resolving Issues with Internet Explorer Malfunctions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-solutions-stop-your-laptop-from-falling-asleep-unexpectedly/"><u>Effortless Solutions: Stop Your Laptop From Falling Asleep Unexpectedly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-fix-overcoming-the-obstacle-of-code-0x800f081f-when-setting-up-net-framework-v35/"><u>Error Fix: Overcoming the Obstacle of Code 0X800F081F When Setting up .NET Framework V3.5</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-pc-errors-with-ease-solving-the-d3dx939dll-file-not-found-issue/"><u>Fix Your PC Errors with Ease: Solving The d3dx9_39.dll File Not Found Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-functional-mic-issue-in-windows-11-solutions-guide/"><u>Fixing a Non-Functional Mic Issue in Windows 11 - Solutions Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-on-iphone-6-plus-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email On iPhone 6 Plus? Heres the Best Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-and-fix-a-type-144-livekernelerror/"><u>How To Address and Fix a Type 144 LiveKernelError</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-adjust-display-settings-when-encountered-with-non-standard-input-delays/"><u>How to Adjust Display Settings When Encountered With Non-Standard Input Delays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-prevent-your-pc-from-going-off-mid-game-tips-for-windows-users/"><u>How to Prevent Your PC From Going Off Mid-Game: Tips for Windows Users</u></a></li>
<li><a href="https://program-issues.techidaily.com/improving-gameplay-smoothness-overcoming-stutters-and-increasing-fps-on-valorant/"><u>Improving Gameplay Smoothness - Overcoming Stutters and Increasing FPS on Valorant</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-5-solutions-for-tecno-spark-10-5g-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Tecno Spark 10 5G Unlock Without Password</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-solution-for-overcoming-fatal-errors-in-software-installs-error-1603-included/"><u>Master Solution for Overcoming Fatal Errors in Software Installs, Error 1603 Included</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-oculus-hardware-maintenance-avoid-and-fix-the-top-errors-of-2024/"><u>Mastering Oculus Hardware Maintenance: Avoid and Fix the Top Errors of 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-auditory-delights-in-cinema-celebrating-the-best-8-film-soundscapes-for-2024/"><u>New Auditory Delights in Cinema - Celebrating the Best 8 Film Soundscapes for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-elevate-your-storytelling-a-step-by-step-ken-burns-effect-tutorial-for-2024/"><u>New Elevate Your Storytelling A Step-by-Step Ken Burns Effect Tutorial for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-update-failed-with-error-0x80240017-expert-strategies-revealed/"><u>Overcoming 'Windows Update Failed with Error 0X80240017': Expert Strategies Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-windows-11s-audio-glitches-expert-tips-for-fixing-broken-volume-control/"><u>Overcoming Windows 11'S Audio Glitches: Expert Tips for Fixing Broken Volume Control</u></a></li>
<li><a href="https://extra-support.techidaily.com/perfect-your-photos-with-text-tips-for-adding-titles-in-microsoft-photos-for-2024/"><u>Perfect Your Photos with Text  Tips for Adding Titles in Microsoft Photos for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/pinnacle-playtime-the-greatest-action-adventure-game-lineup-ever-for-2024/"><u>Pinnacle Playtime  The Greatest Action-Adventure Game Lineup Ever for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolve-the-stuck-startup-a-users-manual-for-windows-preparing-glitches-on-computers/"><u>Resolve the Stuck Startup: A User's Manual for Windows Preparing Glitches on Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-a-broken-start-menu-on-windows-11-step-by-step-tips-and-tricks/"><u>Reviving a Broken Start Menu on Windows 11 - Step-by-Step Tips & Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-network-error-0x800704cf-a-step-by-step-guide/"><u>Solving Windows Network Error 0X800704CF: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-a-step-by-step-guide-to-restoring-usb-port-functionality/"><u>Windows 11: A Step-by-Step Guide to Restoring USB Port Functionality</u></a></li>
</ul></div>
