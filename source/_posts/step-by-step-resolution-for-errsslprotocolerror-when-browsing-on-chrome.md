---
title: Step-by-Step Resolution for ERR_SSL_PROTOCOL_ERROR When Browsing on Chrome
date: 2024-09-30T16:01:21.407Z
updated: 2024-10-04T16:01:26.037Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Resolution for ERR_SSL_PROTOCOL_ERROR When Browsing on Chrome
excerpt: This Article Describes Step-by-Step Resolution for ERR_SSL_PROTOCOL_ERROR When Browsing on Chrome
thumbnail: https://thmb.techidaily.com/7ec641d0887205acbcfc6836f03618d0eee863811c5fb186d0f0c958e752d87a.jpg
---

## Step-by-Step Solution for Windows's Persistent Network Error: 0X800704cf - Now Resolved

When you fail to access another computer of the same network, or when you cannot log in to the Microsoft Store, you may see the 0x800704cf error code. This string seems quite confusing, but in fact it’s not hard to solve the problem.

 We cover solutions for both situations listed above. You may not try them all; simply work down the list until you find the one that does the trick.

* **[If you see 0x800704cf error when connecting to a network PC](https://tools.techidaily.com/drivereasy/download/)**
* **[If you see 0x800704cf error when accessing Microsoft Store](https://tools.techidaily.com/drivereasy/download/)**
* **[Bonus tips: Update your network driver](https://tools.techidaily.com/drivereasy/download/)**

---

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## **Fix 0x800704cf error when connecting to a network PC**

![Fix 0x800704cf error when connecting to a network PC](https://images.drivereasy.com/wp-content/uploads/2020/08/case1.jpg)

 It’s very frustrating when you want to access another network PC to share files or perform specific tasks but are interrupted by the 0x800704cf error. No worries. You can follow the guide below to put things back on track.

1. **[Change adapter options](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset TCP/IP](https://tools.techidaily.com/drivereasy/download/)**
3. **[Reinstall the network adapter](https://tools.techidaily.com/drivereasy/download/)**

 The screenshot below comes from Windows 10, but the fixes also apply to Windows 7/8/11.

### Fix 1 – Change adapter options

 The network adapter enables your computer to transmit and receive data on a local area network. If you’re having the 0x800704cf error, try changing the adapter settings to see if that resolves the problem.

**1)** Right-click the**network icon** in the notification area.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-1-5.jpg)

**2)** Click**Open Network & Internet settings** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-2-8.jpg)

**3)** Select**Status** . Then, click**Change adapter options** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-3-2.jpg)

**4)** Right-click the network you’re currently using, and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-4.jpg)

**5)** Uncheck**Client for Microsoft Networks** , and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/1-5.jpg)

 Restart your device and check if the 0x800704cf goes away. If not, continue with the next fix below.

---

### Fix 2 – Reset TCP/IP

 TCP/IP is a suite of rules that allow computers to communicate on a network. So if there’s something wrong with the[TCP/IP](https://en.wikipedia.org/wiki/Internet%5Fprotocol%5Fsuite) settings, the 0x800704cf error may occur. To see if that’s the case, you can simply do a reset.

**1)** Type**cmd** in the search box. Then, right-click**Command Prompt** and click**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/2-1-7.jpg)

**2)** Click**Yes** when you’re prompted to continue.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/2-3-2.jpg)

**3)** In the command prompt window, type in the following commands and press the **Enter** key after each command.

ipconfig /flushdns

nbtstat -RR

netsh winsock reset

netsh int ip reset

![](https://images.drivereasy.com/wp-content/uploads/2020/08/2-2-4.jpg)

<!-- affiliate ads begin -->
<span id="1982461">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982461.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982461">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982461.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982461%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982461/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now that the DNS cache is cleared, NetBIOS entries are refreshed, and both the IP settings and Winsock catalog is reset, you should reboot your computer for the changes to take effect. After that, check if the issue persists; if yes, head towards the last fix.

---

### Fix 3 – Reinstall the network adapter

 If all the methods above ended nowhere, you should reinstall the network adapter in case it’s corrupted and causes the 0x800704cf error.

**1)** On your keyboard, press the**Windows logo key** and**R** at the same time to open the Run box. Then, type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-1-6.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**2)** Select the**View** tab, and click**Show hidden devices** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-2-8.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Double-click**Network adapters** to view all the devices under this category.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-3-4.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**4)** Right-click a device and click**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-5-1.jpg)

