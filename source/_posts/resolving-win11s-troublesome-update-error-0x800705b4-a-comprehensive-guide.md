---
title: Resolving Win11's Troublesome Update Error (0X800705B4) - A Comprehensive Guide
date: 2024-09-05T10:00:22.190Z
updated: 2024-09-06T10:00:22.190Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Win11's Troublesome Update Error (0X800705B4) - A Comprehensive Guide
excerpt: This Article Describes Resolving Win11's Troublesome Update Error (0X800705B4) - A Comprehensive Guide
thumbnail: https://thmb.techidaily.com/28460332c706ced456fd18767c0466a64d105614a00c30d76ebc074f7652f887.jpg
---

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Comprehensive Guide: Resolve Windows Update Error 0X8024002E Once and For All

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115947/19272" target="_top" id="2115947">
  <img src="//a.impactradius-go.com/display-ad/19272-2115947" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123474/16836" target="_top" id="2123474">
  <img src="//a.impactradius-go.com/display-ad/16836-2123474" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123474/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137412/7443" target="_top" id="2137412">
  <img src="//a.impactradius-go.com/display-ad/7443-2137412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
<!-- affiliate ads begin -->
<span id="1770544">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770544.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770544">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770544.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770544%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770544/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
16. Click**OK** and then click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
17. Check to see if the error occurs. If it doesn’t, repeat step**13 to 16**  until you find out the startup item that causes the issue.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134237/18498" target="_top" id="2134237">
  <img src="//a.impactradius-go.com/display-ad/18498-2134237" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134237/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/n-2024-the-complete-guide-to-astonishing-lyric-videos-with-lyric-video-maker/"><u>[New] In 2024, The Complete Guide to Astonishing Lyric Videos with Lyric Video Maker</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-power-of-the-podium-mastering-audio-in-videography/"><u>[New] The Power of the Podium  Mastering Audio in Videography</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exceptional-online-tv-services-featuring-community-broadcasts/"><u>[Updated] Exceptional Online TV Services Featuring Community Broadcasts</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-saving-your-iphone-screen-a-step-by-step-approach/"><u>[Updated] In 2024, Saving Your iPhone Screen  A Step-by-Step Approach</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/android-call-history-recovery-recover-deleted-call-logs-from-v30-by-fonelab-android-recover-call-logs/"><u>Android Call History Recovery - recover deleted call logs from V30</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-solutions-for-resolving-unintended-keystrokes-and-typos/"><u>Easy Solutions for Resolving Unintended Keystrokes and Typos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-solving-sims-4-error-when-attempting-to-start/"><u>Expert Advice: Solving Sims 4 Error When Attempting to Start</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-strategies-for-addressing-file-non-existence-errors-in-technology-setups/"><u>Expert Strategies for Addressing File Non-Existence Errors in Technology Setups</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211723813-expert-tips-master-the-art-of-restarting-your-malfunctioning-keyboard/"><u>Expert Tips: Master the Art of Restarting Your Malfunctioning Keyboard!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-error-0xc1-for-a-smooth-windows-11-upgrade-experience-solved/"><u>Fixing the Error 0Xc1# for a Smooth Windows 11 Upgrade Experience [SOLVED]</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-can-life360-track-you-when-your-itel-p55plus-is-off-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track You When Your Itel P55+ is off? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-did-your-iphone-8-plus-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>In 2024, Did Your iPhone 8 Plus Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, How Do I Stop Someone From Tracking My Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-which-is-better-video-editor-for-iphone-cameo-or-filmorago/"><u>In 2024, Which Is Better Video Editor for iPhone? Cameo or FilmoraGo?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/instant-troubleshooting-techniques-dealing-with-projector-does-not-recognize-computer-on-a-windows-system/"><u>Instant Troubleshooting Techniques: Dealing with 'Projector Does Not Recognize Computer' On a Windows System</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/leveraging-zoom-tools-to-capture-effective-sessions/"><u>Leveraging Zoom Tools to Capture Effective Sessions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/managing-elevation-requests-for-operations-in-win-11-and-earlier-versions/"><u>Managing Elevation Requests for Operations in Win 11 and Earlier Versions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-resolve-the-window-update-freeze-at-0-problem/"><u>Quick Solutions: Resolve the Window Update Freeze at 0%% Problem</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolution-tips-reactivating-tablet-interactivity-post-display-issues/"><u>Resolution Tips: Reactivating Tablet Interactivity Post-Display Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-overcoming-xerox-update-problem-0x800f020b-on-windows/"><u>Step-by-Step Guide: Overcoming Xerox Update Problem 0X800f020b on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-reinstating-touchscreen-and-stylus-use-for-your-screen/"><u>Step-by-Step Guide: Reinstating Touchscreen & Stylus Use for Your Screen</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solution-overcoming-the-non-playable-sources-issue-on-windows-pcs/"><u>Step-by-Step Solution: Overcoming the Non-Playable Sources Issue on Windows PCs</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-to-prevent-total-war-rome-remastered-from-crashing-on-your-pc/"><u>Step-by-Step Solutions to Prevent Total War: Rome Remastered From Crashing on Your PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/streamline-your-kodi-experience-by-fixing-persistent-buffer-issues/"><u>Streamline Your Kodi Experience by Fixing Persistent Buffer Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/thwarting-the-crash-in-windows-11-life/"><u>Thwarting the 'Crash' In Windows 11 Life</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-8-solutions-resolving-microsofts-windows-10-update-error-0x800f0922/"><u>Top 8 Solutions: Resolving Microsoft's Windows 10 Update Error 0X800F0922</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-and-fixing-the-problem-detected-when-rebooting-error-on-windows-11/"><u>Troubleshooting and Fixing the 'Problem Detected When Rebooting' Error on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/uncomplicated-methods-to-tackle-your-computers-second-screen-projection-difficulty/"><u>Uncomplicated Methods to Tackle Your Computer's Second Screen Projection Difficulty</u></a></li>
<li><a href="https://win-howtos.techidaily.com/unlocking-bluetooth-functionality-in-windows-1110-step-by-step-solutions-revealed/"><u>Unlocking Bluetooth Functionality in Windows 11/10: Step-by-Step Solutions Revealed</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-vivo-y78-5g-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Vivo Y78 5G Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-unresponsiveness-heres-what-you-can-do/"><u>Windows 10 Unresponsiveness? Here's What You Can Do!</u></a></li>
</ul></div>
