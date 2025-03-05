---
title: "Reinvigorate Your Device's Internal Shield: Local Security Authority Features Fully Operational Now"
date: 2025-03-03T18:44:12.824Z
updated: 2025-03-05T19:49:42.289Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Reinvigorate Your Device's Internal Shield: Local Security Authority Features Fully Operational Now"
excerpt: "This Article Describes Reinvigorate Your Device's Internal Shield: Local Security Authority Features Fully Operational Now"
thumbnail: https://thmb.techidaily.com/f8511b1b508552460f630419c51d2d616ebcbf19dbd124bdf2e50582d197ea31.jpg
---

## LSA Safety Measures Fully Operational Again - Secure Your System Now

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-24.png)

Local Security Authority Protection is off

 No need to worry if your Local Security Authority Protection is toggled off: in most cases, it was a UI bug with a certain Windows update patch, meaning that it’s not off, just appears to be off, and you can install another update patch to get it fixed. In other rare cases, you can change your computer settings to get it enabled again. Read on and see how you can fix the Local Security Authority Protection being off problem.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.

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

![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-premier-mac-studio-for-high-quality-recordings-for-2024/"><u>[New] Premier Mac Studio for High-Quality Recordings for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-blueprint-of-visual-communication-instavideo-marketing-mastery-for-2024/"><u>[New] The Blueprint of Visual Communication InstaVideo Marketing Mastery for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-optimize-your-videos-with-these-top-rated-editor-suites/"><u>[Updated] In 2024, Optimize Your Videos with These Top-Rated Editor Suites</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-innovating-highest-quality-canon-sequences-for-2024/"><u>[Updated] Innovating Highest Quality Canon Sequences for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corrected-error-unresponsive-buttons-on-keyboard/"><u>Corrected Error: Unresponsive Buttons on Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-windows-host-service-interruption-rundll32/"><u>Effective Solutions for Windows Host Service Interruption (Rundll32)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-unpleasant-image-malfunction-in-windows-10-and-11/"><u>Fixing the Unpleasant Image Malfunction in Windows 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-missing-desktop-icons-on-windows-11-a-comprehensive-guide/"><u>How to Fix Missing Desktop Icons on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-solution-for-battery-not-working-problems/"><u>Immediate Solution for 'Battery Not Working' Problems</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-secret-technique-for-instantaneous-deletion-of-youtube-discussions/"><u>In 2024, The Secret Technique for Instantaneous Deletion of Youtube Discussions</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-guide-to-converting-speech-to-text-with-google-docs/"><u>In 2024, The Ultimate Guide to Converting Speech to Text with Google Docs</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/maximizing-connectivity-with-the-asus-ax6000-the-ultimate-wi-fi-6-router-review-for-modern-homes/"><u>Maximizing Connectivity with the Asus AX6000 - The Ultimate Wi-Fi 6 Router Review for Modern Homes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/minecraft-not-starting-on-windows-troubleshooting-steps-resolved/"><u>Minecraft Not Starting on Windows: Troubleshooting Steps [RESOLVED]</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-photos-during-transfer-from-iphone-15-pro-max-to-pc-or-mac-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Recover Lost Photos during Transfer from iPhone 15 Pro Max to PC or Mac | Stellar</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-stuck-at-getting-windows-ready-issue-step-by-step-guide/"><u>Resolving 'Stuck at Getting Windows Ready' Issue: Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlock-the-solution-end-window-11-and-10s-infinite-restart-cycle-now/"><u>Unlock the Solution: End Window 11 and 10'S Infinite Restart Cycle Now!</u></a></li>
</ul></div>