**5)** Click**Uninstall** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/3-4-3.jpg)

**6)** Delete all the devices one by one under Network adapters.

 After completing the steps above, restart your machine, and Windows will automatically reinstall the network adapters. The 0x800704cf error should be gone now and you can connect to another network PC without hassle.

---

## **Fix 0x800704cf error when accessing the Microsoft Store**

![Fix 0x800704cf error when accessing the Microsoft Store on Windows 10](https://images.drivereasy.com/wp-content/uploads/2020/08/error-case-2.jpg)

 When you fail to access the Microsoft Store on Windows 10 or 11, this 0x800704cf error will appear. It implies you’re not connected to the Internet, even though you are, as you can use the browser and other applications normally. But don’t worry; here’s a list of fixes that can help.

1. **[Sign in with Microsoft account](https://tools.techidaily.com/drivereasy/download/)**
2. **[Run the Windows troubleshooter](https://tools.techidaily.com/drivereasy/download/)**
3. **[Reset the Microsoft Store](https://tools.techidaily.com/drivereasy/download/)**

### Fix 1 – Sign in with Microsoft account

 The 0x800704cf error can arise when you’re logged in using a local account. Try signing in to your Microsoft account and see if the issue is resolved.

**1)** Click the**Start** button and click the**Settings icon** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-1-9.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918661/19272" target="_top" id="1918661">
  <img src="//a.impactradius-go.com/display-ad/19272-1918661" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918661/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**2)** Click**Accounts** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-2-7.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151866/7443" target="_top" id="2151866">
  <img src="//a.impactradius-go.com/display-ad/7443-2151866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Select**Your info** in the left pane. Then, click**Sign in with a Microsoft account instead** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-3-9.jpg)

**4)** Enter your**account** and**password** to sign in.

**5)** Go back to**Your info** , and click**Verify** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-4-5.jpg)

 Follow the on-screen instruction to verify your identity. Then, open your Microsoft Store and see whether the 0x800704cf code still pops up or not. If this method isn’t helpful, don’t despair. Have a look at more fixes below.

---

### Fix 2 – Run the Windows troubleshooter

 If the 0x800704cf error keeps appearing when you’re using the Microsoft Store, the Windows built-in troubleshooter is an effective tool that may help you out.

**1)** Type**troubleshoot** in the search box and click**Troubleshooting settings** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-1-3.jpg)

**2)** Scroll down to click**Network Adapter** . Then, click**Run the troubleshooter** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-2-3.jpg)

**3)** Select**All network adapters** , and click**Next** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-3-2.jpg)

**4)** Wait for the troubleshooting process to complete, and close the troubleshooter.

**5)** Click**troubleshoot** in the search box and click**Troubleshooting settings** to open the troubleshoot menu again.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-1-4.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**6)** Scroll down to click**Windows Store Apps** and click**Run the troubleshooter** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/5-4-2.jpg)

 Follow the on-screen instruction to fix any detected issues. Then, launch the Microsoft Store and check if it works without error. If not, please try the Fix 3 below.

---

### Fix 3 – Reset the Microsoft store

 If your Microsoft isn’t working properly for whatever reason, one of the solutions is clearing the stored data and resetting it back to the default.

**1)** Click the**Start** button and click the**Settings icon** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/4-1-10.jpg)

**2)** Click**Apps** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-2-4.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2148129/17093" target="_top" id="2148129">
  <img src="//a.impactradius-go.com/display-ad/17093-2148129" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2148129/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Select**Apps & features** . Then, scroll down to click**Microsoft Store** , and click**Advanced options** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-3-2.jpg)

**4)** Scroll down and click**Reset** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-4-1.jpg)

**5)** Click**Reset** .

