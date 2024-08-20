---
title: "Troubleshooting Guide: When Your PC Can't Access Event Logging Services in Windows"
date: 2024-08-19T07:41:18.661Z
updated: 2024-08-20T07:41:18.661Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: When Your PC Can't Access Event Logging Services in Windows"
excerpt: "This Article Describes Troubleshooting Guide: When Your PC Can't Access Event Logging Services in Windows"
thumbnail: https://thmb.techidaily.com/4e831fd04562f2cd6825c32accd78b3641cb3be2e3ea9cbe8b25030ed7edee4b.jpg
---

## Troubleshooting Tips for Windows 10 Issues with The Duo Approach: System File Checker (SFC) and Deployment Image Servicing (DISM)

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586c9a4e6db41.jpg)

 Windows 10 is equipped with some very handy tools that allow you to solve your computer problems.**System File Checker** and**Deployment Image & Servicing Management** tools are ones of them.

You should consider using these tools when:

**a) troubleshooting a buggy Windows system;**
**b) blue screen of death errors occur;**
**c) applications crash;**
**d) some Windows features are not working properly.**

and etc.

 In this post, we will show you some tools that you can use to solve your computer problems:

[**System File Checker tool**](#1)
[**Deployment Image & Servicing Management tool**](#2)
[**System Restore**](#3)

**Run SFC Command to Repair System Files**

 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Admin)** .

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca149cf04d.png)

 When prompted with the UAC, hit**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca13144fd3.jpg)

2) In the Command Prompt window, type in the following command:

sfc /scannow

 Make sure that you have made no typo and hit**Enter** .

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca221df44e.jpg)

Leave the Command Prompt window on until the command completes.

 3) If you see the message saying that   **Windows Resource Protection did not find any integrity violations** , then everything is fine with your system.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca520c7e49.png)

 4) If you see a message saying   **Windows Resource Protection found corrupt files but was unable to fix some of them** , then you need to go to[**safe mode**](https://tools.techidaily.com/drivereasy/download/) and run the system file checker again.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca59f1f21f.jpg)

 If the SFC command doesn’t work well, please mve on to the next section to run the DISM command to fix the SFC command problem and then run SFC command again.

**Run the DISM Command to Fix SFC Problems**

**DISM** stands for Deployment Image & Servicing Management, which is a tool that can fix component store corruption that prevents the SFC command from working properly.

 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Admin)** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca149cf04d.png)

 When prompted with the UAC, hit**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca13144fd3.jpg)

2) In the Command Prompt window, type in the following command:

DISM /Online /Cleanup-Image /RestoreHealth

 Make sure you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586ca8464439b.jpg)

Wait for a while for the whole process to finishes.

 3) When the whole process finishes, restart your computer. Then run SFC command again so it will help you replace any corrupted files with the correct ones.

 **System Refresh or Reset**

 If the above tools cannot help you solve your computer problems, you can have a try at refreshing or resetting your Windows 10.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_586caacd9f489.jpg)

For more detailed information, please go to the posts below:

