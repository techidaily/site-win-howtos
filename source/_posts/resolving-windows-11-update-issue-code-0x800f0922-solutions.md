---
title: Resolving Windows 11 Update Issue - Code 0X800F0922 Solutions
date: 2024-08-19T06:46:06.050Z
updated: 2024-08-20T06:46:06.050Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Windows 11 Update Issue - Code 0X800F0922 Solutions
excerpt: This Article Describes Resolving Windows 11 Update Issue - Code 0X800F0922 Solutions
thumbnail: https://thmb.techidaily.com/db587631bccc11018e71b0f197be1378b7d1dbbecd5a463368074dbdb88b8238.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://extra-tips.techidaily.com/new-capturing-the-cloudline-in-your-backyard-the-revolutionary-dji-spark-unveiled/"><u>[New] Capturing the Cloudline in Your Backyard  The Revolutionary DJI Spark Unveiled</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-cutting-edge-final-cut-pros-best-10-plugins/"><u>[New] Cutting Edge  Final Cut Pro's Best 10 Plugins</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-depth-look-at-fraps-screen-capture/"><u>[New] In-Depth Look at Fraps Screen Capture</u></a></li>
<li><a href="https://win-howtos.techidaily.com/restart-computer-at-games-command/"><u>[RESTART] Computer At Game's Command</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-airborne-cameras-clash-dji-inspire-vs-gopro-max/"><u>[Updated] Airborne Cameras Clash  DJI Inspire vs GoPro MAX</u></a></li>
<li><a href="https://win-howtos.techidaily.com/deciphering-teredo-tunneling-errors-strategies-for-effective-troubleshooting/"><u>Deciphering Teredo Tunneling Errors: Strategies for Effective Troubleshooting</u></a></li>
<li><a href="https://win-howtos.techidaily.com/display-problem-alert-current-refresh-rate-is-unsupported-by-your-screen/"><u>Display Problem Alert: Current Refresh Rate Is Unsupported by Your Screen</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/easy-steps-on-how-to-create-a-new-apple-id-account-on-iphone-xs-drfone-by-drfone-ios/"><u>Easy Steps on How To Create a New Apple ID Account On iPhone XS | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-resolve-your-cs-go-game-crashes-fast/"><u>Easy Steps to Resolve Your CS: GO Game Crashes Fast</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-eliminating-screen-flickering-in-valorant/"><u>Effective Solutions for Eliminating Screen Flickering in VALORANT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-when-system-cant-access-required-modules/"><u>Effective Solutions for When System Can’t Access Required Modules</u></a></li>
<li><a href="https://driver-install.techidaily.com/execute-hp-envy-5530-drivers-on-windows/"><u>Execute HP Envy 5530 Drivers on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-overcoming-wow-stuttering-problems/"><u>Expert Advice on Overcoming WOW Stuttering Problems</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-strategies-for-swift-and-smooth-media-navigation/"><u>Expert Strategies for Swift and Smooth Media Navigation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fast-acting-fixes-to-overcome-windows-update-error-0x80070652/"><u>Fast-Acting Fixes to Overcome Windows Update Error 0X80070652</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-windows-10-troubleshooting-non-functional-right-click-on-your-mouse/"><u>Fixing Windows 10: Troubleshooting Non-Functional Right Click on Your Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-chrome-plugin-failure-to-load-errors-on-windows-10-an-expert-walkthrough/"><u>How To Fix 'Chrome Plugin Failure to Load' Errors On Windows 10: An Expert Walkthrough</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-solutions-to-revive-your-unresponsive-logitech-keyboard/"><u>Immediate Solutions to Revive Your Unresponsive Logitech Keyboard</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-dynamic-backdrop-customization-in-teammate-windows-prepost-calls/"><u>In 2024, Dynamic Backdrop Customization in Teammate Windows, Pre/Post Calls</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-vital-tips-to-preserve-lol-competitions/"><u>In 2024, Vital Tips to Preserve LOL Competitions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/nocturnal-pc-error-wake-refusal-in-windows/"><u>Nocturnal PC Error - Wake Refusal in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/overcoming-facebook-algorithm-change-hurdles-for-2024/"><u>Overcoming Facebook Algorithm Change Hurdles for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-hdcp-limitations-on-your-display-unit-a-guide-to-enhanced-performance/"><u>Overcoming HDCP Limitations on Your Display Unit - A Guide to Enhanced Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-issues-with-windows-event-log-services-connection-problems/"><u>Overcoming Issues with Windows Event Log Services Connection Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/repairing-your-lenovos-unresponsive-mouse-pad-in-different-windows-environments-1187-expert-fixes/"><u>Repairing Your Lenovo's Unresponsive Mouse Pad in Different Windows Environments (11/8/7) - Expert Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-fixing-cannot-initialize-directx-graphics-driver-error/"><u>Solution Steps: Fixing 'Cannot Initialize DirectX Graphics Driver' Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solved-how-to-fix-a-computer-that-cant-close-windows-10/"><u>Solved: How to Fix a Computer That Can't Close Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-correcting-forbidden-responses-http-error-403-in-web-servers/"><u>Troubleshooting and Correcting 'Forbidden' Responses (HTTP Error ⁩ 403) in Web Servers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-resolving-power-surge-issues-in-your-usb-ports-on-windows-10/"><u>Troubleshooting Guide: Resolving 'Power Surge' Issues in Your USB Ports on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-a-non-responsive-windows-10-computer/"><u>Troubleshooting Steps for a Non-Responsive Windows 10 Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-fixed-youtube-sounds-problem-under-windows-11-system/"><u>Troubleshooting the Fixed YouTube Sounds Problem Under Windows 11 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-why-your-pc-wont-update-windows-easy-fixes-inside/"><u>Troubleshooting: Why Your PC Won't Update Windows – Easy Fixes Inside!</u></a></li>
</ul></div>
