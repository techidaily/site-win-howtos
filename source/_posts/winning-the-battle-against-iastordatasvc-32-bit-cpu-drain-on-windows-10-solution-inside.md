---
title: Winning the Battle Against IAStorDataSvc (32 Bit) CPU Drain on Windows 10 [Solution Inside]
date: 2024-08-19T06:57:09.834Z
updated: 2024-08-20T06:57:09.834Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Winning the Battle Against IAStorDataSvc (32 Bit) CPU Drain on Windows 10 [Solution Inside]
excerpt: This Article Describes Winning the Battle Against IAStorDataSvc (32 Bit) CPU Drain on Windows 10 [Solution Inside]
thumbnail: https://thmb.techidaily.com/ad251382f0a7d8c655d1ecfe442682eca929097f4c42dbd9921ea0eb3f9c12b0.jpg
---

## Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

Now try to install Windows Updates now.

After the fixes above, Windows Update should be good to go now.

* [Windows Update](/tag-search/?tagId=62)


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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-easy-youtube-introduction-design-tips-and-tricks/"><u>[New] 2024 Approved  Easy YouTube Introduction Design  Tips and Tricks</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-storyboard-to-screenplay-a-youtube-video-writers-journey/"><u>[New] 2024 Approved  From Storyboard to Screenplay  A YouTube Video Writer's Journey</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-mastering-visual-enhancements-with-polarrs-platform/"><u>2024 Approved  Mastering Visual Enhancements with Polarr's Platform</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-step-by-step-guide-to-ace-11-essential-color-correction-tutorials/"><u>2024 Approved  Step-by-Step Guide to Ace 11 Essential Color Correction Tutorials</u></a></li>
<li><a href="https://win-howtos.techidaily.com/acer-quiet-mode-dilemma-solved-bring-back-the-boom-with-easy-fixes/"><u>Acer Quiet Mode Dilemma Solved: Bring Back the Boom with Easy Fixes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/blending-beats-and-imagery-music-tips-for-instagram-for-2024/"><u>Blending Beats and Imagery  Music Tips for Instagram for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/connect-microsoft-display-adapter-to-windows-10-successfully-a-comprehensive-fix/"><u>Connect Microsoft Display Adapter to Windows 10 Successfully – A Comprehensive Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhance-visuals-on-windows-10-a-guide-to-resolving-pixelated-characters-and-text/"><u>Enhance Visuals on Windows 10: A Guide to Resolving Pixelated Characters & Text</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-how-to-bypass-preparing-to-configure-windows-dilemma/"><u>Fixed! How to Bypass 'Preparing to Configure Windows' Dilemma</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-nonfunctional-laptop-trackpad-on-windows-11-8-and-7-expert-solutions/"><u>Fixing a Nonfunctional Laptop Trackpad on Windows 11, 8 & 7 – Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-error-code-0x8024200d-successful-resolution-of-windows-update-issues/"><u>Fixing Error Code 0X8024200D: Successful Resolution of Windows Update Issues</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-unregistered-class-errors-in-windows-11-efficiently/"><u>How to Fix Unregistered Class Errors in Windows 11 Efficiently</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-13-pro-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 13 Pro System? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-stop-windows-10-from-stuck-on-looping-system-recovery-mode-and-constant-restarts/"><u>How to Stop Windows 10 From Stuck on Looping System Recovery Mode and Constant Restarts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-stop-your-pc-from-continuously-restarting-on-win-11-and-win-10/"><u>How to Stop Your PC From Continuously Restarting on Win 11 and Win 10</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-narzo-n55-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Realme Narzo N55 Phone without Any Data Loss</u></a></li>
<li><a href="https://win-howtos.techidaily.com/identifying-and-resolving-high-sound-levels-in-your-ps4-system/"><u>Identifying & Resolving High Sound Levels in Your PS4 System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/immediate-solutions-stop-counter-strike-go-from-crashing-now/"><u>Immediate Solutions: Stop Counter-Strike Go From Crashing Now!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-itel-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Itel S23+ | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-the-ultimate-framework-perfecting-live-broadcasts-via-obs-and-zoom/"><u>In 2024, The Ultimate Framework  Perfecting Live Broadcasts via OBS & Zoom</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-fixes-for-error-8007000e-during-windows-updates/"><u>Mastering Fixes for Error 8007000E During Windows Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-troubleshooting-steps-for-failed-windows-10-may-2019-version-updates/"><u>Resolved: Troubleshooting Steps for Failed Windows 10 May 2019 Version Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-resolved-fixes-for-non-functional-hardware-connected-to-your-computer/"><u>Successfully Resolved: Fixes for Non-Functional Hardware Connected to Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-troubleshooting-unresponsive-google-chrome-expert-advice-and-solutions/"><u>Successfully Troubleshooting Unresponsive Google Chrome: Expert Advice & Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/tackle-common-dll-errors-proven-fixes-for-windows-users-expert-guide/"><u>Tackle Common Dll Errors: Proven Fixes for Windows Users [Expert Guide]</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/time-savers-screen-recording-on-instagrams-story-for-2024/"><u>Time Savers  Screen Recording on Instagram's Story for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-resolving-failed-initialization-of-newly-fixed-renderer-features/"><u>Troubleshooting and Resolving Failed Initialization of Newly Fixed Renderer Features</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-fixed-video-file-cannot-be-displayed-error-code-224003/"><u>Troubleshooting Guide for Fixed 'Video File Cannot Be Displayed' Error (Code #224003)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-device-detection-issues-in-windows-10s-bluetooth/"><u>Troubleshooting Guide: Fixing Device Detection Issues in Windows 10'S Bluetooth</u></a></li>
<li><a href="https://win-howtos.techidaily.com/understanding-and-correcting-the-libraries-loaderror-code-1114-on-pcs/"><u>Understanding and Correcting the Libraries LoadError (Code: 1114) on PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unstick-your-frozen-steam-software-enhancement-with-these-simple-tips/"><u>Unstick Your Frozen Steam Software Enhancement with These Simple Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-curbing-unwanted-processes/"><u>Windows 10: Curbing Unwanted Processes</u></a></li>
</ul></div>
