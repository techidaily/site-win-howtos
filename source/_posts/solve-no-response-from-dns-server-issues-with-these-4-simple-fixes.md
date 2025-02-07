---
title: Solve 'No Response From DNS Server' Issues with These 4 Simple Fixes
date: 2025-02-06T10:18:58.020Z
updated: 2025-02-07T13:24:54.627Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solve 'No Response From DNS Server' Issues with These 4 Simple Fixes
excerpt: This Article Describes Solve 'No Response From DNS Server' Issues with These 4 Simple Fixes
thumbnail: https://thmb.techidaily.com/2b11c9a35e9bf42b72b792cdfd30fad6b2d3f68c7ff5c3220b9ec5f91e6995e4.jpg
---

## Resolving No-Response From Your DNS Server? Try These Top 4 Tips

![](https://images.drivereasy.com/wp-content/uploads/2017/10/img_59e5d3d537e17.png)

Suddenly you cannot access any websites through the Internet. Then you try to troubleshoot the network problems on your Windows. It tells you the **DNS server not responding** is the culprit. You may see one of these:

“**The DNS server isn’t responding**.  
**Your computer appears to be correctly configured, but the device or resource (DNS server) is not responding**.”

If this problem occurs, don’t worry. Follow this guide to fix it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

If you’d like to know why you can’t browse the Internet due to the **‘DNS server not responding**, you can go to read the [reason part](#reason). Otherwise, follow along with the solutions directly.

1. **[Correct your DNS server address](#solution1)**
2. **[Clear your DNS cache and reset your IP](#solution2)**
3. **[Update your network adapter driver](#solution3)**
4. **[Restart your modem and router](#solution4)**

**Bonus Tip: Try using [VPN](https://tools.techidaily.com/drivereasy/download/)to fix the connection problem.**

**Note:** The screens shown below are from Windows 10, but all the methods also apply to Windows 11/8/7.

### Solution 1: Correct your DNS server address

The DNS server not responding error could be probably caused by an **incorrect DNS server address**. So you can follow these to correct your DNS server address:

1) On your keyboard, press the **Windows logo key** and **R** at the same time to invoke the Run box.

2) Type **control** and press **Enter**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/10/img_59e5c170e3799.png)

3) Click **Network and Sharing Center** in **Large icons**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1287bc28f2e.jpg)

4) Click **Change adapter settings**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1286df40874.jpg)

5) Right-click on **Local Area Connection**, **Ethernet** or **Wi-Fi** according to your Windows. Then click **Properties**.|  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a128e6af137d.png)

6) Click **Internet Protocol Version 4(TCP/IPv4)**, then **Properties**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a128fa0c7dc8.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7) Tick on **Obtain an IP address automatically** and **Obtain DNS server address automatically**. Then click **OK**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12900623628.png)

8) Click **Internet Protocol Version 6(TCP/IPv6)**, then **Properties**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12903014de5.png)

9) Tick on **Obtain an IP address automatically** and **Obtain DNS server address automatically**. Then click **OK**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12905d90a85.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Restart your computer and try to access the website you want to go to again and see if it succeeds.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 2: Clear your DNS cache and reset your IP

There may be problems with your DNS server if its cache is getting full. To see if that’s the case, try clearing the DNS cache and resetting the IP address.

1) Type **cmd** in the search box from the Start menu. Then right-click on **Command Prompt** to select **Run as administrator**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1298fb8c2d7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**Note:** Click **Yes** when prompted by the User Account Control.

2) On the open black window, type the following commands and press **Enter** after each.

 **ipconfig /flushdns**
  
 **ipconfig /registerdns**
  
 **ipconfig /release**
  
 **ipconfig /renew**

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a129aa3217b1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Then restart your computer and try to access the website you want to visit again and see if it succeeds.

---

### Solution 3: Update your network adapter driver

Your DNS server won’t respond if the network adapter driver is outdated. You can update your network adapter driver manually or, if you’re not confident playing around with drivers, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**.

Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

You can update your drivers automatically with either the **FREE** or the **Pro** version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get **full support** and a **30-day money-back guarantee**):

1) **[Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.

2) Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/driver-easy-scan.jpg)

3) Click **Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).  
![](https://images.drivereasy.com/wp-content/uploads/2023/07/driver-easy-update.jpg)  
**Note**: You can do it for free if you like, but it’s partly manual.  

After updating your network adapter driver, please restart your computer. Try to access the website you want to go to again and see if it succeeds.

---

### Solution 4: Restart your modem and router

If your modem or router doesn’t work properly, the DNS server could stop responding, either. You can restart your modem and router if you have one to solve the problem.

1) Press the power button of your modem or router to power off, then wait for a while and press the power button again to start it again.  

![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-28.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Try to access the website you want to go to again and see if it succeeds.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Why can’t I access websites when the DNS server not responding?

First, let’s figure out what a DNS server is. **DNS (** **Domain Name System)** server helps to translate the website address into the IP address for your browser to connect to.

For example, when you want to access our website: **<www.drivereasy.com>** on Chrome, the DNS server translates it into our public IP address: **144.217.68.24** for Chrome to connect to.

So you may know if there’s any wrong with your DNS server, you cannot access any website on your browser. No exception that if your DNS server stops responding, you cannot access the websites through the Internet.

---

Hopefully, this article has helped you fixed the problem. Feel free to comment below with your own experiences and share with your friends or colleagues if they’re experiencing the same problem.

* [network](https://store.drivereasy.com/order/cart.php?PRODS=4731822&QTY=1&AFFILIATE=108875)

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
<li><a href="https://win-howtos.techidaily.com/solved-computer-randomly-restarts-on-windows-11/"><u>[SOLVED] Computer Randomly Restarts on Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-finding-equilibrium-between-professional-life-and-youtubing/"><u>[Updated] 2024 Approved Finding Equilibrium Between Professional Life and YouTubing</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-mastering-mov-to-mpeg-4-conversion-on-win-11-for-2024/"><u>[Updated] Mastering MOV to MPEG-4 Conversion on Win 11 for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-motion-tracking-apps-for-ios-and-android/"><u>Best Motion Tracking Apps for iOS and Android</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-oneplus-12-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On OnePlus 12? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-strategies-to-repair-a-broken-usb-connection-resolving-unknown-device-errors-on-windows-10/"><u>Effective Strategies to Repair a Broken USB Connection: Resolving 'Unknown Device' Errors on Windows 10</u></a></li>
<li><a href="https://tech-hub.techidaily.com/examining-the-quintessential-reasons-behind-chatgpts-swift-ascent-to-global-popularity/"><u>Examining the Quintessential Reasons Behind ChatGPT’s Swift Ascent to Global Popularity</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/from-shot-to-showcase-smooth-video-capture-and-post-editing-with-adobe-connect/"><u>From Shot to Showcase Smooth Video Capture & Post-Editing with Adobe Connect</u></a></li>
<li><a href="https://win-howtos.techidaily.com/get-back-to-battle-faster-expert-advice-on-fixing-slow-download-problems-with-lol/"><u>Get Back to Battle Faster: Expert Advice on Fixing Slow Download Problems with LoL</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guiding-users-through-fixing-windows-10-copy-problems/"><u>Guiding Users Through Fixing Windows 10 Copy Problems</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-dfu-mode-on-apple-iphone-se-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of DFU Mode on Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/network-setup-problem-in-dragon-ball-fighterz-now-corrected/"><u>Network Setup Problem in Dragon Ball FighterZ Now Corrected</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/professional-online-broadcast-capture-methods/"><u>Professional Online Broadcast Capture Methods</u></a></li>
</ul></div>

