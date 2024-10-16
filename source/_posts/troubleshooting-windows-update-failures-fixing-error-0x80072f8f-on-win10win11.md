---
title: Troubleshooting Windows Update Failures - Fixing Error 0X80072F8F on Win10/Win11
date: 2024-10-08T19:32:43.465Z
updated: 2024-10-16T03:15:21.388Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Windows Update Failures - Fixing Error 0X80072F8F on Win10/Win11
excerpt: This Article Describes Troubleshooting Windows Update Failures - Fixing Error 0X80072F8F on Win10/Win11
thumbnail: https://thmb.techidaily.com/6f6094ec46399b3ab308c1c10a0d303a8a2fe57d58887a0de4be9b5a76727ac2.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  
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
<a href="https://aligracehair.sjv.io/c/5597632/2047366/19272" target="_top" id="2047366">
  <img src="//a.impactradius-go.com/display-ad/19272-2047366" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118325/7443" target="_top" id="2118325">
  <img src="//a.impactradius-go.com/display-ad/7443-2118325" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118325/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-mental-gymnastics-at-the-best-puzzle-halls/"><u>[New] In 2024, Mental Gymnastics at the Best Puzzle Halls</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/becoming-a-master-of-instagrams-video-dialogue-dynamics-for-2024/"><u>Becoming a Master of Instagram's Video Dialogue Dynamics for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-successfully-fixing-windows-1nupdate-error-code-0x800f0922-for-seamless-operations/"><u>Guide: Successfully Fixing Windows 1nUpdate Error Code 0X800f0922 for Seamless Operations</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-the-soft-bricked-asus-rog-phone-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Asus ROG Phone 8? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-10t-5g-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Realme 10T 5G Phone without Google Account?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-perfecting-virtual-sessions-best-free-and-paid-zoom-transcribing-tools/"><u>In 2024, Perfecting Virtual Sessions Best Free & Paid Zoom Transcribing Tools</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-toms-gadgetry-hub-your-source-for-cutting-edge-hardware-reviews/"><u>Inside Tom's Gadgetry Hub: Your Source for Cutting-Edge Hardware Reviews</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-how-to-get-your-diagnostic-policy-service-running-again/"><u>Resolved: How to Get Your Diagnostic Policy Service Running Again</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-windows-10-continuous-restart-woes-with-simple-solutions/"><u>Solving Windows 10 Continuous Restart Woes with Simple Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successfully-pairing-microsoft-wireless-dock-on-a-windows-10-system-solutions-and-tips/"><u>Successfully Pairing Microsoft Wireless Dock on a Windows 10 System: Solutions and Tips</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-infinix-smart-8-pro-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Infinix Smart 8 Pro to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-step-by-step-how-to-fix-windows-11-store-error-code-0x80073cf9/"><u>Troubleshooting Step-by-Step: How to Fix Windows 11 Store Error Code 0X80073CF9</u></a></li>
<li><a href="https://win-howtos.techidaily.com/valorant-gaming-fixes-eliminate-screen-distortion-and-enjoy-seamless-play/"><u>Valorant Gaming Fixes: Eliminate Screen Distortion & Enjoy Seamless Play</u></a></li>
<li><a href="https://program-issues.techidaily.com/warriors-guide-to-debugging-call-of-duty-warzone-error-6328-strategies-for-2025-mastering-cod-warzone-error-resolution-defeat-dev-bug-6328-in-the-upcoming-y407/"><u>Warrior's Guide to Debugging Call of Duty: Warzone Error 6328 - Strategies for 202#5. Mastering Cod: Warzone Error Resolution - Defeat Dev Bug 6328 in the Upcoming Year!</u></a></li>
</ul></div>

