---
title: Solve 'No Response From DNS Server' Issues with These 4 Simple Fixes
date: 2024-12-10T22:26:15.312Z
updated: 2024-12-13T18:23:21.661Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Click **Network and Sharing Center** in **Large icons**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1287bc28f2e.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Click **Change adapter settings**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1286df40874.jpg)

5) Right-click on **Local Area Connection**, **Ethernet** or **Wi-Fi** according to your Windows. Then click **Properties**.|  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a128e6af137d.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6) Click **Internet Protocol Version 4(TCP/IPv4)**, then **Properties**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a128fa0c7dc8.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7) Tick on **Obtain an IP address automatically** and **Obtain DNS server address automatically**. Then click **OK**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12900623628.png)

8) Click **Internet Protocol Version 6(TCP/IPv6)**, then **Properties**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12903014de5.png)

9) Tick on **Obtain an IP address automatically** and **Obtain DNS server address automatically**. Then click **OK**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12905d90a85.png)

Restart your computer and try to access the website you want to go to again and see if it succeeds.

---

### Solution 2: Clear your DNS cache and reset your IP

There may be problems with your DNS server if its cache is getting full. To see if that’s the case, try clearing the DNS cache and resetting the IP address.

1) Type **cmd** in the search box from the Start menu. Then right-click on **Command Prompt** to select **Run as administrator**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1298fb8c2d7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**Note:** Click **Yes** when prompted by the User Account Control.

2) On the open black window, type the following commands and press **Enter** after each.

 **ipconfig /flushdns**
  
 **ipconfig /registerdns**
  
 **ipconfig /release**
  
 **ipconfig /renew**

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a129aa3217b1.jpg)

Then restart your computer and try to access the website you want to visit again and see if it succeeds.

---

### Solution 3: Update your network adapter driver

Your DNS server won’t respond if the network adapter driver is outdated. You can update your network adapter driver manually or, if you’re not confident playing around with drivers, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**.

Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

You can update your drivers automatically with either the **FREE** or the **Pro** version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get **full support** and a **30-day money-back guarantee**):

1) **[Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.

2) Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/driver-easy-scan.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Try to access the website you want to go to again and see if it succeeds.

---

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
<li><a href="https://youtube-docs.techidaily.com/ed-brilliant-setups-top-17-gear-for-online-videographers/"><u>[Updated] Brilliant Setups Top 17 Gear for Online Videographers</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-smile-more-using-emojis-in-youtube-conversations-for-2024/"><u>[Updated] Smile More Using Emojis in YouTube Conversations for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-astrological-flair-in-digital-self-portrayals-on-whatsapp/"><u>2024 Approved Astrological Flair in Digital Self-Portrayals on WhatsApp</u></a></li>
<li><a href="https://win-howtos.techidaily.com/application-exe-crashes-solving-the-stopped-working-issue/"><u>Application Exe Crashes: Solving the 'Stopped Working' Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-auto-start-issues-in-windows-11-a-comprehensive-guide/"><u>Diagnosing Auto Start Issues in Windows 11 – A Comprehensive Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-auto-start-problems-for-your-windows-10-device-a-comprehensive-guide/"><u>Diagnosing Auto-Start Problems for Your Windows 10 Device - A Comprehensive Guide</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/expert-advice-on-purging-your-iphone-efficient-strategies-from-stellar-professionals/"><u>Expert Advice on Purging Your iPhone: Efficient Strategies From Stellar Professionals</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-for-repairing-copy-and-paste-feature-failures-on-windows-11-systems/"><u>Expert Tips for Repairing 'Copy and Paste' Feature Failures on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-10-installation-issue-error-code-80240020/"><u>How to Fix Windows 10 Installation Issue - Error Code 80240020</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-google-pixel-7a-easily-by-drfone-android/"><u>In 2024, How To Unlock a Google Pixel 7a Easily?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-t2x-5g-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Vivo T2x 5G</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/native-tongue-learn-romanian-app-style/"><u>Native Tongue: Learn Romanian App Style</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-the-problem-of-dead-keys-on-your-hp-computer-effective-solutions-await/"><u>Solve the Problem of Dead Keys on Your HP Computer – Effective Solutions Await</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steps-to-rectify-kernel32-issues/"><u>Steps to Rectify Kernel32 Issues</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/why-the-value-of-free-titles-on-the-epic-games-store-has-dropped-significantly/"><u>Why the Value of Free Titles on the Epic Games Store Has Dropped Significantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-power-issues-solved-how-to-force-your-computer-to-turn-off/"><u>Windows 10 Power Issues Solved – How to Force Your Computer to Turn Off</u></a></li>
</ul></div>

