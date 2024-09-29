---
title: "Troubleshooting Nonfunctional USB Ports on Windows 11: A Step-by-Step Guide"
date: 2024-09-23T00:41:29.522Z
updated: 2024-09-29T07:01:16.313Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Nonfunctional USB Ports on Windows 11: A Step-by-Step Guide"
excerpt: "This Article Describes Troubleshooting Nonfunctional USB Ports on Windows 11: A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/815d7d8c09f8175fd88f64c74fcffe4ff27128461391bb250305d7aa226764d0.jpg
---

## Troubleshooting Nonfunctional USB Ports on Windows 10/11 - Fixed

 If you find one of your USB devices on Windows 10 isn’t working, read on. Whether it’s a USB mouse, keyboard, pen drive, printer, or some other USB devices altogether, this guide should resolve your problem.

 Note that there are 5 possible solutions here. You may not need to try them all; just start at the top of the list and work your way down.

[1:**Check if the device itself is faulty**](#1)
[2:**Check your power supply**](#2)
[3: **Check your power management settings**](#3)
[4:**Check your USB device drivers**](#4)
[5:**Check your USB ports**](#5)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## **Method 1: Check if the device itself is faulty**

 If the USB device was working before you upgraded to Windows 10, it’s unlikely to be faulty. But coincidences do occur. It’s certainly_possible_ that your device just happened to die right at the same time that you upgraded Windows. So it’s best to rule that possibility out for sure before spending time on more complex troubleshooting.

 To check if the USB device is faulty, simply unplug it (‘Eject’ it if it’s a USB storage device) and plug it into another computer. If it works, the device is fine. If it doesn’t, then you’ve isolated the problem! You just need to buy a replacement.

## **Method 2: Check your power supply (laptop only)**

 Your laptop’s power supply delivers power to your USB ports. If, for some reason, it fails to do this properly, the devices plugged into those USB ports may stop working. Sometimes, this can be fixed quite simply:

1) Unplug the power supply and charger plug from your laptop

2) Restart your laptop

3) Connect your USB device to the laptop again

4) Plug the power supply back in

<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Method 3: Check your power management settings**

 In order to save power, by default, Windows switches your USB controllers off when they’re not in use, and switches them back on again when they’re needed. Unfortunately, sometimes this approach doesn’t work as intended, and Windows fails to switch your USB controllers on again.

 To rule this out as the cause of your USB woes, just stop Windows from ‘managing’ power to your USB controllers and devices:

 1) Open Device Manager (type “Device Manager” in the Windows search field)

![](https://www.drivereasy.com/wp-content/uploads/2015/11/run-devmgmt.msc_.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902309/19272" target="_top" id="1902309">
  <img src="//a.impactradius-go.com/display-ad/19272-1902309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902309/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Expand the**Universal Serial Bus controllers** branch

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430ac388d01.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902304/19272" target="_top" id="1902304">
  <img src="//a.impactradius-go.com/display-ad/19272-1902304" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902304/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Double-click the first **USB Root Hub** device in the list (if you see only one USB Root Hub device, that’s fine)  

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430af9a6bc2.png)

 4) Click the **Power Management**  tab  

![](https://images.drivereasy.com/wp-content/uploads/2016/05/img_57342d99c355a.png)

5) Un-check the **Allow the computer to turn off this device to save power**  checkbox, and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2016/05/img_57342dd22bb58.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135356/19272" target="_top" id="2135356">
  <img src="//a.impactradius-go.com/display-ad/19272-2135356" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135356/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Repeat steps 3-5 for each  USB Root Hub device in your list of Universal Serial Bus controllers

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430b577123a.png)

## **Method 4: Check your USB device drivers**

 Your USB ports not working problem is probably being caused by driver issues. The steps above may resolve it, but if they don’t, or you’re not confident playing around with drivers manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

 2) Run Driver Easy and click**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_594841d4c15c1.jpg)

 3) Click the**Update** button next to a flagged USB driver to automatically download and install the correct version of this driver (you can do this with the FREE version).

 Or click**Update All**  to automatically download and install the correct version of_all_ the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_5948dbf290aa4.jpg)

**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

## **Method 5: Check your USB ports**

 If none of the above methods resolve your problem, your USB ports might be damaged. To find out, you can take your PC to a repair store and ask them to check. If your USB ports are damaged, the repairer should be able to replace them fairly inexpensively.

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
<li><a href="https://extra-tips.techidaily.com/2024-approved-bypassing-education-tips-on-skipping-edgenuity-online-video-lessons/"><u>2024 Approved Bypassing Education Tips on Skipping Edgenuity Online Video Lessons</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-realme-11-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-techniques-for-fixing-no-light-show-a-full-how-to-for-dell-laptop-screen-issues/"><u>Expert Techniques for Fixing No Light Show: A Full How-To for Dell Laptop Screen Issues</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-vivo-g2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-missing-graphics-device-in-starcraft-2-solution-guide/"><u>How to Fix the Missing Graphics Device in StarCraft 2 – Solution Guide</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-nubia-red-magic-8s-pro-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-lava-yuva-2-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Lava Yuva 2? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/newly-released-driver-software-for-the-hp-deskjet-ink-advantage-3755-multifunctional-printer-on-windows-systems-win1087/"><u>Newly Released Driver Software for the HP DeskJet Ink Advantage 3755 Multifunctional Printer on Windows Systems (Win10/8/7)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/perpetual-screen-snapshot-for-2024/"><u>Perpetual Screen Snapshot for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-and-simple-solutions-resolve-your-netflix-audio-problems-instantly/"><u>Quick & Simple Solutions: Resolve Your Netflix Audio Problems Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-found-nvidias-geforce-software-no-longer-faces-settings-recovery-problem/"><u>Solution Found: Nvidia's GeForce Software No Longer Faces Settings Recovery Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-resolving-the-operating-system-cannot-be-detected/"><u>Troubleshooting Steps for Resolving the 'Operating System Cannot Be Detected'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-resolving-display-driver-stopped-responding-issues-on-your-computer/"><u>Understanding and Resolving ‘Display Driver Stopped Responding’ Issues on Your Computer</u></a></li>
</ul></div>

