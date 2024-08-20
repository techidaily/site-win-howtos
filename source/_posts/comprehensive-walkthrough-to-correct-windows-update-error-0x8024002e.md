---
title: Comprehensive Walkthrough to Correct Windows Update Error [0X8024002E]
date: 2024-08-19T06:45:51.425Z
updated: 2024-08-20T06:45:51.425Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Comprehensive Walkthrough to Correct Windows Update Error [0X8024002E]
excerpt: This Article Describes Comprehensive Walkthrough to Correct Windows Update Error [0X8024002E]
thumbnail: https://thmb.techidaily.com/117606e709c16601f4ab8cc26b0c9a6396939e54d91fb29f5e3a869fe4c9b70a.jpg
---

## How to Fix Windows Update Error Code 0X8024002E Easily

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

 A lot of Windows 10 users have reported an error while trying to update their operating system. What usually happens is they fail to install their system updates, and an error code shows up on Windows Update that says “0x8024002e”.

 If this is also happening to you, you’re no doubt very frustrated. But the good news is you should be able to fix it quite easily. We’ve put together some suggestions to help you fix the problem. Here are a few things you can try:

1. **[Reset your Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
2. **[Modify your Windows Update setting in the registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Perform a clean boot](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .
7. Click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
16. Click**OK** and then click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
17. Check to see if the error occurs. If it doesn’t, repeat step**13 to 16**  until you find out the startup item that causes the issue.  
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
<li><a href="https://win-howtos.techidaily.com/fixed-copy-issue-on-windows-11/"><u>[FIXED] Copy Issue on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-windows-11-update-error-0x80070541/"><u>[Fixed] Windows 11 Update Error 0X80070541</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-crafting-immersive-video-experiences-using-captivate-for-2024/"><u>[New] Crafting Immersive Video Experiences Using Captivate for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-the-screen-recorder-showdown-experts-take-on-popular-tools/"><u>[New] In 2024, The Screen Recorder Showdown  Experts' Take on Popular Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-uncovering-true-reflection-in-distorted-facebook-video-for-2024/"><u>[New] Uncovering True Reflection in Distorted Facebook Video for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-asian-miniature-villages-in-creative-sphere-of-mc/"><u>[Updated] Asian Miniature Villages in Creative Sphere of MC</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-beware-the-allure-of-sham-youtube-audience/"><u>[Updated] In 2024, Beware the Allure of Sham YouTube Audience</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-snickerstreamer-share-your-wit-with-a-click/"><u>[Updated] SnickerStreamer  Share Your Wit with a Click</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-breakthrough-techniques-for-building-intricate-iphone-photo-collages/"><u>2024 Approved  Breakthrough Techniques for Building Intricate iPhone Photo Collages</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-the-use-of-telegram-in-a-step-by-step-approach/"><u>2024 Approved  Mastering the Use of Telegram in a Step-by-Step Approach</u></a></li>
<li><a href="https://extra-hints.techidaily.com/are-we-impressed-the-full-on-evaluation-of-inshot-app-for-2024/"><u>Are We Impressed? The Full-On Evaluation of InShot App for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bug-check-recovery-strategies-for-stable-system-operation/"><u>Bug Check Recovery Strategies for Stable System Operation</u></a></li>
<li><a href="https://extra-tips.techidaily.com/chromebook-zoom-excellence-must-know-strategies/"><u>Chromebook Zoom Excellence  Must-Know Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/clear-up-blurry-characters-on-windows-10-with-these-easy-fixes/"><u>Clear Up Blurry Characters on Windows 10 with These Easy Fixes</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>Detailed guide of ispoofer for pogo installation On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ver-top-10-flv-to-youtube-conversion-tools-for-2024/"><u>Discover Top 10 Flv-to-YouTube Conversion Tools for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-when-your-media-device-wont-connect-to-windows-system/"><u>Easy Fixes When Your Media Device Won’t Connect to Windows System</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-no-more-a-step-by-step-solution-for-windows-camera-error-code-0xa00f4292/"><u>Error No More: A Step-by-Step Solution for Windows Camera Error Code 0Xa00f4292</u></a></li>
<li><a href="https://win-howtos.techidaily.com/five-effective-methods-to-optimize-dwms-gpu-use-on-windows-11-and-10-systems/"><u>Five Effective Methods to Optimize DWM's GPU Use on Windows 11 and 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-unresponsive-google-chrome-issue-with-simple-relaunch-steps/"><u>Fix Unresponsive Google Chrome Issue with Simple Relaunch Steps</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-asus-usb20-webcam-issue-in-windows-11/"><u>Fixed ASUS USB2.0 Webcam Issue in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-why-copy-and-paste-doesnt-work-in-windows-11/"><u>Fixing the Issue: Why 'Copy & Paste' Doesn't Work in Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fortnite-not-launching-solved/"><u>Fortnite Not Launching [SOLVED]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-defeating-the-2erious-case-of-miracast-not-working-on-your-gadget/"><u>Guide to Defeating the 2Erious Case of Miracast Not Working on Your Gadget</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-error-1067-the-process-terminated-unexpectedly-in-windows-systems/"><u>How to Fix 'Error 1067: The Process Terminated Unexpectedly' In Windows Systems</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-hell-let-loose-continuous-crashes-on-your-computer/"><u>How to Fix Hell Let Loose Continuous Crashes on Your Computer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-semaphore-timeout-expiration-issue-error-0x80070079/"><u>How to Fix Semaphore Timeout Expiration Issue (Error 0X80#070079)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-get-dvd-files-running-again-in-windows-operating-system/"><u>How to Get DVD Files Running Again in Windows Operating System</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-apple-iphone-xs-max-without-anyone-knowing-drfone-by-drfone-virtual-ios/"><u>How To Leave a Life360 Group On Apple iPhone XS Max Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-record-audio-on-windows-11/"><u>How To Record Audio on Windows 11?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-t-mobile-apple-iphone-7-online-without-sim-card-by-drfone-ios/"><u>How to Unlock T-Mobile Apple iPhone 7 online without SIM Card?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-exploring-youtubes-regular-income-mechanism/"><u>In 2024, Exploring YouTube's Regular Income Mechanism</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-enter-the-ispoofer-discord-server-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>In 2024, How to enter the iSpoofer discord server On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-leading-7-video-streaming-apps-to-enhance-your-youtube-mobile-experience/"><u>In 2024, Leading 7 Video Streaming Apps to Enhance Your YouTube Mobile Experience</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-slicedmedia-studio/"><u>In 2024, SlicedMedia Studio</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-woes-be-gone-a-comprehensive-reset-guide-for-immediate-relief/"><u>Keyboard Woes Be Gone! A Comprehensive Reset Guide for Immediate Relief</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-motorola-moto-g84-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Motorola Moto G84 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/netflix-black-screen-issue-resolved-a-step-by-step-guide-for-uninterrupted-viewing/"><u>Netflix Black Screen Issue Resolved: A Step-by-Step Guide for Uninterrupted Viewing</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-complete-blackout-at-boot-sequence-for-monster-hunter-world-gamers/"><u>Resolving Complete Blackout at Boot Sequence for Monster Hunter World Gamers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-usb-mouse-issues-on-your-laptop-top-tips-and-tricks/"><u>Solve USB Mouse Issues on Your Laptop - Top Tips and Tricks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fixing-your-microphone-problems-in-windows-10/"><u>Step-by-Step Guide to Fixing Your Microphone Problems in Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-unfreezing-your-computers-mouse-control/"><u>Step-by-Step Solutions for Unfreezing Your Computer's Mouse Control</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-troubleshooting-unsticking-a-stuck-computer-mouse/"><u>Step-by-Step Troubleshooting: Unsticking a Stuck Computer Mouse</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-strategies-to-overcome-game-lag-in-fallout-4/"><u>Top Strategies to Overcome Game Lag in Fallout 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-resolve-user-profile-service-couldnt-log-in/"><u>Troubleshooting Guide: How to Resolve 'User Profile Service Couldn't Log In.'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-slow-keyboard-response-easy-remedies-and-tips/"><u>Troubleshooting Slow Keyboard Response: Easy Remedies & Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-unfreezing-a-stuck-computer-mouse-button/"><u>Troubleshooting Tips: Unfreezing a Stuck Computer Mouse Button</u></a></li>
<li><a href="https://youtube-web.techidaily.com/shing-creativity-mastering-the-art-of-360-degree-videography-for-youtube/"><u>Unleashing Creativity  Mastering the Art of 360-Degree Videography for YouTube</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlocking-full-picture-potential-on-instagram-the-ultimate-guide/"><u>Unlocking Full Picture Potential on Instagram: The Ultimate Guide</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-effortless-avi-video-editing-top-cutters-and-trimmers-for-any-device/"><u>Updated 2024 Approved Effortless AVI Video Editing Top Cutters and Trimmers for Any Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-your-usb-to-hdmi-link-isnt-working-fixes-and-tips/"><u>Why Your USB to HDMI Link Isn't Working: Fixes & Tips</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-11-replicating-text-fails/"><u>Windows 11: Replicating Text Fails</u></a></li>
</ul></div>