[**How to refresh Windows 10?**](https://tools.techidaily.com/drivereasy/download/)
[**How to reset Windows 10?**](https://tools.techidaily.com/drivereasy/download/)

**Pro Tip:**
 In many cases, most of your computer problems can be solved by updating your device drivers to their latest versions unless the problems are with the hardware, in which case, you will need to get your hardware replaced.

 To update device drivers, you can use[**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) for assistance. It automatically detects, downloads and updates your missing and outdated device drivers and allow you to finish the whole process in just a couple of minutes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e8abc65e6ec.jpg)

 If you want to have your own professional tech support and tons of other features in Driver Easy such as driver back up and driver restore, by all means, have a try at the[**professional version of Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . It allows you to update all your device drivers in just ONE click and poof, your computer problems are gone!

 You can always ask for a refund thirty days within the purchase if you are not satisfied with it. What’s with the hold up, come on and have a try at[**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) now!

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
<li><a href="https://extra-resources.techidaily.com/new-beyond-expectations-the-latest-lg-tv-bp550-review/"><u>[New] Beyond Expectations  The Latest LG TV BP550 Review</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-changing-ringtones-on-an-iphone-a-user-friendly-approach/"><u>[New] Changing Ringtones on an iPhone  A User-Friendly Approach</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-how-to-record-video-calls-on-facebook-4-methods-for-2024/"><u>[New] How to Record Video Calls on Facebook [4 Methods] for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-monetize-mastery-turning-views-into-revenue-on-vimeo-for-2024/"><u>[New] Monetize Mastery  Turning Views Into Revenue on Vimeo for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-the-world-of-photo-reshaping/"><u>[New] Navigating the World of Photo Reshaping</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-access-all-instagram-video-content-with-free-online-and-os-compatible-exporters-for-2024/"><u>[Updated] Access All Instagram Video Content with Free Online and OS-Compatible Exporters for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-building-a-brand-on-instagram-establishing-a-business-entity/"><u>[Updated] Building a Brand on Instagram  Establishing a Business Entity</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-creating-compelling-youtube-live-content-with-wirecast/"><u>[Updated] In 2024, Creating Compelling Youtube Live Content with WireCast</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-narrowing-down-to-top-8-exceptional-online-platforms-for-free-srt-for-2024/"><u>[Updated] Narrowing Down to Top 8 Exceptional Online Platforms for Free SRT for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-precision-in-perspective-mastery-of-youtube-video-degrees-for-2024/"><u>[Updated] Precision in Perspective  Mastery of Youtube Video Degrees for 2024</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/10-top-rated-software-solutions-to-fix-and-revive-your-digital-images-on-pc-and-macos/"><u>10 Top-Rated Software Solutions to Fix and Revive Your Digital Images on PC & macOS</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-ace-your-gift-shopping-the-ultimate-guide-to-selecting-specialty-stores/"><u>2024 Approved  Ace Your Gift Shopping  The Ultimate Guide to Selecting Specialty Stores</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-strategies-to-acquire-top-notch-hdr-cameras/"><u>2024 Approved  Strategies to Acquire Top-Notch HDR Cameras</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unlocking-the-secrets-of-selecting-a-powerful-podcast-name/"><u>2024 Approved  Unlocking the Secrets of Selecting a Powerful Podcast Name</u></a></li>
<li><a href="https://win-howtos.techidaily.com/answered-troubleshooting-directx-device-instantiation-mishap/"><u>Answered: Troubleshooting DirectX Device Instantiation Mishap</u></a></li>
<li><a href="https://vp-tips.techidaily.com/become-a-selfie-pro-10-premium-free-ios-camera-apps-for-2024/"><u>Become a Selfie Pro  10 Premium, Free iOS Camera Apps for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/bidding-on-shadows-the-2023-virtual-vault-showdown/"><u>Bidding on Shadows  The 2023 Virtual Vault Showdown</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-solutions-to-fix-your-stuck-touchpad-scroll-wheel/"><u>Comprehensive Solutions to Fix Your Stuck Touchpad Scroll Wheel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-walkthrough-to-correct-file-path-not-found-in-windows/"><u>Comprehensive Walkthrough to Correct 'File Path Not Found' In Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-repairing-elevated-cpu-load-from-windows-update-host-wu-dll-in-windows-11/"><u>Diagnosing and Repairing Elevated CPU Load From Windows Update Host (Wu-Dll) in Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-steps-to-get-the-latest-sound-blaster-z-drivers-compatible-with-windows-11/"><u>Easy Steps to Get the Latest Sound Blaster Z Drivers Compatible with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723210011861-expert-solutions-for-windows-users-with-unresponsive-usb-input-gear-mice-and-keyboards-made-functional-again/"><u>Expert Solutions for Windows ^Users with Unresponsive USB Input Gear – Mice and Keyboards Made Functional Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-how-to-successfully-resolve-and-prevent-windows-update-error-0x8024401c-in-windows-10-and-11-os/"><u>Expert Tips: How to Successfully Resolve and Prevent Windows Update Error 0X8024401c in Windows 10 & 11 OS</u></a></li>
<li><a href="https://techidaily.com/exploring-tencentclouds-latest-release-an-exclusive-os-tailored-for-chinese-cpu-chips-including-huawei-kunpeng-and-sugon-hygon/"><u>Exploring TencentCloud’s Latest Release – An Exclusive OS Tailored for Chinese CPU Chips Including Huawei Kunpeng and Sugon Hygon</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-window-10-sluggish-shutdown-problems-simple-solutions/"><u>Fix Your Window 10 Sluggish Shutdown Problems - Simple Solutions</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-lenovo-screen-glare-reduction-mistakes/"><u>Fixing Lenovo Screen Glare Reduction Mistakes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-endless-loop-windows-update-stuck-on-100-percent-solution-inside/"><u>Fixing the Endless Loop: Windows Update Stuck on 100 Percent - Solution Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-frozen-prepare-to-configure-phase-on-your-windows-device-now-resolved/"><u>Fixing the Frozen Prepare-to-Configure Phase on Your Windows Device - Now Resolved</u></a></li>
<li><a href="https://win-howtos.techidaily.com/geforce-experience-wont-open-issue-solved/"><u>GeForce Experience Won't Open Issue [Solved]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-break-free-from-continuous-restarting-in-windows-operating-systems/"><u>How to Break Free From Continuous Restarting in Windows Operating Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-correctly-configure-unidentified-audio-output-devices-on-windows-11-systems/"><u>How to Correctly Configure Unidentified Audio Output Devices on Windows 11 Systems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-photos-from-motorola-edge-2023-by-fonelab-android-recover-photos/"><u>How to get back lost photos from Motorola Edge 2023.</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oneplus-11-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from OnePlus 11 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-complete-analysis-of-theta-ss-advanced-tech/"><u>In 2024, Complete Analysis of Theta S's Advanced Tech</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-guide-to-closer-insight-in-roblox-games/"><u>In 2024, The Ultimate Guide to Closer Insight in Roblox Games</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-xiaomi-redmi-note-12-4g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Xiaomi Redmi Note 12 4G Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-eliminate-error-code-0x800f081f-for-seamless-net-framework-t-35-installation/"><u>Mastering the Fix: Eliminate Error Code 0X800F081F for Seamless .NET Framework T 3.5 Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-usb-dropout-effective-strategies-for-stable-connectivity-fixes/"><u>Overcoming USB Dropout: Effective Strategies for Stable Connectivity Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issues-with-vital-components-of-the-windows-update-system/"><u>Resolved Issues with Vital Components of the Windows Update System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-the-perplexing-code-28-issue-on-your-windows-device-manager/"><u>Resolved: Fixing the Perplexing 'Code 28' Issue on Your Windows Device Manager</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restore-missing-desktop-icons-on-windows-11-a-comprehensive-guide/"><u>Restore Missing Desktop Icons on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restoring-mouse-pointer-visibility-issues-on-windows-11-expert-fixes/"><u>Restoring Mouse Pointer Visibility Issues on Windows 11: Expert Fixes</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-fixing-the-non-functional-fortnite-microphone-step-by-step-guide/"><u>Solved: Fixing the Non-Functional Fortnite Microphone – Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-fixes-for-a-malfunctioning-laptop-touch-pad-across-different-windows-versions/"><u>Step-by-Step Fixes for a Malfunctioning Laptop Touch Pad Across Different Windows Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-laptop-battery-woes-rapid-repair-techniques-for-non-charging-issues/"><u>Stop Laptop Battery Woes - Rapid Repair Techniques for Non-Charging Issues</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/stop-the-loop-of-uninstalling-hardware-drivers-by-nvidia/"><u>Stop the Loop of Uninstalling Hardware Drivers by Nvidia</u></a></li>
<li><a href="https://win-howtos.techidaily.com/stop-the-popping-resolving-crackle-sound-problems-in-windows-operating-systems/"><u>Stop the Popping: Resolving Crackle Sound Problems in Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/surpassing-hurdles-in-nvidia-installation-woes/"><u>Surpassing Hurdles in NVIDIA Installation Woes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/svchostexe-overload-in-windows-11-diagnosis-and-efficient-fixes-revealed/"><u>svchost.exe Overload in Windows 11: Diagnosis and Efficient Fixes Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/system-recovery-halted-fixing-the-persistent-windows-11-error-0x80070091-during-system-restore/"><u>System Recovery Halted: Fixing the Persistent Windows 11 Error 0X80070091 During System Restore</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackling-obs-screenshots-and-captures-the-ultimate-fix-for-black-image-dilemmas/"><u>Tackling OBS Screenshots and Captures - The Ultimate Fix for Black Image Dilemmas</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-right-click-issues-on-a-mouse-with-windows-11/"><u>Troubleshooting Guide: Fixing Right-Click Issues on a Mouse with Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-non-functional-function-key-issues-on-your-asus-laptop/"><u>Troubleshooting Non-Functional Function Key Issues on Your ASUS Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-dealing-with-unresponsive-numeric-keys/"><u>Troubleshooting Tips: Dealing with Unresponsive Numeric Keys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-teredo-did-not-make-the-cut-a-comprehensive-breakdown/"><u>Why Teredo Did Not Make the Cut: A Comprehensive Breakdown</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-user-guide-fixing-hosted-wi-fi-connection-startup-failures/"><u>Windows 10 User Guide: Fixing Hosted Wi-Fi Connection Startup Failures</u></a></li>
</ul></div>
