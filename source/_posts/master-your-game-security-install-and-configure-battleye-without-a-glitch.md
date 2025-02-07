---
title: Master Your Game Security - Install and Configure BattlEye Without a Glitch
date: 2025-02-02T20:58:28.232Z
updated: 2025-02-07T04:19:51.943Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Master Your Game Security - Install and Configure BattlEye Without a Glitch
excerpt: This Article Describes Master Your Game Security - Install and Configure BattlEye Without a Glitch
thumbnail: https://thmb.techidaily.com/aea0b058dad5a8a78b7176f739897c106c85c82d6e617b0cdb68b3405d4743da.png
---

## LSA Safety Measures Fully Operational Again - Secure Your System Now

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Then see if the Local Security Authority Protection is still off.

 If so, please download the installation file for KB5007651 from[here](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5007651) , then double-click the installation file to get it installed.

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-25.png)

 If the “Local Security protection is off” notification is still there when you manually install the KB5007651 update, please move on to the next fix.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-how-to-feature-music-on-instant-stories-for-2024/"><u>[New] How to Feature Music on Instant Stories for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/he-ultimate-guide-to-valorant-video-thumbnail-artistry-for-2024/"><u>[New] The Ultimate Guide to Valorant Video Thumbnail Artistry for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-dissecting-the-difference-360-video-and-vr-filmmaking/"><u>[Updated] In 2024, Dissecting the Difference 360 Video and VR Filmmaking</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-best-mac-video-software-alternatives-to-bandicam/"><u>2024 Approved Best Mac Video Software Alternatives to Bandicam</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-discovering-the-creme-de-la-gaming-crowd-on-tiktok/"><u>2024 Approved Discovering the Crème De La Gaming Crowd on TikTok</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avoid-common-errors-top-5-strategies-to-restore-touchscreen-functionality-on-windows-11/"><u>Avoid Common Errors: Top 5 Strategies to Restore Touchscreen Functionality on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diy-solution-reviving-your-hp-laptops-camera-under-windows-10-compatibility/"><u>DIY Solution: Reviving Your HP Laptop's Camera Under Windows 10 Compatibility</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-on-repairing-an-hp-laptop-with-a-defective-usb-port/"><u>Expert Tips on Repairing an HP Laptop with a Defective USB Port</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-malfunctioning-mic-on-windows-11/"><u>How to Fix a Malfunctioning Mic on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-windows-11-night-mode-problems-step-by-step-solution/"><u>How to Resolve Windows 11 Night Mode Problems – Step-by-Step Solution</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-vivo-y56-5g-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Vivo Y56 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigating-the-challenges-of-library-loading-fixing-loadlibrary-failed-and-error-code-n/"><u>Navigating the Challenges of Library Loading - Fixing 'LoadLibrary Failed' And Error Code N</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/navigating-toms-hardware-informed-reviews-for-savvy-gadget-enthusiasts/"><u>Navigating Tom's Hardware: Informed Reviews for Savvy Gadget Enthusiasts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/no-light-adjustment-in-windows-os/"><u>No Light Adjustment in Windows OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/perfecting-presence-zooming-past-background-imperfections-for-2024/"><u>Perfecting Presence Zooming Past Background Imperfections for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-audio-glitches-speaker-issues-on-windows-operating-systems-solved/"><u>Resolving Audio Glitches: Speaker Issues on Windows Operating Systems Solved</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-updating-your-graphics-card-drivers-in-windows-11/"><u>Step-by-Step Guide: Updating Your Graphics Card Drivers in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-vivo-v29e-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Vivo V29e Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-buildings-wont-load-in-pubg-gaming-smooth-as-ever/"><u>Troubleshoot and Fix 'Buildings Won't Load' In PUBG - Gaming Smooth as Ever</u></a></li>
</ul></div>

