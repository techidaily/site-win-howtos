---
title: "Guide: Successfully Reactivating Your Diagnostic Service"
date: 2024-08-15T11:34:23.339Z
updated: 2024-08-16T11:34:23.339Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Guide: Successfully Reactivating Your Diagnostic Service"
excerpt: "This Article Describes Guide: Successfully Reactivating Your Diagnostic Service"
thumbnail: https://thmb.techidaily.com/fce48d07017735f027e4e8ddac3c46895627ba76a949a72d045632207a784c01.jpg
---

## Diagnostic Policy Service Malfunction? Here's the Solution

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Click the **Update**  button next to a flagged network adapter driver to automatically download and install the correct version of this driver (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **Pro** version – you’ll be prompted to upgrade when you click Update All).

 Driver Easy requires network connection to update drivers. If your windows can’t access the Internet, please use the Offline Scan feature of Driver Easy to help you.

 4) After updating your network adapter driver, please restart your computer.

 5) Run the Network Diagnostics to see if it goes well.

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
<li><a href="https://win-howtos.techidaily.com/fixed-windows-10-red-screen-issue/"><u>[Fixed] Windows 10 Red Screen Issue</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-discovering-best-phone-based-asmr-experiences-for-2024/"><u>[New] Discovering Best Phone-Based ASMR Experiences for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-evaluating-whether-your-video-consumption-needs-a-subscription-boost-for-2024/"><u>[New] Evaluating Whether Your Video Consumption Needs a Subscription Boost for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elevate-your-digital-footprint-crafting-compelling-shorts-thumbnails/"><u>[New] In 2024, Elevate Your Digital Footprint  Crafting Compelling Shorts Thumbnails</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-gaming-hits-with-powerful-hashtag-strategies/"><u>[Updated] 2024 Approved  Gaming Hits with Powerful Hashtag Strategies</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-authenticity-through-customer-produced-videos/"><u>[Updated] Authenticity Through Customer-Produced Videos</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-top-zero-cost-image-amplifier-desktopmobile-edition/"><u>2024 Approved  Top Zero-Cost Image Amplifier  Desktop/Mobile Edition</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-universal-synchronization-zoom-on-phones-tablets-pcs-all/"><u>2024 Approved  Universal Synchronization  Zoom on Phones, Tablets, PCs All</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/best-practices-for-imovie-videos-entering-the-vimeo-realm-for-2024/"><u>Best Practices for iMovie Videos Entering the Vimeo Realm for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/code-fails-to-initiate/"><u>Code Fails to Initiate</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-samsung-galaxy-m34-5g-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Samsung Galaxy M34 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-guide-fixing-the-0x800705b4-issue-during-windows-10-updates/"><u>Comprehensive Guide: Fixing the 0X800705b4 Issue During Windows 10 Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/computers-nightmare-staying-in-sleep-mode/"><u>Computer's Nightmare: Staying In Sleep Mode</u></a></li>
<li><a href="https://win-howtos.techidaily.com/crack-the-code-of-warframe-update-malfunctions-now-corrected/"><u>Crack the Code of Warframe Update Malfunctions - Now Corrected</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208221241-cursor-constantly-blinks-heres-how-you-can-fix-it/"><u>Cursor Constantly Blinks? Here’s How You Can Fix It</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-correct-ps4-chat-device-sound-malfunctions-effectively/"><u>Diagnose and Correct PS4 Chat Device Sound Malfunctions Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-non-functional-touchpad-scroll-on-your-device/"><u>Easy Fixes for Non-Functional Touchpad Scroll on Your Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-alerted-overcoming-invalid-directory-naming-problems-effortlessly/"><u>Error Alerted! Overcoming Invalid Directory Naming Problems Effortlessly</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/event-ensemble-curating-best-dj-templates-for-2024/"><u>Event Ensemble  Curating Best DJ Templates for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-guide-diagnosing-and-fixing-unknown-usb-error-with-descriptor-retrieval-failures/"><u>Expert Guide: Diagnosing and Fixing 'Unknown USB' Error with Descriptor Retrieval Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-windows-update-issue-error-code-80erase00-step-by-step-guide/"><u>Fix Windows Update Issue: Error Code 80Erase00 - Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-stuck-windows-update-on-older-oss-like-win7-new-edition-tips-and-solutions-for-better-user-experience-in-the-current-decade-helpful-tips-and-guid137/"><u>How To Fix Stuck Windows Update on Older OSs Like Win7 - New Edition Tips and Solutions For Better User Experience in the Current Decade! (Helpful Tips & Guides.)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-non-working-night-mode-in-windows-10-and-11-step-by-step-guide/"><u>How To Fix The Non-Working Night Mode in Windows 10 & 11 - Step by Step Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-messages-from-xiaomi-redmi-k70-by-fonelab-android-recover-messages/"><u>How to Rescue Lost Messages from Xiaomi Redmi K70</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-xerox-printer-error-0x800f020b-on-your-windows-machine/"><u>How to Resolve Xerox Printer Error 0X800f020b on Your Windows Machine</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-solve-the-problem-of-windows-10-failing-to-recognize-your-hdmi-connected-television/"><u>How to Solve the Problem of Windows 10 Failing to Recognize Your HDMI-Connected Television</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-successfully-repair-the-server-could-not-be-contacted-by-the-client-mistake-error-0x80072efd/"><u>How To: Successfully Repair The 'Server Could Not Be Contacted By The Client' Mistake (Error 0X80072EFD)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-impact-of-authenticity-in-insta-self-portraits/"><u>In 2024, The Impact of Authenticity in Insta Self-Portraits</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/innovative-ways-to-earn-on-snapchat/"><u>Innovative Ways to Earn on Snapchat</u></a></li>
<li><a href="https://win-howtos.techidaily.com/managing-system-preferences-how-organizations-control-windows-settings/"><u>Managing System Preferences: How Organizations Control Windows Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/navigate-files-easily-on-windows-11-a-comprehensive-help-for-file-explorer-users/"><u>Navigate Files Easily on Windows 11 - A Comprehensive Help for File Explorer Users</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-vivo-s17-pro-by-fonelab-android-recover-data/"><u>Recover lost data from Vivo S17 Pro</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-fixing-the-semaphore-timeout-interval-exceeded-error-code-0x80070079/"><u>Resolved: Fixing the 'Semaphore Timeout Interval Exceeded' Error Code 0X80070079</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-critical-errors-in-cxfreeze-with-minimal-hassle/"><u>Resolving Critical Errors in Cx_Freeze with Minimal Hassle</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-of-excessive-voltage-spikes-in-your-devices-connection-point/"><u>Resolving the Issue of Excessive Voltage Spikes in Your Device's Connection Point</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-update-error-code-0x8023c401c-on-windows-10-and-11/"><u>Resolving Windows Update Error Code 0X802^3C401C on Windows 10 and 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-the-problem-of-inactive-night-light-on-your-windows-10-or-11-device-easily/"><u>Solve the Problem of Inactive Night Light on Your Windows 10 or 11 Device Easily</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-issues-with-your-lenovo-laptops-webcam-a-step-by-step-guide/"><u>Solving Issues with Your Lenovo Laptop's Webcam: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-of-wrong-letters-during-computer-inputs/"><u>Solving the Problem of Wrong Letters During Computer Inputs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-problem-windows-7-update-download-failures-a-comprehensive-guide/"><u>Solving the Problem: Windows 7 Update Download Failures - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tech-support-simplified-how-to-restore-and-repair-your-computer-or-device/"><u>Tech Support Simplified: How to Restore and Repair Your Computer or Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-how-to-correcting-no-signal-detected-by-computermonitor-problems/"><u>The Ultimate How-To: Correcting No Signal Detected by Computer/Monitor Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-trick-to-recover-any-missing-window-from-the-edge-of-sight/"><u>The Ultimate Trick to Recover Any Missing Window From the Edge of Sight</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-correct-system-error-0x887a0006-a-step-by-step-guide-to-a-swift-solution/"><u>Troubleshoot and Correct System Error 0X887A0006: A Step-by-Step Guide to a Swift Solution!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-resolve-nonfunctional-fn-key-issues-on-your-dell-laptop/"><u>Troubleshoot and Resolve Nonfunctional 'FN' Key Issues on Your Dell Laptop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-netflix-audio-trouble-with-simple-fixes/"><u>Troubleshoot Your Netflix Audio Trouble with Simple Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-correcting-windows-error-31-quickly/"><u>Troubleshooting and Correcting Windows Error 31 Quickly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-spontaneous-computer-shutdowns-effective-methods-revealed/"><u>Troubleshooting Spontaneous Computer Shutdowns - Effective Methods Revealed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-to-correct-update-error-0x8024401c-in-windows-11/"><u>Troubleshooting Steps to Correct Update Error 0X8024401C in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-to-solving-the-0x80070490-windows-updates-error-code/"><u>Ultimate Guide to Solving the 0X80070490 Windows Updates Error Code</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlocking-huge-storage-potential-with-everyday-plastic-through-cutting-edge-3d-printed-holography-storing-keys-and-addresses-efficiently/"><u>Unlocking Huge Storage Potential with Everyday Plastic Through Cutting-Edge 3D-Printed Holography - Storing Keys and Addresses Efficiently!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-the-stuck-sims-4-launch-expert-ways-to-get-back-in-action/"><u>Unstick the Stuck Sims 4 Launch - Expert Ways to Get Back in Action</u></a></li>
</ul></div>
