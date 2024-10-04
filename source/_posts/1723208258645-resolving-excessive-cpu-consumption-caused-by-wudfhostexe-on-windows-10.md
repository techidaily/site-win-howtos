---
title: Resolving Excessive CPU Consumption Caused by WUDFHost.exe on Windows 10
date: 2024-09-29T08:43:41.586Z
updated: 2024-10-04T01:22:45.990Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Excessive CPU Consumption Caused by WUDFHost.exe on Windows 10
excerpt: This Article Describes Resolving Excessive CPU Consumption Caused by WUDFHost.exe on Windows 10
thumbnail: https://thmb.techidaily.com/dd0fbdf5cb36119cb6841081ccc0579ed7b5b44574bcc137517a05ce80e5ff57.jpg
---

## Troubleshooting Missing Desktop Icons on Windows 11 – Solved

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf526e8ebcab-1024x552.jpg)

If your desktop icons somehow disappear on your Windows 10 computer, don’t worry, you can try the tips below to fix the issue. Quickly and easily.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these tips

You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Enable Show desktop icons**](#t1)
2. [**Check your desktop icon settings**](#t2)
3. [**Rebuild icon cache**](#t4)
4. [**Perform a system restore**](#t5)
5. [**Reset your computer**](#t6)
6. [**Bonus tip**](#t7)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036481/19272" target="_top" id="2036481">
  <img src="//a.impactradius-go.com/display-ad/19272-2036481" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036481/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Tip 1: Enable Show desktop icons

Make sure you have enabled the “Show desktop icon” feature on Windows 10:

1. Right-click your desktop, click **View**, and check **Show desktop icons**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf52ca259fe4.jpg)
2. Check to see if your desktop icons are back. If not, try Tip 2, below.

---

### Tip 2: Check your desktop icon settings

1. Right-click your desktop and click **Personalize**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf531bcea206.jpg)
2. Click **Themes** \> **Desktop icon settings**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53220a4552.jpg)
3. Select the icons you want to show on desktop, then click **OK**.  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53279e9206.jpg)
4. Check if your “desktop icons missing” problem is resolved. If not, try Tip 3, below.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Tip 3: Rebuild icon cache

You can also try these steps to rebuild the icon cache:

1. Run **Command Prompt** as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53d32cc341.jpg)
2. Copy-paste the following commands one at a time and press **Enter** after each command.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

taskkill /F /IM explorer.exe  
cd /d %userprofile%\AppData\Local  
attrib –h IconCache.db  
del IconCache.db  
start explorer.exe
3. Check if it helps restore your desktop icons. If not, try Tip 4, below.

---

### Tip 4: Perform a system restore

If your desktop icons still don’t show up, you can perform a system restore to return your system to a date when the icons appeared normally on the desktop. Here’s how to perform a system restore to help fix your “desktop icons disappeared in Windows 10” issue:

1. Type **recovery** in the Windows search box, then press **Enter**.
2. At Recovery, click **Open System Restore**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a2728a7e.jpg)
3. Select **Choose a different restore point**, and click **Next**.  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a34c35bc.jpg)
4. Check the box beside **Show more restore points**. You should see a list of ‘restore points’. These are like backups of your computer, as it was at that particular date and time. Think back to a date when your desktop icons showed up, and **select a restore point** from that date or slightly earlier (but no later).  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a4d84f3c.jpg)
5. Click **Next** \> **Finish**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934288/19272" target="_top" id="1934288">
  <img src="//a.impactradius-go.com/display-ad/19272-1934288" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934288/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Check to see if your desktop icons are now restored on Windows 10\. If not, try Tip 5, below.

---

### Tip 5: Reset your computer

If the steps above didn’t work for you. Resetting your computer is worth a try. It fixed the desktop icon issue for some users.

1. Click the **Start** button > the **Settings** icon.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b790f639.jpg)
2. Click **Update & security** \> **Recovery**.
3. In the **Reset this PC** area, click the **Get started** button. Then follow the on-screen instructions to reset your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b9dab56d.jpg)

---

### Bonus tip

A missing or outdated graphics driver may also stop items from appearing properly on PC. You should make sure your graphics card driver is up to date. There are two ways to update your graphics driver: **manually** and **automatically**.

**Update your graphics driver manually** — You can update your driver manually by going to the hardware manufacturer’s website, and searching for the latest driver for your graphics card. But if you take this approach, be sure to choose the driver that’s compatible with the exact model number of your hardware, and your version of Windows.

OR

**Update your graphics driver automatically** — If you don’t have the time, patience, or computer skills to update your driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.
2. Run Driver Easy and click **Scan Now**. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-Scan-Needed.jpg)
3. Click **Update** next to any flagged devices to automatically download the correct version of their drivers, then you can install them manually. Or click **Update All** to automatically download and install them all automatically. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All. You get full support and a 30-day money-back guarantee.)  
![](https://www.drivereasy.com/wp-content/uploads/2022/02/de-update-all-rtx-3080.jpg)  
If you need assistance, please contact Driver Easy’s support team at **<support@drivereasy.com>**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482">
  <img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

Hopefully, this can help you out.

If you have any other suggestions, please feel free to leave a comment below.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://remote-screen-capture.techidaily.com/new-streamers-dilemma-deciding-between-obs-and-shadowplay-for-2024/"><u>[New] Streamers' Dilemma Deciding Between OBS and ShadowPlay for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-bold-profile-features-for-captivating-your-tiktok-audience-for-2024/"><u>[Updated] Bold Profile Features for Captivating Your TikTok Audience for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-from-raw-footage-to-highlight-hits/"><u>[Updated] From Raw Footage to Highlight Hits</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-top-5-cloud-based-voice-customizers-for-chrome-os-vocal-transformation-tools-reviewed/"><u>2024 Approved Top 5 Cloud-Based Voice Customizers for Chrome OS Vocal Transformation Tools Reviewed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-overcome-usb-connectivity-interruptions-and-power-surges-in-windows-11-systems/"><u>Expert Tips to Overcome USB Connectivity Interruptions and Power Surges in Windows 11 Systems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-gmail-password-on-samsung-galaxy-f34-5g-devices-by-drfone-android/"><u>How to Reset Gmail Password on Samsung Galaxy F34 5G Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Xiaomi 14 to PC? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-in-ar-games-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Simulate GPS Movement in AR games On Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-realme-12-pro-5g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Realme 12 Pro 5G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-touchpad-not-functioning-heres-how-to-fix-it-on-windows-os/"><u>Laptop Touchpad Not Functioning? Here's How to Fix It on Windows OS!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-directory-is-invalid-issue-a-comprehensive-guide/"><u>Solve 'Directory Is Invalid' Issue: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/successful-setup-of-nvidia-graphics-drivers/"><u>Successful Setup of Nvidia Graphics Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-restore-print-to-pdf-functionality-on-windows-10-and-11/"><u>Troubleshooting Guide: How to Restore Print to PDF Functionality on Windows 10 and 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-verify-gpu-compatibility-with-directx-11-standard/"><u>Troubleshooting Guide: Verify GPU Compatibility with DirectX 11 Standard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-troubleshooting-overcoming-the-challenge-of-the-notorious-0xc00n000n05-error/"><u>Windows Troubleshooting: Overcoming the Challenge of the Notorious 0Xc00n000N05 Error</u></a></li>
</ul></div>

