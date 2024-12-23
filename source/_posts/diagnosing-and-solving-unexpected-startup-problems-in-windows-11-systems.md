---
title: Diagnosing and Solving Unexpected Startup Problems in Windows 11 Systems
date: 2024-12-17T19:45:02.352Z
updated: 2024-12-22T17:37:32.886Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Solving Unexpected Startup Problems in Windows 11 Systems
excerpt: This Article Describes Diagnosing and Solving Unexpected Startup Problems in Windows 11 Systems
thumbnail: https://thmb.techidaily.com/14e8ddcfb81fc424c37a798e2f4fac450a83bd3f6d231984ceb0349e3e717f14.jpg
---

## Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7be8093704.jpg)

 Your computer startup very slow? or you cannot log in Windows on your computer with the standard user account? After you log in with an administrative account, you’re seeing an error saying:

**Failed to connect to a windows services**
  
 **Windows could not connect to the System Event Notification Service service.**

 I know you’re likely frustrating. But don’t worry. Usually it’s easy to solve out. Read on to see how…

## Try these fixes

 The methods below have helped other users solve the problem. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. **[Check the setting of System Event Notification Service on your computer](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset your Winsock Catalog](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your video card driver](https://tools.techidaily.com/drivereasy/download/)**
4. **[Uninstall the KB2952664 update](https://tools.techidaily.com/drivereasy/download/)**
5. [**Remove klhkum.dll**](https://tools.techidaily.com/drivereasy/download/)

 The following screenshots are from Windows 10\. But you can also follow the steps if you’re having the problem on Windows 7.

### Fix 1: Check the setting of System Event Notification Service on your computer

 You may have the problem due to the incorrect setting of System Event Notification Service.  
 Follow these steps to modify the setting:

1. On your keyboard, hold down the**Windows logo key** and**R** to invoke the Run box.
2. Type**services.msc** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf596c06c.jpg)
3. Right-click**System Event Notification Service** , then select**Restart** . If Restart grayed out, click**Start** instead.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf9e2c9b8.jpg)
4. Right-click System Event Notification Service again, this time select**Properties** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bfcea31f4.jpg)
5. Set the**Startup type** to**Automatic** . Then click **Apply**  \> **OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c08c50e91.jpg)

 Restart your computer to see if the error has gone. If you still see the error, you have something else to try…

---

### Fix 2: Reset your Winsock Catalog

 You very likely have the problem on your computer that joins in a domain network. You could have problem due to some interference of your Winsock Catalog setting.

Follow these steps to reset your Winsock Catalog:

1. On your keyboard, hold down the**Windows logo key** and press**R** to invoke the Run box.
2. Type**cmd** , then press**Shift + Ctrl + Enter** keys together.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c0804d3b9.jpg)
3. An elevated Command Prompt would be open. Type the following command and press Enter.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**netsh winsock reset**

 Restart your computer to see if the error has gone. If you still see the error, don’t worry, move onto the next methods.  
 If resetting Winsock worked temporarily, you can move to Fix 5.

---

### Fix 3: Update your video card driver

 You could probably encounter this error if the video card driver on your computer is outdated, incompatible or corrupt. So you should**update your video card driver** to see if it fixes your problem. If you don’t have the time, patience or skills to update the driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to be troubled by the wrong driver you would be downloading, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the**FREE** or the**Pro version** of Driver Easy. But with the Pro version it takes just 2 steps (and you get**full support and a 30-day money back guarantee** ):

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c1c42f3f2.jpg)
3. C  lick **Update All** to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All).  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**Note** : You can do it for free if you like, but it’s partly manual.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2297ff06.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your computer to see if the error has gone. If the error persists, don’t give up hope, see if the last method could help you…

---

### Fix 4: Uninstall the KB2952664 update

 According to many users’ report, this error could be due to the**KB2952664** Windows Update. If none of the methods above helps you, go with the following steps to**uninstall the KB2952664 update** on your computer:

1. On your keyboard, press the**Windows logo key** and**R** to invoke the Run box.
2. Type**control** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c29a46965.jpg)
3. Select**Uninstall a program** under**Programs** when**View by Category** selected.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2c7bbb7b.jpg)
4. Click View installed updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2f3ae739.jpg)
5. Find and right-click the update with KB2952664, then Uninstall.

Restart your computer to see if the error has gone.

---

### Fix 5: Remove klhkum.dll

 If you have to reset Winsock tens of times a day, you need to try this method. What you should do is checking whether you have “klhkum.dll” or not.

 klhkum.dll’s description is “**System Interceptors PDK usermode service interceptor** ” and it’s intercepting the system when it shouldn’t.  
 So how to remove it? Follow the guide:

1. Press**Ctrl+Shift+Esc** to open the Task Manager.
2. Click the**Startup** tab and find**klhkum.dll** process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-52-10.jpg)
3. Right-click on it and choose**Disable** . You can also open its file location and delete it permanently.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-55-36.jpg)
4. Restart your computer to see if the error has gone.

 One more tip: If you’re using Kaspersky security software and possibly on Windows 7, you need to turn off Kaspersky manually to fix the issue.

---

 Tada! Hopefully this helps. Feel free to comment below with your own experiences.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-the-elite-collection-best-kung-fu-arcade-games/"><u>[New] In 2024, The Elite Collection Best Kung Fu Arcade Games</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/he-route-to-revenue-crafting-content-around-consumer-commodities-for-2024/"><u>[New] The Route to Revenue Crafting Content Around Consumer Commodities for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-viral-audio-waves-top-10-bgm-for-youtube-short-videos/"><u>[Updated] In 2024, Viral Audio Waves Top 10 BGM for YouTube Short Videos</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-samsung-galaxy-xcover-7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/complete-solution-reviving-unresponsive-optical-drives-in-microsoft-windows-environments/"><u>Complete Solution: Reviving Unresponsive Optical Drives in Microsoft Windows Environments</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-unleash-your-creativity-top-10-free-mp4-video-editors-for-2024/"><u>New Unleash Your Creativity Top 10 Free MP4 Video Editors for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rapid-resolution-eliminating-the-out-of-memory-bugs-in-rdr2-through-settings-tweaks/"><u>Rapid Resolution: Eliminating the 'Out of Memory' Bugs in RDR2 Through Settings Tweaks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revived-stalled-audio-in-discord/"><u>Revived Stalled Audio in Discord</u></a></li>
<li><a href="https://win-howtos.techidaily.com/struggling-with-pdf-printer-issues-heres-how-to-overcome-them/"><u>Struggling with PDF Printer Issues? Here's How to Overcome Them</u></a></li>
<li><a href="https://some-guidance.techidaily.com/supreme-display-quality-top-10-ranking-of-4k-screens-for-2024/"><u>Supreme Display Quality #Top 10 Ranking of 4K Screens for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-graphic-driver-conflicts-with-civilization-vi-game/"><u>Troubleshooting Graphic Driver Conflicts with Civilization VI Game</u></a></li>
</ul></div>

