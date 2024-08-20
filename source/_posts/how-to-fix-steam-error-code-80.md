---
title: How to Fix Steam Error Code 80
date: 2024-08-19T06:30:12.304Z
updated: 2024-08-20T06:30:12.304Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Steam Error Code 80
excerpt: This Article Describes How to Fix Steam Error Code 80
thumbnail: https://thmb.techidaily.com/5c0564abc19ad999dbb49e540552fe121e13db8ef37145c72c3f59363b043c6a.jpg
---

## .NET Framework 3.5 Installation Woes? Here's How to Fix Error Code 0X800F081F

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8a7b95c3a7.png)

 If you are seeing an error code**0x800F081F** when you try to install .NET Framework 3.5 on your Windows computer, you are not alone. Many Windows users are reporting it. But the good news is you can fix this error. Here are two fixes you can try:

 Method 1:[**Configure Group Policy**](https://tools.techidaily.com/drivereasy/download/)
 Method 2:[**Install .NET Framework 3.5 using DISM**](https://tools.techidaily.com/drivereasy/download/)

## Method 1: Configure Group Policy

 The 0x800F081F error may occur because the component setting in Group Policy is disabled. You should enable it to see if this fixes the error. To do so:

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
**1)** On your keyboard, press the   **Windows logo key![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png)**  and**R** **key** at the same time to invoke the Run box.

**2)**  Type “**gpedit.msc** ” and press**Enter** on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8b46182da0.png)

**3)**  Go to **Computer Configuration -> Administrative Templates -> System** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8b4b628c80.jpg)

**4)** Double click **Specify settings for optional component installation and component repair** .

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8cb90d9ace.jpg)

**5)** Select**Enabled** . Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8cd1538e66.jpg)

**6)** Try installing .NET Framework 3.5\. If this method works for you, you won’t see the error again. Otherwise, you should try the method below.

## Method 2: Enable the .NET Framework 3.5 feature using DISM

 It is also possible that the error occurs because the .NET Framework 3.5 feature has not been enabled in your system. You can use a DISM command to enable it.

**NOTE** : You need to have installation media or an ISO image for your Windows version to perform this method.

To enable the .NET Framework 3.5 feature using DISM:

**1)** Put the Windows installation media into your computer, or mount the Windows ISO image in your system.

**2)** Press the**Windows logo key** on your keyboard. Then type “**_cmd_** “.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b7455a57b7b.png)

**3)** Right-click “**Command Prompt** ” and select “**Run as administrator** “.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b75954000f6.png)

**4)** Type “ _**Dism /online /enable-feature /featurename:NetFx3 /All /Source:**_ **<DRIVE>** _**:\\sources\\sxs /LimitAccess**_ ” and press**Enter** on your keyboard. (Note that you need to replace the**<DRIVE>** here with the drive letter for the installation media drive or the ISO drive.)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8d9fc19402.png)

