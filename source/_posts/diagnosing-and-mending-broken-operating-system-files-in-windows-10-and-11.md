---
title: Diagnosing and Mending Broken Operating System Files in Windows 10 & 11
date: 2025-02-15T16:49:20.868Z
updated: 2025-02-16T21:51:01.664Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Mending Broken Operating System Files in Windows 10 & 11
excerpt: This Article Describes Diagnosing and Mending Broken Operating System Files in Windows 10 & 11
thumbnail: https://thmb.techidaily.com/8f0b4518ce0df25393954ab31a3f7f9f5a628c2c9b34d40260095f1057a6321d.jpg
---

## Desktop Icon Mystery in Windows 11 Cracked: Find and Fix Your Missing Files Now

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf526e8ebcab-1024x552.jpg)

If your desktop icons somehow disappear on your Windows 10 computer, don’t worry, you can try the tips below to fix the issue. Quickly and easily.

## Try these tips

You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Enable Show desktop icons**](#t1)
2. [**Check your desktop icon settings**](#t2)
3. [**Rebuild icon cache**](#t4)
4. [**Perform a system restore**](#t5)
5. [**Reset your computer**](#t6)
6. [**Bonus tip**](#t7)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53220a4552.jpg)
3. Select the icons you want to show on desktop, then click **OK**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53279e9206.jpg)
4. Check if your “desktop icons missing” problem is resolved. If not, try Tip 3, below.

---

### Tip 3: Rebuild icon cache

You can also try these steps to rebuild the icon cache:

1. Run **Command Prompt** as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53d32cc341.jpg)
2. Copy-paste the following commands one at a time and press **Enter** after each command.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a34c35bc.jpg)
4. Check the box beside **Show more restore points**. You should see a list of ‘restore points’. These are like backups of your computer, as it was at that particular date and time. Think back to a date when your desktop icons showed up, and **select a restore point** from that date or slightly earlier (but no later).  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a4d84f3c.jpg)
5. Click **Next** \> **Finish**.
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://www.drivereasy.com/wp-content/uploads/2022/02/de-update-all-rtx-3080.jpg)  
If you need assistance, please contact Driver Easy’s support team at **<support@drivereasy.com>**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-step-by-step-to-youtube-fame-excellence-in-music-video-reactions/"><u>[New] 2024 Approved Step-by-Step to YouTube Fame Excellence in Music Video Reactions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-a-comprehensive-review-of-screenflows-impact-on-mac-professionals/"><u>[Updated] 2024 Approved A Comprehensive Review of ScreenFlow's Impact on Mac Professionals</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-discover-the-art-of-vocal-variation-for-enhanced-gameplay-experience-free-guide-for-2024/"><u>[Updated] Discover the Art of Vocal Variation for Enhanced Gameplay Experience (Free Guide) for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-unveiling-the-secrets-to-efficient-recording/"><u>2024 Approved Unveiling the Secrets to Efficient Recording</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-guide-to-resolving-the-paired-but-not-connected-dilemma-in-windows-11-bluetooth-setup/"><u>A Guide to Resolving the 'Paired but Not Connected' Dilemma in Windows 11 Bluetooth Setup</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comparing-apples-latest-titans-mac-mini-with-m2-vs-mac-studio-and-m1-performance-showdown-insights/"><u>Comparing Apple's Latest Titans: Mac Mini with M2 vs Mac Studio & M1 Performance Showdown - Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-31-in-windows-explained-fixes-to-get-you-back-on-track/"><u>Error Code 31 in Windows Explained: Fixes to Get You Back on Track</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-the-error-code-0x80004005-in-microsoft-exchange-step-by-step-guide/"><u>How to Fix the Error Code 0X80004005 in Microsoft Exchange - Step-by-Step Guide</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-auditory-illusions-video-meets-apple-music/"><u>In 2024, Auditory Illusions Video Meets Apple Music</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-learn-how-to-lock-stolen-your-iphone-6s-properly-drfone-by-drfone-ios/"><u>In 2024, Learn How To Lock Stolen Your iPhone 6s Properly | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-error-code-faks-a-step-by-step-guide-to-overcoming-challenges-in-minecraft/"><u>Mastering Error Code ˈfaɪks: A Step-by-Step Guide to Overcoming Challenges in Minecraft</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-windows-10-fix-guide-how-to-show-hidden-taskbar/"><u>Mastering Windows 10: Fix Guide - How To Show Hidden Taskbar</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/nikon-d7500-review-for-2024/"><u>Nikon D7500 Review for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-addressing-and-repairing-the-d3d-device-creation-failure/"><u>Solution Guide: Addressing and Repairing the D3D Device Creation Failure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-lenovo-laptop-camera-issues-a-step-by-step-fix/"><u>Solving Lenovo Laptop Camera Issues - A Step-by-Step Fix</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-restoring-your-windows-pcs-built-in-webcam-functionality/"><u>Step-by-Step Guide: Restoring Your Windows PC's Built-In Webcam Functionality</u></a></li>
<li><a href="https://win-howtos.techidaily.com/touchpad-not-scrolling-heres-how-to-get-it-working-again/"><u>Touchpad Not Scrolling? Here's How to Get It Working Again!</u></a></li>
<li><a href="https://discover-comparisons.techidaily.com/tutorial-rapido-per-il-recupero-dei-dati-persi-utilizzando-winscp-sulle-varie-versioni-di-windows/"><u>Tutorial Rapido per Il Recupero Dei Dati Persi Utilizzando WinSCP Sulle Varie Versioni Di Windows</u></a></li>
</ul></div>

