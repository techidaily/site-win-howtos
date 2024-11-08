---
title: Solve 'No Response From DNS Server' Issues with These 4 Simple Fixes
date: 2024-11-04T19:55:36.112Z
updated: 2024-11-07T21:27:55.460Z
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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139123/17108" target="_top" id="2139123">
  <img src="//a.impactradius-go.com/display-ad/17108-2139123" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139123/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4) Click **Change adapter settings**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1286df40874.jpg)

5) Right-click on **Local Area Connection**, **Ethernet** or **Wi-Fi** according to your Windows. Then click **Properties**.|  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a128e6af137d.png)

6) Click **Internet Protocol Version 4(TCP/IPv4)**, then **Properties**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a128fa0c7dc8.png)

7) Tick on **Obtain an IP address automatically** and **Obtain DNS server address automatically**. Then click **OK**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12900623628.png)

8) Click **Internet Protocol Version 6(TCP/IPv6)**, then **Properties**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12903014de5.png)

9) Tick on **Obtain an IP address automatically** and **Obtain DNS server address automatically**. Then click **OK**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a12905d90a85.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Restart your computer and try to access the website you want to go to again and see if it succeeds.

---

### Solution 2: Clear your DNS cache and reset your IP

There may be problems with your DNS server if its cache is getting full. To see if that’s the case, try clearing the DNS cache and resetting the IP address.

1) Type **cmd** in the search box from the Start menu. Then right-click on **Command Prompt** to select **Run as administrator**.  

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1298fb8c2d7.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Note:** Click **Yes** when prompted by the User Account Control.

2) On the open black window, type the following commands and press **Enter** after each.

 **ipconfig /flushdns**
  
 **ipconfig /registerdns**
  
 **ipconfig /release**
  
 **ipconfig /renew**

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a129aa3217b1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049369/7443" target="_top" id="2049369">
  <img src="//a.impactradius-go.com/display-ad/7443-2049369" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049369/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

After updating your network adapter driver, please restart your computer. Try to access the website you want to go to again and see if it succeeds.

---

### Solution 4: Restart your modem and router

If your modem or router doesn’t work properly, the DNS server could stop responding, either. You can restart your modem and router if you have one to solve the problem.

1) Press the power button of your modem or router to power off, then wait for a while and press the power button again to start it again.  

![](https://images.drivereasy.com/wp-content/uploads/2017/05/4-28.jpg)

2) Try to access the website you want to go to again and see if it succeeds.

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047346/19272" target="_top" id="2047346">
  <img src="//a.impactradius-go.com/display-ad/19272-2047346" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047346/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/new-ideal-dialogue-architect-forum-for-2024/"><u>[New] Ideal Dialogue Architect Forum for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-tips-to-triple-your-instagram-video-viewers/"><u>[New] In 2024, Tips to Triple Your Instagram Video Viewers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-the-secrets-to-never-ending-snaps-on-snapchat/"><u>[Updated] 2024 Approved The Secrets to Never-Ending Snaps on Snapchat</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-comprehensive-guide-to-repair-a-broken-integrated-webcam-in-windows-os/"><u>A Comprehensive Guide to Repair a Broken Integrated Webcam in Windows OS</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/become-a-croatian-connoisseur-heres-your-list-of-7-key-benefits/"><u>Become a Croatian Connoisseur – Here's Your List Of 7 Key Benefits</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-vivo-v29e-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Vivo V29e? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-pathways-to-launching-windows-fix/"><u>Essential Pathways to Launching Windows FIX</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-troubleshooting-casting-issues-from-windows-10-to-your-chosen-device/"><u>Fix: Troubleshooting Casting Issues From Windows 10 to Your Chosen Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-unregistered-class-issues-in-windows-11-a-step-by-step-guide/"><u>Fixing Unregistered Class Issues in Windows 11 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-address-the-problem-when-system-resources-are-inadequate/"><u>How to Address the Problem When System Resources Are Inadequate</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-missing-volume-control-icon-in-windows-11-complete-tutorial-with-images/"><u>How to Fix a Missing Volume Control Icon in Windows 11 - Complete Tutorial with Images</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6 to other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-from-apple-iphone-se-2022-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer from Apple iPhone SE (2022) to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-issues-when-the-steam-store-wont-load-a-step-by-step-guide/"><u>Resolving Issues When The Steam Store Won't Load: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-no-response-from-your-dns-server-try-these-top-4-tips/"><u>Resolving No-Response From Your DNS Server? Try These Top 4 Tips!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-rated-vr-filmography-watch-and-download-the-ultimate-selection-of-immersive-4k-hd-1080p-360-degree-experiences/"><u>Top Rated VR Filmography: Watch & Download the Ultimate Selection of Immersive 4K, HD 1080P 360-Degree Experiences</u></a></li>
<li><a href="https://win-howtos.techidaily.com/warframe-pc-stability-issues-solutions-and-fixes/"><u>Warframe PC Stability Issues: Solutions and Fixes</u></a></li>
</ul></div>

