---
title: Remedy for Dxgi.dll Failure in PUBG
date: 2024-10-15T17:44:33.051Z
updated: 2024-10-21T20:44:30.823Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Remedy for Dxgi.dll Failure in PUBG
excerpt: This Article Describes Remedy for Dxgi.dll Failure in PUBG
thumbnail: https://thmb.techidaily.com/b7b1a27d1ec7d492ee38fae4ae064cccff7a07bb81d0c83c83f67196d92674a7.jpg
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Then see if the Local Security Authority Protection is still off.

 If so, please download the installation file for KB5007651 from[here](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5007651) , then double-click the installation file to get it installed.

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-25.png)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148639/16836" target="_top" id="2148639">
  <img src="//a.impactradius-go.com/display-ad/16836-2148639" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148639/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the “Local Security protection is off” notification is still there when you manually install the KB5007651 update, please move on to the next fix.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043603/7443" target="_top" id="2043603">
  <img src="//a.impactradius-go.com/display-ad/7443-2043603" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043603/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037355/7443" target="_top" id="2037355">
  <img src="//a.impactradius-go.com/display-ad/7443-2037355" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037355/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151865/7443" target="_top" id="2151865">
  <img src="//a.impactradius-go.com/display-ad/7443-2151865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151865/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-videos.techidaily.com/new-8-best-mirrorless-cameras-vloggers-should-know/"><u>[New] 8 Best Mirrorless Cameras Vloggers Should Know</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-full-examination-of-djis-drone-inspire-1/"><u>[Updated] Full Examination of DJI's Drone, Inspire 1</u></a></li>
<li><a href="https://win-howtos.techidaily.com/addressing-invisible-network-connections-fixing-wi-fi-on-your-windows-11-pc/"><u>Addressing Invisible Network Connections: Fixing Wi-Fi on Your Windows 11 PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/android-to-apple-how-to-transfer-photos-from-samsung-galaxy-f54-5g-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Android to Apple How To Transfer Photos From Samsung Galaxy F54 5G to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-to-accelerate-windows-7-boot-times/"><u>Effective Solutions to Accelerate Windows 7 Boot Times</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-unresponsive-usb-ports-in-windows-11-for-better-performance/"><u>How to Repair Unresponsive USB Ports in Windows 11 for Better Performance</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-samsung-galaxy-s23-tactical-edition-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Samsung Galaxy S23 Tactical Edition to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-repair-of-microsofts-infamous-80072ee2-update-failure/"><u>Mastering the Repair of Microsoft's Infamous 80072EE2 Update Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-11-stealthy-hiding-of-linguistic-signal/"><u>Mastering Window 11: Stealthy Hiding of Linguistic Signal</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/maximizing-returns-through-mobile-discount-codes-smart-strategies-with-massmail-technology/"><u>Maximizing Returns Through Mobile Discount Codes - Smart Strategies with Massmail Technology</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211384422-nba-2k21-bug-fixed-no-more-green-mishap/"><u>NBA 2K21 Bug Fixed: No More Green Mishap!</u></a></li>
<li><a href="https://extra-hints.techidaily.com/omnipresent-overture-the-virtual-cinema/"><u>Omnipresent Overture The Virtual Cinema</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/the-ultimate-guide-to-starting-your-pc-with-windows-11-on-a-flash-drive-expert-techniques-and-proven-tips/"><u>The Ultimate Guide to Starting Your PC with Windows 11 on a Flash Drive: Expert Techniques & Proven Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-code-24-overcoming-the-device-unavailable-problem-in-windows-operating-systems-wsten-to-win7/"><u>Troubleshoot Code 24: Overcoming the 'Device Unavailable' Problem in Windows Operating Systems WS_TEN to Win7</u></a></li>
<li><a href="https://vp-tips.techidaily.com/troubleshooting-disneyplus-login-issues-how-to-resolve-unrecognized-subscription-problems/"><u>Troubleshooting Disney+ Login Issues: How to Resolve Unrecognized Subscription Problems</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-failed-iphone-app-installations-a-comprehensive-guide/"><u>Troubleshooting Failed iPhone App Installations: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-overcoming-windows-connectivity-issues-with-the-event-notifier-service/"><u>Troubleshooting Guide: Overcoming Windows Connectivity Issues with the Event Notifier Service</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-pvpnet-lol-patcher-when-the-kernel-wont-boot-up-anymore/"><u>Troubleshooting PvP.net LOL Patcher - When the Kernel Won't Boot Up Anymore</u></a></li>
<li><a href="https://win-howtos.techidaily.com/vcruntime140dll-missing-program-cant-start-on-windows-11-solved/"><u>VCRUNTIME140.dll Missing, Program Can't Start on Windows 11 [Solved]</u></a></li>
</ul></div>

