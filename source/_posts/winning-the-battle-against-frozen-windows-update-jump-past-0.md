---
title: "Winning the Battle Against Frozen Windows Update: Jump Past 0%%"
date: 2024-09-05T10:00:17.491Z
updated: 2024-09-06T10:00:17.491Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115948/19272" target="_top" id="2115948">
  <img src="//a.impactradius-go.com/display-ad/19272-2115948" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115948/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Winning Against Windows Update Challenge: Solving Error 0X802n02e Successfully

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134502/19576" target="_top" id="2134502">
  <img src="//a.impactradius-go.com/display-ad/19576-2134502" border="0" alt="https://techidaily.com" width="672" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134502/19576" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115938/19272" target="_top" id="2115938">
  <img src="//a.impactradius-go.com/display-ad/19272-2115938" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115938/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click**OK** .
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
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
