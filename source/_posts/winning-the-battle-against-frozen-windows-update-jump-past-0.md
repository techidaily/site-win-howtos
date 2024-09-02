---
title: "Winning the Battle Against Frozen Windows Update: Jump Past 0%%"
date: 2024-09-01T04:59:26.677Z
updated: 2024-09-02T04:59:26.677Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Winning the Battle Against Frozen Windows Update: Jump Past 0%%"
excerpt: "This Article Describes Winning the Battle Against Frozen Windows Update: Jump Past 0%%"
thumbnail: https://thmb.techidaily.com/ae8528ae334175808b74ac01fefc618d6dd771a5548956162285f37bc39ffc3e.jpeg
---

## Winning Against Windows Update Challenge: Solving Error 0X802n02e Successfully

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

 A lot of Windows 10 users have reported an error while trying to update their operating system. What usually happens is they fail to install their system updates, and an error code shows up on Windows Update that says “0x8024002e”.

 If this is also happening to you, you’re no doubt very frustrated. But the good news is you should be able to fix it quite easily. We’ve put together some suggestions to help you fix the problem. Here are a few things you can try:

1. **[Reset your Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
2. **[Modify your Windows Update setting in the registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Perform a clean boot](https://tools.techidaily.com/drivereasy/download/)**

## Fix 1: Reset your Windows Update components

 The Windows Update “0x8024002e” error code may occur because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this fixes your problem.

To reset these components:

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “cmd” in the Run box, then, on your keyboard, press the**Ctrl** ,**Shift** and**Enter** keys at the same time.

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-884.png)

3. If prompted, click**Yes** .
4. In Command Prompt, type the following lines of command and press**Enter** on your keyboard after typing each:

net stop bits
net stop wuauserv
net stop appidsvc
net stop cryptsvc

5. Type these lines of command and press**Enter** after typing each in Command Prompt:

ren %systemroot%\softwaredistribution softwaredistribution.old
ren %systemroot%\system32\catroot2 catroot2.old

6. In Command Prompt, type these commands and press**Enter** after each:

net start bits
net start wuauserv
net start appidsvc
net start cryptsvc

7. Try updating your system with Windows Update, and see if the 0x8024002e error is gone.

 If it is, then you’ve solved your problem. But if not, you may need to…

## Fix 2: Modify your Windows setting in the registry

 This issue can also be fixes by adjusting a Windows Update setting in the registry. Here is how:

 You may experience serious problems if you don’t modify your registry properly. So be careful for what you’re doing in registry. And in case anything goes wrong, you can back up your registry, which you’ll know how by going through the steps below.

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “regedit” in the Run box and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-905.png)
3. If prompted, click**Yes** .
4. On the Registry Editor, click**File** , then select**Export** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
6. Click**OK** .
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
11. Click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
16. Click**OK** and then click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
17. Check to see if the error occurs. If it doesn’t, repeat step**13 to 16**  until you find out the startup item that causes the issue.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
 If there’s any startup item that causes the 0x8024002e error, you should see what program is this item related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.

 Hopefully one of the fixes above helped you fix your 0x8024002e error on Windows Update. If you have any questions or suggestions, you’re more than welcome to leave us a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-data.techidaily.com/024-approved-analyze-youtube-data-efficiently-with-social-blade-tools/"><u>[New] 2024 Approved  Analyze YouTube Data Efficiently with Social Blade Tools</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-elevating-presentations-with-adobe-captivate-skills/"><u>[New] Elevating Presentations with Adobe Captivate Skills</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-ultimate-capture-assistant-az-audits-and-alternatives-for-2024/"><u>[New] Ultimate Capture Assistant - AZ Audits & Alternatives for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-srt-conversion-compendium-for-media-professionals/"><u>[Updated] 2024 Approved  SRT Conversion Compendium for Media Professionals</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-unveiling-the-purpose-behind-facebooks-blue-emoji/"><u>[Updated] 2024 Approved  Unveiling the Purpose Behind Facebook's Blue Emoji</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-idea-to-airwaves-crafting-compelling-podcast-scripts/"><u>[Updated] From Idea to Airwaves  Crafting Compelling Podcast Scripts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-improving-visual-storytelling-with-secondary-shoots/"><u>[Updated] Improving Visual Storytelling with Secondary Shoots</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-unraveling-the-mystery-what-hides-in-snapchat-emoji-meanings-for-2024/"><u>[Updated] Unraveling the Mystery  What Hides in Snapchat Emoji Meanings for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-the-essence-of-earnings-a-3-step-expedient-to-measure-your-youtube-profitability/"><u>2024 Approved  The Essence of Earnings  A 3-Step Expedient to Measure Your YouTube Profitability</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/advanced-editing-shortcuts-learn-to-use-photoshops-history-for-effortless-artistry/"><u>Advanced Editing Shortcuts: Learn to Use Photoshop's History for Effortless Artistry</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clear-the-shadows-expert-tips-for-overcoming-black-screen-glitches-in-windows-11/"><u>Clear the Shadows: Expert Tips for Overcoming Black Screen Glitches in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/comprehensive-fixes-for-your-livekernelevent-complication-error-117/"><u>Comprehensive Fixes for Your LiveKernelEvent Complication: Error #117</u></a></li>
