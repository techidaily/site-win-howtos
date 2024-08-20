---
title: "Troubleshooting Cod: Addressing and Correcting the WWII Game Bug (Error 4220)"
date: 2024-08-19T07:17:02.540Z
updated: 2024-08-20T07:17:02.540Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Cod: Addressing and Correcting the WWII Game Bug (Error 4220)"
excerpt: "This Article Describes Troubleshooting Cod: Addressing and Correcting the WWII Game Bug (Error 4220)"
thumbnail: https://thmb.techidaily.com/ce2c767b4ea66790422350863194f4cca1e1e1f1b31e78a51ee237f509439d21.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

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
<li><a href="https://vp-tips.techidaily.com/new-harnessing-power-how-to-use-phantoms-retro-vision/"><u>[New] Harnessing Power  How to Use Phantom's Retro Vision</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-vivo-y200e-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/a-comprehensive-fix-guide-to-restore-ethernet-networking-in-windows-10-and-7/"><u>A Comprehensive Fix Guide to Restore Ethernet Networking in Windows 10 & 7</u></a></li>
<li><a href="https://win-howtos.techidaily.com/banishing-crashes-in-overwatch-a-deep-dive-into-resource-retrieval-problems/"><u>Banishing Crashes in Overwatch: A Deep Dive Into Resource Retrieval Problems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/critical-update-overcoming-continuous-restart-issues-in-windows-10-systems/"><u>Critical Update: Overcoming Continuous Restart Issues in Windows 10 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decoding-error-code-0x80070643-a-step-by-step-guide-to-fixing-windows-updates-and-install-failures/"><u>Decoding Error Code 0X80070643: A Step-by-Step Guide to Fixing Windows Updates and Install Failures</u></a></li>
<li><a href="https://win-howtos.techidaily.com/detailed-steps-to-correctly-resolve-chrome-could-not-load-plugin-on-windows-10-machines/"><u>Detailed Steps to Correctly Resolve 'Chrome Could Not Load Plugin' On Windows 10 Machines</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/essential-9-video-calling-apps-android-and-ios-review/"><u>Essential 9 Video Calling Apps  Android & iOS Review</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-google-pixel-8-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-errconnectionrefused-with-pictures/"><u>Fix: ERR_CONNECTION_REFUSED [with Pictures]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-a-non-functional-mic-on-windows-10-a-step-by-step-guide/"><u>Fixing a Non-Functional Mic on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/forward-error-correction-fec/"><u>Forward Error Correction (FEC):</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-a-hanging-windows-11-system-expert-solutions/"><u>How To Fix a Hanging Windows 11 System: Expert Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-error-code-0x8024401c-when-updating-windows-tips-for-windows-11-users/"><u>How to Fix Error Code 0X8024401c When Updating Windows: Tips for Windows 11 Users</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-iphone-15-unavailable-issue-with-ease-by-drfone-ios/"><u>How To Fix iPhone 15 Unavailable Issue With Ease</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-vivo-x-fold-2-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Vivo X Fold 2 to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On OnePlus Ace 2V? | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-analysis-of-asus-rog-strix-xg27acs-unparalleled-precision-meets-dynamic-180hz-gameplay/"><u>In-Depth Analysis of Asus ROG Strix XG27ACS: Unparalleled Precision Meets Dynamic 180Hz Gameplay</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/leading-platforms-for-snagging-snapchat-soundtracks-for-2024/"><u>Leading Platforms for Snagging Snapchat Soundtracks for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-organization-strategies-for-handling-chatgpt-dialogues-with-folders/"><u>Mastering Organization: Strategies for Handling ChatGPT Dialogues with Folders</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigate-the-process-of-engaging-and-exiting-iphones-recovery-mode/"><u>Navigate the Process of Engaging and Exiting iPhone's Recovery Mode</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-error-0x887a0006-a-comprehensive-guide-to-a-quick-and-easy-solution/"><u>Overcoming Error 0X887A0006 - A Comprehensive Guide to a Quick and Easy Solution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-obs-blackout-eliminate-game-recording-screen-issues-today/"><u>Overcoming OBS Blackout: Eliminate Game Recording Screen Issues Today</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-tricks-to-restore-your-skype-video-connection-on-windows-11/"><u>Simple Tricks to Restore Your Skype Video Connection on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/spread-spectrum-techniques-improve-security-by-making-signals-resistant-to-interference-and-eavesdropping/"><u>Spread Spectrum Techniques Improve Security by Making Signals Resistant to Interference and Eavesdropping.</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-game-troubles-tackling-installation-and-updating-problems-efficiently/"><u>Steam Game Troubles: Tackling Installation & Updating Problems Efficiently</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-correcting-asus-webcam-malfunctions-and-blackouts-for-windows-10-users/"><u>Step-by-Step Guide to Correcting ASUS Webcam Malfunctions and Blackouts for Windows 10 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-to-fix-a-stuck-windows-11-installation-process/"><u>Step-by-Step Guide to Fix a Stuck Windows 11 Installation Process</u></a></li>
<li><a href="https://some-skills.techidaily.com/techniques-to-combat-unsteady-shot-dynamics-for-2024/"><u>Techniques to Combat Unsteady Shot Dynamics for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/teredos-quest-foiled-an-in-depth-look-at-their-qualifying-hurdles/"><u>Teredo's Quest Foiled: An In-Depth Look at Their Qualifying Hurdles</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-asus-rog-phone-7-ultimate-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Asus ROG Phone 7 Ultimate Phones</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-easy-anti-cheat-glitches-in-apex-legends-fixed/"><u>Troubleshooting Easy Anti-Cheat Glitches in Apex Legends - Fixed!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-overcome-cannot-access-device-path-in-windows/"><u>Troubleshooting Guide: Overcome 'Cannot Access Device Path in Windows'</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missing-binkw32dll-files-effectively/"><u>Troubleshooting Missing binkw32.dll Files Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-error-5-has-occurred-on-windows-systems-solutions-for-vista-to-windows-11-users/"><u>Troubleshooting the 'Error 5 Has Occurred' On Windows Systems: Solutions for Vista to Windows 11 Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/vr-vexation-computer-crashing-while-gaming/"><u>VR Vexation: Computer Crashing While Gaming</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209859177-why-isnt-the-classic-shortcut-key-combo-work-troubleshooting-steps-inside/"><u>Why Isn't the Classic Shortcut Key Combo Work? Troubleshooting Steps Inside</u></a></li>
<li><a href="https://tech-haven.techidaily.com/will-chatbots-undermine-se-keywords-strategy/"><u>Will Chatbots Undermine SE Keywords Strategy?</u></a></li>
</ul></div>
