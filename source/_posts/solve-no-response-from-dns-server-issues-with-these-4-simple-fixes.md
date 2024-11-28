---
title: Solve 'No Response From DNS Server' Issues with These 4 Simple Fixes
date: 2024-11-27T09:45:55.393Z
updated: 2024-11-28T01:58:45.581Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Click **Change adapter settings**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1286df40874.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Right-click on **Local Area Connection**, **Ethernet** or **Wi-Fi** according to your Windows. Then click **Properties**.|  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a128e6af137d.png)

6) Click **Internet Protocol Version 4(TCP/IPv4)**, then **Properties**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a128fa0c7dc8.png)

7) Tick on **Obtain an IP address automatically** and **Obtain DNS server address automatically**. Then click **OK**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12900623628.png)

8) Click **Internet Protocol Version 6(TCP/IPv6)**, then **Properties**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12903014de5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9) Tick on **Obtain an IP address automatically** and **Obtain DNS server address automatically**. Then click **OK**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12905d90a85.png)

Restart your computer and try to access the website you want to go to again and see if it succeeds.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 2: Clear your DNS cache and reset your IP

There may be problems with your DNS server if its cache is getting full. To see if that’s the case, try clearing the DNS cache and resetting the IP address.

1) Type **cmd** in the search box from the Start menu. Then right-click on **Command Prompt** to select **Run as administrator**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1298fb8c2d7.png)

**Note:** Click **Yes** when prompted by the User Account Control.

2) On the open black window, type the following commands and press **Enter** after each.

 **ipconfig /flushdns**
  
 **ipconfig /registerdns**
  
 **ipconfig /release**
  
 **ipconfig /renew**

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a129aa3217b1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

2) Try to access the website you want to go to again and see if it succeeds.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-links.techidaily.com/updated-circulation-craft-expert-for-2024/"><u>[Updated] Circulation Craft Expert for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-creating-a-personal-brand-on-facebook-for-2024/"><u>[Updated] Creating a Personal Brand on Facebook for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/14-ways-to-make-irresistible-gourmet-vids-for-2024/"><u>14 Ways to Make Irresistible Gourmet Vids for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-comprehensive-scrutiny-of-xstream-video-hubs-features/"><u>2024 Approved Comprehensive Scrutiny of XStream Video Hub's Features</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-enhance-your-channels-voice-dive-into-the-world-of-banner-makers-apps/"><u>2024 Approved Enhance Your Channel's Voice Dive Into the World of Banner Makers (Apps)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-correcting-and-preventing-windows-error-0xc00000xe9-a-detailed-guide/"><u>Expert Tips for Correcting and Preventing Windows Error 0xC00000^XE9 – A Detailed Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-oneplus-nord-n30-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from OnePlus Nord N30 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-list-websites-with-free-thrones-audio-downloads/"><u>In 2024, A-List Websites with Free Thrones Audio Downloads</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-expert-tips-elevating-your-projects-with-movie-maker-in-win11/"><u>In 2024, Expert Tips Elevating Your Projects with Movie Maker in Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-windows-getting-ready-hurdle-expert-fixes-and-tips/"><u>Overcoming the 'Windows Getting Ready' Hurdle: Expert Fixes and Tips</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-lava-storm-5g-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on Lava Storm 5G</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-unavailability-problems-with-destiny-2-servers-a-step-by-step-guide/"><u>Solving Unavailability Problems with Destiny 2 Servers: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-your-problems-the-ultimate-guide-to-resolve-steam-updates-failure/"><u>Solving Your Problems: The Ultimate Guide to Resolve Steam Updates Failure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-the-non-functional-night-light-feature-in-windows-10-and-11/"><u>Troubleshooting Guide: Fixing the Non-Functional Night Light Feature in Windows 10 & 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-astro-a40-microphone-fixes-and-solutions/"><u>Troubleshooting Your Astro A40 Microphone: Fixes & Solutions</u></a></li>
</ul></div>