<li><a href="https://win-howtos.techidaily.com/criteria-for-choosing-windows-hello-friendly-camera/"><u>Criteria for Choosing Windows Hello-Friendly Camera</u></a></li>
<li><a href="https://win-howtos.techidaily.com/csgo-performance-boosters-how-to-overcome-connection-delays/"><u>CS:GO Performance Boosters: How To Overcome Connection Delays</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-a-broken-wacom-pen-connection-in-modern-windows-environments/"><u>Diagnosing and Fixing a Broken Wacom Pen Connection in Modern Windows Environments</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnosing-and-fixing-failed-installations-of-windows-10-version-1607-feature-update/"><u>Diagnosing and Fixing Failed Installations of Windows 10 Version 1607 Feature Update</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-eliminating-game-crashes-for-total-war-rome-remastered/"><u>Expert Advice on Eliminating Game Crashes for Total War: Rome Remastered</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-dark-launch-overcoming-initial-boot-issues-in-monster-hunter-world/"><u>Fixing the Dark Launch: Overcoming Initial Boot Issues in Monster Hunter: World</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211535017-getting-your-microphone-back-on-track-with-windows-11-quick-solutions/"><u>Getting Your Microphone Back on Track with Windows 11 - Quick Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723207148823-how-to-get-rid-of-the-infinite-loading-screen-in-valorant-once-and-for-all/"><u>How to Get Rid of the Infinite Loading Screen in Valorant Once and For All!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015733850-how-to-get-your-lucidsound-ls30-mic-up-and-running-again/"><u>How To Get Your LucidSound LS30 Mic Up and Running Again!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-recover-missing-desktop-icons-on-windows-10-fix-and-guide/"><u>How to Recover Missing Desktop Icons on Windows 10 (Fix & Guide)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-resolve-error-1603-critical-failure-in-software-setup-process/"><u>How to Resolve Error 1603: Critical Failure in Software Setup Process</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-a-step-by-step-approach-to-perfecting-vlog-soundtracks/"><u>In 2024, A Step-by-Step Approach to Perfecting Vlog Soundtracks</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-full-guide-to-bypass-motorola-edge-40-neo-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Motorola Edge 40 Neo FRP</u></a></li>
<li><a href="https://win-howtos.techidaily.com/journeys-end-fortnite-launching-successfully/"><u>Journey's End: Fortnite Launching Successfully</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-crisis-management-for-pcs-comprehensive-strategies-to-repair-windows-error-code-0xc00000e9/"><u>Mastering Crisis Management for PCs: Comprehensive Strategies to Repair Windows Error Code 0xC00000E9</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-fix-for-critical-freezes-a-simple-walkthrough-of-cxfreeze-recovery/"><u>Mastering the Fix for Critical Freezes - A Simple Walkthrough of Cx_Freeze Recovery</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-persistent-green-display-issues-in-windows-10-computers/"><u>Overcoming Persistent Green Display Issues in Windows 10 Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-system-lockups-expert-advice-for-defrosting-frozen-computers/"><u>Overcoming System Lockups: Expert Advice for Defrosting Frozen Computers</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/perfecting-bokeh-mastering-instagram-story-blur/"><u>Perfecting Bokeh  Mastering Instagram Story Blur</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-there-was-an-error-when-trying-to-reset-your-windows-10-pc-tips-and-solutions/"><u>Resolving There Was an Error When Trying to Reset Your Windows 10 PC – Tips & Solutions</u></a></li>
<li><a href="https://some-skills.techidaily.com/revolutionize-daily-routines-a-comprehensive-chatgpt-approach/"><u>Revolutionize Daily Routines: A Comprehensive ChatGPT Approach</u></a></li>
<li><a href="https://tech-haven.techidaily.com/scriptwriting-made-simple-boost-your-youtube-videos-with-chatgpt-insights/"><u>Scriptwriting Made Simple: Boost Your YouTube Videos with ChatGPT Insights</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-reducing-msmpengines-impact-on-your-pcn-windows-11-performance/"><u>Solution: Reducing MsMpEngine's Impact on Your PC'n Windows 11 Performance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-setting-up-bluetooth-on-windows-7-detailed-tutorial/"><u>Successfully Setting Up Bluetooth on Windows 7 - Detailed Tutorial</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-correcting-the-missing-entry-point-error-on-windows/"><u>Troubleshooting and Correcting the Missing Entry Point Error on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-repairing-system-error-5-has-occurred-in-windows-operating-systems-windows-10-7-and-8/"><u>Troubleshooting and Repairing 'System Error 5 Has Occurred' In Windows Operating Systems (Windows 10, 7 & 8)</u></a></li>
</ul></div>
