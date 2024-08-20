---
title: "Security Reactivation Successful: Confirm Your System's Shield Is Onboard"
date: 2024-08-19T07:50:50.816Z
updated: 2024-08-20T07:50:50.816Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Security Reactivation Successful: Confirm Your System's Shield Is Onboard"
excerpt: "This Article Describes Security Reactivation Successful: Confirm Your System's Shield Is Onboard"
thumbnail: https://thmb.techidaily.com/e2a22d0e1eb69e31073b9f86edc15bd17dc9ed7433f25f15297fff8ea322d744.jpg
---

## Critical LSA Shield Fully Operational: Revamp Your System's Local Security Today

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

## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

 Then see if your Local Security Authority protection can be toggled back on.

---

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Bonus tip

 If turning on the Local Security Authority protection doesn’t help to fix your computer problems, you can always try to repair any damaged or corrupted system files, as**the integrity of Windows system files is** essential for proper operation and stability for your computer.

 Tools like **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  can automate the repair process by scanning system files and replacing corrupted ones.

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect. It will run a free scan of your PC and give you**a detailed report of your PC status** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-scan.jpg)
3. Once finished, you’ll see a report showing all the issues. To fix all the issues automatically, click**Start Repair** (You’ll need to purchase the full version. It comes with a**60-day Money-Back Guarantee** so you can refund anytime if Fortect doesn’t fix your problem).  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-choosing-the-best-portable-microphones-for-macos-users/"><u>[New] 2024 Approved  Choosing the Best Portable Microphones for MacOS Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-sound-capture-in-windows-11/"><u>[New] Mastering Sound Capture in Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-top-mp4-to-facebook-video-converter-2023-edition/"><u>[New] Top MP4-to-Facebook Video Converter 2023 Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-how-to-fix-red-screen-of-death/"><u>[SOLVED] How To Fix Red Screen of Death</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-live-broadcast-essentials-for-macos-users-on-mixer-for-2024/"><u>[Updated] Live Broadcast Essentials for macOS Users on Mixer for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-facebook-covers-made-easy-top-10-online-design-services-reviewed/"><u>2024 Approved  Facebook Covers Made Easy  Top 10 Online Design Services Reviewed</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-igniting-laughter-a-path-to-meme-fame/"><u>2024 Approved  Igniting Laughter  A Path to Meme Fame</u></a></li>
<li><a href="https://vp-tips.techidaily.com/5-tools-to-make-a-gif-meme-for-2024/"><u>5 Tools to Make a GIF Meme for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/boosting-windows-7-boot-times-expert-troubleshooting-tips/"><u>Boosting Windows 7 Boot Times: Expert Troubleshooting Tips</u></a></li>
<li><a href="https://video-capture.techidaily.com/capturing-the-world-in-iphone-slow-motion-for-2024/"><u>Capturing the World in iPhone Slow Motion for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-how-to-address-and-fix-msvcr110dll-absence-issue/"><u>Comprehensive Solutions: How to Address and Fix MSVCR110.dll Absence Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-tutorial-on-restoring-connected-audiovideo-settings-in-windows/"><u>Comprehensive Tutorial on Restoring Connected Audio/Video Settings in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-windows-11-bluetooth-connectivity-errors-for-smooth-device-pairing/"><u>Diagnosing & Repairing Windows 11 Bluetooth Connectivity Errors for Smooth Device Pairing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-dealing-with-a-frozen-pointing-device-on-your-computer-system/"><u>Expert Advice: Dealing with a Frozen Pointing Device on Your Computer System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/five-effective-techniques-to-repair-a-malfunctioning-screen-on-windows-11/"><u>Five Effective Techniques to Repair a Malfunctioning Screen on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-frozen-fun-with-simple-tricks/"><u>Fix Your Frozen Fun with Simple Tricks</u></a></li>
<li><a href="https://driver-error.techidaily.com/guiding-users-through-driver-troubleshooting-dm/"><u>Guiding Users Through Driver Troubleshooting (DM)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-and-correct-cyclic-redundancy-check-discrepancies-successfully/"><u>How to Address and Correct Cyclic Redundancy Check Discrepancies Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-the-ineteresourcenotfound-error-in-your-projects/"><u>How to Address the INET_E_RESOURCE_NOT_FOUND Error in Your Projects</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-access-is-denied-error-windows-11-cannot-list-containers/"><u>How to Fix 'Access Is Denied' Error: Windows 11 Cannot List Containers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-notorious-code-28-error-in-windows-device-manager-a-step-by-step-guide/"><u>How to Fix the Notorious 'Code 28' Error in Windows Device Manager: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-seamlessly-play-fallout-4-diagnosing-and-fixing-lag-issues/"><u>How to Seamlessly Play Fallout 4 : Diagnosing and Fixing Lag Issues</u></a></li>
<li><a href="https://fox-helps.techidaily.com/innovating-your-reality-essential-vr-peripherals-guide-for-2024/"><u>Innovating Your Reality  Essential VR Peripherals Guide for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/mastering-video-capture-on-hangouts-for-2024/"><u>Mastering Video Capture on Hangouts for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-disk-read-error-challenge-in-windows-11-effective-techniques-explored/"><u>Overcoming the 'Disk Read Error' Challenge in Windows 11 – Effective Techniques Explored</u></a></li>
<li><a href="https://tech-hub.techidaily.com/protecting-your-assets-the-potential-of-chatgpt-as-a-weapon-in-cybercriminals-arsenal/"><u>Protecting Your Assets: The Potential of ChatGPT as a Weapon in Cybercriminals' Arsenal</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pure-summer-magic-the-top-10-classic-kids-films/"><u>Pure Summer Magic  The Top 10 Classic Kid's Films</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-your-windows-hurdles-and-complications/"><u>Quick Fixes for Your Windows Hurdles & Complications!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-numeric-keyboard-a-step-by-nstep-fix-for-non-working-digits/"><u>Revive Your Numeric Keyboard: A Step-by-nStep Fix for Non-Working Digits</u></a></li>
<li><a href="https://program-issues.techidaily.com/solved-fixing-fall-guys-stuttering-and-lag-issues-in-pc-version/"><u>Solved: Fixing Fall Guys Stuttering and Lag Issues in PC Version</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-device-detection-errors-a-guide-for-bluetooth-in-windows-10/"><u>Solving Device Detection Errors: A Guide for Bluetooth in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-riddle-of-the-green-glitch-in-nba-2k21-a-comprehensive-guide/"><u>Solving the Riddle of the Green Glitch in NBA 2K21 - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-11-usb-connectivity-issues-quick-fixes-and-tips/"><u>Solving Windows 11 USB Connectivity Issues: Quick Fixes and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-correct-chromes-errnetworkchanged-or-similar-issues/"><u>Step-by-Step Guide to Correct Chrome's ERR_NETWORK_CHANGED or Similar Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-get-your-non-responsive-chrome-back-on-track/"><u>Troubleshooting: Get Your Non-Responsive Chrome Back on Track</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-microsoft-telemetry-overwhelms-storage-on-your-windows-10-machine/"><u>Troubleshooting: Microsoft Telemetry Overwhelms Storage on Your Windows 10 Machine</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-top-10-song-recorder-that-you-wont-want-to-miss/"><u>Updated In 2024, Top 10 Song Recorder That You Wont Want to Miss</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-tone-generation-made-simple-5-online-tools/"><u>Updated Tone Generation Made Simple 5 Online Tools</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723204299790-why-is-my-razer-keyboard-not-lights-fix-and-prevent-this-common-problem/"><u>Why Is My Razer Keyboard Not Lights? Fix and Prevent This Common Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-against-unresponsive-file-explorer-on-your-windows-11-system-solution/"><u>Winning Against Unresponsive File Explorer on Your Windows 11 System [Solution]</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/youtube-cash-growth-forecasts-at-no-cost-for-2024/"><u>YouTube Cash Growth Forecasts at No Cost for 2024</u></a></li>
</ul></div>