![](https://images.drivereasy.com/wp-content/uploads/2020/08/6-5-1.jpg)

 Open your Microsoft Store, and the 0x800704cf error won’t be disturbing you anymore.

 Network issue like 0x800704cf error is a common PC problem but it’s insufferable. There’s so much you can’t do without the Internet, and even worse, you can’t search a solution to fix it. If you’ve frequently run into this kind of issues such as no or slow Internet access, be sure to check our bonus tips below.

---

## Bonus tips: Update your network driver

 An outdated or a faulty network driver is known to be the culprit of most network problems. To keep your network connection smooth and strong, you should check if you install the up-to-date network adapter driver. If not, update them, in either way you want.

**Manual driver update** – You can update your network adapter driver manually by going to the manufacturer’s website, and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly:

**1)** **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

**2)** Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2020/08/de-1-5.jpg)

**3)** Click the**Update** button next to the flagged network driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the**FREE version** ).

 Or click**Update All** to automatically download and install the correct version of_all_ the drivers that are missing or out of date on your system. (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click**Update All** ).

![](https://images.drivereasy.com/wp-content/uploads/2020/08/de-2-7.jpg)

 You can do it for free if you like, but it’s partly manual.

**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://tools.techidaily.com/drivereasy/download/) .**

---

 Hopefully this post helped you get rid of the 0x800704cf error. If you have any questions or suggestions, feel free to leave a comment below.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [network adapter](https://tools.techidaily.com/drivereasy/download/)
* [network issue](https://tools.techidaily.com/drivereasy/download/)
* [network problem](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-webster.techidaily.com/levate-your-youtube-presence-with-simple-seo-techniques/"><u>[New] Elevate Your YouTube Presence with Simple SEO Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-perfecting-the-art-of-subtle-sound-enhancements-in-lumafusion/"><u>[New] Perfecting the Art of Subtle Sound Enhancements in Lumafusion</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-learn-about-free-recording-software-today/"><u>2024 Approved Learn About Free Recording Software Today</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/colombias-heartbeat-of-compassion-fundacion-danny/"><u>Colombia’s Heartbeat of Compassion - Fundacion Danny</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-a-non-responsive-dns-server-with-these-4-quick-fixes/"><u>Fix a Non-Responsive DNS Server with These 4 Quick Fixes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-guide-how-to-troubleshoot-and-solve-windows-11-update-error-0x8-tutorial/"><u>Fix Guide: How to Troubleshoot and Solve Windows 11 Update Error (0X8) [Tutorial]</u></a></li>
<li><a href="https://some-tips.techidaily.com/leverage-advanced-traffic-insights-the-power-of-cookiebot-technology-on-websites/"><u>Leverage Advanced Traffic Insights: The Power of Cookiebot Technology on Websites</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-ipados-a-detailed-walkthrough-of-each-software-release/"><u>Mastering iPadOS: A Detailed Walkthrough of Each Software Release</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-microsoft-windows-troubleshooting-quick-fixes-for-entry-point-missing-errors/"><u>Mastering Microsoft Windows Troubleshooting: Quick Fixes for 'Entry Point Missing' Errors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/microphone-not-working-on-laptop-solved/"><u>Microphone Not Working On Laptop [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-issue-modify-security-protocols-for-successful-file-retrieval-and-download/"><u>Resolved Issue: Modify Security Protocols for Successful File Retrieval and Download</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-your-unresponsive-gaming-keyboard-fixes-for-no-light-up-on-razer-devices/"><u>Reviving Your Unresponsive Gaming Keyboard: Fixes for No Light-Up on Razer Devices</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-trim-and-refine-a-step-by-step-guide-to-cropping-videos-in-avidemux/"><u>Updated Trim and Refine A Step-by-Step Guide to Cropping Videos in Avidemux</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/watch-dark-and-learn-a-new-language-germans/"><u>Watch 'Dark' And Learn a New Language, Germans</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-strategies-to-resolve-frozen-windows-11-taskbar-issues-effectively/"><u>Winning Strategies to Resolve Frozen Windows 11 Taskbar Issues Effectively</u></a></li>
</ul></div>

