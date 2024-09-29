---
title: Fixing System Restore Fails with Error Code 0X80070091 in Windows 10 - Solutions Inside
date: 2024-09-28T02:40:00.465Z
updated: 2024-09-28T16:41:11.675Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing System Restore Fails with Error Code 0X80070091 in Windows 10 - Solutions Inside
excerpt: This Article Describes Fixing System Restore Fails with Error Code 0X80070091 in Windows 10 - Solutions Inside
thumbnail: https://thmb.techidaily.com/e591b5728fa84d66a3323b91b4ed2e3f5b0efaa53a757d0b8f7bbc674ee0d976.jpg
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2006933/19272" target="_top" id="2006933">
  <img src="//a.impactradius-go.com/display-ad/19272-2006933" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959773/19272" target="_top" id="1959773">
  <img src="//a.impactradius-go.com/display-ad/19272-1959773" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959773/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135356/19272" target="_top" id="2135356">
  <img src="//a.impactradius-go.com/display-ad/19272-2135356" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135356/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-enhancing-switch-gaming-with-top-cards/"><u>[New] 2024 Approved Enhancing Switch Gaming with Top Cards</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-pretending-playfulness-making-mocks-and-laughs/"><u>[Updated] Pretending Playfulness Making Mocks and Laughs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-how-to-record-itunes-videos/"><u>2024 Approved How to Record iTunes Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-step-by-step-from-viral-tiktok-to-custom-phone-ringtones/"><u>2024 Approved Step-by-Step From Viral TikTok to Custom Phone Ringtones</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/easy-fixes-for-a-non-responsive-left-click-on-computer-mice/"><u>Easy Fixes for a Non-Responsive Left Click on Computer Mice</u></a></li>
<li><a href="https://win-howtos.techidaily.com/exploring-sfc-and-dism-tools-for-effective-windows-11-system-restoration/"><u>Exploring SFC & DISM Tools for Effective Windows 11 System Restoration</u></a></li>
<li><a href="https://facebook.techidaily.com/hacked-out-restore-your-social-media-secrets/"><u>Hacked Out! Restore Your Social Media Secrets</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-create-endless-video-on-iphone/"><u>How-To Create Endless Video on iPhone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-oppo-find-n3-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Oppo Find N3 Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209309001-livekernelevent-117-trouble-heres-how-you-can-fix-it/"><u>LiveKernelEvent 117 Trouble? Here's How You Can Fix It</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/master-your-conversations-gpt-plus-a-premium-plan-for-us-citizens-20mth/"><u>Master Your Conversations: GPT-Plus, a Premium Plan for US Citizens ($20/Mth)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastery-over-kernel32-faults/"><u>Mastery over Kernel32 Faults</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-the-issue-how-to-fix-an-unresponsive-google-chrome-instance/"><u>Resolving the Issue: How to Fix an Unresponsive Google Chrome Instance</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-for-malfunctioning-keys-preceding-user-logon/"><u>Solution for Malfunctioning Keys Preceding User Logon</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-repair-tips-for-lenovo-laptop-fn-key-defects-get-back-to-productivity/"><u>Step-by-Step Repair Tips for Lenovo Laptop FN Key Defects - Get Back to Productivity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-getting-microsoft-print-to-pdf-feature-up-and-running-on-windows-1011/"><u>Step-by-Step: Getting Microsoft Print to PDF Feature Up and Running on Windows 10/11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-no-hardware-recognized-when-installing-windows-7/"><u>Troubleshooting: No Hardware Recognized When Installing Windows 7</u></a></li>
</ul></div>

