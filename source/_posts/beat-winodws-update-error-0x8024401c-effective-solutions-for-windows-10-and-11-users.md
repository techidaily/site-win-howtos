---
title: "Beat Winodws Update Error 0X8024401c: Effective Solutions for Windows 10 & 11 Users"
date: 2024-08-23T14:09:40.610Z
updated: 2024-08-24T14:09:40.610Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Beat Winodws Update Error 0X8024401c: Effective Solutions for Windows 10 & 11 Users"
excerpt: "This Article Describes Beat Winodws Update Error 0X8024401c: Effective Solutions for Windows 10 & 11 Users"
thumbnail: https://thmb.techidaily.com/bab37a5357094e09dd42f37d3cc78e25fe907bbcf4a7b3121bebc119dc83e730.jpg
---

## Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

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
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
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
<li><a href="https://win-howtos.techidaily.com/fixed-code-28-error-in-device-manager-in-windows/"><u>[Fixed] Code 28 Error in Device Manager in Windows</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-ace-your-gameplay-innovative-tvs-to-boost-your-xbox-series-x-adventure-for-2024/"><u>[New] Ace Your Gameplay  Innovative TVs to Boost Your Xbox Series X Adventure for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-beat-boulevard-optimal-dj-video-downloads-for-2024/"><u>[New] Beat Boulevard  Optimal DJ Video Downloads for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-precision-flight-the-new-era-with-yuneec-drone-review/"><u>[New] In 2024, Precision Flight  The New Era with Yuneec Drone Review</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-step-by-written-by-john-smith-phd/"><u>[New] Step-By Written by John Smith, PhD</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-render-your-social-media-footage/"><u>[Updated] 2024 Approved  Render Your Social Media Footage</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-best-of-mobile-8-ranked-free-and-premium-apps-for-androids-video-tiles/"><u>[Updated] Best of Mobile  #8 Ranked Free & Premium Apps for Android's Video Tiles</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-leading-edge-technology-selecting-15-ultimate-cameras/"><u>[Updated] In 2024, Leading Edge Technology  Selecting 15 Ultimate Cameras</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-window-wisdom-taking-precise-screen-captures-for-2024/"><u>[Updated] Window Wisdom  Taking Precise Screen Captures for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-quintessential-14-text-motion-design-examples/"><u>2024 Approved  Quintessential 14 Text Motion Design Examples</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-radiance-hdr-examined-value-or-not/"><u>2024 Approved  Radiance HDR Examined  Value or Not?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/but-investors-are-still-buying-stocks-because-they-expect-strong-corporate-profits-and-rising-economic-growth-over-the-next-six-months-to-drive-further-gain149/"><u>But Investors Are Still Buying Stocks because They Expect Strong Corporate Profits and Rising Economic Growth over the Next Six Months to Drive Further Gains</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-deceptive-alerts-solve-google-chromes-fraudulent-critical-error-problem/"><u>Bypassing Deceptive Alerts: Solve Google Chrome's Fraudulent Critical Error Problem</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpts-boundaries-explored-unanswerable-questions-and-tasks-in-focus/"><u>ChatGPT's Boundaries Explored: Unanswerable Questions and Tasks in Focus</u></a></li>
<li><a href="https://extra-tips.techidaily.com/creating-magnetic-storylines-for-your-vlog-videos/"><u>Creating Magnetic Storylines for Your Vlog Videos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-steps-to-resolve-continuous-system-freezing-on-your-laptop-or-desktop/"><u>Easy Steps to Resolve Continuous System Freezing on Your Laptop or Desktop</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-methods-for-lowering-cpu-usage-in-the-windows-driver-framework/"><u>Effective Methods for Lowering CPU Usage in the Windows Driver Framework</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-solution-reviving-non-functioning-keys-on-your-hp-device/"><u>Effortless Solution: Reviving Non-Functioning Keys on Your HP Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-restoring-access-to-a-non-responsive-dhcp-server/"><u>Expert Advice: Restoring Access to a Non-Responsive DHCP Server</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-locating-and-fixing-missing-msvcr110dll-errors/"><u>Expert Tips: Locating and Fixing Missing MSVCR110.dll Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-nvidia-windows-kernel-mode-driver-stopped-responding-issue/"><u>Fix NVIDIA Windows Kernel Mode Driver Stopped Responding Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-cache-miss-errors-quickly-in-google-chrome-for-a-smooth-web-experience/"><u>Fixing 'Cache Miss' Errors Quickly in Google Chrome for a Smooth Web Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-a-step-by-step-guide-to-resolving-google-chromes-critical-error-scam/"><u>Fixing the Issue: A Step-by-Step Guide to Resolving Google Chrome's 'Critical Error Scam'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-failed-to-create-d3d-device-error-on-windows-solution-guide/"><u>How to Fix the Failed to Create D3D Device Error on Windows – Solution Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-tackle-overuse-of-hard-drive-storage-by-microsofts-telemetry-feature-in-windows-11/"><u>How to Tackle Overuse of Hard Drive Storage by Microsoft's Telemetry Feature in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Infinix Smart 8 HD? | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-efficiently-export-facebook-features-via-chrome-plug-ins/"><u>In 2024, Efficiently Export Facebook Features via Chrome Plug-Ins</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-fostering-fandoms-top-three-storytelling-techniques/"><u>In 2024, Fostering Fandoms  Top Three Storytelling Techniques</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-the-art-of-larger-youtube-media/"><u>In 2024, Mastering the Art of Larger YouTube Media</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-boomerang-edge-captivating-your-instagram-audience/"><u>In 2024, The Boomerang Edge  Captivating Your Instagram Audience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207253905-lose-not-the-sd-card-detection/"><u>Lose Not the SD Card Detection!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/minecraft-error-code-5-explained-quick-fixes-for-a-smooth-gaming-experience/"><u>Minecraft Error Code 5 Explained – Quick Fixes for a Smooth Gaming Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-delays-in-league-of-legends-patch-downloading-processes/"><u>Overcoming Delays in League of Legends Patch Downloading Processes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-out-of-memory-in-red-dead-redemption-ii-adjusting-pagefile-settings/"><u>Solving 'Out Of Memory' In Red Dead Redemption II: Adjusting Pagefile Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-resolving-windows-11s-unresponsive-volume-adjustment/"><u>Step-by-Step Guide to Resolving Windows 11'S Unresponsive Volume Adjustment</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-usb-tethering-mastery-for-windows-10-users/"><u>Step-by-Step USB Tethering Mastery for Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-roadblock-ahead-teredo-fails-to-secure-spot-on-competitive-list/"><u>The Roadblock Ahead: Teredo Fails to Secure Spot on Competitive List</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-review-expert-insights-on-the-latest-computer-hardware/"><u>Tom's Tech Review: Expert Insights on the Latest Computer Hardware</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/top-ranked-apps-for-video-conferencing-and-collaboration/"><u>Top-Ranked Apps for Video Conferencing and Collaboration</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-shockwave-flash-crashes-within-google-chrome-a-comprehensive-guide/"><u>Troubleshooting Shockwave Flash Crashes Within Google Chrome - A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-overcoming-deadly-glitches-in-black-ops-4/"><u>Troubleshooting Tips: Overcoming Deadly Glitches in Black Ops 4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vanishing-act-taskview-on-taskbar-hiding/"><u>Vanishing Act: TaskView on Taskbar Hiding</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-audio-outage-addressed-and-fixed/"><u>Windows 11 Audio Outage Addressed & Fixed</u></a></li>
</ul></div>
