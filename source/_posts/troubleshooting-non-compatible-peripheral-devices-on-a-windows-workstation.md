---
title: Troubleshooting Non-Compatible Peripheral Devices on a Windows Workstation
date: 2025-01-08T16:22:30.689Z
updated: 2025-01-13T16:15:16.699Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Non-Compatible Peripheral Devices on a Windows Workstation
excerpt: This Article Describes Troubleshooting Non-Compatible Peripheral Devices on a Windows Workstation
thumbnail: https://thmb.techidaily.com/f78a12d6fa260b60593d7d84df0572fbc03e543ca8c86ab396fe09af56299ebf.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Method 3: Check your power management settings**

 In order to save power, by default, Windows switches your USB controllers off when they’re not in use, and switches them back on again when they’re needed. Unfortunately, sometimes this approach doesn’t work as intended, and Windows fails to switch your USB controllers on again.

 To rule this out as the cause of your USB woes, just stop Windows from ‘managing’ power to your USB controllers and devices:

 1) Open Device Manager (type “Device Manager” in the Windows search field)

![](https://www.drivereasy.com/wp-content/uploads/2015/11/run-devmgmt.msc_.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Expand the**Universal Serial Bus controllers** branch

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430ac388d01.png)

 3) Double-click the first **USB Root Hub** device in the list (if you see only one USB Root Hub device, that’s fine)  

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430af9a6bc2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Click the **Power Management**  tab  

![](https://images.drivereasy.com/wp-content/uploads/2016/05/img_57342d99c355a.png)

5) Un-check the **Allow the computer to turn off this device to save power**  checkbox, and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2016/05/img_57342dd22bb58.png)

 6) Repeat steps 3-5 for each  USB Root Hub device in your list of Universal Serial Bus controllers

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430b577123a.png)

## **Method 4: Check your USB device drivers**

 Your USB ports not working problem is probably being caused by driver issues. The steps above may resolve it, but if they don’t, or you’re not confident playing around with drivers manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

 2) Run Driver Easy and click**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_594841d4c15c1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click the**Update** button next to a flagged USB driver to automatically download and install the correct version of this driver (you can do this with the FREE version).

 Or click**Update All**  to automatically download and install the correct version of_all_ the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_5948dbf290aa4.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-docs.techidaily.com/n-2024-ryans-wealth-wonders-a-kids-fortune-in-the-streaming-space/"><u>[New] In 2024, Ryan’s Wealth Wonders A Kid's Fortune in the Streaming Space</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-step-by-step-guide-to-nba-streaming-top-15-essentials/"><u>[New] In 2024, Step-by-Step Guide to NBA Streaming - Top 15 Essentials</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ey-elements-in-asmr-video-content/"><u>[New] Key Elements in ASMR Video Content</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-brighten-your-video-with-android-tricks-for-2024/"><u>[Updated] Brighten Your Video with Android Tricks for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723014956804-counter-strike-2-mic-not-functional-heres-your-step-by-step-fix/"><u>Counter-Strike 2 Mic Not Functional? Here's Your Step-by-Step Fix</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-update-drivers-for-canon-mg3600-printer/"><u>Download and Update Drivers for Canon MG3600 Printer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/find-the-start-button-on-windows-10/"><u>Find The Start Button on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/finding-companion-cameras-for-windows-hello-effortlessly/"><u>Finding Companion Cameras for Windows Hello Effortlessly</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-perfecting-cgi-in-depth-tutorial-for-kinemaster-users/"><u>In 2024, Perfecting CGI In-Depth Tutorial for Kinemaster Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-steam-missing-files-issue-regain-your-full-game-access/"><u>Solving the Steam Missing Files Issue: Regain Your Full Game Access</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fix-for-ce-34878-0-playstation-4-error-message-updated-solution/"><u>Step-by-Step Fix for CE-34878-0 Playstation 4 Error Message [UPDATED SOLUTION]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-tutorial-getting-your-windows-optical-drives-back-to-working-order/"><u>Step-by-Step Tutorial: Getting Your Windows Optical Drives Back to Working Order</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/the-ultimate-guide-how-to-securely-retrieve-youtube-captions/"><u>The Ultimate Guide: How to Securely Retrieve YouTube Captions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-a-malfunctioning-shift-key-proven-fixes-you-can-apply-today/"><u>Troubleshooting a Malfunctioning Shift Key - Proven Fixes You Can Apply Today!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-a-hanging-or-stuck-windows-10-computer/"><u>Troubleshooting Tips for a Hanging or Stuck Windows 10 Computer</u></a></li>
</ul></div>