**5)**  Try installing .NET Framework 3.5 and see if the error disappears.

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-learn-to-turn-comments-on-or-off-on-youtube-easily/"><u>[New] 2024 Approved  Learn to Turn Comments On or Off on YouTube Easily</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-partitioned-presence-ranking-splittest-cam/"><u>[New] 2024 Approved  Partitioned Presence  Ranking Splittest Cam</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-best-book-trailers-for-impact/"><u>[New] Best Book Trailers for Impact</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-elevate-your-snapchat-creativity-with-these-6-editors/"><u>[New] Elevate Your Snapchat Creativity with These 6 Editors</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-much-income-arises-from-each-snapshot-video-for-2024/"><u>[New] How Much Income Arises From Each Snapshot (Video) for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-adjusting-google-meet-display-mobile-and-laptop-focus/"><u>[New] In 2024, Adjusting Google Meet Display  Mobile and Laptop Focus</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/nlocking-the-art-of-alluring-youtube-live-image-creation-for-2024/"><u>[New] Unlocking the Art of Alluring YouTube Live Image Creation for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-5-best-360-degree-action-cameras-you-should-use/"><u>[Updated] 5 Best 360-Degree Action Cameras You Should Use</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-unlocking-online-potential-essential-fb-advice-for-businesses/"><u>[Updated] In 2024, Unlocking Online Potential  Essential FB Advice for Businesses</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-top-10-innovative-tweets-de-followers-and-cleanup-apps/"><u>[Updated] Top 10 Innovative Tweets De-Followers & Cleanup Apps</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-structuring-stimulating-podcast-trailers/"><u>2024 Approved  Structuring Stimulating Podcast Trailers</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-honor-magic-6-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Honor Magic 6 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-the-annoying-keeps-showing-up-a-comprehveiw-on-solving-usb-recognition-problems/"><u>Beat the Annoying Keeps Showing Up: A Comprehveiw on Solving USB Recognition Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beat-the-everlasting-flash-tips-and-tricks-for-controlling-your-cursor/"><u>Beat The Everlasting Flash: Tips and Tricks for Controlling Your Cursor</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/boundless-savings-for-your-captured-moments-for-2024/"><u>Boundless Savings for Your Captured Moments for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-guide-troubleshooting-and-repairing-your-malfunctioning-xbox-one-controller/"><u>Complete Guide: Troubleshooting and Repairing Your Malfunctioning Xbox One Controller</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-solve-incorrect-module-data-for-a-stable-gaming-experience/"><u>Diagnose And Solve 'Incorrect Module Data' For a Stable Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-techniques-to-repair-camera-not-working-on-a-lenovo-device/"><u>Effective Techniques to Repair Camera Not Working on a Lenovo Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enable-bluetooth-connectivity-on-your-windows/"><u>Enable Bluetooth Connectivity on Your Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-reinstate-webcam-usage-on-your-hp-device-with-windows-11/"><u>Expert Advice: Reinstate Webcam Usage on Your HP Device with Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/exploring-photodnas-purpose-and-mechanics/"><u>Exploring PhotoDNA's Purpose & Mechanics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-windows-update-error-code-8007000e-fast-simple-solutions/"><u>Fix Windows Update Error Code 80#07000E - Fast, Simple Solutions</u></a></li>
<li><a href="https://win-blog.techidaily.com/fix-your-gaming-experience-dead-space-remake-launch-issues-resolved-updated-guide/"><u>Fix Your Gaming Experience: Dead Space Remake Launch Issues Resolved (Updated Guide )</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-honor-magic-vs-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-shockwave-flash-issues-are-fixed-on-google-chrome-for-a-smoother-experience/"><u>How Shockwave Flash Issues Are Fixed on Google Chrome for a Smoother Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-ethernet-not-working-issues-on-windows-11-and-7/"><u>How to Fix Ethernet Not Working Issues on Windows 11 & 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-when-your-backspace-key-isnt-functioning-correctly/"><u>How to Resolve When Your Backspace Key Isn't Functioning Correctly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-right-click-capabilities-on-your-windows-10-system/"><u>How to Restore Right-Click Capabilities on Your Windows 10 System</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-oppo-a78-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Oppo A78 to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-samsung-galaxy-a25-5g-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Samsung Galaxy A25 5G FRP</u></a></li>
<li><a href="https://win-howtos.techidaily.com/lenovo-keyboard-malfunction-heres-how-you-can-resolve-it/"><u>Lenovo Keyboard Malfunction? Here's How You Can Resolve It!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-pairing-with-windows-10-solutions-to-fix-persistent-bluetooth-connections/"><u>Master Pairing with Windows 10: Solutions to Fix Persistent Bluetooth Connections</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-reviving-unresponsive-ps4-controllers-charge-restoration-steps-inside/"><u>Master the Art of Reviving Unresponsive PS4 Controllers: Charge Restoration Steps Inside</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-sound-of-facts-decoding-digital-audio-workstation-concepts-for-2024/"><u>New The Sound of Facts Decoding Digital Audio Workstation Concepts for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-torrent-download-failures-effective-strategies-and-solutions/"><u>Overcoming Torrent Download Failures: Effective Strategies and Solutions</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-videos-from-honor-x8b-by-fonelab-android-recover-video/"><u>Possible solutions to restore deleted videos from Honor X8b</u></a></li>
<li><a href="https://win-howtos.techidaily.com/qualification-issues-persist-for-teredo-projects/"><u>Qualification Issues Persist for Teredo Projects</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fix-for-err-too-many-redirects-easy-steps-inside/"><u>Quick Fix for ERR TOO MANY REDIRECTS – Easy Steps Inside!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-how-to-repair-a-non-functioning-huion-stylus/"><u>Quick Solutions: How To Repair A Non-Functioning Huion Stylus</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repairing-damaged-registry-entries-in-windows-10-and-11-a-step-by-step-guide/"><u>Repairing Damaged Registry Entries in Windows 10 & 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-puzzle-of-windows-update-failure-error-0x80240017-unraveled/"><u>Solving the Puzzle of Windows Update Failure - Error 0X80240017 Unraveled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-nplus1-access-denied-when-listing-items-inside-containers-issue-easy-steps-and-tips/"><u>Solving Windows N+1: Access Denied When Listing Items Inside Containers Issue - Easy Steps and Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-based-minecraft-startup-problems-a-step-by-step-guide-solved/"><u>Solving Windows-Based Minecraft Startup Problems: A Step-by-Step Guide [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-resolving-the-livekernelevent-code-117-issue/"><u>Step-by-Step Guide: Resolving the LiveKernelEvent Code 117 Issue</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-oppo-reno-8t-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Oppo Reno 8T Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fix-for-a-non-functioning-print-screen-on-windows-operating-systems/"><u>The Ultimate Fix for a Non-Functioning Print Screen on Windows Operating Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-solutions-for-fixing-excessive-cpu-use-by-svchostexe-on-windows-11-systems/"><u>Top Solutions for Fixing Excessive CPU Use by svchost.exe on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-fix-solve-no-pen-or-touch-controls-on-your-screen/"><u>Troubleshooting Fix: Solve 'No Pen or Touch Controls' On Your Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-reactivating-wireless-connectivity-on-devices/"><u>Troubleshooting Guide: Reactivating Wireless Connectivity on Devices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-keyboard-delay-issues-in-windows-10-effective-solutions-applied/"><u>Troubleshooting Keyboard Delay Issues in Windows 10: Effective Solutions Applied</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-the-d3d932dll-not-found-problem/"><u>Troubleshooting Steps for the d3d9_32.dll Not Found Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-laptop-microphone-issues-a-comprehensive-guide/"><u>Troubleshooting Your Laptop Microphone Issues - A Comprehensive Guide</u></a></li>
</ul></div>
