---
title: Disrupting High CPU Usage in Windows 11
date: 2025-02-14T16:51:00.367Z
updated: 2025-02-16T16:58:32.742Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Disrupting High CPU Usage in Windows 11
excerpt: This Article Describes Disrupting High CPU Usage in Windows 11
thumbnail: https://thmb.techidaily.com/f5d1594082aca6452dbc25a49388a37fc7e84721f123ecd76572cb92530c4365.jpg
---

## Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Want us to fix the problem for you?

 If the fix above didn’t work, and you don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

 That’s it – top 3 fixes for your **MsMpEng.exe-eating-up-too-much-CPU-in-Windows 10** problem. Hope this helps and feel free to comment below if you have any further questions. 🙂

* [high CPU](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://desktop-recording.techidaily.com/new-the-art-of-capturing-scenes-ezvides-screencast-solution-for-2024/"><u>[New] The Art of Capturing Scenes EZvide's Screencast Solution for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-choosing-a-font-for-impactful-youtube-credits/"><u>[Updated] 2024 Approved Choosing a Font for Impactful YouTube Credits</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-straightforward-screen-capture-program/"><u>[Updated] In 2024, Straightforward Screen Capture Program</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-optimize-your-content-searchability-with-these-7-top-tier-youtube-tags-extractor-tools/"><u>2024 Approved Optimize Your Content Searchability with These 7 Top-Tier Youtube Tags Extractor Tools</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-tecno-phantom-v-fold-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/beating-the-windows-10-update-blues-cracking-code-0xc1900208-successfully/"><u>Beating the Windows 10 Update Blues: Cracking Code 0xC1900208 Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dell-laptop-keyboard-malfunction-heres-what-you-can-do/"><u>Dell Laptop Keyboard Malfunction? Here's What You Can Do</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722894446253-discover-the-ultimate-list-the-7-best-imessage-games-for-2econdaries/"><u>Discover the Ultimate List: The 7 Best iMessage Games for 2Econdaries</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-the-features-of-the-latest-amazon-fire-hd-8-gen-is-it-a-smart-choice-for-cost-conscious-consumers/"><u>Exploring the Features of the Latest Amazon Fire HD 8 Gen - Is It a Smart Choice for Cost-Conscious Consumers?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/handling-unexpected-computer-lock-ups-in-windows-10-a-comprehensive-tutorial/"><u>Handling Unexpected Computer Lock-Ups in Windows 10: A Comprehensive Tutorial</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-vivo-v27-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/instructions-to-prevent-unwanted-touchpad-input-in-windows-10-with-an-attached-mouse-device/"><u>Instructions to Prevent Unwanted Touchpad Input in Windows 10 with an Attached Mouse Device</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/japans-linguistic-gateway-free-online-tools-for-self-learning/"><u>Japan's Linguistic Gateway: Free Online Tools for Self-Learning</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revitalizing-your-pc-top-techniques-for-fixing-windows-11-with-sfc-and-dism/"><u>Revitalizing Your PC: Top Techniques for Fixing Windows 11 with SFC & DISM</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-correct-user-profile-service-failures-in-windows/"><u>Step-by-Step Guide to Correct User Profile Service Failures in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-to-oppo-find-x7-ultra-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Oppo Find X7 Ultra Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win-howtos.techidaily.com/triumph-over-installation-troubles-how-to-successfully-upgrade-with-windows-10-despite-error-code-80240020/"><u>Triumph Over Installation Troubles: How to Successfully Upgrade with Windows 10, Despite Error Code 80240020</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unraveling-the-puzzle-effective-ways-to-address-google-chrome-black-screen-troubles/"><u>Unraveling The Puzzle - Effective Ways to Address Google Chrome Black Screen Troubles</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win-11-audio-troubleshooting-and-solution/"><u>Win 11 Audio: Troubleshooting and Solution</u></a></li>
</ul></div>

