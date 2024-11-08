---
title: "Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
date: 2024-11-05T22:46:53.735Z
updated: 2024-11-08T05:05:58.493Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
excerpt: "This Article Describes Windows 1N Update Issue Resolved: Eliminating Error Code 0X80240034"
thumbnail: https://thmb.techidaily.com/d44c84cbf0699642eded061365e62aa884811112a5aa8ff88c8335f623b0d0e8.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-crafting-content-gold-youtube-studios-path-to-perfection/"><u>[New] 2024 Approved Crafting Content Gold YouTube Studio's Path to Perfection</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-perfect-shots-effortless-streaming-dslr-on-pcmac/"><u>[New] In 2024, Perfect Shots, Effortless Streaming DSLR on PC/Mac</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-skyline-secrets-expert-iphone-landscape-tips-unveiled/"><u>[Updated] 2024 Approved Skyline Secrets Expert iPhone Landscape Tips Unveiled</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-resolved-managing-delayed-service-response-overcoming-error-1053/"><u>Error Resolved: Managing Delayed Service Response, Overcoming Error 1053</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-wwe-2k-battlegrounds-dx11-feature-level-100-error/"><u>Fix WWE 2K Battlegrounds DX11 Feature Level 10.0 Error</u></a></li>
<li><a href="https://article-tips.techidaily.com/how-to-use-supplemental-video-sequences-effectively/"><u>How to Use Supplemental Video Sequences Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/master-the-art-of-dealing-with-windows-error-code-31-easy-fixes-inside/"><u>Master the Art of Dealing with Windows' Error Code 31: Easy Fixes Inside</u></a></li>
<li><a href="https://fox-blue.techidaily.com/maximize-your-spotify-campaign-roi-an-expert-guide-for-2024/"><u>Maximize Your Spotify Campaign ROI - An Expert Guide for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-infinix-hot-30-5g-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Infinix Hot 30 5G? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/pubg-2024-issue-resolution-expert-guidelines-for-launching-and-playing-without-glitches/"><u>PUBG 2024 Issue Resolution: Expert Guidelines for Launching and Playing Without Glitches</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-resolving-your-unrecognizable-usb-flash-drive/"><u>Quick Solutions: Resolving Your Unrecognizable USB Flash Drive</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-rainbow-six-sieges-latency-problems-a-step-by-step-guide/"><u>Resolving Rainbow Six Siege's Latency Problems - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-resolving-issues-with-your-logitech-mouses-scroll-function/"><u>Troubleshooting Tips: Resolving Issues with Your Logitech Mouse's Scroll Function</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-11-fixing-unresponsive-keys-on-your-pc/"><u>Troubleshooting Windows 11: Fixing Unresponsive Keys on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fixes-for-minecrafts-persistent-error-code-5-problems/"><u>Ultimate Fixes for Minecraft's Persistent Error Code ^5 Problems</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-error-in-updates-code-0x8019/"><u>Unblocking Error in Updates: Code 0X8019</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unlocking-the-potential-of-budget-4k-televisions-the-lg-um7300-49-inch-screen-review/"><u>Unlocking the Potential of Budget 4K Televisions: The LG UM7300 49-Inch Screen Review</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

