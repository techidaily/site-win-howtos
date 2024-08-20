---
title: Step-by-Step Tutorial to Correctly Handle Error Code 0X80072EFD in Windows 11
date: 2024-08-19T06:42:37.728Z
updated: 2024-08-20T06:42:37.728Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Tutorial to Correctly Handle Error Code 0X80072EFD in Windows 11
excerpt: This Article Describes Step-by-Step Tutorial to Correctly Handle Error Code 0X80072EFD in Windows 11
thumbnail: https://thmb.techidaily.com/ebd8fd55586bef5fe806c5a6931ae068dd25745cbaa69a714d4a27725179f8ad.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://video-capture.techidaily.com/new-in-2024-ideal-ps2-emulation-software-for-ios-users/"><u>[New] In 2024, Ideal PS2 Emulation Software for IOS Users</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-the-power-of-words-in-viral-videos-top-20-tiktok-caption-picks/"><u>[New] In 2024, The Power of Words in Viral Videos  Top 20 TikTok Caption Picks</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-provideocapture-pro-10plus-features-and-functionality-overview/"><u>[Updated] ProVideoCapture Pro 10+  Features & Functionality Overview</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleashing-potential-in-ar-applying-lut-techniques/"><u>[Updated] Unleashing Potential in AR  Applying LUT Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-the-class-not-registered-hurdle-on-windows-10-expert-tips-and-tricks/"><u>Bypassing the 'Class Not Registered' Hurdle on Windows 10: Expert Tips & Tricks</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatbot-interaction-patterns-for-realistic-discussions/"><u>Chatbot Interaction Patterns for Realistic Discussions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clear-audio-ahead-step-by-step-fixes-for-common-netflix-sound-issues/"><u>Clear Audio Ahead: Step-by-Step Fixes for Common Netflix Sound Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-stop-that-annoying-blinking-cursor-on-your-pcmac/"><u>Easy Steps to Stop That Annoying Blinking Cursor on Your PC/MAC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-remedies-to-tackle-the-0-hurdle-in-updating-windows-successfully/"><u>Effortless Remedies to Tackle the 0%% Hurdle in Updating Windows Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-dealing-with-corrupted-image-display-in-windows-1110-environments/"><u>Expert Tips for Dealing with Corrupted Image Display in Windows 11/10 Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/failed-installation-of-windows-11-1607-fixes-and-solutions/"><u>Failed Installation of Windows 11 1607: Fixes and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fatal-circuitry-issue-system-halt/"><u>Fatal Circuitry Issue: System Halt</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-synaptics-touchpad-not-scrolling-issue-in-windows-11/"><u>Fix Synaptics Touchpad Not Scrolling Issue in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-invalid-value-for-registry-error-when-opening-photos-on-windows-11/"><u>Fix: Invalid Value for Registry Error When Opening Photos on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-11-how-to-stop-your-pc-from-freezing-during-start-up/"><u>Fixing Windows 11: How to Stop Your PC From Freezing During Start-Up</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-xiaomi-redmi-note-12r-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Xiaomi Redmi Note 12R to Apple TV | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Lava Blaze 2? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-gmail-password-on-realme-10t-5g-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Realme 10T 5G Devices</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-make-your-own-vr-gear-diy-guide-for-google-cardboard-viewers/"><u>In 2024, Make Your Own VR Gear  DIY Guide for Google Cardboard Viewers</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-to-do-if-your-apple-iphone-14-plus-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>In 2024, What to do if your Apple iPhone 14 Plus has bad ESN or blacklisted IMEI?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-addressing-persistent-pauses-at-0-during-windows-updates/"><u>Mastering the Fix: Addressing Persistent Pauses at 0%% During Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimize-performance-managing-high-cpu-use-by-microsoft-defender-antivirus-in-windows-10-devices/"><u>Optimize Performance: Managing High CPU Use by Microsoft Defender Antivirus in Windows 10 Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-valorant-endless-load-troubleshooting-steps/"><u>Overcoming the Valorant Endless Load: Troubleshooting Steps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723206694721-revive-your-steelseries-arctis-5-mic-expert-solutions-to-get-it-working-again/"><u>Revive Your SteelSeries Arctis 5 Mic: Expert Solutions to Get It Working Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-correcting-the-notorious-minecraft-error-n405/"><u>Step-by-Step Guide: Correcting the Notorious Minecraft Error N405</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-non-functional-huion-stylus-top-5-quick-solutions/"><u>Troubleshoot Your Non-Functional Huion Stylus: Top 5 Quick Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-your-ps4-dualshocks-charging-issue/"><u>Troubleshooting Guide: Fixing Your PS4 Dualshock's Charging Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-permanent-100-on-windows-update/"><u>Troubleshooting Guide: Resolving Permanent 100%% on Windows Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-functioning-usb-peripherals-on-windows-7-machines/"><u>Troubleshooting Non-Functioning USB Peripherals on Windows 7 Machines</u></a></li>
</ul></div>
